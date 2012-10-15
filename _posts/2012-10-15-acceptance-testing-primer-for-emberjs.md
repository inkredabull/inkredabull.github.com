---
permalink: /acceptance-testing-primer-for-emberjs/index.html
layout: post
title: Acceptance Testing Primer for Emberjs 
published: true 
categories: [emberjs acceptance testing selenium]
---
__tl;dr : Capybara with phantomjs is the fastest solution around__

Years ago, I loved [Selenium](http://seleniumhq.org/) for everything it
made possible, particularly for the [Firefox plugin](https://addons.mozilla.org/en-US/firefox/addon/selenium-ide/)
that made it so easy to script-record a user acceptance test and dump it
for automation.  

Over the years, I have done my fair share of futzing around with Selenium, and when I
took a look at [Lebowski](https://github.com/FrozenCanuck/Lebowski) a
few months ago, I thought I had found a silver bullet.  It's really 
a clean solution for managing everything around acceptance
testing, that is, if you're going to use Selenium.

Today, my solution of choice is
[Capybara](https://github.com/jnicklas/capybara) with
[PhantomJS](http://phantomjs.org/)/[poltergeist](https://github.com/jonleighton/poltergeist)

So far, Capybara's DSL is so clean and robust for programmatically defining any
user action I've come up with. I don't have any benchmarks to share at
this time for vanilla-Capybara tests vs. Capybara w/headless JS
(poltergeist) but suffice it to say, I spend noticably less time at the
command line.

More to come on how to (acceptance) test your Ember.js apps using
Capybara/poltergeist.
