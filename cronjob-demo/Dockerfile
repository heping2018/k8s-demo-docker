FROM 49.234.200.12/kubernetes/java:1.8
COPY ROOT/cronjob-demo-1.0-SNAPSHOT.jar /cronjob-demo.jar
ENTRYPOINT ["java","-cp","/cronjob-demo.jar","com.mooc.demo.cronjob.Main"]
