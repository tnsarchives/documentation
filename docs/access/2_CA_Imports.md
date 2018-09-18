---
id: 2_CA_Imports
title: Collective Access Imports
---

## Import Data and Media

1. [Batch] Review Data Files for import  
Details for formatting metadata: Workflow for: Creating Metadata for Digitized Material
Files for import will be placed in relevant staging areas: Digitized_from_Analog_WorkingFiles OR Digital_accessions_to_be_processed
2. Move Preservation Files 
TIFFs and non-access formats go to corresponding folder in K:\preservation
2. [Batch] Batch Change Media with Multiple Files
This will need to happen for records with multiple files associated with the same record (such as, photographs with recto/verso). Collective Access import will only recognize filenames with one underscore (_). Appended pages will need to follow a period, for example: KA00140_00004.pg002.jpg / not KA00140_00004_pg002.jpg.

Windows
1. Open Bulk Rename Utility
2. Select folder with files to be batch changed
3. Settings 
Example: KA00140_00004_pg002.jpg to KA00140_00004.pg002.jpg 
Repl. (3) - Replace _ With .
Remove (5) - From 7 to 7 [or the character location of current file]
Add (7) Insert _ at pos. 8 [or the character location of current file] 
Select 'Rename'
This option is for large collections with files that contain multiple pages. Another way to import multiple files associated with one record without changing the filenames, is to import on a directory. 
3. [Batch] Import data into CollectiveAccess 
Login to the backend: http://digitalarchives.library.newschool.edu/admin
Choose "Import" from the top menu and then select "Data" from the dropdown. 
Find the row for “Internal Scan Request Mapping” and click the far right icon for “Import data.”
I usually perform a ‘dry run’ of the import first to see if any parts of the spreadsheet need to be edited.
4. [Batch] Create a Set  
Find > Objects > Search on collection identifier then ‘Refine’ results by selecting records with restricted access (new records import automatically as ‘restricted’)
Save 'Set' with newly imported records as ‘MM-DD-YY [Collection ID] Import.’ 
After reviewing for potential edits, perform batch updates. 
Potential Batch Updates: 
Collection (add a Series, if applicable)
Access (accessible to public)
Minimum Standards Met
5. Import Media 
Transfer Files 
Open program Secure Shell Client.

If logging in for the first time, set up a new profile: 
Click Profiles > Add Profile

Name the profile after the administrator. Press okay.

Host name: digitalarchives.library.newschool.edu
User name: TNS web ID of the administrator with access (adm_martinezk)
Port number: 22

Select Window > New File Transfer.
In new window, remove contents of the finder bar and replace with /collectiveaccess/app/public_html/admin/import/ to reach the collective access directory.
Here, create folders for content to be imported.
Separate large collections of large files, such as multi-page pdfs, into smaller groups that may be imported 30 files or less at a time.


Remove folder contents, then folders, once the import process is complete. This helps avoid confusion and keeps the workspace clean.
Import into CA
Login to CA at http://digitalarchives.library.newschool.edu/admin/
Select Import > Media
Select folder created in the import directory 
Confirm settings before importing:
Import mode: “Import only Media that can be matched with existing records.”
Select object type.
Choose access settings.
Show advanced options > Select match using directory name or filename
Execute media import
6. Update Featured Topics, if relevant
7. Move Access Files
JPEGs and PDFs go to corresponding folder in K:\working_files\Dig_images_access
8. Move finalized data spreadsheet
K:\working_files\Central_Kellen_share\Digital Archives\Digital_CollectiveAccess\Import\Data
9. Update Archivists’ Toolkit 
10. Review Completed Import 
Check relationship types to see that description is accurate for non-designer or non-commissioner roles
Make any new entities accessible to public through batch change 
Review media for missing data
Check that PDFs can be searched, if applicable 
Check that media plays correctly, if applicable 
Check ‘minimum standards met’ for all records through batch
Check that dates are correct for non YYYY formats 
If new collections are added, update AT as needed 


## Batch Updates
1. Create a Set
Select the records you would like to include by performing a search. In this example, we search on the base identifier. 
In the upper right corner, select ‘Find’ > ‘Objects’
Search: [NS021201] > Click ‘Search’ 
After results are returned, select ‘Set Tools’ from the left menu
Select ‘Create Set’ and use the dialog box to name your set. You’ll see a dropdown menu that allows you to add records from the search results, or from checked records. Clicking the box ‘Open set for batch editing’ will automatically open batch editing for this set. If that option is selected, the next step can be skipped. 
2. Batch Edit a Set
In the upper right menu, select ‘Manage’ and then ‘My sets.’ Locate your new set and select the files icon in the ‘# Items’ column to batch edit the records. 
Choose the field you would like to edit, selecting ‘add to each item,’ ‘replace value,’ or ‘remove all values’
Click ‘Execute Batch Edit’




Backend Searching
https://docs.collectiveaccess.org/wiki/Search_Syntax#Searching_for_blank_values

