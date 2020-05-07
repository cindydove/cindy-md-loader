## 将md文档转为js模块的loader
### 下载
`` npm install @cindydove/md-loader -D``

## 使用
``
 {
 test: /\.md/,
 use: '@cindydove/md-loader',
 exclude: /node_modules/
}
``