# Dino

![](screenshot.gif)

Google Chrome's offline minigame

[![OpenStore](https://open-store.io/badges/en_US.png)](https://open-store.io/app/dino.collaproductions)
[![](https://i.imgur.com/KIipzE8.png)](https://t.me/collaproductions)


### Building instructions (Ubuntu-based distros)

Install [clickable](https://clickable-ut.dev/en/latest/install.html):

```
$ sudo add-apt-repository ppa:bhdouglass/clickable
$ sudo apt-get install clickable
```

Clone this repository and build:

```
$ git clone https://github.com/nicolascolla/dino.git
$ cd dino
$ clickable build
```

### Building instructions for 16.04

Install [clickable](https://clickable-ut.dev/en/latest/install.html):

```
$ sudo add-apt-repository ppa:bhdouglass/clickable
$ sudo apt-get install clickable
```

Clone this repository, change the framework and build:

```
$ git clone https://github.com/nicolascolla/taptaptap.git
$ cd taptaptap
$ sed -i 's/ubuntu-sdk-20.04/ubuntu-sdk-16.04.5/' clickable.json
$ sed -i 's/20.04/16.04/' dino.apparmor
$ clickable build
```

You can play the game on any web browser by opening www/index.html.
