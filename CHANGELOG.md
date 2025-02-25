## v1.0.2 (2022-04-11)

#### :house: Internal

- [#4](https://github.com/emberjs/babel-plugin-ember-template-compilation/pull/4) Upgrading dependencies ([@ef4](https://github.com/ef4))

#### Committers: 1

- Edward Faulkner ([@ef4](https://github.com/ef4))

## v1.0.1 (2021-11-04)

#### :bug: Bug Fix

- [#1](https://github.com/emberjs/babel-plugin-ember-template-compilation/pull/1) Ensure babel.parse does not use top level babel config. ([@rwjblue](https://github.com/rwjblue))

#### :house: Internal

- [#2](https://github.com/emberjs/babel-plugin-ember-template-compilation/pull/2) Ensure `yarn.lock` is always in sync ([@rwjblue](https://github.com/rwjblue))

#### Committers: 1

- Robert Jackson ([@rwjblue](https://github.com/rwjblue))

## v5.3.0 (2021-04-12)

#### :rocket: Enhancement

- [#370](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/370) Allow passing getTemplateLocals function directly as an option ([@NullVoxPopuli](https://github.com/NullVoxPopuli))

#### :house: Internal

- [#378](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/378) Add test for reusing an import. ([@rwjblue](https://github.com/rwjblue))

#### Committers: 2

- Robert Jackson ([@rwjblue](https://github.com/rwjblue))
- [@NullVoxPopuli](https://github.com/NullVoxPopuli)

## v5.2.2 (2021-04-01)

#### :bug: Bug Fix

- [#377](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/377) Ensure preexisting imports work correctly ([@chadhietala](https://github.com/chadhietala))

#### Committers: 1

- Chad Hietala ([@chadhietala](https://github.com/chadhietala))

## v5.2.1 (2021-03-24)

#### :bug: Bug Fix

- [#368](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/368) Account for comments in preprocessor for proposals ([@pzuraq](https://github.com/pzuraq))

#### Committers: 1

- Chris Garrett ([@pzuraq](https://github.com/pzuraq))

## v5.2.0 (2021-03-24)

#### :rocket: Enhancement

- [#361](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/361) Add `preprocessEmbeddedTemplates` function ([@pzuraq](https://github.com/pzuraq))
- [#362](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/362) Allow usage of proposals to be used in arbitrary expression positions ([@pzuraq](https://github.com/pzuraq))

#### Committers: 1

- Chris Garrett ([@pzuraq](https://github.com/pzuraq))

## v5.1.0 (2021-03-23)

#### :rocket: Enhancement

- [#360](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/360) Add ability to parse scope function (allow strict mode templates to be more resilient to module cycles). ([@pzuraq](https://github.com/pzuraq))

#### :bug: Bug Fix

- [#359](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/359) Ensure locals are used instead of scope everywhere ([@pzuraq](https://github.com/pzuraq))

#### Committers: 1

- Chris Garrett ([@pzuraq](https://github.com/pzuraq))

## v5.0.0 (2021-03-17)

#### :boom: Breaking Change

- [#358](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/358) Rename `scope` to `locals` for strict mode transpilation ([@pzuraq](https://github.com/pzuraq))

#### :rocket: Enhancement

- [#358](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/358) Adds a `templateCompilerPath` option ([@pzuraq](https://github.com/pzuraq))

#### Committers: 1

- Chris Garrett ([@pzuraq](https://github.com/pzuraq))

## v4.4.6 (2021-03-17)

#### :bug: Bug Fix

- [#357](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/357) [BUGFIX] Use a unique identifier for each reference ([@pzuraq](https://github.com/pzuraq))

#### Committers: 1

- Chris Garrett ([@pzuraq](https://github.com/pzuraq))

## v4.4.5 (2021-03-12)

#### :bug: Bug Fix

- [#355](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/355) Avoid sharing list of previously added imports. ([@rwjblue](https://github.com/rwjblue))

#### Committers: 1

- Robert Jackson ([@rwjblue](https://github.com/rwjblue))

## v4.4.4 (2021-02-25)

#### :bug: Bug Fix

- [#349](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/349) Fix defaulting of `ensureModuleApiPolyfill` to true ([@jamescdavis](https://github.com/jamescdavis))

#### Committers: 1

- James C. Davis ([@jamescdavis](https://github.com/jamescdavis))

## v4.4.3 (2021-02-24)

#### :bug: Bug Fix

- [#348](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/348) Rename `strict` to `strictMode` ([@pzuraq](https://github.com/pzuraq))

#### Committers: 1

- Chris Garrett ([@pzuraq](https://github.com/pzuraq))

## v4.4.2 (2021-02-24)

#### :bug: Bug Fix

- [#347](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/347) Default `ensureModuleApiPolyfill` to true ([@pzuraq](https://github.com/pzuraq))

#### Committers: 1

- Chris Garrett ([@pzuraq](https://github.com/pzuraq))

## v4.4.1 (2021-02-24)

#### :bug: Bug Fix

- [#346](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/346) Ensure proposal syntaxes work with Ember module API polyfill ([@pzuraq](https://github.com/pzuraq))

#### Committers: 1

- Chris Garrett ([@pzuraq](https://github.com/pzuraq))

## v4.4.0 (2021-02-23)

#### :rocket: Enhancement

- [#339](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/339) Add `moduleOverrides` options ([@pzuraq](https://github.com/pzuraq))
- [#338](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/338) Refactor to use `createTemplateFactory` ([@pzuraq](https://github.com/pzuraq))
- [#336](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/336) Implements an option to support the template tag imports proposal ([@pzuraq](https://github.com/pzuraq))

#### Committers: 1

- Chris Garrett ([@pzuraq](https://github.com/pzuraq))

## v4.3.0 (2021-02-22)

#### :rocket: Enhancement

- [#335](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/335) Implements an option to support the template literal imports proposal ([@pzuraq](https://github.com/pzuraq))
- [#334](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/334) Add support for multiple imports ([@pzuraq](https://github.com/pzuraq))
- [#333](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/333) [FEAT] Add `shouldParseScope`, `disableTemplateTag`, `disableFunctionCall` options ([@pzuraq](https://github.com/pzuraq))
- [#332](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/332) Adds `useEmberModule` option ([@pzuraq](https://github.com/pzuraq))

#### Committers: 1

- Chris Garrett ([@pzuraq](https://github.com/pzuraq))

## v4.2.1 (2020-11-09)

#### :bug: Bug Fix

- [#297](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/297) Fix issues when using emoji in templates while transpiling for IE11 ([@rwjblue](https://github.com/rwjblue))

#### Committers: 1

- Robert Jackson ([@rwjblue](https://github.com/rwjblue))

## v4.2.0 (2020-08-10)

#### :rocket: Enhancement

- [#251](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/251) [FEAT] Adds isProduction flag ([@pzuraq](https://github.com/pzuraq))

#### Committers: 2

- Chris Garrett ([@pzuraq](https://github.com/pzuraq))
- Robert Jackson ([@rwjblue](https://github.com/rwjblue))

## v4.1.0 (2020-05-07)

#### :rocket: Enhancement / :bug: Fix

- [#216](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/216) Avoid assuming ember-template-compiler result is JSON ([@rwjblue](https://github.com/rwjblue))

#### Committers: 1

- Robert Jackson ([@rwjblue](https://github.com/rwjblue))

## v4.0.1 (2020-05-06)

#### :bug: Bug Fix

- [#215](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/215) Add support for hbs(`...`) ([@chancancode](https://github.com/chancancode))

#### Committers: 1

- Godfrey Chan ([@chancancode](https://github.com/chancancode))

## v4.0.0 (2020-05-06)

#### :boom: Breaking Change

- [#210](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/210) Drop Node 8 support. ([@rwjblue](https://github.com/rwjblue))

#### :house: Internal

- [#211](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/211) Update release automation dependencies and settings. ([@rwjblue](https://github.com/rwjblue))

#### Committers: 2

- Robert Jackson ([@rwjblue](https://github.com/rwjblue))
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)

## v3.1.0 (2020-05-06)

#### :rocket: Enhancement

- [#208](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/208) Add ability to transfer compilation errors into runtime. ([@rwjblue](https://github.com/rwjblue))

#### :house: Internal

- [#209](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/209) Add Node 14 to CI. ([@rwjblue](https://github.com/rwjblue))

#### Committers: 2

- Robert Jackson ([@rwjblue](https://github.com/rwjblue))
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)

## v3.0.1 (2019-12-11)

#### :bug: Bug Fix

- [#134](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/134) Ensure `*/` included in a template does break surrounding JS. ([@rwjblue](https://github.com/rwjblue))

#### Committers: 1

- Robert Jackson ([@rwjblue](https://github.com/rwjblue))

## v3.0.0 (2019-10-01)

- Released in order to avoid incompatibilities between ember-cli-htmlbars and ember-cli-htmlbars-inline-precompile. Contains no changes from prior version.

## v2.1.1 (2019-09-29)

#### :bug: Bug Fix

- [#104](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/104) Ensure JSON.stringify'ed value is valid for hbs() options. ([@rwjblue](https://github.com/rwjblue))

#### Committers: 1

- Robert Jackson ([@rwjblue](https://github.com/rwjblue))

## v2.1.0 (2019-09-09)

#### :rocket: Enhancement

- [#92](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/92) Allow named exports to be replaced. ([@rwjblue](https://github.com/rwjblue))

#### Committers: 2

- Robert Jackson ([@rwjblue](https://github.com/rwjblue))
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)

## v2.0.0 (2019-08-30)

#### :boom: Breaking Change

- [#77](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/77) Drop Node 6 and 11 support. ([@rwjblue](https://github.com/rwjblue))
- [#50](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/50) Drop support for Node 4 ([@Turbo87](https://github.com/Turbo87))

#### :rocket: Enhancement

- [#89](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/89) Add an inline comment with the original template. ([@rwjblue](https://github.com/rwjblue))
- [#75](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/75) Add ability to pass static options to transpilation. ([@rwjblue](https://github.com/rwjblue))
- [#42](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/42) Test templates from MU co-located tests ([@NullVoxPopuli](https://github.com/NullVoxPopuli))

#### :memo: Documentation

- [#86](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/86) Add requirements section to README. ([@rwjblue](https://github.com/rwjblue))
- [#83](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/83) Revamp README. ([@rwjblue](https://github.com/rwjblue))

#### :house: Internal

- [#87](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/87) Update the test harness to use Babel 7. ([@rwjblue](https://github.com/rwjblue))
- [#85](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/85) Migrate to building AST nodes instead of replacing with source. ([@rwjblue](https://github.com/rwjblue))
- [#84](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/84) Add release-it setup. ([@rwjblue](https://github.com/rwjblue))
- [#79](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/79) Remove unused code for support MU. ([@rwjblue](https://github.com/rwjblue))
- [#76](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/76) Migrate to GH Actions. ([@rwjblue](https://github.com/rwjblue))
- [#57](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/57) TravisCI: Remove deprecated `sudo: false` option ([@Turbo87](https://github.com/Turbo87))
- [#40](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/40) nit: ensure concise functions are used consistently ([@stefanpenner](https://github.com/stefanpenner))

#### Committers: 5

- L. Preston Sego III ([@NullVoxPopuli](https://github.com/NullVoxPopuli))
- Robert Jackson ([@rwjblue](https://github.com/rwjblue))
- Stefan Penner ([@stefanpenner](https://github.com/stefanpenner))
- Tobias Bieniek ([@Turbo87](https://github.com/Turbo87))
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)

## [v0.2.5](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/tree/v0.2.5) (2018-06-02)

[Full Changelog](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/compare/v0.2.4...v0.2.5)

**Implemented enhancements:**

- Pass through `content` to `precompile`. [\#37](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/37) ([rwjblue](https://github.com/rwjblue))

**Merged pull requests:**

- Update jest-runner-eslint to the latest version 🚀 [\#35](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/35) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))
- Update jest-runner-eslint to the latest version 🚀 [\#34](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/34) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))
- Use Jest to run ESLint checks [\#32](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/32) ([Turbo87](https://github.com/Turbo87))
- Cleanup TravisCI config [\#31](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/31) ([Turbo87](https://github.com/Turbo87))

## [v0.2.4](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/tree/v0.2.4) (2018-03-22)

[Full Changelog](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/compare/v0.1.1...v0.2.4)

**Implemented enhancements:**

- Allow `modulePaths` configuration [\#30](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/30) ([Turbo87](https://github.com/Turbo87))

**Merged pull requests:**

- Replace `mocha` with `jest` [\#29](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/29) ([Turbo87](https://github.com/Turbo87))
- Update `yarn.lock` file [\#28](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/28) ([Turbo87](https://github.com/Turbo87))
- Update mocha to the latest version 🚀 [\#27](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/27) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))
- Update mocha to the latest version 🚀 [\#26](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/26) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))

## [v0.1.1](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/tree/v0.1.1) (2017-07-21)

[Full Changelog](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/compare/v0.2.3...v0.1.1)

**Implemented enhancements:**

- CI: Use "auto-dist-tag" for deployment [\#24](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/24) ([Turbo87](https://github.com/Turbo87))

**Merged pull requests:**

- md5 cacheKey in v0.1.x [\#25](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/25) ([hjdivad](https://github.com/hjdivad))

## [v0.2.3](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/tree/v0.2.3) (2017-03-13)

[Full Changelog](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/compare/v0.2.2...v0.2.3)

**Merged pull requests:**

- Avoid error when processing expressions before import has ocurred. [\#23](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/23) ([rwjblue](https://github.com/rwjblue))

## [v0.2.2](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/tree/v0.2.2) (2017-03-13)

[Full Changelog](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/compare/v0.2.1...v0.2.2)

**Merged pull requests:**

- Add failing test for usage after modules transform. [\#22](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/22) ([rwjblue](https://github.com/rwjblue))

## [v0.2.1](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/tree/v0.2.1) (2017-03-11)

[Full Changelog](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/compare/v0.2.0...v0.2.1)

**Merged pull requests:**

- Refactor to work when before babel-plugin-transform-es2015-template-literals. [\#21](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/21) ([rwjblue](https://github.com/rwjblue))

## [v0.2.0](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/tree/v0.2.0) (2017-03-11)

[Full Changelog](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/compare/v0.1.0...v0.2.0)

**Closed issues:**

- An in-range update of babel-core is breaking the build 🚨 [\#18](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/issues/18)
- needs to support caching [\#17](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/issues/17)

**Merged pull requests:**

- Add basic caching for babel@6 usage. [\#20](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/20) ([rwjblue](https://github.com/rwjblue))
- CI: Enable automatic NPM deployment for tags [\#19](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/19) ([Turbo87](https://github.com/Turbo87))

## [v0.1.0](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/tree/v0.1.0) (2016-08-10)

[Full Changelog](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/compare/0.0.5...v0.1.0)

**Implemented enhancements:**

- will be improved by [\#3](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/issues/3)
- Cleanup & referencesImport\(\) [\#13](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/13) ([Turbo87](https://github.com/Turbo87))

**Closed issues:**

- Migrate to ember-cli org? [\#14](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/issues/14)
- placeholders inside a tagged template string are not supported [\#9](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/issues/9)

**Merged pull requests:**

- Update all dependencies 🌴 [\#16](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/16) ([greenkeeperio-bot](https://github.com/greenkeeperio-bot))
- Incorporate cache keys. [\#15](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/15) ([rwjblue](https://github.com/rwjblue))
- Adjust Babel 6 options usage [\#12](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/12) ([Turbo87](https://github.com/Turbo87))
- Port plugin to Babel 6 [\#8](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/8) ([topaxi](https://github.com/topaxi))

## [0.0.5](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/tree/0.0.5) (2015-07-10)

[Full Changelog](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/compare/0.0.4...0.0.5)

**Merged pull requests:**

- Allow single string as argument for hbs [\#7](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/7) ([pangratz](https://github.com/pangratz))

## [0.0.4](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/tree/0.0.4) (2015-06-30)

[Full Changelog](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/compare/v0.0.3...0.0.4)

## [v0.0.3](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/tree/v0.0.3) (2015-06-26)

[Full Changelog](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/compare/v0.0.2...v0.0.3)

**Closed issues:**

- Babel deprecation with 5.6.14 - Use `path.replaceWithSourceString`. [\#5](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/issues/5)

**Merged pull requests:**

- Use `path.replaceWithSourceString` to avoid deprecation. [\#6](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/6) ([rwjblue](https://github.com/rwjblue))

## [v0.0.2](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/tree/v0.0.2) (2015-06-13)

[Full Changelog](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/compare/v0.0.1...v0.0.2)

**Merged pull requests:**

- Replace remove\(\) with dangerouslyRemove\(\) [\#4](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/pull/4) ([alisdair](https://github.com/alisdair))

## [v0.0.1](https://github.com/ember-cli/babel-plugin-htmlbars-inline-precompile/tree/v0.0.1) (2015-05-06)

\* _This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)_
