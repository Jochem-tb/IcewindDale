---
dg-home: true
dg-publish: true
dg-hide-in-graph: true
---
![[rotf_cover_art_banner.png]]
# Journal
**[[Chronicles]] | [[Quests]] |  [[Characters]] | [[Battles]] | [[XP]] | [[Loot]] | [Calendar](https://app.fantasy-calendar.com/calendars/38f9e3f5098bac1f655a4fb4241f35eb)**

```dataview
TABLE WITHOUT ID 
	file.link as "§",
	summary AS "Chronicle ([[Chronicles|see all]])" 
FROM "Journal" WHERE file.name != "Quests" AND file.name != "Battles" AND file.name != "XP" AND file.name != "Loot" AND file.name != "Characters" AND file.name != "Chronicles"
SORT file.name DESC
LIMIT 3
```



