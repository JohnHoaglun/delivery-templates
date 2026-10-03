<%*
let timestamp = tp.date.now("YYYY-MM-DD HH-mm-ss")
let title = await tp.system.prompt("Optional note title")
let finalTitle = (title && title.trim() !== "") ? `${timestamp} ${title}` : timestamp
await tp.file.rename(finalTitle)
%>---
created: <% tp.date.now("YYYY-MM-DD HH:mm:ss") %>
brief description: ""
repo_location: ""
project_location: ""
tags: []
---

<!--
Attachments: images pasted into this file go in assets-private/ next to this note.
RESEARCH.md content (body and images) is always private -- never promoted, never
pushed to a repo. Not yet auto-enforced (no per-note attachment-routing plugin
wired up in the source Obsidian vault) -- place images in the correct folder by
hand until that lands.
-->


