## Git cherry-pick
---
>**Git cherry-pick** - применяет к древу проекта изменений, внесенных отдельным коммитом.

```
git cherry-pick BUG_FIX_TAG — изменения, внесенные указанным коммитом будут применены к дереву, автоматически проиндексированы и станут коммитом в активной ветке.

git cherry-pick BUG_FIX_TAG -n — ключ "-n" показывает, что изменения надо просто применить к дереву проекта без индексации и создания коммита.
```