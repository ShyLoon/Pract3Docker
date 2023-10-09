FROM openjdk:latest

LABEL version="1.3"

WORKDIR /calcs

COPY calc.java /calcs/
# запуск приложения
RUN javac calc.java 

CMD ["java", "calc"]