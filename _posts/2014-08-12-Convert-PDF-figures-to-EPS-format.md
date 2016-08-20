---
layout: post
cover: 'assets/images/cover7.jpg'
title: Convert PDF figures to EPS format
date:   2014-01-18 10:18:00
tags: LaTeX Publishing Data formats
subclass: 'post tag-test tag-content'
categories: 'caspee'
navigation: True
logo: 'assets/images/ghost.png'
disqus: true
author: Admin
---

In MacOS open the terminal and use `cd` command to go to the folder where the PDF figures are going to be converted to EPS. Then execute the following code:

```  for f in *.pdf; do pdftops -eps $f; done
```

For more information visit this thread on [ubuntuforums.org](https://ubuntuforums.org/showthread.php?t=1159624) website
