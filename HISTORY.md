V2.3.2
==================
* exposed `--px-datetime-range-field-margin-between-fields-overwrite` css var

V2.3.1
==================
* exposed `--px-datetime-range-field-display` css var

V2.3.0
==================
* Added ability to hoist timezone dropdown

V2.2.1
==================
* Set bottom padding to 0 by default to align better with other input fields

V2.2.0
==================
* added `fullWidth` to layout field using css-grid

V2.1.5
==================
* added more flexibility for position the fields

V2.1.4
==================
* fixing demo pages for IE11

V2.1.3
==================
* added validation when fromMoment and toMoment are passed in

V2.1.2
==================
* added required to the demo

V2.1.1
==================
* cleaned up api docs

V2.1.0
==================
* added ability to display title above the fields through the `showFieldTitles` property

v2.0.3
==================
* Updated to newest px-datetime-common behavior version

v2.0.2
==================
* added `sudo:required` to travis

v2.0.1
==================
* fix link in docs

v2.0.0
==================
* Polymer 1.X/2.X hybrid support
* range property has been deleted, please use `fromMoment` and `toMoment` for controlling the range. the px-datetime-range-submitted event still exists when a new range is applied.
* `fromMoment` and `toMoment` can be null to have an empty field

v1.1.1
==================
* add device flags

v1.1.0
==================
* added `hideValidationMessages` property

v1.0.4
==================
* add min and max date support

v1.0.3
==================
* Fix comment for analyzer

v1.0.2
==================
* fix demo

v1.0.1
==================
* runtime theming for demo

v1.0.0
==================
* refreshed component
* Updated documentation
* combined -predix and -sketch sass files
* added the option to have the fields wrap or not
* added a hideIcon property

v0.6.0
==================
* added localization through resources, language, formats and Px.moment.changeLocale()

v0.5.11
==================
* converted timeZone property to typeahead

v0.5.10
==================
* add Cloud Flare cache reset

v0.5.9
==================
* fixed responsive spacing per design feedback

v0.5.8
==================
* add Event Fired information

v0.5.7
==================
* add link to Moment documentation

v0.5.6
==================
* added styling section to API documentation

v0.5.5
==================
* fixed typo in component description

v0.5.4
==================
* moved theming style includes and updated ghp.sh
* updated api for new colors

v0.5.3
==================
* Update to px-demo
* removed demosass
* Updated to cool grays

v0.5.2
==================
* Update colors design to pick up new colors

v0.5.1
==================
* changing ghp.sh to account for Alpha releases

v0.5.0
==================
* Updated dependencies

v0.4.14
==================
* changing browser in wct testing from safari 8 to safari 10 on elcapitan

v0.4.13
==================
* changing all devDeps to ^

v0.4.12
==================
* Update px-theme to 2.0.1 and update test fixtures

v0.4.11
==================
* update dependencies for dropdown

v0.4.10
==================
* removing px-theme style call


v0.4.9
==================
* changing Gruntfile.js to gulpfile.js

v0.4.8
==================
* added style variable for theming

v0.4.7
==================
* bower updating px-demo-snippet

v0.4.6
==================
* fixed codepen

v0.4.5
==================
* Update dependencies

v0.4.4
==================
* Latest demo snippet component & latest gulpfile

v0.4.3
==================
* Correcting a minor dep version issue

v0.4.2
==================
* Added correct event listener to demo event counter

v0.4.1
==================
* Fixed demo event counter

v0.4.0
==================
* Uprev

v0.3.14
==================
* changed moment.tz to Px.moment.tz in tests

v0.3.13
==================
* added overflow to demoContainer and removed flex__wrap from mega-demo

v0.3.12
==================
* updated mega demo styles and bower px-demo-snippet to ^

v0.3.11
==================
* Added --px-datetime-range-field-to-color

v0.3.10
==================
* added image to readme, removed watch, added view on github

v0.3.9
==================
* Added vulcanize

v0.3.8
==================
* Updated component description in demo

v0.3.7
==================
* updated footer in demo

v0.3.6
==================
* added footer to demo

v0.3.5
==================
* updated range error message

v0.3.4
==================
* added onerror to shield images.

v0.3.3
==================
* updated mega demo configurations and properties margin

v0.3.2
==================
* fixed merge conflicts

v0.3.1
==================
* updated demo page

v0.3.0
==================
* Added blockPastDates

v0.2.0
==================
* Upgrade to Polymer 1.5.0

v0.1.8
==================
* bind time zone to both fields

v0.1.7
==================
* remove dependency on moment

v0.1.6
==================
* rework to use px-datetime-field

v0.1.5
==================
* added oss_notice to bower ignore

v0.1.4
==================
* added tests for displayOptions for buttons

v0.1.3
==================
* added pull request test for travis and updated OSS Notice

v0.1.2
==================
* added passing of displayOptions for buttons\

v0.1.1
==================
* updated tests for attrs

v0.1.0
==================
* Upgrade to Polymer 1.4.0
* Travis integration and test updates

v0.0.1
==================
* Initial release
