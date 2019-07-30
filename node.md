//=>建立本地仓库和远程仓库的链接
查看本地仓库和那些远程仓管库有链接
$ git remote - v 
让本地仓库和远程新建一个链接
$

$git clone[远程仓库git地址][别名可以不设置，默认是仓库名]
<!-- 
真是项目中开发流程
1.组长或者负责人先创建中央仓库、
2.小组成员基于$ git clone 把远程仓库及默认的内容克隆到本地（解决了三个事情：初始化一个本地仓库）
3.每个组员完成自己的代码之后，基于'git add /git commit"
 -->
###NPM###
node package manage:node 模块管理工具，根据NPM我们可快安装，卸载所需要的资源文件（例如;jQuery vue vue-router）
去NODAE官网 :http://nodejs.org/zh-cn/下载NODE
$node -v
$npm -v出现版本信息成功
####基于NPM进行模块管理
https://www.npmjs.com/
$ npm install xxxx把模块安装到当前项目中（node_modules）
$ npm install xxx -g 把模块安装到全局变量中
$ npm i  xxx@1.0.0 安装到指定版本号的模块
$ npm view xxx version >xxx.version.json
$ npm init -y
$ npm i xxx --save
$ npm i xxx --save-dev
$ npm intall


$ npm root -g 查看全局安装模块目录
$ npm uninstall xxx
$ npm uninstall xxx -g 卸载安装过的模块