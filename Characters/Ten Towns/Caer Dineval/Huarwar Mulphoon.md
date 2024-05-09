---
dg-publish: true
role: Gate Guard, Black Swords Cultist, Innkeeper's Son
age: Young
race: Human
gender: Man
descriptors: ["Strapping","Surly","Brave"]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
