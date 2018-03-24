Test Automation Project
Simple Java test automation framework to cover a purchase request in "Konakart" website

Concepts Included
Page Object Modeling
Data Driven Framework

Tools
Gradle
TestNG
Selenium Webdriver

Requirements
In order to utilise this project you need to have the following installed locally:
1-Eclips
2-Google Chrome Installed 
3-Java 1.8

To run all test cases, use the "Main" class.

Reporting
Reports for each test case is generated through TestNG automatically


Configuration And Setup
Eclipse
To get it working on a regular Eclipse 4.2.1 or later, follow these steps:
1. Using the "Eclipse Marketplace" settings panel under the 
   Eclipse "Help" menu, install the Gradle tooling 
   functionality.  You can do it through the "Install New
   Software" menu, but it isn't recommended.  If Market is
   missing from your Eclipse, then add the repo:
   http://download.eclipse.org/releases/juno
   and then install the "market" and restart Eclipse.
2. Download the .zip archive of this GitHub project 
   distribution and unzip it to your workspace.  An example:
   "C:\Eclipse32\workspace\WebDriverTestingTemplate\" .
3. Use the Eclipse "Import" function from the Eclipse "File
   menu" to import a "Project" of type "Gradle".
4. Browse using the import wizard to your projects "root" 
   directory.  Then click the "Build model" button.
5. Check all checkboxes .  You could also choose to add all 
   to your "working set" if you like but it isn't required.
6. Rebuild the dependencies by right clicking on the project
   and then choose Gradle-->Refresh All Dependencies
7. Right click on Main class and choose "Run As-->TestNG

