# 第 2 节：js 小技巧

---

1. 求数组中的最小值
   ```
   Math.min.apply(null, arr)
   ```
2. 求数组中的最大值
   ```
   Math.max.apply(null, arr)
   ```
 注：call 与 apply 的作用是改变函数运行时的上下文环境，区别是传参方式不同
