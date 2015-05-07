Modifier l'environnement de tous les users
---
créer un script sh dans /etc/profile.d/

Passwordless ssh
---
```
ssh-keygen -t rsa
cat .ssh/id_rsa.pub >> .ssh/authorized_keys (ou sur le authorized_keys de la machine cible)
```

CentOS
===
```
yum search MON_PROGRAMME
yum install MON_PROGRAMME
```
