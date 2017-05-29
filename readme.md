#WRIO local development package

Please refer wiki for local development instructions

# Clone your repositories there

Note: replace "webRunes" in the URLs below to your github name, if you're going to
work on this fork.

If you're going to work on front-end only, first two will be enough
```
git clone https://github.com/webRunes/WRIO-local-dev
cd WRIO-local-dev

git clone https://github.com/webRunes/WRIO-InternetOS
git clone https://github.com/webRunes/Default-WRIO-Theme
```

If you're going to work on back-end too, clone backend repos as well

```
git clone https://github.com/webRunes/Core-WRIO-App
git clone https://github.com/webRunes/Login-WRIO-App
git clone https://github.com/webRunes/Storage-WRIO-App
git clone https://github.com/webRunes/webGold-WRIO-App
git clone https://github.com/webRunes/Chess-WRIO-Game
git clone https://github.com/webRunes/Plus-WRIO-App
git clone https://github.com/webRunes/Titter-WRIO-App
```

install yarn, if you don't have one

```
npm install -g yarn
cd WRIO-InternetOS
yarn
npm run devserver
```
Now each time you start frontend server, run
```
cd WRIO-InternetOS
npm run devserver
```
note: use ```sudo npm run devserver``` on unix systems


[Local development of WRIO-InternetOS front end](https://github.com/webRunes/WRIO-InternetOS/wiki/Deploy-on-localhost)  
[How to setup development process on local machine](https://github.com/webRunes/WRIO-local-dev)
