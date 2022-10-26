# CMPG-323-Project-4---31924220

# What is this process?
This process is a process that automates entering data into the database.

# How does the process work?
The process starts by reading data from tables in Excel into data tables in UiPath.
The process then creates a data table to store result data in to export to Excel at the end of the process.
The process then opens the Microsoft Edge browser and navigates to the URL that the website is on and it then automatically signs in for the user.
The process then navigates to the Zones tab and creates each zone but interrupts the creation process after each addition to make sure that the previous record has been added to the database and then stores the check result in the results data table. The same steps are followed for both Categories and Devices.
After adding all data to the database using the website, the process automatically logs the user out and exports the result data to the Excel spreadsheet.

# Publishing the process
I was unsure how to prove that I successfully published the process, so I attached a screenshot:
![Screenshot (113)](https://user-images.githubusercontent.com/67644109/197999009-3ccdff87-24fd-4955-8f6c-7c8cce578995.png)
