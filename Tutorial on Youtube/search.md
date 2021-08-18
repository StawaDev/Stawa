# BDFD - How to make Search Commands Dank Meme

## Search Command
```
$nomention
$setUserVar[search;online]
You only have 3 choice, please choose it!

$randomText[`Home,`;`Bank,`;`Wallet,`], $randomText[`House,`;`PayPal,` `Bed,`], $randomText[`Door.`;`Under Bed.`;`Chair.`]
```

## Bank

```
$nomention
$onlyIf[$getUserVar[search]==online;]
$setUserVar[search;off]
You get caught by police because you robbing a Bank
```

## Home

```
$nomention
$onlyIf[$getUserVar[search]==online;]
$setUserVar[search;off]
Nice, you get in your neighbor home!
```

Quick Notes:
- You can add some rewards to Bank and Home!

## Confused? Please Go Watch This Video
[![Youtube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=wrZxctulIyU&t=189s)
