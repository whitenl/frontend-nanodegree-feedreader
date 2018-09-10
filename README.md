# Project Overview

Front end nanodegree Udacity project. Wrote tests against an existing web-based RSS Feed Reader application. Used [Jasmine](http://jasmine.github.io/) for testing.


## The following tests were added:

1. A test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
2. A test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
3. A test that ensures the menu element is hidden by default.
4. A test that ensures the menu changes visibility when the menu icon is clicked. This test has two expectations: does the menu display when clicked and does it hide when clicked again.
5. A test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
6. A test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.


## How to run
Download [repository](https://github.com/whitenl/frontend-nanodegree-feedreader.git). Open file index.html in browser. Jasmine test results will be displayed at the bottom of the page.
