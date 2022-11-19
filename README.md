# Vault

Vault is used to avoid leaking sensitive information (passwords, secrets)

To start the vault:

* Install Docker
* Run the following command

```shell
docker run -d --cap-add=IPC_LOCK --env-file=.env vault server
```

