```dataview 
LIST file.ctime
```

```dataview 
LIST FROM "1️ Primary Sources" where rating < "5/5"
```

```dataview
LIST
FROM "Activity"
```

```dataview
TABLE workout
FROM "2 Collections"
SORT file.ctime DESC
LIMIT 14
```

```dataview
TASK
WHERE !completed
LIMIT 10
GROUP BY file.link
SORT rows.file.ctime ASC
```

```dataview
CALENDAR file.mtime
FROM ""
```