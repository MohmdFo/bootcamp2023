```sh
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

```sh
git config --global user.name "name"
git config --global user.email "youremail@mail.com"
```

```
Host github.com
    PreferredAuthentications publickey
    IdentityFile ~/.ssh/id_rsa
```