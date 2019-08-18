### nakadi
---
https://github.com/zalando/nakadi

```
```

```sh
./gradlew startNakadi
./gradlew stopNakadi
curl -v -XPORT http://localhost:8080/event-types -H "Content-type: application/json" -d '{
  "name": "order.ORDER_RECEIVED",
  "owning_application": "order-service",
  "category": "undefined",
  "schema": {
    "type": "json_schema",
    "schema": "{ \"additionalProperties\": true }"
  }
}'
```

```
```


