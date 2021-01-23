---
title: Blog-post-cheatsheet
author: sagrudd
date: '2021-01-23'
slug: []
categories: []
tags: []
---

It is now two weeks since the last post - not a good start to the plan to be a
little more active with social updates, progress reports and thoughts.

Here is a brief reminder (for the author alone) of the process for creating a
blog post. 

- The first task is to use the `Addins` dialog in RStudio to create a new post. 

![](images/Screen Shot 2021-01-23 at 4.43.02 pm.png)

We the hack at the `Rmd` (or `md`) template for a bit, share words of wisdom and
thoughts. Proof-read, commit and push. Then finally - using a `Terminal` tab
or window just run the script

```
# pull, prepare, commit and push
sh ./scripts/deploy.sh
```

Should be as simple as that...