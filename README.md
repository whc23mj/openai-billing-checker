# openai-billing-checker
OpenAI API Billing Checker(Batch)
Useing the apikey to query the balance of the openai billing, which can query a key worth $120.

#### Explanation
1、This is a pure open-source project that uses JavaScript scripts within HTML to request content. It will not collect any data.

2、Support multiple KEY queries, automatically extract KEY and query in batches.

3、Supports reverse proxy queries, making your queries more secure.
![20230509180207](https://github.com/whc23mj/openai-billing/assets/2191887/099de586-ff65-47f6-b8b4-86f420f726ab)
![20230509180751](https://github.com/whc23mj/openai-billing/assets/2191887/cb9570ed-c448-4c2d-bf3d-e89a724d3e6b)

### Reverse Proxy Setup
1、Register and login to Cloudflare.

2、Click Workers，Create a Service，select HTTP Router

3、After creating, click the quick edit button, copy the code from cloudflare.worker.js in the project, paste it into the editing area, save and deploy.

4、Get the link for reverse proxy, or use your own domain as reverse proxy.
