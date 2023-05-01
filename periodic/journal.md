---
creation-date: <% tp.file.creation_date("YYYY-MM-DD") %>
tags: periodic/journal
---
last-modified: `$= dv.current().file.mtime`
- prev:: [[j-<% tp.date.yesterday() %>]]
- wr:: [[w-<% tp.date.now("YYYY-MM") %>-W<% tp.date.now("ww") %>]]
# j-<% tp.date.now("YYYY-MM-DD") %>
```todoist
{
"name": "Todoist tasks",
"filter": " <% tp.date.now() %> | overdue "
}
```
## Daily Habit Building:
- [ ] exercise in the mornings
- [ ] value checkin
## 📖 Reading:
## 📜 Tasks: <% tp.file.cursor() %>
## Main thing: 
## HELLO 🪁✨ {{time}}