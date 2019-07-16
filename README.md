# Serverless Express Example

## Installation

### [AWS CLI Installation](http://docs.aws.amazon.com/cli/latest/userguide/installing.html)

```bash
pip install awscli --upgrade --user
aws --version
```

### [AWS Profiles](https://serverless.com/framework/docs/providers/aws/guide/credentials/)

```bash
aws configure
```

![](docs/profiles.png)

### Ruby

TODO

### Rails

TODO

### [Serverless](https://github.com/serverless/serverless) 

```bash
npm install
npm install -g serverless
```


## Usage


### Serve Serverless Locally

```bash
serverless offline start

curl http://localhost:3000/
```


### Invoke function locally

[Docs](https://serverless.com/framework/docs/providers/aws/cli-reference/invoke-local/)

```
serverless invoke local --function api
```

### Deployment

```bash
serverless deploy --stage dev --aws-profile your-aws-profile
```

### Removal

```bash
serverless remove --stage dev --aws-profile your-aws-profile
```



## Articles & Resources

* [serverless.yml Reference](https://serverless.com/framework/docs/providers/aws/guide/serverless.yml/)
* [Serverless Offline Plugin](https://github.com/dherault/serverless-offline)
