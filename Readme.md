<h2 align="center" style="border-bottom: none;"> 📬 Background Jobs 📭</h1>
<h4 align="center">Node.js + Redis</h4>

<p align="center">
    <img src="./docs/images/nodejs_logo.png" alt="React chat logo" width="90px"/>
    <img src="./docs/images/redis_logo.png" alt="React chat logo" width="90px"/>
</p>

An example setup with Express, bull, docker-compose and Redis.

🛎 It is like a API that you can call from your app to execute background jobs

#### How to use

```bash
$ git clone https://github.com/PeterPimentel/background-jobs-node
$ cd background-jobs-node/
$ npm install

$ docker-compose up //Redis
$ npm run dev //API
```