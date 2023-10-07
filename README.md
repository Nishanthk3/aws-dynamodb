## Command to run the docker compose 
```
docker-compose -f docker-compose-dynamodb.yaml up
```

## GUI for DynamoDB - [dynamodb-admin](https://github.com/aaronshaf/dynamodb-admin)
- Install [npm package](https://www.npmjs.com/package/dynamodb-admin?activeTab=code) for above DynamoDB UI
### Command to run the dynamodb-admin GUI
```
DYNAMO_ENDPOINT=http://localhost:9094  dynamodb-admin -p 7000 
```

## Reference
- https://medium.com/swlh/a-gui-for-local-dynamodb-dynamodb-admin-b16998323f8e
- https://www.npmjs.com/package/dynamodb-admin
