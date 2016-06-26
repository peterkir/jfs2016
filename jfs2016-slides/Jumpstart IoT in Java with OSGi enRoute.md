General 


page #, name, ...
eclipse oomph setup for code


01. Title, picture

02. about me

03. overview
		components Java8 (part of noobs), OSGi enRoute distro, JPM
		Raspberry Pi;
			
		
	cheap, easy

04. motivation
		why java, osgi 

05. Setup
	
	* Raspberry Pi - initial setup NOOBs https://www.raspberrypi.org/downloads/noobs/
		
	* Installation Java JPM, bnd remote agent
	
	java -version
	sudo jpm install -f biz.aQute.remote.main
	curl https://bndtools.ci.cloudbees.com/job/bnd.master/719/artifact/dist/bundles/biz.aQute.jpm.run/biz.aQute.jpm.run-3.0.0.jar >jpm.jar
	sudo java -jar jpm.jar init
		
	
		Eclipse IDE with bndtools 3.2 release

		
14. Q&A
	links and contact info

15. Order
	http://de.farnell.com/raspberry-pi/raspberrypi-modb-1gb/raspberry-pi-3-model-b/dp/2525225
	
16. Reference links	
	http://enroute.osgi.org/
	http://enroute.osgi.org/tutorial_iot/050-start.html
