# openai-billing-checker
OpenAI API余额查询(批量)
使用 apikey 查询 openai apikey 余额，可查询 120$ 的key

#### 说明
1、纯开源项目，使用 html 内的js 脚本请求内容，不会收集任何数据

2、支持多个 KEY 查询，自动提取 KEY 并批量查询

3、支持反向代理查询，让你的查询更安心
![20230509180207](https://github.com/whc23mj/openai-billing/assets/2191887/099de586-ff65-47f6-b8b4-86f420f726ab)
![20230509180751](https://github.com/whc23mj/openai-billing/assets/2191887/cb9570ed-c448-4c2d-bf3d-e89a724d3e6b)

### 反向代理搭建
1、注册并登录 Cloudflare

2、点击 Workers，Create a Service，选择HTTP Router

3、创建后点击快速编辑按钮，将项目中 cloudflare.worker.js 中的代码复制下来，粘贴到编辑区域，保存并部署即可。

4、获取反向代理的链接，或者使用自己的 domain 作为反向代理
