

## Important

**FocalPoint is no longer actively developed or updated. At the current time, Focalpoint is fully functional and compatible with Joomla 3.7.5. I will still provide full support for any users with an active subscription purchased from the Focalpointx.com website. Please send email to me at the address on your subscription confirmation and I'll respond as quick as possible.**

**Developing and maintaining FocalPoint over the past 3 years has been a blast. I have learned a lot from this experience. It has been inspiring seeing the many creative implementations people have built using a tool I created. I thank all of you.**

**Moving forward, FocalPoint consumes too much time which isn't covered by the subscription fees. My regular business and my sanity have suffered for it. It's been a tough decision but the FocalPointx.com site has been deleted.**

**Kind Regards,
John Pitchers
13 September, 2017**

---
# Focalpoint

## Advanced mapping extension for Joomla CMS

This is the repo for the FocalPoint mapping extension for Joomla. It is compatible with all version of Joomla 3.x. 

Use this extension to create advanced map based directories with custom legends, markers, infoboxes and hundreds of locations. Define the content for each location using CCK functionality. And, give your users the ability to search and filter using familiar UI elements.

**Installation Instructions** 
1. Download the latest zipped installation archive from this Github repo or from [focalpointx.com](http://focalpointx.com/). 
2. Install the component via the Joomla extension manager. No need to unzip the archive.
3. Follow the on screen wizard to set up your first map.

These extensions are available to subscribers. Subscribers also receive support and a money back guarantee.

**License**
The license under which the FocalPoint extension for Joomla! is released is the General Public License Version 2 (GPL v2) from the Free Software Foundation. A copy of the license is included with every download. You can also view the license online. Please see http://www.gnu.org/licenses/gpl-faq.html for more information on the GPL license.

Under the terms of this license you are free to use the software in any way you wish. You are free to modify the software in any way you wish and create derivative works.


#### Current Build 1.2.7
Fixes unclosed ul tags when sidebars are placed at the top or bottom of the map.


#### Build 1.2.6

Adds language entry for "Find out more".
Fixes issue with the Geocoder Tool not loading on the maps page in the administrator over https.
Fixes spelling error "Suburn or Postal code" as default search text.


#### Build 1.2.5

Fixes a bug where unpublished and trashed location types and legends would still be displayed.
Adds maximum zoom to global configuration and map configuration options.
Fixes a bug where a quotation mark in a location title would break the front end javascript.


#### Build 1.2.4

Change to focalpoint.xml enables a field for KML file storage for a new plugin in the works.


#### Build 1.2.3

Allows the Google Maps API to load over https.
Fixes an issue where custom fields can be defined without a name.
Fixes issues where notices and warnings were being generated when custom field details were changed and conflicted with previously saved location data.


#### Build 1.2.2

Change to the administrator's location form so the description field reads filters as per the Global Configuration settings.


#### Build 1.2.1

Minor fix to default map template 


#### Build: 1.2

Started as a bug fix release but grew to include new features.
Added the option to display the map or list view in the first tab. It's in the global configuration and can be overridden in the map settings.
Fix language issues. All english text hard coded in the template files has been replaced with language declarations and can be overridden with language files in the normal way.
Custom field options now include Select Boxes and Multi Select Boxes.
Better, more refined icon pins and cluster icons.
The infobox "Find out more" link can now link to a menu item.
Removed the ability to change the name of a custom field once it has been saved. This was causing issues with data being lost when the custom field name was altered.
Fixed missing div in sidebar sub-template.
Custom fields are now accessible in the map view. Previously they were only available in the locations view. A note has been added to the default template files.
Custom field values can now be displayed in location descriptions and infoboxes by wrapping the custom field name in curly brakets. ie {your-custom-field}. This will be extended in 1.3 with the ability to define an infobox template.


#### Build: 1.1

Added support for plugins and modules. Main component will be free with additional functionality provided by the way of commercial plugins.


#### Build: 1.0.2

Fixed minor layout issue with Get Directions form with some templates.
Added custom image layout template to front end view.
Fixed layout issue with custom image field in admin location view.
Fixed issue caused by conflict with custom textareas and new class in Joomla3.3 validation.js
Fixed issue with popup staying on screen after a map tab has been deleted.
Added missing language file definitions
Fixed drop down filter fields on location and map views showing duplicate "-- Select --" in first 2 rows.
Added icons to titles in all admin views.


#### Build: 1.0.1
Fixed minor bugs and language file omissions.


#### Build: 1.0

Soon to be published and offered for sale. http://joomlamaps.com. Development started on J2.5 in May 2013. Migrated to J3.2 March 2014.


#### Build 1.0

Stable version for first release. Contains a lot of bug fixes and layout tweaks.


#### Build: 0.9.2 beta

Added modal geocoding tool to location pages. Lots of tweaks and bug fixes. New layout on location page and 'back to map' button added.


#### Build: 0.9.1 beta

A mountain of tweaks and bug fixes to both the backend and frontend. Also added a modal geocoding tool to the map page. Will consider the same tool for the location page so users can finetune the placement of the pin on the map.


#### Build: 0.9 beta

This build adds a getting started walk through on installation. Few bug fixes and tweaks.


#### Build: 0.8.2 beta

This build adds 'Get Directions' to the location view and options to load bootstrap if it's not present. Also cleaned up much of the front end code.


#### Build: 0.8.1 beta

This build fixes a few issues and bugs and adds some small layout changes to the backend. Finally the Javascript to search,filter and display a list view seems completely stable.


#### Build: 0.8 beta
This build adds;

**Location List View**
Fully functional list view that works with the new search feature and legend toggles. Can be disabled/enabled via the admin.

**Suburb/Postcode Search**
Ajax Map Search uses Googles Geocoding API to find and zoom the map to the desired location. Shows/hides locations based on distances from the search result. The distance and map zoom level is configurable via the admin. Search can be disabled via the admin.


----------------
**Disclaimer**
Joomla! is the trademark of Open Source Matters, Inc in the United States and other countries. The Joomla! name is used under a limited license granted by Open Source Matters. Viperfish Media Pty LTD is not affiliated with or endorsed by Open Source Matters or the Joomla! Project.

