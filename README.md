# Eclipse RAP Incubator GEF Port

## Building RAP Runtime

The RAP project uses Maven in combination with [Eclipse Tycho](https://github.com/eclipse/tycho) to build its bundles, and p2 repositories, and it's easy to run the build locally! All you need is [Maven installed](https://maven.apache.org/install.html) on your computer, and then you need to run the following command from the root [`pom.xml`](./pom.xml) of the RAP Incubator Git repository:

    mvn clean verify

As a result, you get a p2 repository with all bundles in the directory

    repository/target/repository/

## Old Remarks

### 12/8/2010

This initial port of Draw2D, GEF and Zest for RAP is still under development.  
It is currently based on an unstable fork of the GEF project but will be updated for the Indigo release.  
It requires changes that are forthcoming in the RAP target platform itself and will currently not function.  
It is currently checked into HEAD so that others may begin to analyze for use in their environments.  
This file will be updated when the status changes.  

### 1/3/2011

There is a patch in bug 285397 on the rwt and workbench plugins from CVS HEAD.  
With that patch you will be able to run the gef demo project.  
