# BlockChainPOCApplication
This is demo application of Blockchain that uses Corda Plateform. This is V2 that includes multiple counterparties (logic is present) with attachment functionlity. 

This version still allow only one counter party selection from UI but can be easily changed by adding 'multiple' attribute in HTML file.

#Prerequisites
1. Java 1.8.x(http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) for later must be installed on system.
2. JAVA_HOME environment must be set with Java 1.8.x (or any later version installed on system).
3. PATH environment variable must include Java 1.8.x (or any later version installed on system).
4. Chrome browser to run web template.

#Starting up application
1. Download the application from github.
2. Start command prompt and navigate extracted folder where runnodes.bat file is placed.
3. run - > 

		runnodes.bat.
			
4. If Java version are correctly installed and environment variables are set correctly the below message would be displayed.
			
			<<location>>>runnodes.bat
			Starting nodes in <<location>>
			Starting corda.jar in <<location>>\BankofAmerica on debug port 5005
			Starting corda-webserver.jar in <<location>>\BankofAmerica on debug port 5006
			Starting corda.jar in <<location>>\Controller on debug port 5007
			Starting corda.jar in <<location>>\Genpact on debug port 5008
			Starting corda-webserver.jar in <<location>>\Genpact on debug port 5009
			Starting corda.jar in <<location>>\JPMorganChase on debug port 5010
			Starting corda-webserver.jar in <<location>>\JPMorganChase on debug port 5011			
			Started 7 processes
			Finished starting nodes	

5.  It will open up 7 windows -

	a) Windows for webserver, one for each node (total 3 windows).
		
	b) Windows for command line intraction with Corda. (Total 4 windows - 1 for each party and 1 for Controller (notary)).
		
6.  Urls for templates -

		JPMorganChase - http://localhost:10007/web/template/		
		BankofAmerica - http://localhost:10010/web/template/
		Genpact - http://localhost:10013/web/template/		

