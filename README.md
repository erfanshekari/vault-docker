# Deploy Vault On Container
Modify initial secrets on .env file
~~~shell
VAULT_ROOT_TOKEN="your-secret-root-token"
VAULT_USERNAME="admin"
VAULT_PASSWORD="admin"
VAULT_DEV_ROOT_TOKEN_ID="your-secret-root-token"
~~~
### Start Service
~~~shell
docker compose up -d
~~~
