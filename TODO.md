## A remplir

```dataview
TABLE tags as "Type", dateformat(file.mtime, "dd.MM.yyyy - HH:mm") as "Last Modified", dateformat(file.ctime, "dd.MM.yyyy - HH:mm") as Created FROM #todo SORT file.mtime DESC
```
