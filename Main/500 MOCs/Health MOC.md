---
tags:
  - type/moc
  - "#health"
created: 2025-11-10 21:11
---
# MOC: Health MOC

## Overview
Overall health MOC.

## Core Themes
- [[Diet MOC]]

## Key Zettels (Dataview)
```dataview
TABLE status as Status, file.mtime as "Modified"
FROM #health
WHERE file.name != "Health MOC"
WHERE file.name != "Diet MOC"
SORT file.mtime DESC
LIMIT 20
```

