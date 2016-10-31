# from trumpinsane to insane: a coin swap #

Insane is independent of trump. It is a new compile, with a different genesis block, merkel hash root, nonce, unix start time, ports, pchMessages, base58 address which begins with the letter "i" for insane. It is a new chain and can not intermingle with its predecessor. It retains similar characteristics (see below). One difference is to allow mining up to 14,000 blocks, to give an opportunity for people to mine it. 


----


- Coin Swap to avoid confusion and make coin exchange friendly
- Algorithm: X11
- Ticker: INSANE 
- INSANE count: 22,000,000
- Reward system: PoS with initial 14,000 PoW blocks to mine
- Interest: 2 per cent, with staking from block 0
- 50 coins reward per block till 14,000
- Block times averaging 8 minutes
- Minimum Stake Age is 12 hours
- Maximised Stake Age is 120 hours

----

# Mining 14000 blocks #

<p>Mining is available at <a href="http://cryptominers.online:8080/getting_started" target="_blank">CRYPTOMINERS.ONLINE</a>.</p>


----

# Swapping Coins #

<p>The deadline is in early to mid November. Check at <a href="http://insanecoin.com" target="_blank">insanecoin.com</a>, and at <a href="https://bitcointalk.org/index.php?topic=1625942.0" target="_blank">the bitcointalk insane thread</a> to make sure you do not miss the deadline.</p> The address to return coins to is: <a href="http://109.169.57.125:3001/address/THNHFC6SxHw6ngjcmBNxCy4an2P7D4hXEj" target="_blank">THNHFC6SxHw6ngjcmBNxCy4an2P7D4hXEj</a> 

----


# Destroying Returned Trumpinsane #

<p>After a claim has been settled the Trumpinsane should be destroyed. An address was made for this purpose. It was made using a Python Base58 and Base58Check implementation template. No private key was generated and the coins do not stake, nor can they be removed by anyone.</p>

<p><a href="http://109.169.57.125:3001/address/TBurntrumpinsaneCoinSwapDeadZMtQWg" target="_blank">TBurntrumpinsaneCoinSwapDeadZMtQWg</a></p>

<p>Broken down: "T Burn trumpinsane CoinSwap Dead ZMtQWg." </p>

<p>The last six characters, ZMtQWg, act as a checksum, and are generated using the Python Base58 and Base58Check implementation template along with the first 28 chosen characters.</p>

----

# Trumpinsane Bounty Pot #

<p>The Bounty Pot sent by me to <a href="http://109.169.57.125:3001/address/THNHFC6SxHw6ngjcmBNxCy4an2P7D4hXEj" target="_blank">THNHFC6SxHw6ngjcmBNxCy4an2P7D4hXEj</a> is destroyed. Other coins returned to <a href="http://109.169.57.125:3001/address/THNHFC6SxHw6ngjcmBNxCy4an2P7D4hXEj" target="_blank">THNHFC6SxHw6ngjcmBNxCy4an2P7D4hXEj</a> will aso be destroyed after they have confirmed and the transaction checked.:</p>

<p><a href="http://109.169.57.125:3001/address/TBurntrumpinsaneCoinSwapDeadZMtQWg" target="_blank">TBurntrumpinsaneCoinSwapDeadZMtQWg</a></p>

<p><strong>NB. Check on <a href="http://insanecoin.com" target="_blank">insanecoin.com</a>, and at <a href="https://bitcointalk.org/index.php?topic=1625942.0" target="_blank">the bitcointalk insane thread</a> to make sure you send to  the correct admin address. Do not send directly to the burn address.</strong></p>


----

# An extra 7.5 million insane #

<p>There is circa 7.5 million insane to decide about what to do with. This is the money left over after all swaps have been undertaken. Under Trumpinsane 6.5 million had stood unused in 1 account. </p>

----

# Insane Explorer #


<p>An explorer is running here, which I have put up, (but alternative arrangements will be made):</p>

<p><a href="http://216.189.144.26:3001/" target="_blank">http://216.189.144.26:3001/</a></p>

----
<p>insane.conf</p>

<p>username=<br />
password=<br />
daemon=1<br />
rpcallowip=127.0.0.1<br />
listen=1<br />
rpcport=8029<br />
port=8028<br />
addnode=91.121.67.93<br />
addnode=37.220.9.226:33700<br />
addnode=216.189.144.26</p>

----

# Windows QT (Mac on its way) #

<p><a href="http://crunckspool.co.uk/wallets/insane-qt.exe" target="_blank">crunckspool</a>, with mining to follow</p>

----

# linux people #

<p>apt-get install git build-essential libssl-dev libboost-all-dev libdb++-dev libminiupnpc-dev qt-sdk -y</p>


----

- To use the " USE_UPNP=- " or not! Just add it if you are used to it. 


- server

<p>make -f makefile.unix</p>

<p>./insaned</p>

----

- linux qt

<p>qmake -qt=qt4</p>
<p>make</p>

----

# extra #

<p> Coin swap details and mining details to be provided at <a href="https://bitcointalk.org/index.php?topic=1625942.0" target="_blank">bitcointalk</a> by any interested parties. This includes what to do with the extra 7.5 million insane.</p>

----

# Insane in the Membrane! #

<p><img alt="insane in the membrane" src="http://v013o.popscreen.com/eDlncHQwMTI=_o_cypress-hill---insane-in-the-brain.jpg" style="width: 533px; height: 400px;" /></p>


----

<p>Best of luck, Mountaind</p>




