# KintoHub Express Example

## Overview

Express is one of the widely used web frameworks in Node.js. It can be built easily for microservice on KintoHub!

[Live Example](https://8caf94bb-c2e5-45cf-898d-ca5b19954cda.api.master.kintohub.com/express-example/hello/wolrd)

__About KintoHub:__

KintoHub aligns teams to ship & operate cloud native apps with ease. [Learn More](https://www.kintohub.com)

## Deployment
1. Apply this template to your [Github](https://github.com/kintohub/express-example/generate)
2. Create a [Microservice Block](https://docs.kintohub.com/docs/kintoblocks/microservices) on KintoHub
3. Connect your GithubApp to KintoHub and select the Repository you just generated on your account.
4. Set the **name** of your kinto block
5. Choose `Node.js` as the **language** and `11.7.0` as the **version**
6. Set the **Build Command** as `npm install`
7. Set the **Start Command** as `npm start`
8. Set the **Port** as `80`

You're now good to go! Click **Create Microservice**. Now click **Build Latest Commit**

... The build takes about 40 seconds. Once complete, Click *Add to Project*

Follow the instruction to creating a new project. Once created, you can then click *Open* on your Ionic block and see it running live!

## Installation & Local Run
Ensure you have node 10 or higher.

1. `npm install`
2. `npm start`

## Usage
#### Optional Environment Variables
Default value  = `Hello`
```
GREETING=Hi
```

#### Endpoint
[Live Example](https://8caf94bb-c2e5-45cf-898d-ca5b19954cda.api.master.kintohub.com/express-example/hello/wolrd)
```
GET http://localhost/hello/world
```

#### Response
```json
{
  "message": "Hello world"
}
``` 

## What's Next?

You can do a lot with KintoHub and your deployed application. Some helpful links for next steps that you may consider with this project.

* [Creating multiple environments](https://docs.kintohub.com/docs/projects/environments)
