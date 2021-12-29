# Freebox os dashboard
Node-RED flows to manage your Freebox with a Raspberry Pi
![Freebox os Dashboard](https://user-images.githubusercontent.com/54369031/130830690-dce667fe-11a1-4af0-b936-cefbe5593a22.png)

## Language
French only
## Install
Node RED installation :
```
bash <(curl -sL https://raw.githubusercontent.com/node-red/linux-installers/master/deb/update-nodejs-and-nodered)
```

### Palette needed :
`
node-red-contrib-crypto-js-dynamic
`
\
`
node-red-dashboard
`

Command line installation :
```
cd ~/.nodered
npm install node-red-contrib-crypto-js-dynamic
npm install node-red-dashboard
```
## Features
- Reboot button
- Uplink and Downlink gauge speed
- Upload and Download chart
- xDSL gain chart
- xDSL protocol and modulation
- Uptime
- Synchronisation and connection state
- IPv4 and IPv6 display
- Temperatures and fan speed
- DHCP main informations
- Static and dynamic IP - Host tables
- Connexion history
- Log of all connexions losts, with a monthly bar chart of all interruptions