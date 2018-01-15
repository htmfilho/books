---
layout: post
title: "Functional Thinking"
author: Neal Ford
date: 2018-01-07 12:00:00 +0200
categories: functional programming book
---

Neal is really good at explaining functional concepts, but I think he exagerated
exploring 4 programming languages in just 157 pages. The book's cover uses the 
expression "Paradigm over syntax" to sustain the thesis that learning a new
programming language is easy, but learning a new paradigm is difficult. But Neal 
spent more time explaining the syntax of those languages than the paradigm 
itself. Their differences are so acentuated that I felt easier to learn the 
functional concepts than all the syntax differences to implement them among all 
those languages. In my opinion, programming languages are difficult by nature,
otherwise I would learn [Haskell] in no time, with all the functional concepts I 
already know, but it doesn't seen to help. We take years to master a programming
language as well as its ecosystem.

I think the book would be more effective if it consistently followed the 
pattern:

1. explore a problem in an imperative way;
2. refactor it to a hibrid solution, still imperative but using functional 
   tools (optional); and
3. refactor to a pure functional solution;

but I don't know if the author found some problem to follow it because he did
like that at the beginning and than he changed his mind.

Anyway, I have learned a lot reading this book and I do recommend it for those
who are trying to become poliglot programmers, like myself. If you're a 
passionate Java programmer, be careful! This book will motivate you to move
forward and learn other languages because you will feel stuck with Java and 
whatever action you take to make it look more functional will result in more 
verbose code. High-order functions, streams, lazyness are a good start, but not
enough.

I was happy to see Clojure in the book, mainly used to illustrate the purely 
functional solution and how elegant it is to follow the functional paradigm in
comparison to the other multi-functional languages.

[Haskell]: https://www.haskell.org