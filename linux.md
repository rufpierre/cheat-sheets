Modifier l'environnement de tous les users
---
créer un script sh dans /etc/profile.d/

Passwordless ssh
---
```
ssh-keygen -t rsa
cat .ssh/id_rsa.pub >> .ssh/authorized_keys (ou sur le authorized_keys de la machine cible)
```

Installation d'un programme
---
*Exemple avec maven*

Installer depuis l'archive
```
$ wget http://mirror.cc.columbia.edu/pub/software/apache/maven/maven-3/3.0.5/binaries/apache-maven-3.0.5-bin.tar.gz
$ sudo tar xzf apache-maven-3.0.5-bin.tar.gz -C /usr/local
$ cd /usr/local
$ sudo ln -s apache-maven-3.0.5 maven
```

Setter le path maven pour tout le système
```
sudo vi /etc/profile.d/maven.sh
```

```
export M2_HOME=/usr/local/maven
export PATH=${M2_HOME}/bin:${PATH}
```


CentOS
===
```
yum search MON_PROGRAMME
yum install MON_PROGRAMME
```
