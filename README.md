# angular-addtocalendar [![Build Status](https://travis-ci.org/jshor/angular-addtocalendar.png?branch=master)](https://travis-ci.org/jshor/angular-addtocalendar) [![Dependency Status](https://david-dm.org/jshor/angular-addtocalendar.svg?branch=master)](https://david-dm.org/jshor/angular-addtocalendar)
v0.0.4

An AngularJS directive for adding an event to calendar apps. It supports .ics files for iCalendar and Outlook and also supports Google Calendar, Yahoo! Calendar and Microsoft Calendar. It makes use of [ics.js](https://github.com/nwcell/ics.js) by Travis Krause.

Enjoy!

## Installation

    bower install angular-addtocalendar

## Demo

For a demo, please [click here](http://jshor.github.io/angular-addtocalendar/).

## Example

	<addtocalendar
 		start-date="20150704T190000"
 		end-date="20150704T210000"
 		title="Fourth of July Fireworks"
 		location="Battery Park City, New York, NY"
 		class-name="btn btn-sm btn-default dropdown-toggle"
 		description="Celebrate the independence of the United States with fireworks in one of the greatest cities in the world."
 	></addtocalendar>

## Attributes

| **Attribute** 	| **Description**                                                                                              	| **Format**                                                                   	| **Example**                                                                                                	| **Required** 	|
|---------------	|--------------------------------------------------------------------------------------------------------------	|------------------------------------------------------------------------------	|------------------------------------------------------------------------------------------------------------	|--------------	|
| `title`       	| Name of the event.                                                                                           	| Plain text                                                                   	| Fourth of July Fireworks                                                                                   	| Yes          	|
| `description` 	| Description of the event.                                                                                    	| Plain text. Default nil.                                                     	| Celebrate the independence of the United States with fireworks in one of the greatest cities in the world. 	| No           	|
| `location`    	| Location of the event.                                                                                       	| Plain text                                                                   	| Battery Park City, New York, NY                                                                            	| Yes          	|
| `start-date`  	| The timestamp of when the event begins.                                                                      	| Date string in format `YYYYMMDDToHHMMSS`                                     	| 20150704T190000                                                                                            	| Yes          	|
| `end-date`    	| The timestamp of when the event ends.                                                                        	| Date string in format `YYYYMMDDToHHMMSS`                                     	| 20150704T210000                                                                                            	| Yes          	|
| `class-name`  	| The bootstrap class for the dropdown button ([more info](http://getbootstrap.com/components/#btn-dropdowns)) 	| Bootstrap class/plain text. Default `btn btn-sm btn-default dropdown-toggle` 	| btn btn-sm btn-default dropdown-toggle                                                                     	| No           	|

## Bugs

Please report all bugs [here](https://github.com/jshor/angular-addtocalendar/issues).

## Changelog

Available [here](https://github.com/jshor/angular-addtocalendar/blob/master/CHANGELOG.md).
