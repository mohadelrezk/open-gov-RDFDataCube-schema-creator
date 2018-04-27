Generic Data Cube Schema Creator
===============================

Overview
--------
A generic Open Refine project to model RDF data cubes schema.

the RDF Data Cube Vocabulary: http://www.w3.org/TR/vocab-data-cube/.


Similar Project
--------
https://github.com/GMDSP-Linked-Data/GenericStatsCube

Contents
--------

- Skelton spreadsheet.
- JSON file containing RDF refine Skelton of the RDF Data Cube Vocabulary.
- Example folders.
- RDF Cube Vocabulary Schema.
- Read Me.

Installation
--------
1. Download/Open/Run Open Refine (http://openrefine.org/)
2. Add the RDF Extension to Refine (http://refine.deri.ie/)

** Use latest version =>
 
 https://github.com/fadmaa/grefine-rdf-extension/releases/tag/v0.9.0


Usage
--------
1- Copy and Fill Spreadsheet “Assisted_CubeSchema_Creator.xlx” 

2- Creating New Open Refine Project using spreadsheet file.

3- Copy RDF Skelton in “RDF-refine-skelton-for-RDF-DATA-CUBE-VOCABULARY.json”

4- Paste it in the Apply operations window in the Open Refine Project.

5- Extract => as Turtle or RDF/XML 

Done !

###follow the screens:
[1]

![img](screen_samples/1.png)

[2]

![img](screen_samples/2.png)

[3]

![img](screen_samples/3.png)

[4]

![img](screen_samples/4.png)

[5]

![img](screen_samples/5.png)

[6]

![img](screen_samples/s02.png)

[7]

![img](screen_samples/s03.png)

[8]

![img](screen_samples/s3.png)

[9]

![img](screen_samples/s4.png)

[10]

![img](screen_samples/s5.png)

[11]

![img](screen_samples/s6.png)

[12]

![img](screen_samples/s7.png)

[13]

![img](screen_samples/s8.png)

[14]

![img](screen_samples/s9.png)

[15]

![img](screen_samples/s10.png)

[16]

![img](screen_samples/s16.png)

[17]

![img](screen_samples/s17.png)

[18]

![img](screen_samples/s18.png)

[19]

![img](screen_samples/s19.png)

[20]

![img](screen_samples/s20.png)

[21]

![img](screen_samples/s21.png)

[22]

![img](screen_samples/s22.png)

[23]

![img](screen_samples/s23.png)

[24]

![img](screen_samples/s24.png)

[25]

![img](screen_samples/s25.png)




Help
--------
Consult example folders for details on how to fill the spreadsheet. 


Linux installation
----------
    $ mkdir openrefine28
    $cd openrefine28
    $wget https://github.com/OpenRefine/OpenRefine/releases/download/2.8/openrefine-linux-2.8.tar.gz
    $tar -xvzf openrefine-linux-2.8.tar.gz
    
change port/host
-------
    $cd openrefine28/openrefine-2.8
    $nano refine.ini 
    change PORT/HOST if neede

    
install grefine rdf extension
----------
    $cd openrefine28
    $mkdir openrefine-rdf-extension
    $wget https://github.com/fadmaa/grefine-rdf-extension/releases/download/v0.9.0/orefine-rdf-extension-0.9.zip
    $unzip  orefine-rdf-extension-0.9.zip
    $mv  orefine-rdf-extension-0.9 ../openrefine-2.8/webapp/extensions/
    
java disply error [only if occured]
-------
    $unset DISPLAY

Run openrefine server / with orefine rdf ext
-----
    $cd openrefine28/openrefine-2.8
    $screen -S ogi-open-refine-8007 ./refine
    
    
---------------------
Last update: 19th July 2017

