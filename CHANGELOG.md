<a name="0.1.0"></a>
# 0.1.0 (2015-09-17)


### Bug Fixes

* add missing 'use strict's ([397294e](https://github.com/algolia/intantsearch.js/commit/397294e))
* add title for brands ([2e67c47](https://github.com/algolia/intantsearch.js/commit/2e67c47))
* allow adding css classes to the searchBox wrapper ([6ef0b0b](https://github.com/algolia/intantsearch.js/commit/6ef0b0b)), closes [#22](https://github.com/algolia/intantsearch.js/issues/22) [#24](https://github.com/algolia/intantsearch.js/issues/24)
* allow html in pagination labels ([4147358](https://github.com/algolia/intantsearch.js/commit/4147358)), closes [#36](https://github.com/algolia/intantsearch.js/issues/36)
* cap the number of page displayed ([bc6c2e2](https://github.com/algolia/intantsearch.js/commit/bc6c2e2))
* change no results message ([80acf33](https://github.com/algolia/intantsearch.js/commit/80acf33))
* do not use memoize & co ([32c64e6](https://github.com/algolia/intantsearch.js/commit/32c64e6))
* expose main dist/ instead of index.js ([98bd889](https://github.com/algolia/intantsearch.js/commit/98bd889))
* Fix merge issues ([3b5e8f4](https://github.com/algolia/intantsearch.js/commit/3b5e8f4))
* fixed hits display height, no more scroll jumps ([6b4319d](https://github.com/algolia/intantsearch.js/commit/6b4319d))
* folder requires uses a trailing / to ease recognition of /index.js ([3ef55a3](https://github.com/algolia/intantsearch.js/commit/3ef55a3))
* Handle plural forms in template ([1bfd109](https://github.com/algolia/intantsearch.js/commit/1bfd109))
* Handle zero, one and many ([5434ca2](https://github.com/algolia/intantsearch.js/commit/5434ca2))
* hits widget should allow hitsPerPage configuration, pagination should not ([a2221a8](https://github.com/algolia/intantsearch.js/commit/a2221a8))
* instantSearch => instantsearch ([bdcbf18](https://github.com/algolia/intantsearch.js/commit/bdcbf18)), closes [#7](https://github.com/algolia/intantsearch.js/issues/7)
* Keep `en-EN` as demo default ([6c2a043](https://github.com/algolia/intantsearch.js/commit/6c2a043))
* no more needed to override css class here ([2b314c0](https://github.com/algolia/intantsearch.js/commit/2b314c0))
* no need for a flag in refinementList refine() ([9b8fa3f](https://github.com/algolia/intantsearch.js/commit/9b8fa3f))
* no state needed for Hogan component ([d8a3a4c](https://github.com/algolia/intantsearch.js/commit/d8a3a4c))
* react-nouislider will live in our repo for now ([49520f1](https://github.com/algolia/intantsearch.js/commit/49520f1))
* reduce the dependency between REACT components and helper ([9309a4c](https://github.com/algolia/intantsearch.js/commit/9309a4c))
* Remove `htmlAttribute` in favor of `cssClass` ([59a0bc5](https://github.com/algolia/intantsearch.js/commit/59a0bc5))
* remove data-role from searchBox ([bdfe6d3](https://github.com/algolia/intantsearch.js/commit/bdfe6d3))
* remove linebreak ([e5f1720](https://github.com/algolia/intantsearch.js/commit/e5f1720))
* **core:** recursively merge arrays in searchParameters ([dbadcdb](https://github.com/algolia/intantsearch.js/commit/dbadcdb)), closes [#80](https://github.com/algolia/intantsearch.js/issues/80)
* rename BEM root algolia-magic to as ([5f3329d](https://github.com/algolia/intantsearch.js/commit/5f3329d)), closes [#24](https://github.com/algolia/intantsearch.js/issues/24)
* rename results component to hits ([7b9eb25](https://github.com/algolia/intantsearch.js/commit/7b9eb25))
* Set `cssClass` as optional in documentation ([e7ac953](https://github.com/algolia/intantsearch.js/commit/e7ac953))
* set visibility:hidden by default for uneeded pagination links ([19fddba](https://github.com/algolia/intantsearch.js/commit/19fddba)), closes [#37](https://github.com/algolia/intantsearch.js/issues/37)
* strict container check ([ec23e34](https://github.com/algolia/intantsearch.js/commit/ec23e34))
* switch back to divs, rendering glitch ([b44943a](https://github.com/algolia/intantsearch.js/commit/b44943a))
* toggleRefine was no more working ([e6e35df](https://github.com/algolia/intantsearch.js/commit/e6e35df))
* update algoliasearch and algoliasearch-helper ([e944d12](https://github.com/algolia/intantsearch.js/commit/e944d12))
* **multipleChoiceList:** `limit` should be pure JS ([68bdf81](https://github.com/algolia/intantsearch.js/commit/68bdf81))
* upgrade all libs, switch to ^ dependencies ([79d0a64](https://github.com/algolia/intantsearch.js/commit/79d0a64))
* **template:** throw when no way to deal with the template type ([f5d151a](https://github.com/algolia/intantsearch.js/commit/f5d151a))
* Use `appId` and `apiKey` keys ([5716552](https://github.com/algolia/intantsearch.js/commit/5716552))
* use cssClass instead of inputClass or addClass ([6826bd6](https://github.com/algolia/intantsearch.js/commit/6826bd6))
* use toggleRefinement ([b497b02](https://github.com/algolia/intantsearch.js/commit/b497b02))
* widgets.searchbox => widgets.searchBox ([6c49e18](https://github.com/algolia/intantsearch.js/commit/6c49e18))
* wrap in an li the checkbox ([dfe629d](https://github.com/algolia/intantsearch.js/commit/dfe629d))

### Features

* Add `htmlAttributes` to indexSelector ([ceed8ae](https://github.com/algolia/intantsearch.js/commit/ceed8ae))
* Add stats widget ([8290542](https://github.com/algolia/intantsearch.js/commit/8290542))
* Add support for `className` ([898a2fa](https://github.com/algolia/intantsearch.js/commit/898a2fa))
* Add Toggle example ([d801807](https://github.com/algolia/intantsearch.js/commit/d801807))
* Check that currentIndex is in indices list ([494dbe9](https://github.com/algolia/intantsearch.js/commit/494dbe9))
* example now uses the instant_search index ([63b4b50](https://github.com/algolia/intantsearch.js/commit/63b4b50))
* expose instantsearch.version ([ae5ef94](https://github.com/algolia/intantsearch.js/commit/ae5ef94))
* **menu:** first widget version ([a888143](https://github.com/algolia/intantsearch.js/commit/a888143))
* expose instantsearch() as main init method ([27baf55](https://github.com/algolia/intantsearch.js/commit/27baf55)), closes [#6](https://github.com/algolia/intantsearch.js/issues/6)
* formatNumber in Stats widget ([cf6a83c](https://github.com/algolia/intantsearch.js/commit/cf6a83c))
* indexSelector widget ([b60ed36](https://github.com/algolia/intantsearch.js/commit/b60ed36))
* multipleChoiceList => refinementList ([423542d](https://github.com/algolia/intantsearch.js/commit/423542d)), closes [#64](https://github.com/algolia/intantsearch.js/issues/64)
* multipleChoiceList first iteration ([bc91bfb](https://github.com/algolia/intantsearch.js/commit/bc91bfb))
* MutlipleChoiceList second pass ([ac74dfb](https://github.com/algolia/intantsearch.js/commit/ac74dfb))
* pagination component ([fad2720](https://github.com/algolia/intantsearch.js/commit/fad2720))
* pimp the npm run dev example using instant search data ([ea666ad](https://github.com/algolia/intantsearch.js/commit/ea666ad)), closes [#20](https://github.com/algolia/intantsearch.js/issues/20)
* **pagination:** add hitsPerPage and maxPages options ([7e558ce](https://github.com/algolia/intantsearch.js/commit/7e558ce))
* **slider:** allow overriding css classes from a user stylesheet ([a1e87dd](https://github.com/algolia/intantsearch.js/commit/a1e87dd))
* **slider:** first iteration ([229bb02](https://github.com/algolia/intantsearch.js/commit/229bb02))
* Switch/Toggle widget ([3b2a450](https://github.com/algolia/intantsearch.js/commit/3b2a450))
* Use `helpers.formatNumber` syntax instead of `_formatNumber` ([6207514](https://github.com/algolia/intantsearch.js/commit/6207514))
* Warn users if we do not override `helpers` in templates ([a4199a5](https://github.com/algolia/intantsearch.js/commit/a4199a5))
* **slider:** second iteration ([885aff6](https://github.com/algolia/intantsearch.js/commit/885aff6))



<a name="0.0.0"></a>
## [0.0.0](https://github.com/algolia/intantsearch.js/compare/v0.0.0...v0.0.0) (2015-09-17)

First commit