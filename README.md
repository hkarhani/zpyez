# ZPyEZ

Imagine Juniper's Powerful Micro-framework PyEZ, Accessible with “sockets on steroids" 0MQ, further simplified with ZeroRPC! 

That is in a nutshell Zero-PyEZ! It is an Auto-built Container based on juniper/pyez exposing zeroRPC (zerorpc.io)..

Now you can use PyEZ from any Framework supporting zerorpc - especially crafted for NodeJS Users! 

With this thin-wrapper and connected micro-service, you can take full control of any Junos Device from NodeJS! 

You can build the container, or just pull it from the auto-built Image: 

docker -d -p 8484:8484 hkarhani/zpyez

Notebooks using both Python and NodeJS Clients are published as well. 

- Two bugs has been detected in NodeJS client (related to facts / load commands), which were not seen with Python client - still investigating the issue. 
