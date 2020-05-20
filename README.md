<a href="https://aimeos.org/">
    <img src="https://wellcoin.tk/img/logo.png" alt="logo" title="Wellcoin" align="right" />
</a>

Wellcoin (WELL) integration/staging repository
======================
> Official Repository - PoS/MN

:star: Wellcoin is an experimental digital currency that enables anonymous, instant payments to anyone, anywhere in the world. Wellcoin uses peer-to-peer technology to operate with no central authority: managing transactions and issuing money are carried out collectively by the network. Wellcoin is the name of the open source software which enables the use of this currency.

<p align="center"><a href="https://github.com/wellcoin/wellcoin"><img src="https://wellcoin.tk/img/wallet.png" /></a></p>
<hr>

|Specifications		   		| 					  |						|					  |
|:-------------------- 		| :------------------ | :------------------ | :------------------ |
|Name  		                | `Wellcoin`             |Blocks per Day   	| `1440`              |
|Ticker 				    | `WELL`               |Block Time  			| `1 MINUTE`          |
|Algorithm					| `Quark`             |Stake Min Age		| `3 MINUTES`           |
|Type 						| `PoS/MN`            |Halving Block  		| `0`            |
|Total Suply 			    | `18,000,000 ZCR`    |Port 			    | `19193`    		  |
|Masternode Collateral      | `5,000 WELL`         |Datadir			    | `.wellcoin`			  |

<p align="center"><img src="https://wellcoin.tk/img/blocks.png" /></a></p>

Add nodes
======================
```
# zcore.conf

addnode=
addnode=
addnode=
```

Staking
======================
Enable
```
# wellcoin.conf
staking=1
```

Disable
```
# wellcoin.conf
staking=0
```

<h3>Licence</h3>
Wellcoin is released under the terms of the MIT license. See COPYING for more information or see https://opensource.org/licenses/MIT.

