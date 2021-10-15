# BDFD - Buy Commands

```
$nomention
$onlyIf[$getUserVar[money;$authorID]>200;You don't have enough money to buy it!]
$setVar[money;$sub[$getUserVar[money;$authorID];200];$authorID]
$setVar[Laptop;$sum[$getUserVar[Laptop;$authorID];1];$authorID]
You just buy A Laptop for $200!
```

## Variable Required

- Variable Name: Laptop
- Variable Value: 0

## Confused? Please Go Watch This Video
[![Youtube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCzmk62UFOAcHxWshM1LNgFw)
