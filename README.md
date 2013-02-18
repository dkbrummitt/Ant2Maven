Ant2Maven
=========

This Python based project can be used to copy an Ant Based Project to a Maven project.  
It will: 
  * generate the proper maven directory structure
  * copy source, xml, and property files into the proper directory
  * generate a POM
  * add dependencies to the POM according to the JAR files found
  * load the JAR files into the LOCAL m2 directory
   
NOTE:  
This script will NOT add dependancies based on "real" repository settings holdings.  So far, I havent found a reliable way to do this across all JARs.  
But it will at least get you up and running locally with out a migraine.   
