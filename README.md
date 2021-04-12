# bunnings
This is an initial commit to the Bunnings Test Automation Challenge.
The automation is done utilising the opensource jmeter tool and will need to be downloaded to execute the tests.
The test plan file and the test data file are checked in.
Test data file will need to be placed in jmeters working directory (i.e /bin folder)
simply run the following command from <jmeter installationdirectory>/bin> jmeter -n -t testPlan.jmx -l testreport.jtl
Open jmeter GUI and right click on Test Plan, navigate to Add, then Listener and then click on Aggregate Report. Provide the path to testreport.jtl file to view latest results
There is a deliberate error in the testing data for the product item "test"
