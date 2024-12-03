# Keycloak練習用

## 起動
```
docker compose up
```

1. `keycloak-1  | 2024-12-03 08:27:02,413 WARN  [org.keycloak.quarkus.runtime.KeycloakMain] (main) Running the server in development mode. DO NOT use this configuration in production.`というログがコンソールに出力されるのを待つ
2. http://localhost:18080にアクセス
3. admin/passwordでログイン
