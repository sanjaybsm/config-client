# Spring Config Cllient example

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

This is project is build using the tutorial from Spring
[https://spring.io/guides/gs/centralized-configuration/]

# Important thing!

  - Make sure your config server is running before using the client, example can be found here [https://github.com/sanjaybsm/config-centralised.git]
  - Refresh the config property file. Make sure to commit the changes to config property file and run [http://localhost:11000/actuator/refresh] api to fetch the property from config server dynamically