# This Site

This is my collection of elaborate notes on topics that interest me.
I'm a software engineer, and most of the topics you'll find here are related to development and technology.

It is worth noting that when I was thinking about how to write those notes, I decided that I wanted a way 
to display original code snippets, which comes from the repository, and not copy and paste from the text editor. 
The reason for this decision is because in most posts or articles that show source code, it is often not complete or has errors.
To achieve this goal, I have looked for existing solutions, blogging platforms,... but zero, silence, nothing,...
Then I went to the static site generators (sphinx, mkdocs,...), and again zero, silence, nada...

I wanted something like a PR with code reviews, which is real code that evolves over time and tells a story.

Maybe something like jupyter notebooks?... close, but no. But, as a side note regarding the jupyter notebooks,
I discovered something interesting: the concept of [Literate Programming](https://en.wikipedia.org/wiki/Literate_programming).
But this is for another day.

So I finally decided to take a middle route and use something simple and powerful like [mkdocs](https://www.mkdocs.org),
and write a custom plugin that basically allows me to show differences from different branches of a git repository. 

An example:

```Diff
 def hello(name: str) -> str:
-    return "hello" + name
+    return f"Hello {name}!"

print(hello("john"))
```

