---
tags:
  - type/moc
created: 2025-11-09 21:14
---
# MOC: Goals MOC

```dataview
TABLE status as Status, file.mtime as "Modified"
FROM #type/goal
WHERE file.name != "Goal Template"
SORT file.mtime DESC
LIMIT 20
```
