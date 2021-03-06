##2017-02-27
#####CHANGED:
* updated angular-cli to 1.0.0-rc.0
* fixed max available date in epic component
* misc refactors


##2017-02-21
#####ADDED:
* apod info dialog component
* apod page: view info button functionality (opens a dialog with apod explanation)

#####CHANGED:
* epic page: interval slide and interval are showing data in ms instead of seconds
* renamed epic/apod .component to epic/apod -page.component
* apod page: youtube vids are now correctly displayed in the main apod
* styles for .mat-spinner

#####REMOVED:
* rovers link and route
* footer links, leaving only two



##2017-02-17
#####ADDED:
* epic page: autoplay option (for changing images in card)
* epic page: swipe event on image (swipe to change image)
* epic page: epics thumbnails with events
* epic page: autoplay speed slider
* apod page: spinner while apod image is not fully loaded

#####CHANGED:
* epic page: epic card styles
* epic page: fixed image changing on date change (earlier date was changing, but image was frozen)



##2017-02-16
#####CHANGED:
* apod component: fixed error when navigating from /apod to home
(unsubscribing null error)
* apod component: sorted apods by date
* updated material2 to beta.2
* updated home page (**still needs work tho**)
* updated pollyfills
* some global styles

#####ADDED:
* nasa service: get daily epics
* epic page: datepicker (**still needs work tho**)
* gifshot npm package
* _gifService (for creating gif from epic images later on)_



##2017-02-14
#####ADDED:
* angular/material2 npm package
* angular/flex-layout npm package
* nasa service: getting monthly apods

#####CHANGED:
* APOD page (updated with material2)
* APOD page (added option to view older apods)
* navbar (updated with material2)
* footer (updated with material2)
* some global styles

#####REMOVED:
* normalize.css
* ng2 material datepicker



##2017-02-11
#####ADDED:
* homepage
* nasa service (for API calls)
* navbar
* footer
* Astronomy Picture of the Day
* some global styles
* font awesome
* momentjs
* normalize.css
* ng2 material datepicker
* web-animations-js
