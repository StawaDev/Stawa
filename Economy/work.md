## Global Work with Global Balance (Every server amount will be the same amount)

```
$setVar[money;$sum[$getVar[money;
$authorID];$random[5;20]];$authorID]
```

## Local Work with Local Balance

```
$setUserVar[money;$sum[$getUserVar[money;
$authorID];$random[5;20]];$authorID]
```
## Variable Required
- Variable Name: money
- Variable Value: 0

## Quick notes:

- You can change money variable to whatever you want.
- Global Balance means everyserver will be show with the same amounts and Local Balance means everysingle server will be show different amounts

## Next Step
https://github.com/StawaDev/Stawa/blob/main/Economy/balance.md
