---
id: 1_AT_Processes
title: Archivists' Toolkit Processes
---

## Introduction

Archivists Toolkit (AT) is an archival management system the New School Archives uses to catalog and keep track of our collections. We also use it to generate collection guides for our website, and library catalog records.

AT is also the way we know exactly where each box and folder from each collection lives. Archivists Toolkit is the main place where we store location information, so if the actual location does not match up with the data in AT, the box or the folder is, essentially, “lost” in the Archives.

AT has been loaded onto every workstation in the office, so it is accessible wherever you may be working. 

## The Basics
### Important Information about AT
AT has several shortcomings that will influence your work processes. It is important to keep these deficiencies in mind as you are working.
There is no “undo” function!
There is no “spell check” function.
It is easy to accidentally drag information into the wrong location on the left-hand side of the screen.

In summary, please work slowly and carefully in AT. Save your work often.

The Save button is located on the far right of the toolbar running across the bottom of the screen. The icon is a floppy disk. Use it often.

Be wary of the Delete Component button on the second toolbar from the bottom. Do not click it!


### Modules
AT has five different modules. You will likely only be using two of them, Resources and Accessions. Most likely, you will be working primarily in the Resources module.

By double clicking on Resources, you will open a list of every collection in the New School Archives. 

To find a particular collection, start typing its name into the “Filter Search Results” bar in the top right corner. Alternatively, you can sort the collections in alphabetical order by title, or numerically by collection number.



Double click on a record to open it.

### Inside a Record

Across the top of the record, you will see four tabs labeled, Basic Description, Names & Subjects, Notes Etc. & Deaccessions, and Finding Aid Data. 
­

In Basic Description you will find fields for folder titles, dates, amounts of materials (extent), and locations of folders.  

### Finding Locations

To find the location of a folder in a processed collection, look on the Basic Description tab in AT for that folder.

In the lower right corner, you will see a field called Instances. Double click on the rows of information in this field (there may be more than one if materials are different sizes and, consequently, stored in different size boxes).
­

A window titled Analog Instances will appear on your screen. At the very bottom of the window you will see a location that corresponds to the shelf numbering in the New School Archives.

Sometimes we send boxes offsite for storage, particularly larger size boxes. If the box is not physically located in the New School Archives, you will see a note that reads: Clancy Cullen Offsite Storage. At the top of this window in the Container 1 barcode field, there should be a serial number. 

For instructions on how to assign locations, see the following section.

## Assigning locations (instances)
Each smallest component (file or item) should have an “instance” entered in AT. This assigns a location to the component.

Here are the steps for adding an instance:
Click “Add Instance” to assign a location. A pop-up window will appear asking what type of instance you would like to create. Always select “Mixed materials.”
In the next window, “Container 1 Type” should be box and “Container 2 Type” should be folder. Enter the appropriate number next to the indicator field for each. When the component being described takes up numerous folders within the same box, enter the range of files. If the box is going offsite, enter the barcode for the box next to “Container barcode,” or use the Yale Plug-in to apply barcode information to any component with the same instance (ie if multiple folders are in the same box, use the plug-in to attach the barcode information to each instead of manually entering it in the instance for each folder.) Click “OK” when complete.
Example:

To assign a location to this instance click “Manage Locations”

This will bring up a new window. Highlight the box you are adding a location to and click 
“Add Location Link” at the bottom. Search for the appropriate shelf in Kellen or select 
“Clancy-Cullen” if the box is going offsite.

### Mixed boxes
To locate a mixed box with available space and add material to it:
Open AT and double click on “Resources” in the left navigation pane.
In the “Filter search results” bar on the top right of the window type “Mixed”
Double click to open the relevant mixed resource: If the collection you are processing is KA, for example, open the resource titled “Mixed KA”
This will open the resource record for “Mixed KA” (or “Mixed.PIC, etc.) Look through the list on the left-hand navigation pane for a box of the appropriate size with room
Add the material to that box and number in accordance with the other material in that mixed box. 
Steps 6-7 are no longer done, but since this is a former practice you will find resource records for mixed boxes with “children.” Skip to step 8.
In the left-hand navigation pane, click to highlight the box you have added to and then click the button “Add Child”
Add a title to the basic description for this child that follows this format: “COLLECTION NAME (COLLECTION NUMBER) (f. [folder number]) and select “file” from the drop-down menu next to “Level”
If the mixed box is now full, click back into the title of that box and edit the title to sau (FULL)
Add the location of this material to the collection record following the steps above

### Hive storage instances
For material stored in the hives, fill in the instance for that material in the following way:
Container 1 type: Choose “Box”
Container 1 instance: spell out: "Hive A", "Hive B", or "Hive C"
Container 2 type: Slot
Container 2 type instance: Enter slot number

