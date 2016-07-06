# Speaker Notes

#1 Title 

Questions: 
- Who of you owns a RasPi?
- Who has been developing with Java on the RasPi?

#3 Ingredients

## Hardware
* Raspberry Pi Model 3
* Developer Machine
* Sunfounder Sensor Kit
* RaspberryPi Touchscreen

## Software
* Debian based Linux OS
* pre-installed Java 8
* Eclipse IDE
* bndtools OSGi development environment
* enRoute OSGi Templates

## Infrastructure
* GitHub as SCM
* Continuous builds via TravisCI
* RepoManagement via jpm4j

# 4.1 / 4.2 Motivation
* Why would someone want to develop with Java

# 5.1 Technology dive

# 5.2 Technology dive
* Language improvements
* more concise language expressions
* simpler VM monitoring

# 5.3 OSGi Modularity
* devide a complex system into parts with defined interfaces
* divide and conquer is established process from complexity handling

# 5.4 OSGi Architecture
* Bundles – Bundles are the OSGi components made by the developers.
* Services – The services layer connects bundles in a dynamic way by offering a publish-find-bind model for plain old Java objects.
* Life-Cycle – The API to install, start, stop, update, and uninstall bundles.
* Modules – The layer that defines how a bundle can import and export code.
* Security – The layer that handles the security aspects.
* Execution Environment – Defines what methods and classes are available in a specific platform.

# 5.5 OSGi Nano-Service (Microservices are Mainstream ;-) [ the REAL POWER of OSGi ]
* Nano-services (only a JavaObject) should be looked upon as a software design primitive
* services are dynamic
* service registry significantly simplified application code because it handle so many common patterns.
* Configuration Admin service and the Declarative Services 
* Declarative Services makes writing a service implementation as simple as writing a POJO with a few annotations
* Configuration Admin can be used to not only configure service implementations, it can also control the life cycle

# 5.6 enRoute
* describing how to develop a Service Oriented System
* Mission
	* Profiles
	* Tool Chain
	* Documentation and Tutorials
	* Community

# 6.1 Tools
Complete tool chain for development, scm and CI, CD included

# 6.2 Eclipse 
* very flexible and customizable IDE
* writing of own plugins possible

# 6.3 Bndtools
* MANIFEST.MF is generated
* real-life/byte-code dependency management
* flexible and versatile repository management (P2, Maven, file-based, jpm4j, ...)
* immediate bundle creation after each save
* Declarative Service via Java annotations (type safe and no XML)

7.1 Raspi Setup

7.2 one-time setup
* installation of jpm and remote run agent

7.3 development
* launch remote agent and ready!

7.4 Dev PC Setup
* Eclipse and ... installation

7.5 IDEfix installer
* LIVE DEMO 

8.x Deployment
