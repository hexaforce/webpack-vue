# webpack-vue

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

```
warning autoprefixer > browserslist@2.11.3: Browserslist 2 could fail on reading Browserslist >3.0 config used in other tools.
warning css-loader > cssnano > autoprefixer > browserslist@1.7.7: Browserslist 2 could fail on reading Browserslist >3.0 config used in other tools.
warning css-loader > cssnano > postcss-merge-rules > browserslist@1.7.7: Browserslist 2 could fail on reading Browserslist >3.0 config used in other tools.
warning css-loader > cssnano > postcss-merge-rules > caniuse-api > browserslist@1.7.7: Browserslist 2 could fail on reading Browserslist >3.0 config used in other tools.
warning css-loader > cssnano > postcss-merge-rules > postcss-selector-parser > flatten@1.0.2: I wrote this module a very long time ago; you should use something else.
warning eslint > file-entry-cache > flat-cache > circular-json@0.3.3: CircularJSON is in maintenance only, flatted is its successor.
warning extract-text-webpack-plugin@3.0.2: Deprecated. Please use https://github.com/webpack-contrib/mini-css-extract-plugin
warning karma > socket.io > socket.io-parser > json3@3.3.2: Please use the native JSON object instead of JSON 3
warning karma-coverage > istanbul@0.4.5: This module is no longer maintained, try this instead:
  npm i nyc
Visit https://istanbul.js.org/integrations for other alternatives.
warning mocha > json3@3.3.2: Please use the native JSON object instead of JSON 3
warning nightwatch > mocha-nightwatch > json3@3.3.2: Please use the native JSON object instead of JSON 3
warning nightwatch > proxy-agent > socks-proxy-agent > socks@1.1.10: If using 2.x branch, please upgrade to at least 2.1.6 to avoid a serious bug with socket data flow and an import issue introduced in 2.1.0
warning sinon > @sinonjs/formatio > samsam@1.3.0: This package has been deprecated in favour of @sinonjs/samsam
warning webpack-bundle-analyzer > bfj-node4@5.3.1: Switch to the `bfj` package for fixes and new features!
```
```
warning autoprefixer> browserslist@2.11.3：Browserslist 2が他のツールで使用されているBrowserslist> 3.0の設定の読み取りに失敗することがありました。
warning css-loader> cssnano> autoprefixer> browserslist@1.7.7：Browserslist 2は、他のツールで使用されているBrowserslist> 3.0設定の読み取りに失敗することがありました。
warning css-loader> cssnano> postcss-merge-rules> browserslist@1.7.7：Browserslist 2は、他のツールで使用されているBrowserslist> 3.0設定の読み取りに失敗することがありました。
warning css-loader> cssnano> postcss-merge-rules> caniuse-api> browserslist@1.7.7：Browserslist 2は、他のツールで使用されているBrowserslist> 3.0設定の読み取りに失敗することがありました。
warning css-loader> cssnano> postcss-merge-rules> postcss-selector-parser> flatten@1.0.2：このモジュールはかなり前に書いたものです。他のものを使うべきです。
警告eslint> file-entry-cache>フラットキャッシュ> circular-json@0.3.3：CircularJSONはメンテナンス中のみで、flattedはその後継です。
warning extract-text-webpack-plugin@3.0.2：非推奨です。 https://github.com/webpack-contrib/mini-css-extract-pluginを使用してください
warning karma> socket.io> socket.io-parser> json3@3.3.2：JSON 3の代わりにネイティブのJSONオブジェクトを使用してください
warning karma-coverage> istanbul@0.4.5：このモジュールはもうメンテナンスされていません。代わりにこれを試してください：
  npm私nyc
他の選択肢についてはhttps://istanbul.js.org/integrationsをご覧ください。
warning mocha> json3@3.3.2：JSON 3の代わりにネイティブのJSONオブジェクトを使ってください
warning nightwatch> mocha-nightwatch> json3@3.3.2：JSON 3の代わりにネイティブのJSONオブジェクトを使ってください
warning nightwatch> proxy-agent> socks-proxy-agent> socks@1.1.10：2.xブランチを使用している場合、ソケットデータフローに関する深刻なバグおよび2.1で発生したインポートの問題を回避するために少なくとも2.1.6にアップグレードしてください.0
warning sinon> @ sinonjs / formatio> samsam@1.3.0：このパッケージは@ sinonjs / samsamを支持して推奨されていません。
警告webpack-bundle-analyzer> bfj-node4@5.3.1：修正と新機能を得るために `bfj`パッケージに切り替えてください！
```
```
Running eslint --fix to comply with chosen preset rules...
```

