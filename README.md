# ecmascript-stack
A Well Currated Stack of ECMAScript dependencies used as mono repo and is shared in my development projects.


## Install
```
npm i -g @frank-dspeed/ecmascript-stack
```



## Usage?

mkdir project
cd project
npm init
npm link @frank-dspeed/ecmascript-stack
create dev-bundle.js


```js
import * from '@frank-dspeed/ecmascript-stack/@rollup/rollup' 


```


rollup -c dev-bundle.config.js


in development 
import { ... } from 'dev-bundle.dist.js

when you add new dependencies simply add them to your dev-bundle before you start using them in code.


## Included Stuff

@rollup/*
@webpack/*
@systemjs/*
@stealjs/*
@canjs/can/*
@mostjs/*
@most/*
@rxjs/*
@vue/*
@react/*
