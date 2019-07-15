# New Tech Demo

# Agenda

- Node
- NPM
- React
- Redux

# Why Node？

# 优势

- 高并发
  - 事件驱动
- 生态圈
- 单线程控制
  - 内存管理清晰
  - 不需要多线程切换


## 事件流
![](https://images2015.cnblogs.com/blog/849589/201707/849589-20170709225535712-2041092305.png)

# 劣势

- Callback Hell
- 单线程
- 不擅长 CPU 密集型操作
    - 浮点数
    - 会导致 main thread 挂起
- 有可能抛出异常

## Callback Hell

```
  getData(function(a){  
      getMoreData(a, function(b){
          getMoreData(b, function(c){ 
              getMoreData(c, function(d){ 
                  getMoreData(d, function(e){ 
                      ...
                  });
              });
          });
      });
  });
```




# With Node?

Server
- NPM
- Router
- Express

Client
- Less/Sass
- React/Angular/Vue
  - Redux
- Jest/Mocha
- Webpack
