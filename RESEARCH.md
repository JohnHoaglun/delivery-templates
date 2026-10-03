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

