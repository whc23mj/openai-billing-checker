# openai-billing-checker（[中文](./README_CN.md)）
OpenAI API Billing Checker (Muti-KEYs)

Using the apikey to query the balance of the OpenAI billing, which can query a key worth $120.

### Features
1、This is a pure open-source project that using JavaScript within HTML to request content. It will not collect any data.

2、Support multi-KEYs queries, automatically extract KEY and query in batches.

3、Supports reverse proxy queries, making your queries more secure.
![20230525093654](https://github.com/whc23mj/openai-billing-checker/assets/2191887/5613b762-98e2-421a-b696-946a98ae5e18)
![20230525093741](https://github.com/whc23mj/openai-billing-checker/assets/2191887/b43e512e-1104-4bed-896b-a8e54893056f)

### Reverse Proxy Setup
1、Register and login to Cloudflare.

2、Click Workers，Create a Service，select HTTP Router

3、After creating, click the quick edit button, copy the code from cloudflare.worker.js in the project, paste it into the editing area, save and deploy.

4、Get the link for reverse proxy, or use your own domain as reverse proxy.

### Thanks
1、https://github.com/ClarenceDan/openai-billing

2、https://github.com/herobrine19/openai-billing
