How to set run time spring active profiles runt time

theare  are  three types of environment.


1. application-dev.properties
2. application-uat.properties
3. application-prod.properties


after building jar, if you want to run java applicaiton with  (dev) envrionment,
then run below command


java -jar demo-0.0.1-SNAPSHOT.jar --spring.profiles.active=dev


after building jar, if you want to run java applicaiton with  (uat) envrionment,
then run below command


java -jar demo-0.0.1-SNAPSHOT.jar --spring.profiles.active=uat


after building jar, if you want to run java applicaiton with  (prod) envrionment,
then run below command


java -jar demo-0.0.1-SNAPSHOT.jar --spring.profiles.active=prod

