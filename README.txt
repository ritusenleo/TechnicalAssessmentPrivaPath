Configuration:

Configuration file path: TechicalTest_Map_Automation\Configuration\Config.properties
url =https://www.google.com/maps
browser =chrome

Please set appropriate browser in the config file before running the tests. 
Kindly note that the solution is tested in Chrome but not tested in Firefox due to an environment issue 
in my development environment.


How to Run Tests:

Run Test in Eclipse Version: 2020-06 (4.16.0):

1.	Unzip attached TechicalTest_Map_Automation.zip
2.	Launch Eclipse IDE (Version: 2020-06 (4.16.0)) , select ‘Import’ from ‘File’ menu 
3.	In the ‘Import’ dialog, expand the ‘General’ folder. Select ‘Existing’ Projects into Workspace’ and click ‘Next’
4.	It will display the ‘Import Projects’ dialog box. Choose ‘select archive file’ option and click ‘Browse’
5.	Navigate to the folder of the exported file. Select the file and click ‘Open’
6.	In the ‘Import Projects’ dialog, ensure that browsed path is displayed. Click ‘Finish’
7.	Ensure that the imported project is displayed in the Eclipse IDE.
8.      Select the project and build it once.
9.	The Solution can be run in two ways: 
     A. JUNIT TEST:
      i.   Go to '/TechicalTest_Map_Automation/src/test/java/runner/TestRunner.java' 
      ii.  Double click and open the file
      iii. Right Click and Run as Junit Test
     
     B.	CUCUMBER FEATURE:
	  
      i.   Go to '/TechicalTest_Map_Automation/src/main/resources/feature/Map.feature'
      ii.  Double click and open the file
      iii. Right Click and Run as Cucumber feature

10. Report will be generated under '/TechicalTest_Map_Automation/target/reports/extentReport.html'  
    [Refresh 'target' folder before opening the report folder]

 

