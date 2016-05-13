# angular.mdPickers
材料设计的日期/时间 角材料


## 在线演示

* [CodePen](http://codepen.io/alenaksu/full/eNzbrZ)


## 要求

* [moment.js](http://momentjs.com/)
* [AngularJS](https://angularjs.org/)
* [Angular Material](https://material.angularjs.org/)

## 使用

安装通过 Bower:

```bash
bower install mdPickers
```

使用 Angular:
```javascript
angular.module( 'YourApp', [ 'mdPickers' ] )
  .controller("YourController", YourController );
```

## Building mdPickers

第一次安装或更新你的本地项目的__npm__工具:

```bash
# First install all the npm tools:
npm install

# or update
npm update
```

然后运行默认的 gulp 任务 :

```bash
# builds all files in the `dist` directory
gulp
```
