# GCAL-for-Windows

GCAL for Windows: versions and documentation. 
By Gopalapriya das. 
Gaurabda Calendar Program for calculation of the calendar for vaisnavas, according Gaudiya-Vaisnava tradition. 
2006-2014 © ISKCON GBC Vaishnava Calendar Comitee. 
Last stable version: GCAL 11.2.

Versions of Gaurabda Calendar program

Development of this application started in 2006.

History:
2006 – basic discussion about program
2007 – looking for algorithms and user interface
2008 – beta testing

GCAL 0.0 (GCAL 0)
(Previously with another name)
RELEASE DATE:
- initial version in non-resizeable dialog window

GCAL 1.0
RELEASE DATE: 28-Sep-2007 
- unified behaviour for naksatra, tithi and sankranti dialog
- fixed bug for tithi calculation
- select & copy from text in main window
- implemented ekadasi parana calculation according last specification
- writes location for calendar calculations
- calculates celebration dates for future years for appearance day calc.
- changed Compare tool
- export to external file also to TEXT file

GCAL 1.1
RELEASE DATE: 18-Dec-2007
- windows are resizeable
- added introductional page "Today" with information about today's vaisnava day. Location for Today calculation are set in menu "Settings / My Location"
- changed user interface

GCAL 1.1.6
RELEASE DATE: 4-Feb-2008
- little improved textual output
- all changes mentioned in beta-testing results
- changed "Select Location" dialog window

GCAL 1.1.7
RELEASE DATE: 7-Feb-2008
- corrected dialog window for location is attached.
New functions:
- add new location
- edit location
- remove location
- reset to build-in list of locations
- locations dialog available in menu Settings->Locations
- storing of location list (changes in loc.list are persistent)

GCAL 1.1.8
RELEASE DATE: 10-Feb-2008
- fixed bug in My Location dialog window

GCAL 1.1.9
RELEASE DATE: 18-Feb-2008
- added command-line arguments

GCAL 1.1.10
RELEASE DATE: 19-Apr-2008
- added underline for menu items
- corrected correction of Ekadasi Parana time according DST
- corrected calculation of initial TODAY page
- updated (no) DST for Arizona, Puerto Rico and Hawaii: set for not used
- corrected TIMEZONE parameter for console mode

GCAL 1.1.11
RELEASE DATE: 21-Apr-2008
- added choice for ayanamsa value (Fagan/Lahiri/Krishnamurti/Raman)
- corrected calculation of moonrise/moonset
- corrected printing of DST note in calendar listing

GCAL 1.2.0
RELEASE DATE: 2-MAY-2008
- added calculation "Next Tithi" and "Prev Tithi" for keys F5 and F7, active, when window contains result of calculation of tithi times
- custom defined events
- added show setting items: - Month header, Dont show empty days, Show begining of Masa
- added new locations: total count is 2381 cities
- new names for DST according international standard
- corrected ekadasi parana for unmilani dvadasi

GCAL 1.2.1
RELEASE DATE: 8-MAY-2008
- corrected using of custom event (used immediately after creation)
- editing of custom event
- limited length for custom event description text to 39 chars
- saving of settings for shown info
- corrected ksaya tithi listing
- corrected "Asia/Urunqi" to "China"
- fixed bug in Settings/Location/Create Location and Edit and Export Location
- removed blank lines in calendar listing
- added hidden choice for setting Ayanamsa and Sankranti (CTRL+SHIFT+F11)
- storage of configuration files in separate subdirectory "config"

GCAL 1.2.2
RELEASE DATE: 28-MAY-2008
- changed ekadasi parana calculation for naksatra mahadvadasis

GCAL 1.2.3
RELEASE DATE: 30-MAY-2008
- fixed initialization of hour for staring date for calendar calculations
- increase of precision of algorithms: naksatra and tithi start calculation
- changed size of dialog window "Observed Events"
- correction of exporting calendar results into file
- correction of running progress during calculation
- set limit of max 90 years for calendar calculation
- storing of default values for dialog windows for various calculations
- corrected printing of ksaya tithi time
- corrected printing of vriddhi info

GCAL 1.2.4
RELEASE DATE: 5-JUNE-2008
- removed "Save Content" from Edit menu
- fixed "Naksatra Mahadvadasi" bug

