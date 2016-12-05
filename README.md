Lisk Network Stats
============
This is a visual interface for tracking lisk network status. It uses WebSockets to receive stats from running nodes and output them through an angular interface. It is the front-end implementation for [lisk-network-reporter](https://github.com/karek314/lisk-network-reporter).


## Installation
<pre>
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.32.1/install.sh | bash
export NVM_DIR="/root/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh"  # This loads nvm
nvm install 6.2.0
git clone https://github.com/karek314/lisk-network-stats
cd lisk-network-stats
npm install
npm install -g grunt-cli
</pre>

## Build
<pre>
grunt
</pre>


##Run
<pre>
PORT=3010 WS_SECRET=test npm start
</pre>

see the interface at http://localhost:3010

## Credits
Thanks to [cuberdo](https://github.com/cubedro/) and his [eth-netstats](https://github.com/cubedro/eth-netstats). This software has been created on the top of his work.
