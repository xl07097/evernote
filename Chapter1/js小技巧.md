# 第2节：js 小技巧

---

1. 求数组中的最小值
   ```JavaScript
   Math.min.apply(null, arr)
   Math.min(...arr) // 扩展运算符
   ```
2. 求数组中的最大值
   ```JavaScript
   Math.max.apply(null, arr)
   Math.max(...arr) // 扩展运算符
   ```
 > 注：`call` 与 `apply` 的作用是改变函数运行时的上下文环境，区别是传参方式不同

3. `for` 循环中使用 `setTimeout` 打印 `1,2,3......`
   * 使用 setTimeout 的第三个参数（IE10+）
   ```JavaScript
    for(var i = o; i < 10; i++){
        setTimeout(function(j){
            console.log(j);
        }, 1000, i)
    }
   ```
   * 使用自执行函数（IIFE）
   ```JavaScript
    for(var i = 0;i < 10; i++){
        (function(j){
            setTimeout(function(){
                console.log(j)
            }, 1000)
        })(i)
    }
   ```
   * 使用 `let` 定义局部变量，不会出现变量提升`（hoisting）`
    ```JavaScript
    for(let i = 0;i < 10; i++){
        setTimeout(function(){
            console.log(i)
        }, 1000)
    }
   ```
