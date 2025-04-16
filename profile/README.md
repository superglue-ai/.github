
<p align="center">
  <img src="https://github.com/user-attachments/assets/be0e65d4-dcd8-4133-9841-b08799e087e7" width="350" alt="superglue_logo_white">
</p>

<h2 align="center">self-healing integration agent 🍯</h2>

superglue is a self-healing integration agent. You can deploy it as a proxy between you and any complex / legacy APIs and always get the data that you want in the format you expect. Here's how it works: You prompt superglue in natural language (like "get all issues from jira"), provide an API URL, and superglue transforms the prompt into corresponding API calls. What superglue does under the hood:

- Automatically generates the API configuration by analyzing API docs.
- Handles pagination, authentication, and error retries.
- Creates deterministic transformations (using JSONata for creating transformation rules), into the exact schema you need.
- Validates that all data coming through follows that schema, and fixes transformations when they break.

superglue uses LLMs only during configuration setup and transformation rule creation, making the glueing process deterministic and extremely efficient in terms of latency and cost.

If you’re spending a lot of time writing code connecting to weird APIs, fumbling with custom fields in foreign language ERPs, mapping JSONs, extracting data from compressed CSVs sitting on FTP servers, and making sure your integrations don’t break when something unexpected comes through, superglue might be for you.

<div align="center">

[![GitHub](https://img.shields.io/github/license/superglue-ai/superglue?style=flat-square)](https://github.com/superglue-ai/superglue/blob/main/LICENSE)
[![Y Combinator](https://img.shields.io/badge/Y%20Combinator-W25-orange?style=flat-square)](https://www.ycombinator.com/companies/superglue)
[![Client SDK](https://img.shields.io/npm/v/@superglue/client?style=flat-square&logo=npm)](https://www.npmjs.com/package/@superglue/client)
[![Docker](https://img.shields.io/docker/pulls/superglueai/superglue?style=flat-square&logo=Docker)](https://hub.docker.com/r/superglueai/superglue)
[![Twitter Adina](https://img.shields.io/twitter/follow/adinagoerres?style=flat-square&logo=X)](https://twitter.com/adinagoerres)
[![Twitter Stefan](https://img.shields.io/twitter/follow/sfaistenauer?style=flat-square&logo=X)](https://twitter.com/sfaistenauer)


</div>

## 🤝 contributions

we love your contributions. feel free to chime in and build with us.

check our [open superglue issues](https://github.com/superglue-ai/superglue/issues) and [open superglue pull requests](https://github.com/superglue-ai/superglue/pulls) for more information.

## 💬 join the community

join our [discord](https://discord.gg/vUKnuhHtfW) to stay in the loop about latest releases.
