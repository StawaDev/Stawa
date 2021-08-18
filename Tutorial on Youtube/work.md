# BDFD - How to make work commands like Dank Meme

## Apply Job

```
$nomention
$setUserVar[workname;Developer;$authorID]
$setUserVar[requirework;$sum[$getUserVar[requirework];1]]
Now you work as Developer
```

## Work Command

```
$nomention
$onlyIf[$getUserVar[requirework]>0;You don't apply a job, please apply `+work list`]

$title[You work as $getUserVar[workname]]
$description[You got $$random[10;20]]
$color[11FF00]
$setUserVar[money;$sum[$getUserVar[money];$random[10;20]]]
```


## Confused? Please Go Watch This Video
[![Youtube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=PDIpsCm_mng&t=4s)
