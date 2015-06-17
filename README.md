# org.dita-community.preprocess-tester
Trivial plugin that just makes it easy to run the base OT preprocessing in isolation for testing and learning purposes.

Modify the build.xml file to add or remove preprocess targets from the @depends attribute on the `<target>` element.
The results of preprocessing will be in the temp directory.

Use the transformation type "preprocess-test":

````
ant -Dtranstype=preprocess-test -Dargs.input=mymap.ditamap
````