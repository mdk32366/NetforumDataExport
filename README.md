### NetforumDataExport

Processes, files, and techniques for extracting as much, if not all, information out of Netforum to either CSV or Excel data formats.  Also included is information on API access to Netforum from Salesforce, should that be deemed interesting.

#### References

[From 2014 - Netforum data export to excel](https://gravitatesolutions.com/export-netforum-data-to-excel/)

[Netforum's Actual Landing Page (Not Easy to Pin Down)](http://www.abila.com/association-software/association-management/netforum-enterprise/)

[Netforum KB - You need a support contract to access the answers](http://kb.abila.com/)

[A plug in for exporting netFORUM data to a CSV, WITH THE KEYS](https://wordpress.org/plugins/netforum-directory-with-importer/)

[Complete Netforum Documentation](http://documentation.abila.com/netforum-enterprise/2015.1/Default_Left.htm#CSHID=Reports%2FReporting_Services.htm|StartTopic=Content%2FReports%2FReporting_Services.htm|SkinName=Abila)

[Exporting MSSQL to Excel Documentation](https://www.mssqltips.com/sqlservertutorial/202/simple-way-to-export-data-from-sql-server/)

**From within the interface:**

"The key difference between these two exports is that the Export to ASCII Delimited/CSV will carry the Column Headers from netFORUM and the Export to Excel will not.

The below spreadsheet shows data that has used the direct Export Raw Data to Excel option. The first row in the Excel spreadsheet is data."

**Through SSMS to the SQL DB, and then out to Excel:**

Netforum uses an SQL (probably MSSQL) back end.  If this is so, then the DOG SIMPLEST approach is to go straight to the back end using SSMS and do a database export to excel.  It's essentially a wizard, and with, like, four steps you can export the contents of the entire DB to excel spreadsheets.

