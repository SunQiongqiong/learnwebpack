
# npm i -D 是 npm install --save-dev 的简写，是指安装模块并保存到 package.json 的 devDependencies
# 安装最新稳定版
npm i -D webpack

# 安装指定版本
npm i -D webpack@<version>

# 安装最新体验版本
npm i -D webpack@beta




#目录结构
index,html----------页面入口文件
show.js-------------JS工具函数文件
main.js-------------JS执行入口文件
webpack.config.js---Webpack在执行构建时从此文件默认读取配置



只需在终端里运行webpack(非全局安装需使用node_modules/.bin/webpack)命令就可以了
