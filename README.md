# cloud-configuration-manager

* Not the spring cloud based cloud configuration manager. Learn what is spring cloud configuration.

* cloud config UI to onboard the application and manage the configuration.
* cloud config agent to pull the changes from config server by applicationName and Version using http.
* cloud config server to store the configuration in mongodb.
* client application and agent will run in a single container. client application should read the specific keys into the application.
