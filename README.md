# meza-conf-secret
hosts and encrypted conf

The secret.yml file is a place to store sensitive credentials and other data.

Using ansible-vault with a password file, you can decrypt the content to view it.

`sudo ansible-vault view /opt/conf-meza/secret/monolith/secret.yml --vault-password-file /opt/conf-meza/users/meza-ansible/.vault-pass-monolith.txt`
