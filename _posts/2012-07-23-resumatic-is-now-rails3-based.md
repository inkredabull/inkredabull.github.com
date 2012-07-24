---
permalink: /resumatic-is-now-rails3-based/index.html
layout: post
title: Resumatic is now Rails3-based 
published: true 
categories: [rails3]
---
I finally brought [Resumatic](https://github.com/inkredabull/resumatic) into the 21st century; it's now a Rails 3.2.0 app. 

While I originally intended to go [step-by-step](http://railscasts.com/episodes/225-upgrading-to-rails-3-part-1), 
whereby I was going to wrap the app with some regression tests, upgrade, run the tests to prove I didn't (or did) break 
something, and then be happy, I soon tired of that given the many dependencies (RSpec, rvm, Rails, etc.)

Given the size of the app, I just decided to get a fresh gemset, install Rails 3.2.0, create a new container 
project via 'new', and then copy all the necessary files from the Rails 2 version in to the Rails 3 container, tweaking
wherever new syntax was required.  

Someday I'll add tests...
