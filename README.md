# Envoy

## 構築手順

`/etc/hosts` に下記を追記

```text
127.0.0.1 nginx.local
127.0.0.1 httpd.local
```

```bash
docker-compose up -d
```

```bash
curl nginx.local
curl httpd.local
```

## Reference

[envoy](https://www.envoyproxy.io/docs/envoy/latest/configuration/overview/example)

