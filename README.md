#tp1 devops
###info VM
Nom utilisateur: yves 
Mot de passe: yvon

##Avec VMWARE
Alors j'ai effectué ce TP1 sur VMWare. J'ai choisi une image et ensuite il faut ensuite changer la mémoire ram à 1GB.

###Installation de nodejs@12
```
apt get update
```
```
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
```

ensuite 

```
sudo apt install openssh-server nodejs 
```

##Virtualbox
Nous avons rencontrer des problèmes avec VMware lorsque nous avons voulu provisonner notre VM avec Vagrant. Le provider est payant donc nous allons utiliser Virtualbox.
### Vagrant
Intallation Vagrant 

```
brew cask install vagrant
```
Ensuite il faut créer un fichier "vagrantfile" et un script provisionning "bootstrap.sh"