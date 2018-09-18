---
id: 11_scan_requests
title: Overview
---
Scan requests have alternate workflows, largely depending upon the number of scans being made for a job. If there are between 1 and 10 scans in a scan request, the Archivist who requests the scans is responsible for carrying out the upload(s) to CA. This can be done before or after supplying the image(s) to the Researcher, depending upon the circumstance (i.e., if providing a high-res file thru Dropbox, Archivist does not need to do the CA upload first; if supplying the jpg, Archivist could upload first and send a link to CA for the Researcher to download or put the jpg into Dropbox).

## Between 1-10 scans:
1. Archivist requesting scans creates catalog record(s) in CA and uploads the file(s), unless files are large PDFs. If files are large PDFs, alert Digital Archivist that catalog record has been created and the file is ready for upload.
2. Update Filemaker to indicate that file has been uploaded.
3. Move access and preservation files to access and preservation folders.

## More than 10 scans:
For scan requests involving more than 10 scans, files will be batch uploaded by the Digital Archivist. In these cases, a batch upload template needs to be created.

1. Before scanning, Archivist creates a folder for the scan request in Digitized_from_Analog folder, prepares batch upload template for these scans, and puts template into this folder.
2. When alerting Scan Tech about job, Archivist indicates where Scan Tech will find batch upload template.
3. Scan Tech enters image IDs and box/folder fields in template. Alerts Archivist when done.
4. Archivist assigns Student Worker to complete remaining fields in template, and performs QC on the scans. Alerts Archivist when done.
5. Archivist reviews, then alerts Digital Archivist that template and images are ready for upload.
6. Digital Archivist performs batch upload.
7. Update Filemaker to indicate that files have been uploaded.
8. Moves access and preservation files to access and preservation folders.


## Detailed Breakdown of Process
1. For each scan request, the researcher should complete required fields on the scan request flag:
-Initials
-Date
-Consecutive number starting with 1 for each batch of scan requests

2. The Reference Archivist enters the required fields into the FileMaker Digitization Request record, and sends an email update to the Scan Tech and to the archivist@newschool.edu. 
Instructions for entering digitization requests in Filemaker can be found in the manual Tools and How-Tos: Filemaker Researcher Log_FINAL_20180906
Send email with with subject line: 'Scan Request ###’ and cc the archivist@ account

