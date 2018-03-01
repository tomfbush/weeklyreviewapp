# Weekly Review Checklist app

## Introduction

This is a very basic "app" (web page) that just loads up a Bootstrapped predefined list of weekly actions that need to be completed. I use this locally so there's no issue with the fact that the state of each item doesn't persist. Should be easy enough for someone to adapt, the code is possibly nasty, it was just a quick hour hack to see if I could get my head round a few bits of AngularJS.

There is a demo at http://www.tombush.co.uk/weekly-review-app/ if you want to take a look... have, er, fun? ;-)

## Todo

  * Use ``https://favqs.com/api/qotd`` to get some quotes in there
  * Use $http service in ng to get the quotes, learning from https://www.sitepoint.com/api-calls-angularjs-http-service/
  * Add Discus to this? Or some other kind of commenting system... or is it going straight into Wordpress? Might be nice to have the reaction

## Roadmap

### 0.1 (wishy-washy)

  * basic functionality to allow ticking of pre-defined boxes
  * progress bar that calculates % of items ticked

### 0.2 [PLANNED]

  * progress bar to detach and scroll with screen
  * move completed items to bottom of list
