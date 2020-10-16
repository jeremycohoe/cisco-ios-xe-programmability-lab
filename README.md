# Welcome to the Cisco IOS XE Programmablity Lab

### Version 17.3
Looking for the previous version of the lab? Go to [README-17.2.md](https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab/blob/master/README-17.2.md).

### Lab Topology
To access the lab, you will need to use a Remote Desktop connection to the specific jump host.  The jump host is used to allow remotes access into all lab devices within the given pod envrionment.

Please refer to the IOS XE Programambility Lab Acess Sheet for specific pod access instructions and details

![](./imgs/lab_topology.png)

The services, features, and technologies that are enabled with the lab envrionment are shown below:

![](./imgs/pod_details.png)

The modules below enable IOS XE Device Lifecycle Management:

![](./imgs/device_lifecycle.png)

## Modules

### [Day 0 - Guest Shell, Guest Share](https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-day0-guestshell-guestshare)
The Guestshell Linux container within IOS XE is a CentOS 8 based operating system available that is integrated and available for programmability and automation use cases. In this simple example the container will be enabled and the shared folder between IOS XE and the Guest Shell will be explored.

### [Day 1 - API Role Based Access Control](http://10.85.134.66/day1apirbac/README.html)
This module has not yet been made public - Cisco internal access only.

### [Day 1 - Tooling - pyATS](https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-module-6-mdt)
pyATS

### [Day 2 - gRPC Model Driven Telemetry + TLS]()
This module relies on SSL/TLS crypto certificate, so it is recommended to complete the DayN/gNOI cert.proto module prior, speciffically just the 2 steps the detail generating and loading certificates into IOS XE with the gnoi_cert tooling.

### [Day N - gNOI cert.proto Certificate Management API](https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-module-5-gnmi)
Details




