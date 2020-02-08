# gitmoji-commit-graphs
> Generate a distribution graph of different commit types for repositories following the gitmoji standard. 

Tested on WSL (Ubuntu 18.04) and Windows 10. The last step (opening the graph) will not work on linux, but the fix is trivial.

Here's the graph of this repository (at commit `544eb3f1f4e02850c2e175ca6f7ae5a27eac0792`)

```bash
$ commit-types-distribution -o example.png
```

![](./example.png)

