# A fresh attempt to a fully functioning dockersied private blockchain initially with two nodes and a bootnode

* Durin the first attempt everything seemed to working but all of a sudden the mining stopped and I couldn't make transactions among the nodes.

* I will be changing the name of my ethereum network as well. As puppeth I think keeps the already generated networks in its memory.

* There was also the issue of imported accounts in metamask, I will be solving that issue this time as well. There must not be any issues ideally as things seemed to work well outside the docker world even with the imported accounts.

* Okay so the importing accounts takes quite long. In order of minutes! So it is bit of a time consuming process. I could create two more accounts so that I have found nodes for a full mesh network setup.

* Through metamsk everything seems to be working okay. I can send funds through metamask from important accounts to the already created account and the other way around is working as well.

* But I can not seem to do the same using the geth console from within the docker containers.

- [x] See if you can find transaction receipts created within the metamask using the geth console.
- [x] See if you can transfer funds between the imported accounts through geth console.
- [ ] See if you can transfer funds between imported and generated accounts using geth console.

* Need to see what could be the problem in terms of generated and important account funds transferss using geth console. Networking seems to be working fine. Could be an issue related to rpc or how geth commands are used in general to start the blockchain nodes.
