# openai-billing-checker（[中文](./README_CN.md)）
OpenAI API Billing Checker(Batch)

Using the apikey to query the balance of the OpenAI billing, which can query a key worth $120.

#### Features
1、This is a pure open-source project that using JavaScript within HTML to request content. It will not collect any data.

2、Support multi-KEYs queries, automatically extract KEY and query in batches.

3、Supports reverse proxy queries, making your queries more secure.
![20230524110229](https://github.com/whc23mj/openai-billing-checker/assets/2191887/9babf379-cfec-4366-8c78-f32a9018b01f)
![20230524110320](https://github.com/whc23mj/openai-billing-checker/assets/2191887/a55da03f-d905-4340-b3fd-113a1e31d1cd)



### Reverse Proxy Setup
1、Register and login to Cloudflare.

2、Click Workers，Create a Service，select HTTP Router

3、After creating, click the quick edit button, copy the code from cloudflare.worker.js in the project, paste it into the editing area, save and deploy.

4、Get the link for reverse proxy, or use your own domain as reverse proxy.
