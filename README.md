# Example of using 3 IRIS Health Community instances (EM, CD, preview)

## This is a simple docker-compose example that spins up three containers based on the 3 latest community editions of IRIS Health: 

* [IRIS Health community EXTENDED MAINTENANCE](./docker-compose.yml)
* [IRIS Health community CONTINUOUS DELIVERY](./docker-compose.yml)
* [IRIS Health community DEVELOPER PREVIEW](./docker-compose.yml)

## start/stop 

* [start.sh](./start.sh) - spins up all containers via docker-compose and 
    invokes iris/configure.sh in the iris containers
* [stop.sh](./stop.sh) - removes all containers

## configure.sh
* [iris/configure.sh](./iris/configure.sh) - configures the IRIS Health container's CSPConfigName

## IRIS Health Management Portal

With this pod, the user can access each instance's Management Portal immediately without relying on the private web server. If running on your local machine, use these URLs:
* [IRIS Health EM Management Portal](http://localhost:8004/csp/sys/UtilHome.csp)
* [IRIS Health CD Management Portal](http://localhost:8004/csp/sys/UtilHome.csp)
* [IRIS Health PREVIEW Management Portal](http://localhost:8006/csp/sys/UtilHome.csp)

## IRIS Health APIs

With this pod, the user can access each instance's Management Portal immediately without relying on the private web server. If running on your local machine, use these URLs:
### API Atelier
* [IRIS Health EM API Atelier](http://localhost:8004/api/atelier/)
* [IRIS Health CD API Atelier](http://localhost:8005/api/atelier/)
* [IRIS Health PREVIEW API Atelier](http://localhost:8006/api/atelier/)
### API Management
* [IRIS Health EM API Management](http://localhost:8004/api/mgmnt/)
* [IRIS Health CD API Management](http://localhost:8005/api/mgmnt/)
* [IRIS Health PREVIEW API Management](http://localhost:8006/api/mgmnt/)
### IRIS Health Monitor Metrics
* [IRIS Health EM METRICS](http://localhost:8004/api/monitor/metrics)
* [IRIS Health CD METRICS](http://localhost:8005/api/monitor/metrics)
* [IRIS Health PREVIEW METRICS](http://localhost:8006/api/monitor/metrics)
### LICENSES
* [License Key EM](http://localhost:8004/csp/sys/mgr/%25CSP.UI.Portal.License.Key.zen)
* [License Key CD](http://localhost:8005/csp/sys/mgr/%25CSP.UI.Portal.License.Key.zen)
* [License Key PREVIEW](http://localhost:8006/csp/sys/mgr/%25CSP.UI.Portal.License.Key.zen)
### Management Portal
* [Management Portal EM](http://localhost:8004/csp/sys/UtilHome.csp)
* [Management Portal CD](http://localhost:8005/csp/sys/UtilHome.csp)
* [Management Portal PREVIEW](http://localhost:8006/csp/sys/UtilHome.csp)