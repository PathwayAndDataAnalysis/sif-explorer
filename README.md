# CausalPath Newt Webserver

CausalPath Webserver with new newt as a visualization tool.

### Requirements

- Node v14.x.x
- Unzip (get it with `sudo apt install unzip`)
- Java (preferably Java 11, get it with `sudo apt install openjdk-11-jdk`)

#### Check node version

- Enter `node --version` in your terminal and it should output `v14.x.x`
- if you do not see such output in your terminal, then you have to install node JS

## Install [Node JS](https://nodejs.org/)

### Linux

#### 1. Using [nvm](https://github.com/nvm-sh/nvm/blob/master/README.md)

```bash
sudo apt-get update
sudo apt-get upgrade
```

Install [curl](https://curl.se/)

```bash
sudo apt install curl
```

Install nvm

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```

Installing nvm using nvm

```bash
nvm install 14
```

Check version

```bash
node --version
```

### Windows

- Visit https://nodejs.org/en/ and download installation file and install it

### MacOS

- Install using homebrew:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install node
node --version
```

## Getting Started

```bash
git clone https://github.com/PathwayAndDataAnalysis/causalpath-newt-webserver.git
cd causalpath-newt-webserver
npm install

npm start
```



## Latest Updates:

- Click on `> Query On SIF Graph Server` and you will see the newt window.

- Now for querying SifGraph click on `Query button` in Newt window.

- Two Options of query will open up select `SifGraph Server (NEW)`.

- Select the query option from the dropdown menu.

### ToDo:

- Add API call to make query execute.
- Add pending query options.
