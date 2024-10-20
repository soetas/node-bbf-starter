# node-bbf-starter

> 洋葱模型和cluster模式

## 多进程

 
## CPU和内存

> 过载保护

```js
try {
  const cmd = `ps -p ${process.pid} -o pid,rss,vsz,pcpu,comm`
  const stdout = await promisify(exec)(cmd)
  console.log(stdout)
} catch(e) {
  console.log(e.message)

}

```

> Node.js中只能使用部分内存：64位操作系统下约为1.4G，32位操作系统下约为0.7G

## I/O

> 异步队列

## 缓存

> 缓存雪崩、缓存击穿和缓存穿透



## 安全


## 性能

> 日志记录、监控和告警




## 自动化
