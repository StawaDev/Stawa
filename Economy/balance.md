## Global Balance:

```
$title[$username's Balance]
$description[
Money: $getVar[money;$authorID]
]
```

## Local Balance:

```
$title[$username's Balance]
$description[
Money: $getUserVar[money;$authorID]
]
```

## Variable Required
- Variable Name: money
- Variable Value: 0

Quick notes:

- You can change money variable to whatever you want.
- Global Balance means everyserver will be show with the same amounts and Local Balance means everysingle server will be show different amounts
