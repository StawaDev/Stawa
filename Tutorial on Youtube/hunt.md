# BDFD - How to make Hunt commands like Dank Meme

## Hunt Command
```
$nomention
$username's just hunt $randomText[Nothing;Rabbit;Bird]
$setVar[$randomText[Nothing;Rabbit;Bird];$sum[1];$authorID]
```

## Inventory

```
$nomention
$thumbnail[$userAvatar[$authorID]]
$title[$username's Inventory]
$description[
Bird: $getVar[Bird;$authorID]
Rabbit: $getVar[Rabbit;$authorID]
]
$color[ffffff]
```
