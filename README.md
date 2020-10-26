# kc - Simple Kafka Client

## Compile

```bash
TAG_NAME=v$(cat VERSION) make tag
```

## Running

### Setting variables

```bash
export KAFKA_BOOTSTRAP_SERVERS=broker:9092
export CA_CERT_LOCATION=../certs/ca/ca-cert
export KAFKA_TOPIC=mytopic
export USER_CERT_LOCATION=../certs/client/cli-signed.crt
export USER_KEY_LOCATION=../certs/client/cli.key
```

### Testing

```bash
./kc_linux-amd64
```