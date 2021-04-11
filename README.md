## Expert: Digital Forensics Challenge - Save the Animals

**Author's Name:** Mandy Galante

**Author's Organization:** Red Bank Regional High School

### The Challenge

Links to the various challenge files can be found above or an entire copy of this repository can be made using:

```git  clone https://github.com/PIVOT-Project/DigitalForensicsChallenge```

A link to Google Drive is also available below:

[Resources](https://drive.google.com/folderview?id=0B5wo_1rRmpqVZ3Myc2xtNFBkT0k&usp=sharing)

Challange - https://pivotproject.org/challenges/digital-forensics-challenge

### Solution

Product_E1

* Picture can be found in the packet capture by exporting HTTP objects with Wireshark
* JPG Exif information reveals time and location

Product_P1

* Txt file can be found in the packet capture by exporting HTTP objects with Wireshark
* File needs to be renamed to .jpg extension
* Exif information reveals time and location

Product_D1

* Hard Drive analysis (Autopsy) - Recover Product_D1.jpg from free space.
* JPG Exif information reveals time and location


Product_R1 

* Hard Drive analysis (Autopsy) - Recover f0009604.jpg from free space which is the last image.
* Exif information reveals time and location

During Hard Drive Analysis Product+Prices file can be found. File seems like a spreads heed and extension .xlsx needs to be added for it to be opened. File requires password to be viewed.

SAM hive can be explored with Registry Explorer and user Hive has available bookmarks with information of Full Names of the bad guys and Password for "private documents"

Password for "Private Documents" used to open Product+Prices.xlsx spreadsheet which contains information of Nickname, Price and answer the question which is the most expensive product and why.

Packet trace file also contains source url of downloaded product images which points to domain of gang's website, pinging the domain answers both questions. Website also contains information of bad guys role in the gang.

Lastly alleged buyers information can be found in the browser files - formhistory.sqlite, table moz_formhistory.

