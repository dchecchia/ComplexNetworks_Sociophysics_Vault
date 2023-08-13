#Utility
# VM Project
```dataview
TABLE
file.mtime as "Last Modified"
FROM #VM
WHERE file.mtime >= date(today) - dur(1 day)
SORT file.mtime DESC
```

# LCD Project
```dataview
TABLE
file.mtime as "Last Modified"
FROM #LCD
WHERE file.mtime >= date(today) - dur(1 day)
SORT file.mtime DESC
```

# ADM Project
```dataview
TABLE
file.mtime as "Last Modified"
FROM #ADM
WHERE file.mtime >= date(today) - dur(1 day)
SORT file.mtime DESC
```
