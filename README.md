# Welcome to the Cisco IOS XE Programmablity Lab

### Version 17.3
Looking for the previous version of the lab?

[https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab/blob/master/README-17.2.md](https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab/blob/master/README-17.2.md)

### Lab Topology
To access the lab, you will need to use a Remote Desktop connection to the specific jump host.  The jump host is used to allow remotes access into all lab devices within the given pod envrionment.

Please refer to the IOS XE Programambility Lab Acess Sheet for specific pod access instructions and details

![](./imgs/lab_topology.png)

The services, features, and technologies that are enabled with the lab envrionment are shown below:

![](./imgs/pod_details.png)

The modules below enable IOS XE Device Lifecycle Management:

![](./imgs/device_lifecycle.png)

## Modules

# Day 0 - Guest Shell, Guest Share

[https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-day0-guestshell-guestshare](https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-day0-guestshell-guestshare)

The Guestshell Linux container within IOS XE is a CentOS 8 based operating system available that is integrated and available for programmability and automation use cases. In this simple example the container will be enabled and the shared folder between IOS XE and the Guest Shell will be explored.

# Day 1 - API Role Based Access Control

[http://10.85.134.66/day1apirbac/README.html](http://10.85.134.66/day1apirbac/README.html)

This module has not yet been made public - access it interally via:

# Day 1 - Tooling - pyATS

[https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-...](https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-...)

pyATS - TBD


# Day 2 - gRPC Model Driven Telemetry + TLS

[https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-module-6-mdt](https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-module-6-mdt)

The Day 2 gRPC Model Driven Telemetry with TLS module covers gRPC telemetry being secured with TLS certificates between the IOS XE switch and the Telegraf collector, so it is sent securely over the network.

# Day N - gNOI cert.proto Certificate Management API

[https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-module-5-gnmi](https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-module-5-gnmi)

The Day N gNOI cert.proto "certificate management API" is used to install TLS certificate into IOS XE from the Linux/Ubuntu tooling machine. Once the certificates are loaded some tooling is used to validate the secure connection. gNOI cert.proto is also used in the "Day 2 gRPC-TLS" module to load the certificate to secure the telemetry connection.





