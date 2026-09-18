# confluent_redis_kafka_connector

Offline zip of the Redis Kafka Connect connector plugin **0.9.1**.

## Layout

```
packages/redis-redis-kafka-connect-0.9.1.zip
GROUP.md
README.md
```

```bash
unzip packages/redis-redis-kafka-connect-0.9.1.zip -d /usr/share/java/kafka-connect-plugins/
```

Then restart Connect and check `/connector-plugins`. Config export (no secrets): [kafka-connect_connector_config_bulk_export](https://github.com/nwlterry/kafka-connect_connector_config_bulk_export).

---

See [GROUP.md](GROUP.md) for sibling repositories. Catalog: https://github.com/nwlterry/nwlterry
