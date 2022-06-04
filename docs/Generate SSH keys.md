# Generate SSH keys

## Generate public/private rsa key pair

```bash
ssh-keygen -t rsa -b 4096 -f ~/.ssh/KEY_NAME.key -C "KEY_DESCRIPTION"
```

Enter passphrase (empty for no passphrase).

Identification will be saved in `~/.ssh/KEY_NAME.key`
Public key will be saved in `~/.ssh/KEY_NAME.key.pub`
