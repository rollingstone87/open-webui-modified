## 基于0.6.41的OPENWEBUI的修改版

修改了DOCKERFILE，支持从CDN资源加载CSS/JS注入以修改
1. 背景图片: url: http://cache.wasai.chat/bgpic.jpg
2. 更改了三个字体：url: http://cache.wasai.chat/*.woff2
3. 更改了代码窗的互动方式，参考源：https://linux.do/t/topic/440439

## 使用方式：
1. git clone https://github.com/rollingstone87/open-webui-modified.git
2. cd open-webui-modified
3. docker build -t open-webui-modified .
4. docker run -d -p 5556:8080 -v open-webui:/app/backend/data --name open-webui-modified open-webui-modified
