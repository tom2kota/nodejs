# [Node.js](https://nodejs.org/en/) => UBUNTU
Node.js install | npm | node | Yarn | curl - UBUNTU

Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine.

[docs](https://tom2kota.github.io/nodejs/)

--------

## Ubuntu packages upgrade 
```
sudo apt update

sudo apt upgrade

sudo apt autoremove

```

-------------------

## curl install
```

sudo apt install curl

```

-------------------

### YARN

```
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt update && sudo apt install yarn
export PATH="$PATH:/opt/yarn-[version]/bin"
export PATH="$PATH:`yarn global bin`"
yarn --version
curl --compressed -o- -L https://yarnpkg.com/install.sh | bash
yarn upgrade
```

###### [Node.js Release Working Group](https://github.com/nodejs/Release#nodejs-release-working-group)

Using a Node.js [version management package](https://github.com/nvm-sh/nvm)

``` 
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash

export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm

command -v nvm

nvm ls-remote

nvm install 12.18.2
nvm install node

nvm ls
nvm use node 12.18.2
nvm alias default 12.18.2

node -v
nvm run node --version
```

in a terminal to see if ```n``` is installed on your system. If it’s installed, 
you can run ```n 10``` to install and use Node.js version 10.

To update npm
```
nvm install lts/* --reinstall-packages-from=default --latest-npm

nvm install-latest-npm
```

To restore your PATH, you can deactivate it:
```
nvm deactivate
```

To set a default Node version to be used in any new shell, use the alias 'default':
```
nvm alias default node
```



```

```



```

```

