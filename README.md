# 写代码 老是忘 弄个工具箱 方便随时复制

### js类


##### 1.生成 16 32位ID

``` js
Math.random().toString(32).substring(2,)
// 'jm3h7337hq'
```
##### 2 js的 switch 写法
```
var action = {
  'key':'val',
  'key':function(){}
}
// 调用 
action[str] || action['defult']
action[str]() // function
```
##### 2. export import {}

```
// 变量
export var m = 1;
export {m};
export {n as m};
// 函数
export function func_A() {};
export function func_B() {};

function f() {}
export {f};
// 匿名函数
export default function fun_C () {}

// import 使用
import {func_A, func_B} from './utils.js';
import * as func from './utils.js';
// import 匿名
import fun_C from './utils.js';
```



















### php类
