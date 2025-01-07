FROM openjdk:alpine

WORKDIR /testdir/java

COPY calc.java /testdir/java/

RUN javac calc.java

CMD [ "java" , "calc" ]