3. The Scanning Technician
Before scanning, check CA to confirm (as much as possible) that the image has not already been scanned (it's possible that the flag was misplaced or that one was never in place)
Check Working Files and other possible locations for files 

4.  Depending on the number and size of files either Processing Archivist (if there are only a few scans to uploaded manually) or Digital Archivist (for larger batch upload) creates record(s) in CollectiveAccess using base file name as CollectiveAccess identifier and including, at minimum:
a title
creation date (can be approximate)
related collection
creators must also be included if known. 

5. Processing Archivist adds links to Archivists Toolkit following instructions in Tools and How-Tos: Archivists' Toolkit Basics_IN PROGRESS.

6. After the files have been uploaded to Collective Access the Digital Archivist transfers preservation TIFFs to the appropriate collection folder in Central Kellen Share/preservation/Still_Images_Text_Preservation ("K:\preservation\Still_Images_Text_Preservation"). Transfers access JPEG and/or PDF files to the appropriate collection folder in working_files/Dig_images_Access ("K:\working_files\Dig_images_access") and deletes empty collection folder from that year’s folder.
Scanning Project
Scanning project priorities are determined according to researcher demand, preservation needs, archivist processing/cataloging needs, and relevant time-sensitive classes, events or initiatives. They are managed in the document Digitization_Queue located in Collection_management/Tracking ("K:\working_files\Central_Kellen_share\Collection_management\Tracking\Digitization_Queue.docx") and periodically reviewed in archives staff bi-weekly meetings.

At the beginning of each new project, Digital Archivist determines whether descriptive metadata should be created at the time of scanning and/or after scanning is completed. Generally, scanned items with clearly indicated titles, creation dates, etc, may have the descriptive metadata generated at the time of scan by Scanning Technician, and any items that require more research or knowledge should have descriptive metadata completed after scanning by Asst Dir for Dig Archives, Dig Production Mgr, Associate Archivist or Asst Archivist. 

If metadata is to be generated at time of scanning, follow these steps:
Digital Archivist creates spreadsheet template in Google Sheets to be used by Scanning Technician.
Scanning Technician completes scans for scanning project following instructions in the Workflow: Scan Tech_IN PROGRESS.
Once scanning is completed, Digital Archivist uploads spreadsheet created by Scanning Technician according to instructions in CollectiveAccess_Batch_Uploads_Data.  The Google spreadsheet should be downloaded and saved in the collection folder on the shared drive.
Then, if there is only one access file per CollectiveAccess Record, Digital Archivist can follow instructions in CollectiveAccess_Batch_Uploads_Media to upload access files. If there is more than one access file per CollectiveAccess record the media files will need to be uploaded individually [unless this is fixed in CollectiveAccess at some point].

If scan tech does not create spreadsheet while scanning Dig Archivist batch uploads media into blank records and then completes them individually, or can begin by creating a record in CollectiveAccess for a scanned item and then duplicate that record to retain any fields that might be the same across records, overwriting fields that are different from record to record.

Complete steps 6 & 7 from the Scan Request Procedure above.

When Scan Tech notifies via Archivist account that scanning is complete, Processing Archivist updates FMPRO with number of files and indicates “SCANNING COMPLETE” in note field. (FMPRO also need to be updated when (a) scans have been furnished to researcher; (b) scans have been uploaded.

[Processing Archivist confirms that flags have been correctly created and folders stamped by Scan Tech] - [something about QC?] - 
who creates Batch Upload Template? - These instructions are in Tools and How-Tos: Cataloging in CA. Can we combine? https://docs.google.com/document/d/1txizLAFNywR46p4kU0yC-DQzp4QSNAS6sX6xfCxujTY/edit#heading=h.jxp5u5qfcs40
who adds scan ID numbers to AT in Repos. Processing Note?
who fills out metadata in template? - these instructions are somewhat described above and in Tools and How-Tos: Cataloging in CA https://docs.google.com/document/d/1txizLAFNywR46p4kU0yC-DQzp4QSNAS6sX6xfCxujTY/edit#heading=h.jxp5u5qfcs40
change folder name and communicate to Katie that template and media are ready to be uploaded?
Scan Request Payments
Fees for scanning can be found in “Reproduction_Revisions_20180717_FINAL” saved here: K:\working_files\Central_Kellen_share\Procedures_Guidelines_Workflows_Policies\Patrons_Public_Svc_Scanning. We accept payment via check or credit card. Checks are preferable and should be made out to New School Archives & Special Collections. Scan requests should not be submitted until payment has been received. If the patron is planning to use the reproductions for publication/exhibition, the scan request should not be submitted until they have returned the completed publication agreement form.
Setting up Credit Card Payment
TK
Tracking

Once the cost of a scan request has been calculated and the patron has agreed to move forward with the request, create an invoice for the order (unless the researcher says they do not require one.) Use the form “Invoice_BLANK” found here: K:\working_files\Central_Kellen_share\Forms-Blank_Signs\Invoices_Purchasing. Save the form here: K:\working_files\Central_Kellen_share\Reproduction_scanning_publication\Invoices_Agreements_Outstanding

Once the payment has been received move the invoice to K:\working_files\Central_Kellen_share\Reproduction_scanning_publication\Invoices_and_Agreements_COMPLETE\Invoices_PAID

When the payment is complete also record the order in “Incoming funds log_CURRENT” saved here: K:\working_files\Central_Kellen_share\General_administration\Incoming_funds. Enter the received payment at the bottom of the spreadsheet above the line that says “Cumulative Restricted.” If the payment was made by check, record the amount in the column that says “Amount gift restricted.” If made by credit card, record in the column that says “Amount general operating.”
Publication
If the patron is planning to use the reproductions for publication, exhibition, or other public use, they must complete a publication agreement form. That form is found here: K:\working_files\Central_Kellen_share\Agreement-Templates_Licensing_Rights\Publication_Broadcast_Exhibition

Upon sending the form to the patron save the form, with the patron’s name appended to the file name, in this folder: Reproduction_scanning_publication/Invoices_Agreements_Outstanding
Once complete, move the completed form to: K:\working_files\Central_Kellen_share\Reproduction_scanning_publication\Invoices_and_Agreements_COMPLETE\Agreements_Complete.

The agreement should also be uploaded to Filemaker and the publication/exhibition information should be entered in the “Publications and Exhibitions Module.” Instructions for doing so can be found in Workflow: Filemaker Researcher Log_INPROGRESS. 
