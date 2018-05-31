# Feed Reader Testing

## Table of Contents

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Feed Reader Testing](#feed-reader-testing)
	- [Table of Contents](#table-of-contents)
	- [How to get it](#how-to-get-it)
	- [How it is working](#how-it-is-working)
		- [Required dependencies](#required-dependencies)

<!-- /TOC -->

## How to get it

You can reach it: https://schwaott.github.io/frontend-nanodegree-feedreader/.

## How it is working

The test results appear at the bottom of the page. Tests that are greens have passed, red ones have failed.

Test to make sure that the allFeeds variable has been defined and that it is not empty.
Test loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
Test loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
Test ensures the menu element is hidden by default.
Test ensures the menu changes visibility when the menu icon is clicked.
Test ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
Test ensures when a new feed is loaded by the loadFeed function that the content actually changes.

### Required dependencies

Use the latest version of your browser.
