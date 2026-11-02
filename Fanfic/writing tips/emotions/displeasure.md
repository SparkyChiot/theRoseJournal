```dataview
LIST
WHERE filter(file.tags, (t) => replace(t, "#", "") = this.file.name)
```
#emotion