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
                                                                                
found 0 vulnerabilities
 in 15662 scanned packages

npm WARN ajv-keywords@2.1.1 requires a peer of ajv@^5.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN css-loader@2.1.1 requires a peer of webpack@^4.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN optimize-css-assets-webpack-plugin@5.0.1 requires a peer of webpack@^4.0.0 but none is installed. You must install peer dependencies yourself.

audited 15662 packages in 7.442s
found 0 vulnerabilities
```