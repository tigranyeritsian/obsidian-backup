---
tags:
  - type/moc
created: <% tp.file.creation_date() %>
---
# MOC: <% tp.file.title %>

## Overview
Brief description of this knowledge domain.

## Core Themes
- [[Theme 1 MOC]]
- [[Theme 2 MOC]]

## Key Zettels (Dataview)
```dataview
TABLE status as Status, file.mtime as "Modified"
FROM #zettel AND #
SORT file.mtime DESC
LIMIT 20