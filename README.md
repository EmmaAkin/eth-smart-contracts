# LAToken Ethereum Smart Contracts

## Contents

+ [LAToken](#latoken)
+ [Smart contracts](#smart-contacts)
+ [Getting started](#getting-started)
+ [Installation](#installation)
+ [Testing](#testing)
+ [Contact us](#contact-us)
+ [Executive summary](#latoken-executive-summary)

## LAToken - [https://latoken.com](https://latoken.com)

> LAToken is a platform for buying and selling fractions of assets ranging from Real Estate and loans to the Works of Art.

Provide information about the asset and the share you want to sell. After independent valuation of the asset you can issue on the LAT platform tokens backed by the disposed asset. Then sell your tokens in the LAT marketplace and get funds. You can continue using your asset after the sale and buy it back.

Looking for a more liquid and diverse portfolio of assets? Liquid Asset Tokens give you fractional ownership of physical assets to help diversify your investments.

[https://latoken.com/](https://latoken.com/)

## Smart contracts

> What is Smart Contract: [Wikipedia](https://en.wikipedia.org/wiki/Ethereum#Smart_contracts)

During the testing period LAToken uses Ethereum to provide tokens functionalities. Currently, all our tokens (LATP, LAT, assets tokens) is ERC20 compatible Ethereum Smart Contracts.

This repository consists [Truffle](http://truffleframework.com/)-based smart contracts of out main token types. Using this contracts we can provide secure, robust, high performant way of assets tokenization and tokens transfering.

## Getting started

Be sure that you have already installed:

1. `geth` (manually, or with Mist/Ethereum Wallet) - [https://github.com/ethereum/mist/releases]()
2. `node.js` - [https://nodejs.org/en/download/]()
3. `npm` - should come with `node.js` as well
4. `truffle` - [http://truffleframework.com/]()

After that feel free to clone this repo to your disk:

```
git clone https://github.com/LAToken/eth-smart-contracts.git
```

## Installation

When everything is prepared and saved to the disk, you can just run:

```
cd eth-smart-contracts
npm i
```

So, now everything should be prepared, installed and ready to use.

## Testing

To check everything up you can use internal Truffle testing system based on [Mocha.js](https://mochajs.org)

To run all tests provided just type:

```
truffle test
```

## Contact us

We will be happy to tell you something more or to provide our help here:

![](data:image/gif;base64,R0lGODlhEAAQAOYAAAAAAP////3+/+75//H6/wCk+mPK/XTQ/Zzd/d3z/u35//P7//n9/wer+g6u+hCu+hGu+hOv+hax+hix+hiy+hmx+xmy+hqy+huy+hyz+h2z+x2z+h+0+yG0+yK0+yO1+iS1+iW2+ii3+yi2+iq3+yu4+yy4+y24+y64+y65+y+5+zC6+zG5+zG6+zK6+zK6+jO6+jS6+zW7+za7+ze7+zi8+zq9+zu9+zy9+zy++z29+z2++z6++z6/+z+++0C/+0G/+0K/+0O/+0PA+0TA+0XB+0bA+0bB+0fB+0fC+0jB+0jC+0nC+07D+0/E/FHF+13I/F3J/F/J/GDJ/GDK/GHK/HTQ/HfR/HrS/IfW/IjX/IvY/YzY/Y3Z/ZLb/ZXb/Znd/Zvd/Zze/Z3e/Z/f/aDf/aHf/aPg/aTh/ani/azj/bDk/bXm/cPr/s3u/tPw/tXx/tvz/t70/uv4/ur4/vv+//7//////wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEAAHcALAAAAAAQABAAAAfcgAGCAXJkBkxKVWNyg41mJSkkNUEzJSZljQFYEkEvNys0QT85FQeDaw5EJk8DbSc8Pj5CEWoBAxs4QBRegiMNLEQ+OxtzZx1APhldgmFaTiw+QB5kUzGxGVuNbxewMlJLPLDYggsEYB/hPElKPeLLdUU2KrCwS1TWPhdcAQIiBShHukVBwwHIDxBQBLnJ0qRFtA5mFGzI4YNHBjaD4HDboYFOADUPhgSB8SHMAAZfQAyBkGbQlQk6jNDAcGPIPAtWMo0xUaIGEBchSJwIYydTgARipCBhQgVBnEaBAAA7)   [Twitter]( https://twitter.com/LATokens)

![](data:image/gif;base64,R0lGODlhEAAQAPcAAAAAAP////Dy+O7w9vj5/LG8177H3tzh7ePn8QYrgQYsgQowgwswgwwxhAwxgw8zhRQ3iBQ4iBQ4hxw+jB0/jB1AjB5AjB9BjSJEjyRGkCVHkSVGkCdIkShJkilKkylJkilKkipKkypLkytLlCtMlCxMlC1NlS5OlS9Pli9OlS9PlTBQljFQlzFRlzFQljJRlzNSmDJRljNSlzRSmDVUmTVTmDZUmTZVmDdVmjdWmjdVmTdWmThWmjhXmjlXmzpXmzpYmzpZmztZnDtZmzxanD1anT1bnT1anD9cnkJgoENfoERgoEhkokllo0hkoUlkokploktmpE5ppU9ppVBqpVhyq2Z+smqAtGuBtG6EtnCGt3GHt3OIuHaLun2RvX+TvoKVwJWlyZqpzKa00qWz0ai106e00qm21Ky51a251a661rS/2bXA2bjD27vF3MPM4MTN4cvT5OXp8ipMk0Jgn2B5rpKjx6261fP1+fL0+Pr7/e/y9+ru9PX3+vT2+ff5+/r7/P///wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEAAIEALAAAAAAQABAAAAjvAAMIDOCnQBcpVLiowTOwoRsVFULkwFHCgog1DQOQcXDiiBEVHTz0eLEgzMA4CXgIIeICCRgxTWwAUWAggJ4QJIQAcSHkj0AsHoSgwECgTYQjQIakqBFAwJwfQIAcgYCGC4eoPHrACZDHjBIaUUFcYcIj6owgDZegwBrFyY6oPW5sCSAnicyoOaBk+RB1iAw6AQ5k4DEk6ggrbCQUiSqjSgAEKspKlXAG0IYTOmPUCTCgRdkhLS70CfBGQVIdT+x48eGjMAM2A8M0YGGkx4kVQ4jAePAl4x0PFEjkyGFigoY0GQXuKaNlyhQsY/g0DAgAOw==)  [Facebook](www.facebook.com/LiquidAssetToken/)

![](data:image/gif;base64,R0lGODlhEAAQAPcAAAAAAP/////5+tbd6t7l8OXr9cvX5snb6+ny+ePv963Q4+r0+vX6/QB+vAB8u9bs9+r2/PX7/vz+/wCOzgCHwwCDwQCBvgCCvQib3Auc3B+i3COl3iSj2yml3Cuo3y2q4TSq3jWq3kKy5FS45GXA6WOz2GWx1IDJ6YXN7qPV67bh9b7h8dzw+QCPywCNygCNyQCIwQCGwACHwAKMxgOU0waLwgiV0QeNxAeLwwiLwwqY1gmV0QmUzwmRywmNxQqV0AqOxgyVzw6c2g2Qxw+PxRGQxROXzxKRxROTyRORxRSRxhWWzhaWzBaVyxie1xaUxxaSxhmh3Buj3hmYzhiQxByj3hmVyByc0xua0BqVyByZzh6g2B2Xyx6bzx2VyB2WyB6WyB+XyR+WyCOm3yGe0yCXyCGZyyOf1SGXySGXyCObzSSbziOZyiWczySayyedziup4Cun3Sqm2yqi1C2p3yui1Smcyy2n2yuh0yqcyy2l2C2k1y2j1iyi1Cyg0jCs4S6l2S6m2S+m2i+m2C2ezjCn2zCo2zCn2jKp3TGp3DGo2zOq3jWs3zau4jat4Tas3zWr3TSo2jeu4jaq3Div4jmv4jmr3Dyv4UOz5ECr2Eyr01Cw2VKw2VOv1Vi331u331685WXB6Wi94me63Xe/3XnB4IHK6JDP6pvR55rQ5qPa8qLZ8aPZ8J3R56bb8p/S56TX7anc8qfY7a7e8azZ67Le8K/b7cLl9NPr9eTz+eb0+uv3/Oj0+ZrR5ub0+eHz+fX7/fT6/P3////+/f///wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEAAMQALAAAAAAQABAAAAj/AAMIDLBrVShMIkiogjCwISsNUeBIovRByhhXDQOYoiEnBAhGjiRV+pMBxcBaEwIdMpQI0aJHdDY0wqAiALAgZPboAXSo0BYdHUZc8lAlQooXfebwOfNjh6UTD3RBiiMkFicmfpa4wPJp1gIBAW45ucMB1Js1TTbJYhFgGIEEAU7ZEKRokhszQ0b5ClDgAAJhAUTx2DMokiYibIBQKDFgoIRMRupc8fTqApowPswYUPArQK4pXfC0gBUMhhIxXqyYoIIE14oZbbT0YBCAlgMwZcDceJLDCiEuairYGkiqAZQyX8CkSXIki4VSGVvhkFFEjJgiMWqgyiiQV6pOeex0BerFq2FAADs=) [Telegram](https://t.me/latoken)

![](data:image/gif;base64,R0lGODlhEAARAPcAAAAAAP///wADawAKbgASdAAWeAAZeAAdewAcegAgfQAhfQAjfwAjfAAmgAAngKGvzgAsgwArgkdnpert8wAwhQAzhwAyhmuJuL7K3gA1hwA1hgo+jBRHkDNgoGaFtbXE28jU5QA8jAM9jQtCjwtDjxxRmB5RlydZnitbnTNhojRioDZjokRuqVl+sVh9sFh9r1yBs2eKuHeXwXSTvHqXwIGdw4ymyY2nyY+oyZqwz5600a2/17fG28PQ4s/Z5tbe6SVbnkdzqoikyJCqyZyz0KG305+10J+1z7zM38TR4dbf6uzw9eHo8OTr8uXr8evw9QB57g2B7w+C7B2K8iiP8SiQ8CiP7yqR8SqR7yyS8iyR8C2S7zGV8jKV8zOW8zSX8zWX8zua8z2a8T6b9D6c9D2b8EGc8ESd8Eaf70+i7lSm8Vqp8Vup8Vyq8WOt8Gev8miw8Xa3836784jB9YvC843D9I3D85jI9qHN9azT9q/V95vK86vT9rHW9r7d98fg9dzs+fH3/MDe9svj9tPn997u+uXx+ur1/ff6/OXy+uz1+vv9/vr8/ff5+vT7/vn7+/3+/v3+/f7//f///f///v7+/v39/fX19f///wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEAAJgALAAAAAAQABEAAAjyAAMIHBjoj6WBCAVWEjjJDRyElSAN7EFE4B4odwYuGsJEYCMNHgIoMjOlzsAYGygJnCFASIBCYrywYRTAB4MTKgNcKBBE4BsuWvQEwEAhBBKBHypY2BEATxUwawSuQNBCIKUOB1gEcIRmDJY+AWw0EAFCYA4IGXgEsEPlS5sAl0wkgCHwEYoDLgIcMkNmi58ANBaQUCIQh4MRPwLQuZIlToAJJRTUEPgEiIEHAQCVCXMmUQAZBCQMTBHBSQBKcrpYERRAx4AbApdwKDIwTxQ1kwK8UDEwyRGEc6QQCiDJSJOBlhYKRJSGj8JICREaGhQ9QEAAOw==) [Steemit](https://steemit.com/@latoken)

![](data:image/gif;base64,R0lGODlhEAAQAPcAAAAAAP///8YAFdAAGcwAIckAJNEALfvl6tcbTfbH1P3y9fUARewfZv0zeeyJq/bE1fUAV9gAUM0AS90naeI8eup4ofKpw/CqxPS6z/vl7dgAUqYAQPNlnP+yz9sCXvCdwe58tm8AOjMAH2ggS6+kq//8/gcAFBwXNFDK+VnO+XjX+rPk9mrK6Kvm+cXx/13G5WXI437T6tPu9vj8/Smvy3rN34DO3q/h69Ht89rx9kW5z2DC1LLh6uz4+t7z9sLp6tTs7RlFRlm4ufr//y6emg5MSSqWkO35+Kba1SOQfwZ4XCyfg0uOfVuqlxCFZCGie+n38xGjdB+VcVG6mNfw6C2tgUS2kEe8lX70y4/UvZPWwL3z4cXp3crq3/X7+RXChB/JjButeSLJjiqygU2/lrng0tLu5ACVW5Liw8Pp1FGSW22dZkF9KzlmAPX38XF7Bvv+ydXXuIx8AJqFC+m4G7ycM+3EReasA/nWgO7hv/789+SiF+ipKumsQfHMi/bft/rs09+LAO2qOvPRmPjmx/337fuWAPuaCPmdDv/Nf//dq9x8APXYtNlnCthXKNE+E+6tnckiBr0AAPn5+f///wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEAAJQALAAAAAAQABAAAAjJAAMIHCgQUCGCCAn+CdQnoUAvWcwIVHQIUR4XPGYQ1HLmikA3deSsSUHjBsE0Y6ogWaFCTRs2O2L4IPhjiRMiL1A0eTMnDsEeNWAYUZLERgsgggwlIphDBwshUp50EYjnjp0DHywIxCHjCJkwaAQyavQIgQYDDwhi+TLlAocJAiQV8EAhw8ASJIKc2LAgAoFIjhIQxMBAgggTIRqAgLSHDhyCFQZAGFGEySSBfBYNIqjAQYcyYMRsEUjIjx6HQ6xE4eIwIRQqrQMCADs=) [Slack](https://latoken.herokuapp.com/)

![](data:image/gif;base64,R0lGODlhEAAQAOYAAAAAAP///+Tq7ZKeo8PP1HyBg4+dor3IzHyChOTq7PH09fP///9HAv9UFP9jKv9rMv92Qv/39P89AP9ZJv8wAP/+/v7+/v39/fr6+vj4+PX19fT09PHx8e3t7erq6unp6ejo6ODg4Nzc3Nra2tXV1dTU1MnJycfHx8bGxsXFxcTExMLCwsHBwb+/v76+vru7u7W1tbOzs7CwsK2traysrKqqqqenp6WlpaSkpKOjo6GhoaCgoJ+fn56enp2dnZubm5iYmJeXl5WVlZSUlJKSkpGRkZCQkIyMjIiIiIaGhoSEhHx8fHZ2dnR0dHNzc2xsbGlpaUtLS////wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEAAFIALAAAAAAQABAAAAeMgAGCg4SFhoeIhBxDLSRCMBaJMTUoUSVAIokrghhILBeGITBMTCwhhiA+PUYDBCMjBwZHNjsfgjcrTxqGClAmPII6S4IMEoINFIJNOIImPwEVDw6CEBMRAUEnghtJgguE3wFKGYMxPgEJCDg5BQIBQi+FOU0pLjIyLipONoceND1FiPiY0SGRwYOGAgEAOw==) [Reddit](https://www.reddit.com/r/LAToken/)

You can also contact us by email: [contact@latoken.com](mailto:contact@latoken.com)

## LAToken Executive Summary

The Liquid Asset Token (LAT) platform offers anyone the potential to unlock the value of illiquid assets ranging from real estate and banks loans to works of art. Through the creation of digital tokens, any asset can be bought, sold, or traded in fractional shares on a secondary market, enabling asset owners to more effectively leverage the value of their previously illiquid holdings. Real estate assets, for example, are estimated to be worth $217 trillion worldwide, with liquidity barriers existing in every market. 

"The secondary and the primary markets of fractional ownership of home equity and mortgages are now on the verge of a breakthrough, thanks to cryptocurrency blockchain smart contracts" - says David Drake, chair of LDJ Real Estate Fund and member of advisory board of LAT. 

The LAT platform gives asset owners a new way to gain liquidity by making fractional asset ownership possible and tradable with minimal transaction costs. 

Asset owners can quickly get cash by issuing Liquid Asset Tokensand selling them via the LAT marketplace, while simultaneously keeping the actual asset for their use instead of borrowing money and paying interest.

Investors can buy fractional shares of assets via LAT, can manage a more diversified and risk-balanced portfolio with in-depth asset data stored on a blockchain.
"LAT unlocks the value of assets by transforming the way money flows between asset owners, borrowers, banks and investors. With the LAT blockchain, assets records are traceable, transactions are registered, and ownership is verifiable. The net result is that previously illiquid assets are now tradable without the expensive and cumbersome securitization processes needed to protect investors. Access to capital for banks, borrowers and asset owners occurs at dramatically lower cost." - said Valentin Preobrazhenskiy, CEO of LAT.

The platform is based on an existing home equity marketplace, founded by the CEO of LAT, that has facilitated 12,000 mortgage offers and more than 1000 deals from 7 banks and 25 investors in the past six months.

The LAT platform currently includes both a Wallet for purchasing and management of asset tokens transactions and a TestNet.

Creating a fractional asset in the Test Net is straightforward. Asset owners create an Asset Token, purchase Proof-of-Asset service, and list the token at LAT marketplace. In addition, an Asset Token issuer can buy insurance or other instruments to make the token more attractive to investors.

Investors can trade and manage assets portfolios via the LAT investment terminal. The terminal provides trading functions, access to credible assets data stored on blockchain and asset portfolio analytics tools.

A LAT token will be needed to buy asset tokens created on the platform and to pay fees for the creation of asset tokens and transactions with them.
