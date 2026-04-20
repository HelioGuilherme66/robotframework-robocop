# Release notes

## [9.0.0](https://github.com/HelioGuilherme66/robotframework-robocop/compare/v8.2.7...v9.0.0) (2026-04-20)


### ⚠ BREAKING CHANGES

* Redesign configuration layerfor full typing and OOP friendliness ([#1661](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1661))
* add deprecated-return-keyword rule fix and deprecate ReplaceReturns formatter ([#1643](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1643))
* deprecate deprecated-statement rule and split into deprecated-return-setting ([#1639](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1639))
* Drop support for Python 3.9 and Robot Framework 4.* ([#1619](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1619))
* Add fixable rules ([#1617](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1617))w
* Refactor source files handling with common SourceFile class ([#1615](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1615))

### Features

* Add case_normalization parameter to enforce case by RenameKeywords ([#1667](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1667)) ([49a0b02](https://github.com/HelioGuilherme66/robotframework-robocop/commit/49a0b025fbe535e2d855b65db2f557f75c1c9bb9))
* add commented-out-code detection rule (COM06) ([#1564](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1564)) ([8afa9d2](https://github.com/HelioGuilherme66/robotframework-robocop/commit/8afa9d268d4ca909cf56225992962c39a088f8bf))
* Add complete typing annotations ([#1657](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1657)) ([5e97a85](https://github.com/HelioGuilherme66/robotframework-robocop/commit/5e97a8583fc8beb51a8b4eca5300bcb6574e72ac))
* add deprecated-return-keyword rule fix and deprecate ReplaceReturns formatter ([#1643](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1643)) ([48e747c](https://github.com/HelioGuilherme66/robotframework-robocop/commit/48e747c9dbbfce3edd30add4120bcec30d03bf62))
* Add different kind of TextEdit for convenience ([#1641](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1641)) ([95bd99f](https://github.com/HelioGuilherme66/robotframework-robocop/commit/95bd99f558c19c3c76b970e704a73193f03db08b))
* add docs_urls property to rule class ([#1545](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1545)) ([ab29942](https://github.com/HelioGuilherme66/robotframework-robocop/commit/ab299428a84e3c53980c167674332293277c6306))
* add extend-select linter option ([#1554](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1554)) ([851bb4d](https://github.com/HelioGuilherme66/robotframework-robocop/commit/851bb4df28ca014483dd9c01f7279314b2e42fee))
* add file-level caching for linter and formatter to skip unchanged files ([#1565](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1565)) ([ceb02cc](https://github.com/HelioGuilherme66/robotframework-robocop/commit/ceb02ccff7cf5316ef8debb5040bfa625981eba0))
* Add fix to deprecate-return-setting rule ([#1642](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1642)) ([113c011](https://github.com/HelioGuilherme66/robotframework-robocop/commit/113c011cbaa04cbc349abf13b6c09146d0f4d3b7))
* Add fixable rules ([#1617](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1617))w ([128c849](https://github.com/HelioGuilherme66/robotframework-robocop/commit/128c849f320d392fa267653c737a0616fb62b620))
* Add full typing safety with mypy checks ([#1662](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1662)) ([d27e59f](https://github.com/HelioGuilherme66/robotframework-robocop/commit/d27e59f6268ff04938885e4d82f2de09bc326098))
* add MCP server for AI assistant integration ([#1583](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1583)) ([c68330a](https://github.com/HelioGuilherme66/robotframework-robocop/commit/c68330a34a740e86388ee540327ed6f1d1fe83fb))
* add performance tests to benchmark Robocop on release ([#1611](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1611)) ([eea1c56](https://github.com/HelioGuilherme66/robotframework-robocop/commit/eea1c5692dd908ee3d64b82088e532c9e54914f0))
* Add set-keyword-with-type rule ([#1655](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1655)) ([eced886](https://github.com/HelioGuilherme66/robotframework-robocop/commit/eced88693547ea99073fa9d89f1fbd3ed7a0e7ae))
* add three separate rules for variable type annotations (RF 7.3+) ([#1579](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1579)) ([03ef483](https://github.com/HelioGuilherme66/robotframework-robocop/commit/03ef483446a153137035c48f8f6e63ce02cca480))
* allow to check and report issue from the rule class ([#1644](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1644)) ([8aff795](https://github.com/HelioGuilherme66/robotframework-robocop/commit/8aff795642436c1e39dd5d37ab31acd4ec6f3704))
* allow to manually disable report ([#1543](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1543)) ([856f5dd](https://github.com/HelioGuilherme66/robotframework-robocop/commit/856f5ddafb10efb7b241f76d0a4c80e0de70fbc1))
* automate release process with release-please ([#1571](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1571)) ([4bd6d3f](https://github.com/HelioGuilherme66/robotframework-robocop/commit/4bd6d3f5cddaa4c85085ca87b8960720e77d8dd6))
* change mixed-tabs-and-spaces rule behaviour to report all occurences of mixed tabs and spaces in a file ([#1530](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1530)) ([b90c8be](https://github.com/HelioGuilherme66/robotframework-robocop/commit/b90c8be7cd72e6be8078b77bcb25e7d1fb5f8b42))
* Deprecate AddMissingEnd formatter ([#1647](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1647)) ([b97368c](https://github.com/HelioGuilherme66/robotframework-robocop/commit/b97368ce2d96b092ead145c29d8e201361690d63))
* deprecate deprecated-statement rule and split into deprecated-return-setting ([#1639](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1639)) ([2f9010a](https://github.com/HelioGuilherme66/robotframework-robocop/commit/2f9010ae3c1d3d0793086d8ccf5f74e85e3a7e3f))
* do not print diagnostic messages in diff mode, only file changes ([#1625](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1625)) ([41f4ff0](https://github.com/HelioGuilherme66/robotframework-robocop/commit/41f4ff0784ec5cadb4687a6ed2615db9680e36ee))
* Drop support for Python 3.9 and Robot Framework 4.* ([#1619](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1619)) ([2e73142](https://github.com/HelioGuilherme66/robotframework-robocop/commit/2e731420ccc210bbfc2519a639b2618a1e486ed1))
* emit warning when select/extend-select/ignore use non existing rule ([#1670](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1670)) ([5e3320f](https://github.com/HelioGuilherme66/robotframework-robocop/commit/5e3320fd600417c48c9c19aa89ab74162e2377e0))
* extend disablers to ignore whole node ([#1551](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1551)) ([8bb27f7](https://github.com/HelioGuilherme66/robotframework-robocop/commit/8bb27f749b968d7be8081cf1bb4b081ed73f3c19))
* Filter fixable rules with --fixable and --unfixable ([#1620](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1620)) ([ed91630](https://github.com/HelioGuilherme66/robotframework-robocop/commit/ed916307e5696483616eadaff68c8481759e69b3))
* Fix rule where it is being report ([#1630](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1630)) ([443d59b](https://github.com/HelioGuilherme66/robotframework-robocop/commit/443d59b71211c60aea549415f837541e9d641da7))
* Ignore quoted parts when renaming or linting keyword name ([#1671](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1671)) ([399e0c5](https://github.com/HelioGuilherme66/robotframework-robocop/commit/399e0c54d4113c8b2f5921306d11722226f8c68b))
* Ignore unused variables starting with `_` underscore ([#1550](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1550)) ([6c325b5](https://github.com/HelioGuilherme66/robotframework-robocop/commit/6c325b554fedea7089c600509d36a88e016b8ce6))
* Implement multiple configuration files config manager ([#1208](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1208)) ([957aa12](https://github.com/HelioGuilherme66/robotframework-robocop/commit/957aa12a49ae39176ca7b7bc090299f183f84f21))
* Improve performance of inconsistent-variable-name and possible-overwriting rules ([#1646](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1646)) ([581ec82](https://github.com/HelioGuilherme66/robotframework-robocop/commit/581ec828bec3a38c41c71fab4e72d71ed6e6b350))
* Improve performance of unused-variable and unused-argument rules ([#1645](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1645)) ([4bb29c4](https://github.com/HelioGuilherme66/robotframework-robocop/commit/4bb29c43c78bcb6cc74b8c96f8da5a3d61279234))
* inherit another configuration file with extends option ([#1537](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1537)) ([6a514b1](https://github.com/HelioGuilherme66/robotframework-robocop/commit/6a514b117fa53be6e1546612cc3b37f5ad30e132))
* Integrate Formatter with Robocop ([#1210](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1210)) ([ca524c3](https://github.com/HelioGuilherme66/robotframework-robocop/commit/ca524c3ba29a8a50fb84a95f32492a0c1cdf69ff))
* list rules can now return result programatically ([#1629](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1629)) ([457d135](https://github.com/HelioGuilherme66/robotframework-robocop/commit/457d135c053be6dd5c0f8727d7ac6c07ee23e918))
* Make MCP aware of local config ([#1673](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1673)) ([55e18b6](https://github.com/HelioGuilherme66/robotframework-robocop/commit/55e18b68924f9db0eb24ad441904f96351d529d6))
* **mcp:** add new tools and improve UX for large codebases ([#1601](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1601)) ([9b1d871](https://github.com/HelioGuilherme66/robotframework-robocop/commit/9b1d871a2c40549de1d2f1b707201da47f6c68a6))
* **mcp:** add response caching and error handling middleware ([#1599](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1599)) ([406cfbe](https://github.com/HelioGuilherme66/robotframework-robocop/commit/406cfbefaa229664fdd39e5265f2f47958aabb64))
* **mcp:** Allow to pass configuration file path via MCP tools ([#1691](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1691)) ([da5dc6e](https://github.com/HelioGuilherme66/robotframework-robocop/commit/da5dc6e04cda7764608fd10abf4e9e7574836a2e))
* **mcp:** enhance MCP server with batch operations, quality metrics, and improved LLM guidance ([#1593](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1593)) ([c6a853b](https://github.com/HelioGuilherme66/robotframework-robocop/commit/c6a853bd016eff8f65742c79c511fd8712abc1a3))
* per_file_ignores option to ignore rules matching file patterns ([#1542](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1542)) ([a8be5b1](https://github.com/HelioGuilherme66/robotframework-robocop/commit/a8be5b1a84352b6a010aa9df33cec32d493c2d4d))
* Redesign configuration layerfor full typing and OOP friendliness ([#1661](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1661)) ([42045dc](https://github.com/HelioGuilherme66/robotframework-robocop/commit/42045dc71f4062705d48dbd6aabea1b1a238bf87))
* Refactor print_issues report to gain 3x perfomance gain on printing ([#1605](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1605)) ([6755d96](https://github.com/HelioGuilherme66/robotframework-robocop/commit/6755d96ceadb0b78a80f6e70e5e262967029fde3))
* refactor source file handling ([#1613](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1613)) ([0e7f04e](https://github.com/HelioGuilherme66/robotframework-robocop/commit/0e7f04ee07ea271610f55fe67af59dfd912292cd))
* rename custom-formatters to extend-select ([#1553](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1553)) ([0df328a](https://github.com/HelioGuilherme66/robotframework-robocop/commit/0df328ab858c1e3a1e8adf7ea7d877252966afce))
* Replace `typer-slim` with `typer` ([#1685](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1685)) ([b83400f](https://github.com/HelioGuilherme66/robotframework-robocop/commit/b83400f5727d4a4b82092319401abdf7fba699e8))
* restore project checks as separate command ([#1556](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1556)) ([e06371c](https://github.com/HelioGuilherme66/robotframework-robocop/commit/e06371c5ae0f2896ea0129b0d8f63e261dec3e71))
* Skip documentation by default in NormalizeSeparators ([#1672](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1672)) ([5b1ae35](https://github.com/HelioGuilherme66/robotframework-robocop/commit/5b1ae35af3d914a324dd697e754bbceff5e496de))
* split deprecated-statement to deprecated-force-tags and add fix for it ([#1622](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1622)) ([0316605](https://github.com/HelioGuilherme66/robotframework-robocop/commit/03166058f8d76e8476e8166741793eb3f07aa089))
* split deprecated-statement to deprecated-loop-keyword rule ([#1637](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1637)) ([9342c67](https://github.com/HelioGuilherme66/robotframework-robocop/commit/9342c677068ed058f23dbc7165870ba3ec9ee380))
* split deprecated-statement to deprecated-return-keyword ([#1638](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1638)) ([a0fcd14](https://github.com/HelioGuilherme66/robotframework-robocop/commit/a0fcd14aaf254cebb2a5f98378ef061f217da8d7))
* split deprecated-statement to deprecated-run-keyword-if rule ([#1632](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1632)) ([a974abd](https://github.com/HelioGuilherme66/robotframework-robocop/commit/a974abd29c45ed25c3753ec56210b4d423786e42))
* split too long settings from settings section ([#1559](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1559)) ([9bf3788](https://github.com/HelioGuilherme66/robotframework-robocop/commit/9bf3788106b369ce16b66b4de037e1cd64998cd3))
* Split wrong-case-in-keyword-name into itself and wrong-case-in-keyword-call ([10393cb](https://github.com/HelioGuilherme66/robotframework-robocop/commit/10393cb9295a8b12ff25793e039b2b93fc9c16bf))
* Update RenameVariables formatter so it treats numbers as part of word and does not split on it ([#1663](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1663)) ([eddfd96](https://github.com/HelioGuilherme66/robotframework-robocop/commit/eddfd96751ab1b10b6e626239be63118e9ec5c58))
* **VAR02:** add ignore parameter for unused-variable rule ([#1576](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1576)) ([0c2ebf4](https://github.com/HelioGuilherme66/robotframework-robocop/commit/0c2ebf41a2f43f0cb73e586b3e254c02cdfacf7c))
* Variable type conversion - support duplicate-argument rule ([#1654](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1654)) ([af8d35a](https://github.com/HelioGuilherme66/robotframework-robocop/commit/af8d35a72b6a3e33d94a5f3127369156f80366c2))
* Variable type conversion - support duplicated-assigned-var-name rule ([#1650](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1650)) ([3f304e5](https://github.com/HelioGuilherme66/robotframework-robocop/commit/3f304e5c8fe8136a23fc0a7adeb8eccd24b1ba66))
* Variable type conversion - support inconsistent-variable-name rule ([#1651](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1651)) ([9a0f525](https://github.com/HelioGuilherme66/robotframework-robocop/commit/9a0f525b51e1e89baa54e87ee41ade37715e5277))
* Variable type conversion - support non-local-variables-should-be-uppercase ([#1652](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1652)) ([97f4725](https://github.com/HelioGuilherme66/robotframework-robocop/commit/97f47250dc9685d830ab1c3c460f8c217d86ca43))
* Variable type conversion - support possible-variable-overwriting' rule ([#1653](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1653)) ([322cd95](https://github.com/HelioGuilherme66/robotframework-robocop/commit/322cd95ac352a23d75797f9d19d61add0d3101be))


### Bug Fixes

* `wrong-case-in-keyword-name` rule false positive reports on `.` characters ([#1561](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1561)) ([f2eb584](https://github.com/HelioGuilherme66/robotframework-robocop/commit/f2eb5848ed5b98ea171c6c5d814da5b880117184))
* add explicit typing-extensions dependency ([#1680](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1680)) ([b406f25](https://github.com/HelioGuilherme66/robotframework-robocop/commit/b406f2519b5ca8aaf5048d3b1a5ddffb74383c71))
* Add missing robot:exit-on-failure tag to reserved tag list ([#1712](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1712)) ([1f2097a](https://github.com/HelioGuilherme66/robotframework-robocop/commit/1f2097a701984439a3a3e5c2583ac37f21d06bb4))
* **caching:** Fix CLI always overriding cache=true/false in the configuration file ([#1608](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1608)) ([b31a5ef](https://github.com/HelioGuilherme66/robotframework-robocop/commit/b31a5ef95c1d706623656aa3f1417730f8c23034))
* elevating scope of variable raises possible-variable-overwritting ([#1064](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1064)) ([e5d30f4](https://github.com/HelioGuilherme66/robotframework-robocop/commit/e5d30f418402cd64896844d517ec46daaeff4b9a))
* ensure that configuration files are loaded in the order (robocop.toml &gt; robot.toml &gt; pyproject.toml) ([#1729](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1729)) ([b7e041f](https://github.com/HelioGuilherme66/robotframework-robocop/commit/b7e041f314e375035fc61d29348425df8168dc89))
* Fix [#1174](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1174) expression-can-be-simplified raised for == 0 ([#1649](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1649)) ([d0f4985](https://github.com/HelioGuilherme66/robotframework-robocop/commit/d0f49857c07bf14696acde6531497ed88447bee7))
* Fix [#1422](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1422) - ReplaceWithVAR formatter replacing variables with item access ([#1648](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1648)) ([a9c3377](https://github.com/HelioGuilherme66/robotframework-robocop/commit/a9c3377bb1b7b40b798d68f7b59f5903f06477bc))
* Fix `AlignKeywordsSection` and `AlignTestCasesSection` not aligning VAR variables ([#1531](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1531)) ([4aa28a3](https://github.com/HelioGuilherme66/robotframework-robocop/commit/4aa28a30eb6b883e61f9e188297b6cdbad3537a6))
* Fix caching the issues with fixes ([#1623](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1623)) ([256874b](https://github.com/HelioGuilherme66/robotframework-robocop/commit/256874b096e6fcf9e3bbb7e6ed501e19fc61c1b0))
* Fix circular import error due to ConfigManager split from config.py ([#1695](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1695)) ([09e3fda](https://github.com/HelioGuilherme66/robotframework-robocop/commit/09e3fdaa8e83a16b19f49c5f199f728d056fde27))
* Fix documentation typos & add documentation linter ([#1738](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1738)) ([2a45e93](https://github.com/HelioGuilherme66/robotframework-robocop/commit/2a45e93432c94d1b8bf76b999172b1f582053e6e))
* Fix extend-select matching only on rule id, not on rule name ([#1669](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1669)) ([403ff7d](https://github.com/HelioGuilherme66/robotframework-robocop/commit/403ff7d4ef54a92be48513c180c1cf002d80fefd))
* Fix fatal attribute error when running Robocop ([#1698](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1698)) ([47ac87e](https://github.com/HelioGuilherme66/robotframework-robocop/commit/47ac87eae4a4a789d1bda4159dad285c725b8449))
* Fix format --extend-select not enabling formatters ([#1668](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1668)) ([3c76c50](https://github.com/HelioGuilherme66/robotframework-robocop/commit/3c76c500c42d9c076c99d49e7b3bb3ff6cae83f8))
* Fix missing force-exclude flag from the configuration file ([#1708](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1708)) ([90cea8c](https://github.com/HelioGuilherme66/robotframework-robocop/commit/90cea8c9ee78552e8c86a58297553e6703f50e38))
* Fix not all issue format parameters supported by extended output ([#1624](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1624)) ([727c38d](https://github.com/HelioGuilherme66/robotframework-robocop/commit/727c38d9d39d63c0b4fc4563bf40a9e0f2680222))
* Fix section-out-of-order not supporting comments section ([#1725](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1725)) ([56f0ab2](https://github.com/HelioGuilherme66/robotframework-robocop/commit/56f0ab2a2dffbabddfccf5473be369b8252cf9de))
* Fix too-long-variable-name throwing exception on Set X Variable without arguments ([#1675](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1675)) ([3a55663](https://github.com/HelioGuilherme66/robotframework-robocop/commit/3a556635729b2b5f1b9fd3654cdf9c5777391db8))
* Fix unused-variable reported on the FOR loop variable with type ([#1706](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1706)) ([260f4f4](https://github.com/HelioGuilherme66/robotframework-robocop/commit/260f4f44c012266a8fdce06a8c5ece84e4c98383))
* Fix unused-variable reported on variable names starting with digit ([#1689](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1689)) ([fc6b78d](https://github.com/HelioGuilherme66/robotframework-robocop/commit/fc6b78de9faa3d61acc0a6e9f8424c0cc4333efa))
* ignore variables in tags & keyword tags ([#1066](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1066)) ([ecfd497](https://github.com/HelioGuilherme66/robotframework-robocop/commit/ecfd4977e694ee6df824982a88aa143dbbd94931))
* Invalid Robocop disabler accepted as disabler for all rules ([#1569](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1569)) ([595ffdb](https://github.com/HelioGuilherme66/robotframework-robocop/commit/595ffdb83a3b50ccebf4883493b221076782836b))
* Keyword naming rules with library import with underscores is now detected properly ([#1734](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1734)) ([a86b1d4](https://github.com/HelioGuilherme66/robotframework-robocop/commit/a86b1d4133008a844ac45268076874f85189390b))
* **mcp:** fix limit handling bugs and add enhancements ([#1589](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1589)) ([0926a4d](https://github.com/HelioGuilherme66/robotframework-robocop/commit/0926a4d114b10bdb8a468a472f1105d9a227c645))
* multiple paths passed to robocop check/format command resolving to the same config ([#1614](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1614)) ([bdcfd48](https://github.com/HelioGuilherme66/robotframework-robocop/commit/bdcfd489f7a0b5e00c190ae8a7fc9a87a22c25f0))
* optional `no-embedded-keyword-arguments` rule fatal exception when reading a file with invalid syntax ([#1534](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1534)) ([cc7e83f](https://github.com/HelioGuilherme66/robotframework-robocop/commit/cc7e83f4dcd1c51e1a7f169d41011672061e262e))
* path to dependency file should be directory ([#1154](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1154)) ([7b165cd](https://github.com/HelioGuilherme66/robotframework-robocop/commit/7b165cd72e1901963e66a188f2f9c646e250286d))
* piping output not working on WIndows because of code lines converted to emojis ([#1541](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1541)) ([07aea82](https://github.com/HelioGuilherme66/robotframework-robocop/commit/07aea82e8bfa07adbdea545d9d2ecacbd0411210))
* pygments 2.20.0 failing to build our documentaton ([#1731](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1731)) ([e6a5945](https://github.com/HelioGuilherme66/robotframework-robocop/commit/e6a594589b9e23d24c505b47fd4bd7f090d98130))
* **release:** fix triggering Github workflows from automated scripts ([#1594](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1594)) ([72ce0ff](https://github.com/HelioGuilherme66/robotframework-robocop/commit/72ce0ff36aed05eef362aa0aeed80324b2ec7a8e))
* unused-argument rule raised when argument is used in item access or inline eval ([#1687](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1687)) ([d014a53](https://github.com/HelioGuilherme66/robotframework-robocop/commit/d014a53d32b9effe696fccc993f675efb3724941))
* unused-variable if first declared as argument and used in the loop ([#978](https://github.com/HelioGuilherme66/robotframework-robocop/issues/978)) ([75f5556](https://github.com/HelioGuilherme66/robotframework-robocop/commit/75f55566d81032fc76a9b70160b55a5167fa91b0))
* unused-variable with variables in [Setup], [Teardown] and [Timeout] ([#1063](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1063)) ([dfad472](https://github.com/HelioGuilherme66/robotframework-robocop/commit/dfad4721de25d50c6dc2a9e65d072aecc05ff7f5))


### Documentation

* add annotations rule group to documentation ([#1439](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1439)) ([#1588](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1588)) ([50cbfa7](https://github.com/HelioGuilherme66/robotframework-robocop/commit/50cbfa72cd34997ce0a63aeaaa5e109a05f83bb6))
* Add caching documentation ([#1572](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1572)) ([5d941e8](https://github.com/HelioGuilherme66/robotframework-robocop/commit/5d941e849f5ac84a8208b1d21ccdf861006b4cbc))
* Add deprecated_names section to rules list in docs ([#1529](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1529)) ([c8f6ddf](https://github.com/HelioGuilherme66/robotframework-robocop/commit/c8f6ddfc86b17af2d6914ec3979ff5c2c656dbc7))
* add megalinter integration page ([#1558](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1558)) ([efb2672](https://github.com/HelioGuilherme66/robotframework-robocop/commit/efb2672286fbec56b889d0a7af61d8314935b304))
* Fix rst-style urls in the documentation ([#1640](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1640)) ([eb1dcab](https://github.com/HelioGuilherme66/robotframework-robocop/commit/eb1dcababfa81b5d47af59066d952c22a844247d))
* improve changelog for 7.0.0 ([#1563](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1563)) ([97f429b](https://github.com/HelioGuilherme66/robotframework-robocop/commit/97f429b6afd15e9f5d116307eaf9ffc8a8025504))


### Refactoring

* Refactor source files handling with common SourceFile class ([#1615](https://github.com/HelioGuilherme66/robotframework-robocop/issues/1615)) ([25d30da](https://github.com/HelioGuilherme66/robotframework-robocop/commit/25d30dabfc2840d253da4aa0e692fb75ef188d31))

## [8.2.7](https://github.com/MarketSquare/robotframework-robocop/compare/v8.2.6...v8.2.7) (2026-04-14)


### Bug Fixes

* Keyword naming rules with library import with underscores is now detected properly ([#1734](https://github.com/MarketSquare/robotframework-robocop/issues/1734)) ([a86b1d4](https://github.com/MarketSquare/robotframework-robocop/commit/a86b1d4133008a844ac45268076874f85189390b))

## [8.2.6](https://github.com/MarketSquare/robotframework-robocop/compare/v8.2.5...v8.2.6) (2026-04-13)


### Bug Fixes

* ensure that configuration files are loaded in the order (robocop.toml &gt; robot.toml &gt; pyproject.toml) ([#1729](https://github.com/MarketSquare/robotframework-robocop/issues/1729)) ([b7e041f](https://github.com/MarketSquare/robotframework-robocop/commit/b7e041f314e375035fc61d29348425df8168dc89))
* pygments 2.20.0 failing to build our documentaton ([#1731](https://github.com/MarketSquare/robotframework-robocop/issues/1731)) ([e6a5945](https://github.com/MarketSquare/robotframework-robocop/commit/e6a594589b9e23d24c505b47fd4bd7f090d98130))

## [8.2.5](https://github.com/MarketSquare/robotframework-robocop/compare/v8.2.4...v8.2.5) (2026-04-07)


### Bug Fixes

* Fix section-out-of-order not supporting comments section ([#1725](https://github.com/MarketSquare/robotframework-robocop/issues/1725)) ([56f0ab2](https://github.com/MarketSquare/robotframework-robocop/commit/56f0ab2a2dffbabddfccf5473be369b8252cf9de))

## [8.2.4](https://github.com/MarketSquare/robotframework-robocop/compare/v8.2.3...v8.2.4) (2026-03-27)


### Bug Fixes

* Add missing robot:exit-on-failure tag to reserved tag list ([#1712](https://github.com/MarketSquare/robotframework-robocop/issues/1712)) ([1f2097a](https://github.com/MarketSquare/robotframework-robocop/commit/1f2097a701984439a3a3e5c2583ac37f21d06bb4))

## [8.2.3](https://github.com/MarketSquare/robotframework-robocop/compare/v8.2.2...v8.2.3) (2026-03-17)


### Bug Fixes

* Fix missing force-exclude flag from the configuration file ([#1708](https://github.com/MarketSquare/robotframework-robocop/issues/1708)) ([90cea8c](https://github.com/MarketSquare/robotframework-robocop/commit/90cea8c9ee78552e8c86a58297553e6703f50e38))
* Fix unused-variable reported on the FOR loop variable with type ([#1706](https://github.com/MarketSquare/robotframework-robocop/issues/1706)) ([260f4f4](https://github.com/MarketSquare/robotframework-robocop/commit/260f4f44c012266a8fdce06a8c5ece84e4c98383))

## [8.2.2](https://github.com/MarketSquare/robotframework-robocop/compare/v8.2.1...v8.2.2) (2026-02-27)


### Bug Fixes

* Fix fatal attribute error when running Robocop ([#1698](https://github.com/MarketSquare/robotframework-robocop/issues/1698)) ([47ac87e](https://github.com/MarketSquare/robotframework-robocop/commit/47ac87eae4a4a789d1bda4159dad285c725b8449))

## [8.2.1](https://github.com/MarketSquare/robotframework-robocop/compare/v8.2.0...v8.2.1) (2026-02-27)


### Bug Fixes

* Fix circular import error due to ConfigManager split from config.py ([#1695](https://github.com/MarketSquare/robotframework-robocop/issues/1695)) ([09e3fda](https://github.com/MarketSquare/robotframework-robocop/commit/09e3fdaa8e83a16b19f49c5f199f728d056fde27))

## [8.2.0](https://github.com/MarketSquare/robotframework-robocop/compare/v8.1.1...v8.2.0) (2026-02-22)


### Features

* **mcp:** Allow to pass configuration file path via MCP tools ([#1691](https://github.com/MarketSquare/robotframework-robocop/issues/1691)) ([da5dc6e](https://github.com/MarketSquare/robotframework-robocop/commit/da5dc6e04cda7764608fd10abf4e9e7574836a2e))

## [8.1.1](https://github.com/MarketSquare/robotframework-robocop/compare/v8.1.0...v8.1.1) (2026-02-20)


### Bug Fixes

* Fix unused-variable reported on variable names starting with digit ([#1689](https://github.com/MarketSquare/robotframework-robocop/issues/1689)) ([fc6b78d](https://github.com/MarketSquare/robotframework-robocop/commit/fc6b78de9faa3d61acc0a6e9f8424c0cc4333efa))

## [8.1.0](https://github.com/MarketSquare/robotframework-robocop/compare/v8.0.0...v8.1.0) (2026-02-19)


### Features

* Replace `typer-slim` with `typer` ([#1685](https://github.com/MarketSquare/robotframework-robocop/issues/1685)) ([b83400f](https://github.com/MarketSquare/robotframework-robocop/commit/b83400f5727d4a4b82092319401abdf7fba699e8))


### Bug Fixes

* unused-argument rule raised when argument is used in item access or inline eval ([#1687](https://github.com/MarketSquare/robotframework-robocop/issues/1687)) ([d014a53](https://github.com/MarketSquare/robotframework-robocop/commit/d014a53d32b9effe696fccc993f675efb3724941))

## [8.0.0](https://github.com/MarketSquare/robotframework-robocop/compare/v7.2.0...v8.0.0) (2026-02-11)


More detailed notes regarding 8.0.0 [here](8.0.0.md).

### Breaking changes

* dropped support for Python 3.9
* dropped support for Robot Framework 4
* Deprecated ``deprecated-statement`` rule
* Deprecated ``ReplaceReturns`` formatter
* Deprecated ``AddMissingEnd`` formatter
* refactored source files handling with common ``SourceFile`` class
* redesigned configuration layer for typing safety and OOP friendliness

### Features

* Fixable rules (#1617) (128c849)
* deprecate ``deprecated-statement`` rule and split into new rules
* new rule DEPR08 ``deprecated-run-keyword-if``
* new rule DEPR09 ``deprecated-loop-keyword``
* new rule DEPR10 ``deprecated-return-keyword`` (with a fix)
* new rule DEPR11 ``deprecated-return-setting`` (with a fix)
* Robocop is now more verbose
* Keyword naming rules and formatters quotation handling
* performance improvements (#1611) (eea1c56)
* ``report()`` can be now used from the rule class (#1644) (8aff795)
* Robocop is now fully typed (#1661) (42045dc)
* list rules can now return the result when used from the Python (#1629) (457d135)
* MCP is now aware of local config (#1673) (55e18b6)
* Skip documentation by default in NormalizeSeparators (#1672) (5b1ae35)
* Added or improved support for variable type conversion (#1654) (#1650) (#1651) (#1652) #1653)
* New rule ANN04 ``set-keyword-with-type``
* Add ``case_normalization`` parameter to enforce case by RenameKeywords (#1667) (49a0b02)

### Bug fixes

* add explicit typing-extensions dependency (#1680) (b406f25)
* Fix #1174 expression-can-be-simplified raised for == 0 (#1649) (d0f4985)
* Fix #1422 - ReplaceWithVAR formatter replacing variables with item access (#1648) (a9c3377)
* Fix caching the issues with fixes (#1623) (256874b)
* Fix extend-select matching only on rule id, not on rule name (#1669) (403ff7d)
* Fix format --extend-select not enabling formatters (#1668) (3c76c50)
* Fix not all issue format parameters supported by extended output (#1624) (727c38d)
* Fix too-long-variable-name throwing exception on Set X Variable without arguments (#1675) (3a55663)
* multiple paths passed to robocop check/format command resolving to the same config (#1614) (bdcfd48)
* Fix rst-style urls in the documentation (#1640) (eb1dcab)
* Update RenameVariables formatter so it treats numbers as part of word and does not split on it (#1663) (eddfd96)

## [7.2.0](https://github.com/MarketSquare/robotframework-robocop/compare/v7.1.0...v7.2.0) (2026-01-01)


### Features

* **mcp:** add new tools and improve UX for large codebases ([#1601](https://github.com/MarketSquare/robotframework-robocop/issues/1601)) ([9b1d871](https://github.com/MarketSquare/robotframework-robocop/commit/9b1d871a2c40549de1d2f1b707201da47f6c68a6))
* **mcp:** add response caching and error handling middleware ([#1599](https://github.com/MarketSquare/robotframework-robocop/issues/1599)) ([406cfbe](https://github.com/MarketSquare/robotframework-robocop/commit/406cfbefaa229664fdd39e5265f2f47958aabb64))
* **mcp:** enhance MCP server with batch operations, quality metrics, and improved LLM guidance ([#1593](https://github.com/MarketSquare/robotframework-robocop/issues/1593)) ([c6a853b](https://github.com/MarketSquare/robotframework-robocop/commit/c6a853bd016eff8f65742c79c511fd8712abc1a3))
* Refactor print_issues report to gain 3x perfomance gain on printing ([#1605](https://github.com/MarketSquare/robotframework-robocop/issues/1605)) ([6755d96](https://github.com/MarketSquare/robotframework-robocop/commit/6755d96ceadb0b78a80f6e70e5e262967029fde3))


### Bug Fixes

* **caching:** Fix CLI always overriding cache=true/false in the configuration file ([#1608](https://github.com/MarketSquare/robotframework-robocop/issues/1608)) ([b31a5ef](https://github.com/MarketSquare/robotframework-robocop/commit/b31a5ef95c1d706623656aa3f1417730f8c23034))
* **release:** fix triggering Github workflows from automated scripts ([#1594](https://github.com/MarketSquare/robotframework-robocop/issues/1594)) ([72ce0ff](https://github.com/MarketSquare/robotframework-robocop/commit/72ce0ff36aed05eef362aa0aeed80324b2ec7a8e))

## [7.1.0](https://github.com/MarketSquare/robotframework-robocop/compare/v7.0.0...v7.1.0) (2025-12-23)


### Features

* add commented-out-code detection rule (COM06) ([#1564](https://github.com/MarketSquare/robotframework-robocop/issues/1564)) ([8afa9d2](https://github.com/MarketSquare/robotframework-robocop/commit/8afa9d268d4ca909cf56225992962c39a088f8bf))
* add file-level caching for linter and formatter to skip unchanged files ([#1565](https://github.com/MarketSquare/robotframework-robocop/issues/1565)) ([ceb02cc](https://github.com/MarketSquare/robotframework-robocop/commit/ceb02ccff7cf5316ef8debb5040bfa625981eba0))
* add MCP server for AI assistant integration ([#1583](https://github.com/MarketSquare/robotframework-robocop/issues/1583)) ([c68330a](https://github.com/MarketSquare/robotframework-robocop/commit/c68330a34a740e86388ee540327ed6f1d1fe83fb))
* add three separate rules for variable type annotations (RF 7.3+) ([#1579](https://github.com/MarketSquare/robotframework-robocop/issues/1579)) ([03ef483](https://github.com/MarketSquare/robotframework-robocop/commit/03ef483446a153137035c48f8f6e63ce02cca480))
* automate release process with release-please ([#1571](https://github.com/MarketSquare/robotframework-robocop/issues/1571)) ([4bd6d3f](https://github.com/MarketSquare/robotframework-robocop/commit/4bd6d3f5cddaa4c85085ca87b8960720e77d8dd6))
* **VAR02:** add ignore parameter for unused-variable rule ([#1576](https://github.com/MarketSquare/robotframework-robocop/issues/1576)) ([0c2ebf4](https://github.com/MarketSquare/robotframework-robocop/commit/0c2ebf41a2f43f0cb73e586b3e254c02cdfacf7c))


### Bug Fixes

* Invalid Robocop disabler accepted as disabler for all rules ([#1569](https://github.com/MarketSquare/robotframework-robocop/issues/1569)) ([595ffdb](https://github.com/MarketSquare/robotframework-robocop/commit/595ffdb83a3b50ccebf4883493b221076782836b))
* **mcp:** fix limit handling bugs and add enhancements ([#1589](https://github.com/MarketSquare/robotframework-robocop/issues/1589)) ([0926a4d](https://github.com/MarketSquare/robotframework-robocop/commit/0926a4d114b10bdb8a468a472f1105d9a227c645))


### Documentation

* add annotations rule group to documentation ([#1439](https://github.com/MarketSquare/robotframework-robocop/issues/1439)) ([#1588](https://github.com/MarketSquare/robotframework-robocop/issues/1588)) ([50cbfa7](https://github.com/MarketSquare/robotframework-robocop/commit/50cbfa72cd34997ce0a63aeaaa5e109a05f83bb6))
* Add caching documentation ([#1572](https://github.com/MarketSquare/robotframework-robocop/issues/1572)) ([5d941e8](https://github.com/MarketSquare/robotframework-robocop/commit/5d941e849f5ac84a8208b1d21ccdf861006b4cbc))

## 7.0.0

### Features

- **Breaking change** Add option ``--extend-select`` for linter and formatter ([issue #1546](https://github.com/MarketSquare/robotframework-robocop/issues/1546))

    ``--extend-select`` allows to enable rules and formatters on top of the ``select`` configuration. It can be used to
    retain all default rules or formatters and only add additional ones:
    
    ```
    robocop check --extend-select no-embedded-keyword-arguments
    robocop format --extend-select AlignKeywordsSection --extend-select CustomFormatter
    ```

    Since previous ``--custom-formatters`` formatter option already behaved like a ``--extend-select`` option (which was
    not documented), it is now **deprecated and renamed** to ``--extend-select`` instead.

    It is also recommended to use ``--extend-select`` over ``--configue name.enabled=True``.

- **Breaking change** Split ``wrong-case-in-keyword-name`` rule into two separate rules ([issue #1471](https://github.com/MarketSquare/robotframework-robocop/issues/1471)):

    ``wrong-case-in-keyword-name`` which checks case convention in keyword definition name
    ``wrong-case-in-keyword-call`` which checks case convention in keyword call name

    It allows configuring different conventions for keyword definition and keyword call names. If you have existing
    configuration for ``wrong-case-in-keyword-name`` (you are ignoring it or configuring) you need to apply the same
    config to ``wrong-case-in-keyword-call`` to retain old behaviour.

- ``SplitTooLongLine`` can now split more settings types: Library imports, Test Tags and Keyword Tags ([issue #1454](https://github.com/MarketSquare/robotframework-robocop/issues/1454))

    Example code before and after the change:

    ```robotframework
    Library    CustomLibraryWithLongerNameAndSeveralArguments    first_argument    second_argument=${longer_variable_name}    WITH NAME    name
    ```

    ```robotframework
    Library             CustomLibraryWithLongerNameAndSeveralArguments
    ...                     first_argument
    ...                     second_argument=${longer_variable_name}
    ...                 WITH NAME    name
    ```

- Restore project checkers ([issue #1108](https://github.com/MarketSquare/robotframework-robocop/issues/1108))

    Project checkers were temporarily removed in the Robocop 6.0. There are now brought back in a new form, as a separate
    command:

    ```
    robocop check-project
    ```

    This command behaves similarly to the ``check`` command, but it only runs project rules.

    The project checks itself were also refactored to be more flexible. See [project checker](https://robocop.dev/stable/linter/linter/#project-checks)
    and [custom rules project checker](https://robocop.dev/stable/linter/custom_rules/#project-checks) for reference.

- Extend robocop disablers to the whole node ([issue #1515](https://github.com/MarketSquare/robotframework-robocop/issues/1515)

    Robocop will now ignore issues in the whole node (keyword, test case, for loop, keyword call, etc.) when the disabler
    is set in the header / keyword call body. For example:

    ```robotframework
    *** Keywords ***
    My Keyword  
        FOR    ${var}    IN    1  2  3  # robocop: off=unused-variable
             Log    1
        END
        Keyword    # robocop: off=bad-indent
        ...    ${var}
        ...    ${var2}
    ```

    Previously, Robocop would ignore ``unused-variable`` only when reported on the ``FOR`` header and ``bad-indent`` only
    when reported on the same line as disabler comment. After this change, those issues will be ignored in the whole
    FOR loop and the whole ``Keyword`` call respectively.

- Ignore unused variables starting with ``_`` (``${_variable}``) ([issue #1457](https://github.com/MarketSquare/robotframework-robocop/issues/1457)

### Fixes

- Fix ``unused-variable`` and ``variable-overwritten-before-usage`` rules not reporting violations in ``TRY`` blocks ([issue #1548](https://github.com/MarketSquare/robotframework-robocop/issues/1548))
- Fix ``wrong-case-in-keyword-call`` rule false positive report on names with ``.`` character with first_word_capitalized = True ([issue #1555](https://github.com/MarketSquare/robotframework-robocop/issues/1555))
- Fix ``wrong-case-in-keyword-name`` rule incorrectly handling names with ``.`` character ([issue #1555](https://github.com/MarketSquare/robotframework-robocop/issues/1555))

### Documentation

- Added documentation linters (with MegaLinter) and fixed several issues in our documentation.

## 6.13.0

### Features

- Add ``per_file_ignores`` option to ignore rules matching file patterns ([issue #1134](https://github.com/MarketSquare/robotframework-robocop/issues/1134))

Example configuration:

```toml
[tool.robocop.lint.per_file_ignores]
"test.robot" = ["VAR02"]
"ignore_subdir/*" = ["empty-line-after-section", "DOC01"]
"ignore_file_in_subpath/test2.robot" = ["SPC10"]
```

- Allow manually disabling reports with ``enabled=False``. It can be used to disable default ``print_issues`` report ([issue #1540](https://github.com/MarketSquare/robotframework-robocop/issues/1540))
- Add ``docs_url`` property to rule class which points to rule documentation URL ([issue #1432](https://github.com/MarketSquare/robotframework-robocop/issues/1432))

### Fixes

- Fix piping output (``robocop check > output.txt``) not working on Windows because of code lines converted to emojis ([issue #1539](https://github.com/MarketSquare/robotframework-robocop/issues/1539))
- Fix configuration file loaded from the root directory with ``--ignore-file-config`` option enabled (other configuration files were correctly ignored)

### Documentation

- Describe how to extend the Robocop Rule class using ``docs_url`` as an example ([here](https://robocop.dev/stable/linter/custom_rules/#change-rule-class-behaviour)).

## 6.12.0

### Features

- Add ``extends`` configuration parameter which allows inheriting configuration from another file ([issue #1453](https://github.com/MarketSquare/robotframework-robocop/issues/1453))
- Change ``mixed-tabs-and-spaces`` (SPC06) rule behaviour to report all occurrences of mixed tabs and spaces in a file ([issue #848](https://github.com/MarketSquare/robotframework-robocop/issues/848))
-  ``format_files`` (robocop API entrypoint for formatting files) now accepts ``return_result`` parameter for returning exit code instead of raising SystemExit
- ``RenameVariables`` not longer replaces spaces in variable names with the math operators ([issue #1428](https://github.com/MarketSquare/robotframework-robocop/issues/1428))

### Fixes

- Fix ``AlignKeywordsSection`` and ``AlignTestCasesSection`` not aligning VAR variables ([issue #1493](https://github.com/MarketSquare/robotframework-robocop/issues/1493))
- Fix optional ``no-embedded-keyword-arguments`` rule fatal exception when reading a file with invalid syntax
- Fix the empty configuration file causing Robocop to fail ([issue #1536](https://github.com/MarketSquare/robotframework-robocop/issues/1536))

### Documentation

- Add ``deprecated names`` section to all the rules that list previous names and ids of the rule

## 6.11.0

### Features

- Add ``--silent`` option to disable all output when running Robocop ([issue #1512](https://github.com/MarketSquare/robotframework-robocop/issues/1512))
- Improve startup performance of the Robocop (using a Robocop repository as a benchmark: from 5s to 0.3s). It was done
  by fixing issues in handling ignored files and by properly caching configuration files (to avoid multiple lookups).
  The difference may be noticeable only for the large, complex projects ([issue #1503](https://github.com/MarketSquare/robotframework-robocop/issues/1503))

### Fixes

- Fix directories from the ``.gitignore`` file not ignored ([issue #1503](https://github.com/MarketSquare/robotframework-robocop/issues/1503))
- Fix ``migrate`` command migrating formatters with ``enabled=False`` from the old transform to select option ([issue #1492](https://github.com/MarketSquare/robotframework-robocop/issues/1492))
- Fix ``migrate`` command not splitting multiline configurations ([issue #1491](https://github.com/MarketSquare/robotframework-robocop/issues/1491))
- Fix multiline inline IF splitting. To avoid issues when formatting such code, **all inline IFs are now flattened to a single line** ([issue #1506](https://github.com/MarketSquare/robotframework-robocop/issues/1506)):

```robotframework
*** Test Cases ***
Multiline inline IF
    IF    True
    ...    Something
```

becomes:

```robotframework
*** Test Cases ***
Multiline inline IF
    IF    True    Something
```
- Fix ``enabled`` formatter parameter not validating as a boolean ([issue #1476](https://github.com/MarketSquare/robotframework-robocop/issues/1476))

### Documentation

- Mark disabled rules in the documentation (previously they were not distinguishable from the enabled rules) ([issue #1518](https://github.com/MarketSquare/robotframework-robocop/issues/1518))
- Add two new sections to the documentation:
  - [Python API Reference](https://robocop.dev/stable/user_guide/python_api/)
  - [AI integration](https://robocop.dev/stable//integrations/ai/)

## 6.10.1

### Fixes

- Fix ``verbose``, ``force_exclude`` and ``skip_gitignore`` options not supported in the configuration file

### Documentation

- Fix incorrect code examples in the documentation.

## 6.10.0

### Documentation

Release a new documentation website.

Rewrite of our documentation from Sphinx to MkDocs, now hosted at https://robocop.dev.

## 6.9.2

### Fixes

- Fix invalid Robot Framework dependency version range

## 6.9.1

### Fixes

- Fix invalid rule positions stopping Sonar Qube import ([issue #1417](https://github.com/MarketSquare/robotframework-robocop/issues/1417))
End-to-end testing of Sonar Qube issue imports revealed multiple problems with diagnostic positioning.
All problematic rules included an incorrect offset of 1. The following rules have been corrected:

- ``invalid-setting-in-resource`` (ERR16)
- ``unreachable-code`` (MISC10)
- ``keyword-name-is-reserved-word`` (NAME03)
- ``invalid-section`` (NAME16)

## 6.9.0

### Documentation

Rule documentation now contains information about deprecated names. It is especially helpful during migration to
Robocop 6.0 or comparing results between old and new Robocop reports.

## 6.8.3

### Fixes

- Fix Robocop failing to scan directory with dangling symlink ([issue #1494](https://github.com/MarketSquare/robotframework-robocop/issues/1494))

Robocop should be able to scan a directory with dangling (pointing to a non-existing path) symlink.

## 6.8.2

### Fixes

- Fix comment handling in Set Variable If with ReplaceWithVAR formatter ([issue #1495](https://github.com/MarketSquare/robotframework-robocop/issues/1495))

``ReplaceWithVAR`` no longer abruptly stops when converting ``Set Variable If`` with comments to ``VAR``.

## 6.8.1

### Fixes

- Fix Python 3.14 compatibility issues, where Robocop disabled 1/3 of the rules.

## 6.8.0

### Features

- Add a new rule: unused disabler rule ([issue #1312](https://github.com/MarketSquare/robotframework-robocop/issues/1312))

A new rule ``unused-disabler`` (MISC15) has been added to detect Robocop disabler directives (such as ``# noqa`` or
``# robocop: off``) that are not being used. This typically occurs when:

- A code violation is fixed, but the disabler is not removed
- A rule is disabled globally, making local disablers redundant
- Multiple overlapping disablers are present

- Improved comment handling in SplitTooLongLine formatter ([issue #1444](https://github.com/MarketSquare/robotframework-robocop/issues/1444))

The ``SplitTooLongLine`` formatter now has better comment handling.

**Previous behavior:**

When formatting keyword call or ``VAR`` by ``SplitTooLongLine`` formatter, comments were moved above the statement,
for example:

```
Long Keyword That Will Be Split    multiple   args  # comment
```

Was formatted to:

```
# comment
Long Keyword That Will Be Split
...    multiple
...    args
```

This caused unindented effect where robocop disabler directives (e.g. ``# robocop: off``) were also moved above the
statement and no longer applied correctly.

**New behavior:**

Comments are now kept on the first line of the split statement:

```
Long Keyword That Will Be Split  # comment
...    multiple
...    args
```

This ensures that disablers and other comments remain associated with the correct statement.

- Disablers are discoverable anywhere in comments

Disabler directives can now be placed anywhere within a comment, not just at the beginning.

**Previous behavior:**

Only the first disabler at the start of a comment was recognised:

```
# only robocop: off=some-rule is recognized
Keyword Call  # robocop: off=some-rule robocop: fmt: off

# only noqa is recognized
Keyword Call  # noqa robocop fmt: off

# nothing is recognized
Keyword Call  # TODO: robocop: off
```

**New behavior:**

All disablers are now recognised regardless of their position in the comment. Additionally, the syntax is more
flexible and rules can be separated by commas with or without spaces:

```
# Both formats are now valid:
# robocop: off=rule1,rule2
# robocop: off=rule1, rule2
```

### Fixes

- Fix overwrite mode not working from the configuration file ([issue #1478](https://github.com/MarketSquare/robotframework-robocop/issues/1478))

Fixed an issue where the ``overwrite`` mode was not being applied when specified in the configuration file. The
following configuration now works correctly:

```toml
[tool.robocop.format]
overwrite = false
```

- Fix rules url pointing to a non-existing location ([issue #1481](https://github.com/MarketSquare/robotframework-robocop/issues/1481))

Rules urls (such as SARIF helpUri, or diagnostic message urls) were pointing to non-existent locations after a
documentation refactor. URLs now correctly point to:

https://robocop.readthedocs.io/en/v{version}/rules/rules_list.html#{rule-name} .

- Fix line too long rule reporting lines with new disablers

New disabler directives (``robocop: fmt: off`` and ``fmt: off``) were not ignored by ``line-too-long`` rule.

From now on, together with other disablers, comments with disablers will be ignored when checking line length.
