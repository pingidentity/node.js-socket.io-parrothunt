# Elastic Beam Sample App (Parrot Hunt)

Elastic Beam is a Silicon Valley startup - still in stealth mode so our web site is not yet visible. Our mission is to build *“Layer 7 Networking & Security”* in Software. We are focused on Cloud-first, API-first deployments with products built on Linux 3.x.

>API Proxy, an Elastic Beam software product, helps in scaling and securing both REST and WebSocket API’s. It will load balance all connections directly at the API level and supports session stickiness and TLS/SSL.

### Objective of this Repo
* Contains the software code for building and deploying a Node.js HTML5 app. Core technologies used in this app are socket.io and WebGL
* Explains how to loadbalance socket.io apps running in Node.js using our software: API Proxy
* Demonstrates how to scale socket.io app with cookie based stickiness using TLS 1.2


### DevOps Setup

Make sure that [Node.js](https://nodejs.org/) is installed on your system.

1. Clone this repo
    - **$ git clone https://github.com/elasticbeam/node.js-socket.io-parrothunt.git**
2. Start the Parrot Hunt App
    - cd parrothunt/server and run
	- node server.js
3. Verify Install of Parrot Hunt App
    - **http://<host>:8080**
    - Note: Parrot Hunt app uses WebGL technology. Please make sure that your [browser supports](https://get.webgl.org/)  WebGL.
4. API Proxy for Load Balancing Parrot Hunt App
    - API Proxy helps to load balance socket.io requests from browsers to multiple Parrot Hunt apps running on Node.js servers. If you want to run multiple Parrot Hunt applications on a single machine, then make sure that the Node.js servers run on different ports. Please see below for deployment model:
    
    - ![alt text](https://s3-us-west-2.amazonaws.com/elasticbeam-public/apps/nodejs/websocket_webgl/parrothunt/parrothunt_scaling.png "Api-Proxy socket.io cookie based sticky loadblancing")

### How to get API Proxy from Elastic Beam?
Please send an email to **support@elasticbeam.com** We will get back to you in less than 24 hours for access to our software product!

Thank you!