
### install node
```
// check
node -v
npm -v


// install

// install curl
sudo apt install curl

// for *latest* release
curl -sL https://deb.nodesource.com/setup_10.x | sudo bash -

// for *LTS* release
curl -sL https://deb.nodesource.com/setup_8.x | sudo bash -

// Install Node.Js And NPM
sudo apt install nodejs

```

### install truffle

`sudo npm install -g truffle`

### create a folder

```
mkdir smart_contract
cd smart_contract
```

### create a file named *truffle.js* 

`vi truffle.js`

and write

```
module.exports = {
  networks: {
    development: {
      host: "127.0.0.1",
      port: 8545,
      network_id: "*" // Match any network id
    }
  }
};

```

### install *ganache*

goto `https://truffleframework.com/ganache` and download *ganache*
[ checked allow executing file as program on file permission (simple right click and open properties) ]

### install MetaMask google chrome extention and configure it
goto `https://metamask.io/` and install chrome extention

### collect phrase backup data
`truffle develop`

You will fill a mnemonic like:
Mnemonic: candy maple cake sugar pudding cream another rich big crumble sweet treat

### setup metamask
```
open metamask 
logout
import using account send phrase
enter phrase and password
```
