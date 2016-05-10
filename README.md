# Jasmine: Feed Reader Testing

This project utilises Red-Green-Refactor development for a web-based application that reads RSS feeds. 

## Tests

The following tests were made using the [Jasmine](http://jasmine.github.io/) JS library.

* RSS Feeds
	* are defined
	* URLs defined and not empty
	* names defined and not empty

* The menu
	* hidden by default
	* changes visibility when the menu icon is clicked

* Initial entries
	* when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container

* New Feed Selection
	* when a new feed is loaded by the loadFeed function, the content actually changes

## How to run the tests

The Jasmine console is embedded into index.html. Simply run this file in any modern browser and scroll to the bottom to see the test results.
