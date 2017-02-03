
'cheap-module-eval-source-map' causing issues

Steps to repro:

```
npm i -g webpack-dev-server
npm i webpack
webpack-dev-server
```
goto http://localhost:8080
open dev console


What's causing it?

Something in `node_modules\this-causes-error\` is not playing well with `cheap-module-eval-source-map`
