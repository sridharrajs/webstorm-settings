### Requires
`rq_` is the short form for `require`.

| Command| Description|
|-------|------------|
|`rq`   |`let <tab> = require(<tab>)`|
| `rq__`|`let _ = require('lodash')`|
|`rq_qs`  |`let qs = require('qs')` |
|`rq_fs`  |`let fs = require('fs')` |

### Functions

`fn` is the short form for `function`. So,


| Command| Description|
|-------|------------|
| `nfn`|Named function |
| `afn`|Anonymous function |
| `rfn`|Express request function |
| `sfn`|Static function |

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

|Command|Description|
|-------|-----------|
|`clog`|`console.log(<TAB>);`|
|`us;`|`'use strict';`|

### Testing

* `rq_desc` => for the describe template
* `let expect = require('expect')` => `rq_expect`