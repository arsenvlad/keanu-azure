# Simple Example

```
azure account set "POC subscription"
azure group create --name "keanu-example1" --location "westus"
azure group deployment create --resource-group "keanu-example1" --template-file "simple-example.json"
```