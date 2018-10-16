# Release Procedure

Build pipeline builds releases and deploys to package repository for tagged 
releases. This can be triggered with :

    mvn release:prepare && mvn release:clean    