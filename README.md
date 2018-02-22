# IRIS Tokensale


Opening time:
 
    presaleStart = 1521426600, Monday March 19, 2018 10:30:00 (am) in time zone Asia/Singapore (+08)
    presaleEnd = 1522044000, Monday March 26, 2018 14:00:00 (pm) in time zone Asia/Singapore (+08)
    publicsaleStart = 1522895400, Thursday April 05, 2018 10:30:00 (am) in time zone Asia/Singapore (+08)
    publicsaleEnd = 1523512800, Thursday April 12, 2018 14:00:00 (pm) in time zone Asia/Singapore (+08)

## Presale and Public Sale (fallback function)

* min purchase 0.001 ether
* max purchase 20000 ether;
* pre-authorised 


## Private Sale (placeTokens)

* by Admin user
* tokens minted on demand before or while sale is active.
* uses `placeTokens()` function

## Authorisation

* by CS and Admin user 
* can approve or block
* call `authoriseAccount()` / `authoriseManyAccounts()` / `blockAccount()`


##  Rate 

* presale 1 ETH = 4000 IRT
* publicsale 1ETH = 2500 IRT
* Admin user can set both of rate 
* call  `setPresaleRate()` /  `setPublicsaleRate()`function


## Finishing the sale (owner) - passes control of token back to the owner

* call `finishSale()` 

## Starting Trading

* call `startTrading()` on the TOKEN-contract



