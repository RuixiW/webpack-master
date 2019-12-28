# webpack 安装
  npm init 初始化，生成package.json文件
  npm install --save-dev webpack webpack-cli
# webpack可以进行0配置
  -打包工具 -> 输出后的结构（js模块）
  -打包 ->支持js的模块化
  在node_modules下bin的wenbpack.cmd里判断使用
 # 手动配置webpack
 webpack.config.js
 
 
 npx webpack --config xxx 或
 更改配置文件名字：package.json ->script ->build(任意名字都可)：webpack --config wenpack.config.js -> npm run build
 
 开发环境：npm install webpack-dev-server --save-dev
 webpack.config.js里配置devServer
 package里配置


npm install html-webpack-plugin --save-dev
  
