# cljsjs/ag-grid - The JavaScript Datagrid for Enterprise

React Toolbox depends on React with Addons, so, to be able to use it, you not only have to depend in
cljsjs/ag-grid:

[](dependency)
```clojure
[cljsjs/ag-grid "8.2.0-0"] ;; latest release
```
[](/dependency)

This jar comes with `deps.cljs` as used by the [Foreign Libs][flibs] feature
of the ClojureScript compiler. After adding the above dependency to your project
you can require the packaged library like:

```clojure
(ns application.core
  (:require [cljsjs.ag-grid]))
```

[flibs]: https://github.com/clojure/clojurescript/wiki/Packaging-Foreign-Dependencies
