FROM Java:openjdk-8u72-jdk
ADD BuildTools.jar /server
WORKDIR /server
RUN java -jar BuildTools.jar -rev 1.7.10
CMD java -jar craftbukkit-1.8.6.jar
