# Build and run java with docker container

<<<<<<< HEAD
docker pull jacknorthrup/oracle8


Two files are used, one to complie the XX.java
and one to Run the compiled XX.class

when running do not use the extension to run XX.class
just enter:   Run XX 
=======
Build with docker or pull from source:
docker build -f dockerize-your-java-application -t jacknorthrup/oracle8:latest .

or just run:
./CreateDockerImage.sh

docker pull jacknorthrup/oracle8

# To execute/run:
Run <compiled-java-class>
example:
Run Main
------
# To compile 
Compile Main.java

The class file will  be created
>>>>>>> 01f41772cd129fbbc3249860487f5dc3c2147227
