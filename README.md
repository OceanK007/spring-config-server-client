# Spring cloud config server and client #

* For client application:
	1. Config file must be "bootstrap" -- not "application" -- so that it is read early in the application startup process. The server.port could be specified in either file, but the URI to the config server affects the startup sequence.

	2. The application name in bootstrap.yml must be matching with the configuration file defined in ConfigData folder deployed at github.

# URL for details
* https://github.com/kennyk65/Microservices-With-Spring-Student-Files/blob/master/LabInstructions/Lab%203.md