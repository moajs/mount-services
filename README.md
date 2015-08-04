# mount-services

 service层位于 `app/services`，主要完成多模型共同操作，完成某一个业务，一般只有业务比较复杂的适合才会这样使用。
 
 service层概念最早出现java spring框架中。

## Install

    npm install --save mount-services

## Usages

```
var $services = require('mount-services')(__dirname);
console.log($services);

var users_service = require('mount-services')(__dirname).users_service;
```