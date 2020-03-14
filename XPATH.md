# XPATH

cheatsheet → [https://devhints.io/xpath](https://devhints.io/xpath)

XPATH allow you to naviguate through an XML file

Here an example of an XML file :
```
<CATALOG>
    <CD>
        <TITLE>Empire Burlesque</TITLE>
        <ARTIST>Bob Dylan</ARTIST>
        <COUNTRY>USA</COUNTRY>
        <COMPANY>Columbia</COMPANY>
        <PRICE>10.90</PRICE>
        <YEAR>1985</YEAR>
    </CD>
    <CD>
        <TITLE>Hide your heart</TITLE>
        <ARTIST>Bonnie Tyler</ARTIST>
        <COUNTRY>UK</COUNTRY>
        <COMPANY>CBS Records</COMPANY>
        <PRICE>9.90</PRICE>
        <YEAR>1988</YEAR>
    </CD>
    <CD>
        <TITLE>Greatest Hits</TITLE>
        <ARTIST>Dolly Parton</ARTIST>
        <COUNTRY>USA</COUNTRY>
        <COMPANY>RCA</COMPANY>
        <PRICE>9.90</PRICE>
        <YEAR>1982</YEAR>
    </CD>
    <CD>
        <TITLE>Still got the blues</TITLE>
        <ARTIST>Gary Moore</ARTIST>
        <COUNTRY>UK</COUNTRY>
        <COMPANY>Virgin records</COMPANY>
        <PRICE>10.20</PRICE>
        <YEAR>1990</YEAR>
    </CD>
</CATALOG>
```

To get every nodes
> /*

The dot is for the current node
> ./

> .//

To get the first CD
> /CD[1]

To get the price price of the CD 'Greatest hits'
> /CD[./TITLE = ‘Greatest hits’]/PRICE

To get all CDs which the year is superior to 1988
> /CD[./YEAR > 1988]

To get all the year present in the file
> //YEAR

To get all node where the node name starts with ART
> /*[starts-with(local-name(),'ART')]

