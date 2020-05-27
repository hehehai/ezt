
## parcel
官网：https://parceljs.org/cli.html

开发：
- `parcel src/index.html --open`
--open 命令参数表示，当程序允许起来即在浏览器打开该程序的服务地址

- `parcel build src/index.html --no-content-hash --no-minify --no-source-maps --public-url ./`
--no-content-hash 禁用文件 hash 命名
--no-minify 禁用代码压缩
--no-source-maps 禁用源代码映射
--public-url 设置要提供服务的公共 URL（表示将在打包后的文件引用地址增加服务路径目录）
