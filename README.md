## Frontend Nanodegree Feedreader

This project reads and displays RSS feeds from different sources. The aim of this project is to make Javascript Unit Tests using [Jasmine](http://jasmine.github.io/).

### How To Run The Application

Just [download](https://github.com/jrarama/frontend-nanodegree-feedreader/archive/master.zip) the project, extract it and open the index.html in your favorite modern browser.

### Tests Performed

Items in bold text are tests added by the developer which is not initially required.

 * test if `allFeeds` variable is defined
 * **test if `allFeeds` variable is an array**
 * test if all `allFeeds` items has non-empty `url` property
 * test if all `allFeeds` items has non-empty `name` property
 * test if the menu is hidden by default
 * test if the menu changes visibility when menu icon is clicked
 * test if the `.feed` container contains at least a single .entry element after loadFeed function is called
 * test if the `.feed` container's content actually changes when new feed is loaded