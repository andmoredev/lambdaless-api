# Lambdaless API

For more details on how it works go to [How to build a Serverless API without using a single Lambda](https://medium.com/@amorenom/how-to-build-a-serverless-api-in-aws-without-using-a-single-lambda-522ce43a6fb6)

# Pre requisites
* [AWS CLI is installed](https://aws.amazon.com/cli/)
* [SAM CLI is installed](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html)
* [npm is installed](https://www.npmjs.com/get-npm)
* [Your AWS Configuration is pointing to your account](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html)

# How to run
* Clone repository
* Replace any instance of [BUCKET-NAME] with the name of your bucket.
* Run the following command
```javascript
npm run deploy
```