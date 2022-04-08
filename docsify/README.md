# 准备目录
1. 参考模板文件（在目录"/docsify"），创建目录
1. 修改CNAME、index.html、README.md和_sidebar.md

# 部署(两种方法)
## 使用Github Pages部署
1. 准备的目录提交到github的main分支
1. [部署](https://docs.github.com/cn/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
1. 域名CNAME指向github页面，如andrewwang79.github.io
1. 勾选github页面的"Enforce HTTPS"

## 自行部署
1. 安装本地工具，依赖Node.js：npm i docsify-cli -g
1. 创建空项目：docsify init XYZ
1. 启动服务：cd XYZ && docsify serve

# 资料
* https://angry-swanson-b4e47b.netlify.app/zh-cn/quickstart
* https://segmentfault.com/a/1190000017576714
* https://github.com/docsifyjs/docsify/blob/develop/index.html
* https://www.wenjinyu.me/zh/docsify-make-a-notebook-application-of-your-own/
