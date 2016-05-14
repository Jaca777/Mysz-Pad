FROM  java:openjdk-8u72
MAINTAINER MyszAndPad
ADD /craftbukkit.jar /
ADD /eula_.txt /
ENV PORT = 25565
ENV SIZE=128
ENV SLOTS=0
ENV ONLINE-MODE=true
CMD java -Xmx${SIZE}m -jar craftbukkit.jar --online-mode ${ONLINE-MODE} --size ${SLOTS} --port ${PORT} ; rm eula.txt ; mv eula_.txt eula.txt ; java -Xmx${SIZE}m -jar craftbukkit.jar --online-mode ${ONLINE-MODE} --size ${SLOTS} --port ${PORT}
