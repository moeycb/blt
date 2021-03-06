# Change Log

## [8.4.2](https://github.com/acquia/blt/tree/8.4.2) (2016-09-14)
[Full Changelog](https://github.com/acquia/blt/compare/8.4.1...8.4.2)

**Implemented enhancements:**

- Create init tasks for ci [\#379](https://github.com/acquia/blt/issues/379)
- Allow customization of blt update file excludes. [\#396](https://github.com/acquia/blt/pull/396) ([grasmash](https://github.com/grasmash))
- Updating Phing to latest version. [\#395](https://github.com/acquia/blt/pull/395) ([grasmash](https://github.com/grasmash))
- Removing duplicative drupal scaffold files. [\#391](https://github.com/acquia/blt/pull/391) ([grasmash](https://github.com/grasmash))
- Ignoring various files in rsync update. [\#390](https://github.com/acquia/blt/pull/390) ([grasmash](https://github.com/grasmash))
- Fixes \#379: Adding init tasks for ci config. [\#389](https://github.com/acquia/blt/pull/389) ([grasmash](https://github.com/grasmash))
- Making deprecated file deletion opt-in. [\#388](https://github.com/acquia/blt/pull/388) ([grasmash](https://github.com/grasmash))

**Fixed bugs:**

- Update ACSF hooks to use new blt vendor settings. [\#393](https://github.com/acquia/blt/pull/393) ([dpagini](https://github.com/dpagini))
- fix template/.gitattributes [\#392](https://github.com/acquia/blt/pull/392) ([dpagini](https://github.com/dpagini))
- Adding quotes to Behat tags. [\#387](https://github.com/acquia/blt/pull/387) ([grasmash](https://github.com/grasmash))

**Misc merged pull requests**

- Adding tests and docs for travis:ci:init command. [\#398](https://github.com/acquia/blt/pull/398) ([grasmash](https://github.com/grasmash))
- Simple grammar update to add a space. [\#397](https://github.com/acquia/blt/pull/397) ([dpagini](https://github.com/dpagini))
- BLT: Encourage cache clear upon project creation. [\#394](https://github.com/acquia/blt/pull/394) ([bhasselbeck](https://github.com/bhasselbeck))
- Removing invaid @todo. [\#386](https://github.com/acquia/blt/pull/386) ([grasmash](https://github.com/grasmash))

## [8.4.1](https://github.com/acquia/blt/tree/8.4.1) (2016-09-12)
[Full Changelog](https://github.com/acquia/blt/compare/8.4.0...8.4.1)

**Implemented enhancements:**

- BLT presumes sites/default, complicates multisite settings [\#380](https://github.com/acquia/blt/issues/380)
- Automate execution of `blt update` after composer update [\#341](https://github.com/acquia/blt/issues/341)
- Install BLT alias automatically for developers [\#284](https://github.com/acquia/blt/issues/284)
- Fixes \#380: Allow $site\_dir to be defined for multisite. [\#382](https://github.com/acquia/blt/pull/382) ([grasmash](https://github.com/grasmash))
- Making vm:init task more verbose. [\#376](https://github.com/acquia/blt/pull/376) ([grasmash](https://github.com/grasmash))
- Replacing external Phing random string task with internal one. [\#375](https://github.com/acquia/blt/pull/375) ([grasmash](https://github.com/grasmash))
- Added search modules [\#374](https://github.com/acquia/blt/pull/374) ([danepowell](https://github.com/danepowell))
- Chmod settings.php to 644 instead of 755 [\#370](https://github.com/acquia/blt/pull/370) ([bkosborne](https://github.com/bkosborne))
- Fixes \#341 \#284: Automating alias installation and template updates. [\#368](https://github.com/acquia/blt/pull/368) ([grasmash](https://github.com/grasmash))

**Fixed bugs:**

- fatal: A branch named 'master-build' already exists. [\#381](https://github.com/acquia/blt/issues/381)
- Fixing multiple deployment target bug. [\#373](https://github.com/acquia/blt/pull/373) ([grasmash](https://github.com/grasmash))
- Revert "Modify deploy phing to enable multiple environment deployments." [\#372](https://github.com/acquia/blt/pull/372) ([grasmash](https://github.com/grasmash))
- Modify deploy phing to enable multiple environment deployments. [\#363](https://github.com/acquia/blt/pull/363) ([marksakurada](https://github.com/marksakurada))

**Closed issues:**

- Move all common settings files to `sites/all/settings` [\#147](https://github.com/acquia/blt/issues/147)

**Misc merged pull requests**

- Updating documentation. [\#383](https://github.com/acquia/blt/pull/383) ([grasmash](https://github.com/grasmash))
- Update RELEASE.md [\#378](https://github.com/acquia/blt/pull/378) ([grasmash](https://github.com/grasmash))
- Updating CONTRIBUTING.md and RELEASE.md [\#371](https://github.com/acquia/blt/pull/371) ([grasmash](https://github.com/grasmash))

## [8.4.0](https://github.com/acquia/blt/tree/8.4.0) (2016-09-09)
[Full Changelog](https://github.com/acquia/blt/compare/8.3.4...8.4.0)

**Implemented enhancements:**

- local-sync.xml tasks should use drush instead of exec and aliases [\#56](https://github.com/acquia/blt/issues/56)
- Bolt should adhere to verbose options and not hardcode them [\#36](https://github.com/acquia/blt/issues/36)
- Removing extraneous base.settings.php. [\#367](https://github.com/acquia/blt/pull/367) ([grasmash](https://github.com/grasmash))
- Fixes \#36, \#56: Making DrushTask conform to Phing verbosity. Converting \<exec\> instances to \<drush\>. [\#366](https://github.com/acquia/blt/pull/366) ([grasmash](https://github.com/grasmash))
- Making repetitive messages less verbose. [\#365](https://github.com/acquia/blt/pull/365) ([grasmash](https://github.com/grasmash))
- Moving default settings files out of template. [\#364](https://github.com/acquia/blt/pull/364) ([grasmash](https://github.com/grasmash))
- Adding patches and tmp to deploy excludes [\#362](https://github.com/acquia/blt/pull/362) ([dpagini](https://github.com/dpagini))

## [8.3.4](https://github.com/acquia/blt/tree/8.3.4) (2016-09-02)
[Full Changelog](https://github.com/acquia/blt/compare/8.3.3...8.3.4)

**Implemented enhancements:**

- BLT doesn't define file system storage intelligently [\#211](https://github.com/acquia/blt/issues/211)
- Fixes \#211: Store filepaths intelligently. [\#359](https://github.com/acquia/blt/pull/359) ([grasmash](https://github.com/grasmash))
- Add configuration for filesystem settings. \(\#211\) [\#322](https://github.com/acquia/blt/pull/322) ([pixlkat](https://github.com/pixlkat))
- Resolves \#44: Register lint:twig console command. [\#297](https://github.com/acquia/blt/pull/297) ([grasmash](https://github.com/grasmash))

**Fixed bugs:**

- drush problem with deploy:acsf:init [\#356](https://github.com/acquia/blt/issues/356)
- VM Initialization \(./blt.sh vm:init\) freezes in terminal when copying drush aliases [\#241](https://github.com/acquia/blt/issues/241)
- Fixing bug in `blt init` [\#360](https://github.com/acquia/blt/pull/360) ([grasmash](https://github.com/grasmash))
- Fixes \#356: deploy:acsf:init uses wrong docroot. [\#357](https://github.com/acquia/blt/pull/357) ([grasmash](https://github.com/grasmash))

**Misc merged pull requests**

- Fix the setup amp stack anchor. [\#355](https://github.com/acquia/blt/pull/355) ([naveenvalecha](https://github.com/naveenvalecha))
- Adding CHANGELOG.md and generator settings. [\#354](https://github.com/acquia/blt/pull/354) ([grasmash](https://github.com/grasmash))

## [8.3.3](https://github.com/acquia/blt/tree/8.3.3) (2016-09-01)
[Full Changelog](https://github.com/acquia/blt/compare/8.3.2...8.3.3)

**Implemented enhancements:**

- Move tests/phpunit/Bolt tests into /tests [\#295](https://github.com/acquia/blt/issues/295)
- Completing pipelines build file. [\#351](https://github.com/acquia/blt/pull/351) ([grasmash](https://github.com/grasmash))
- Tweaking verbosity. [\#349](https://github.com/acquia/blt/pull/349) ([grasmash](https://github.com/grasmash))
- Increasing verbosity of all exec tasks. [\#347](https://github.com/acquia/blt/pull/347) ([grasmash](https://github.com/grasmash))

**Fixed bugs:**

- Configuration written to settings.php during install [\#345](https://github.com/acquia/blt/issues/345)
- Issue \#345: Changing require\_once\(\) to require\(\). [\#346](https://github.com/acquia/blt/pull/346) ([grasmash](https://github.com/grasmash))

**Misc merged pull requests**

- Switch -Dbehat.param to path in single behat test example. [\#353](https://github.com/acquia/blt/pull/353) ([seanpclark](https://github.com/seanpclark))

## [8.3.2](https://github.com/acquia/blt/tree/8.3.2) (2016-08-31)
[Full Changelog](https://github.com/acquia/blt/compare/8.3.1...8.3.2)

**Implemented enhancements:**

- NPM management of deployed front-end libraries [\#333](https://github.com/acquia/blt/issues/333)
- Add nodejs frontend tools for drupalvm integration [\#324](https://github.com/acquia/blt/issues/324)
- Removing DevDesktop settings include. [\#343](https://github.com/acquia/blt/pull/343) ([grasmash](https://github.com/grasmash))
- Set perms on settings files. [\#342](https://github.com/acquia/blt/pull/342) ([danepowell](https://github.com/danepowell))
- Adding an update.sh script. [\#339](https://github.com/acquia/blt/pull/339) ([grasmash](https://github.com/grasmash))
- Issue \#333: Allow deployment of front-end libraries. [\#334](https://github.com/acquia/blt/pull/334) ([danepowell](https://github.com/danepowell))

**Fixed bugs:**

- override blt phing target [\#316](https://github.com/acquia/blt/issues/316)
- drush.wrapper broken by xdebug message [\#315](https://github.com/acquia/blt/issues/315)
- PHPUnit Tests should load project.local.yml [\#309](https://github.com/acquia/blt/issues/309)
- Removing Phantom JS CDN URL. [\#340](https://github.com/acquia/blt/pull/340) ([grasmash](https://github.com/grasmash))
- Fixes \#315: Resolving xdebug and drush.wrapper bug. [\#337](https://github.com/acquia/blt/pull/337) ([grasmash](https://github.com/grasmash))
- Ignoring a lightning patch. [\#335](https://github.com/acquia/blt/pull/335) ([grasmash](https://github.com/grasmash))

**Closed issues:**

- Clean up the Continuous Integration instructions [\#319](https://github.com/acquia/blt/issues/319)

**Misc merged pull requests**

- The URL in template README.md is malformed [\#336](https://github.com/acquia/blt/pull/336) ([bhasselbeck](https://github.com/bhasselbeck))
- Added tips on features wrappers. [\#330](https://github.com/acquia/blt/pull/330) ([danepowell](https://github.com/danepowell))
- Setup and deploy should install frontend dependencies. [\#327](https://github.com/acquia/blt/pull/327) ([danepowell](https://github.com/danepowell))
- Felt backwards to me. [\#326](https://github.com/acquia/blt/pull/326) ([justinlevi](https://github.com/justinlevi))
- Githiub BLT Issue \#324: Includes NodeJS tools as well as php-bcmath… [\#325](https://github.com/acquia/blt/pull/325) ([bhasselbeck](https://github.com/bhasselbeck))
- \#319 - Cleaning up ci.md [\#320](https://github.com/acquia/blt/pull/320) ([webkenny](https://github.com/webkenny))
- Updated editorconfig for composer.json. [\#318](https://github.com/acquia/blt/pull/318) ([danepowell](https://github.com/danepowell))
- Allow overrides of blt phing targets: fixes \#316. [\#317](https://github.com/acquia/blt/pull/317) ([dpagini](https://github.com/dpagini))
- Move phpunit tests \(\#295\) [\#313](https://github.com/acquia/blt/pull/313) ([pixlkat](https://github.com/pixlkat))
- PHPUnit/TestBase.php import project.local.yml overrides [\#311](https://github.com/acquia/blt/pull/311) ([dpagini](https://github.com/dpagini))
- Fixing working directory for drush tasks. [\#310](https://github.com/acquia/blt/pull/310) ([grasmash](https://github.com/grasmash))
- Simplifying drupal vm aliases. [\#308](https://github.com/acquia/blt/pull/308) ([grasmash](https://github.com/grasmash))
- Adding pipelines WIP. [\#307](https://github.com/acquia/blt/pull/307) ([grasmash](https://github.com/grasmash))
- Move git hooks [\#306](https://github.com/acquia/blt/pull/306) ([grasmash](https://github.com/grasmash))
- Document how to handle config and content conflicts. [\#305](https://github.com/acquia/blt/pull/305) ([danepowell](https://github.com/danepowell))
- Moving git-hooks out of template. [\#304](https://github.com/acquia/blt/pull/304) ([grasmash](https://github.com/grasmash))
- Add documentation for running a single behat test with phing. [\#286](https://github.com/acquia/blt/pull/286) ([marksakurada](https://github.com/marksakurada))

## [8.3.1](https://github.com/acquia/blt/tree/8.3.1) (2016-08-16)
[Full Changelog](https://github.com/acquia/blt/compare/8.3.0...8.3.1)

**Closed issues:**

- PhantomJS installation fails 403 Issue. [\#223](https://github.com/acquia/blt/issues/223)
- Allow separate setup and build frontend tasks [\#221](https://github.com/acquia/blt/issues/221)
- When using VM built with vm:init, NFS synced folder doesn't always mount correctly [\#214](https://github.com/acquia/blt/issues/214)
- Remove architecture.md [\#204](https://github.com/acquia/blt/issues/204)
- Travis CI Automated Deployment Problems [\#196](https://github.com/acquia/blt/issues/196)
- Simplify front end file inclusion [\#146](https://github.com/acquia/blt/issues/146)
- Difference between PHPUnit Tests included with Bolt versus PHPUnit tests in my custom module [\#143](https://github.com/acquia/blt/issues/143)
- Site installs crash if files directory is not empty [\#128](https://github.com/acquia/blt/issues/128)
- Installation script fails when using VM and configuration directory exists [\#64](https://github.com/acquia/blt/issues/64)

**Misc merged pull requests**

- Resolves \#204: Removing architecture.md. [\#303](https://github.com/acquia/blt/pull/303) ([grasmash](https://github.com/grasmash))
- Improving upgrade path. [\#302](https://github.com/acquia/blt/pull/302) ([grasmash](https://github.com/grasmash))
- Removing composer-patches fork. [\#301](https://github.com/acquia/blt/pull/301) ([grasmash](https://github.com/grasmash))
- Fixing bug in docs deletion. [\#300](https://github.com/acquia/blt/pull/300) ([grasmash](https://github.com/grasmash))
- Replaced require with require\_once in settings.php and blt.settings.php [\#298](https://github.com/acquia/blt/pull/298) ([aweingarten](https://github.com/aweingarten))
- Resolves \#196: Travis CI documentation. [\#293](https://github.com/acquia/blt/pull/293) ([grasmash](https://github.com/grasmash))
- Updating phantomjs-installer to 2.x. [\#292](https://github.com/acquia/blt/pull/292) ([grasmash](https://github.com/grasmash))
- Resolves \#221: Adding frontend-setup target-hook. [\#291](https://github.com/acquia/blt/pull/291) ([grasmash](https://github.com/grasmash))
- Resolves \#146: Simplify frontend file inclusion. [\#289](https://github.com/acquia/blt/pull/289) ([grasmash](https://github.com/grasmash))
- Update top-level .editorconfig to include composer.json indent size. [\#287](https://github.com/acquia/blt/pull/287) ([jrbeeman](https://github.com/jrbeeman))
- \[BUGFIX\] Tests may fail due to PhantomJs not ready [\#283](https://github.com/acquia/blt/pull/283) ([mickaelperrin](https://github.com/mickaelperrin))
- Updated features doc. [\#281](https://github.com/acquia/blt/pull/281) ([danepowell](https://github.com/danepowell))

## [8.3.0](https://github.com/acquia/blt/tree/8.3.0) (2016-08-11)
[Full Changelog](https://github.com/acquia/blt/compare/8.2.0...8.3.0)

**Implemented enhancements:**

- Make -r in drush.wrapper read from drush.root in project.yml [\#262](https://github.com/acquia/blt/issues/262)
- Get project prefix from project.yml for git-commit hook [\#249](https://github.com/acquia/blt/issues/249)

**Fixed bugs:**

- TravisCI installs failing [\#273](https://github.com/acquia/blt/issues/273)
- The local:refresh task overwrites local.settings.php [\#248](https://github.com/acquia/blt/issues/248)
- Issue updating BLT [\#245](https://github.com/acquia/blt/issues/245)

**Closed issues:**

- Documentation Improvements [\#261](https://github.com/acquia/blt/issues/261)
- Document how to run a partial set of tests [\#243](https://github.com/acquia/blt/issues/243)
- Patches pulled from Drupal.org's core issue queue do not apply against drupal/core Composer dependency [\#240](https://github.com/acquia/blt/issues/240)
- Can't use composer to require new modules [\#238](https://github.com/acquia/blt/issues/238)
- Document how to modify deploy excludes [\#237](https://github.com/acquia/blt/issues/237)
- Can BLT projects be built without Lightning? [\#235](https://github.com/acquia/blt/issues/235)
- Cloud hook permissions are not being passed to the deployed artifact. [\#233](https://github.com/acquia/blt/issues/233)
- Force certain directories when deploying to Acquia Cloud [\#227](https://github.com/acquia/blt/issues/227)
- Improve composer documentation [\#226](https://github.com/acquia/blt/issues/226)
- Document lightning requirement for npm [\#220](https://github.com/acquia/blt/issues/220)
- Document how to commit dependencies [\#219](https://github.com/acquia/blt/issues/219)
- Local setup fails on Drupal\Core\Installer\Exception\AlreadyInstalledException + Contains unmentioned dependencies [\#218](https://github.com/acquia/blt/issues/218)
- Investigate converting BLT into a composer package [\#213](https://github.com/acquia/blt/issues/213)
- why is composer.json using packagist instead of https://packages.drupal.org/8?  [\#187](https://github.com/acquia/blt/issues/187)
- Patch failures should cause composer install to fail [\#183](https://github.com/acquia/blt/issues/183)
- Document using Behat with Drupal VM [\#176](https://github.com/acquia/blt/issues/176)
- ./blt.sh blt:update error - Update seems broken on Windows & Mac [\#171](https://github.com/acquia/blt/issues/171)
- composer.json install-path for custom module hosted externally? [\#170](https://github.com/acquia/blt/issues/170)
- Git PHPUnit tests take a reeeeally long time [\#166](https://github.com/acquia/blt/issues/166)
- Drupal VM Build Failure when using deafult box/config.yml [\#161](https://github.com/acquia/blt/issues/161)
- Rename build dir [\#160](https://github.com/acquia/blt/issues/160)
- Some files are not removed from build artifact [\#157](https://github.com/acquia/blt/issues/157)
- Support alternate front end build tasks [\#154](https://github.com/acquia/blt/issues/154)
- project.acquia\_subname should be defined or otherwise replaced in project.yml [\#139](https://github.com/acquia/blt/issues/139)
- Permission Denied on blt bash alias creation [\#133](https://github.com/acquia/blt/issues/133)
- Command site-install needs a higher bootstrap level to run - you will need to invoke drush from a more functional Drupal environment to run this command. [\#132](https://github.com/acquia/blt/issues/132)
- Incorrect link [\#118](https://github.com/acquia/blt/issues/118)
- Create's output 'next instructions' are out of date [\#109](https://github.com/acquia/blt/issues/109)
- Cannot Write Settings.php  [\#103](https://github.com/acquia/blt/issues/103)
- Build failing on drush alias [\#101](https://github.com/acquia/blt/issues/101)
- Add test coverage for ACSF configuration. [\#90](https://github.com/acquia/blt/issues/90)
- grasmash/phing composer dependency Build Failure [\#88](https://github.com/acquia/blt/issues/88)
- Enable local Twig Debugging [\#85](https://github.com/acquia/blt/issues/85)
- \[RFC\] Change the name to avoid confusion with the CMS named Bolt. [\#81](https://github.com/acquia/blt/issues/81)
- Avoiding Github rate limiting [\#70](https://github.com/acquia/blt/issues/70)
- Make vendor name configurable [\#67](https://github.com/acquia/blt/issues/67)
- Distinction needed between 'CI' environment and 'local' environment [\#52](https://github.com/acquia/blt/issues/52)
- ACSF does not get hash salt set [\#46](https://github.com/acquia/blt/issues/46)
- Running setup:bolt:update has error [\#45](https://github.com/acquia/blt/issues/45)
- Provide default services.yml, including APCu config [\#40](https://github.com/acquia/blt/issues/40)
- Document overriding Phing variable values [\#24](https://github.com/acquia/blt/issues/24)
- Improve DX of project creation [\#23](https://github.com/acquia/blt/issues/23)
- Generating a deployment artifact for ACE is slow [\#22](https://github.com/acquia/blt/issues/22)
- Example factory hooks. [\#21](https://github.com/acquia/blt/issues/21)
- How do you use standard/minimal core profiles? [\#20](https://github.com/acquia/blt/issues/20)
- Typo in deploy:artifact:add-remote usage. [\#16](https://github.com/acquia/blt/issues/16)
- PHPUnit Drush test should use the actual local URL [\#12](https://github.com/acquia/blt/issues/12)
- PHPUnit Git tests shouldn't create actual commits [\#11](https://github.com/acquia/blt/issues/11)
- composer install is run twice on initial setup [\#8](https://github.com/acquia/blt/issues/8)
- Switch documentation to not use line breaks at 80 cols [\#4](https://github.com/acquia/blt/issues/4)

**Misc merged pull requests**

- Resolves \#243: Document how to run a partial set of tests. [\#282](https://github.com/acquia/blt/pull/282) ([grasmash](https://github.com/grasmash))
- Resolves \#219: Documenting committing dependencies. [\#280](https://github.com/acquia/blt/pull/280) ([grasmash](https://github.com/grasmash))
- Resolves \#226: Adding composer docs. [\#278](https://github.com/acquia/blt/pull/278) ([grasmash](https://github.com/grasmash))
- Resolves \#237: Document deploy excludes. [\#277](https://github.com/acquia/blt/pull/277) ([grasmash](https://github.com/grasmash))
- Making drush docroot smarter. [\#276](https://github.com/acquia/blt/pull/276) ([grasmash](https://github.com/grasmash))
- Moving docs to readme. [\#275](https://github.com/acquia/blt/pull/275) ([grasmash](https://github.com/grasmash))
- Adding blt extension docs. [\#272](https://github.com/acquia/blt/pull/272) ([grasmash](https://github.com/grasmash))
- \[BUGFIX\] Failed Behat tests keeps pahntomJS running [\#271](https://github.com/acquia/blt/pull/271) ([mickaelperrin](https://github.com/mickaelperrin))
- Mkdocs [\#270](https://github.com/acquia/blt/pull/270) ([grasmash](https://github.com/grasmash))
- Fixed broken git commit msg hook. [\#269](https://github.com/acquia/blt/pull/269) ([danepowell](https://github.com/danepowell))
- Mkdocs [\#268](https://github.com/acquia/blt/pull/268) ([grasmash](https://github.com/grasmash))
- Mkdocs [\#267](https://github.com/acquia/blt/pull/267) ([grasmash](https://github.com/grasmash))
- Updating mkdocs to fix build errors. [\#266](https://github.com/acquia/blt/pull/266) ([grasmash](https://github.com/grasmash))
- Replace blt sh mentions with blt alias. [\#263](https://github.com/acquia/blt/pull/263) ([ChuChuNaKu](https://github.com/ChuChuNaKu))
- Updating Drupal Console. [\#258](https://github.com/acquia/blt/pull/258) ([grasmash](https://github.com/grasmash))
- Updating deploy excludes. [\#257](https://github.com/acquia/blt/pull/257) ([grasmash](https://github.com/grasmash))
- Resolves \#249: Adding yaml parser to git-commit hook. [\#256](https://github.com/acquia/blt/pull/256) ([grasmash](https://github.com/grasmash))
- Update repo-architecture.md [\#239](https://github.com/acquia/blt/pull/239) ([rhuffstedtler](https://github.com/rhuffstedtler))
- Removing undocumented bower dependency. [\#236](https://github.com/acquia/blt/pull/236) ([grasmash](https://github.com/grasmash))
- Issue 233: Removing --no-p option from rsync command in deploy:copy task [\#234](https://github.com/acquia/blt/pull/234) ([msherron](https://github.com/msherron))
- Remove scripts/drupal directory from blt/update-scaffold [\#232](https://github.com/acquia/blt/pull/232) ([pixlkat](https://github.com/pixlkat))
- Making security test failure more verbose. [\#231](https://github.com/acquia/blt/pull/231) ([grasmash](https://github.com/grasmash))
- Updating drupal-scaffold. [\#230](https://github.com/acquia/blt/pull/230) ([grasmash](https://github.com/grasmash))
- \#227 Force certain directories when deploying to Acquia Cloud. [\#228](https://github.com/acquia/blt/pull/228) ([webkenny](https://github.com/webkenny))
- Update release-process.md to fix typo [\#225](https://github.com/acquia/blt/pull/225) ([kmbremner](https://github.com/kmbremner))
- \[console\] Update Drupal Console to 1.0 ver. [\#224](https://github.com/acquia/blt/pull/224) ([jmolivas](https://github.com/jmolivas))
- Update includes.settings.php [\#222](https://github.com/acquia/blt/pull/222) ([janaksingh](https://github.com/janaksingh))
- Converting BLT to composer package. [\#217](https://github.com/acquia/blt/pull/217) ([grasmash](https://github.com/grasmash))
- Ignoring Behat tests with PHPCS, adding style-guide dir exemption. [\#216](https://github.com/acquia/blt/pull/216) ([grasmash](https://github.com/grasmash))
- Fixes \#214: Fix default Drupal VM synced\_folder path doc. [\#215](https://github.com/acquia/blt/pull/215) ([geerlingguy](https://github.com/geerlingguy))
- Don't overwrite local config files [\#210](https://github.com/acquia/blt/pull/210) ([gapple](https://github.com/gapple))
- Adding docroot to drush.wrapper. [\#209](https://github.com/acquia/blt/pull/209) ([grasmash](https://github.com/grasmash))
- Fixed dev env detection on ACSF. [\#207](https://github.com/acquia/blt/pull/207) ([danepowell](https://github.com/danepowell))
- Fix permission changes to default sites directory contents [\#206](https://github.com/acquia/blt/pull/206) ([gapple](https://github.com/gapple))
- Removing Icon from gitignore [\#205](https://github.com/acquia/blt/pull/205) ([CashWilliams](https://github.com/CashWilliams))
- Ignore custom theme node\_modules folder [\#203](https://github.com/acquia/blt/pull/203) ([justinlevi](https://github.com/justinlevi))
- Language update [\#202](https://github.com/acquia/blt/pull/202) ([justinlevi](https://github.com/justinlevi))
- Fixing prompt for BLT alias. [\#201](https://github.com/acquia/blt/pull/201) ([grasmash](https://github.com/grasmash))
- Subversion needed for ./blt.sh blt:update in VM [\#200](https://github.com/acquia/blt/pull/200) ([justinlevi](https://github.com/justinlevi))
- Fixing up drush.wrapper. [\#199](https://github.com/acquia/blt/pull/199) ([grasmash](https://github.com/grasmash))
- Update composer.json [\#198](https://github.com/acquia/blt/pull/198) ([skippednote](https://github.com/skippednote))
- Correctly detect environments on ACSF. [\#197](https://github.com/acquia/blt/pull/197) ([danepowell](https://github.com/danepowell))
- Adding support for custom commands in frontend and setup targets. [\#195](https://github.com/acquia/blt/pull/195) ([grasmash](https://github.com/grasmash))
- Revert "Adding support for custom commands in frontend and setup targets." [\#194](https://github.com/acquia/blt/pull/194) ([grasmash](https://github.com/grasmash))
- Adding support for custom commands in frontend and setup targets. [\#193](https://github.com/acquia/blt/pull/193) ([grasmash](https://github.com/grasmash))
- Adding composer validation early in Travis build. [\#192](https://github.com/acquia/blt/pull/192) ([grasmash](https://github.com/grasmash))
- Support composer patches. [\#191](https://github.com/acquia/blt/pull/191) ([danepowell](https://github.com/danepowell))
- Adding more excludes for deployments. [\#189](https://github.com/acquia/blt/pull/189) ([grasmash](https://github.com/grasmash))
- Adding docs for using local patches. [\#188](https://github.com/acquia/blt/pull/188) ([grasmash](https://github.com/grasmash))
- Update local-development.md [\#186](https://github.com/acquia/blt/pull/186) ([grasmash](https://github.com/grasmash))
- Composer install should fail on bad patches. [\#185](https://github.com/acquia/blt/pull/185) ([danepowell](https://github.com/danepowell))
- Provide temp files location in default local settings. [\#184](https://github.com/acquia/blt/pull/184) ([CashWilliams](https://github.com/CashWilliams))
- Adding install-phantomjs script for composer. [\#182](https://github.com/acquia/blt/pull/182) ([grasmash](https://github.com/grasmash))
- Ensuring that project.local.yml overrides core yml values. [\#181](https://github.com/acquia/blt/pull/181) ([grasmash](https://github.com/grasmash))
- Minor Typo fix and updating default selenium port [\#178](https://github.com/acquia/blt/pull/178) ([justinlevi](https://github.com/justinlevi))
- Update local-development.md [\#177](https://github.com/acquia/blt/pull/177) ([grasmash](https://github.com/grasmash))
- Tweaking deploy excludes. [\#175](https://github.com/acquia/blt/pull/175) ([grasmash](https://github.com/grasmash))
- Updated update scaffold. [\#173](https://github.com/acquia/blt/pull/173) ([danepowell](https://github.com/danepowell))
- Defining custom docroot for Drupal VM in project.local.yml. [\#172](https://github.com/acquia/blt/pull/172) ([grasmash](https://github.com/grasmash))
- Clarifying load test environments [\#169](https://github.com/acquia/blt/pull/169) ([ghazlewood](https://github.com/ghazlewood))
- Resolves \#166: Speed up GitTest commit-msg checks. [\#168](https://github.com/acquia/blt/pull/168) ([grasmash](https://github.com/grasmash))
- Removing :artifact from deploy targets. [\#167](https://github.com/acquia/blt/pull/167) ([grasmash](https://github.com/grasmash))
- Improve composer validation. [\#165](https://github.com/acquia/blt/pull/165) ([danepowell](https://github.com/danepowell))
- Changing deploy to use rsync. [\#162](https://github.com/acquia/blt/pull/162) ([grasmash](https://github.com/grasmash))
- Allow project.local.yml for different local environments. [\#158](https://github.com/acquia/blt/pull/158) ([damontgomery](https://github.com/damontgomery))
- Minor update scaffold cleanup. [\#156](https://github.com/acquia/blt/pull/156) ([danepowell](https://github.com/danepowell))
- Fixing remote repo value. [\#155](https://github.com/acquia/blt/pull/155) ([grasmash](https://github.com/grasmash))
- Workin on BLT deploys. \(\#152\) [\#153](https://github.com/acquia/blt/pull/153) ([grasmash](https://github.com/grasmash))
- Workin on BLT deploys. [\#152](https://github.com/acquia/blt/pull/152) ([grasmash](https://github.com/grasmash))
- Don't fail on chmod. [\#151](https://github.com/acquia/blt/pull/151) ([danepowell](https://github.com/danepowell))
- Cleaning vendor dir of deployment artifact. [\#150](https://github.com/acquia/blt/pull/150) ([grasmash](https://github.com/grasmash))
- Adding deploy.dryRun param for deploy:artifact target. [\#149](https://github.com/acquia/blt/pull/149) ([grasmash](https://github.com/grasmash))
- Adding PHP Bz2 to Drupal VM config. [\#145](https://github.com/acquia/blt/pull/145) ([grasmash](https://github.com/grasmash))
- Fixing failing Behat tests in child project. [\#144](https://github.com/acquia/blt/pull/144) ([grasmash](https://github.com/grasmash))
- Improving VM instructions. [\#142](https://github.com/acquia/blt/pull/142) ([grasmash](https://github.com/grasmash))
- Created common settings includes file. [\#141](https://github.com/acquia/blt/pull/141) ([danepowell](https://github.com/danepowell))
- Make project description configurable. [\#140](https://github.com/acquia/blt/pull/140) ([greylabel](https://github.com/greylabel))
- Update INSTALL.md [\#138](https://github.com/acquia/blt/pull/138) ([haynescw](https://github.com/haynescw))
- Making chmod on site/default optional. [\#137](https://github.com/acquia/blt/pull/137) ([grasmash](https://github.com/grasmash))
- Updated features doc. [\#136](https://github.com/acquia/blt/pull/136) ([danepowell](https://github.com/danepowell))
- Update php minimum requirement [\#135](https://github.com/acquia/blt/pull/135) ([skippednote](https://github.com/skippednote))
- Improving output of blt:alias. [\#134](https://github.com/acquia/blt/pull/134) ([grasmash](https://github.com/grasmash))
- Isolating Bolt PHPunit tests in Bolt subdir. [\#131](https://github.com/acquia/blt/pull/131) ([grasmash](https://github.com/grasmash))
- Updating default behat config for bolt updates. [\#130](https://github.com/acquia/blt/pull/130) ([grasmash](https://github.com/grasmash))
- Adding a default value for drush.default\_alias. [\#129](https://github.com/acquia/blt/pull/129) ([grasmash](https://github.com/grasmash))
- Make phpcs test 1st for faster test fail [\#127](https://github.com/acquia/blt/pull/127) ([grasmash](https://github.com/grasmash))
- Adding more detailed instructions to log output. [\#126](https://github.com/acquia/blt/pull/126) ([grasmash](https://github.com/grasmash))
- DX improvement by adding composer install to blt.sh [\#125](https://github.com/acquia/blt/pull/125) ([grasmash](https://github.com/grasmash))
- Adding local.protocol and local.hostname. [\#122](https://github.com/acquia/blt/pull/122) ([grasmash](https://github.com/grasmash))
- Rermoving unneeded files from update scripts. [\#121](https://github.com/acquia/blt/pull/121) ([grasmash](https://github.com/grasmash))
- Updating .gitignore, adding drupal console. [\#120](https://github.com/acquia/blt/pull/120) ([grasmash](https://github.com/grasmash))
- Specifying config dir in setup:drupal:install. [\#119](https://github.com/acquia/blt/pull/119) ([grasmash](https://github.com/grasmash))
- Allowing delete prompt to be skipped if do.abort = y. [\#115](https://github.com/acquia/blt/pull/115) ([grasmash](https://github.com/grasmash))
- build:validate:test is deprecated. [\#114](https://github.com/acquia/blt/pull/114) ([danepowell](https://github.com/danepowell))
- Support ACSF vanity domains. [\#112](https://github.com/acquia/blt/pull/112) ([danepowell](https://github.com/danepowell))
- Updating instructions output by create command. [\#110](https://github.com/acquia/blt/pull/110) ([grasmash](https://github.com/grasmash))
- Removed the now deleted deploy directory from the update-scaffold scr… [\#108](https://github.com/acquia/blt/pull/108) ([aweingarten](https://github.com/aweingarten))
- Fixing incorrect references to bolt. [\#107](https://github.com/acquia/blt/pull/107) ([grasmash](https://github.com/grasmash))
- Update local-development.md [\#106](https://github.com/acquia/blt/pull/106) ([grasmash](https://github.com/grasmash))
- Adding Drupal VM 3.1 integration. [\#105](https://github.com/acquia/blt/pull/105) ([grasmash](https://github.com/grasmash))
- Updating docs for Drupal VM. [\#104](https://github.com/acquia/blt/pull/104) ([grasmash](https://github.com/grasmash))
- Excluding Lightning AJAX Behat tests. [\#102](https://github.com/acquia/blt/pull/102) ([grasmash](https://github.com/grasmash))
- Update README.md to explain acronym [\#97](https://github.com/acquia/blt/pull/97) ([cam8001](https://github.com/cam8001))
- Fixing drush alias bug. [\#96](https://github.com/acquia/blt/pull/96) ([grasmash](https://github.com/grasmash))
- Adding tugboat support. [\#95](https://github.com/acquia/blt/pull/95) ([grasmash](https://github.com/grasmash))
- Forcing only stable versions of Lightning. [\#94](https://github.com/acquia/blt/pull/94) ([grasmash](https://github.com/grasmash))
- Fixed alias script after rename. [\#91](https://github.com/acquia/blt/pull/91) ([danepowell](https://github.com/danepowell))
- Renaming Bolt to BLT. [\#87](https://github.com/acquia/blt/pull/87) ([grasmash](https://github.com/grasmash))
- Enable local Twig debugging [\#86](https://github.com/acquia/blt/pull/86) ([dpagini](https://github.com/dpagini))
- Issue \#52: Splitting local tasks from CI tasks. [\#84](https://github.com/acquia/blt/pull/84) ([grasmash](https://github.com/grasmash))
- Updated composer docs. [\#83](https://github.com/acquia/blt/pull/83) ([danepowell](https://github.com/danepowell))
- Updated license in composer.json. [\#80](https://github.com/acquia/blt/pull/80) ([danepowell](https://github.com/danepowell))
- Use verb in past tense inc commit messages. [\#77](https://github.com/acquia/blt/pull/77) ([alexdesignworks](https://github.com/alexdesignworks))
- Add conditional around front:build so it will work without a theme. [\#76](https://github.com/acquia/blt/pull/76) ([damontgomery](https://github.com/damontgomery))
- Fixing deployments [\#75](https://github.com/acquia/blt/pull/75) ([grasmash](https://github.com/grasmash))
- Fixed Travis deploys. [\#74](https://github.com/acquia/blt/pull/74) ([danepowell](https://github.com/danepowell))
- Test. [\#73](https://github.com/acquia/blt/pull/73) ([grasmash](https://github.com/grasmash))
- Fixed config import on site installs. [\#69](https://github.com/acquia/blt/pull/69) ([danepowell](https://github.com/danepowell))
- Make vendor name configurable. [\#68](https://github.com/acquia/blt/pull/68) ([greylabel](https://github.com/greylabel))
- Fixes an issue where if no front end exists, build fails [\#66](https://github.com/acquia/blt/pull/66) ([kylebrowning](https://github.com/kylebrowning))
- Adding warning when xdebug is enabled. [\#62](https://github.com/acquia/blt/pull/62) ([grasmash](https://github.com/grasmash))
- Run automated tests on live dbs. [\#61](https://github.com/acquia/blt/pull/61) ([danepowell](https://github.com/danepowell))
- Improve Travis CI deployments. [\#60](https://github.com/acquia/blt/pull/60) ([danepowell](https://github.com/danepowell))
- Deploy bug: get the current branch name for the deployment. [\#58](https://github.com/acquia/blt/pull/58) ([damontgomery](https://github.com/damontgomery))
- Documentation on Drush aliases. [\#57](https://github.com/acquia/blt/pull/57) ([danepowell](https://github.com/danepowell))
- Fix formatting for multi-line preformatted text. [\#51](https://github.com/acquia/blt/pull/51) ([geerlingguy](https://github.com/geerlingguy))
- Updated features workflow doc. [\#50](https://github.com/acquia/blt/pull/50) ([danepowell](https://github.com/danepowell))
- Update composer for lightning [\#49](https://github.com/acquia/blt/pull/49) ([damontgomery](https://github.com/damontgomery))
- Make sure SSH key has 4096 bits [\#48](https://github.com/acquia/blt/pull/48) ([geerlingguy](https://github.com/geerlingguy))
- Resolves \#40: Disable APCu caching to prevent memory exhaustion [\#43](https://github.com/acquia/blt/pull/43) ([danepowell](https://github.com/danepowell))
- Removing branch argument from deploy tasks. [\#42](https://github.com/acquia/blt/pull/42) ([grasmash](https://github.com/grasmash))
- Added docs on field management using Features. [\#41](https://github.com/acquia/blt/pull/41) ([danepowell](https://github.com/danepowell))
- Updating Lightning to RC4. [\#39](https://github.com/acquia/blt/pull/39) ([grasmash](https://github.com/grasmash))
- Improving dev desktop settings.php compatibility. [\#37](https://github.com/acquia/blt/pull/37) ([grasmash](https://github.com/grasmash))
- Cleans up spacing in composer.json [\#35](https://github.com/acquia/blt/pull/35) ([kylebrowning](https://github.com/kylebrowning))
- Adding pre-commit hook to setup:bolt:update. [\#33](https://github.com/acquia/blt/pull/33) ([grasmash](https://github.com/grasmash))
- Changing pre-commit phpcs validation to find docroot differently. [\#32](https://github.com/acquia/blt/pull/32) ([grasmash](https://github.com/grasmash))
- Cleaning up ACSF documentation. [\#29](https://github.com/acquia/blt/pull/29) ([grasmash](https://github.com/grasmash))
- Cleaning up example factory hooks. [\#28](https://github.com/acquia/blt/pull/28) ([grasmash](https://github.com/grasmash))
- Refactoring git pre-commit hook to improve performance. [\#27](https://github.com/acquia/blt/pull/27) ([grasmash](https://github.com/grasmash))
- Adds a couple of factory hook examples [\#26](https://github.com/acquia/blt/pull/26) ([kylebrowning](https://github.com/kylebrowning))
- Add directions for overridding the docroot used by Drush for Drupal VM. [\#25](https://github.com/acquia/blt/pull/25) ([geerlingguy](https://github.com/geerlingguy))
- Move Bolt's build status to the top of the README. [\#19](https://github.com/acquia/blt/pull/19) ([geerlingguy](https://github.com/geerlingguy))
- ACSF support for deploy step [\#18](https://github.com/acquia/blt/pull/18) ([damontgomery](https://github.com/damontgomery))
- Make Bolt alias compatible with all Unix environments. [\#15](https://github.com/acquia/blt/pull/15) ([danepowell](https://github.com/danepowell))
- Updating phing after upstream pull request was merged. [\#14](https://github.com/acquia/blt/pull/14) ([grasmash](https://github.com/grasmash))
- Validate composer files. [\#10](https://github.com/acquia/blt/pull/10) ([danepowell](https://github.com/danepowell))
- Fix formatting in local-development.md documentation. [\#7](https://github.com/acquia/blt/pull/7) ([geerlingguy](https://github.com/geerlingguy))
- Removing bolt: prefix from targets. [\#6](https://github.com/acquia/blt/pull/6) ([grasmash](https://github.com/grasmash))
- Removing 80 col line breaks from docs. [\#5](https://github.com/acquia/blt/pull/5) ([grasmash](https://github.com/grasmash))
- Support for aliases [\#2](https://github.com/acquia/blt/pull/2) ([damontgomery](https://github.com/damontgomery))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*