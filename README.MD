## Auto send balance of Token

#### Clone Project

```
git clone https://github.com/thuandv68/bot-auto-send.git
cd bot-auto-send
```

#### Install Package
```
npm install

chmod +x bot

sudo npm link

```

#### Config [In config.js]

```
    TOKEN: "",
    PRIVATE_KEY: "",
    ADDR_TO: "",
    DELAY: 1, // second
    RPC: {
        URL: "https://linea.drpc.org",
        NAME: 'Linea Mainnet',
        CHAIN_ID: 59144
    }
```

#### RUN 

```
auto-send run
```