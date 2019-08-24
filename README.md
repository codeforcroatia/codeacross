# [Open Data Day Croatia](http://odd.codeforcroatia.org/)

A Jekyll-flavored version of the meetup site, hosted by GitHub pages.

Since this site doesn't have a database, RSVPs are simply links to external site. Have fun GitHubbing! :octocat:

## Creating/Editing a Meetup

Just head over to [prose.io](https://prose.io/#codeforcroatia/opendataday/tree/gh-pages) and start a new post. Naming conventions will automatically be handled for you, but it is important that you fill out the metadata by clicking the content icon on the right. It should generate something like this:

````
---
layout: "meetup"
categories: "meetup"
title: "Google IO Extended"
date: "2014-06-25 11:00:00"
permalink: "/io-extended-2014/" <!-- optional -->
identifier: "unique-id-per-content-for-all-languages"
lang: en
host: "Jon Moss"
address: "Suite 404, 90 John Street, NYC"
link: "https://www.facebook.com/events/294642260712985/"
background: "url(http://i.imgur.com/U9bGouP.jpg)"
---
````

## Todo

- [ ] Mentorship content type
- [x] Blog content type
- [ ] Set up Jenkins CI
- [ ] Enable GitHub pages plugins
- [ ] Test run #43 @world-domination/time-travel
- [x] Translation function (see [dwalkr/jekyll-multilingual](https://github.com/dwalkr/jekyll-multilingual))

## Upgrading

Copy over everything except /_posts, and _config.yml.

## Thanks

Thanks to [HS Hackers](http://nyc.hshackers.org/) who created original version on which is this site based.