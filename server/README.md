# neoOntology Server

This directory comprises the files necessary to build an image of a default neoOntology server.

These files include:

- The default ontologies (/owl) for building a maintenance repository as a Digital Twin.
- The default files (/obj, /dat, /xml) to track objects using neoOntologyAR
- The default files (/png, /wav, etc.) to manage other datatypes related with maintenance operations.
- The Dockerfile to build the node.js app to serve maintenance data dynamically to different services (AR, web, sensors, etc.).

In order to run the datastore in your computer, you need to run the following commands in Dock...