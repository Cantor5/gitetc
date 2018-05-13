Comments in Markdown
====================

The most platform-independent syntax is

```
(empty line)
[comment]: # (This actually is the most platform independent comment)
```

Both conditions are important:

1. Using # (and not <>)
2. With an empty line before the comment. Empty line after the comment has no impact on the result.

The strict Markdown specification CommonMark only works as intended with this syntax (and not with <> and/or an empty line)
