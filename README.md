# Meenakshi-NHSBSA

**About the Framework –** 

**Feature File:** 
Feature files store high-level description of scenarios, scenario outline and steps in the Gherkin language
The feature file “NHSFeature.feature”, is placed under the folder “src/test/resources/features”

**Configuration File:**
The configuration file “config.properties” is placed under the folder “src/test/java/config”. 
All user inputs and data validations are fetched from this file

**StepDefinition File:**
The step definition file “commonSteps.java” is placed under the package “src/test/java/steps”

**POM File:**
The objects, locators and corresponding reusable methods are present under the package “src/test/java/pages” with the class name “CommonPage.java”

**Utilities File:**
This package is placed under “src/test/java/Utils” and is created to separate the main driver class and configuration files and to make the code look more readable. 
The class file “Drivers.java” is used to initialize the browser driver.

**Test Runner File:**
The test runner file executes the Cucumber feature files and coordinates the steps defined in those feature files with the corresponding step definitions
This Test Runner file is under location location "src/test/java/runner/"

**Pre-requisites: Below software are required to be installed on a local machine:**

1.	Java (JDK)
2.	Eclipse IDE – If running from the IDE
   
**Running the Project: 
Make sure the pre-requisites are performed before running.**

Step 1: Open the Eclipse IDE on your local machine and open the project.

Step 2: Go to Test Runner file at location "src/test/java/runner/"

Step 3: Right-click on the Project name --> Run As --> Junit Test
