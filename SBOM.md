# Source SBOM

**Initial source snapshot, not a release report.** Source commit `c2a0f18ce028a4cced582567a73d57f0d03cd00f` predates the tooling commit. Future release reports use exact published tags.

Source repository inventory only; completeness is UNKNOWN. Syft inventories tracked source/package manifests. Gitlinks and declared vendored/model evidence are inspected at immutable pins. CMake declarations are conditional requirements, not resolved installations. This is NOT proof of operating-system packages, static-link closure, build-time resolution, or the contents of release binaries.

Generation: **success**

## Source identity

wave-owl/aprs-python `c2a0f18ce028a4cced582567a73d57f0d03cd00f`

- sbom:role: source-root
- sbom:git-commit: c2a0f18ce028a4cced582567a73d57f0d03cd00f
- sbom:git-tree: d7b3858fdda65d253ee9692129e28be9b5824f22
- sbom:source-repository: https://github.com/wave-owl/aprs-python
- sbom:release-tags: []
- sbom:license-evidence: [{"path": "LICENSE", "sha256": "8177f97513213526df2cf6184d8ff986c675afb514d4e68a404010521b880643"}]
- sbom:license-resolution: unresolved; manual review required

## Generation errors

None.

## Components and unresolved licenses

| Component | Version | Role | License |
| --- | --- | --- | --- |
| wave-owl/aprs-python | c2a0f18ce028a4cced582567a73d57f0d03cd00f | source-root | unresolved; manual review required |
| Conditional source requirements declared by Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by docs/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by setup.py | unresolved | conditional-build-runtime-requirement | unresolved |
| setup.py install_requires=[] | unresolved | conditional-build-runtime-requirement | unresolved |
| dev_requirements.txt and docs requirements are build/test-only | unresolved | conditional-build-runtime-requirement | unresolved |
| actions/checkout | v2 | Syft source/package discovery | unresolved |
| actions/setup-python | v2 | Syft source/package discovery | unresolved |
| /Users/gerolfziegenhain/src/wave-owl/local/sbom-upstream-results/aprs-python/.source-input/.github/workflows/testing.yml | unresolved | Syft source/package discovery | unresolved |

License evidence paths/hashes, source manifests, model hashes and conditional
CMake declarations are recorded in SBOM.cdx.json. Declared upstream pins do not
prove vendored equivalence. No dependency installation or build was performed.
