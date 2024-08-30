---
title: "Installation unter Linux"
date: 2020-12-31T09:29:07+02:00
draft: false
chapter: true
weight: 60
---
# Installation von Element Desktop unter Linux
Wir empfehlen das Installieren des Clients über die Paketverwaltung der jeweiligen Distribution. Die folgenden Befehle installieren den Element Desktop Client über die Kommandozeile.

### Debian/Ubuntu
```sh
sudo apt install -y wget apt-transport-https

sudo wget -O /usr/share/keyrings/element-io-archive-keyring.gpg https://packages.element.io/debian/element-io-archive-keyring.gpg

echo "deb [signed-by=/usr/share/keyrings/element-io-archive-keyring.gpg] https://packages.element.io/debian/ default main" | sudo tee /etc/apt/sources.list.d/element-io.list

sudo apt update

sudo apt install element-desktop
```

Für alle weiteren Derivate und Optionen, lohnt sich ein Blick auf die Website von Element:

[**_https://element.io/download#linux_**](https://element.io/download#linux)