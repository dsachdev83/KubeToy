# KubeToy
## v1.7.0
### Tested with ICP versions: 2.1.0 - 3.1.0

A simple Node.js application that deploys to IBM Cloud Private.  It is used to help 
explore the functionality of Kubernetes.  This toy application has a user interface 
which you can:

* write messages to the log (stdout / stderr)
* intentionally crash the application to view auto repair
* toggle a liveness probe and monitor Kubernetes behavior  
* read config maps and secrets from environment vars and files
* interact with Cloud Object Storage

**[Playing with the logs](documentation/Logs.md)** 
Use the app to write to the logs, then view the logs in the UI and via Kibana.

**[Crash the app](documentation/Crash.md)**
Intentionally crash the application and watch it self heal.

**[ConfigMaps and Secrets](documentation/Config.md)** Explore configuration options for apps 
deployed to ICP.

**[Network](documentation/Network.md)** Ping and do DNS lookups from the server side app.  You can verify
visibilty of related ClusterIP services.

**[Ingress](documentation/Ingress.md)** Show how you can, with the help of nginx you can set up an
ingress for this app, with your own custom certs providing SSL protection.






