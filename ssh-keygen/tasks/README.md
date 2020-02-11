SSH 秘密鍵・公開鍵の作成と公開鍵の登録を行う。
```
ansible-playbook -i hosts ssh-keygen/keygen-local.yml
ansible-playbook -i hosts ssh-keygen/authkey-remote.yml --ask-pass
```
