## Mac OS Installation (1)

Welcome to the Mac OS Installation Steps  

http://www.enterprisedb.com/products-services-training/pgdownload#macosx



## We are going to build DVD Rental Database

Open the PostGre SQL server settings

![image-20181001132006784](/Users/s4555024/Library/Application Support/typora-user-images/image-20181001132006784.png)

![image-20181001132309527](/Users/s4555024/Library/Application Support/typora-user-images/image-20181001132309527.png)



As you can see above  we went over installing [PostgreSQL](http://www.postgresql.org/download/) and [pgAdmin](http://www.pgadmin.org/download/). 

Here are the steps we performed (and reviewed at the end):

1. Download iZip application from [www.izip.com](http://www.zip.com/)
2. Open and extract the dvdrental.tar file using iZip
3. Search for pgAdmin III and open it
4. Double-click on PostgreSQL 9.5 to see the Databases drop-down
5. Right-click on Databases and select “New Database…”
6. Name a new database and select Done.
7. Right click on that new database and select “Restore…”
8. Find the path to the dvdrental.tar file (remember to enable all file extensions)
9. Select it and then click on “Restore”
10. Click on the refresh button with your database selected
11. You should now be able to see Tables(15) in the drop-down menu of your Database
12. You can test this by executing an “Arbitrary SQL Query on the Database”