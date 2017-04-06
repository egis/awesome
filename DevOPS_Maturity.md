# DevOps Maturity
## Development

|Capability|Level 1|Level 2|Level 3|  
|----------|-----------|------|----|  
|**Plan**|Issue tracking|Commits are traceable to issues||
|**Code**|VCS|DVCS|Code Reviews|
|**Code Analysis**|Linting|Code Reviews|Static Analysis|
|**Build**|1 step build|1 step build on dev workstation|Offline build|
|**Test**|Automated Tests|Test results per PR|Epemeral testing instance per PR|
|**Release**|Canary releases|Rolling deployment|Scheduled timed|
|**Deploy**|1 step deploy|staging / canaries|continuos deployment|
|**Run**|Run on dev dev|Run offline|Cheap environment e.g. docker|
|**Docs**|* Getting Started<br>* Javadocs|High Level|Production Support/Low Level|

## Infrastructure / Operations

|Capability|Level 1|Level 2|Level 3|  
|----------|-----------|------|----|  
|**Configure**|Infrastructure as code|Tested configs|continous config deployment|
|**Monitor**|Up/Down|Metrics/Errors|Anomaly Detection/Event correlation|
|**Scale**|Horizinal|Vertcal|Automated|
|**HA**|Master/Slave|Master-Master|Resilent to service outages|
|**DR**|Backups|Offsite DR|Tested DR|
|**Security**||||
|**Performance**||||
|**Docs**||||

   
![](http://www.jamesbowman.me/post/cdlandscape/ContinuousDeliveryToolLandscape.jpeg)
From [http://www.jamesbowman.me/post/continuous-delivery-tool-landscape/](http://www.jamesbowman.me/post/continuous-delivery-tool-landscape/)
