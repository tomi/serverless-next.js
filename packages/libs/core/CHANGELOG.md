# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [3.5.0-alpha.1](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.5.0-alpha.0...v3.5.0-alpha.1) (2021-10-13)

**Note:** Version bump only for package @sls-next/core

# [3.5.0-alpha.0](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.4.0...v3.5.0-alpha.0) (2021-10-06)

### Features

- **core, lambda-at-edge:** handle Redirects in uncached SSG Requests ([#1786](https://github.com/serverless-nextjs/serverless-next.js/issues/1786)) ([2a7cf73](https://github.com/serverless-nextjs/serverless-next.js/commit/2a7cf738d1fab0e73b5a39c2702e721af4884e29))

# [3.4.0](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.4.0-alpha.14...v3.4.0) (2021-10-02)

**Note:** Version bump only for package @sls-next/core

# [3.4.0-alpha.12](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.4.0-alpha.11...v3.4.0-alpha.12) (2021-09-27)

### Features

- **nextjs-component, core, lambda-at-edge:** experimental - add build.useV2Handler option to enable using genericized default/regeneration handlers ([#1747](https://github.com/serverless-nextjs/serverless-next.js/issues/1747)) ([afd8a79](https://github.com/serverless-nextjs/serverless-next.js/commit/afd8a79a5a19adb631f627198a9e7d904bbf34c6))

# [3.4.0-alpha.11](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.4.0-alpha.10...v3.4.0-alpha.11) (2021-09-25)

### Bug Fixes

- **core:** handle external redirect destinations with query parameters correctly ([#1744](https://github.com/serverless-nextjs/serverless-next.js/issues/1744)) ([58001fc](https://github.com/serverless-nextjs/serverless-next.js/commit/58001fc993c432af0309ccbbe4541a6bd1d00d08))

# [3.4.0-alpha.10](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.4.0-alpha.9...v3.4.0-alpha.10) (2021-09-24)

**Note:** Version bump only for package @sls-next/core

# [3.4.0-alpha.9](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.4.0-alpha.8...v3.4.0-alpha.9) (2021-09-17)

### Features

- **core, lambda-at-edge, nextjs-component:** experimental - allow serving static pages/data from origin request handler only (and disable origin response handler) ([#1696](https://github.com/serverless-nextjs/serverless-next.js/issues/1696)) ([7fcdc7f](https://github.com/serverless-nextjs/serverless-next.js/commit/7fcdc7fd4970402c7f19e09a7fa90d22a82804e4))

# [3.4.0-alpha.8](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.4.0-alpha.7...v3.4.0-alpha.8) (2021-09-15)

### Features

- **core, nextjs-component:** improve routing and support cross rewrites for consolidated API pages in default lambda ([#1693](https://github.com/serverless-nextjs/serverless-next.js/issues/1693)) ([f058d51](https://github.com/serverless-nextjs/serverless-next.js/commit/f058d5111d8ba1bcb02cc81cd4d52b43fd4d52ee))

# [3.4.0-alpha.6](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.4.0-alpha.5...v3.4.0-alpha.6) (2021-09-13)

### Bug Fixes

- **core:** fallback to using page's html render function when html is empty ([#1680](https://github.com/serverless-nextjs/serverless-next.js/issues/1680)) ([ef38698](https://github.com/serverless-nextjs/serverless-next.js/commit/ef38698dff32778904df7902fb51952256f43bd4))

# [3.4.0-alpha.1](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.4.0-alpha.0...v3.4.0-alpha.1) (2021-09-08)

### Features

- **core:** add domain locale detection for rewrites and non default locales ([#1640](https://github.com/serverless-nextjs/serverless-next.js/issues/1640)) ([#1641](https://github.com/serverless-nextjs/serverless-next.js/issues/1641)) ([cbab741](https://github.com/serverless-nextjs/serverless-next.js/commit/cbab7419e8bddfbde8b97104d0229307fc5694d8))

# [3.4.0-alpha.0](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.3.1-alpha.1...v3.4.0-alpha.0) (2021-09-03)

**Note:** Version bump only for package @sls-next/core

## [3.3.1-alpha.1](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.3.1-alpha.0...v3.3.1-alpha.1) (2021-09-02)

### Bug Fixes

- **lambda-at-edge, e2e-tests:** fix and add e2e tests for ISR pages when locales are used ([#1622](https://github.com/serverless-nextjs/serverless-next.js/issues/1622)) ([6acc057](https://github.com/serverless-nextjs/serverless-next.js/commit/6acc057aad85b4caab1e2f71db8f8a90b3b54fc1))

# [3.3.0](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.3.0-alpha.6...v3.3.0) (2021-09-01)

**Note:** Version bump only for package @sls-next/core

# [3.3.0-alpha.6](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.3.0-alpha.5...v3.3.0-alpha.6) (2021-08-31)

### Bug Fixes

- **core:** fix renderPageToHtml for work for all next.js versions ([#1611](https://github.com/serverless-nextjs/serverless-next.js/issues/1611)) ([d3a10b2](https://github.com/serverless-nextjs/serverless-next.js/commit/d3a10b2d7ed9d14afd1a09436f9fbf911fde001e))

# [3.3.0-alpha.5](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.3.0-alpha.4...v3.3.0-alpha.5) (2021-08-27)

### Bug Fixes

- **core, lambda-at-edge:** render page to HTML properly for next.js 11.1+ versions ([#1596](https://github.com/serverless-nextjs/serverless-next.js/issues/1596)) ([ee88a68](https://github.com/serverless-nextjs/serverless-next.js/commit/ee88a683792b972760067821e21f78654562c1ec))

# [3.3.0-alpha.3](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.3.0-alpha.2...v3.3.0-alpha.3) (2021-08-25)

### Bug Fixes

- **core:** fix preview mode with a dynamic route is used ([#1585](https://github.com/serverless-nextjs/serverless-next.js/issues/1585)) ([316bd2a](https://github.com/serverless-nextjs/serverless-next.js/commit/316bd2a348f726bf8fc116b8b759acd9103d5037)), closes [#1527](https://github.com/serverless-nextjs/serverless-next.js/issues/1527)

# [3.3.0-alpha.1](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.3.0-alpha.0...v3.3.0-alpha.1) (2021-08-21)

**Note:** Version bump only for package @sls-next/core

## [3.2.1-alpha.0](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.2.0...v3.2.1-alpha.0) (2021-08-04)

### Bug Fixes

- **core:** allow lowercase locale prefixes by standardizing locale casing on server-side, update locale redirect casing ([#1496](https://github.com/serverless-nextjs/serverless-next.js/issues/1496)) ([a8765d1](https://github.com/serverless-nextjs/serverless-next.js/commit/a8765d1ff0e34b2e8d5f185e3aea84afed59b009))

# [3.2.0](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.2.0-alpha.29...v3.2.0) (2021-08-03)

**Note:** Version bump only for package @sls-next/core

# [3.2.0-alpha.25](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.2.0-alpha.24...v3.2.0-alpha.25) (2021-08-02)

### Bug Fixes

- **core:** locale redirect should not be lowercased ([#1484](https://github.com/serverless-nextjs/serverless-next.js/issues/1484)) ([f4ea8f5](https://github.com/serverless-nextjs/serverless-next.js/commit/f4ea8f58c2d104b287d7e5342cbf794bd6689f31))

# [3.2.0-alpha.23](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.2.0-alpha.22...v3.2.0-alpha.23) (2021-07-31)

### Bug Fixes

- **core, lambda-at-edge:** do not replace .html for public files in r… ([#1473](https://github.com/serverless-nextjs/serverless-next.js/issues/1473)) ([62c0fe2](https://github.com/serverless-nextjs/serverless-next.js/commit/62c0fe2e0c9d6341831d496bf143369d8df0a93e))

# [3.2.0-alpha.17](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.2.0-alpha.16...v3.2.0-alpha.17) (2021-07-07)

**Note:** Version bump only for package @sls-next/core

# [3.2.0-alpha.13](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.2.0-alpha.12...v3.2.0-alpha.13) (2021-07-02)

**Note:** Version bump only for package @sls-next/core

# [3.2.0-alpha.12](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.2.0-alpha.11...v3.2.0-alpha.12) (2021-07-01)

**Note:** Version bump only for package @sls-next/core

# [3.2.0-alpha.11](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.2.0-alpha.10...v3.2.0-alpha.11) (2021-06-30)

### Bug Fixes

- **core:** support no-op rewrites ([#1329](https://github.com/serverless-nextjs/serverless-next.js/issues/1329)) ([27d1943](https://github.com/serverless-nextjs/serverless-next.js/commit/27d1943f2d193eecba7c8cb99d33ffcccb463e41))

# [3.2.0-alpha.7](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.2.0-alpha.6...v3.2.0-alpha.7) (2021-06-28)

### Features

- **core:** support locale-based domain redirects [wip] ([#1299](https://github.com/serverless-nextjs/serverless-next.js/issues/1299)) ([5836142](https://github.com/serverless-nextjs/serverless-next.js/commit/58361424be8e6f4fcfa69f6b5956d3cf1b55cd97))

# [3.2.0-alpha.6](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.2.0-alpha.5...v3.2.0-alpha.6) (2021-06-27)

**Note:** Version bump only for package @sls-next/core

# [3.2.0-alpha.2](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.2.0-alpha.1...v3.2.0-alpha.2) (2021-06-26)

**Note:** Version bump only for package @sls-next/core

## [3.1.1-alpha.0](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.1.0...v3.1.1-alpha.0) (2021-06-26)

### Bug Fixes

- **core:** add s-maxage=0 cache-control headers to redirect responses ([#1298](https://github.com/serverless-nextjs/serverless-next.js/issues/1298)) ([6220078](https://github.com/serverless-nextjs/serverless-next.js/commit/6220078cedac2c56ed0c314e0416890fab4aa891))

# [3.1.0](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.1.0-alpha.16...v3.1.0) (2021-06-25)

**Note:** Version bump only for package @sls-next/core

# [3.1.0-alpha.16](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.1.0-alpha.15...v3.1.0-alpha.16) (2021-06-25)

### Features

- **core:** add domain locale detection ([#1283](https://github.com/serverless-nextjs/serverless-next.js/issues/1283)) ([#1296](https://github.com/serverless-nextjs/serverless-next.js/issues/1296)) ([b331695](https://github.com/serverless-nextjs/serverless-next.js/commit/b33169526eb30aeffd5f1b95a781709019f00248))

# [3.1.0-alpha.14](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.1.0-alpha.13...v3.1.0-alpha.14) (2021-06-24)

### Bug Fixes

- **core, e2e-tests:** fix ISR, make e2e tests retryable ([#1290](https://github.com/serverless-nextjs/serverless-next.js/issues/1290)) ([83d19f0](https://github.com/serverless-nextjs/serverless-next.js/commit/83d19f0b607441a76746fa8cf4dacddd52d8b20a))

# [3.1.0-alpha.7](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.1.0-alpha.6...v3.1.0-alpha.7) (2021-06-22)

**Note:** Version bump only for package @sls-next/core

# [3.1.0-alpha.6](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.1.0-alpha.5...v3.1.0-alpha.6) (2021-06-21)

### Bug Fixes

- **core:** fix data route locales ([#1268](https://github.com/serverless-nextjs/serverless-next.js/issues/1268)) ([e1c8cd8](https://github.com/serverless-nextjs/serverless-next.js/commit/e1c8cd8e5cc36a20ec4363911a501f232f51bd04))

# [3.1.0-alpha.5](https://github.com/serverless-nextjs/serverless-next.js/compare/v3.1.0-alpha.4...v3.1.0-alpha.5) (2021-06-19)

**Note:** Version bump only for package @sls-next/core

# [1.0.0-alpha.24](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.23...@sls-next/core@1.0.0-alpha.24) (2021-06-16)

### Bug Fixes

- **core:** data request page JS path should use the one from the manifest ([#1241](https://github.com/serverless-nextjs/serverless-next.js/issues/1241)) ([f774a30](https://github.com/serverless-nextjs/serverless-next.js/commit/f774a30e1fa07d7f0d755106c68b50442d0c0d7f))

# [1.0.0-alpha.23](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.22...@sls-next/core@1.0.0-alpha.23) (2021-06-16)

### Bug Fixes

- **core:** use JS page path from manifest instead of manually constru… ([#1238](https://github.com/serverless-nextjs/serverless-next.js/issues/1238)) ([cac8918](https://github.com/serverless-nextjs/serverless-next.js/commit/cac89183546770363a56f0ad61ae6834ff5e4310))

# [1.0.0-alpha.22](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.21...@sls-next/core@1.0.0-alpha.22) (2021-06-09)

**Note:** Version bump only for package @sls-next/core

# [1.0.0-alpha.21](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.19...@sls-next/core@1.0.0-alpha.21) (2021-06-07)

### Bug Fixes

- **core, lambda-at-edge:** set error status codes in core, refactor error handling ([#1153](https://github.com/serverless-nextjs/serverless-next.js/issues/1153)) ([6d4ae93](https://github.com/serverless-nextjs/serverless-next.js/commit/6d4ae936d64d0dda1d4b077ddc402b6f1afae88b))

# [1.0.0-alpha.20](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.19...@sls-next/core@1.0.0-alpha.20) (2021-06-07)

### Bug Fixes

- **core, lambda-at-edge:** set error status codes in core, refactor error handling ([#1153](https://github.com/serverless-nextjs/serverless-next.js/issues/1153)) ([6d4ae93](https://github.com/serverless-nextjs/serverless-next.js/commit/6d4ae936d64d0dda1d4b077ddc402b6f1afae88b))

# [1.0.0-alpha.19](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.18...@sls-next/core@1.0.0-alpha.19) (2021-05-29)

### Bug Fixes

- **core, lambda-at-edge:** support static 500 page and localized stat… ([#1135](https://github.com/serverless-nextjs/serverless-next.js/issues/1135)) ([c0573c1](https://github.com/serverless-nextjs/serverless-next.js/commit/c0573c193e8a148277244ef93b4250f28b27f840))

# [1.0.0-alpha.18](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.17...@sls-next/core@1.0.0-alpha.18) (2021-05-27)

**Note:** Version bump only for package @sls-next/core

# [1.0.0-alpha.17](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.16...@sls-next/core@1.0.0-alpha.17) (2021-05-27)

### Bug Fixes

- **core, lambda-at-edge, e2e-tests:** fix locale rewrites to dynamic ssr ([#1132](https://github.com/serverless-nextjs/serverless-next.js/issues/1132)) ([91c1ddf](https://github.com/serverless-nextjs/serverless-next.js/commit/91c1ddf91dd97abe70079b2dd2a3be4861b70208))

# [1.0.0-alpha.16](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.15...@sls-next/core@1.0.0-alpha.16) (2021-05-25)

### Bug Fixes

- **core:** check for explicitly disabled locale detection ([#1129](https://github.com/serverless-nextjs/serverless-next.js/issues/1129)) ([0a39211](https://github.com/serverless-nextjs/serverless-next.js/commit/0a3921159513a927c5f8606e8550c12a5641396f))

# [1.0.0-alpha.15](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.14...@sls-next/core@1.0.0-alpha.15) (2021-05-25)

### Bug Fixes

- **core:** fix infinite redirects on NEXT_LOCALE cookie ([#1128](https://github.com/serverless-nextjs/serverless-next.js/issues/1128)) ([01d4d88](https://github.com/serverless-nextjs/serverless-next.js/commit/01d4d88afe2ca4e164ce12e5ac8ea2b75dbfe96c))

# [1.0.0-alpha.14](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.13...@sls-next/core@1.0.0-alpha.14) (2021-05-25)

### Bug Fixes

- **core, lambda-at-edge:** fix page inclusion logic in default-handler build ([#1126](https://github.com/serverless-nextjs/serverless-next.js/issues/1126)) ([5fdf3fe](https://github.com/serverless-nextjs/serverless-next.js/commit/5fdf3fe04146e60a01681b0bfe21c1147fea6fd4))

# [1.0.0-alpha.13](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.12...@sls-next/core@1.0.0-alpha.13) (2021-05-25)

**Note:** Version bump only for package @sls-next/core

# [1.0.0-alpha.12](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.11...@sls-next/core@1.0.0-alpha.12) (2021-05-24)

### Bug Fixes

- **core:** redirect based on NEXT_LOCALE cookie and add e2e test for … ([#1116](https://github.com/serverless-nextjs/serverless-next.js/issues/1116)) ([48773f4](https://github.com/serverless-nextjs/serverless-next.js/commit/48773f4fd1aa13896981b7ce3c9462d8429e6f86))

# [1.0.0-alpha.11](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.10...@sls-next/core@1.0.0-alpha.11) (2021-05-23)

### Bug Fixes

- **core:** fix accept language redirect condition ([#1110](https://github.com/serverless-nextjs/serverless-next.js/issues/1110)) ([f05ccbc](https://github.com/serverless-nextjs/serverless-next.js/commit/f05ccbcbb8e57c6281d542fea20ff9b4b5d5efa7))

# [1.0.0-alpha.10](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.9...@sls-next/core@1.0.0-alpha.10) (2021-05-21)

**Note:** Version bump only for package @sls-next/core

# [1.0.0-alpha.9](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.8...@sls-next/core@1.0.0-alpha.9) (2021-05-20)

### Bug Fixes

- **core:** add logging of path when pathToRegexStr fails ([#1082](https://github.com/serverless-nextjs/serverless-next.js/issues/1082)) ([31cc4b1](https://github.com/serverless-nextjs/serverless-next.js/commit/31cc4b15eace8797c2d4f8595122a03b077bd7d1))

# [1.0.0-alpha.8](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.7...@sls-next/core@1.0.0-alpha.8) (2021-05-20)

**Note:** Version bump only for package @sls-next/core

# [1.0.0-alpha.7](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.6...@sls-next/core@1.0.0-alpha.7) (2021-05-19)

### Features

- **lambda-at-edge:** incremental static regeneration ([#1028](https://github.com/serverless-nextjs/serverless-next.js/issues/1028)) ([d5bbdc6](https://github.com/serverless-nextjs/serverless-next.js/commit/d5bbdc6d395ae732ec0757744482bf8bc25e820f))

# [1.0.0-alpha.6](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.5...@sls-next/core@1.0.0-alpha.6) (2021-05-14)

**Note:** Version bump only for package @sls-next/core

# [1.0.0-alpha.5](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.4...@sls-next/core@1.0.0-alpha.5) (2021-05-14)

**Note:** Version bump only for package @sls-next/core

# [1.0.0-alpha.4](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.3...@sls-next/core@1.0.0-alpha.4) (2021-05-11)

**Note:** Version bump only for package @sls-next/core

# [1.0.0-alpha.3](https://github.com/serverless-nextjs/serverless-next.js/compare/@sls-next/core@1.0.0-alpha.2...@sls-next/core@1.0.0-alpha.3) (2021-05-09)

### Performance Improvements

- **core, lambda-at-edge:** cold start improvements ([#1044](https://github.com/serverless-nextjs/serverless-next.js/issues/1044)) ([0ee1394](https://github.com/serverless-nextjs/serverless-next.js/commit/0ee1394d83141332d594010d6e2550daac30d245))

# 1.0.0-alpha.2 (2021-05-05)

### Bug Fixes

- **core:** extend locale matching to secondary languages ([#1040](https://github.com/serverless-nextjs/serverless-next.js/issues/1040)) ([a2c476c](https://github.com/serverless-nextjs/serverless-next.js/commit/a2c476cb923b3a2a382541c7ff9327c0861bfd1c))
