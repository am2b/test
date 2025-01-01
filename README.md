create directory of keyring and create config file:
```bash
keyring_init.sh
```

create a new vault in keyring directory:
```bash
create_new_vault.sh new_vault_name
```

add a new item to a vault:
```bash
add_new_item.sh -i item_name -v vault_name
```

encrypt a item:
```bash
encrypt_item.sh -i item_name -v vault_name
```

decrypt a item:
```bash
decrypt_item.sh -i item_name -v vault_name
```

list all vaults in the keyring directory:
```bash
list_vaults.sh
```

generate password:
```bash
generate_password.sh length
```
