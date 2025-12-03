## 基于0.6.41的OPENWEBUI的修改版

修改了DOCKERFILE，支持从CDN资源加载CSS/JS注入以修改
1. 背景图片: url: http://cache.wasai.chat/bgpic.jpg
2. 更改了三个字体：url: http://cache.wasai.chat/*.woff2
3. 更改了代码窗的互动方式，参考源：https://linux.do/t/topic/440439

## 使用方式：
1. git clone本项目
2. cd 项目目录
3. docker build -t image_name .
4. docker 启动该镜像
