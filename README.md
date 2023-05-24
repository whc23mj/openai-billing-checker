# openai-billing-checker
OpenAI API Billing Checker(Batch)[简体中文](./README_CN.md)

Using the apikey to query the balance of the openai billing, which can query a key worth $120.

#### Explanation
1、This is a pure open-source project that uses JavaScript scripts within HTML to request content. It will not collect any data.

2、Support multiple KEY queries, automatically extract KEY and query in batches.

3、Supports reverse proxy queries, making your queries more secure.
![20230524093349](https://github.com/whc23mj/openai-billing-checker/assets/2191887/e1f81f09-0f77-4cbe-bfcf-d133321763ef)
![20230524093454](https://github.com/whc23mj/openai-billing-checker/assets/2191887/ce175ee1-491e-4f68-8cc7-a9ca6b5f500a)


### Reverse Proxy Setup
1、Register and login to Cloudflare.

2、Click Workers，Create a Service，select HTTP Router

3、After creating, click the quick edit button, copy the code from cloudflare.worker.js in the project, paste it into the editing area, save and deploy.

4、Get the link for reverse proxy, or use your own domain as reverse proxy.
