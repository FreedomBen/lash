lash
====

(Note:  This product does not yet exist)

lash (lazy bash) is a very simple language that compiles into bash

`lash` is a superset of `bash` (meaning all valid `bash` is also valid `lash`) that allows you to lazily write `bash` without running into the common pitfalls and annoyances of `bash`.  It also adds alternate syntax for common `bash` patterns that makes things simpler.

`lash` compiles into pure `bash`, so you can distribute your script as `bash` without fear of a dependency on the `lash` compiler.

`lash` also offers some simple features like bash compression to reduce filesize (the compression eliminates whitespace by adding lots of semicolons and not importing the comments from `lash`)
