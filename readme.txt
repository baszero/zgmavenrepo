Install new libs into this maven repo:

mvn install:install-file -DgroupId=org.hibernate -DartifactId=jtidy -Dversion=r8-20060801 -Dfile=/Users/baszero/Desktop/org/hibernate/jtidy/r8-20060801/jtidy-r8-20060801.jar  -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=.  -DcreateChecksum=true


