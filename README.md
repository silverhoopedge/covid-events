# covid-events
Use this code snippet to change title for postponed or cancelled or virtual published events
## Tested in an enviroment that is using:
* The Events Calendar plugin 
* WP 5.3.2
* PHP version 7+
## Not yet tested for 
* recurring series of published events (i.e. available with pro version of The Events Calendar plugin)
* published events with many tags already in use
* Tip: you might need to clear cache so the revised title is displayed
## Suggested procedure
### Create 3 tags in WordPress Administration (WP-Admin) dashboard in Events section (lower case, exact spelling match)
* New tag: postponed
* New tag: cancelled
* New tag: virtual
### Edit Published Events to add the proper tag (cancelled or postponed or virtual)
* Can edit each indivdual published event
* Can use quick edit
* Can use bulk actions
* Use one tag per published event (cancelled -OR- postponed)
