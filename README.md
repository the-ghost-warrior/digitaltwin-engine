# __*DigitalTwin-Engine*__

The Digitaltwin-Engine is an umbrella project for maintaining the state and behaviour
of IoT appliances using DigitalTwins.

__The engine consists of multiple modules which takes care of:__
* Appliance Provision.
* Appliance Telemetry.
* Infrastructure health checks
* Service routing
* Security

***

### __*EngineGateway*__

This module takes care of all incoming request authorization, validation & context based routing to 
appropriate API.

***

### __*EngineDataStore*__

This module takes care of all interactions with persistence layer, in this case all Digital-twins are 
stored in MongoDB.

***
