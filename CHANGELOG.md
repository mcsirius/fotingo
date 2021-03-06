# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="1.9.2"></a>
## [1.9.2](https://github.com/tagoro9/fotingo/compare/v1.9.1...v1.9.2) (2018-03-27)


### Bug Fixes

* **GitUtil:** relace ignore ~ when creating branch name ([#69](https://github.com/tagoro9/fotingo/issues/69)) ([531e6a7](https://github.com/tagoro9/fotingo/commit/531e6a7))



<a name="1.9.1"></a>
## [1.9.1](https://github.com/tagoro9/fotingo/compare/v1.9.0...v1.9.1) (2018-01-04)


### Bug Fixes

* **issue:** replace & when sanitizing the summary ([#68](https://github.com/tagoro9/fotingo/issues/68)) ([2708f89](https://github.com/tagoro9/fotingo/commit/2708f89))



<a name="1.9.0"></a>
# [1.9.0](https://github.com/tagoro9/fotingo/compare/v1.8.3...v1.9.0) (2017-12-29)


### Features

* **start:** add option to create an issue ([#67](https://github.com/tagoro9/fotingo/issues/67)) ([c1952b7](https://github.com/tagoro9/fotingo/commit/c1952b7))



<a name="1.8.3"></a>
## [1.8.3](https://github.com/tagoro9/fotingo/compare/v1.8.2...v1.8.3) (2017-12-22)


### Bug Fixes

* **release:** check that a release name is passed ([#66](https://github.com/tagoro9/fotingo/issues/66)) ([cab5cc6](https://github.com/tagoro9/fotingo/commit/cab5cc6))



<a name="1.8.2"></a>
## [1.8.2](https://github.com/tagoro9/fotingo/compare/v1.8.1...v1.8.2) (2017-10-26)


### Bug Fixes

* loosen the node required version ([#61](https://github.com/tagoro9/fotingo/issues/61)) ([6e50a21](https://github.com/tagoro9/fotingo/commit/6e50a21))



<a name="1.8.1"></a>
## [1.8.1](https://github.com/tagoro9/fotingo/compare/v1.8.0...v1.8.1) (2017-10-26)


### Bug Fixes

* **release:** use notes title for jira release desc ([#59](https://github.com/tagoro9/fotingo/issues/59)) ([494fc8f](https://github.com/tagoro9/fotingo/commit/494fc8f))



<a name="1.8.0"></a>
# [1.8.0](https://github.com/tagoro9/fotingo/compare/v1.7.1...v1.8.0) (2017-10-20)


### Bug Fixes

* **createBranchName:** del < and > from sanitized summary ([#55](https://github.com/tagoro9/fotingo/issues/55)) ([45c6422](https://github.com/tagoro9/fotingo/commit/45c6422))
* **readme:** fix typo in sample .fotingo file and fix yarn install cmd([#54](https://github.com/tagoro9/fotingo/issues/54)) ([d1056b9](https://github.com/tagoro9/fotingo/commit/d1056b9))


### Features

* create a release command ([#57](https://github.com/tagoro9/fotingo/issues/57)) ([3aa10e2](https://github.com/tagoro9/fotingo/commit/3aa10e2))



<a name="1.7.1"></a>
## [1.7.1](https://github.com/tagoro9/fotingo/compare/v1.7.0...v1.7.1) (2017-07-25)


### Bug Fixes

* **git:** extract information from branch name according to branch template ([#51](https://github.com/tagoro9/fotingo/issues/51)) ([a0f0fc3](https://github.com/tagoro9/fotingo/commit/a0f0fc3))



<a name="1.7.0"></a>
# [1.7.0](https://github.com/tagoro9/fotingo/compare/v1.6.1...v1.7.0) (2017-06-15)


### Bug Fixes

* **engines:** accept newer versions of yarn ([#39](https://github.com/tagoro9/fotingo/issues/39)) ([9536691](https://github.com/tagoro9/fotingo/commit/9536691)), closes [#37](https://github.com/tagoro9/fotingo/issues/37)
* **git:** handle push errors ([#45](https://github.com/tagoro9/fotingo/issues/45)) ([b0f27c4](https://github.com/tagoro9/fotingo/commit/b0f27c4)), closes [#40](https://github.com/tagoro9/fotingo/issues/40)
* **jira:** show error when login fails in second attempt ([#44](https://github.com/tagoro9/fotingo/issues/44)) ([eb2be89](https://github.com/tagoro9/fotingo/commit/eb2be89)), closes [#42](https://github.com/tagoro9/fotingo/issues/42)


### Features

* **start:** allow user to define branch name templates ([#47](https://github.com/tagoro9/fotingo/issues/47)) ([b5af3dc](https://github.com/tagoro9/fotingo/commit/b5af3dc)), closes [#43](https://github.com/tagoro9/fotingo/issues/43) [#38](https://github.com/tagoro9/fotingo/issues/38)



<a name="1.6.1"></a>
## [1.6.1](https://github.com/tagoro9/fotingo/compare/v1.6.0...v1.6.1) (2017-04-13)


### Bug Fixes

* **config:** defaul to file if no in memory value ([2e7c4e0](https://github.com/tagoro9/fotingo/commit/2e7c4e0))
* **review:** update git base branch too with -b ([d31cf64](https://github.com/tagoro9/fotingo/commit/d31cf64))



<a name="1.6.0"></a>
# [1.6.0](https://github.com/tagoro9/fotingo/compare/v1.5.0...v1.6.0) (2017-04-08)


### Features

* allow to overwrite base branch ([#35](https://github.com/tagoro9/fotingo/issues/35)) ([a581f22](https://github.com/tagoro9/fotingo/commit/a581f22)), closes [#34](https://github.com/tagoro9/fotingo/issues/34)



<a name="1.5.0"></a>
# [1.5.0](https://github.com/tagoro9/fotingo/compare/v1.4.3...v1.5.0) (2017-03-18)


### Features

* **review:** allow to add reviewers to the PR ([#33](https://github.com/tagoro9/fotingo/issues/33)) ([1eea1a1](https://github.com/tagoro9/fotingo/commit/1eea1a1)), closes [#4](https://github.com/tagoro9/fotingo/issues/4)
* **Start:** add -n option ([#32](https://github.com/tagoro9/fotingo/issues/32)) ([6271083](https://github.com/tagoro9/fotingo/commit/6271083)), closes [#18](https://github.com/tagoro9/fotingo/issues/18)



<a name="1.4.3"></a>
## [1.4.3](https://github.com/tagoro9/fotingo/compare/v1.4.2...v1.4.3) (2017-03-17)


### Bug Fixes

* **git:** show an error when there is no key in the agent ([#30](https://github.com/tagoro9/fotingo/issues/30)) ([d275199](https://github.com/tagoro9/fotingo/commit/d275199)), closes [#8](https://github.com/tagoro9/fotingo/issues/8)
* **Github:** show error message when PR already exists ([#26](https://github.com/tagoro9/fotingo/issues/26)) ([eeecd18](https://github.com/tagoro9/fotingo/commit/eeecd18)), closes [#25](https://github.com/tagoro9/fotingo/issues/25)
* **Jira:** infer in review state correctly ([#31](https://github.com/tagoro9/fotingo/issues/31)) ([da1fbcf](https://github.com/tagoro9/fotingo/commit/da1fbcf)), closes [#29](https://github.com/tagoro9/fotingo/issues/29)
* **Review:** show error message when no issue in branch ([#27](https://github.com/tagoro9/fotingo/issues/27)) ([b5fee66](https://github.com/tagoro9/fotingo/commit/b5fee66)), closes [#16](https://github.com/tagoro9/fotingo/issues/16)



<a name="1.4.2"></a>
## [1.4.2](https://github.com/tagoro9/fotingo/compare/v1.4.1...v1.4.2) (2017-03-16)


### Bug Fixes

* **script:** make lib/fotingo.js executable ([97b20b4](https://github.com/tagoro9/fotingo/commit/97b20b4))



<a name="1.4.1"></a>
## [1.4.1](https://github.com/tagoro9/fotingo/compare/v1.4.0...v1.4.1) (2017-03-16)


### Bug Fixes

* **build:** build it correctly ([add0014](https://github.com/tagoro9/fotingo/commit/add0014))



<a name="1.4.0"></a>
# [1.4.0](https://github.com/tagoro9/fotingo/compare/v1.3.2...v1.4.0) (2017-03-16)


### Features

* **Jira:** improve issue transition setup ([#24](https://github.com/tagoro9/fotingo/issues/24)) ([c214884](https://github.com/tagoro9/fotingo/commit/c214884)), closes [#11](https://github.com/tagoro9/fotingo/issues/11)



<a name="1.3.2"></a>
## [1.3.2](https://github.com/tagoro9/fotingo/compare/v1.3.1...v1.3.2) (2017-03-16)


### Bug Fixes

* **git:** parse issues correctly ([#22](https://github.com/tagoro9/fotingo/issues/22)) ([ca571fb](https://github.com/tagoro9/fotingo/commit/ca571fb)), closes [#15](https://github.com/tagoro9/fotingo/issues/15)
* **git:** read remote and branch from config when getting history ([#21](https://github.com/tagoro9/fotingo/issues/21)) ([6b062eb](https://github.com/tagoro9/fotingo/commit/6b062eb))
* **Github:** do not add links to issues if mode is simple ([#23](https://github.com/tagoro9/fotingo/issues/23)) ([411a2bd](https://github.com/tagoro9/fotingo/commit/411a2bd)), closes [#14](https://github.com/tagoro9/fotingo/issues/14)



<a name="1.3.1"></a>
## [1.3.1](https://github.com/tagoro9/fotingo/compare/v1.3.0...v1.3.1) (2017-03-03)


### Bug Fixes

* **ui:** show issues and branch names in ui ([#13](https://github.com/tagoro9/fotingo/issues/13)) ([67c40a9](https://github.com/tagoro9/fotingo/commit/67c40a9)), closes [#12](https://github.com/tagoro9/fotingo/issues/12)



<a name="1.3.0"></a>
# [1.3.0](https://github.com/tagoro9/fotingo/compare/v1.2.0...v1.3.0) (2017-03-02)


### Features

* **config:** allow to have local config files ([#9](https://github.com/tagoro9/fotingo/issues/9)) ([4d436dd](https://github.com/tagoro9/fotingo/commit/4d436dd))
* **review:** allow to add labels to PRs ([#10](https://github.com/tagoro9/fotingo/issues/10)) ([5d4d487](https://github.com/tagoro9/fotingo/commit/5d4d487))



<a name="1.2.0"></a>
# [1.2.0](https://github.com/tagoro9/fotingo/compare/v1.1.1...v1.2.0) (2017-02-24)


### Bug Fixes

* **config:** only create config file when there is none ([57de6b2](https://github.com/tagoro9/fotingo/commit/57de6b2))
* **errors:** do not show ugly end message for unknown errors ([339ebb1](https://github.com/tagoro9/fotingo/commit/339ebb1))
* **git:** handle duplicate branch errors ([b22da57](https://github.com/tagoro9/fotingo/commit/b22da57))
* **jira:** fix typo in IN_REVIEW status value ([83d70af](https://github.com/tagoro9/fotingo/commit/83d70af))


### Features

* **git:** push and track branch to remote ([7ac254b](https://github.com/tagoro9/fotingo/commit/7ac254b))
* **jira:** improve setup UI for transition ids ([69576a0](https://github.com/tagoro9/fotingo/commit/69576a0))



<a name="1.1.1"></a>
## [1.1.1](https://github.com/tagoro9/fotingo/compare/v1.1.0...v1.1.1) (2017-02-18)


### Bug Fixes

* **github:** handle empty commit bodies ([5626d0e](https://github.com/tagoro9/fotingo/commit/5626d0e))
* **jira:** do not skip root question ([3bbb764](https://github.com/tagoro9/fotingo/commit/3bbb764))
* **review:** show correct total number of steps ([894556b](https://github.com/tagoro9/fotingo/commit/894556b))
* **review:** wait for all promises to print footer ([c820678](https://github.com/tagoro9/fotingo/commit/c820678))



<a name="1.1.0"></a>
# [1.1.0](https://github.com/tagoro9/fotingo/compare/v1.0.4...v1.1.0) (2017-02-16)


### Bug Fixes

* **github:** correctly read branch name when creating PR title ([cb6a279](https://github.com/tagoro9/fotingo/commit/cb6a279))


### Features

* **git:** use conventional changelog parser to get commit info ([9d02d71](https://github.com/tagoro9/fotingo/commit/9d02d71))
* **review:** show PR url at the end of the process ([2dd868d](https://github.com/tagoro9/fotingo/commit/2dd868d))



<a name="1.0.4"></a>
## [1.0.4](https://github.com/tagoro9/fotingo/compare/v1.0.3...v1.0.4) (2017-02-13)


### Bug Fixes

* **review:** pass IN_REVIEW status when updating issue ([bdd9021](https://github.com/tagoro9/fotingo/commit/bdd9021))



<a name="1.0.3"></a>
## [1.0.3](https://github.com/tagoro9/fotingo/compare/v1.0.2...v1.0.3) (2017-02-13)


### Bug Fixes

* **git:** create correct branch names for stories ([9973c4d](https://github.com/tagoro9/fotingo/commit/9973c4d))
* **review:** pass correct issue status name ([b899eb3](https://github.com/tagoro9/fotingo/commit/b899eb3))
