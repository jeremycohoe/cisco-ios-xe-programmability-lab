# Welcome to the Cisco IOS XE Programmablity Lab

### Version 17.6 SEVT
Looking for the previous version of the lab?

[https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab/blob/master/README-17.5.md](https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab/blob/master/README-17.5.md)

### Lab Topology
To access the lab, you will need to use a Remote Desktop connection to the specific jump host.  The jump host is used to allow remotes access into all lab devices within the given pod envrionment.

Please refer to the IOS XE Programambility Lab Acess Sheet for specific pod access instructions and details

![](./imgs/lab_topology.png)

The services, features, and technologies that are enabled with the lab envrionment are shown below:

![](./imgs/pod_details.png)

The modules below enable IOS XE Device Lifecycle Management:

![](./imgs/device_lifecycle.png)

## Modules

# Day 0 - NETCONF from Guest Shell

The NETCONF interface on IOS XE is now accessible from within the Guest Shell. No interface configuration or connectivity is required and this can be used at Day 0. The ncclient python library can be used to connect to the NETCONF interface when there is no IP connectivity, similar to the Python CLI modules and API. This can be used by ZTP at Day 0 to programmatically configure the device using either CLI or YANG API calls


[https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-day0-guestshell-guestshare](https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-day0-guestshell-guestshare)

# Day 1 - gNOI OS.proto

gNOI defines a set of gRPC-based microservices for executing operational commands on network devices. OS Install, Activate, and Verification are defined and addressed as part of the "OS.proto" specification
https://github.com/openconfig/gnoi/blob/master/os/os.proto

The OS service provides an interface for OS installation on a Target. The Client progresses through 3 RPCs:
1) Installation - provide the Target with the OS package.
2) Activation - activate an installed OS package.
3) Verification – verify the installed and activated version


[https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-module-5-gnmi](https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-module-5-gnmi)


# Day 2 - gRPC Model Driven Telemetry with FQDN

gRPC Dial-Out Model Driven Telemetry supports using a DNS based named receiver instead of an IP address. There are many advantages of using DNS instead of IP addresses and now the streaming telemetry network services are included.

[https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-module-6-mdt](https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-module-6-mdt)

# Day N and Tooling - YANG Suite with RESTCONF, YANG Suite with gNMI

YANG Suite was released into Github in early 2021 and now there are additional plugins being added to the solution. The RESTCONF plugin uses the OpenAPI Swagger UI to more easily work with the API and YANG data models. The gNMI plugin is a full featured gNMI client supporting GET, SET, and Subscribe operations.

[https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-YANGSuite](https://github.com/jeremycohoe/cisco-ios-xe-programmability-lab-YANGSuite)






