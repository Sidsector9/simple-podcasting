# Changelog

All notable changes to this project will be documented in this file, per [the Keep a Changelog standard](http://keepachangelog.com/).

## [Unreleased] - TBD

## [1.3.0] - 2022-10-18
**Note that this version bumps the minimum PHP version from 7.0 to 7.4 and the minimum WordPress version from 4.6 to 5.7.**

### Added
- Podcasts Taxonomy term(s) added in block settings (props [@helen](https://github.com/helen), [@jeffpaul](https://github.com/jeffpaul), [@faisal-alvi](https://github.com/faisal-alvi), [@peterwilsoncc](https://github.com/peterwilsoncc), [@cadic](https://github.com/cadic) via [#183](https://github.com/10up/simple-podcasting/pull/183)).
- Type of show setting for the podcast (props [@cadic](https://github.com/cadic), [@faisal-alvi](https://github.com/faisal-alvi), [@jeffpaul](https://github.com/jeffpaul) via [#188](https://github.com/10up/simple-podcasting/pull/188)).

### Changed
- Podcasting Categories and Sub-Categories (props [@zamanq](https://github.com/zamanq), [@jeffpaul](https://github.com/jeffpaul), [@dkotter](https://github.com/dkotter), [@cadic](https://github.com/cadic), [@dchucks](https://github.com/dchucks) via [#179](https://github.com/10up/simple-podcasting/pull/179)).
- Bumped minimum PHP version required from 7.0 to 7.4 (props [@peterwilsoncc](https://github.com/peterwilsoncc), [@cadic](https://github.com/cadic), [@jeffpaul](https://github.com/jeffpaul), [@vikrampm1](https://github.com/vikrampm1) via [#184](https://github.com/10up/simple-podcasting/pull/184)).
- Bumped minimum WordPress version required from 4.6 to 5.7 (props [@peterwilsoncc](https://github.com/peterwilsoncc), [@cadic](https://github.com/cadic), [@jeffpaul](https://github.com/jeffpaul), [@vikrampm1](https://github.com/vikrampm1) via [#184](https://github.com/10up/simple-podcasting/pull/184)).
- Upgrade dependencies (props [@cadic](https://github.com/cadic), [@faisal-alvi](https://github.com/faisal-alvi) via [#187](https://github.com/10up/simple-podcasting/pull/187)).

### Fixed
- Saving podcast enclosure with Classic Editor (props [@cadic](https://github.com/cadic), [@faisal-alvi](https://github.com/faisal-alvi) via [#186](https://github.com/10up/simple-podcasting/pull/186)).

### Security
- Bump `got` from 10.7.0 to 11.8.5 (props [@faisal-alvi](https://github.com/faisal-alvi), [@iamdharmesh](https://github.com/iamdharmesh), [@jeffpaul](https://github.com/jeffpaul) via [#185](https://github.com/10up/simple-podcasting/pull/185)).
- Bump `@wordpress/env` from 4.5.0 to 5.2.0 (props [@faisal-alvi](https://github.com/faisal-alvi), [@iamdharmesh](https://github.com/iamdharmesh), [@jeffpaul](https://github.com/jeffpaul) via [#185](https://github.com/10up/simple-podcasting/pull/185)).

## [1.2.4] - 2022-07-27
### Added
- Season number, episode number and episode type attributes can now be stored with a Podcast (props [@zamanq](https://github.com/zamanq), [@dchucks](https://github.com/dchucks), [@cadic](https://github.com/cadic) via [#175](https://github.com/10up/simple-podcasting/pull/175)).

### Changed
- Bump WordPress version "tested up to" 6.0 (props [@cadic](https://github.com/cadic) via [#171](https://github.com/10up/simple-podcasting/issues/171)).

### Fixed
- Incorrect Language value in the Feed (props [@zamanq](https://github.com/zamanq), [@dchucks](https://github.com/dchucks), [@cadic](https://github.com/cadic) via [#176](https://github.com/10up/simple-podcasting/pull/176)).

### Security
- Bump `terser` from 5.12.1 to 5.14.2 (props [@dependabot](https://github.com/apps/dependabot) via [#180](https://github.com/10up/simple-podcasting/pull/180)).

## [1.2.3] - 2022-04-28
### Added
- Compatibility tests against PHP 7 and 8 (props [@cadic](https://github.com/cadic), [@dkotter](https://github.com/dkotter), [@jeffpaul](https://github.com/jeffpaul) via [#150](https://github.com/10up/simple-podcasting/pull/150)).
- Default Pull Request Reviewers via CODEOWNERS file (props [@jeffpaul](https://github.com/jeffpaul), [@cadic](https://github.com/cadic) via [#156](https://github.com/10up/simple-podcasting/pull/156)).
- Dependency security scanning (props [@jeffpaul](https://github.com/jeffpaul) via [#168](https://github.com/10up/simple-podcasting/pull/168)).

### Changed
- Unit tests against PHP 8 (props [@cadic](https://github.com/cadic), [@dkotter](https://github.com/dkotter), [@jeffpaul](https://github.com/jeffpaul) via [#150](https://github.com/10up/simple-podcasting/pull/150)).
- Bump required PHP 7.0 (props [@cadic](https://github.com/cadic), [@dkotter](https://github.com/dkotter), [@jeffpaul](https://github.com/jeffpaul) via [#150](https://github.com/10up/simple-podcasting/pull/150)).
- Replaced custom commands with @10up/cypress-wp-utils in end-to-end tests (props [@dinhtungdu](https://github.com/dinhtungdu), [@cadic](https://github.com/cadic), [@jeffpaul](https://github.com/jeffpaul) via [#162](https://github.com/10up/simple-podcasting/pull/162)).

### Fixed
- Missing `<enclosure>` in feed item (props [@davexpression](https://github.com/davexpression), [@cadic](https://github.com/cadic), [@jeffpaul](https://github.com/jeffpaul) via [#147](https://github.com/10up/simple-podcasting/pull/147)).
- Failing Cypress test on WP Minimum (props [@dinhtungdu](https://github.com/dinhtungdu), [@cadic](https://github.com/cadic), [@jeffpaul](https://github.com/jeffpaul) via [#164](https://github.com/10up/simple-podcasting/pull/164)).
- Updated badges in readme (props [@cadic](https://github.com/cadic), [@jeffpaul](https://github.com/jeffpaul) via [#167](https://github.com/10up/simple-podcasting/pull/167)).

### Security
- Upgraded node dependencies (props [@cadic](https://github.com/cadic), [@iamdharmesh](https://github.com/iamdharmesh), [@jeffpaul](https://github.com/jeffpaul) via [#158](https://github.com/10up/simple-podcasting/pull/158) and [#163](https://github.com/10up/simple-podcasting/pull/163)).
- Bump async from 2.6.3 to 2.6.4 (props [@dependabot](https://github.com/apps/dependabot) via [#166](https://github.com/10up/simple-podcasting/pull/166)).
- Bump node-forge from 1.2.1 to 1.3.0 (props [@dependabot](https://github.com/apps/dependabot) via [#160](https://github.com/10up/simple-podcasting/pull/160)).
- Bump minimist from 1.2.5 to 1.2.6 (props [@dependabot](https://github.com/apps/dependabot) via [#159](https://github.com/10up/simple-podcasting/pull/159)).

## [1.2.2] - 2022-03-01
### Added
- Filter `simple_podcasting_feed_item` to modify RSS feed item data before output (props [@cadic](https://github.com/cadic), [@iamdharmesh](https://github.com/iamdharmesh), [@jeffpaul](https://github.com/jeffpaul) via [#144](https://github.com/10up/simple-podcasting/pull/144)).
- Unit tests (props [@cadic](https://github.com/cadic) via [#142](https://github.com/10up/simple-podcasting/pull/142), [@dkotter](https://github.com/dkotter), [@jeffpaul](https://github.com/jeffpaul)).
- GitHub action job to run PHPCS (props [@cadic](https://github.com/cadic), [@dkotter](https://github.com/dkotter) via [#136](https://github.com/10up/simple-podcasting/pull/136)).
- Auto-create pot file in languages folder during the build process (props [@dkotter](https://github.com/dkotter), [@cadic](https://github.com/cadic) via [#131](https://github.com/10up/simple-podcasting/pull/131)).

### Changed
- Bump WordPress "tested up to" version 5.9 (props [@sudip-10up](https://github.com/sudip-10up), [@cadic](https://github.com/cadic), [@peterwilsoncc](https://github.com/peterwilsoncc) via [#140](https://github.com/10up/simple-podcasting/pull/140)).

### Fixed
- End-to-end tests with WordPress 5.9 element IDs (props[@cadic](https://github.com/cadic), [@felipeelia](https://github.com/felipeelia), [@dinhtungdu](https://github.com/dinhtungdu) via [#146](https://github.com/10up/simple-podcasting/pull/146)).
- Podcast feed link output on Edit Podcast screen (props [@mehidi258](https://github.com/mehidi258), [@jeffpaul](https://github.com/jeffpaul), [@cadic](https://github.com/cadic) via [#139](https://github.com/10up/simple-podcasting/pull/139)).
- Bug fix for `is_feed` being called too early (props [@tomjn](https://github.com/tomjn), [@jeffpaul](https://github.com/jeffpaul) via [#135](https://github.com/10up/simple-podcasting/pull/135)).
- Missing and incorrect text-domain (props [@dkotter](https://github.com/dkotter), [@cadic](https://github.com/cadic) via [#131](https://github.com/10up/simple-podcasting/pull/131)).

### Security
- Bump `nanoid` from 3.1.25 to 3.2.0 (props [@dependabot](https://github.com/apps/dependabot) via [#143](https://github.com/10up/simple-podcasting/pull/143)).

## [1.2.1] - 2021-12-16
### Added
- Filter `simple_podcasting_episodes_per_page` to override default of 250 episodes per podcast feed (props [@pabamato](https://github.com/pabamato), [@dinhtungdu](https://github.com/dinhtungdu), [@monomo111](https://github.com/monomo111), [@jeffpaul](https://github.com/jeffpaul), [@jakemgold](https://github.com/jakemgold) via [#109](https://github.com/10up/simple-podcasting/pull/109)).
- End-to-end testing using Cypress and `wp-env` (props [@dinhtungdu](https://github.com/dinhtungdu), [@markjaquith](https://github.com/markjaquith), [@youknowriad](https://github.com/youknowriad), [@helen](https://github.com/helen) via [#115](https://github.com/10up/simple-podcasting/pull/115), [#117](https://github.com/10up/simple-podcasting/pull/117)).
- Issue management automation via GitHub Actions (props [@jeffpaul](https://github.com/jeffpaul) via [#119](https://github.com/10up/simple-podcasting/pull/119)).
- Pull request template (props [@jeffpaul](https://github.com/jeffpaul), [@dinhtungdu](https://github.com/dinhtungdu) via [#125](https://github.com/10up/simple-podcasting/pull/125)).

### Changed
- Default number of episodes in RSS feeds increased from 10 to 250 (props [@pabamato](https://github.com/pabamato), [@dinhtungdu](https://github.com/dinhtungdu), [@monomo111](https://github.com/monomo111), [@jeffpaul](https://github.com/jeffpaul), [@jakemgold](https://github.com/jakemgold) via [#109](https://github.com/10up/simple-podcasting/pull/109)).
- Use `@wordpress/scripts` as the build tool (props [@dinhtungdu](https://github.com/dinhtungdu) via [#114](https://github.com/10up/simple-podcasting/pull/114)).
- Bump WordPress version “tested up to” 5.8.1 (props [David Chabbi](https://www.linkedin.com/in/david-chabbi-985719b4/), [@jeffpaul](https://github.com/jeffpaul), [@pabamato](https://github.com/pabamato) via  [#106](https://github.com/10up/simple-podcasting/pull/106), [#110](https://github.com/10up/simple-podcasting/pull/110), [#124](https://github.com/10up/simple-podcasting/pull/124)).
- Documentation updates (props [@meszarosrob](https://github.com/meszarosrob), [@dinhtungdu](https://github.com/dinhtungdu) via [#101](https://github.com/10up/simple-podcasting/pull/101)).

### Fixed
- 'podcast' block core dependency  (props [@pabamato](https://github.com/pabamato), [@dinhtungdu](https://github.com/dinhtungdu), [@monomo111](https://github.com/monomo111), [@jeffpaul](https://github.com/jeffpaul), [@jakemgold](https://github.com/jakemgold) via [#109](https://github.com/10up/simple-podcasting/pull/109)).
- Minimum WordPress version used by `wp-env` (props [@dinhtungdu](https://github.com/dinhtungdu) via [#122](https://github.com/10up/simple-podcasting/pull/122)).

## [1.2.0] - 2020-07-10
### Added
- Podcast image in the taxonomy list table view (props [@Firestorm980](https://github.com/Firestorm980), [@helen](https://github.com/helen) via [#87](https://github.com/10up/simple-podcasting/pull/87)).
- Ability for user to transform to/from the podcast and audio blocks (props [@Firestorm980](https://github.com/Firestorm980), [@helen](https://github.com/helen) via [#85](https://github.com/10up/simple-podcasting/pull/85)).
- Core `MediaReplaceFlow` to edit the podcast media (props [@Firestorm980](https://github.com/Firestorm980), [@helen](https://github.com/helen) via [#86](https://github.com/10up/simple-podcasting/pull/86)).

### Changed
- GitHub Actions from HCL to YAML workflow syntax (props [@helen](https://github.com/helen) via [#78](https://github.com/10up/simple-podcasting/pull/78)).
- Stop committing built files (props [@helen](https://github.com/helen) via [#95](https://github.com/10up/simple-podcasting/pull/95)).
- Documentation updates (props [@jeffpaul](https://github.com/jeffpaul), [@nhalstead](https://github.com/nhalstead) via [#76](https://github.com/10up/simple-podcasting/pull/76), [#79](https://github.com/10up/simple-podcasting/pull/79)).

### Fixed
- Using the upload or drag and drop instead of media library populates duration and mimetype (props [@Firestorm980](https://github.com/Firestorm980), [@helen](https://github.com/helen) via [#82](https://github.com/10up/simple-podcasting/pull/82)).
- Issue where it is possible to add non-audio files to the Podcast block (props [@mattheu](https://github.com/mattheu) via [#77](https://github.com/10up/simple-podcasting/pull/77)).
- Issue where React would throw an error relating to keys for list items (props [@Firestorm980](https://github.com/Firestorm980), [@helen](https://github.com/helen) via [#85](https://github.com/10up/simple-podcasting/pull/85)).
- Ensure podcast-related meta is deleted after block is removed. (props [@dinhtungdu](https://github.com/dinhtungdu) via [#96](https://github.com/10up/simple-podcasting/pull/96)).

## [1.1.1] - 2019-08-02
### Added
- GitHub Actions for WordPress.org plugin deploy (props [@helen](https://github.com/helen) via [#75](https://github.com/10up/simple-podcasting/pull/75)).

### Fixed
- Compatibility with WordPress 5.2 (props [@adamsilverstein](https://github.com/adamsilverstein) via [#68](https://github.com/10up/simple-podcasting/pull/68), [#70](https://github.com/10up/simple-podcasting/pull/70)).
- Corrected `10up/wp_mock` reference for Composer (props [@oscarssanchez](https://github.com/oscarssanchez) via [#69](https://github.com/10up/simple-podcasting/pull/69)).

## [1.1.0] - 2018-12-04
### Added
- Retrieve metadata for externally hosted audio files in the block editor.
- Specify email address for a given podcast.
- Set language for a given podcast.
- Developers: Add linting for coding standards.

### Changed
- Clearer language on the add new podcast form.

### Fixed
- Delete all associated meta when block is removed from a post.
- Restore all block editor functionality to align with Gutenberg/block changes.
- Fully clear add new form after creating a new podcast.

## [1.0.1] - 2018-07-02
### Fixed
- Properly output podcast categories and subcategories in the feed.
- Avoid a minified JS error when selecting a podcast image.
- Display podcast summary on edit form.

## [1.0.0] - 2018-06-29
- Initial plugin release.

[Unreleased]: https://github.com/10up/simple-podcasting/compare/trunk...develop
[1.2.4]: https://github.com/10up/simple-podcasting/compare/1.2.3-deploy...1.2.4
[1.2.3]: https://github.com/10up/simple-podcasting/compare/1.2.2...1.2.3-deploy
[1.2.2]: https://github.com/10up/simple-podcasting/compare/1.2.1...1.2.2
[1.2.1]: https://github.com/10up/simple-podcasting/compare/1.2.0...1.2.1
[1.2.0]: https://github.com/10up/simple-podcasting/compare/1.1.1...1.2.0
[1.1.1]: https://github.com/10up/simple-podcasting/compare/f8a958c...1.1.1
[1.1.0]: https://github.com/10up/simple-podcasting/compare/1.0.1...f8a958c
[1.0.1]: https://github.com/10up/simple-podcasting/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/10up/simple-podcasting/releases/tag/1.0.0