GCAL 1.2.5
RELEASE DATE: 7-JUNE-2008
- corrected handling of (ksaya/adhika) masa sequences

GCAL 1.2.6
RELEASE DATE: 10-JUNE-2008
- corrected calculation of sankrantis
- corrected print-out of tithi times
- default ayanamsa method is Krishnamurti
- changed layout for calculation of sankrantis

GCAL 1.2.7
RELEASE DATE: 19-JUNE-2008
- default ayanamsa set to Lahiri
- corrected appearance day calculation (crashing)
- corrected masa listing (strange dates)

GCAL 1.2.8 (GCAL 1)
RELEASE DATE: 22-JUNE-2008
- corrected today screen (error in showing of the information)
- corrected closing of multiple windows (in prev version when first opened window was closed, application terminated, now app will terminate only when last window is closed)

GCAL 1.3.0
RELEASE DATE: 1-SEPT-2008 (GCAL 1.1)
- corrected "Bengalooru" to "Bangalore" in Location List
- possibility to export calendar to iCalendar format (.ics file) and vCalendar format (.vcs)
- changed appearance of the Settings dialog
- added recalculation of calendar after setting ayanamsa/sankranti method
- added tithi calculation to naksatra screen and changed title to "Tithi & Naksatra List"
- changed choosing of country in the Create Country window + automatic updating of DST system according country + automatic updating of TimeZone offset according selected DST system
- introduced classes for events (0 for Appearance days of the Lord, ... 6 for Custom Events)
- improved Find Event dialog window ... 3 conditions for a day + more values
- printing capability for all outputs, special output for Calendar and Tithi and Naksatra List
- corrected DST adding to sankranti time
- renamed "Tithi Timing" to "Day Inspector" + improved layout
- changed dialog window "Day Inspector" – ability to insert Gregorian date simultaneously with Gaurabda date
- possibility to show location in Google Maps

GCAL 1.3.1 (GCAL 2)
RELEASE DATE: 8-SEPT-2008
EXPIRATION DATE: 15-DEC-2008
- corrected freezing in „Day Inspector“ dialog window
- added scroll-box to "All Results"-tab in the Event Finder window
- changed "colon separated value" to "comma separated value"

GCAL 2.1
ALFA RELEASE DATE: 30-OCT-2008 (GCAL 2.1)
- main window remembers its position on screen between launching application
- corrected behaviour in EditLocation dialog window - enabling of OK button, when manualy typing the name of country
- corrected behaviour in GetLocation and EditLocation dialog windows - not changing selection in Timezone combobox
- improved behaviour in GetLocation and EditLocation dialog windows - DST combobox contains only DST systems valid for selected Timezone (that means there are not so many irrelevant choices in DST combobox)
- corrected display of Today information when sankranti occurs
- changed command line structure (see document "GCal Command Line using.doc")
- added possibility to save Appearance Day calculation results in the XML format
- merge of "Day Inspector", "Sankranti" and "Tithi&Naksatra List" into one screen - "Core Events"
- restructured dialog windows for calculation inputs

GCAL 2.2
ALFA RELEASE DATE: 5-NOV-2008 (GCAL 2.2)
- corrected calculation of Core Events and Appearance Day

GCAL 2.3
ALFA RELEASE DATE: 20-NOV-2008 (GCAL 2.3)
- corrected writing of the XML file format for Appearance Day data

GCAL 3
RELEASE DATE: 9-DEC-2008
EXPIRATION DATE: 15-MAR-2009
- added writing of calendar results in HTML table format, setting of first day in week is in the Calendar Display Settings / Advanced.
- corrected closing of the application by command 'Exit" in the main menu
- in Today screen, showing sunset, noon and sunrise time 
- for Calendar display is now showing of paksa, naksatra, yoga and fasting flag made optional (settings are available at the "Festivals" pane in the Calendar Display Settings)
- added printing of the change of the DST system (transition from local time to DST and back), optional setting is available at the "Advanced" pane in the Calendar Display Settings
- corrected fasting data for Advaita Acarya Appearance Day
- corrected bug in Calendar Display Settings Window (was not saving settings when changing tabs)

Wish List
- button "Stop" in calculation window
- history for calculations
- updating of Location database
- writing new Country into database
- "location manager window"
- "events manager window"
- rich text output
- update of application/data via Internet

