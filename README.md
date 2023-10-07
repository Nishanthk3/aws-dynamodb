## Command to run the docker compose 
```
docker-compose -f docker-compose-dynamodb.yaml up
```
The docker-compose-dynamodb.yaml file bring up
- GUI for DynamoDB - [dynamodb-admin](https://github.com/aaronshaf/dynamodb-admin)
- Will create test tables
- Will insert seed data into the tables
- UI will run on http://localhost:7000/


### Command to run the dynamodb-admin GUI 
#### Note: [Need not run this separately, as its included in the docker file itself
```
DYNAMO_ENDPOINT=http://localhost:9094  dynamodb-admin -p 7000 
```

## Reference
- https://medium.com/swlh/a-gui-for-local-dynamodb-dynamodb-admin-b16998323f8e
- https://www.npmjs.com/package/dynamodb-admin
