Welcome to the pygbag packages (actually wheel format) repository list.

README.md should be in  /wiki/pkg/`<import name>`/README.md , not the pypi project name.
  
It should have a short example whenever possible and covers those points :  
- the case when a loop must be async-ified
- files have been modified, explain why
- files added, what are they for ?
- files removed ( explain why , maybe size / irrelevant ... )
- missing/extra functionnalitites list details
- what does it bring that pygame cannot do, or cannot do in an easy way.
- ideally point to a PR from a pygbag branch toward main branch. [example](https://github.com/pmp-p/nurses_2-wasm/pull/1/files)

The actual wheels are located here :

[https://github.com/pygame-web/archives/tree/main/repo/pkg/](https://github.com/pygame-web/archives/tree/main/repo/pkg/)

They are downloaded on code evaluation, from executing your main.py modules based on raised import errors.
so put your imports at the top, and possibly order them to limit looping over import errors.


[edit this page](https://github.com/pygame-web/pygame-web.github.io/edit/main/wiki/pkg/README.md)