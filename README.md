# Host Web Service with AWS Lambda

More info here:  [https://coderecipe.ai/architectures/71853269](https://coderecipe.ai/architectures/71853269)

### Prerequisites
```  
npm install serverless  
```  
Make sure you have AWS access key and secrete keys setup locally, following this video [here](https://www.youtube.com/watch?v=KngM5bfpttA)


### Download the code locally

```  
serverless create --template-url https://github.com/CodeRecipe-dev/apigw-lambda --path apigw-lambda
```

### Deploy to the cloud
 
```
cd apigw-lambda

serverless deploy
```
