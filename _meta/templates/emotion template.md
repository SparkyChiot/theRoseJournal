## Body Language
```dataview
LIST
FROM #bodylanguage
WHERE filter(file.tags, (t) => replace(t, "#", "") = this.file.name)
```

## What to use instead of "said"
```dataview
LIST
FROM #bodylanguage
WHERE filter(file.tags, (t) => replace(t, "#", "") = this.file.name)
```

#emotion
