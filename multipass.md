# Multipass



installation sur ubuntu :

~~~bash
sudo snap install multipass
~~~

commandes :

~~~bash
# nouvelle vm
multipass launch -n nomvm
# nouvelle vm avec cloud-init
multipass launch --cloud-init fichier.yaml 
# stop vm
multipass stop  nomvm
# start vm
multipass start  nomvm
# ouvrir un shell
multipass shell nomvm
# supprimer un vm
multipass delete nomvm
multipass purge
## configurer une vm 
multipass launch -n strapapp -c 2 -m 2G --cloud-init cloud-init-strapapp.yaml

~~~



## Lancement des VM

~~~bash
openssl rand -base64 24
chartbrew



~~~

