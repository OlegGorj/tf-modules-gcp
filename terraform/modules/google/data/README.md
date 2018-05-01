
## Set up Vault

SSH to prod-vault-0 and run:

```
$ vault init
$ vault unseal (x3)
```

SSH to prod-vault-1 and run:

```
$ vault unseal (x3)
```

Update the vault_token variable in Atlas and then queue a plan and apply.
