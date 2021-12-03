# doj-casino 

Edited Casino Pack for QBus Framework

# Updated 11/30/21
- seat switching in qb-blackjack fixed (misplaced callback caused whole mess up...)
#### Updated 11/14/21
- Casino now uses Casino Chips

# Dependencies
**[qb-menu](https://github.com/qbcore-framework/qb-menu)**

**[qb-target](https://github.com/BerkieBb/qb-target)** 

**[textUi](https://github.com/dojwun/textUi)**

**[casinoUi](https://github.com/dojwun/casinoUi)**

# Images
![casino_redchip](https://i.imgur.com/JBjBg0n.png)
![casino_whitechip](https://i.imgur.com/1nWyXiI.png)
![casino_bluechip](https://i.imgur.com/pOi0vc5.png)
![casino_blackchip](https://i.imgur.com/9z2b6ga.png)
![casino_goldchip](https://i.imgur.com/7NPjx6H.png)
![casino_member](https://i.imgur.com/SOxFphs.png)
![casino_vip](https://i.imgur.com/nBvSini.png)

### qb-core/shared.lua info
```
	["casino_redchip"] 				 = {["name"] = "casino_redchip", 			 ["label"] = "Casino Chip", 			["weight"] = 0, 		["type"] = "item", 		["image"] = "casino_redchip.png", 				["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false,   ["combinable"] = nil,   ["description"] = "Diamond Casino Inside Track Chip"}, 
	["casino_whitechip"] 			 = {["name"] = "casino_whitechip", 			 ["label"] = "Casino Chip", 			["weight"] = 0, 		["type"] = "item", 		["image"] = "casino_whitechip.png", 			["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false,   ["combinable"] = nil,   ["description"] = "Diamond Casino Slot Machine Chip"},
	["casino_bluechip"] 			 = {["name"] = "casino_bluechip", 			 ["label"] = "Casino Chip", 			["weight"] = 0, 		["type"] = "item", 		["image"] = "casino_bluechip.png", 				["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false,   ["combinable"] = nil,   ["description"] = "Diamond Casino Roulette Chip"},
	["casino_blackchip"] 			 = {["name"] = "casino_blackchip", 			 ["label"] = "Casino Chip", 			["weight"] = 0, 		["type"] = "item", 		["image"] = "casino_blackchip.png", 			["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false,   ["combinable"] = nil,   ["description"] = "Diamond Casino Blackjack Chip"},
	["casino_goldchip"] 			 = {["name"] = "casino_goldchip", 			 ["label"] = "Casino Chip", 			["weight"] = 0, 		["type"] = "item", 		["image"] = "casino_goldchip.png", 				["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false,   ["combinable"] = nil,   ["description"] = "Diamond Casino Chip"},
	["casino_member"] 				 = {["name"] = "casino_member", 			 ["label"] = "Casino Membership", 		["weight"] = 500, 		["type"] = "item", 		["image"] = "casino_member.png", 				["unique"] = true, 		["useable"] = false, 	["shouldClose"] = false,   ["combinable"] = nil,   ["description"] = "Diamond Casino Member Card"},
	["casino_vip"] 					 = {["name"] = "casino_vip", 			 	 ["label"] = "V.I.P Membership", 		["weight"] = 500, 		["type"] = "item", 		["image"] = "casino_vip.png", 				    ["unique"] = true, 		["useable"] = false, 	["shouldClose"] = false,   ["combinable"] = nil,   ["description"] = "Diamond Casino V.I.P Card"},


```  

## Casino Entrance
- Casino IPL: (casino accessible without the use of teleports)

**[preview](https://streamable.com/jem98k)**

**[source](https://forum.cfx.re/t/cayo-perico-casino-dlc-ipl-loader/2099391)**

## Casino Luckywheel
- Luckywheel: (peek to spin the luckywheel with $5000 a V.I.P membership)

**[preview](https://streamable.com/ucv48w)**

**[source](https://github.com/Sn0wBiT/esx_tpnrp_luckywheel)**



## Casino Inside Track
- Inside Track: (bet on virtual racehorses with a casino membership and a 100 min chip bet)
 
**[preview](https://streamable.com/m5eyk)**

**[source](https://github.com/MRV6/mp_insidetrack)**

## Casino Blackjack 
- [Bugged with multiple people, re-work coming soon]
- Blackjack: (play 14 blackjack tables with a casino membership and a 10 min chip bet)

**[preview](https://streamable.com/jpabhl)**

**[source](https://github.com/Xinerki/kgv-blackjack)**


## Casino Slot Machines *(contact if interested)* ```</dojwun>#2103```
- Slot Machines: (play 44 slotmachines with a casino membership and a different bet each slot) -REMOVED

**[preview](https://streamable.com/5xwkki)** -REMOVED

**[source](https://forum.cfx.re/t/qb-casino-slots-machine-with-sounds/4766305)** -REMOVED


## Casino Roulette
- Roulette: (now works but locations need to be adjusted)

**[preview](https://streamable.com/85vjqc)**

**[source](https://forum.cfx.re/t/standalone-paid-aquiver-casino-roulette/2925508)**