### Yale Plug-in
The Yale Plug-in applies the barcode and location information for a box to every instance it appears in. If a collection has multiple files in the same box, this automatically updates the instance for each file with the barcode and location information for the shared box. To use the plug-in close out of the resource and select “Plugins” from the menu at the top of the page. Select “Yale tasks”-->”Assign container information.” Select the box you would like to add a barcode to and choose “Assign container information.” Enter the barcode in the applicable box and then click “Assign values.” At the bottom of the window, with the same box selected, click “Add location link” and select Clancy-Cullen. When finished hit “Done.”

## Collections with digital objects

For all collections on our digital collections site (digitalarchives.library.newschool.edu) that have digital objects for completed collections, you will ensure that there’s a collection level note in the AT record. Formerly, digital object links were added at the series level, so you will find legacy resource records with these links. This is no longer the practice, and digital object links should only be inserted in the other finding aids note at the collection level. , and add digital object links at the Series level. This will create a link between the finding aid to the digital collections site.

### Other Finding Aids note
Look on the website to see if the finding aid has been uploaded previously (before anything had been digitized). If so, you will need to re-upload the finding aid upon revision. In this event, add a new row for the collection in the MASTER_Finding_Aid_TRACKING_CURRENT file saved in the collections management folder. Update Column D and other relevant fields to track progress in prepping for upload.
Make sure an Other Finding Aid note is present for that collection in AT. If not, add one:
In  AT Other Finding Aid note (under Notes Etc. & Deaccessions tab) for corresponding collection, enter text:
For selected item-level description and images from the [add collection title], see the New School Archives Digital Collections at [paste URL of collection level page here]
Highlight the URL, and click on the box, “wrap in tag.” Chose “extref” option. In next box, select “onRequest,” show = new, and copy the URL again into the “href” field. 
A properly formed example is below for reference:
<extref actuate="onRequest" href="http://digitalarchives.library.newschool.edu/index.php/Detail/collections/etc." show="new">http://digitalarchives.library.newschool.edu/index.php/Detail/collections/NS021201</extref>.
The reason the note text is formed this way is that the URL will still be visible to human readers even if there is a problem with the links themselves. Jenny also believes that this makes the finding aid compatible with software used by people with visual impairments.

### Adding Digital Object Links 
Check to see if the finding aid has digital object links by looking at the instances at the series and/or component levels. If there are not any existing digital object links, do not add any.  
If there is a preexisting finding aid with digital object links at series or component level: create a digital object record in AT at the Series level. You’ll only create a digital object record for the series that have digital objects on the digital collections site.
Click Add Instance and select Digital Object. Make sure the words “Digital Object” are highlighted or AT won’t allow you to progress to the next step. Digital Object screen will appear. Complete the following fields:
Title: For Series-level links, enter the text, “Link to selected images from this series.” Where there are no series in the digital collection, enter, “Link to selected images.”
Object Type: Choose best fit; usually it will be image. Sometimes it will be text. You will not need sound or moving image. [WHY?] Ask Jenny/Wendy if you’re not sure.
Digital Object ID: Paste the Series Identifier that you copied from the Series page on the digital collections site. If there is no series on the digital collection site, enter the Collection Identifier (hint: it’s the same as the Resource ID for the collection in AT).
File Version: Back on digital collections Series page, “Click to view all items from this collection.” Copy the URL of the Objects page related to this Series. If there is no series for this collection, from the Collection page, “Click to view all items from this collection.”
In AT under File Version, URI: Paste the URL for this Series (or Collection).
Use Statement: Select either Image-Service or Text-OCR-unedited. Text-OCR-unedited should be used for objects that have been uploaded as PDF files—e.g., catalogs, theses, scrapbooks. If in doubt, ASK, don’t guess. Do not select any other options without discussing first with Wendy/Jenny.
EAD Dao Actuate: Choose onRequest 
EAD Dao Show: Choose New
Click Open URI in Web Browse to confirm that the link is correct. If not, fix it!
Repeat for each Series in the collection that has an associated Series on the digital collections site. If there are no series on the digital collections site (this is a case where you’re adding a Digital Object link from only one series), your work is complete.


## Importing Resource Records 
### Reference Materials
Template: 
This template was lifted from the PACSCL Hidden Collection Processing Project, created by Matt Herbison. The source:
http://clir.pacscl.org/2012/03/19/excel-to-xml-the-spreadsheet-from-heaven/
A copy of the spreadsheet can be accessed here:
http://public.herbison.org/ead/
A guide to using the template can be found at these sites:
http://clir.pacscl.org/wp-content/uploads/2009/07/PACSCL-Finding-Aids-Spreadsheet-Guide.pdf
http://images.library.amnh.org/hiddencollections/wp-content/uploads/2012/07/ContainerLists_ATimport.pdf (this one provided by Liza)
Guide on server: 
archivists_toolkit/spreadsheet_import/PACSL Finding Aid Spreadsheet Guide 
archivists_toolkit/spreadsheet_import/EAD_AT_Template

### Formatting Data






