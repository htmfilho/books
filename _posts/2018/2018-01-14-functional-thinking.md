---
layout: post
title: "Functional Thinking"
author: Neal Ford
date: 2018-01-07 12:00:00 +0200
categories: functional programming book
link: https://www.amazon.com/gp/product/1449365515/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=1449365515&linkCode=as2&tag=c03ce-20&linkId=ebebe602d6240e6b33784bb2de8a06e4
image: //ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&MarketPlace=US&ASIN=1449365515&ServiceVersion=20070822&ID=AsinImage&WS=1&Format=_SL250_&tag=c03ce-20
another_image: //ir-na.amazon-adsystem.com/e/ir?t=c03ce-20&l=am2&o=1&a=1449365515
---

Neal is really good at explaining functional concepts, but I think he exagerated exploring 4 programming languages in just 157 pages. The book's cover uses the expression "Paradigm over syntax" to sustain the thesis that learning a new programming language is easy, but learning a new paradigm is difficult. I have the impression Neal spent more time explaining the syntax of those languages than the paradigm itself. Their differences are so acentuated that I felt easier to learn the functional concepts than all the syntax differences to implement them among all those languages. In my opinion, programming languages are difficult by nature, otherwise I would learn [Haskell] in no time, with all the functional concepts I already know, but it doesn't seen to help. According to Peter Norvig, we may [take years to master a programming language as well as its ecosystem][peter-norvig].

I think the book would be more effective if it consistently followed the pattern:

1. explore a problem in an imperative way
2. refactor it to a hibrid solution, still imperative but using functional tools (optional)
3. refactor to a pure functional solution

Actually, the author followed this pattern at the beginning, but I don't know why he didn't continue like that.

Anyway, I have learned a lot reading this book and I do recommend it for those who are trying to become poliglot programmers, like myself. If you're a passionate Java programmer, be careful! This book will motivate you to move forward and learn other languages because you will feel stuck with Java. Whatever action you take to make it look more functional will result in more verbose code (e.g. declare every final). High-order functions, streams, lazyness are a good start, but not enough.

I was happy to see Clojure in the book, mainly used to illustrate the purely functional solution and how elegant it is to follow the functional paradigm in comparison to the other multi-functional languages.

Neal's new book, "<a target="_blank" href="https://www.amazon.com/gp/product/1491986360/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=1491986360&linkCode=as2&tag=c03ce-20&linkId=3cb8f263e1d0f22220d0b37acaa92ad1">Building Evolutionary Architectures: Support Constant Change</a><img src="//ir-na.amazon-adsystem.com/e/ir?t=c03ce-20&l=am2&o=1&a=1491986360" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />", is already in my the backlog.

[Haskell]: https://www.haskell.org
[peter-norvig]: https://www.norvig.com/21-days.html