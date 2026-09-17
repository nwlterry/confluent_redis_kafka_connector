# confluent_redis_kafka_connector

Offline zip of the Redis Kafka Connect connector plugin, version **0.9.1**.

## File

`redis-redis-kafka-connect-0.9.1.zip`

Install into a Kafka Connect plugin path (Confluent/Connect worker):

```bash
unzip redis-redis-kafka-connect-0.9.1.zip -d /usr/share/java/kafka-connect-plugins/
```

Then restart the Connect worker and confirm the connector class is listed on `/connector-plugins`.

Bulk-export of connector configs (without secrets): [kafka-connect_connector_config_bulk_export](https://github.com/nwlterry/kafka-connect_connector_config_bulk_export).
