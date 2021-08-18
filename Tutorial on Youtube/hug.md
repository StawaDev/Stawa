# BDFD - How to make hugs commands like Yui

## Hug Command #1
```
$nomention
$title[**$username** hugs **$username[$mentioned[1;yes]]**]
$image[$randomText[https://c.tenor.com/WMJBDcjhvU4AAAAC/anime-hug.gif; https://1.bp.blogspot.com/-JUqgHJmjyDs/YG76cI82URI/AAAAAAAAD_w/0QtzGkpiel0OlTVEdRCDLmK5Ot46rEq8QCLcBGAsYHQ/s300/romantic%2Banime%2Bhug%2Bgif1.gif]]
$color[fffff]
$footer[That's $getUserVar[hugcount;$authorID] hugs now!]
$setUserVar[hugcount;$sum[$getUserVar[hugcount];1]]
```

## Hug Command #2
```
$nomention
$onlyIf[$getUserVar[hugcount;$authorID]>1;**Level UP!** You've reach **Level 1** for hugs with $username[$mentioned[1;yes]]'s]
$setUserVar[lvlhug;$sum[$getUserVar[lvlhug;$authorID];1];$authorID]
$setVar[once;claimed;$authorID]
$onlyIf[$getVar[once;$authorID]!=claimed;]
```

## Variable Required
- Variable Name: once
- Variable Value: 

- Variable Name: hugcount
- Variable Value: 1

- Variable Name: huglvl
- Variable Value: 0

## Confused? Please Go Watch This Video
[![Youtube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCzmk62UFOAcHxWshM1LNgFw)
