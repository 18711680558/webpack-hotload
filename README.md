Webpack Hot Middleware
-----------------------
Webpack热加载模板

## 1. 原因
> 现有的模板都不满足要求，不是缺少模块，就是限制太多，修改起来非常麻烦，于是自己重启了一个项目，实验了多次，才得到了这么一个可灵活配置webpack模板。

## 2. 特性
1. 支持第三方的库的AMD加载；
2. 支持多入口webpack编译；
3. 支持Vue等端对端的解决方案；
4. 支持yaml配置文件；

## 3. 运行方式
```bash
#   启动调试模式
npm run dev
#   启动生产模式
#   支持github网站发布
npm run build
```