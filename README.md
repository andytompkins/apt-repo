apt-repo
========

program to create apt repos and add packages to them


Installation
* mkdir /etc/apt-repo
* cp repo.conf.sample /etc/apt-repo/repo.conf
* cp *.tmpl /etc/apt-repo
* edit the config and templates to suit your needs
* create the directory for your repo and distributions (mkdir -p /opt/repo/dists)
* cp apt-repo /usr/bin
