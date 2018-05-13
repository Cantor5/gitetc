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
[see also][L1]

[L1]: https://stackoverflow.com/questions/4823468/comments-in-markdown?rq=1
