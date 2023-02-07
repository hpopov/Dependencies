# Dependencies
Maven URL should be https://maven.pkg.github.com/hpopov/Dependencies/repository 

Other capabilities are not tested (text below outdated). For more details, please, check: https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-apache-maven-registry

# To install a dependency here you have to execute this command using cmd:
# mvn install:install-file -DlocalRepositoryPath=Path:\to\this\repo -Dfile=%1
# from the directory, which contains POM for your dependency, where %1 points to dependency jar file.
# and also do so for attached source and java docs jars
