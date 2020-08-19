##Short Report Are Dæhlen

In this assignment i have learned the basics of Heroku, as well as gotten more practice using the commandline and setting environment variables.

I ran into some problems with the Java JDK when trying to build the program using the *mvn clean install* command. I solved this by changing my environment variable and starting over. I must have done something wrong during the **Getting Started On Heroku With Java** tutorial.

To validate that the software development environment was working I ran the *echo %JAVA_HOME%* command in the commandline. This gave me confirmation that the software development environment was properly configured.

Multiple problems were encountered with the Heroku platform. When running the command *heroku config:set ENERGY="20 GeV"* my console only replies **'C:\Program' is not recognized as an internal or external command, operable program or batch file.**. I never managed to fix this issue, but rather set the config variables through Heroku's [website](https://dashboard.heroku.com/apps/).

A pending issue that occurred during the assignment was the implementation of the PostgreSQL software development environment. When running the command *heroku pg:psql* it does not recognize the command even though i have set the environment variable. I have no idea how to fix this issue as of yet.
