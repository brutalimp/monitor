<h1 align="center">前端性能监控与错误捕捉</h1>

## 描述
- 本脚本是基于window.performence而实现的性能监控方法，可记录dom树渲染耗时（domcontentloaded）,页面加载耗时（onload), 页面请求总时长等。
- 记录基于navigator的操作系统，浏览器等信息。
- 资源加载错误，js执行错误，基于unhandledrejection事件的Promise异常错误。
- 其他有用的信息可自己酌情添加。

## 使用方法
- 添加monitor.js文件到项目中
- 在app初始文件中引入该文件

## 注意事项
- 需要修改保存日志中的后端路径地址
- 如果需要记录页面白屏时间，则需要放开【whiteScreen】部分代码

## LICENCE
MIT

