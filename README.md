Ant2Maven
=========

This Python based project can be used to copy an Ant Based Project to a Maven project.  It will: &lt;ul>&lt;li>generate the proper maven directory structure.&lt;/li>&lt;li>copy source, xml, and property files into the proper director&lt;/li>&lt;li>generate a POM &lt;/li>&lt;li>add dependencies to the POM according to the JAR files found.&lt;/li>&lt;li>load the JAR files into the LOCAL m2 directory&lt;/li>&lt;/ul> NOTE:  This script will NOT add dependancies based on "real" repository settings holdings.  But it will at least get you up and running locally with out a migraine.   