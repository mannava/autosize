## Changelog

##### v.3.0.3 - 2015-04-23
* Avoided adjusting the height for hidden textarea elements.  Fixes #155.

##### v.3.0.2 - 2015-04-23
* Reworked to respect max-height of any unit-type.  Fixes #191.

##### v.3.0.1 - 2015-04-23
* Fixed the destroy event so that it removes it's own event handler. Fixes #218.

##### v.3.0.0 - 2015-04-15
* Added new methods for updating and destroying:

	* autosize.update(elements)
	* autosize.destroy(elements)

* Renamed custom events as to not use jQuery's custom events namespace:

	* autosize.resized renamed to autosize:resized
	* autosize.update renamed to autosize:update
	* autosize.destroy renamed to autosize:destroy

##### v.2.0.1 - 2015-04-15
* Version bump for NPM publishing purposes

##### v.2.0.0 - 2015-02-25

* Smaller, simplier code-base
* New API.  Example usage: `autosize(document.querySelectorAll(textarea));`
* Dropped jQuery dependency
* Dropped IE7-IE8 support
* Dropped optional parameters
* Closes #98, closes #106, closes #123, fixes #129, fixes #132, fixes #139, closes #140, closes #166, closes #168, closes #192, closes #193, closes #197