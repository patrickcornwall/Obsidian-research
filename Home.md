```dataview
LIST
SORT file.mtime DESC
LIMIT 10
```

```dataview
TASK
WHERE !completed
SORT file.mtime DESC
```