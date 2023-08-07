# Deploy Vault Production
Modify vault token on .env file
~~~shell
MY_VAULT_TOKEN="your-secret-root-token"
~~~
### Start Vault Server
~~~shell
docker compose up -d
~~~
### Init Or Unseal Tokens
~~~shell
sh init.sh
~~~