```
                                                                                
                       === npm audit security report ===                        
                                                                                
# Run  npm install --save-dev karma@4.1.0  to resolve 15 vulnerabilities
SEMVER WARNING: Recommended action is a potentially breaking change
┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Moderate      │ Prototype Pollution                                          │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ lodash                                                       │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ karma [dev]                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ karma > lodash                                               │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/782                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Low           │ Prototype Pollution                                          │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ lodash                                                       │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ karma [dev]                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ karma > lodash                                               │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/577                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Low           │ Regular Expression Denial of Service                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ debug                                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ karma [dev]                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ karma > socket.io > debug                                    │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/534                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Low           │ Regular Expression Denial of Service                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ debug                                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ karma [dev]                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ karma > socket.io > engine.io > debug                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/534                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Low           │ Regular Expression Denial of Service                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ debug                                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ karma [dev]                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ karma > socket.io > socket.io-adapter > debug                │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/534                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Low           │ Regular Expression Denial of Service                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ debug                                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ karma [dev]                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ karma > socket.io > socket.io-client > debug                 │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/534                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Low           │ Regular Expression Denial of Service                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ debug                                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ karma [dev]                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ karma > socket.io > socket.io-client > engine.io-client >    │
│               │ debug                                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/534                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Low           │ Regular Expression Denial of Service                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ debug                                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ karma [dev]                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ karma > socket.io > socket.io-adapter > socket.io-parser >   │
│               │ debug                                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/534                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Low           │ Regular Expression Denial of Service                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ debug                                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ karma [dev]                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ karma > socket.io > socket.io-client > socket.io-parser >    │
│               │ debug                                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/534                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Low           │ Regular Expression Denial of Service                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ debug                                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ karma [dev]                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ karma > socket.io > socket.io-parser > debug                 │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/534                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Low           │ Regular Expression Denial of Service                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ braces                                                       │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ karma [dev]                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ karma > chokidar > anymatch > micromatch > braces            │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/786                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Low           │ Regular Expression Denial of Service                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ braces                                                       │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ karma [dev]                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ karma > expand-braces > braces                               │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/786                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ High          │ Denial of Service                                            │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ ws                                                           │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ karma [dev]                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ karma > socket.io > engine.io > ws                           │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/550                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ High          │ Denial of Service                                            │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ ws                                                           │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ karma [dev]                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ karma > socket.io > socket.io-client > engine.io-client > ws │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/550                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ High          │ Regular Expression Denial of Service                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ parsejson                                                    │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ karma [dev]                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ karma > socket.io > socket.io-client > engine.io-client >    │
│               │ parsejson                                                    │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/528                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


# Run  npm install --save-dev nightwatch@1.1.11  to resolve 6 vulnerabilities
SEMVER WARNING: Recommended action is a potentially breaking change
┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Low           │ Regular Expression Denial of Service                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ debug                                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ nightwatch [dev]                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ nightwatch > mocha-nightwatch > debug                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/534                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Critical      │ Command Injection                                            │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ growl                                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ nightwatch [dev]                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ nightwatch > mocha-nightwatch > growl                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/146                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ High          │ Denial of Service                                            │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ http-proxy-agent                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ nightwatch [dev]                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ nightwatch > proxy-agent > http-proxy-agent                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/607                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ High          │ Denial of Service                                            │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ http-proxy-agent                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ nightwatch [dev]                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ nightwatch > proxy-agent > pac-proxy-agent >                 │
│               │ http-proxy-agent                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/607                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ High          │ Denial of Service                                            │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ https-proxy-agent                                            │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ nightwatch [dev]                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ nightwatch > proxy-agent > https-proxy-agent                 │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/593                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ High          │ Denial of Service                                            │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ https-proxy-agent                                            │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ nightwatch [dev]                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ nightwatch > proxy-agent > pac-proxy-agent >                 │
│               │ https-proxy-agent                                            │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/593                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


# Run  npm install --save-dev mocha@6.1.4  to resolve 2 vulnerabilities
SEMVER WARNING: Recommended action is a potentially breaking change
┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Low           │ Regular Expression Denial of Service                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ debug                                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ mocha [dev]                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ mocha > debug                                                │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/534                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Critical      │ Command Injection                                            │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ growl                                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ mocha [dev]                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ mocha > growl                                                │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/146                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


# Run  npm install --save-dev css-loader@2.1.1  to resolve 2 vulnerabilities
SEMVER WARNING: Recommended action is a potentially breaking change
┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Moderate      │ Denial of Service                                            │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ js-yaml                                                      │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ css-loader [dev]                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ css-loader > cssnano > postcss-svgo > svgo > js-yaml         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/788                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ High          │ Code Injection                                               │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ js-yaml                                                      │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ css-loader [dev]                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ css-loader > cssnano > postcss-svgo > svgo > js-yaml         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/813                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


# Run  npm install --save-dev optimize-css-assets-webpack-plugin@5.0.1  to resolve 2 vulnerabilities
SEMVER WARNING: Recommended action is a potentially breaking change
┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Moderate      │ Denial of Service                                            │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ js-yaml                                                      │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ optimize-css-assets-webpack-plugin [dev]                     │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ optimize-css-assets-webpack-plugin > cssnano > postcss-svgo  │
│               │ > svgo > js-yaml                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/788                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ High          │ Code Injection                                               │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ js-yaml                                                      │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ optimize-css-assets-webpack-plugin [dev]                     │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ optimize-css-assets-webpack-plugin > cssnano > postcss-svgo  │
│               │ > svgo > js-yaml                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/813                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


# Run  npm install --save-dev url-loader@1.1.2  to resolve 1 vulnerability
SEMVER WARNING: Recommended action is a potentially breaking change
┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Moderate      │ Regular Expression Denial of Service                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ mime                                                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ url-loader [dev]                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ url-loader > mime                                            │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/535                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


# Run  npm install --save-dev webpack-bundle-analyzer@3.3.2  to resolve 1 vulnerability
SEMVER WARNING: Recommended action is a potentially breaking change
┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Moderate      │ Cross-Site Scripting                                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ webpack-bundle-analyzer                                      │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ webpack-bundle-analyzer [dev]                                │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ webpack-bundle-analyzer                                      │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/826                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


# Run  npm install --save-dev babel-plugin-istanbul@5.1.4  to resolve 1 vulnerability
SEMVER WARNING: Recommended action is a potentially breaking change
┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Low           │ Regular Expression Denial of Service                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ braces                                                       │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ babel-plugin-istanbul [dev]                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ babel-plugin-istanbul > test-exclude > micromatch > braces   │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/786                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


found 30 vulnerabilities (14 low, 5 moderate, 9 high, 2 critical) in 14689 scanned packages
  30 vulnerabilities require semver-major dependency updates.
```