# Amazon Textract  Extraction feature

## Create a small command line app that scans a file and outputs a JSON result.

1. mkdir textract-lab


2. cd textract-lab && yarn init (for Windows run: cd textract-lab ; yarn init )


3. touch index.js


4. yarn add commander aws-sdk lodash

### Set Up an AWS Account and Create an IAM User (https://docs.aws.amazon.com/textract/latest/dg/setting-up.html)

- Configure an IAM User to use textract.

- Open config.js and paste the following (insert your keys plus the region)
#### module.exports = {awsAccesskeyID: "",awsSecretAccessKey: "",awsRegion: ""};

#  Testing

- run 
```
node index.js scan /path-to-your-file/file-example.png
```
