# Webstorm-settings

A repo for my [WebStorm](https://www.jetbrains.com/webstorm/) settings

### Requires
`rq_` is the short form for `require`.

* `let <tab> = require(<tab>)`=> `rq`   
* `let _ = require('lodash')` => `rq__`
* `let qs = require('qs')` => `rq_qs`  
* `let fs = require('fs')` => `rq_fs`  
* `let mongoose = require('mongoose')` => `rq_mon`  

### Functions

`fn` is the short form for `function`. So,

* Named function => `nfn`
* Anonymous function => `afn`
* Request function => `rfn`
* Static function => `sfn`

`nfn ` gives

    function <Tab> (<Tab>) {
      <Tab>
    }

### Lodash

> Lodash is a modern JavaScript utility library delivering modularity, performance & extras.

`_` is the short form. So,

* `_.each()`   => `_e`  
* `_.map()`    => `_m`  
* `_.reduce()` => `_r`  

### Express

>  Express is Fast, unopinionated, minimalist web framework for Node.js

`e` stands for `express`

* `e_route` => express router boilerplate

### Trivials

* `console.log(<TAB>);` => `clog`
* `"use strict";` => `us;`

### Testing

* `rq_desc` => for the describe template
* `let expect = require('expect')` => `rq_expect`

### LICENSE

MIT
