# Playing With Fuse

## On Deploy
    When this file is dropped into a Fuse container, any 
    xml files in OSGI-INF/blueprint will be automatically 
    registered.

    This particular example add an endpoint to the default CXF 
    servlet, and defines a ref to our JaxRS implementation code.

## Installation
    mvn package
    fire up Fuse
        > bin/fuse
        > osgi:install -s file:/vagrant/play1-1.0-SNAPSHOT.jar

