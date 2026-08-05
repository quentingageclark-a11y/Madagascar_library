---
title: "Madagascar Papers"
order: 0
chapter: 1
section: 0
layout: "md.jlmd"
tags: ["module1", "track_julia"]
---

# Madagascar Papers

This module holds the Madagascar code papers ported into Julia as Pluto notebooks.

To add a new paper, drop a `.jl` Pluto notebook into `src/module1_papers/`. Give it frontmatter like this:

```julia
#> [frontmatter]
#> chapter = 1
#> section = 2
#> order = 2
#> title = "Title of the paper"
#> tags = ["module1", "track_julia"]
#> layout = "layout.jlhtml"
```

It will automatically show up in the sidebar under this module.
