---
created: 2024-12-11T21:29
updated: 2024-12-12T15:07
tags:
  - person
aliases: 
associatedGroup: 
gender: 
race: 
age: 
class: 
location: 
condition: 
status: 
---

<%*
const hasTitle = !tp.file.title.startsWith("newNPC");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter NPC Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

> [!infobox]
> # `=this.file.name`
> ![[imagePlaceholder.webp]]
> ###### Basic Information
> Type |  Stat |
> ---|---|
> Location | `=this.Location` |
> Group | `=this.associatedGroup` |
> Gender | `=this.gender` |
> Race | `=this.race` |
> Age | `=this.age` |
> Condition | `=this.condition` |
> Status | `=this.status` |


## Profile

<% tp.file.cursor() %>

### Bio
Birth:
Death:
Belief:

### Description
##### Physical appearance

##### Personality traits

##### Personal history
##### Education
##### Employment

##### Accomplishment & Achievements

##### Failures & Embarrassments

##### Morality & Philosophy

##### Social
Parents:
Siblings:
Children: