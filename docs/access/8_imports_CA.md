---
id: 8_imports_CA
title: Create Records 
---

## Overview
 
 If there are between 1 and 10 scans in a scan request, the Archivist who requests the scans is responsible for carrying out the upload(s) to CA. This can be done before or after supplying the image(s) to the researcher, depending upon the circumstance (i.e., if you're providing a high-res file through Dropbox you do not need to do the CA upload first; if you're supplying the jpeg, you could upload first and send a link to CA for the researcher to download or put the jpg into Dropbox). 
 
 Steps for uploading scan requests with 1-10 files: 
 1. Create catalog record(s) in CA and upload the file(s).
 2. Update Filemaker to indicate that file has been uploaded.
 3. Move access and preservation files to access and preservation folders.
 
 If there are more than 10 files, the files would be batch uploaded by the Digital Archives office through the batch import process described next. 
 
 ## Batch Imports
 
 ### Import Data
 1. Review spreadsheets for import  
  - Details for formatting metadata: Workflow for: Creating Metadata for Digitized Material
    - Files for import will be placed in relevant staging areas: Digitized_from_Analog_WorkingFiles OR Digital_accessions_to_be_processed
 2. Move Preservation Files 
  - TIFFs and non-access formats go to corresponding collection folder in K:\preservation
 2. Batch Change Media with Multiple Files
  - This will need to happen for records with multiple files associated with the same record (such as, photographs with recto/verso). Collective Access import will only recognize an underscore (_) as it pertains to the record ID. Appended pages will need to follow a period, for example: KA00140_00004.pg002.jpg / not KA00140_00004_pg002.jpg.
 
 **Windows**
 1. Open Bulk Rename Utility
 2. Select folder with files to be batch changed
 3. Settings:   
Example: KA00140_00004_pg002.jpg to KA00140_00004.pg002.jpg 
    - Repl. (3) - Replace _ With .
     - Remove (5) - From 7 to 7 [or the character location of current file]
     - Add (7) Insert _ at pos. 8 [or the character location of current file] 
     - Select 'Rename'
 - This option is for large collections with files that contain multiple pages. 
 - Another way to import multiple files associated with one record without changing the filenames, is to import on a directory. 
 3. Import data into CollectiveAccess 
  - Login to the backend: http://digitalarchives.library.newschool.edu/admin
  - Choose "Import" from the top menu and then select "Data" from the dropdown. 
   - Find the row for “Internal Scan Request Mapping” and click the far right icon for “Import data.”
   - It’s best practice to perform a ‘dry run’ of the import first to see if any parts of the spreadsheet need to be edited.  
 *Note:* When creating thesis records, use the data import marked “Thesis Mapping.” 
 
 4. Create a Set  
 - Find > Objects > Search on collection identifier then ‘Refine’ results by selecting records with restricted access (new records import automatically as ‘restricted’)
 - Save 'Set' with newly imported records as ‘MM-DD-YY [Collection ID] Import.’ 
 - After reviewing for potential edits, perform batch updates. 
-  Potential Batch Updates: 
   - Collection (add a Series, if applicable)
   - Access (accessible to public)
   - Minimum Standards Met - Checked
   
   ### Import Media 
   1. Transfer Files 
  - Open Windows program Secure Shell Client.
   ![ssh portal](assets/access/1_ssh_portal.png)
  - If logging in for the first time, set up a new profile: 
    - Click Profiles > Add Profile
    - Name the profile after the administrator. Press okay.
    - Host name: digitalarchives.library.newschool.edu
    - User name: TNS web ID of the administrator with access (in this example: adm_martinezk)
    - Port number: 22
- Select Window > New File Transfer.
- In new window, remove contents of the finder bar and replace with /collectiveaccess/app/public_html/admin/import/ to reach the collective access directory.
- Here, create folders for content to be imported.
- Separate large collections of large files, such as multi-page pdfs, into smaller groups that may be imported 30 files or less at a time.
- Remove folder contents, then folders, once the import process is complete. This helps avoid confusion and keeps the workspace clean.
2. Import into CA
- Login to CA at http://digitalarchives.library.newschool.edu/admin/
- Select Import > Media
- Select folder created in the import directory 
- Confirm settings before importing:
   - Import mode: “Import only Media that can be matched with existing records.”
   - Select object type.
   - Choose access settings.
   - Show advanced options > Select match using directory name or filename
   - Execute media import
6. Update Featured Topics, if relevant
7. Move Access Files
 - JPEGs and PDFs go to corresponding folder in K:\working_files\Dig_images_access
8. Move finalized data spreadsheet
- K:\working_files\Central_Kellen_share\Digital Archives\Digital_CollectiveAccess\Import\Data
9. Update Archivists’ Toolkit 
- See ‘Adding Digital Object Links’ in AT Processes
10. Checklist for Completed Import 
- Check relationship types to see that description is accurate for non-designer or non-commissioner roles
- Make any new entities accessible to public through batch change 
- Review media for missing data
- Check that PDFs can be searched, if applicable 
- Check that media plays correctly, if applicable 
- Check ‘minimum standards met’ for all records through batch
- Check that dates are correct for non YYYY formats 
- If new collections are added, update AT as needed 

