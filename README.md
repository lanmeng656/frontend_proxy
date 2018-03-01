# frontend_proxy
前端开发用到的本地代理程序，避免AJAX因跨域无法请求

###  使用方法
1.修改config.js文件

    apiPath:'/api/', // api的目录
    method:'POST',// 代理请求的方法
    remoteHost:'www.chenbinfa.com' // 代理目标域名

2.前端用到的静态文件放在 public文件夹中
3.运行 npm install
4.运行 node index.js 