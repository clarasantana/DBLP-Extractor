DBLP Data

The Digital Bibliography & Library Project provides open bibliographic information, the full data is contained in a XML which can be downloaded on http://dblp.uni-trier.de/xml/. This code process the DBLP data in order to extract the authors and co-authors.

Instructions:

1. Move into the same directory the xml file and the codes.
2. Get into the directory and compile them: javac Parser.java
3. Start the program with the command: java -mx900M -DentityExpansionLimit=2500000 Parser dblp.xml > out.txt
4. The result will be storaged on out.txt

