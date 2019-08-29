FROM openjdk:8-jdk-alpine
ADD sentinel-dashboard-1.6.3.jar app.jar
ENTRYPOINT exec java -Dserver.port=8080 -Dsentinel.dashboard.autoRemoveMachineMillis=${AUTO_REMOVE_MACHINE_MILLIS:300000} -Dsentinel.dashboard.auth.username=${USER_NAME:sentinel} -Dsentinel.dashboard.auth.password=${PASSWORD:sentinel} -jar app.jar