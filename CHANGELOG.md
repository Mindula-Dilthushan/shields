# Changelog

Note: this changelog is for the shields.io server. The changelog for the badge-maker NPM package is at https://github.com/badges/shields/blob/master/badge-maker/CHANGELOG.md

---

## server-2025-02-01

- Changelog for Release server-2024-09-02 [#10490](https://github.com/badges/shields/issues/10490)
- Publish linux/amd64 docker images for snapshot builds only [#10476](https://github.com/badges/shields/issues/10476)
- Fix Gitea not having credentials/authorizedOrigins in Docker environments [#10486](https://github.com/badges/shields/issues/10486)
- Revert "Add Platform linux/arm64 to Docker Build (#10441)" [#10477](https://github.com/badges/shields/issues/10477)
- fix typo in pepy downloads [#10475](https://github.com/badges/shields/issues/10475)
- Add Platform linux/arm64 to Docker Build [#10441](https://github.com/badges/shields/issues/10441)
- ignore a couple of docusaurus warnings [#10469](https://github.com/badges/shields/issues/10469)
- Use Ecologi API to power Treeware badges [#10467](https://github.com/badges/shields/issues/10467)
- un-pin buildx version [#10453](https://github.com/badges/shields/issues/10453)
- move go version badge to platform support category [#10444](https://github.com/badges/shields/issues/10444)
- remove libraries we don't need in docker build [#10443](https://github.com/badges/shields/issues/10443)
- [Crates] Implement Dependents Badge [#10438](https://github.com/badges/shields/issues/10438)
- [Crates] Added crate size badge [#10421](https://github.com/badges/shields/issues/10421)
- Fix branch in [Bitrise] tests [#10439](https://github.com/badges/shields/issues/10439)
- Changelog for Release server-2024-08-01 [#10424](https://github.com/badges/shields/issues/10424)
- send Cross-Origin-Resource-Policy header on all responses [#10420](https://github.com/badges/shields/issues/10420)
- migrate [MozillaObservatory] to new API [#10402](https://github.com/badges/shields/issues/10402)
- use metric() for [discord] and [revolt] badges [#10406](https://github.com/badges/shields/issues/10406)
- remove reference to CircleCI [#10405](https://github.com/badges/shields/issues/10405)
- Cache text only static badges for longer [#10403](https://github.com/badges/shields/issues/10403)
- update [pub] points service test [#10398](https://github.com/badges/shields/issues/10398)
- update [pypi] license test example [#10399](https://github.com/badges/shields/issues/10399)
- update [PythonVersionFromToml] test example [#10400](https://github.com/badges/shields/issues/10400)
- Fix [FreeCodeCampPoints] not found handling [#10377](https://github.com/badges/shields/issues/10377)
- Fix [Gerrit] new change test [#10376](https://github.com/badges/shields/issues/10376)
- Fix [AmoVersion] test [#10375](https://github.com/badges/shields/issues/10375)
- Fix [EcologiCarbonOffset] test [#10374](https://github.com/badges/shields/issues/10374)
- Fix [Gitea] not found message [#10373](https://github.com/badges/shields/issues/10373)
- Mock [JenkinsCoverage] Cobertura job found test [#10372](https://github.com/badges/shields/issues/10372)
- Deprecate [Bountysource] service [#10371](https://github.com/badges/shields/issues/10371)
- Sunsetting Shields custom logos [#10347](https://github.com/badges/shields/issues/10347)
- Use ellipsis when many versions returned for [ModrinthGameVersions] [#10350](https://github.com/badges/shields/issues/10350)
- Cleanup unused bits and pieces [#10349](https://github.com/badges/shields/issues/10349)
- Update daily tests reference in README [#10348](https://github.com/badges/shields/issues/10348)
- Update c8 configuration [#10361](https://github.com/badges/shields/issues/10361)
- deprecate [tokei] service [#9581](https://github.com/badges/shields/issues/9581)
- Add code coverage action [#10340](https://github.com/badges/shields/issues/10340)
- Update badges in README [#10341](https://github.com/badges/shields/issues/10341)
- Remove unused parameters in [Chocolatey Resharper PowershellGallery] [#10345](https://github.com/badges/shields/issues/10345)
- Add CF-Ray header value to Sentry errors if available [#10339](https://github.com/badges/shields/issues/10339)
- Use XML for Chocolatey, affects [Chocolatey Resharper PowershellGallery] [#10344](https://github.com/badges/shields/issues/10344)
- include gituhb contributors badge in docs site [#10337](https://github.com/badges/shields/issues/10337)
- run full test suite daily [#10320](https://github.com/badges/shields/issues/10320)
- Changelog for Release server-2024-07-01 [#10318](https://github.com/badges/shields/issues/10318)
- Add [AUR] Popularity Badge [#10304](https://github.com/badges/shields/issues/10304)
- fix npm badges when `maintainers` not in response [#10286](https://github.com/badges/shields/issues/10286)
- Expose `logoBase64` and `links` in badge-maker NPM package [#10283](https://github.com/badges/shields/issues/10283)
- Remove `logoPosition` [#10284](https://github.com/badges/shields/issues/10284)
- [MBIN] Add subscribers badge [#10270](https://github.com/badges/shields/issues/10270)
- Improve Docusaurus Dependabot setup [#10262](https://github.com/badges/shields/issues/10262)
- Update documentation and tests to [docsrs] [#10240](https://github.com/badges/shields/issues/10240)
- Add [Docker] support for loong64 arch [#10241](https://github.com/badges/shields/issues/10241)
- simpleicons 12 blog [#10222](https://github.com/badges/shields/issues/10222)
- Add puppetforge quality score badges [#10201](https://github.com/badges/shields/issues/10201)
- Fix [GithubPullRequestCheckState] test [#10200](https://github.com/badges/shields/issues/10200)
- Switch Cobertura job URL [#10217](https://github.com/badges/shields/issues/10217)
- Fully mock flaky [CodeClimate] multi-step tests [#10218](https://github.com/badges/shields/issues/10218)
- Update Changelog [#10215](https://github.com/badges/shields/issues/10215)
- Remove namedLogo from defaultBadgeData of non-social badges [#10195](https://github.com/badges/shields/issues/10195)
- Update number of badges served each month [#10197](https://github.com/badges/shields/issues/10197)
- Delete old deprecated services [#10196](https://github.com/badges/shields/issues/10196)
- handle [BitbucketPipelines] responses with missing result key [#10163](https://github.com/badges/shields/issues/10163)
- Update description of GitHub commit status badge [#10198](https://github.com/badges/shields/issues/10198)
- chore: fix spelling of GitHub in badge descriptions [#10199](https://github.com/badges/shields/issues/10199)
- Add [GithubCheckRuns] service [#7759](https://github.com/badges/shields/issues/7759)
- feat: add Revolt badge [#10093](https://github.com/badges/shields/issues/10093)
- ensure color is string before calling toLowerCase() [#10129](https://github.com/badges/shields/issues/10129)
- instruct dependabot to monitor composite actions [#10139](https://github.com/badges/shields/issues/10139)
- run tests on node 22 [#10127](https://github.com/badges/shields/issues/10127)
- tweaks to libraries.io token pooling code [#10074](https://github.com/badges/shields/issues/10074)
- fix [pypi] status badge when package has no 'Development Status' classifier [#10107](https://github.com/badges/shields/issues/10107)
- clarify yml paths in server-secrets docs [#10106](https://github.com/badges/shields/issues/10106)
- Update region flag name in flyctl deploy command [#10134](https://github.com/badges/shields/issues/10134)
- Changelog for Release server-2024-05-01 [#10131](https://github.com/badges/shields/issues/10131)
- improve performance of getIconSize() [#10125](https://github.com/badges/shields/issues/10125)
- [Hexpm] Fix badges for pre-release only versions [#10112](https://github.com/badges/shields/issues/10112)
- add logoSize to globalQueryParams [#10110](https://github.com/badges/shields/issues/10110)
- feat(logos): support auto-sizing mode [#9191](https://github.com/badges/shields/issues/9191)
- support setting pypiBaseUrl by environment variables and queryParameters; affects [pypi] [#10044](https://github.com/badges/shields/issues/10044)
- upgrade @docusaurus/core and docusaurus-openapi [#10108](https://github.com/badges/shields/issues/10108)
- Add 0BSD license to licenseTypes and [PypiLicense] [#10092](https://github.com/badges/shields/issues/10092)
- Update Mastodon profile URL [#10082](https://github.com/badges/shields/issues/10082)
- [GitHubGoMod] Ignore comment after version (fixes #10079) [#10080](https://github.com/badges/shields/issues/10080)
- Revert "chore(deps): bump simple-icons from 11.10.0 to 11.11.0 (#10068)" [#10075](https://github.com/badges/shields/issues/10075)
- Perf: Librariesio repo dependencies [#10062](https://github.com/badges/shields/issues/10062)
- [Chocolatey Nuget] Fix "not found" error for chocolatey badge [#10060](https://github.com/badges/shields/issues/10060)
- Changelog for Release server-2024-04-01 [#10057](https://github.com/badges/shields/issues/10057)
- improve performance of [GithubLastCommit] [GitlabLastCommit] [GiteaLastCommit] [#10046](https://github.com/badges/shields/issues/10046)
- [BitbucketLastCommit] Add Bitbucket last commit [#10043](https://github.com/badges/shields/issues/10043)
- [GithubLastCommit] [GitlabLastCommit] [GiteaLastCommit] Support file path for last commit [#10041](https://github.com/badges/shields/issues/10041)
- upgrade to docusaurus 3 [#9820](https://github.com/badges/shields/issues/9820)
- redirect [npm] /dt to /d18m [#10033](https://github.com/badges/shields/issues/10033)
- Add [JSR] version service [#10030](https://github.com/badges/shields/issues/10030)
- Add [snapcraft] version badge [#9976](https://github.com/badges/shields/issues/9976)
- Changelog for Release server-2024-03-01 [#9998](https://github.com/badges/shields/issues/9998)
- feat(gitea): add last commit badge [#9995](https://github.com/badges/shields/issues/9995)
- [GithubCreatedAt] Add Created At Badge for Github [#9981](https://github.com/badges/shields/issues/9981)
- Added custom bucket url support for [Scoop] [#9984](https://github.com/badges/shields/issues/9984)
- randomize tokens on token pool init [#9980](https://github.com/badges/shields/issues/9980)
- Complete the examples --> openApi migration; affects [node sonar travis wordpress visualstudio librariesio] [#9977](https://github.com/badges/shields/issues/9977)
- Improve our approach for testing auth (part 1) [#9681](https://github.com/badges/shields/issues/9681)
- [NpmUnpackedSize] Unpacked Size Badge [#9954](https://github.com/badges/shields/issues/9954)
- [Website] Render `status: down` badge if website is unresponsive [#9966](https://github.com/badges/shields/issues/9966)
- deprecate TAS [#9932](https://github.com/badges/shields/issues/9932)
- migrate examples to openApi part 37; affects [bitbucket bitrise chromewebstore circleci] [#9881](https://github.com/badges/shields/issues/9881)
- migrate some services from examples to openApi part 46; affects [codeclimate librariesio nexus] and securityheaders [#9933](https://github.com/badges/shields/issues/9933)
- [GITEA] add forks, stars, issues and pr badges [#9923](https://github.com/badges/shields/issues/9923)
- migrate some services from examples to openApi part 45; affects [github coveralls visualstudiomarketplace] [#9930](https://github.com/badges/shields/issues/9930)
- migrate some services from examples to openApi part 47; affects [docker] [#9934](https://github.com/badges/shields/issues/9934)
- tolerate missing short_version in [visualstudioappcenter] [#9951](https://github.com/badges/shields/issues/9951)
- [Crates] Only use non-yanked crate versions (ready for merge) [#9949](https://github.com/badges/shields/issues/9949)
- migrate some services from examples to openApi part 44; affects [sonar] [#9919](https://github.com/badges/shields/issues/9919)
- migrate some services from examples to openApi part 43; affects [jenkins] [#9918](https://github.com/badges/shields/issues/9918)
- use brightgreen for build passing in package docs [#9917](https://github.com/badges/shields/issues/9917)
- Changelog for Release server-2024-02-01 [#9935](https://github.com/badges/shields/issues/9935)
- migrate some services from examples to openApi [#9904](https://github.com/badges/shields/issues/9904)
- migrate some services from examples to openApi [#9915](https://github.com/badges/shields/issues/9915)
- migrate some services from examples to openApi part 39; affects [maven gradle] [#9902](https://github.com/badges/shields/issues/9902)
- migrate some services from examples to openApi [#9903](https://github.com/badges/shields/issues/9903)
- feat: added up_message and down_message to [uptimerobotstatus] [#9662](https://github.com/badges/shields/issues/9662)
- Add [Hangar] Badges [#9800](https://github.com/badges/shields/issues/9800)
- migrate examples to openApi part 38; affects [github] [#9889](https://github.com/badges/shields/issues/9889)
- [crates] tidyup [#9883](https://github.com/badges/shields/issues/9883)
- small docs fix: defs --> prestart [#9887](https://github.com/badges/shields/issues/9887)
- sort categories by title (except core) [#9888](https://github.com/badges/shields/issues/9888)
- Add Support for [Nostr] Followers [#9870](https://github.com/badges/shields/issues/9870)
- replace experimental API usage with newly available v1 API [#9886](https://github.com/badges/shields/issues/9886)
- Update [Gitea] defaults to gitea.com [#9872](https://github.com/badges/shields/issues/9872)
- [crates] MSRV Badge [#9871](https://github.com/badges/shields/issues/9871)
- migrate examples to openApi part 35; affects [npm] [#9866](https://github.com/badges/shields/issues/9866)
- migrate examples to openApi part 36; affects [myget nuget resharper chocolatey powershellgallery] [#9873](https://github.com/badges/shields/issues/9873)
- Add [galaxytoolshed] Version [#8249](https://github.com/badges/shields/issues/8249)
- fix default style docs for social badges [#9869](https://github.com/badges/shields/issues/9869)
- migrate examples to openApi part 34; affects [github] [#9865](https://github.com/badges/shields/issues/9865)
- Fix typo in OpenAPI service documentation [#9868](https://github.com/badges/shields/issues/9868)
- migrate examples to openApi part 33; affects [bower drone localizely mozillaobservatory pythonversionfromtoml] [#9864](https://github.com/badges/shields/issues/9864)
- migrate some services from examples to openApi part 31; affects [packagecontrol discourse] [#9858](https://github.com/badges/shields/issues/9858)
- migrate some services from examples to openApi [#9857](https://github.com/badges/shields/issues/9857)
- Changelog for Release server-2024-01-01 [#9863](https://github.com/badges/shields/issues/9863)
- migrate some services from examples to openApi [#9856](https://github.com/badges/shields/issues/9856)
- migrate examples to openApi part 32; affects [azuredevops youtube] [#9861](https://github.com/badges/shields/issues/9861)
- call [docker] with auth [#9803](https://github.com/badges/shields/issues/9803)
- migrate some services from examples to openApi part 28; affects [aur cran mastodon matrix npmstat nyc thunderstore twitter] [#9855](https://github.com/badges/shields/issues/9855)
- Ensure social category badges are rendered with social style and logo; affects [gitlab keybase lemmy modrinth thunderstore twitch] gist github reddit [#9859](https://github.com/badges/shields/issues/9859)
- deploy on node 20 [#9799](https://github.com/badges/shields/issues/9799)
- Small [YouTube] cleanup [#9860](https://github.com/badges/shields/issues/9860)
- add description to interval enums [#9854](https://github.com/badges/shields/issues/9854)
- convert 'style' param to enum [#9853](https://github.com/badges/shields/issues/9853)
- increase page size for github release badge by semver [#9818](https://github.com/badges/shields/issues/9818)
- migrate examples to openApi part 26; affects [gitlab] [#9752](https://github.com/badges/shields/issues/9752)
- migrate some services from examples to openApi [#9841](https://github.com/badges/shields/issues/9841)
- migrate some services from examples to openApi [#9737](https://github.com/badges/shields/issues/9737)
- migrate examples to openApi part 23; affects [wordpress] [#9732](https://github.com/badges/shields/issues/9732)
- Fix typo in queryParams documentation [#9840](https://github.com/badges/shields/issues/9840)
- migrate some services from examples to openApi [#9749](https://github.com/badges/shields/issues/9749)
- migrate examples to openApi part 18; affects [conda feedz gem openvsx readthedocs] github [#9607](https://github.com/badges/shields/issues/9607)
- migrate some services from examples to openApi [#9716](https://github.com/badges/shields/issues/9716)
- migrate some services from examples to openApi [#9731](https://github.com/badges/shields/issues/9731)
- migrate examples to openApi part 20: TUTORIAL.md [#9713](https://github.com/badges/shields/issues/9713)
- link to mterczynski.pl/joi-schema-generator in validation docs [#9700](https://github.com/badges/shields/issues/9700)
- [Thunderstore] Add Thunderstore Badges [#9782](https://github.com/badges/shields/issues/9782)
- migrate examples to openApi part 19; affects [azuredevops codacy greasyfork jenkinsplugininstalls jetbrains osslifecycle travis visualstudio] and librariesio, uptimerobot [#9610](https://github.com/badges/shields/issues/9610)
- migrate examples to openApi part 17; affects [buildkite cii codeship crates jsdelivr npms] and bundlephobia [#9584](https://github.com/badges/shields/issues/9584)
- Add [Raycast] Badge [#9801](https://github.com/badges/shields/issues/9801)
- [GITEA] add new gitea service (release/languages) [#9781](https://github.com/badges/shields/issues/9781)
- improve documentation for [dynamicxml] service [#9798](https://github.com/badges/shields/issues/9798)
- Add [NpmStatDownloads] Badge [#9783](https://github.com/badges/shields/issues/9783)
- [pub] Use official version endpoint for pub-service [#9802](https://github.com/badges/shields/issues/9802)
- fix typo in docs [#9804](https://github.com/badges/shields/issues/9804)
- stop linking to twitter [#9685](https://github.com/badges/shields/issues/9685)
- cache weblate badges for longer [#9786](https://github.com/badges/shields/issues/9786)
- [Discourse] Update schema keys to use plural form (`topic_count` -> `topics_count`) [#9778](https://github.com/badges/shields/issues/9778)
- cache some badges for longer [#9785](https://github.com/badges/shields/issues/9785)
- log 429s to sentry (attempt 2); affects [dynamic endpoint uptimerobot weblate opencollective discord github] [#9546](https://github.com/badges/shields/issues/9546)
- migrate examples to openApi part 15; affects [pingpong polymart spiget] [#9561](https://github.com/badges/shields/issues/9561)
- migrate examples to openApi part 14; affects [azuredevops discord netlify opencollective pub ros visualstudio] [#9560](https://github.com/badges/shields/issues/9560)
- migrate examples to openApi part 13; affects [curseforge date fedora hsts modrinth ore] [#9499](https://github.com/badges/shields/issues/9499)
- Changelog for Release server-2023-12-04 [#9779](https://github.com/badges/shields/issues/9779)
- update website docs, migrate examples to openapi [#9612](https://github.com/badges/shields/issues/9612)
- move from @renovate/pep440 to @renovatebot/pep440 [#9614](https://github.com/badges/shields/issues/9614)
- deprecate/fix [ansible] galaxy services [#9648](https://github.com/badges/shields/issues/9648)
- call [pepy] with auth [#9748](https://github.com/badges/shields/issues/9748)
- fix [GitHubCommitActivity] service tests [#9736](https://github.com/badges/shields/issues/9736)
- migrate examples to openApi part 12; affects [GitHub Gist] [#9500](https://github.com/badges/shields/issues/9500)
- add meaningful descriptions including keywords [#9715](https://github.com/badges/shields/issues/9715)
- Changelog for Release server-2023-11-01 [#9705](https://github.com/badges/shields/issues/9705)
- migrate examples to openApi part 16; affects [gitlabrelease swagger] [#9565](https://github.com/badges/shields/issues/9565)
- twitter --> X [#9678](https://github.com/badges/shields/issues/9678)
- fix greasyfork 404 bug [#9632](https://github.com/badges/shields/issues/9632)
- Fix several typos [#9658](https://github.com/badges/shields/issues/9658)
- Hacktoberfest 2023 support - resolves #9636 [#9637](https://github.com/badges/shields/issues/9637)
- switch to fixed OpenCollective images [#9615](https://github.com/badges/shields/issues/9615)
- Changelog for Release server-2023-10-02 [#9635](https://github.com/badges/shields/issues/9635)
- add python package total downloads from [pepy] badge [#9564](https://github.com/badges/shields/issues/9564)
- sync docusaurus plugin versions [#9608](https://github.com/badges/shields/issues/9608)
- migrate examples to openApi part 10 [#9466](https://github.com/badges/shields/issues/9466)
- migrate examples to openApi part 9; affects [bowerlicense conda freecodecamp galaxytoolshed jenkins-plugin npmtypedefinitions puppetforge] [#9465](https://github.com/badges/shields/issues/9465)
- fix review apps [#9582](https://github.com/badges/shields/issues/9582)
- deprecate [redmine] plugin rating badges [#9568](https://github.com/badges/shields/issues/9568)
- fix mismatch in documentation and examples given in tutorial [#9580](https://github.com/badges/shields/issues/9580)
- fix [aur] service tests [#9566](https://github.com/badges/shields/issues/9566)
- fix [bower] version badge [#9567](https://github.com/badges/shields/issues/9567)
- Add [PythonVersionFromToml] shield [#9516](https://github.com/badges/shields/issues/9516)
- Add [dub] score badge service [#9549](https://github.com/badges/shields/issues/9549)
- Changelog for Release server-2023-09-04 [#9548](https://github.com/badges/shields/issues/9548)
- migrate examples to openApi part 7; affects [reuse sourceforge sourcegraph spack stackexchange testspace treeware twitch] [#9464](https://github.com/badges/shields/issues/9464)
- Fix [testspace] badges [#9525](https://github.com/badges/shields/issues/9525)
- fix rSt code example [#9528](https://github.com/badges/shields/issues/9528)
- Point to security policy in README [#9544](https://github.com/badges/shields/issues/9544)
- Fix commands injection in Github workflow [#9542](https://github.com/badges/shields/issues/9542)
- migrate examples to openApi part 8; affects [ubuntu uptimerobot vaadin vcpkg visualstudiomarketplace wheelmap] [#9463](https://github.com/badges/shields/issues/9463)
- Add dynamic TOML support via [DynamicToml] Service [#9517](https://github.com/badges/shields/issues/9517)
- migrate `examples` to `openApi` part 11: enums; affects [codefactor conda depfu homebrew jsdelivr reddit sourceforge testspace vaadin github] [#9437](https://github.com/badges/shields/issues/9437)
- Revert "log an error to sentry if an upstream service responds with `429 Too Many Requests` (#9505)" [#9523](https://github.com/badges/shields/issues/9523)
- cache [pypi] downloads for longer [#9522](https://github.com/badges/shields/issues/9522)
- log an error to sentry if an upstream service responds with `429 Too Many Requests` [#9505](https://github.com/badges/shields/issues/9505)
- Docs: update TUTORIAL.md add BaseTomlService [#9518](https://github.com/badges/shields/issues/9518)
- Replace localhost with domain in example link. [#9506](https://github.com/badges/shields/issues/9506)
- [twitter] --> x [#9496](https://github.com/badges/shields/issues/9496)
- use defaultBadgeData as object instead of function in tutorial docs [#9502](https://github.com/badges/shields/issues/9502)
- add docstrings for website status service [#9495](https://github.com/badges/shields/issues/9495)
- migrate `examples` to `openApi` part5; affects [itunes jetbrains jitpack keybase lemmy luarocks maintenance openvsx] [#9431](https://github.com/badges/shields/issues/9431)
- migrate `examples` to `openApi` part 4; affects [ecologi elm flathub gem gitter GithubTotalDiscussions greasyfork hackage hackernews homebrew] [#9430](https://github.com/badges/shields/issues/9430)
- [bundlejs] add badge for the npm package size [#9055](https://github.com/badges/shields/issues/9055)
- Switch [OpenCollective] badges to use GraphQL and auth [#9387](https://github.com/badges/shields/issues/9387)
- migrate examples to openApi part 6; affects [opencollective opm ossf powershell pub pypi reddit repology] [#9462](https://github.com/badges/shields/issues/9462)
- devops: Add ci warning for swizzled docusaurus components [#9467](https://github.com/badges/shields/issues/9467)
- migrate `examples` to `openApi` part 3; affects [conan cookbook coverity cpan debian docker docsrs dub eclipse] [#9429](https://github.com/badges/shields/issues/9429)
- Add TOML support with BaseTomlService [#9438](https://github.com/badges/shields/issues/9438)
- [Pulsar] Add Pulsar Badges for Stargazers & Downloads [#8767](https://github.com/badges/shields/issues/8767)
- Add [CurseForge] badges [#9252](https://github.com/badges/shields/issues/9252)
- update npm prune command [#9470](https://github.com/badges/shields/issues/9470)
- remove obsolete entries from dependabot.yml [#9469](https://github.com/badges/shields/issues/9469)
- output DockerHub digest in publish-docker-next workflow [#9471](https://github.com/badges/shields/issues/9471)
- delete close-bot [#9468](https://github.com/badges/shields/issues/9468)
- Add docstrings for version service [#9411](https://github.com/badges/shields/issues/9411)
- deploy on node 18 [#9385](https://github.com/badges/shields/issues/9385)
- migrate `examples` to `openApi` part 2; affects [archlinux bitcomponents bountysource cdnjs chrome clearlydefined clojars cocoapods coincap] [#9428](https://github.com/badges/shields/issues/9428)
- allow calling [github] without auth [#9427](https://github.com/badges/shields/issues/9427)
- fix [github] service tests [#9425](https://github.com/badges/shields/issues/9425)
- Changelog for Release server-2023-08-01 [#9435](https://github.com/badges/shields/issues/9435)
- fix 'draft release' action part 2 [#9434](https://github.com/badges/shields/issues/9434)
- fix 'draft release' action [#9432](https://github.com/badges/shields/issues/9432)
- Convert `examples` arrays to `openApi` objects (part 1) [#9320](https://github.com/badges/shields/issues/9320)
- add a blog post about GH Tag/Release filter param [#9424](https://github.com/badges/shields/issues/9424)
- add some tests for [docsrs] [#9423](https://github.com/badges/shields/issues/9423)
- Migrate from docs.rs' builds API to status API [#9422](https://github.com/badges/shields/issues/9422)
- exclude assets dir from raster redirects [#9409](https://github.com/badges/shields/issues/9409)
- move some docs to the website [#9347](https://github.com/badges/shields/issues/9347)
- [OpenVSX] Fix OpenVSX API call for unversioned package URLs [#9408](https://github.com/badges/shields/issues/9408)
- devops: automate bug report tests [#9386](https://github.com/badges/shields/issues/9386)
- Add support for [Lemmy] [#9368](https://github.com/badges/shields/issues/9368)
- upgrade to npm 9 [#9323](https://github.com/badges/shields/issues/9323)
- run service/docker builds on merge queue builds [#8943](https://github.com/badges/shields/issues/8943)
- Go back to default YouTube cache [#9372](https://github.com/badges/shields/issues/9372)
- cache docker badges for longer (take 3) [#9369](https://github.com/badges/shields/issues/9369)
- edit comment about styles to remove in future [#9363](https://github.com/badges/shields/issues/9363)
- Revert "[OpenCollective] update opencollective to api v2 (#9346)" [#9362](https://github.com/badges/shields/issues/9362)
- improve docs for github issues search badge [#9360](https://github.com/badges/shields/issues/9360)
- [OpenCollective] update opencollective to api v2 [#9346](https://github.com/badges/shields/issues/9346)
- Add [GitHubDiscussionsSearch] and GitHubRepoDiscussionsSearch service [#9340](https://github.com/badges/shields/issues/9340)
- Allow user to filter github tags and releases [#9193](https://github.com/badges/shields/issues/9193)
- don't URL encode slash in [githubactionsworkflow] badge [#9322](https://github.com/badges/shields/issues/9322)
- add a bit of border to select boxes [#9348](https://github.com/badges/shields/issues/9348)
- deprecate [snyk] badges [#9349](https://github.com/badges/shields/issues/9349)
- increase max-age on [docker] badges, again [#9350](https://github.com/badges/shields/issues/9350)
- Changelog for Release server-2023-07-02 [#9344](https://github.com/badges/shields/issues/9344)
- cache [dockerpulls] badges for an hour [#9343](https://github.com/badges/shields/issues/9343)
- Mention YouTube API services and link to Google Privacy Policy [#9339](https://github.com/badges/shields/issues/9339)
- add a bit of border to text boxes [#9324](https://github.com/badges/shields/issues/9324)
- allow negative timestamps in relative [date] badge [#9321](https://github.com/badges/shields/issues/9321)
- Adjust `deploy-review-app` script [#9317](https://github.com/badges/shields/issues/9317)
- temp fix: wrap code examples tabs in narrow browser windows [#9302](https://github.com/badges/shields/issues/9302)
- upgrade to graphql 16 [#9290](https://github.com/badges/shields/issues/9290)
- chore(frontend): open homepage feature links in new tab [#9300](https://github.com/badges/shields/issues/9300)
- adapt opencollective images to theme background [#9298](https://github.com/badges/shields/issues/9298)
- run package tests on node 20 [#9293](https://github.com/badges/shields/issues/9293)
- try running tests on node 18 [#9292](https://github.com/badges/shields/issues/9292)
- Upgrade to ESLint 8; affects [docker factorio] [#9289](https://github.com/badges/shields/issues/9289)
- remove obsolete travis .org examples [#9284](https://github.com/badges/shields/issues/9284)
- increase max age on reddit badges [#9282](https://github.com/badges/shields/issues/9282)
- set a sensible meta description [#9283](https://github.com/badges/shields/issues/9283)
- fix a load of spacing issues in frontend content [#9281](https://github.com/badges/shields/issues/9281)
- migrate frontend to docusaurus [#9014](https://github.com/badges/shields/issues/9014)
- feat: Add author filter option for [GithubCommitActivity] [#9251](https://github.com/badges/shields/issues/9251)
- Fix: [GithubCommitActivity] invalid branch error handling [#9258](https://github.com/badges/shields/issues/9258)
- Implement a pattern for dealing with upstream APIs which are slow on the first hit; affects [endpoint] [#9233](https://github.com/badges/shields/issues/9233)
- Delete old deprecated services [#9254](https://github.com/badges/shields/issues/9254)
- Fix [CodeClimate] tests and examples [#9253](https://github.com/badges/shields/issues/9253)
- embiggen youtube cache, again [#9250](https://github.com/badges/shields/issues/9250)
- feat: add 'canceled' status to netlify deploy badge [#9240](https://github.com/badges/shields/issues/9240)
- php-version.js: Fix typos [#9239](https://github.com/badges/shields/issues/9239)
- increase default cache on youtube badges [#9238](https://github.com/badges/shields/issues/9238)
- disable dependabot auto rebase [#9234](https://github.com/badges/shields/issues/9234)
- Changelog for Release server-2023-06-01 [#9219](https://github.com/badges/shields/issues/9219)
- fix typo in test name [#9216](https://github.com/badges/shields/issues/9216)
- Add docstrings for validators service [#9197](https://github.com/badges/shields/issues/9197)
- feat: Add total commits to [GitHubCommitActivity] [#9196](https://github.com/badges/shields/issues/9196)
- add docstrings for text-formatters service [#9188](https://github.com/badges/shields/issues/9188)
- set a custom error on 429 [#9159](https://github.com/badges/shields/issues/9159)
- deprecate [travis].org badges [#9171](https://github.com/badges/shields/issues/9171)
- count private sponsors on [GithubSponsors] badge [#9170](https://github.com/badges/shields/issues/9170)
- Correct issue template in footer (new badge requests url is incorrect) [#9153](https://github.com/badges/shields/issues/9153)
- Changelog for Release server-2023-05-01 [#9139](https://github.com/badges/shields/issues/9139)
- switch from xmldom to @xmldom/xmldom [#9100](https://github.com/badges/shields/issues/9100)
- fail to start server if there are duplicate service names [#9099](https://github.com/badges/shields/issues/9099)
- Add docstrings for route builder service [#9118](https://github.com/badges/shields/issues/9118)
- fix [sourceforge] downloads [#9102](https://github.com/badges/shields/issues/9102)
- [SourceForge] Added badges for SourceForge [#9078](https://github.com/badges/shields/issues/9078)
- add fly.io PR review apps [#9069](https://github.com/badges/shields/issues/9069)
- remove redis token persistence backend [#9065](https://github.com/badges/shields/issues/9065)
- remove pull_request:edited trigger from most workflows [#9072](https://github.com/badges/shields/issues/9072)
- crates: Use `?include=` to reduce crates.io backend load [#9081](https://github.com/badges/shields/issues/9081)
- Export OpenAPI definitions from service examples; affects [dynamic endpoint static] [#8966](https://github.com/badges/shields/issues/8966)
- fix markdown summary if there are pending tests [#9068](https://github.com/badges/shields/issues/9068)
- Update the hint of simple-icons [#9054](https://github.com/badges/shields/issues/9054)
- Changelog for Release server-2023-04-02 [#9052](https://github.com/badges/shields/issues/9052)
- [CTAN] fallback to date if version is empty [#9036](https://github.com/badges/shields/issues/9036)
- update docker hosting docs [#9018](https://github.com/badges/shields/issues/9018)
- [JenkinsCoverage] Update Jenkins Code Coverage API for new plugin version [#9010](https://github.com/badges/shields/issues/9010)
- Update to [CTAN] API version 2.0 [#9016](https://github.com/badges/shields/issues/9016)
- Fix tests for [dynamic endpoint] services [#9015](https://github.com/badges/shields/issues/9015)
- log into the right registry [#9009](https://github.com/badges/shields/issues/9009)
- push images to both GHCR and DockerHub [#9008](https://github.com/badges/shields/issues/9008)
- handle missing statistics array in [VisualStudioMarketplace] badges [#8985](https://github.com/badges/shields/issues/8985)
- [Netlify] upgrade colors for SVG parsing [#8971](https://github.com/badges/shields/issues/8971)
- adjust route for [npmsio] badges [#8967](https://github.com/badges/shields/issues/8967)
- sort service path matches [#8968](https://github.com/badges/shields/issues/8968)
- Fix [Vcpkg] version service for different version fields [#8945](https://github.com/badges/shields/issues/8945)
- update docs following token pool changes [#8933](https://github.com/badges/shields/issues/8933)
- only try to close pool if one exists [#8947](https://github.com/badges/shields/issues/8947)
- misc minor fixes to [githubsize node pypi] [#8946](https://github.com/badges/shields/issues/8946)
- Changelog for Release server-2023-03-01 [#8949](https://github.com/badges/shields/issues/8949)
- remove migrate-token-pool.js [#8931](https://github.com/badges/shields/issues/8931)
- fix: for crates.io versions, use max_stable_version if it exists [#8687](https://github.com/badges/shields/issues/8687)
- fix TypeError: console.warning is not a function [#8930](https://github.com/badges/shields/issues/8930)
- migrate token pooling to postgres [#8922](https://github.com/badges/shields/issues/8922)
- don't autofocus search [#8927](https://github.com/badges/shields/issues/8927)
- Add [Vcpkg] version service [#8923](https://github.com/badges/shields/issues/8923)
- fix: Set uid/gid in docker image to 0 [#8908](https://github.com/badges/shields/issues/8908)
- pin 'deploy docs' build to node 16 [#8925](https://github.com/badges/shields/issues/8925)
- documentation html fixes [#8887](https://github.com/badges/shields/issues/8887)
- bump scoutcamp to 18.1.2 [#8891](https://github.com/badges/shields/issues/8891)
- expose port 443 in Dockerfile [#8889](https://github.com/badges/shields/issues/8889)
- Changelog for Release server-2023-02-01 [#8871](https://github.com/badges/shields/issues/8871)
- skip danger on repo ranger commits [#8866](https://github.com/badges/shields/issues/8866)
- Add ESLint checks for IcedFrisby exclusive/skipped tests [#8839](https://github.com/badges/shields/issues/8839)
- build docker images with buildkit v0.9.1 [#8862](https://github.com/badges/shields/issues/8862)
- replace [twitter] badge with static fallback [#8842](https://github.com/badges/shields/issues/8842)
- add a note about fine-grained PATs in the docs [#8823](https://github.com/badges/shields/issues/8823)
- migrate service tests to GH actions [#8421](https://github.com/badges/shields/issues/8421)
- remove danger-plugin-no-test-shortcuts [#8815](https://github.com/badges/shields/issues/8815)
- Add various [Polymart] badges [#8811](https://github.com/badges/shields/issues/8811)
- update [githubpipenv] tests/examples [#8797](https://github.com/badges/shields/issues/8797)
- fix service test loader on windows, add tests [#8786](https://github.com/badges/shields/issues/8786)
- Add docstrings for pipenv helpers [#8787](https://github.com/badges/shields/issues/8787)
- migrate danger CI job to GHA [#8477](https://github.com/badges/shields/issues/8477)
- deprecate [apm] service [#8773](https://github.com/badges/shields/issues/8773)
- Docstrings for php-version service [#8766](https://github.com/badges/shields/issues/8766)
- deprecate lgtm; lgtm service tests should be passing [#8771](https://github.com/badges/shields/issues/8771)
- Changelog for Release server-2023-01-01 [#8765](https://github.com/badges/shields/issues/8765)
- migrate frontend tests to GHA [#8541](https://github.com/badges/shields/issues/8541)
- Send `X-GitHub-Api-Version` when calling [GitHub] v3 API [#8669](https://github.com/badges/shields/issues/8669)
- add [VpmVersion] badge [#8755](https://github.com/badges/shields/issues/8755)
- Add [modrinth] game versions [#8673](https://github.com/badges/shields/issues/8673)
- don't try to call .entries on null or undefined [#8757](https://github.com/badges/shields/issues/8757)
- fix debug logging of undefined query params [#8540](https://github.com/badges/shields/issues/8540)
- run close-bot on node 16 [#8740](https://github.com/badges/shields/issues/8740)
- allow all numeric branch names in [githubactionsworkflowstatus] [#8734](https://github.com/badges/shields/issues/8734)
- switch [GithubActionsWorkflowStatus] to SVG scraper [#8738](https://github.com/badges/shields/issues/8738)
- handle workflow runs that do not have a conclusion [#8717](https://github.com/badges/shields/issues/8717)
- add a clarifying comment to [pypi] getLicenses [#8718](https://github.com/badges/shields/issues/8718)
- switch from github workflows to github actions workflows; test [githubactionsworkflowstatus githubworkflowstatus] [#8475](https://github.com/badges/shields/issues/8475)
- fall back to classifiers if license text is really long [#8690](https://github.com/badges/shields/issues/8690)
- docs/issue template improvements for badge requests [#8668](https://github.com/badges/shields/issues/8668)
- allow passing key to [stackexchange] [#8539](https://github.com/badges/shields/issues/8539)
- Changelog for Release server-2022-12-01 [#8670](https://github.com/badges/shields/issues/8670)
- fix: support logoColor to shield icons. [#8263](https://github.com/badges/shields/issues/8263)
- migrate e2e tests to GHA [#8562](https://github.com/badges/shields/issues/8562)
- handle missing properties array in [VisualStudioMarketplaceVersion] [#8603](https://github.com/badges/shields/issues/8603)
- don't call external services in core tests [#8643](https://github.com/badges/shields/issues/8643)
- add a missing redirect to coveralls [#8644](https://github.com/badges/shields/issues/8644)
- deprecate [wercker] service [#8642](https://github.com/badges/shields/issues/8642)
- Add [Coincap] Cryptocurrency badges [#8623](https://github.com/badges/shields/issues/8623)
- Add [modrinth] version [#8604](https://github.com/badges/shields/issues/8604)
- [factorio-mod-portal] services [#8625](https://github.com/badges/shields/issues/8625)
- [Coveralls] for GitLab [#8584](https://github.com/badges/shields/issues/8584)
- Remove 'suggest badges' feature [#8311](https://github.com/badges/shields/issues/8311)
- Add [modrinth] followers [#8601](https://github.com/badges/shields/issues/8601)
- Update the [modrinth] API to v2 [#8600](https://github.com/badges/shields/issues/8600)
- bump actions/setup-node to v3 [#8542](https://github.com/badges/shields/issues/8542)
- tidy up [GitHubGist] routes [#8510](https://github.com/badges/shields/issues/8510)
- fix [flathub] version error handling [#8500](https://github.com/badges/shields/issues/8500)
- fix [tas] private project test [#8514](https://github.com/badges/shields/issues/8514)
- Changelog for Release server-2022-11-01 [#8588](https://github.com/badges/shields/issues/8588)
- [Ansible] Add collection badge [#8578](https://github.com/badges/shields/issues/8578)
- fix [githubpullrequestcheckstate] service tests [#8548](https://github.com/badges/shields/issues/8548)
- require array to have at least 1 item in [githublastcommit] [#8563](https://github.com/badges/shields/issues/8563)
- [VisualStudioMarketplace] Add support to prerelease extensions version (Issue #8207) [#8561](https://github.com/badges/shields/issues/8561)
- feat: add [GitlabLastCommit] service [#8508](https://github.com/badges/shields/issues/8508)
- fix [swagger] service tests (allow 0 items in array) [#8564](https://github.com/badges/shields/issues/8564)
- fix codecov badge for non-default branch [#8565](https://github.com/badges/shields/issues/8565)
- fixes for integration test rate limit issues [#8538](https://github.com/badges/shields/issues/8538)
- remove failing [lgtm] test case [#8547](https://github.com/badges/shields/issues/8547)
- Add [GitHubLastCommit] by committer badge [#8537](https://github.com/badges/shields/issues/8537)
- [GitHubReleaseDate] - published_at field [#8543](https://github.com/badges/shields/issues/8543)
- Fix [Testspace] with new "untested" value in case_counts array [#8544](https://github.com/badges/shields/issues/8544)
- fix: Support WAITING status for GitHub deployments [#8521](https://github.com/badges/shields/issues/8521)
- update [bitbucket] private repo test [#8520](https://github.com/badges/shields/issues/8520)
- update [powershellgallery] platform example [#8518](https://github.com/badges/shields/issues/8518)
- fix [myget] downloads (tenant) test [#8513](https://github.com/badges/shields/issues/8513)
- [Whatpulse] badge for a user and for a team [#8466](https://github.com/badges/shields/issues/8466)
- increase timeout for [reuse] not found test [#8519](https://github.com/badges/shields/issues/8519)
- update [JenkinsPluginInstalls] test example [#8511](https://github.com/badges/shields/issues/8511)
- migrate integration tests to GH actions [#8423](https://github.com/badges/shields/issues/8423)
- deprecate [pkgreview] service [#8499](https://github.com/badges/shields/issues/8499)
- Changelog for Release server-2022-10-08 [#8507](https://github.com/badges/shields/issues/8507)
- deprecate [criterion] service [#8501](https://github.com/badges/shields/issues/8501)
- fix [wordpress] php version not set test [#8496](https://github.com/badges/shields/issues/8496)
- fix formatRelativeDate error handling; run [date] [#8497](https://github.com/badges/shields/issues/8497)
- allow/validate bitbucket_username / bitbucket_password in private config schema [#8472](https://github.com/badges/shields/issues/8472)
- fix [pub] points badge test and example [#8498](https://github.com/badges/shields/issues/8498)
- feat: add [GitlabLanguageCount] service [#8377](https://github.com/badges/shields/issues/8377)
- docs: update wording and url for freecodecamp usernames [#8480](https://github.com/badges/shields/issues/8480)
- [GitHubGistStars] add GitHub Gist Stars [#8471](https://github.com/badges/shields/issues/8471)
- fix display/search of CII badge examples [#8473](https://github.com/badges/shields/issues/8473)
- feat: add 2022 support to GitHub Hacktoberfest [#8468](https://github.com/badges/shields/issues/8468)
- [GitLabCoverage] subgroup bug [#8401](https://github.com/badges/shields/issues/8401)
- implement ruby gems-specific version sort/color functions [#8434](https://github.com/badges/shields/issues/8434)
- Add `rc` to pre-release identifiers [#8435](https://github.com/badges/shields/issues/8435)
- [GitHub] Number of commits between branches/tags/commits [#8394](https://github.com/badges/shields/issues/8394)
- [Packagist] dependency version [#8371](https://github.com/badges/shields/issues/8371)
- return string instead of object from getDependencyVersion function [#8396](https://github.com/badges/shields/issues/8396)
- conform to standard js quote rules [#8395](https://github.com/badges/shields/issues/8395)
- fix Docker build status invalid response data bug [#8392](https://github.com/badges/shields/issues/8392)
- use Joi type for Joi schemas [#8380](https://github.com/badges/shields/issues/8380)
- Docstrings for package json helpers [#8373](https://github.com/badges/shields/issues/8373)
- migrate package tests to GHA [#8351](https://github.com/badges/shields/issues/8351)
- improve workflow job names [#8376](https://github.com/badges/shields/issues/8376)
- feat: add [gitlab]-helper for encapsulate docs and err [#8295](https://github.com/badges/shields/issues/8295)
- Changelog for Release server-2022-09-04 [#8374](https://github.com/badges/shields/issues/8374)
- get the tests passing on windows [#8350](https://github.com/badges/shields/issues/8350)
- [DockerSize] Docker image size multi arch [#8290](https://github.com/badges/shields/issues/8290)
- migrate 'main' tests to GH actions [#8332](https://github.com/badges/shields/issues/8332)
- upgrade gatsby [#8334](https://github.com/badges/shields/issues/8334)
- Custom domains for [JitPack] artifacts [#8333](https://github.com/badges/shields/issues/8333)
- fix [dockerstars] service [#8316](https://github.com/badges/shields/issues/8316)
- Fix: Broken Badge generation for decimal activity values [#8315](https://github.com/badges/shields/issues/8315)
- feat: add [gitlabmergerequests] service [#8166](https://github.com/badges/shields/issues/8166)
- Fix variable naming for [ROS] version service [#8292](https://github.com/badges/shields/issues/8292)
- feat: add [GitlabStars] service [#8209](https://github.com/badges/shields/issues/8209)
- Fix invalid `rst` format when `alt` or `target` is present [#8275](https://github.com/badges/shields/issues/8275)
- [GithubGistLastCommit] GitHub gist last commit [#8272](https://github.com/badges/shields/issues/8272)
- chore: fix typo in badge request template [#8254](https://github.com/badges/shields/issues/8254)
- [GitHub] GitHub file size for a specific branch [#8262](https://github.com/badges/shields/issues/8262)
- Changelog for Release server-2022-08-01 [#8268](https://github.com/badges/shields/issues/8268)
- [pypi] Add Framework Version Badges support [#8261](https://github.com/badges/shields/issues/8261)
- feat: add [GitlabForks] server [#8208](https://github.com/badges/shields/issues/8208)
- Update PyPI api according to https://warehouse.pypa.io/api-reference/json.html [#8251](https://github.com/badges/shields/issues/8251)
- Add [galaxytoolshed] Activity [#8164](https://github.com/badges/shields/issues/8164)
- Fix wording in code-walkthrough.md [#8240](https://github.com/badges/shields/issues/8240)
- Fix typo in service-tests.md [#8239](https://github.com/badges/shields/issues/8239)
- [greasyfork] Add Greasy Fork rating badges [#8087](https://github.com/badges/shields/issues/8087)
- Fix heroku review apps (sort of) [#8213](https://github.com/badges/shields/issues/8213)
- Fix missing `dayjs` -> `moment` [#8204](https://github.com/badges/shields/issues/8204)
- refactor(deps): Replace moment with dayjs [#8192](https://github.com/badges/shields/issues/8192)
- add spaces round pipe in [conda] badge [#8189](https://github.com/badges/shields/issues/8189)
- Add [ROS] version service [#8169](https://github.com/badges/shields/issues/8169)
- feat: add [gitlabissues] service [#8108](https://github.com/badges/shields/issues/8108)
- add docs on nouns in route [#8141](https://github.com/badges/shields/issues/8141)
- Changelog for Release server-2022-07-03 [#8163](https://github.com/badges/shields/issues/8163)
- moar fixes for [gitlab] auth [#8162](https://github.com/badges/shields/issues/8162)
- Add [galaxytoolshed] services [#8114](https://github.com/badges/shields/issues/8114)
- Docstrings for licenses service [#8160](https://github.com/badges/shields/issues/8160)
- fix [gitlab] auth [#8145](https://github.com/badges/shields/issues/8145)
- change routes for [gitlab] license and contributors badges [#8140](https://github.com/badges/shields/issues/8140)
- ci: support new circle PR url variable [#8135](https://github.com/badges/shields/issues/8135)
- increase cache length on AUR version badge, run [AUR] [#8110](https://github.com/badges/shields/issues/8110)
- Use GraphQL to fix GitHub file count badges [github] [#8112](https://github.com/badges/shields/issues/8112)
- update targets for [bower] service tests [#8107](https://github.com/badges/shields/issues/8107)
- accept version with suffix in [ore] service tests [#8106](https://github.com/badges/shields/issues/8106)
- style: unified self-managed gitlab instance name [#8105](https://github.com/badges/shields/issues/8105)
- feat: add [gitlab] contributors service [#8084](https://github.com/badges/shields/issues/8084)
- fix: display greasy fork dd correctly [#8088](https://github.com/badges/shields/issues/8088)
- [greasyfork] Add Greasy Fork service badges [#8080](https://github.com/badges/shields/issues/8080)
- Fix typos in endpoint badge docs [#8085](https://github.com/badges/shields/issues/8085)
- fix: gitlab licence service docs and example [#8083](https://github.com/badges/shields/issues/8083)
- add docstrings for endpoint-common service [#8079](https://github.com/badges/shields/issues/8079)
- fix(gitlab service test): fix gitlab pipeline & tag(nested group) service test, run [gitlabtag gitlabpipeline] [#8076](https://github.com/badges/shields/issues/8076)
- Add [gitlablicense] services [#8024](https://github.com/badges/shields/issues/8024)
- [Spack] Package Manager: Update Domain [#8046](https://github.com/badges/shields/issues/8046)
- Docstrings for dynamic-common service [#8027](https://github.com/badges/shields/issues/8027)
- switch [jitpack] to use latestOk endpoint [#8041](https://github.com/badges/shields/issues/8041)
- Dependency updates

## server-2024-09-02

- Publish linux/amd64 docker images for snapshot builds [#10476](https://github.com/badges/shields/issues/10476)
- Fix Gitea not having credentials/authorizedOrigins in Docker environments [#10486](https://github.com/badges/shields/issues/10486)
- fix typo in pepy downloads [#10475](https://github.com/badges/shields/issues/10475)
- ignore a couple of docusaurus warnings [#10469](https://github.com/badges/shields/issues/10469)
- Use Ecologi API to power Treeware badges [#10467](https://github.com/badges/shields/issues/10467)
- move go version badge to platform support category [#10444](https://github.com/badges/shields/issues/10444)
- [Crates] Implement Dependents Badge [#10438](https://github.com/badges/shields/issues/10438)
- [Crates] Added crate size badge [#10421](https://github.com/badges/shields/issues/10421)
- Dependency updates

## server-2024-08-01

- send Cross-Origin-Resource-Policy header on all responses [#10420](https://github.com/badges/shields/issues/10420)
- migrate [MozillaObservatory] to new API [#10402](https://github.com/badges/shields/issues/10402)
- use metric() for [discord] and [revolt] badges [#10406](https://github.com/badges/shields/issues/10406)
- Cache text only static badges for longer [#10403](https://github.com/badges/shields/issues/10403)
- Fix [FreeCodeCampPoints] not found handling [#10377](https://github.com/badges/shields/issues/10377)
- Fix [Gitea] not found message [#10373](https://github.com/badges/shields/issues/10373)
- Deprecate [Bountysource] service [#10371](https://github.com/badges/shields/issues/10371)
- Sunset Shields custom logos [#10347](https://github.com/badges/shields/issues/10347)
- Use ellipsis when many versions returned for [ModrinthGameVersions] [#10350](https://github.com/badges/shields/issues/10350)
- deprecate [tokei] service [#9581](https://github.com/badges/shields/issues/9581)
- Add CF-Ray header value to Sentry errors if available [#10339](https://github.com/badges/shields/issues/10339)
- Use XML for Chocolatey, affects [Chocolatey Resharper PowershellGallery] [#10344](https://github.com/badges/shields/issues/10344)
- include github contributors badge in docs site [#10337](https://github.com/badges/shields/issues/10337)
- Dependency updates

## server-2024-07-01

- Add [AUR] Popularity Badge [#10304](https://github.com/badges/shields/issues/10304)
- fix npm badges when `maintainers` not in response [#10286](https://github.com/badges/shields/issues/10286)
- Expose `logoBase64` and `links` in badge-maker NPM package [#10283](https://github.com/badges/shields/issues/10283)
- Remove `logoPosition` [#10284](https://github.com/badges/shields/issues/10284)
- [MBIN] Add subscribers badge [#10270](https://github.com/badges/shields/issues/10270)
- Add [Docker] support for loong64 arch [#10241](https://github.com/badges/shields/issues/10241)
- Add puppetforge quality score badges [#10201](https://github.com/badges/shields/issues/10201)
- Dependency updates

## server-2024-06-01

- Remove namedLogo from defaultBadgeData of non-social badges [#10195](https://github.com/badges/shields/issues/10195)
- Update number of badges served each month [#10197](https://github.com/badges/shields/issues/10197)
- Delete old deprecated services [#10196](https://github.com/badges/shields/issues/10196)
- handle [BitbucketPipelines] responses with missing result key [#10163](https://github.com/badges/shields/issues/10163)
- Update description of GitHub commit status badge [#10198](https://github.com/badges/shields/issues/10198)
- chore: fix spelling of GitHub in badge descriptions [#10199](https://github.com/badges/shields/issues/10199)
- Add [GithubCheckRuns] service [#7759](https://github.com/badges/shields/issues/7759)
- feat: add Revolt badge [#10093](https://github.com/badges/shields/issues/10093)
- ensure color is string before calling toLowerCase() [#10129](https://github.com/badges/shields/issues/10129)
- instruct dependabot to monitor composite actions [#10139](https://github.com/badges/shields/issues/10139)
- run tests on node 22 [#10127](https://github.com/badges/shields/issues/10127)
- tweaks to libraries.io token pooling code [#10074](https://github.com/badges/shields/issues/10074)
- fix [pypi] status badge when package has no 'Development Status' classifier [#10107](https://github.com/badges/shields/issues/10107)
- clarify yml paths in server-secrets docs [#10106](https://github.com/badges/shields/issues/10106)
- Update region flag name in flyctl deploy command [#10134](https://github.com/badges/shields/issues/10134)
- Dependency updates

## server-2024-05-01

- [Hexpm] Fix badges for pre-release only versions [#10112](https://github.com/badges/shields/issues/10112)
- feat(logos): support auto-sizing mode [#9191](https://github.com/badges/shields/issues/9191) [#10110](https://github.com/badges/shields/issues/10110) [#10125](https://github.com/badges/shields/issues/10125)
- support setting pypiBaseUrl by environment variables and queryParameters; affects [pypi] [#10044](https://github.com/badges/shields/issues/10044)
- Add 0BSD license to licenseTypes and [PypiLicense] [#10092](https://github.com/badges/shields/issues/10092)
- Update Mastodon profile URL [#10082](https://github.com/badges/shields/issues/10082)
- [GitHubGoMod] Ignore comment after version (fixes #10079) [#10080](https://github.com/badges/shields/issues/10080)
- Perf: Librariesio repo dependencies [#10062](https://github.com/badges/shields/issues/10062)
- [Chocolatey Nuget] Fix "not found" error for chocolatey badge [#10060](https://github.com/badges/shields/issues/10060)
- Dependency updates

## server-2024-04-01

- improve performance of [GithubLastCommit] [GitlabLastCommit] [GiteaLastCommit] [#10046](https://github.com/badges/shields/issues/10046)
- [BitbucketLastCommit] Add Bitbucket last commit [#10043](https://github.com/badges/shields/issues/10043)
- [GithubLastCommit] [GitlabLastCommit] [GiteaLastCommit] Support file path for last commit [#10041](https://github.com/badges/shields/issues/10041)
- upgrade to docusaurus 3 [#9820](https://github.com/badges/shields/issues/9820)
- redirect [npm] /dt to /d18m [#10033](https://github.com/badges/shields/issues/10033)
- Add [JSR] version service [#10030](https://github.com/badges/shields/issues/10030)
- Add [snapcraft] version badge [#9976](https://github.com/badges/shields/issues/9976)
- Dependency updates

## server-2024-03-01

- feat(gitea): add last commit badge [#9995](https://github.com/badges/shields/issues/9995)
- [GithubCreatedAt] Add Created At Badge for Github [#9981](https://github.com/badges/shields/issues/9981)
- Added custom bucket url support for [Scoop] [#9984](https://github.com/badges/shields/issues/9984)
- [NpmUnpackedSize] Unpacked Size Badge [#9954](https://github.com/badges/shields/issues/9954)
- [Website] Render `status: down` badge if website is unresponsive [#9966](https://github.com/badges/shields/issues/9966)
- deprecate TAS [#9932](https://github.com/badges/shields/issues/9932)
- [GITEA] add forks, stars, issues and pr badges [#9923](https://github.com/badges/shields/issues/9923)
- tolerate missing short_version in [visualstudioappcenter] [#9951](https://github.com/badges/shields/issues/9951)
- [Crates] Only use non-yanked crate versions (ready for merge) [#9949](https://github.com/badges/shields/issues/9949)
- Dependency updates

## server-2024-02-01

- feat: added up_message and down_message to [uptimerobotstatus] [#9662](https://github.com/badges/shields/issues/9662)
- Add [Hangar] Badges [#9800](https://github.com/badges/shields/issues/9800)
- sort categories by title (except core) [#9888](https://github.com/badges/shields/issues/9888)
- Add Support for [Nostr] Followers [#9870](https://github.com/badges/shields/issues/9870)
- [thunderstore] replace experimental API usage with newly available v1 API [#9886](https://github.com/badges/shields/issues/9886)
- Update [Gitea] defaults to gitea.com [#9872](https://github.com/badges/shields/issues/9872)
- [crates] MSRV Badge [#9871](https://github.com/badges/shields/issues/9871)
- Add [galaxytoolshed] Version [#8249](https://github.com/badges/shields/issues/8249)
- fix default style docs for social badges [#9869](https://github.com/badges/shields/issues/9869)
- Dependency updates

## server-2024-01-01

The most important changes in this release for users hosting their own instance are:

The shields docker image is now based on node 20:

- deploy on node 20 [#9799](https://github.com/badges/shields/issues/9799)

It is now possible to use [authentication for DockerHub](https://github.com/badges/shields/blob/master/doc/server-secrets.md#dockerhub) to allow higher API rate limit or access to private repos:

- call [docker] with auth [#9803](https://github.com/badges/shields/issues/9803)

### New Badges

- [Thunderstore] Add Thunderstore Badges [#9782](https://github.com/badges/shields/issues/9782)
- Add [Raycast] Badge [#9801](https://github.com/badges/shields/issues/9801)
- [GITEA] add new gitea service (release/languages) [#9781](https://github.com/badges/shields/issues/9781)
- Add [NpmStatDownloads] Badge [#9783](https://github.com/badges/shields/issues/9783)

### Frontend Changes

- improve documentation for [dynamicxml] service [#9798](https://github.com/badges/shields/issues/9798)
- add description to interval enums [#9854](https://github.com/badges/shields/issues/9854)
- convert 'style' param to enum [#9853](https://github.com/badges/shields/issues/9853)
- Ensure social category badges are rendered with social style and logo; affects [gitlab keybase lemmy modrinth thunderstore twitch] gist github reddit [#9859](https://github.com/badges/shields/issues/9859)

### Fixes

- [pub] Use official version endpoint for pub-service [#9802](https://github.com/badges/shields/issues/9802)
- cache weblate badges for longer [#9786](https://github.com/badges/shields/issues/9786)
- [Discourse] Update schema keys to use plural form (`topic_count` -> `topics_count`) [#9778](https://github.com/badges/shields/issues/9778)
- cache some badges for longer [#9785](https://github.com/badges/shields/issues/9785)
- increase page size for github release badge by semver [#9818](https://github.com/badges/shields/issues/9818)
- Dependency updates

## server-2023-12-04

- move from @renovate/pep440 to @renovatebot/pep440 [#9614](https://github.com/badges/shields/issues/9614)
- deprecate/fix [ansible] galaxy services [#9648](https://github.com/badges/shields/issues/9648)
- call [pepy] with auth [#9748](https://github.com/badges/shields/issues/9748)
- add meaningful descriptions including keywords [#9715](https://github.com/badges/shields/issues/9715)
- Dependency updates

## server-2023-11-01

- fix greasyfork 404 bug [#9632](https://github.com/badges/shields/issues/9632)
- Hacktoberfest 2023 support - resolves #9636 [#9637](https://github.com/badges/shields/issues/9637)
- switch to fixed OpenCollective images [#9615](https://github.com/badges/shields/issues/9615)
- Dependency updates

## server-2023-10-02

- add python package total downloads from [pepy] badge [#9564](https://github.com/badges/shields/issues/9564)
- deprecate [redmine] plugin rating badges [#9568](https://github.com/badges/shields/issues/9568)
- fix [bower] version badge [#9567](https://github.com/badges/shields/issues/9567)
- Add [PythonVersionFromToml] shield [#9516](https://github.com/badges/shields/issues/9516)
- Add [dub] score badge service [#9549](https://github.com/badges/shields/issues/9549)
- Dependency updates

## server-2023-09-04

- Fix [testspace] badges [#9525](https://github.com/badges/shields/issues/9525)
- fix rSt code example [#9528](https://github.com/badges/shields/issues/9528)
- Add dynamic TOML support via [DynamicToml] Service [#9517](https://github.com/badges/shields/issues/9517)
- cache [pypi] downloads for longer [#9522](https://github.com/badges/shields/issues/9522)
- [twitter] --> x [#9496](https://github.com/badges/shields/issues/9496)
- [bundlejs] add badge for the npm package size [#9055](https://github.com/badges/shields/issues/9055)
- Switch [OpenCollective] badges to use GraphQL and auth [#9387](https://github.com/badges/shields/issues/9387)
- [Pulsar] Add Pulsar Badges for Stargazers & Downloads [#8767](https://github.com/badges/shields/issues/8767)
- Add [CurseForge] badges [#9252](https://github.com/badges/shields/issues/9252)
- deploy on node 18 [#9385](https://github.com/badges/shields/issues/9385)
- allow calling [github] without auth [#9427](https://github.com/badges/shields/issues/9427)
- Dependency updates

## server-2023-08-01

- Convert `examples` arrays to `openApi` objects (part 1) [#9320](https://github.com/badges/shields/issues/9320)
- Migrate from docs.rs' builds API to status API [#9422](https://github.com/badges/shields/issues/9422)
- [OpenVSX] Fix OpenVSX API call for unversioned package URLs [#9408](https://github.com/badges/shields/issues/9408)
- Add support for [Lemmy] [#9368](https://github.com/badges/shields/issues/9368)
- upgrade to npm 9 [#9323](https://github.com/badges/shields/issues/9323)
- Go back to default YouTube cache [#9372](https://github.com/badges/shields/issues/9372)
- Add [GitHubDiscussionsSearch] and GitHubRepoDiscussionsSearch service [#9340](https://github.com/badges/shields/issues/9340)
- Allow user to filter github tags and releases [#9193](https://github.com/badges/shields/issues/9193)
- don't URL encode slash in [githubactionsworkflow] badge [#9322](https://github.com/badges/shields/issues/9322)
- add a bit of border to select boxes [#9348](https://github.com/badges/shields/issues/9348)
- deprecate [snyk] badges [#9349](https://github.com/badges/shields/issues/9349)
- increase max-age on [docker] badges, again [#9350](https://github.com/badges/shields/issues/9350) [#9369](https://github.com/badges/shields/issues/9369)
- Dependency updates

## server-2023-07-02

By far the most significant change in this release is the long-awaited launch of the re-designed frontend:

- migrate frontend to docusaurus [#9014](https://github.com/badges/shields/issues/9014)
- fix a load of spacing issues in frontend content [#9281](https://github.com/badges/shields/issues/9281)
- set a sensible meta description [#9283](https://github.com/badges/shields/issues/9283)
- chore(frontend): open homepage feature links in new tab [#9300](https://github.com/badges/shields/issues/9300)
- adapt opencollective images to theme background [#9298](https://github.com/badges/shields/issues/9298)
- temp fix: wrap code examples tabs in narrow browser windows [#9302](https://github.com/badges/shields/issues/9302)
- add a bit of border to text boxes [#9324](https://github.com/badges/shields/issues/9324)

Other changes in this release:

- cache [dockerpulls] badges for an hour [#9343](https://github.com/badges/shields/issues/9343)
- Mention YouTube API services and link to Google Privacy Policy [#9339](https://github.com/badges/shields/issues/9339)
- allow negative timestamps in relative [date] badge [#9321](https://github.com/badges/shields/issues/9321)
- upgrade to graphql 16 [#9290](https://github.com/badges/shields/issues/9290)
- remove obsolete travis .org examples [#9284](https://github.com/badges/shields/issues/9284)
- increase max age on reddit badges [#9282](https://github.com/badges/shields/issues/9282)
- feat: Add author filter option for [GithubCommitActivity] [#9251](https://github.com/badges/shields/issues/9251)
- Fix: [GithubCommitActivity] invalid branch error handling [#9258](https://github.com/badges/shields/issues/9258)
- Implement a pattern for dealing with upstream APIs which are slow on the first hit; affects [endpoint] [#9233](https://github.com/badges/shields/issues/9233)
- Delete old deprecated services [#9254](https://github.com/badges/shields/issues/9254)
- feat: add 'canceled' status to netlify deploy badge [#9240](https://github.com/badges/shields/issues/9240)
- increase default cache on youtube badges [#9238](https://github.com/badges/shields/issues/9238)
- embiggen youtube cache, again [#9250](https://github.com/badges/shields/issues/9250)
- Dependency updates

## server-2023-06-01

- feat: Add total commits to [GitHubCommitActivity] [#9196](https://github.com/badges/shields/issues/9196)
- set a custom error on 429 [#9159](https://github.com/badges/shields/issues/9159)
- deprecate [travis].org badges [#9171](https://github.com/badges/shields/issues/9171)
- count private sponsors on [GithubSponsors] badge [#9170](https://github.com/badges/shields/issues/9170)
- Dependency updates

## server-2023-05-01

**Removal:** For users who need to maintain a Github Token pool, storage has been provided via the `RedisTokenPersistence` and `REDIS_URL` settings. This feature was deprecated in `server-2023-03-01`. As of this release, the `RedisTokenPersistence` backend is now removed. If you are using this feature, you will need to migrate to using the `SQLTokenPersistence` backend for storage and provide a postgres connection string via the `POSTGRES_URL` setting. [#8922](https://github.com/badges/shields/issues/8922)

- fail to start server if there are duplicate service names [#9099](https://github.com/badges/shields/issues/9099)
- [SourceForge] Added badges for SourceForge [#9078](https://github.com/badges/shields/issues/9078) [#9102](https://github.com/badges/shields/issues/9102)
- crates: Use `?include=` to reduce crates.io backend load [#9081](https://github.com/badges/shields/issues/9081)
- Dependency updates

## server-2023-04-02

- [JenkinsCoverage] Update Jenkins Code Coverage API for new plugin version [#9010](https://github.com/badges/shields/issues/9010)
- [CTAN] fallback to date if version is empty [#9036](https://github.com/badges/shields/issues/9036)
- Update to [CTAN] API version 2.0 [#9016](https://github.com/badges/shields/issues/9016)
- handle missing statistics array in [VisualStudioMarketplace] badges [#8985](https://github.com/badges/shields/issues/8985)
- [Netlify] upgrade colors for SVG parsing [#8971](https://github.com/badges/shields/issues/8971)
- Fix [Vcpkg] version service for different version fields [#8945](https://github.com/badges/shields/issues/8945)
- only try to close pool if one exists [#8947](https://github.com/badges/shields/issues/8947)
- misc minor fixes to [githubsize node pypi] [#8946](https://github.com/badges/shields/issues/8946)
- Dependency updates

## server-2023-03-01

**Deprecation:** For users who need to maintain a Github Token pool, storage has been provided via the `RedisTokenPersistence` and `REDIS_URL` settings. As of this release, the `RedisTokenPersistence` backend is now deprecated and will be removed in a future release. If you are using this feature, you will need to migrate to using the `SQLTokenPersistence` backend for storage and provide a postgres connection string via the `POSTGRES_URL` setting. [#8922](https://github.com/badges/shields/issues/8922)

- fix: for crates.io versions, use max_stable_version if it exists [#8687](https://github.com/badges/shields/issues/8687)
- don't autofocus search [#8927](https://github.com/badges/shields/issues/8927)
- Add [Vcpkg] version service [#8923](https://github.com/badges/shields/issues/8923)
- fix: Set uid/gid in docker image to 0 [#8908](https://github.com/badges/shields/issues/8908)
- expose port 443 in Dockerfile [#8889](https://github.com/badges/shields/issues/8889)
- Dependency updates

## server-2023-02-01

- replace [twitter] badge with static fallback [#8842](https://github.com/badges/shields/issues/8842)
- Add various [Polymart] badges [#8811](https://github.com/badges/shields/issues/8811)
- update [githubpipenv] tests/examples [#8797](https://github.com/badges/shields/issues/8797)
- deprecate [apm] service [#8773](https://github.com/badges/shields/issues/8773)
- deprecate lgtm [#8771](https://github.com/badges/shields/issues/8771)
- Dependency updates

## server-2023-01-01

- Breaking change: Routes for GitHub workflows badge have changed. See https://github.com/badges/shields/issues/8671 for more details
- Behaviour change: In this release we fixed a long standing bug. GitHub badges were previously not reading the base URL from the `config.service.baseUri`.
  This release fixes that bug, bringing the code into line with the documented behaviour. This should not cause a behaviour change for most users,
  but users who had previously set a value in `config.service.baseUri` which was previously ignored could see this now have an effect.
  Users who configure their instance using env vars rather than yaml should see no change.
- Send `X-GitHub-Api-Version` when calling [GitHub] v3 API [#8669](https://github.com/badges/shields/issues/8669)
- add [VpmVersion] badge [#8755](https://github.com/badges/shields/issues/8755)
- Add [modrinth] game versions [#8673](https://github.com/badges/shields/issues/8673)
- fix debug logging of undefined query params [#8540](https://github.com/badges/shields/issues/8540), [#8757](https://github.com/badges/shields/issues/8757)
- fall back to classifiers if [pypi] license text is really long [#8690](https://github.com/badges/shields/issues/8690)
- allow passing key to [stackexchange] [#8539](https://github.com/badges/shields/issues/8539)
- Dependency updates

## server-2022-12-01

- fix: support logoColor to shield icons. [#8263](https://github.com/badges/shields/issues/8263)
- handle missing properties array in [VisualStudioMarketplaceVersion] [#8603](https://github.com/badges/shields/issues/8603)
- deprecate [wercker] service [#8642](https://github.com/badges/shields/issues/8642)
- Add [Coincap] Cryptocurrency badges [#8623](https://github.com/badges/shields/issues/8623)
- Add [modrinth] version [#8604](https://github.com/badges/shields/issues/8604)
- [factorio-mod-portal] services [#8625](https://github.com/badges/shields/issues/8625)
- [Coveralls] for GitLab [#8584](https://github.com/badges/shields/issues/8584), [#8644](https://github.com/badges/shields/issues/8644)
- Remove 'suggest badges' feature [#8311](https://github.com/badges/shields/issues/8311)
- Add [modrinth] followers [#8601](https://github.com/badges/shields/issues/8601)
- Update the [modrinth] API to v2 [#8600](https://github.com/badges/shields/issues/8600)
- tidy up [GitHubGist] routes [#8510](https://github.com/badges/shields/issues/8510)
- fix [flathub] version error handling [#8500](https://github.com/badges/shields/issues/8500)
- Dependency updates

## server-2022-11-01

- [Ansible] Add collection badge [#8578](https://github.com/badges/shields/issues/8578)
- [VisualStudioMarketplace] Add support to prerelease extensions version (Issue #8207) [#8561](https://github.com/badges/shields/issues/8561)
- feat: add [GitlabLastCommit] service [#8508](https://github.com/badges/shields/issues/8508)
- fix [swagger] service tests (allow 0 items in array) [#8564](https://github.com/badges/shields/issues/8564)
- fix codecov badge for non-default branch [#8565](https://github.com/badges/shields/issues/8565)
- Add [GitHubLastCommit] by committer badge [#8537](https://github.com/badges/shields/issues/8537)
- [GitHubReleaseDate] - published_at field [#8543](https://github.com/badges/shields/issues/8543)
- Fix [Testspace] with new "untested" value in case_counts array [#8544](https://github.com/badges/shields/issues/8544)
- fix: Support WAITING status for GitHub deployments [#8521](https://github.com/badges/shields/issues/8521)
- [Whatpulse] badge for a user and for a team [#8466](https://github.com/badges/shields/issues/8466)
- deprecate [pkgreview] service [#8499](https://github.com/badges/shields/issues/8499)
- Dependency updates

## server-2022-10-08

- deprecate [criterion] service [#8501](https://github.com/badges/shields/issues/8501)
- fix formatRelativeDate error handling; run [date] [#8497](https://github.com/badges/shields/issues/8497)
- allow/validate bitbucket_username / bitbucket_password in private config schema [#8472](https://github.com/badges/shields/issues/8472)
- fix [pub] points badge test and example [#8498](https://github.com/badges/shields/issues/8498)
- feat: add [GitlabLanguageCount] service [#8377](https://github.com/badges/shields/issues/8377)
- [GitHubGistStars] add GitHub Gist Stars [#8471](https://github.com/badges/shields/issues/8471)
- fix display/search of CII badge examples [#8473](https://github.com/badges/shields/issues/8473)
- feat: add 2022 support to GitHub Hacktoberfest [#8468](https://github.com/badges/shields/issues/8468)
- fix [GitLabCoverage] subgroup bug [#8401](https://github.com/badges/shields/issues/8401)
- implement ruby gems-specific version sort/color functions [#8434](https://github.com/badges/shields/issues/8434)
- Add `rc` to pre-release identifiers [#8435](https://github.com/badges/shields/issues/8435)
- add [GitHub] Number of commits between branches/tags/commits [#8394](https://github.com/badges/shields/issues/8394)
- add [Packagist] dependency version [#8371](https://github.com/badges/shields/issues/8371)
- fix Docker build status invalid response data bug [#8392](https://github.com/badges/shields/issues/8392)
- Dependency updates

## server-2022-09-04

- fix frontend compile for users running on Windows [#8350](https://github.com/badges/shields/issues/8350)
- [DockerSize] Docker image size multi arch [#8290](https://github.com/badges/shields/issues/8290)
- upgrade gatsby [#8334](https://github.com/badges/shields/issues/8334)
- Custom domains for [JitPack] artifacts [#8333](https://github.com/badges/shields/issues/8333)
- fix [dockerstars] service [#8316](https://github.com/badges/shields/issues/8316)
- [BountySource] Fix: Broken Badge generation for decimal activity values [#8315](https://github.com/badges/shields/issues/8315)
- feat: add [gitlabmergerequests] service [#8166](https://github.com/badges/shields/issues/8166)
- Fix terminology for [ROS] version service [#8292](https://github.com/badges/shields/issues/8292)
- feat: add [GitlabStars] service [#8209](https://github.com/badges/shields/issues/8209)
- Fix invalid `rst` format when `alt` or `target` is present [#8275](https://github.com/badges/shields/issues/8275)
- [GithubGistLastCommit] GitHub gist last commit [#8272](https://github.com/badges/shields/issues/8272)
- [GitHub] GitHub file size for a specific branch [#8262](https://github.com/badges/shields/issues/8262)
- Dependency updates

## server-2022-08-01

- [pypi] Add Framework Version Badges support [#8261](https://github.com/badges/shields/issues/8261)
- feat: add [GitlabForks] server [#8208](https://github.com/badges/shields/issues/8208)
- Update PyPI api according to https://warehouse.pypa.io/api-reference/json.html [#8251](https://github.com/badges/shields/issues/8251)
- Add [galaxytoolshed] Activity [#8164](https://github.com/badges/shields/issues/8164)
- [greasyfork] Add Greasy Fork rating badges [#8087](https://github.com/badges/shields/issues/8087)
- refactor(deps): Replace moment with dayjs [#8192](https://github.com/badges/shields/issues/8192)
- add spaces round pipe in [conda] badge [#8189](https://github.com/badges/shields/issues/8189)
- Add [ROS] version service [#8169](https://github.com/badges/shields/issues/8169)
- feat: add [gitlabissues] service [#8108](https://github.com/badges/shields/issues/8108)
- Dependency updates

## server-2022-07-03

- Add [galaxytoolshed] services [#8114](https://github.com/badges/shields/issues/8114)
- fix [gitlab] auth [#8145](https://github.com/badges/shields/issues/8145) [#8162](https://github.com/badges/shields/issues/8162)
- increase cache length on AUR version badge, run [AUR] [#8110](https://github.com/badges/shields/issues/8110)
- Use GraphQL to fix GitHub file count badges [github] [#8112](https://github.com/badges/shields/issues/8112)
- feat: add [gitlab] contributors service [#8084](https://github.com/badges/shields/issues/8084)
- [greasyfork] Add Greasy Fork service badges [#8080](https://github.com/badges/shields/issues/8080)
- Add [gitlablicense] services [#8024](https://github.com/badges/shields/issues/8024)
- [Spack] Package Manager: Update Domain [#8046](https://github.com/badges/shields/issues/8046)
- switch [jitpack] to use latestOk endpoint [#8041](https://github.com/badges/shields/issues/8041)
- Dependency updates

## server-2022-06-01

- Update GitLab logo (2022) [#7984](https://github.com/badges/shields/issues/7984)
- [GitHub] Added milestone property to GitHub issue details service [#7864](https://github.com/badges/shields/issues/7864)
- [Spack] Package Manager: Update Endpoint [#7957](https://github.com/badges/shields/issues/7957)
- Update Chocolatey API endpoint URL [#7952](https://github.com/badges/shields/issues/7952)
- [Flathub]Add downloads badge [#7724](https://github.com/badges/shields/issues/7724)
- replace the outdated Telegram logo with the newest [#7831](https://github.com/badges/shields/issues/7831)
- add [PUB] points badge [#7918](https://github.com/badges/shields/issues/7918)
- add [PUB] popularity badge [#7920](https://github.com/badges/shields/issues/7920)
- add [PUB] likes badge [#7916](https://github.com/badges/shields/issues/7916)
- Dependency updates

## server-2022-05-03

- [OSSFScorecard] Create scorecard badge service [#7687](https://github.com/badges/shields/issues/7687)
- Stringify [githublanguagecount] message [#7881](https://github.com/badges/shields/issues/7881)
- Stringify and trim whitespace from a few services [#7880](https://github.com/badges/shields/issues/7880)
- add labels to Dockerfile [#7862](https://github.com/badges/shields/issues/7862)
- handle missing 'fly-client-ip' [#7814](https://github.com/badges/shields/issues/7814)
- Dependency updates

## server-2022-04-03

- Breaking change: This release updates ioredis from v4 to v5.
  If you are using redis for GitHub token pooling, redis connection strings of the form
  `redis://junkusername:authpassword@example.com:1234` will need to be updated to
  `redis://:authpassword@example.com:1234`. See the
  [ioredis upgrade guide](https://github.com/luin/ioredis/wiki/Upgrading-from-v4-to-v5)
  for further details.
- fix installation issue on npm >= 8.5.5 [#7809](https://github.com/badges/shields/issues/7809)
- two fixes for [packagist] schemas [#7782](https://github.com/badges/shields/issues/7782)
- allow requireCloudflare setting to work when hosted on fly.io [#7781](https://github.com/badges/shields/issues/7781)
- fix [pypi] badges when package has null license [#7761](https://github.com/badges/shields/issues/7761)
- Add a [pub] publisher badge [#7715](https://github.com/badges/shields/issues/7715)
- Switch Steam file size badge to informational color [#7722](https://github.com/badges/shields/issues/7722)
- Make W3C and Youtube documentation links clickable [#7721](https://github.com/badges/shields/issues/7721)
- Improve Wercker examples [#7720](https://github.com/badges/shields/issues/7720)
- Improve Cirrus CI examples [#7719](https://github.com/badges/shields/issues/7719)
- Support [CodeClimate] responses with multiple data items [#7716](https://github.com/badges/shields/issues/7716)
- Delete [TeamCityCoverage] and [BowerVersion] redirectors [#7718](https://github.com/badges/shields/issues/7718)
- Deprecate [Shippable] service [#7717](https://github.com/badges/shields/issues/7717)
- fix: restore version comparison updates from #4173 [#4254](https://github.com/badges/shields/issues/4254)
- [piwheels], filter out versions with no files [#7696](https://github.com/badges/shields/issues/7696)
- set a longer cacheLength on [librariesio] badges [#7692](https://github.com/badges/shields/issues/7692)
- improve python version formatting [#7682](https://github.com/badges/shields/issues/7682)
- Clarify GitHub All Contributors badge [#7690](https://github.com/badges/shields/issues/7690)
- Support [HexPM] packages with no stable release [#7685](https://github.com/badges/shields/issues/7685)
- Add Test at Scale Badge [#7612](https://github.com/badges/shields/issues/7612)
- [packagist] api v2 support [#7681](https://github.com/badges/shields/issues/7681)
- Add [piwheels] version badge [#7656](https://github.com/badges/shields/issues/7656)
- Dependency updates

## server-2022-03-01

- Add [Conan] version service (#7460)
- remove suspended [github] tokens from the pool [#7654](https://github.com/badges/shields/issues/7654)
- generate links without trailing : if port not set [#7655](https://github.com/badges/shields/issues/7655)
- Use the latest build status when checking docs.rs [#7613](https://github.com/badges/shields/issues/7613)
- Remove no download handling and add API warning to [Wordpress] badges [#7606](https://github.com/badges/shields/issues/7606)
- set a higher default cacheLength on rating/star category [#7587](https://github.com/badges/shields/issues/7587)
- Update [amo] to use v4 API, set custom `cacheLength`s [#7586](https://github.com/badges/shields/issues/7586)
- fix(amo): include trailing slash in API call [#7585](https://github.com/badges/shields/issues/7585)
- fix docker image user agent [#7582](https://github.com/badges/shields/issues/7582)
- Delete deprecated Codetally and continuousphp services [#7572](https://github.com/badges/shields/issues/7572)
- Deprecate [Requires] service [#7571](https://github.com/badges/shields/issues/7571)
- [AUR] Fix RPC URL [#7570](https://github.com/badges/shields/issues/7570)
- Dependency updates

## server-2022-02-01

- [Depfu] Add support for Gitlab [#7475](https://github.com/badges/shields/issues/7475)
- replace label in hn-user-karma with U/ [#7500](https://github.com/badges/shields/issues/7500)
- Support [Feedz] response with multiple pages without items [#7476](https://github.com/badges/shields/issues/7476)
- revert decamelize and humanize-string to old versions [#7449](https://github.com/badges/shields/issues/7449)
- Dependency updates

## server-2022-01-01

- minor [reddit] improvements [#7436](https://github.com/badges/shields/issues/7436)
- [HackerNews] Show User Karma [#7411](https://github.com/badges/shields/issues/7411)
- [YouTube] Drop support for removed dislikes [#7410](https://github.com/badges/shields/issues/7410)
- change closed GitHub issue color to purple [#7374](https://github.com/badges/shields/issues/7374)
- restore cors header injection from #4171 [#4255](https://github.com/badges/shields/issues/4255)
- [GithubPackageJson] Get version from monorepo subfolder package.json [#7350](https://github.com/badges/shields/issues/7350)
- Dependency updates

## server-2021-12-01

- Send better user-agent values [#7309](https://github.com/badges/shields/issues/7309)
  Self-hosting users now send a user agent which indicates the server version and starts `shields (self-hosted)/` by default.
  This can be configured using the env var `USER_AGENT_BASE`
- upgrade to node 16 [#7271](https://github.com/badges/shields/issues/7271)
- feat: deprecate dependabot badges [#7274](https://github.com/badges/shields/issues/7274)
- fix: npmversion tagged service test [#7269](https://github.com/badges/shields/issues/7269)
- feat: create new Test Results category [#7218](https://github.com/badges/shields/issues/7218)
- Migration from Request to Got for all HTTP requests is completed in this release
- Dependency updates

## server-2021-11-04

- migrate regularUpdate() from request-->got [#7215](https://github.com/badges/shields/issues/7215)
- migrate github badges to use got instead of request; affects [github librariesio] [#7212](https://github.com/badges/shields/issues/7212)
- deprecate David badges [#7197](https://github.com/badges/shields/issues/7197)
- fix: ensure libraries.io header values are processed numerically [#7196](https://github.com/badges/shields/issues/7196)
- Add authentication for Libraries.io-based badges, run [Libraries Bower] [#7080](https://github.com/badges/shields/issues/7080)
- fixes and tests for pipenv helpers [#7194](https://github.com/badges/shields/issues/7194)
- add GitLab Release badge, run all [GitLab] [#7021](https://github.com/badges/shields/issues/7021)
- set content-length header on badge responses [#7179](https://github.com/badges/shields/issues/7179)
- fix [github] release/tag/download schema [#7170](https://github.com/badges/shields/issues/7170)
- Supported nested groups on [GitLabPipeline] badge [#7159](https://github.com/badges/shields/issues/7159)
- Support nested groups on [GitLabTag] badge [#7158](https://github.com/badges/shields/issues/7158)
- Fixing incorrect JetBrains Plugin rating values for [JetBrainsRating] [#7140](https://github.com/badges/shields/issues/7140)
- support using release or tag name in [GitHub] Release version badge [#7075](https://github.com/badges/shields/issues/7075)
- feat: support branches in sonar badges [#7065](https://github.com/badges/shields/issues/7065)
- Add [Modrinth] total downloads badge [#7132](https://github.com/badges/shields/issues/7132)
- remove [github] admin routes [#7105](https://github.com/badges/shields/issues/7105)
- Dependency updates

## server-2021-10-04

- feat: add 2021 support to GitHub Hacktoberfest [#7086](https://github.com/badges/shields/issues/7086)
- Add [ClearlyDefined] service [#6944](https://github.com/badges/shields/issues/6944)
- handle null licenses in crates.io response schema, run [crates] [#7074](https://github.com/badges/shields/issues/7074)
- [OBS] add Open Build Service service-badge [#6993](https://github.com/badges/shields/issues/6993)
- Correction of badges url in self-hosting configuration with a custom port. Issue 7025 [#7036](https://github.com/badges/shields/issues/7036)
- fix: support gitlab token via env var [#7023](https://github.com/badges/shields/issues/7023)
- Add API-based support for [GitLab] badges, add new GitLab Tag badge [#6988](https://github.com/badges/shields/issues/6988)
- [freecodecamp]: allow + symbol in username [#7016](https://github.com/badges/shields/issues/7016)
- Rename Riot to Element in Matrix badge help [#6996](https://github.com/badges/shields/issues/6996)
- Fixed Reddit Negative Karma Issue [#6992](https://github.com/badges/shields/issues/6992)
- Dependency updates

## server-2021-09-01

- use multi-stage build to reduce size of docker images [#6938](https://github.com/badges/shields/issues/6938)
- remove disableStrictSsl param from [jenkins] [#6887](https://github.com/badges/shields/issues/6887)
- refactor(GitHubCommitActivity): switch to v4/GraphQL API [#6959](https://github.com/badges/shields/issues/6959)
- feat: add freecodecamp badge [#6958](https://github.com/badges/shields/issues/6958)
- use the right version of NPM in docker build [#6941](https://github.com/badges/shields/issues/6941)
- [TwitchExtensionVersion] New badge [#6900](https://github.com/badges/shields/issues/6900)
- enforce strict SSL checking for [coverity] [#6886](https://github.com/badges/shields/issues/6886)
- Update self hosting docs [#6877](https://github.com/badges/shields/issues/6877)
- Support optionalDependencies in [GithubPackageJson] [#6749](https://github.com/badges/shields/issues/6749)
- Dependency updates

## server-2021-08-01

- use v5 API for [AUR] badges [#6836](https://github.com/badges/shields/issues/6836)
- [Sonar] Fix invalid fetch query to sonarqube >=6.6 [#6636](https://github.com/badges/shields/issues/6636)
- Delegate discord logo to simple-icons, which matches the current branding [#6764](https://github.com/badges/shields/issues/6764)
- Re-apply 'Migrate request to got (part 1)' [#6755](https://github.com/badges/shields/issues/6755)
- Delete old deprecated badges [#6756](https://github.com/badges/shields/issues/6756)
- Replace opn-cli with open-cli [#6747](https://github.com/badges/shields/issues/6747)
- Verify that Node 14 is installed in development [#6748](https://github.com/badges/shields/issues/6748)
- Migrate from CommonJS to ESM [#6651](https://github.com/badges/shields/issues/6651)
- Add Wikiapiary Extension Badge [WikiapiaryInstalls] [#6678](https://github.com/badges/shields/issues/6678)
- deprecate [beerpay] [#6708](https://github.com/badges/shields/issues/6708)
- deprecate [microbadger] [#6709](https://github.com/badges/shields/issues/6709)
- [npmsioscore] Support npm score [#6630](https://github.com/badges/shields/issues/6630)
- Add [Weblate] badges [#6677](https://github.com/badges/shields/issues/6677)
- Dependency updates

## server-2021-07-01

- improve [MavenCentral], [MavenMetadata], and [GradlePluginPortal] [#6628](https://github.com/badges/shields/issues/6628)
- fix: fix regex to match [codecov]'s flags [#6655](https://github.com/badges/shields/issues/6655)
- fix usage style [#6638](https://github.com/badges/shields/issues/6638)
- update simple-icons to v5 with by-name lookup backwards compatibility [#6591](https://github.com/badges/shields/issues/6591)
- [GradlePluginPortal] add gradle plugin portal [#6449](https://github.com/badges/shields/issues/6449)
- upgrade some vulnerable packages [#6569](https://github.com/badges/shields/issues/6569)
- increase max-age for download and social badges [#6567](https://github.com/badges/shields/issues/6567)
- Dependency updates

## server-2021-06-01

- Changed creating badges to open a new Window/Tab [#6536](https://github.com/badges/shields/issues/6536)
- Make for-the-badge letter spacing more predictable, and rewrite layout logic [#5754](https://github.com/badges/shields/issues/5754)
- deprecate DockerBuild service [#6529](https://github.com/badges/shields/issues/6529)
- Remove rate limiting functionality [#6513](https://github.com/badges/shields/issues/6513)
- [GitHub] Move to 'funding' category [#5846](https://github.com/badges/shields/issues/5846)
- Add GitHub discussions total badge [GithubTotalDiscussions] [#6472](https://github.com/badges/shields/issues/6472)
- Add optional query parameter (include_prereleases) to [GemVersion] [#6451](https://github.com/badges/shields/issues/6451)
- Add [PingPong] Service [#6327](https://github.com/badges/shields/issues/6327)
- Dependency updates

## server-2021-05-01

- Add setting which allows setting a timeout on HTTP requests
  This is configured with the new `REQUEST_TIMEOUT_SECONDS` setting. If a request takes longer
  than this number of seconds a `408 Request Timeout` response will be returned.
- Deprecate [Bintray] service [#6423](https://github.com/badges/shields/issues/6423)
- Support git hash in [nexus] SNAPSHOT version [#6369](https://github.com/badges/shields/issues/6369)
- Replace 4183C4 with blue [#6366](https://github.com/badges/shields/issues/6366)
- [Youtube] Added channel view count and subscriber count badges [#6333](https://github.com/badges/shields/issues/6333)
- Fix Netlify badge by adding new color schema [#6340](https://github.com/badges/shields/issues/6340)
- [REUSE] Add service badges [#6330](https://github.com/badges/shields/issues/6330)
- Dependency updates

## server-2021-04-01

- Use NPM packages to provide fonts instead of Google Fonts [#6274](https://github.com/badges/shields/issues/6274)
- Prevent duplication of parameters in badge examples [#6272](https://github.com/badges/shields/issues/6272)
- Add docs for all types of releases [#6210](https://github.com/badges/shields/issues/6210)
- refresh self-hosting docs [#6273](https://github.com/badges/shields/issues/6273)
- allow missing 'goal' key in [liberapay] badges [#6258](https://github.com/badges/shields/issues/6258)
- use got to push influx metrics [#6257](https://github.com/badges/shields/issues/6257)
- Dependency updates

## server-2021-03-01

- ensure redirect target path is correctly encoded [#6229](https://github.com/badges/shields/issues/6229)
- [SecurityHeaders] Added a possibility for no follow redirects [#6212](https://github.com/badges/shields/issues/6212)
- catch URL parse error in [endpoint] badge [#6214](https://github.com/badges/shields/issues/6214)
- [Homebrew] Add homebrew downloads badge [#6209](https://github.com/badges/shields/issues/6209)
- update [pkgreview] url [#6189](https://github.com/badges/shields/issues/6189)
- Make [Twitch] a social badge [#6183](https://github.com/badges/shields/issues/6183)
- update [flathub] error handling [#6185](https://github.com/badges/shields/issues/6185)
- Add [Testspace] badges [#6162](https://github.com/badges/shields/issues/6162)
- Dependency updates

## server-2021-02-01

- Docs.rs badge (#6098)
- Fix feedz service in case the package page gets paginated (#6101)
- [Bitbucket] Server Adding Auth Tokens and Resolving Pull Request api … (#6076)
- Dependency updates

## server-2021-01-18

- Gotta start somewhere
