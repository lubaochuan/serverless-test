# demo code
source: [A crash course on Serverless with Node.js](https://hackernoon.com/a-crash-course-on-serverless-with-node-js-632b37d58b44)

```
$ npm install -g serverless
$ serverless config credentials --provider aws --key xxxxxxxxxxxxxx --secret xxxxxxxxxxxxxx
$ serverless create --template aws-nodejs --path my-service
$ serverless deploy -v
$ serverless invoke -f hello -l
$ npm init
$ npm install serverless-offline --save-dev
$ serverless
$ serverless offline start
```
