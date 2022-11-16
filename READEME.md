**Install**

```bash
# https://nodejs.org/en/
[x] node v18.12.1
[x] npm  v9.1.1

# Packets NPM global (~$ npm i -g moleculer-cli@0.8.0)
C:\Users\pi\Desktop>npm list --global
C:\Users\pi\AppData\Roaming\npm
├── moleculer-cli@0.8.0
├── node-red@3.0.2
└── npm@9.1.1

# Packets NPM node-red 
# ~$ cd C:\Users\pi\.node-red
# ~$ npm i nats@2.9.0
C:\Users\pi\.node-red>npm list         
node-red-project@0.0.1 C:\Users\pi\.node-red
├── nats@2.9.0
└── node-red-contrib-moleculer@0.5.2     

# Packets NPM moleculer
# ~$ cd C:\Users\pi\Desktop\moleculer-and-node-red\moleculer-based
# ~$ npm i --save
C:\Users\pi\Desktop\moleculer-and-node-red\moleculer-based>npm list
moleculer-based@1.0.0 C:\Users\pi\Desktop\moleculer-and-node-red\moleculer-based
├── jest-cli@27.5.1
├── jest@27.5.1
├── moleculer-repl@0.6.6
├── moleculer-web@0.10.4
├── moleculer@0.14.26
└── nats@2.9.0
```

**RUN**




```bash
[x] NATS 
(C:\Users\pi\Desktop\moleculer-and-node-red\nats-server-v2.9.6-windows-amd64\nats-server.exe)

[x] API e GREETER 
~$ cd C:\Users\pi\Desktop\moleculer-and-node-red\moleculer-based
~$ npm run dev

[x] NODE-RED 
# Paste the flow to your local node-Red C:\Users\pi\.node-red\lib\flows\flows.json or simply import the clipboard by copying and gluing the JSON code
~$ node-red
# http://127.0.0.1:1880/
```