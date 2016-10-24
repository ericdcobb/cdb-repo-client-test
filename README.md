.npmrc for nexus 2

```
registry = http://localhost:8081/nexus/content/groups/npm-group/
email=my@email.com
always-auth=true
_auth=YWRtaW46YWRtaW4xMjM=
```

Nexus 3, not using .npmrc, instead:

```
npm login --registry=http://192.168.1.39:8081/repository/npm-group/
npm config set registry http://192.168.1.39:8081/repository/npm-group/
```
