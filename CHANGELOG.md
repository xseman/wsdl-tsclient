# Changelog

All notable changes to this project will be documented in this file.

## [1.8.0](https://github.com/xseman/wsdl-tsclient/compare/v1.7.1...v1.8.0) (2024-08-12)


### Features

* add esm option ([bde0490](https://github.com/xseman/wsdl-tsclient/commit/bde049045da8493945f62d373b11c8ca8643e6c6))
* **cli:** add option for modelPropertyNaming ([8670d29](https://github.com/xseman/wsdl-tsclient/commit/8670d29a8f98815a74d442595b7d7d3ebdb5388c))
* eslint fixes plus other minor improvements ([c530e61](https://github.com/xseman/wsdl-tsclient/commit/c530e61a22f56b6f4e505893189f2a6467f32975))


### Bug Fixes

* Add Typescript declearation ([d6cc3c9](https://github.com/xseman/wsdl-tsclient/commit/d6cc3c9cbcb3a8ec1ec1991982faa44de963814c))
* No reference to built files ([4343968](https://github.com/xseman/wsdl-tsclient/commit/43439685e040769f0451a291647ea7bb22a7a870))
* update esm generator ([7b78863](https://github.com/xseman/wsdl-tsclient/commit/7b78863dd090db2e14659fa5e503112518eccbfe))
* wire --esm cli flag to options ([3fd9a16](https://github.com/xseman/wsdl-tsclient/commit/3fd9a167e8119cbcd4657c21c063b78e02db4bdf))


### Dependency updates

* update ([5a6deb6](https://github.com/xseman/wsdl-tsclient/commit/5a6deb6d6bfa01243ac7f8e49386070d994ca7c8))
* update 2 ([9190a04](https://github.com/xseman/wsdl-tsclient/commit/9190a046b51ad965ec71e8a973aa53271b2f7585))
* update 3 ([2ea3280](https://github.com/xseman/wsdl-tsclient/commit/2ea32800307e098cfe7fc3c81d22442d06761e9d))


### Documentation

* mention 1.7.0 in changelog ([5058989](https://github.com/xseman/wsdl-tsclient/commit/50589893cc4dc08b759ff0f90cce43fdea240542))
* release 1.5.0 ([9d870a6](https://github.com/xseman/wsdl-tsclient/commit/9d870a6f66fdd1f452c4c785b9acee4ef9c8e736))
* update ([f4f244f](https://github.com/xseman/wsdl-tsclient/commit/f4f244f035f5f5ecd954f19ac05820645a619aca))
* update CLI options ([1ee5bc0](https://github.com/xseman/wsdl-tsclient/commit/1ee5bc052042978a46a6b9dc9629467be787872c))


### Maintenance

* add missing 1.6.0 changelog ([ab482ef](https://github.com/xseman/wsdl-tsclient/commit/ab482efd03b63f502712a42f5fd054a53d972ba0))
* add release please with provenance ([49dc863](https://github.com/xseman/wsdl-tsclient/commit/49dc86324cd946a07250334292e94f41ba355333))
* inline variable ([34ab146](https://github.com/xseman/wsdl-tsclient/commit/34ab1466d28288727c3daeff55f1b88f617207a2))
* move @types/yargs-parser to devDeps ([56dadd8](https://github.com/xseman/wsdl-tsclient/commit/56dadd8deee4a34dbb1f5e1116880350412639be))
* remove todo ([3ce445d](https://github.com/xseman/wsdl-tsclient/commit/3ce445d84200b988addf1e4a7efec937e05b6a75))
* remove travisci ([59757f0](https://github.com/xseman/wsdl-tsclient/commit/59757f027999f8766f2217b6e78fc2350c1df39a))
* remove travisci badge ([b3341ee](https://github.com/xseman/wsdl-tsclient/commit/b3341ee08340cb464296e26eafc847a04cc14fbc))
* update args desc ([bdd3e51](https://github.com/xseman/wsdl-tsclient/commit/bdd3e51836ab5dc24acc1243d3b6ae3bce639d8c))
* update release ([ac61d24](https://github.com/xseman/wsdl-tsclient/commit/ac61d245b4ee9dd076732ea46e89a4d1e1aad5c2))
* update setup-node ([60758af](https://github.com/xseman/wsdl-tsclient/commit/60758af3695ae04c34410c073ba6fdc7e0d858a3))


### Tests

* 2 ([2fbde51](https://github.com/xseman/wsdl-tsclient/commit/2fbde51525e4e55ca95af18d2c3aeb3f31822be7))

## [1.7.0] - 2024-07-15

- [feat(cli): add option for modelPropertyNaming](https://github.com/dderevjanik/wsdl-tsclient/commit/8670d29a8f98815a74d442595b7d7d3ebdb5388c) `--modelPropertyNaming=` 

## [1.6.0] - 2024-07-02

- Fix for code generation types not matching what node-soap produces by @nahidakbar in https://github.com/dderevjanik/wsdl-tsclient/pull/54
- fix for insensitive names and use of prefix and suffix by @vekexasia in https://github.com/dderevjanik/wsdl-tsclient/pull/46
- Reduce constraints on "soap" version by @mike-marcacci in https://github.com/dderevjanik/wsdl-tsclient/pull/77
- Fix products test by @icholy in https://github.com/dderevjanik/wsdl-tsclient/pull/65
- Handle namespaced primitive types by @icholy in https://github.com/dderevjanik/wsdl-tsclient/pull/79
- ESlint fixes plus other minor improvements by @svandriel in https://github.com/dderevjanik/wsdl-tsclient/pull/82
- Fixed: Output message without nested element defaulted to request type by @svandriel in https://github.com/dderevjanik/wsdl-tsclient/pull/83
- Bugfix: move development-only dependencies to devDependencies by @svandriel in https://github.com/dderevjanik/wsdl-tsclient/pull/85
- Make tsc invocation (during tests) work on windows as well by @svandriel in https://github.com/dderevjanik/wsdl-tsclient/pull/88

## [1.5.0] - 2024-04-16

- Project: Update soap dependency to 1.0.0 [#73](https://github.com/dderevjanik/wsdl-tsclient/pull/73) by @taylorreece
- ParseAndGenerate: Add optional `options` parameter all methods by @ZimGil

## [1.4.0] - 2022-04-27

- Fix issue with self recursive WSDL types [#39](https://github.com/dderevjanik/wsdl-tsclient/pull/39) by @mtranter
- Fix issue with `quiet` option not working properly
- Project: Updated several npm packages
- Project: Added eslint
- Project: Added test for typechecking generated wsdl clients [#19](https://github.com/dderevjanik/wsdl-tsclient/pull/19)
- Project: Add more jsdoc to `parseAndGenerate` and `parsedWsdl`
- ParseAndGenerate: Support for `colors`, `verbose` and `queit` options (before it was only possible through CLI)
- Docs: Mention `basicAuth` in `README.md`

## [1.3.1] - 2021-07-01

- Project: Updated several npm packages
- Parser: Fixed issue while finding name for sub-definition, which has same name as parent definition, fixes [#16](https://github.com/dderevjanik/wsdl-tsclient/issues/16)
- Generator: Sanitize method, param and property names (e.g. names with `-`), fixes [#16](https://github.com/dderevjanik/wsdl-tsclient/issues/16) [#18](https://github.com/dderevjanik/wsdl-tsclient/issues/18)

## [1.2.0] - 2021-06-26

- CLI: Add option for `maxRecursiveDefinitionName`, default `64`
- CLI: Add option for `caseInsensitiveNames`, default `false`
- Parser: Warn user if recursive definition name exceed `32`
- Parser: Option for `caseInsensitiveNames`, fix [#12](https://github.com/dderevjanik/wsdl-tsclient/pull/12) by @jakethagle
- Generator: Fix incorrect case

## [1.1.4] - 2021-05-10

- Parser: Fix `sourceName` for definitions
- Parser: Add warn logs when parsing `ComplexType` as `any`
- Parser: Partial options for `parse` function
- Generator: Partial options for `generate` function
- More meaningful source code comments

## [1.1.3] - 2021-05-03

- Fix cyclic error when parsing `ComplexType`. Now generates `any` type
- Fix problem with duplicated imports (importing same definition for client/service/port)

## [1.1.2] - 2021-05-01

- Fix wrong generated callback result
- Parser: Improved message for cyclic errors
- Parser: Improved message for finding non-collision definition name

## [1.1.1] - 2021-04-20

- Fix wrong AsyncFunction return's type generation #10
- Fix Ports importing bad definition filename
- Fix generated Port's method names

## [1.1.0] - 2021-04-17

- Engine: Is possible to pass URL to WSDL (with `http://` or `https://` prefix)
- Generator: Fix problem with generating import paths on Windows
- Parser: Pefix `targetNSAlias` and `targetNamespace` with `@`
- Parser: Parse input/output with `parts` only
- Parser: Better error reports for cyclic error
- Parser: Add verbose logs for parsing Service,Port,Method and Definitons
- Project: Add tests for generating clients from wsdl and checking Definitions
- CLI: Reworked to support more `yargs` features
- CLI: Show number of errors occured
- CLI: Detect `NO_COLOR` and `DEBUG` environment variables

## [1.0.1] - 2021-03-21

- Engine: Reworked engine completely by separating `Parser` and `Generator` logic
- Engine: `targetNSAlias` and `targetNamespace` is included in defition jsdoc instead of properties
- Engine:  Generator now generates Client interface based on wsdl name to avoid namespace merging
- Engine:  Support color logs (green for info, red for errors)
- Engine: `Write` logs are printed before file is saved
- Engine: Support for `modelNamePrefix` and `modelNameSuffix`
- Parser: Sanitize definition names by striping reserved characters (e.g. `:`)
- Parser: Definition's jsdoc includes sourcename of definition
- Generator: Generates `index.ts` with all re-exported definitions, ports, services and client
- CLI: Fixed glob
- CLI: Generating client to `outputDir/{wsdlFilename}` directory
- CLI: `--quiet` flag for suppressing all logs
- CLI: `--verbose` flag for verbose logs
- CLI: `--no-color` flag for turning off colourful logs
- CLI: `--emitDefinitionsOnly` flag to generate only Defintions files (no Ports, Service nor Clients)
- CLI: `--modelNamePrefix` and `--modelNameSuffix`
- Project: Updated README  by adding section about how to use generated client

## [0.3.5] - 2021-03-10

- Project: Fix path to dist sources #8 by @cobraz

## [0.3.4] - 2021-03-10

- Fix problem with generated methods that includes javascript keywords as param names

## [0.3.3] - 2021-03-09

- Project: Add typescript declaration #3 by @cobraz

## [0.3.2] - 2021-03-04

- CLI: Add `version` and `help` params
- Project: Add MIT license
- Project: Add minimum node engine (base on node-soap)

## [0.3.1] - 2021-03-03

- CLI: Add support for glob pattern
- Generator: Add support for generating named client

## [0.2.0] - 2021-03-01

- Generator: Use camelcase for generating definitions, filenames and function params
- CLI: Replace `-i` with `WSDL`
