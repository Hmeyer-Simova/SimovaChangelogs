Build Status
=================
[![Build Status](https://dev.azure.com/simova/Product%20Development/_apis/build/status/DPS%202016dev%20Build?branchName=2016_DEV)](https://dev.azure.com/simova/Product%20Development/_build/latest?definitionId=5&branchName=2016_DEV)

Release Changelog
=================

(*pre git = tracked by TFS)

V1.0.31.0
---

Change | Commit | Author
-------|--------|-------
Multiple download elements out of DMS are not loaded correctly on the dashboard | | Lukas Böhm & Christian Lienau
Dataset sequence doesn't work | [624ce446](https://dev.azure.com/simova/Product%20Development/_git/DOTNET%20-%20DPS%20by%20Simova/commit/624ce4467e8d73975a641e68a1402ae2d90a55ce?refName=refs%2Fheads%2F%23366) | Huschke Meyer
Added Html encoding to prevent cross-site-scripting | [f443146b](https://dev.azure.com/simova/Product%20Development/_git/2e2ddebd-eb82-40ff-9fcb-e47322c79bbf/commit/f443146bd59c955a0029dfa1ca9c7c940af8ee24) | Huschke Meyer
Wrong file name when downloading a report | [3e75ca45](https://dev.azure.com/simova/Product%20Development/_git/NAV%20-%20DPS%20by%20Simova/commit/3e75ca45d122bcf84263dd39aed29e5bdc41fe15?refName=refs%2Fheads%2F%23333) | Lukas Böhm
Card page columns aligment (left/right) not possible | [89c94f19](https://dev.azure.com/simova/Product%20Development/_git/2e2ddebd-eb82-40ff-9fcb-e47322c79bbf/commit/89c94f196a3e6ceb976bfaac748b6a1e9c2d9b70) | Christian Lienau
Error Messages (Toast message) are empty | [89c94f19](https://dev.azure.com/simova/Product%20Development/_git/2e2ddebd-eb82-40ff-9fcb-e47322c79bbf/commit/89c94f196a3e6ceb976bfaac748b6a1e9c2d9b70) | Christian Lienau
Input field configuration |  | Huschke Meyer  
Removed unmask password symbol | [3491e2ac](https://dev.azure.com/simova/Product%20Development/_git/DOTNET%20-%20DPS%20by%20Simova/commit/3491e2ac3988f49958b5a0b69d9ae3558b42d06b?refName=refs%2Fheads%2F%231077) | Huschke Meyer
Dashboard Group activation does not work | [67aa7bbe](https://dev.azure.com/simova/Product%20Development/_git/DOTNET%20-%20DPS%20by%20Simova/commit/67aa7bbe91a4dc3228365b8804edad9b40ba1913?refName=refs%2Fheads%2Fmaster) | Huschke Meyer
Datepicker in basket editing does not work | [67aa7bbe](https://dev.azure.com/simova/Product%20Development/_git/DOTNET%20-%20DPS%20by%20Simova/commit/67aa7bbe91a4dc3228365b8804edad9b40ba1913?refName=refs%2Fheads%2Fmaster) | Huschke Meyer
Form information| [0f18a499](https://dev.azure.com/simova/Product%20Development/_git/DOTNET%20-%20DPS%20by%20Simova/commit/0f18a499e8f3cf0f5cedbf48eb005da796cb65dd?refName=refs%2Fheads%2F%23216) | Huschke Meyer
Use standard SMTP setup | [b3663b4b](https://dev.azure.com/simova/Product%20Development/_git/NAV%20-%20DPS%20by%20Simova/commit/b3663b4b26c5f2a629938e402a3f2748da7f6b0f?refName=refs%2Fheads%2F2016_DEV) | Markus Czernia
Cleanup Web Users | [beda4d18](https://dev.azure.com/simova/Product%20Development/_git/NAV%20-%20DPS%20by%20Simova/commit/beda4d188fd2533608f7e606684d1c4df2c60d60?refName=refs%2Fheads%2F2016_DEV) | Huschke Meyer
Action caption visual glitch | [0f18a499](https://dev.azure.com/simova/Product%20Development/_git/DOTNET%20-%20DPS%20by%20Simova/commit/0f18a499e8f3cf0f5cedbf48eb005da796cb65dd?refName=refs%2Fheads%2F%23216) | Huschke Meyer
Update MaterializeCSS to Latest Stable | [0f18a499](https://dev.azure.com/simova/Product%20Development/_git/DOTNET%20-%20DPS%20by%20Simova/commit/0f18a499e8f3cf0f5cedbf48eb005da796cb65dd?refName=refs%2Fheads%2F%23216) | Huschke Meyer
Update Jquery to Latest Stable | [e110f11f](https://dev.azure.com/simova/Product%20Development/_git/DOTNET%20-%20DPS%20by%20Simova/commit/e110f11f09dc3e28bd796ae21d48a303368c0e4c?refName=refs%2Fheads%2F%23216) | Huschke Meyer
Entries cannot be edited from the shopping cart | [a53b6ac5](https://dev.azure.com/simova/Product%20Development/_git/DOTNET%20-%20DPS%20by%20Simova/commit/a53b6ac52bbda576ba351a3be6c602678a2b8bd4?refName=refs%2Fheads%2Fmaster) | Christian Lienau
DPS - extend CSS insert to requests | [519d13da](https://dev.azure.com/simova/Product%20Development/_git/DOTNET%20-%20DPS%20by%20Simova/commit/519d13da8325fd33fe2f373b97101a04222b27a0?refName=refs%2Fheads%2Fmaster) | Christian Lienau
Added Changelog.md | [4d5b245e](https://dev.azure.com/simova/Product%20Development/_git/DOTNET%20-%20DPS%20by%20Simova/commit/4d5b245e50062b6924e1242f977642e9b076741d?refName=refs%2Fheads%2F%23216) | Huschke Meyer



V1.0.28.0(Pre git)
---

Change |
-------|
Custom CSS styles for EVERY Item in DPS |
Read-only Property for Input Fields |
Calendar: improved GUI |
Default values of basic fields are not transferred |
Form title was not displayed |
Master data -> Actions -> Form -> FactBox (Settings) -> "Form Sub Title". The value was not written In the shopping cart and in the shopping cart history there was a display error when calculating the columns, this was corrected. |
Min Max Value for numerical values was not working |
Revise shopping cart history |
Hover Color from a line action was not configured. |
Wrong style for the record links |
Revised Timed Out window |


V1.0.24.0(Pre git)
---

Change |
-------|
The log-in area and all login screens of the portal have been redesigned.  |
Recently there is an optically separated registration area to increase user friendliness. Functionally, everything has remained the same. |
In the download area there was an error in the filtering, which caused the detail view to close. This bug has been fixed. |
The language file for Switzerland contained a wrong decimal separator, this was checked and corrected. |
In the shopping cart and in the shopping cart history there was a display error when calculating the columns, this was corrected. |
There was another display error in the e-mail templates, this was corrected. |



V1.0.23.0(Pre git)
---

Change |
-------|
A new view style makes it possible to display text in HTML style on detail pages. This text area could appear as a stack in the dashboard and be displayed when diving onto the new element. |
The upload area has also been embellished. If an image already exists when uploading, there are now 4 options for how to proceed with the file. |
The headers were not displayed correctly in the portrait format of a mobile phone, this has been fixed. |


V1.0.22.1(Pre git)
---

Change |
-------|
Special character conversion revised. |
An error occurred during the ordering process, this was corrected. |
The whole line could not be activated in the header area, this error was corrected. |
The content type is now transferred with the upload. |


V1.0.22.0(Pre git)
---

Change |
-------|
The dashboard got a new view style called order form. |
With this you can create a form on the dashboard, where you can send the fields directly. This allows instant access and a direct view. |
Fixed bug with special character conversion. |


V1.0.21.2(Pre git)
---

Change |
-------|
Safari: The filtering in combination with a diagram has thrown an error, this has been fixed. |
Safari: A scrollbar was shown in the tables, which was unnecessary there and therefore removed. |


V1.0.21.1(Pre git)
---

Change |
-------|
In DPS Management the "Create" popup closes automatically after successful input and clears all fields. |
The file names placeholders were revised and all locked characters were excluded. |
Info Popup Bug fixed, now the correct texts are displayed. |
The Email Request Template field now has a dropdown box. |
The Basket Icon field has set the default shopping cart icon. |


V1.0.21.0(Pre git)
---

Change |
-------|
A new KPI information tile has been added to the dashboard. In this tile any KPI value from Microsoft Dynamics NAV / BC can now be displayed on the dashboard. To enable a symbol (e.g. the Euro sign) or a text display after the KPI for currency KPIs, you can configure post-texts. The current setup only allows filtering to one value. If several filters are set, the first entry is always used. |



V1.0.20.0(Pre git)
---

Change |
-------|
The old calendar was removed and replaced |
Important changes are for example different view styles, new headers and footers, a new design as well as changed or new actions. |
The header now consists of rows below each other. The first line offers the possibility to go one step forward or backward, as well as the view of the current date. The second line, on the other hand, is only visible if it has been activated. There are several configurable fields in Navision. These include the complete switching on of the second line in the header, as well as the activation of the today button, the views day/week/month and a button to display all events. |
The footer is just as configurable as the header. It consists only of a single line, in which you can activate different list views, as well as the ICal button. Depending on how many lists have been activated, 2 different layouts are used. With only one list view and one ICal, both elements position themselves opposite to each other at the edge, that is, the list is left at the edge and the ICal is right at the edge. If several lists are activated, the ICal remains on the right and all views are centered in the middle. To get a balance in the layout, the width of the ICal button is as wide as the distance from the left to the list elements. |
The content is defined as before by date, title and subtitle fields. What is new is that you can now set symbols and background colors on the respective events (invoices, events, etc.). You can get the symbols from Font-Awesome by using the complete i-Tag. Background colors are accepted as RGB, RGBA, HEX or in English. If you want the same icon or background color for all events, you can also use the 2 fields "Global Event Symbol" and "Global Event Background Color". |
Note: The background color and the icon on the event itself is not standard, here a setup on the customer side must be done in the provided table. |
If you click on an event, you get directly to the respective detailed map. |
All headings of the list views as well as of the ICal and the "All Events" button can be set up. |
The calendar element can be built in on the dashboard or as a view style. |
The calendar is created in Responsive Design and adapts to the different spans. Additionally, the calendar element is also available in our app. |


V1.0.19.0(Pre git)
---

Change |
-------|
Redesign and extension of the DPS Management page |
Unification of the icons from the DPS Portal with those from the DPS Management Page. During this process the icons of the two categories "Status" and "Styles" were exchanged to make the meaning clearer. |
Headings and texts have been added for better comprehension. |
The sorting function in the first column of the table has been revised to allow up and down sorting. |
The category "Links" was also designed more clearly and got its own modal in which all functions have been retained. |
Two new categories named "Language" and "Changelog" were added. With the category "Language" you can review/adjust existing language files and it’s possible to create new ones. New created language files are based on the English language and has to be adjusted manually. With the category "Changelog" you get an overview of the current DPS product changelog. |
Redesign of the Responsive Design on the DPS Management page |
Logo adjustment on the login page in dark design. |


V1.0.18.2(Pre git)
---

Change |
-------|
Publish functionality on Web User Page. |
Input Option Filter with type filter. |
Download Content Type with spaces. |
Sorting with Keyindex and ascending for initial state in Table. |
iCal Format correction for Mac and IOS. |


V1.0.18.1(Pre git)
---

Change |
-------|
The delivery and invoice addresses in the user administration have a checkbox in Navision, which enables the display and hiding of the address data. |
In addition, there is an individual field in Navision in which it is possible to create a text or a new openable box using HTML code. This appears above the user administration. |
In the user management you can hide the complete section by omitting the heading. This rule does not apply to the log-in area. |
Google Browser Specific fix for Datepicker. |


V1.0.18.0(Pre git)
---

Change |
-------|
Add grouping and filter option to downloads. |


V1.0.17.0(Pre git)
---

Change |
-------|
Maintenance page added to DPS Management. |
Confirmation mail added to new registration. |
During the registration there is now a new field "customer number", as well as password conditions, which can be set variably. |
Re-design of the Login/PasswordForgot/PasswordReset and SignUp page. Adjustments to the usability. |
Design revision of all error messages. |
Adjustment of the page breaks for longer texts. |


V1.0.16.0(Pre git)
---

Change |
-------|
The user administration has got a more compact design and now has a search function, as well as a more limited display for the addresses. For the "Load more" button there is now an adjustable headline. |
It is now adjustable whether you jump from an action to the shopping cart or to the dashboard. |
The registration page now has several form fields and a new styling. Herewith a better registration should be possible. |
Web users can be automatically assigned to contacts using the appropriate function. If the contact does not exist, you can create it directly. |
New user-defined fields can be output in the views that do not belong to the actual table. This is done using dynamic mappings. |
New email notification after registration. |
Furthermore the bug with the password change button has been fixed. |
2 small style adjustments in the calendar. Also the mobile scrolling was prevented to move the month, this is only possible when wiping from left to right or vice versa. |
The shopping cart information is no longer displayed as a small box in the upper right corner, but extends over the entire width below the navigation. |
The set margin (left/right) in the dashboard of the respective groups is now removed from mobile and the group is centered. |


V1.0.15.0(Pre git)
---

Change |
-------|
When publishing, a corresponding dialog is now displayed. |
All web users can be checked for missing information in the web user map. |
Table locks are now prevented by multiple requests.
There is a new configuration parameter "DebugLevel" in which the output in log files can be configured. |
Various bug fixes in the web frontend.


V1.0.14.1(Pre git)
---

Change |
-------|
The user administration has been extended by a log-in area. Here the user can view his e-mail address as well as his user name. The "Change password" has been moved to this area for structural reasons.  |
The visibility of the business data has been reworked so that minor bugs have been fixed. |


V1.0.14.0(Pre git)
---

Change |
-------|
A separate page has been created for the user administration. Here it is now possible to change the password by action. In addition, the own contact data, delivery and billing addresses, as well as contact data of the contact person are displayed. |
If there are orders in the shopping cart, a popup window is displayed on all levels to indicate that the shopping cart still must be confirmed/completed. The popup window can be shown or hidden by configuration. In addition, the note text can be freely defined. |
Fixed a problem where email confirmation was not sent when placing an order. |
The code length of the labels was reduced from 50 to 30 characters. During an update you must make sure that there are no labels longer than 30 characters. The pre-upgrade process checks the length of the code field. If it exceeds 30 characters a message will be displayed. |
The calendar in version 1.0.13.5 and earlier had a problem displaying the correct weekday. This bug has been fixed in the new version. |


V1.0.13.5(Pre git)
---

Change |
-------|
New Function "Send Welcome Email (All) |
"Delivery Required" depends on "Business Type Required" in Actions |
Fixed a problem where some emails were not sent when placing an order |
The shifted widths in the shopping cart have been fixed. |
The problem with the order of the input fields has been fixed. |


V1.0.13.4(Pre git)
---

Change |
-------|
Registration link to external website. |
The navision values were set to data record fields.  |
Buggy records of record fields fixed. |
Fixed dropdown box, if there are no entries, the dropdown box is not hidden. |
Fixed an error when displaying form fields on an entire line. |
Table action buttons displayed smaller. |


V1.0.13.3(Pre git)
---

Change |
-------|
Multi Company support. |
Change XMLPort DPS User Import ID to valid license range.  |


V1.0.13.2(Pre git)
---

Change |
-------|
Flex adaptation of the dashboard elements without the attribute full width. |
Text Image Combination centered Display adjusted.  |
Linking extended by several types. |
Restriction of the maximum file size and the type of file during file upload. |
The shopping cart icon is now configurable. |
An individual info text can now be set up in the shopping cart. |


V1.0.13.1(Pre git)
---

Change |
-------|
Calendar Design revised |
The filter area has been redesigned and a malfunction has been repaired |
Tooltip design designed more neutrally  |
Mandatory field Legend display Error fixed |
News background color can now also be completely set in Transparent  |
Dashboard Action Buttons are now configurable in Microsoft Dynamics NAV |


V1.0.13.0(Pre git)
---

Change |
-------|
Error message for 0 values |
Calendar Style Revision |
Development Filter Integration |
Add iCal Download |


V1.0.12.0(Pre git)
---

Change |
-------|
Footer rearranges itself on mobile devices. |
New text formatting on all pages. |
Changing Columns on Mobile Devices. |
New style for all Action Buttons. |
Added functionality to archive DPS Orders periodically.  |
Adding an error message for 0 values. |


V1.0.11.4(Pre git)
---

Change |
-------|
Column width adjusted on the iPad |
Slider White space reduced |
The action buttons are uniformly adjusted in style. |
The error effect in the forms is highlighted more strongly. |
Added a legend for the mandatory fields. |


V1.0.11.3(Pre git)
---

Change |
-------|
Dropdown fixed. |
Flex style customization. |
Slider Text Version - Headline removed. |
Sorting of versions changed. |


V1.0.11.2(Pre git)
---

Change |
-------|
Cookie Bar Design |
Dropdown height is now reduced automatically. |
Scroll function of news fixed. |
Add Flex to Row. |


V1.0.11.1(Pre git)
---

Change |
-------|
Basket line removed if no editable fields are available. |
Scrollbar available again in News. |
Filter works correct now. |
Header Info texts are no longer truncated. |


V1.0.11.0(Pre git)
---

Change |
-------|
Table Input Option problem in Site and Basket. |
Background images in dashboard and list views can be set separately. |
New input field type "Selection" - "Select". From to Range adjustable Static or dynamic via table fields. |
Performance optimization during data transfer from Navision to the IIS server. |
Image gallery adjustable via 1-5 image mappings. |
Login area redesigned. |
Performance improved or speeded up when displaying the page. |
Table view with new scrolling function. |
Table view Paging does not reload already loaded data sets, but works via a cache. |
Column widths adjusted. Equal width of head and body. |
Table export button (CSV, PDF, Excel) redesigned in footer. |
Footer - All captions and values have the same width for a more structured display. |
Scrolling of the body is prevented if you are on a scrolling element and have reached the end or the beginning. |
Sequence of the menu changed. Start page and shopping cart are now in front. |
All input fields changed for a uniform representation. Positioning of the input fields 2 columns or over the entire width with one setting. |
In Navision, clients are only displayed according to data records. |
The text is no longer truncated in the "Cue "s in the dashboard but is displayed with "...". |
Only one element in a dashboard group is no longer displayed filled. |
Language dependent Filter Problem in Navision fixed e.g. with a Boool field "Yes" "No" is now "true" "false". |
Added new icons for record and language in menu.  |
New animations for selections, new Hovereffects in shopping cart and collection view. |
Report printing via code unit creates a DPS order to the rows, so Customer ID or Vendor ID and delivery addresses can be better read out in further processing. |
Input option can also be displayed as Modal. |
Input option as dropdown display improved. Search input is positioned at the bottom when the box opens to the top. |
Users can be set inactive. |


V1.0.10.3(Pre git)
---

Change |
-------|
Table Input Option problem in Site and Basket. |
jquery 3.3.1 relation in DPS Management Site. |
Filter on Dynamics NAV User Page and Web User Page. |
Default created captions has an “SYSTEM_” prefix now. |
Simova DPS App API to WS.


V1.0.10.2(Pre git)
---

Change |
-------|
Filter as Text (Alternative to slider). |
Allow first column click to show details in Table View. |
Shows the correct Input Option Field value in Basket Overview. |
Dataset Table Lines does not load in the dashboard anymore. The Lines will only loaded in the detail view. |
Dataset Table Line Web Content is configurable now in Factbox. |
Default Dataset Table View Style changed from “None” to “Table” |
New Settings “Disable Search” to disable the search in overviews. |
Input Field type Setting “Decimal Place” for “Number” type. |
Web Content automatically validate the number to the given format. |
Actual version is written to configuration. |


V1.0.10.1(Pre git)
---

Change |
-------|
Custom Option Input Field. |
Report over Codeunit Action. |



V1.0.10.0(Pre git)
---

Change |
-------|
New License System. |
Simova DPS App support (Prototype). |
Config Language Settings not override on update. |
Order Upload / Download Files. |
Cue Count overflow. |


V1.0.9.5(Pre git)
---

Change |
-------|
Language problems. |
User Password reset. |
E-Mail system config missing. |


V1.0.9.4(Pre git)
---

Change |
-------|
Copy Dataset. |
Detail Line Problems fixed. |


V1.0.9.3(Pre git)
---

Change |
-------|
News Control. |
Cookie Message. |
Style Issues.  |
User Instance problem. |
Many Usability improvements. |


V1.0.9.2(Pre git)
---

Change |
-------|
Performance Improved to display larger data volumes. (Paging) |
Dasboard configuration improved. |
Dataset publish information “Changed By” and “Changed Date”. |
Factboxes to display more informations in navision. |


V1.0.9.1(Pre git)
---

Change |
-------|
Add to Basket Validation in Process Codeunit. |
Version Info on Setup. |
Upgrade improved with Pre and Post Upgrade. |
Direct detail view on only one element in list. |
Prevent Detail View from dashboard element Cue, Calendar or Chart. |
docma shows document from cycle lists. |
No action on detail view then hide container. |
Ajax calls abort on page leave. |
Loading Spinner visible on more actions. |


V1.0.9.0(Pre git)
---

Change |
-------|
Comments/Info text saved in Blob. |
Registration on login page. |
Info text with html style. |
Service user, Service password, service domain to web service connection (Encrypted). |
Detail View can be disabled. |
Info text on Form. |
Select box with configured dataset table. |
Image for delete icon in basket and a confirm message on delete an entry. |
State Canceled on orders. |
Backup for upgrade a site in DPS Management Site. |
Dependency check to Visual C++ 2017 Redistributable. |
Notification language to Navision user. |
Download Button Text can be set correctly |
Double Click problems on Buttons. |
Check(bool) values on form. |


V1.0.8.2(Pre git)
---

Change |
-------|
Multiple calendar works now |
Padding style of editable fields. |
Multi line text box works now. No reloading anymore. |
Add Visual Studio C++ 2015 Redistributable as dependency to installer. |
Basket loading problem.


V1.0.8.1(Pre git)
---

Change |
-------|
Video autoplay configurable. |
Lazyload for images. |
Basket loading problem. |


V1.0.8.0(Pre git)
---

Change |
-------|
Multiple Slider as filter. |
Option Fields with filter definitions. |
Dashboard Elements get background and foreground color from style. |
Dataset configuration in Navision improved. |
New Captions insert all configured languages into the lines. |
Single Dataset publishing. Metadata moved from User Table to User Dataset Mapping Table. |
Html Text export from Dataset information. |
Config language parameter are split into language Config files. |
Description for the Order Action in Navision. |
Max Length for input fields from type text and multiline. |
Setting to disable the Navigation buttons. |
Role center cue for uploads. |
Code Redesign. |
Portal Title can be set with config now. |
Portal mini logo can be set with config now. |
Datepicker and Timepicker problems fixed. |
Contact Person button is not visible if the contactperson is not configured for the user. |


V1.0.7.0(Pre git)
---

Change |
-------|
Following text after field value. |
Video problem on iphone. |
Filter/Slider problem on Style Collection. |
On hover a Quick Action no pointer will be shown. |


V1.0.6.0(Pre git)
---

Change |
-------|
Video on Dashboard. |
Upload Count on Record available now. |


V1.0.5.0(Pre git)
---

Change |
-------|
Make Quote from Item Sample Codeunit. |
Style height can be set on Dashboard Group. |
All modal windows replaced with card style. |
User validation in NAV. |
DMS Upload / Download. |
Some minor bug fixes. |


V1.0.4.0(Pre git)
---

Change |
-------|
Year and month selection in calendar. |
Some minor bug fixes. |


V1.0.3.0(Pre git)
---

Change |
-------|
More detailed Styling for Dashboard. |
Type Formular. |
Role Center Requests added. |
Calendar on dashboard. |
Mini Chart on dashboard. |
Button on dashboard. |
Edit Mode on more than one codeunit action. |
Setting for mouse scroll over slider. |
Editable option Multiline. |
Slide dots are visible over the content. |
Input fields configured now to an action. |
Browser back button works correct. |
Lines can now be selected without an editable field |.
Some minor bug fixes. |
REMOVE: Page DPS Order Line List |


V1.0.2.0(Pre git)
---

Change |
-------|
Styling for Dashboard.
Dashboard Types Cue, Quick Action and Picture.
Picture for Dashboard Type “Cue”.
Offline availability for icon fonts ionicon, materialize icon, fontawesome and glyphicon.
Dashboard Fill configuration. (Only one Element).
Dashboard Static Height configuration.
Slide Animation with Timeout configuration.
Slide Navigation visibility configuration.
Table Export visibility configuration.
Dashboard configuration in Navision to a data table.
Data Table validation in Navision with colouring.


V1.0.1.0(Pre git)
---

Change |
-------|
Chart Type on Data Table. |
Size of data table can now be configured like a group with Column Span and Column Offset. |
Range Filter functionality on a field with a slider. |
Scrolling Group redesigned. |
Action “Create Role Center” on DPS Setup. |
Action “Assign Role Center” on DPS Dynamics User |
Action “Check Line” on DPS Dataset Table to validate error faster. |
Dataset configuration more user friendly. |
UpdateImages works correct now. |
Option Field show the Text option not the number. |
SMTP Password in setup is masked now. |
Field “Name” is Readonly now in Web User Business Mapping. |
The User Management shows the correct user now. |


V1.0.0.1(Pre git)
---

Change |
-------| 
Delivery Address Functionalities. |
Multiple customer management for portal user. |
Contact Person button. |
Support for DMS by Simova or File System with UNC Path. |
Upload functionality to order and to dataset table. |
Download functionality. |
Footer can be configured better. |
Flow Fields value shown correctly. |
