# Changelog

[npm history][1]

[1]: https://www.npmjs.com/package/@google-cloud/language?activeTab=versions

### [3.2.3](https://www.github.com/googleapis/nodejs-language/compare/v3.2.2...v3.2.3) (2019-06-26)


### Bug Fixes

* **docs:** link to reference docs section on googleapis.dev ([#267](https://www.github.com/googleapis/nodejs-language/issues/267)) ([d7d8440](https://www.github.com/googleapis/nodejs-language/commit/d7d8440))

### [3.2.2](https://www.github.com/googleapis/nodejs-language/compare/v3.2.1...v3.2.2) (2019-06-14)


### Bug Fixes

* **docs:** move to new client docs URL ([#263](https://www.github.com/googleapis/nodejs-language/issues/263)) ([7bbc8a2](https://www.github.com/googleapis/nodejs-language/commit/7bbc8a2))

### [3.2.1](https://www.github.com/googleapis/nodejs-language/compare/v3.2.0...v3.2.1) (2019-06-11)


### Bug Fixes

* **deps:** update dependency mathjs to v6 ([#261](https://www.github.com/googleapis/nodejs-language/issues/261)) ([eeb2847](https://www.github.com/googleapis/nodejs-language/commit/eeb2847))

## [3.2.0](https://www.github.com/googleapis/nodejs-language/compare/v3.1.0...v3.2.0) (2019-06-06)


### Features

* add .repo-metadata.json and generate README ([#255](https://www.github.com/googleapis/nodejs-language/issues/255)) ([0853696](https://www.github.com/googleapis/nodejs-language/commit/0853696))

## [3.1.0](https://www.github.com/googleapis/nodejs-language/compare/v3.0.0...v3.1.0) (2019-06-05)


### Features

* support apiEndpoint override in client constructor ([#256](https://www.github.com/googleapis/nodejs-language/issues/256)) ([48ac8fd](https://www.github.com/googleapis/nodejs-language/commit/48ac8fd))

## [3.0.0](https://www.github.com/googleapis/nodejs-language/compare/v2.1.0...v3.0.0) (2019-05-20)


### ⚠ BREAKING CHANGES

* upgrade engines field to >=8.10.0 (#232)

### Bug Fixes

* **deps:** update dependency @google-cloud/automl to ^0.2.0 ([#223](https://www.github.com/googleapis/nodejs-language/issues/223)) ([1fe903a](https://www.github.com/googleapis/nodejs-language/commit/1fe903a))
* DEADLINE_EXCEEDED error is no longer retried ([a32713f](https://www.github.com/googleapis/nodejs-language/commit/a32713f))
* DEADLINE_EXCEEDED is idempotent ([#241](https://www.github.com/googleapis/nodejs-language/issues/241)) ([dbd417f](https://www.github.com/googleapis/nodejs-language/commit/dbd417f))
* improve docstrings, and add more field validation ([#224](https://www.github.com/googleapis/nodejs-language/issues/224)) ([ed2c692](https://www.github.com/googleapis/nodejs-language/commit/ed2c692))
* **deps:** update dependency @google-cloud/automl to v1 ([#242](https://www.github.com/googleapis/nodejs-language/issues/242)) ([c7e4797](https://www.github.com/googleapis/nodejs-language/commit/c7e4797))
* **deps:** update dependency google-gax to ^0.26.0 ([#230](https://www.github.com/googleapis/nodejs-language/issues/230)) ([5b8af98](https://www.github.com/googleapis/nodejs-language/commit/5b8af98))
* **deps:** update dependency google-gax to v1 ([#240](https://www.github.com/googleapis/nodejs-language/issues/240)) ([54660e1](https://www.github.com/googleapis/nodejs-language/commit/54660e1))


### Build System

* upgrade engines field to >=8.10.0 ([#232](https://www.github.com/googleapis/nodejs-language/issues/232)) ([ec540f3](https://www.github.com/googleapis/nodejs-language/commit/ec540f3))

## v2.1.0

03-22-2019 10:34 PDT

### New Features
- feat: add additional entity types ([#220](https://github.com/googleapis/nodejs-language/pull/220))

### Internal / Testing Changes
- chore: publish to npm using wombat ([#218](https://github.com/googleapis/nodejs-language/pull/218))
- build: use per-repo npm publish token ([#216](https://github.com/googleapis/nodejs-language/pull/216))

## v2.0.2

03-14-2019 07:43 PDT

### Bug Fixes
- fix: throw on invalid credentials ([#204](https://github.com/googleapis/nodejs-language/pull/204))

### Documentation
- docs: update comments on protos ([#208](https://github.com/googleapis/nodejs-language/pull/208))
- docs: update links in contrib guide ([#206](https://github.com/googleapis/nodejs-language/pull/206))
- docs: update contributing path in README ([#200](https://github.com/googleapis/nodejs-language/pull/200))
- docs: move CONTRIBUTING.md to root ([#199](https://github.com/googleapis/nodejs-language/pull/199))
- docs: add lint/fix example to contributing guide ([#197](https://github.com/googleapis/nodejs-language/pull/197))

### Internal / Testing Changes
- chore: update require statement code style
- build: Add docuploader credentials to node publish jobs ([#211](https://github.com/googleapis/nodejs-language/pull/211))
- build: use node10 to run samples-test, system-test etc ([#210](https://github.com/googleapis/nodejs-language/pull/210))
- build: update release configuration
- chore(deps): update dependency mocha to v6 ([#207](https://github.com/googleapis/nodejs-language/pull/207))
- build: use linkinator for docs test ([#205](https://github.com/googleapis/nodejs-language/pull/205))
- fix(deps): update dependency yargs to v13 ([#203](https://github.com/googleapis/nodejs-language/pull/203))
- build: create docs test npm scripts ([#202](https://github.com/googleapis/nodejs-language/pull/202))
- build: test using @grpc/grpc-js in CI ([#201](https://github.com/googleapis/nodejs-language/pull/201))

## v2.0.1

01-31-2019 23:11 PST

### Implementation Changes
- refactor: reordered gRPC message types

### Dependencies
- fix(deps): update dependency google-gax to ^0.25.0 ([#195](https://github.com/googleapis/nodejs-language/pull/195))
- fix(deps): update dependency google-gax to ^0.24.0 ([#193](https://github.com/googleapis/nodejs-language/pull/193))
- fix(deps): update dependency google-gax to ^0.23.0 ([#189](https://github.com/googleapis/nodejs-language/pull/189))
- fix(deps): update dependency google-gax to ^0.22.0 ([#162](https://github.com/googleapis/nodejs-language/pull/162))

### Documentation
- docs: update the readme ([#172](https://github.com/googleapis/nodejs-language/pull/172))
- docs: update readme badges ([#171](https://github.com/googleapis/nodejs-language/pull/171))
- docs(samples): updated samples code to use async await ([#154](https://github.com/googleapis/nodejs-language/pull/154))
- Language Automl samples ([#126](https://github.com/googleapis/nodejs-language/pull/126))

### Internal / Testing Changes
- chore(deps): update dependency eslint-config-prettier to v4 ([#194](https://github.com/googleapis/nodejs-language/pull/194))
- build: ignore googleapis.com in doc link check ([#192](https://github.com/googleapis/nodejs-language/pull/192))
- chore: sync gapic files
- build: check broken links in generated docs ([#187](https://github.com/googleapis/nodejs-language/pull/187))
- refactor: modernize the sample tests ([#185](https://github.com/googleapis/nodejs-language/pull/185))
- chore(build): inject yoshi automation key ([#183](https://github.com/googleapis/nodejs-language/pull/183))
- chore: update nyc and eslint configs ([#182](https://github.com/googleapis/nodejs-language/pull/182))
- chore: fix publish.sh permission +x ([#180](https://github.com/googleapis/nodejs-language/pull/180))
- fix(build): fix Kokoro release script ([#179](https://github.com/googleapis/nodejs-language/pull/179))
- build: add Kokoro configs for autorelease ([#178](https://github.com/googleapis/nodejs-language/pull/178))
- chore: always nyc report before calling codecov ([#175](https://github.com/googleapis/nodejs-language/pull/175))
- chore: nyc ignore build/test by default ([#174](https://github.com/googleapis/nodejs-language/pull/174))
- fix(build): fix system key decryption ([#169](https://github.com/googleapis/nodejs-language/pull/169))
- chore: add synth.metadata
- chore: update eslintignore config ([#161](https://github.com/googleapis/nodejs-language/pull/161))
- chore(deps): update @google-cloud/nodejs-repo-tools to v3 ([#160](https://github.com/googleapis/nodejs-language/pull/160))
- chore: udpate lint configs ([#158](https://github.com/googleapis/nodejs-language/pull/158))
- chore: drop contributors from multiple places ([#159](https://github.com/googleapis/nodejs-language/pull/159))
- chore: use latest npm on Windows ([#156](https://github.com/googleapis/nodejs-language/pull/156))
- chore: update CircleCI config ([#155](https://github.com/googleapis/nodejs-language/pull/155))
- chore: include build in eslintignore ([#151](https://github.com/googleapis/nodejs-language/pull/151))
- chore(deps): update dependency eslint-plugin-node to v8 ([#147](https://github.com/googleapis/nodejs-language/pull/147))
- chore: update issue templates ([#146](https://github.com/googleapis/nodejs-language/pull/146))
- chore: remove old issue template ([#144](https://github.com/googleapis/nodejs-language/pull/144))
- build: run tests on node11 ([#143](https://github.com/googleapis/nodejs-language/pull/143))
- chores(build): do not collect sponge.xml from windows builds ([#142](https://github.com/googleapis/nodejs-language/pull/142))
- chores(build): run codecov on continuous builds ([#141](https://github.com/googleapis/nodejs-language/pull/141))
- chore: update new issue template ([#140](https://github.com/googleapis/nodejs-language/pull/140))
- chore(deps): update dependency sinon to v7 ([#134](https://github.com/googleapis/nodejs-language/pull/134))
- build: fix codecov uploading on Kokoro ([#135](https://github.com/googleapis/nodejs-language/pull/135))
- Update kokoro config ([#132](https://github.com/googleapis/nodejs-language/pull/132))
- chore(deps): update dependency eslint-plugin-prettier to v3 ([#131](https://github.com/googleapis/nodejs-language/pull/131))

## v2.0.0

### Breaking changes
- fix: drop support for node.js 4.x and 9.x ([#73](https://github.com/googleapis/nodejs-language/pull/73))

### New Features

### Dependencies
- fix(deps): update dependency google-gax to ^0.20.0 ([#117](https://github.com/googleapis/nodejs-language/pull/117))
- fix(deps): update dependency google-gax to ^0.19.0 ([#103](https://github.com/googleapis/nodejs-language/pull/103))
- fix(deps): update dependency google-gax to ^0.18.0 ([#89](https://github.com/googleapis/nodejs-language/pull/89))
-  fix: update dependencies ([#57](https://github.com/googleapis/nodejs-language/pull/57))

### Documentation
- samples: updates all _file_gcs to _gcs ([#102](https://github.com/googleapis/nodejs-language/pull/102))
- samples: Language region tag update ([#101](https://github.com/googleapis/nodejs-language/pull/101))
- fix: update sample to use a long enough string for classify-text ([#97](https://github.com/googleapis/nodejs-language/pull/97))

### Internal / Testing Changes
- Update kokoro config ([#125](https://github.com/googleapis/nodejs-language/pull/125))
- test: remove appveyor config ([#124](https://github.com/googleapis/nodejs-language/pull/124))
- Update the CI config ([#123](https://github.com/googleapis/nodejs-language/pull/123))
- Enable prefer-const in the eslint config ([#121](https://github.com/googleapis/nodejs-language/pull/121))
- Enable no-var in eslint ([#120](https://github.com/googleapis/nodejs-language/pull/120))
- Use mocha for sample tests ([#119](https://github.com/googleapis/nodejs-language/pull/119))
- Switch to let/const ([#118](https://github.com/googleapis/nodejs-language/pull/118))
- Update CI config ([#115](https://github.com/googleapis/nodejs-language/pull/115))
- Update synth and storage ([#113](https://github.com/googleapis/nodejs-language/pull/113))
- Retry npm install in CI ([#112](https://github.com/googleapis/nodejs-language/pull/112))
- Update kokoro config ([#108](https://github.com/googleapis/nodejs-language/pull/108))
- Update kokoro config ([#107](https://github.com/googleapis/nodejs-language/pull/107))
- chore(deps): update dependency nyc to v13 ([#106](https://github.com/googleapis/nodejs-language/pull/106))
- Update the CI config ([#105](https://github.com/googleapis/nodejs-language/pull/105))
- chore: make the CircleCI config consistent
- chore(deps): update dependency eslint-config-prettier to v3 ([#98](https://github.com/googleapis/nodejs-language/pull/98))
- chore: do not use npm ci ([#96](https://github.com/googleapis/nodejs-language/pull/96))
- chore: ignore package-lock.json ([#93](https://github.com/googleapis/nodejs-language/pull/93))
- chore(deps): lock file maintenance ([#92](https://github.com/googleapis/nodejs-language/pull/92))
- chore: update renovate config ([#91](https://github.com/googleapis/nodejs-language/pull/91))
- remove that whitespace ([#90](https://github.com/googleapis/nodejs-language/pull/90))
- Update CircleCI config ([#88](https://github.com/googleapis/nodejs-language/pull/88))
- chore: add node templates to synth.py ([#84](https://github.com/googleapis/nodejs-language/pull/84))
- chore(deps): lock file maintenance ([#87](https://github.com/googleapis/nodejs-language/pull/87))
- chore: move mocha options to mocha.opts ([#85](https://github.com/googleapis/nodejs-language/pull/85))
- chore: require node 8 for samples ([#86](https://github.com/googleapis/nodejs-language/pull/86))
- chore(deps): lock file maintenance ([#83](https://github.com/googleapis/nodejs-language/pull/83))
- chore(deps): update dependency eslint-plugin-node to v7 ([#80](https://github.com/googleapis/nodejs-language/pull/80))
- test: use strictEqual in tests ([#81](https://github.com/googleapis/nodejs-language/pull/81))
- chore(deps): lock file maintenance ([#79](https://github.com/googleapis/nodejs-language/pull/79))
- chore(build): use `npm ci` instead of `npm install` ([#76](https://github.com/googleapis/nodejs-language/pull/76))
- chore(deps): lock file maintenance ([#75](https://github.com/googleapis/nodejs-language/pull/75))
- chore(deps): lock file maintenance ([#74](https://github.com/googleapis/nodejs-language/pull/74))
- chore(deps): lock file maintenance ([#72](https://github.com/googleapis/nodejs-language/pull/72))
- chore(deps): lock file maintenance ([#71](https://github.com/googleapis/nodejs-language/pull/71))
- chore(deps): lock file maintenance ([#70](https://github.com/googleapis/nodejs-language/pull/70))
- chore(deps): lock file maintenance ([#69](https://github.com/googleapis/nodejs-language/pull/69))
- fix(deps): update dependency yargs to v12 ([#68](https://github.com/googleapis/nodejs-language/pull/68))
- update google-gax and add synth.py ([#64](https://github.com/googleapis/nodejs-language/pull/64))
- chore(deps): update dependency sinon to v6.0.1 ([#65](https://github.com/googleapis/nodejs-language/pull/65))
- Configure Renovate ([#58](https://github.com/googleapis/nodejs-language/pull/58))
- refactor: drop repo-tool as an exec wrapper ([#62](https://github.com/googleapis/nodejs-language/pull/62))
- chore: update sample lockfiles ([#61](https://github.com/googleapis/nodejs-language/pull/61))
- fix: update linking for samples ([#60](https://github.com/googleapis/nodejs-language/pull/60))
- chore(package): update eslint to version 5.0.0 ([#59](https://github.com/googleapis/nodejs-language/pull/59))
- chore(package): update nyc to version 12.0.2 ([#55](https://github.com/googleapis/nodejs-language/pull/55))
- chore: lock files maintenance ([#53](https://github.com/googleapis/nodejs-language/pull/53))
- chore: timeout for system test ([#51](https://github.com/googleapis/nodejs-language/pull/51))
- chore: lock files maintenance ([#50](https://github.com/googleapis/nodejs-language/pull/50))
- chore: test on node10 ([#49](https://github.com/googleapis/nodejs-language/pull/49))
- chore: lock files maintenance ([#48](https://github.com/googleapis/nodejs-language/pull/48))
- chore: one more workaround for repo-tools EPERM ([#46](https://github.com/googleapis/nodejs-language/pull/46))
- chore: workaround for repo-tools EPERM ([#45](https://github.com/googleapis/nodejs-language/pull/45))
- chore: make samples depend on the current version ([#44](https://github.com/googleapis/nodejs-language/pull/44))
- chore: setup nighty build in CircleCI ([#43](https://github.com/googleapis/nodejs-language/pull/43))
