---
permalink: /what-is-a-metamorph/index.html
layout: post
title: What is a Metamorph? 
published: true 
categories: [metamorph emberjs]
---
I've seen this error a number of times:

`Cannot perform operations on a Metamorph that is not in the DOM`

... and I'll admit, I've not known exactly what a Metamorph is but 
for the most part, I can usually remember whatever it was that I just did that
caused the error, undo, and find a different way. 

Today, the thought crossed my mind: "What *is* a Metamorph?" and that's
when I went digging.  

I knew from having seen the "metamorph-#-start/end" references in 
script tags that it was part of the magic that makes Ember.js
bindings work, but I didn't know exactly where it came from.

Suprisingly, I couldn't find any search results
answering the question.  It was only after digging through 
some stackoverflow answers that my curiosity was satisfied 
when I found [this](https://github.com/tomhuda/metamorph.js/).
