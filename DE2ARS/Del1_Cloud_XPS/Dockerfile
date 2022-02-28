# Use an official Java jdk 
FROM openjdk:13-jdk-oracle

ARG WHICH_XP=1
ENV WHICH_XP=$WHICH_XP
# Set the working directory to /app
WORKDIR /home/

COPY . /home/


# Run the app
CMD java -jar Del1_XP$WHICH_XP.jar

COPY $HOME .

