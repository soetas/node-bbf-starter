# node-bbf-starter

> 洋葱模型和cluster模式

__微服务架构__


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

内存泄漏:

- 常发性
- 偶发性
- 一次性
- 隐性


## I/O

> 异步队列和本地缓存、共享内存


## 缓存

> 缓存雪崩、缓存击穿和缓存穿透


## 安全

### xss

### csrf

### sql

### dos


## 性能

> 日志记录、监控和告警





## 自动化
