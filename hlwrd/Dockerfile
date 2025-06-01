FROM openjdk

RUN mkdir -p /java/hlwrd

COPY . /java/hlwrd

WORKDIR /java

EXPOSE 8001

RUN javac hlwrd/Main.java

CMD ["java", "hlwrd.Main"]