# for-stackoverflow-question-num-01
Wildfly versions - LoggerFactory is not a Logback LoggerContext but Logback is on the classpath.

This repository is aimed to better understand the following question in Stackoverflow : 

https://stackoverflow.com/questions/71147054/wildfly-upgrade-runtimeexception-loggerfactory-is-not-a-logback-loggercontext

In the directories starting with "with-wildfly", you will find :
- the "pom.xml" file I used in the project and ;
- the resulting "wildfly-output.txt" that contains the Wildfly server logs that were generated.

You can find in the "wildfly-output.txt" of the directory "with-wildfly-21.0.2.Final-it-works-and-with-logs" that the program
displays a message in the logs : "Scheduled is working". The message should be displayed in the other "wildfly-output.txt" files of the 
2 other directories but it isn't.

