# Changelog

## [1.0.5](https://github.com/ryanjpayne/fcs-action/compare/v5.0.1...v1.0.5) (2026-08-20)


### ⚠ BREAKING CHANGES

* support fcs cli release 4.0.0 ([#82](https://github.com/ryanjpayne/fcs-action/issues/82))
* support cli release 2.2.0 ([#71](https://github.com/ryanjpayne/fcs-action/issues/71))
* **api:** use csdownloads/combined/files-download/v2 endpoint and require Cloud Security Tools Download API scope
* Latest FCS CLI with Image Assessment ([#29](https://github.com/ryanjpayne/fcs-action/issues/29))

### Features

* add new policy_rule option and doc changes for newer cli version ([#26](https://github.com/ryanjpayne/fcs-action/issues/26)) ([64cf4ad](https://github.com/ryanjpayne/fcs-action/commit/64cf4ad954614cf7b674ef51ac9dcdc215c4aea9))
* add project_name parameter for IaC scans ([#54](https://github.com/ryanjpayne/fcs-action/issues/54)) ([bec18d8](https://github.com/ryanjpayne/fcs-action/commit/bec18d8efd67bc5c7d5cbff43b28b1f961e02d61)), closes [#35](https://github.com/ryanjpayne/fcs-action/issues/35)
* **api:** use csdownloads/combined/files-download/v2 endpoint ([#59](https://github.com/ryanjpayne/fcs-action/issues/59)) ([67aa979](https://github.com/ryanjpayne/fcs-action/commit/67aa979c9da5db36eeca53c6079e4bd34fc4ac78))
* initial commit containing first crack ([539230d](https://github.com/ryanjpayne/fcs-action/commit/539230d91b06ce1776d225d7b6e8dc50cc9b64f5))
* Latest FCS CLI with Image Assessment ([#29](https://github.com/ryanjpayne/fcs-action/issues/29)) ([82645d0](https://github.com/ryanjpayne/fcs-action/commit/82645d07dbb863638742b5991c2a47570bc810a8))
* support cli release 2.2.0 ([#71](https://github.com/ryanjpayne/fcs-action/issues/71)) ([4c5e939](https://github.com/ryanjpayne/fcs-action/commit/4c5e939fdfe0197fc89b894ae5ba988280fb3ce3))
* support fcs cli release 4.0.0 ([#82](https://github.com/ryanjpayne/fcs-action/issues/82)) ([ef0aef2](https://github.com/ryanjpayne/fcs-action/commit/ef0aef252afdddbd23674972962f69b6449d2bb6))


### Bug Fixes

* adds timeout support for image scan, cleans up docs, and ensure output path dir exists for iac ([#41](https://github.com/ryanjpayne/fcs-action/issues/41)) ([3f8c435](https://github.com/ryanjpayne/fcs-action/commit/3f8c435b6f8ccb6064e6f29ff54a877aca14ccaa))
* allow path and config to coexist ([#7](https://github.com/ryanjpayne/fcs-action/issues/7)) ([3147eaf](https://github.com/ryanjpayne/fcs-action/commit/3147eaf8c8953f4521d677d9fddcabcbdfa42b02))
* convert SARIF when output_path is a directory ([933a899](https://github.com/ryanjpayne/fcs-action/commit/933a8997a333cdc3860f639dc4e5e6dcc88c128d))
* enable GitHub severity levels for SARIF files ([#49](https://github.com/ryanjpayne/fcs-action/issues/49)) ([a17e7b3](https://github.com/ryanjpayne/fcs-action/commit/a17e7b39c96fec3f0892a5141a26fe2e24aeb4ed))
* fixing sarif informationuri issue temporarily ([#9](https://github.com/ryanjpayne/fcs-action/issues/9)) ([75e518f](https://github.com/ryanjpayne/fcs-action/commit/75e518ff7374d8eab95908b0a3811ac28806d049))
* handle output path filenames for IaC SARIF conversion and null fields in image scans ([#50](https://github.com/ryanjpayne/fcs-action/issues/50)) ([e6b3a9c](https://github.com/ryanjpayne/fcs-action/commit/e6b3a9c6b81820163d1566c48b5429b00c35ca69))
* improve GitHub Code Scanning severity and display ([#73](https://github.com/ryanjpayne/fcs-action/issues/73)) ([3ce3544](https://github.com/ryanjpayne/fcs-action/commit/3ce354478e9914935b28e0f0ae4ab62f10c673f2))
* pass falcon region to fcs_scan.sh ([#80](https://github.com/ryanjpayne/fcs-action/issues/80)) ([2ed452a](https://github.com/ryanjpayne/fcs-action/commit/2ed452a25fbd0b0990258c8c3facc42c6f9bf5ff))
* refactor and enhance existing content ([#3](https://github.com/ryanjpayne/fcs-action/issues/3)) ([e53ca70](https://github.com/ryanjpayne/fcs-action/commit/e53ca7084358ffdb4f5e2e676b0aa82dcc364cf7))
* rewrite .sarif output_path to .json for IaC scans ([407b841](https://github.com/ryanjpayne/fcs-action/commit/407b841f9309b3ef89d6c2227cb948735a31558b))
* sarif conversion ([#86](https://github.com/ryanjpayne/fcs-action/issues/86)) ([d2989fb](https://github.com/ryanjpayne/fcs-action/commit/d2989fb294879d287d20109c7d689ea81ca36b9c))
* strip \r from CLI output before parsing Results saved to file path ([a895e82](https://github.com/ryanjpayne/fcs-action/commit/a895e825df9b999bc5c3e39c86aa3bde080aa415))
* strip ANSI escape codes from CLI output before parsing file path ([1f442d6](https://github.com/ryanjpayne/fcs-action/commit/1f442d60d0ad7895d8862dc8283dcaf9fd825798))
* support 2.3.0 multi-arch image scan results ([#77](https://github.com/ryanjpayne/fcs-action/issues/77)) ([c891641](https://github.com/ryanjpayne/fcs-action/commit/c891641a27c3f143fe78329129dd4dff712fdd27))
* updated sarif to fix iac and uri concerns ([#31](https://github.com/ryanjpayne/fcs-action/issues/31)) ([6111f24](https://github.com/ryanjpayne/fcs-action/commit/6111f24173e6b06347c7551a6394665eade88dd5))
* use bin from container to fix permission issues ([#21](https://github.com/ryanjpayne/fcs-action/issues/21)) ([af3c6c1](https://github.com/ryanjpayne/fcs-action/commit/af3c6c1521fe352c1289cdced46211d9be5eee89))


### Miscellaneous

* add branding for actions.yml ([#14](https://github.com/ryanjpayne/fcs-action/issues/14)) ([ec5cf44](https://github.com/ryanjpayne/fcs-action/commit/ec5cf444a9e495d9b3637b93272bbeb424685574))
* bootstrap releases for path: . ([#4](https://github.com/ryanjpayne/fcs-action/issues/4)) ([a47640f](https://github.com/ryanjpayne/fcs-action/commit/a47640ffdd8b5a92c0df14e9572ed01771d22598))
* **main:** release 1.0.0 ([#6](https://github.com/ryanjpayne/fcs-action/issues/6)) ([82f6891](https://github.com/ryanjpayne/fcs-action/commit/82f6891460780f15f334ae7c9cc21707f13161df))
* **main:** release 1.0.1 ([#8](https://github.com/ryanjpayne/fcs-action/issues/8)) ([fb89930](https://github.com/ryanjpayne/fcs-action/commit/fb8993062f83a53b482930920e6c496008b75fdc))
* **main:** release 1.0.2 ([#10](https://github.com/ryanjpayne/fcs-action/issues/10)) ([808629b](https://github.com/ryanjpayne/fcs-action/commit/808629b6635a4f7138152b1046f9d707beef4e12))
* **main:** release 1.0.3 ([#15](https://github.com/ryanjpayne/fcs-action/issues/15)) ([1c9e39f](https://github.com/ryanjpayne/fcs-action/commit/1c9e39fb4eb209b878147e3200fe993eb412fff8))
* **main:** release 1.0.5 ([#18](https://github.com/ryanjpayne/fcs-action/issues/18)) ([4a40a33](https://github.com/ryanjpayne/fcs-action/commit/4a40a330629b2a7b4b5a4dcf1acfeddb26b42953))
* **main:** release 1.0.6 ([#22](https://github.com/ryanjpayne/fcs-action/issues/22)) ([951794b](https://github.com/ryanjpayne/fcs-action/commit/951794b9a397c3130ffcd6f37a69977c7d31db5a))
* **main:** release 1.1.0 ([#28](https://github.com/ryanjpayne/fcs-action/issues/28)) ([e58d364](https://github.com/ryanjpayne/fcs-action/commit/e58d364629a2cbbd7ae598c9bf5f98eac118cd54))
* **main:** release 2.0.0 ([d5b6210](https://github.com/ryanjpayne/fcs-action/commit/d5b6210b35b5ff521f6309bff61237172bbf08c6))
* **main:** release 2.0.1 ([#40](https://github.com/ryanjpayne/fcs-action/issues/40)) ([cc3e4f3](https://github.com/ryanjpayne/fcs-action/commit/cc3e4f351a3aa348ca4fd75d687f84d5a0853f7c))
* **main:** release 2.0.2 ([#42](https://github.com/ryanjpayne/fcs-action/issues/42)) ([15c45f4](https://github.com/ryanjpayne/fcs-action/commit/15c45f4b775fdb66a67c929cb63edd30e00dda9e))
* **main:** release 2.0.3 ([#53](https://github.com/ryanjpayne/fcs-action/issues/53)) ([5b14389](https://github.com/ryanjpayne/fcs-action/commit/5b14389017b1daf69ac159235e93164b1eefba8f))
* **main:** release 2.1.0 ([#56](https://github.com/ryanjpayne/fcs-action/issues/56)) ([f39ced5](https://github.com/ryanjpayne/fcs-action/commit/f39ced5abf1851ccab89fc470a1b78f53ae2318a))
* **main:** release 3.0.0 ([#61](https://github.com/ryanjpayne/fcs-action/issues/61)) ([71aa81f](https://github.com/ryanjpayne/fcs-action/commit/71aa81f05a997ff13f5bbd9e5781ba29dec9c599))
* **main:** release 4.0.0 ([#72](https://github.com/ryanjpayne/fcs-action/issues/72)) ([0e9d7bb](https://github.com/ryanjpayne/fcs-action/commit/0e9d7bba776ed4dc623f8d0c5f0888f36e090d90))
* **main:** release 4.0.1 ([#74](https://github.com/ryanjpayne/fcs-action/issues/74)) ([340a860](https://github.com/ryanjpayne/fcs-action/commit/340a86029db9fcb0287b5df183639f8d487dc206))
* **main:** release 4.0.2 ([#81](https://github.com/ryanjpayne/fcs-action/issues/81)) ([1acaef6](https://github.com/ryanjpayne/fcs-action/commit/1acaef68003b789af89c3beaf7ab8e0fcfcf925a))
* **main:** release 5.0.1 ([#84](https://github.com/ryanjpayne/fcs-action/issues/84)) ([69f76ec](https://github.com/ryanjpayne/fcs-action/commit/69f76ec06fa958bf4df2522604444209d78deb9b))
* minor updates ([22bda06](https://github.com/ryanjpayne/fcs-action/commit/22bda06ea32681c6896a9ad30ec776193411feac))
* release 1.0.3 ([223d540](https://github.com/ryanjpayne/fcs-action/commit/223d540d93b96cba622c4fbb3d55743f7b1d4ead))
* release 1.0.5 ([#17](https://github.com/ryanjpayne/fcs-action/issues/17)) ([62fdc91](https://github.com/ryanjpayne/fcs-action/commit/62fdc91bfb6a3291b338ffbe7a7aba4ca6793002))
* release-please manifest files ([f85683c](https://github.com/ryanjpayne/fcs-action/commit/f85683cee79a91355bfe96db22fbd36c068c0a3f))
* reset tf example file ([36b48a8](https://github.com/ryanjpayne/fcs-action/commit/36b48a8696bda63b6eef444b6b10643f0180179b))
* temp disable sarif upload until public ([#11](https://github.com/ryanjpayne/fcs-action/issues/11)) ([56fa829](https://github.com/ryanjpayne/fcs-action/commit/56fa82942889402c42ca8526dd1848b8a59be125))
* test file updates ([cc15c0c](https://github.com/ryanjpayne/fcs-action/commit/cc15c0cc7556dd64576ce3bbfc70e946b72b835a))
* update gitignore ([093d734](https://github.com/ryanjpayne/fcs-action/commit/093d734ff4b2f97dab6a59b8654448065227ab11))
* update release-please ([#5](https://github.com/ryanjpayne/fcs-action/issues/5)) ([6cb0147](https://github.com/ryanjpayne/fcs-action/commit/6cb0147aeb38ae84b87d2bb3e28640cf323f610e))

## [5.0.1](https://github.com/CrowdStrike/fcs-action/compare/v5.0.0...v5.0.1) (2026-08-10)


### Bug Fixes

* sarif conversion ([#86](https://github.com/CrowdStrike/fcs-action/issues/86)) ([d2989fb](https://github.com/CrowdStrike/fcs-action/commit/d2989fb294879d287d20109c7d689ea81ca36b9c))

## [4.0.2](https://github.com/CrowdStrike/fcs-action/compare/v4.0.1...v4.0.2) (2026-07-16)


### Bug Fixes

* pass falcon region to fcs_scan.sh ([#80](https://github.com/CrowdStrike/fcs-action/issues/80)) ([2ed452a](https://github.com/CrowdStrike/fcs-action/commit/2ed452a25fbd0b0990258c8c3facc42c6f9bf5ff))

## [4.0.1](https://github.com/CrowdStrike/fcs-action/compare/v4.0.0...v4.0.1) (2026-04-14)


### Bug Fixes

* improve GitHub Code Scanning severity and display ([#73](https://github.com/CrowdStrike/fcs-action/issues/73)) ([3ce3544](https://github.com/CrowdStrike/fcs-action/commit/3ce354478e9914935b28e0f0ae4ab62f10c673f2))
* support 2.3.0 multi-arch image scan results ([#77](https://github.com/CrowdStrike/fcs-action/issues/77)) ([c891641](https://github.com/CrowdStrike/fcs-action/commit/c891641a27c3f143fe78329129dd4dff712fdd27))

## [4.0.0](https://github.com/CrowdStrike/fcs-action/compare/v3.0.0...v4.0.0) (2026-02-26)


### ⚠ BREAKING CHANGES

* support cli release 2.2.0 ([#71](https://github.com/CrowdStrike/fcs-action/issues/71))

### Features

* support cli release 2.2.0 ([#71](https://github.com/CrowdStrike/fcs-action/issues/71)) ([4c5e939](https://github.com/CrowdStrike/fcs-action/commit/4c5e939fdfe0197fc89b894ae5ba988280fb3ce3))

## [3.0.0](https://github.com/crowdstrike/fcs-action/compare/v2.1.0...v3.0.0) (2025-12-17)


### ⚠ BREAKING CHANGES

* **api:** use csdownloads/combined/files-download/v2 endpoint and require Cloud Security Tools Download API scope

### Features

* **api:** use csdownloads/combined/files-download/v2 endpoint ([#59](https://github.com/crowdstrike/fcs-action/issues/59)) ([67aa979](https://github.com/crowdstrike/fcs-action/commit/67aa979c9da5db36eeca53c6079e4bd34fc4ac78))

## [2.1.0](https://github.com/crowdstrike/fcs-action/compare/v2.0.3...v2.1.0) (2025-12-03)


### Features

* add project_name parameter for IaC scans ([#54](https://github.com/crowdstrike/fcs-action/issues/54)) ([bec18d8](https://github.com/crowdstrike/fcs-action/commit/bec18d8efd67bc5c7d5cbff43b28b1f961e02d61)), closes [#35](https://github.com/crowdstrike/fcs-action/issues/35)


### Miscellaneous

* reset tf example file ([36b48a8](https://github.com/crowdstrike/fcs-action/commit/36b48a8696bda63b6eef444b6b10643f0180179b))
* test file updates ([cc15c0c](https://github.com/crowdstrike/fcs-action/commit/cc15c0cc7556dd64576ce3bbfc70e946b72b835a))

## [2.0.3](https://github.com/crowdstrike/fcs-action/compare/v2.0.2...v2.0.3) (2025-11-20)


### Bug Fixes

* enable GitHub severity levels for SARIF files ([#49](https://github.com/crowdstrike/fcs-action/issues/49)) ([a17e7b3](https://github.com/crowdstrike/fcs-action/commit/a17e7b39c96fec3f0892a5141a26fe2e24aeb4ed))
* handle output path filenames for IaC SARIF conversion and null fields in image scans ([#50](https://github.com/crowdstrike/fcs-action/issues/50)) ([e6b3a9c](https://github.com/crowdstrike/fcs-action/commit/e6b3a9c6b81820163d1566c48b5429b00c35ca69))


### Miscellaneous

* release-please manifest files ([f85683c](https://github.com/crowdstrike/fcs-action/commit/f85683cee79a91355bfe96db22fbd36c068c0a3f))
* update gitignore ([093d734](https://github.com/crowdstrike/fcs-action/commit/093d734ff4b2f97dab6a59b8654448065227ab11))

## [2.0.2](https://github.com/CrowdStrike/fcs-action/compare/v2.0.1...v2.0.2) (2025-09-12)


### Bug Fixes

* adds timeout support for image scan, cleans up docs, and ensure output path dir exists for iac ([#41](https://github.com/CrowdStrike/fcs-action/issues/41)) ([3f8c435](https://github.com/CrowdStrike/fcs-action/commit/3f8c435b6f8ccb6064e6f29ff54a877aca14ccaa))

## [2.0.1](https://github.com/CrowdStrike/fcs-action/compare/v2.0.0...v2.0.1) (2025-09-10)


### Miscellaneous

* minor updates ([22bda06](https://github.com/CrowdStrike/fcs-action/commit/22bda06ea32681c6896a9ad30ec776193411feac))

## [2.0.0](https://github.com/CrowdStrike/fcs-action/compare/v1.1.0...v2.0.0) (2025-08-15)


### ⚠ BREAKING CHANGES

* Latest FCS CLI with Image Assessment ([#29](https://github.com/CrowdStrike/fcs-action/issues/29))

### Features

* Latest FCS CLI with Image Assessment ([#29](https://github.com/CrowdStrike/fcs-action/issues/29)) ([82645d0](https://github.com/CrowdStrike/fcs-action/commit/82645d07dbb863638742b5991c2a47570bc810a8))


### Bug Fixes

* updated sarif to fix iac and uri concerns ([#31](https://github.com/CrowdStrike/fcs-action/issues/31)) ([6111f24](https://github.com/CrowdStrike/fcs-action/commit/6111f24173e6b06347c7551a6394665eade88dd5))

## [1.1.0](https://github.com/CrowdStrike/fcs-action/compare/v1.0.6...v1.1.0) (2025-05-16)


### Features

* add new policy_rule option and doc changes for newer cli version ([#26](https://github.com/CrowdStrike/fcs-action/issues/26)) ([64cf4ad](https://github.com/CrowdStrike/fcs-action/commit/64cf4ad954614cf7b674ef51ac9dcdc215c4aea9))

## [1.0.6](https://github.com/crowdstrike/fcs-action/compare/v1.0.5...v1.0.6) (2024-10-19)


### Bug Fixes

* use bin from container to fix permission issues ([#21](https://github.com/crowdstrike/fcs-action/issues/21)) ([af3c6c1](https://github.com/crowdstrike/fcs-action/commit/af3c6c1521fe352c1289cdced46211d9be5eee89))

## [1.0.5](https://github.com/crowdstrike/fcs-action/compare/v1.0.4...v1.0.5) (2024-08-26)


### Miscellaneous

* release 1.0.5 ([#17](https://github.com/crowdstrike/fcs-action/issues/17)) ([62fdc91](https://github.com/crowdstrike/fcs-action/commit/62fdc91bfb6a3291b338ffbe7a7aba4ca6793002))

## [1.0.4](https://github.com/crowdstrike/fcs-action/compare/v1.0.3...v1.0.4) (2024-08-26)

## [1.0.3](https://github.com/crowdstrike/fcs-action/compare/v1.0.2...v1.0.3) (2024-08-26)


### Miscellaneous

* add branding for actions.yml ([#14](https://github.com/crowdstrike/fcs-action/issues/14)) ([ec5cf44](https://github.com/crowdstrike/fcs-action/commit/ec5cf444a9e495d9b3637b93272bbeb424685574))
* release 1.0.3 ([223d540](https://github.com/crowdstrike/fcs-action/commit/223d540d93b96cba622c4fbb3d55743f7b1d4ead))

## [1.0.2](https://github.com/CrowdStrike/fcs-action/compare/v1.0.1...v1.0.2) (2024-08-13)


### Bug Fixes

* fixing sarif informationuri issue temporarily ([#9](https://github.com/CrowdStrike/fcs-action/issues/9)) ([75e518f](https://github.com/CrowdStrike/fcs-action/commit/75e518ff7374d8eab95908b0a3811ac28806d049))

## [1.0.1](https://github.com/crowdstrike/fcs-action/compare/v1.0.0...v1.0.1) (2024-07-12)


### Bug Fixes

* allow path and config to coexist ([#7](https://github.com/crowdstrike/fcs-action/issues/7)) ([3147eaf](https://github.com/crowdstrike/fcs-action/commit/3147eaf8c8953f4521d677d9fddcabcbdfa42b02))

## 1.0.0 (2024-07-12)


### Features

* initial commit containing first crack ([539230d](https://github.com/CrowdStrike/fcs-action/commit/539230d91b06ce1776d225d7b6e8dc50cc9b64f5))


### Bug Fixes

* refactor and enhance existing content ([#3](https://github.com/CrowdStrike/fcs-action/issues/3)) ([e53ca70](https://github.com/CrowdStrike/fcs-action/commit/e53ca7084358ffdb4f5e2e676b0aa82dcc364cf7))
