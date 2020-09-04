
> Title:  scoping the project, Desc:   scope of the project, including user journey, stakeholder, epic and tasks

> Filename: joomlavel-documentation / scoping_document.md

> Created: 2020-08-31, Fixed: 2020-08-31, Created_by: J. Walczak

> Contribution: 



# introduction
## stakeholders
1. agency
2. developer
3. devOps
4. configurations assistent

## user journey
1. an agency is interessted in Joomlavel, start gathering of informations and gets necessary information 
2. a dev is interessted in Joomlavel and start to test it
3. a dev is creating first generic component within 5 sec with very slim commands (convention over configuration), component can be zip-installed in a running joomla! instance
4. a dev is creating a generic laravel instance within 5 sec with basic configuration options, packet can be copied to a traditional-hoster (i.e. 1&1)
5. a dev is modifieing generic component by uncommenting, to enable REST connections to laravel instance and OpenAPI
6. a devOps or developer is integrating laravelinstance packet on traditional hoster with a joomla instance

# functional description
##Overview over epics
1. 'i am interessted in JoomLavel', distribution of tutorials, documentation and quickstart
2. RAD for Joomla Component - php file tool for fast creation on Joomla Component
3. RAD for Laravel Packet - still undefinied tool for fast Laravel deployment on traditional hoster

##Overview of User Stories
E1.1 ...
E2.1 As a developer i clone the JoomLavel-Connector project to develop my first Joomla component => clone and type:" php JoomLavel make: component BobsFirstComponent"
E2.2 As a configurations assistent, developer or devOps i install own JoomLavel-Component on my instance and make basic configuration in Joomla administration => basic configuration should be preconfigured and should expect a simple api endpoint (i.e. https: //api.nasa.gov/insight_weather/?api_key=DEMO_KEY&feedtype=json&ver=1.0)
  => basic configuration cound be an OpenAPI 3.0 source
E2.3 As a developer i want to extend my JoomLavel-Connector with custom code => uncomment or comment command or type: i.e. 
 "php JoomLavel make: middleware", to manipulate Source API Data before presenting
 "php JoomLavel make: service", to hardcode a Source API
 "php JoomLavel make: presenter", to create own presenter

E3.1 As a developer i clone the JoomLavel-Api project to develop my first JoomLavel API => clone and type:" php JoomLavel make: api AliceFirstLaravel"
