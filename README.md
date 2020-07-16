# Basic connection to DynamoDB
This repository shows the connection with a DynamoDB Table through credentials and how connect with your local version. The code doesnt have a  good programming practices becuase its focus is show an easy use of the DyanmoDB's SDK.

The steps used to set up DynamoDB Local are the following:

1. [Download DynamoDB](https://s3.us-west-2.amazonaws.com/dynamodb-local/dynamodb_local_latest.zip)
2. Unzip files
3. Execute DynamoDB with the following command:
'java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb'
4. Go to the console through http://localhost:8000/shell

However, to access since Java, must be guaranteed that aws cli is [installed](https://docs.aws.amazon.com/es_es/cli/latest/userguide/install-cliv2.html) and [configured](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html). The above is resumed on [AWS documentation](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DynamoDBLocal.DownloadingAndRunning.html)
