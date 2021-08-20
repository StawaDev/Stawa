# BDFD - How to make Profile commands like Dank Meme

## Profile commands
```
$nomention
$title[Profile]
$thumbnail[$userAvatar[$authorID]]
$description[
Select One!
]
$color[ffff]
$newSelectMenu[testo;1;1;Other views...]
$addSelectMenuOption[testo;Currency;Currency;Your economy;no;]
$addSelectMenuOption[testo;Commands;Commands;Commands used;no;]
$addSelectMenuOption[testo;Profile;Profile;Profile info;no;]
```

## $onInteraction[profile]

```
$nomention

$if[$message==Currency]
$title[$username's Balance]
$thumbnail[$userAvatar[$authorID]]
$description[
money: $getUserVar[money;$authorID]
bank: $getUserVar[bank;$authorID]
]
$color[ffff]
$endif
$if[$message==Commands]
$color[11ff20]
$description[
hug: $getUserVar[hugcount]
work: $getUserVar[workcount]
daily: $getUserVar[dailycount]
]
$endif
$if[$message==Profile]
$title[Profile]
$thumbnail[$userAvatar[$authorID]]
$description[
Description profile...
]
$color[ffff]
$endif
```
