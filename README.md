# Experiment-15
## The study of the Selenium Web Testing Tool reveals its effectiveness in automating web applications for testing purposes across different browsers and platforms.
What is Selenium? 
JavaScript framework that runs in your web browser Works anywhere JavaScript is supported Hooks for many other languages Java, Ruby, Python Can simulate a user navigating through pages and then assert for specific marks on the pages All you need to really know is HTML to start using it right away
Selenium IDE 
Selenium Integrated Development Environment (IDE) is a Firefox plugin that lets testers to record their actions as they follow the workflow that they need to test.
 It provides a Graphical User Interface for recording user actions using Firefox which is used to learn and use Selenium, but it can only be used with Firefox browser as other browsers are not supported. 
However, the recorded scripts can be converted into various programming languages supported by Selenium and the scripts can be executed on other browsers as well. 
Selenium-IDEDownload 

Step 1 − Launch Firefox and navigate to the following URL - http://seleniumhq.org/download/. Under the Selenium IDE section, click on the link that shows the current version number as shown below.
<img width="1034" height="365" alt="image" src="https://github.com/user-attachments/assets/e9e1bcbc-6df8-4b67-8b38-7df69629ebad" />

Step 2 − Firefox add-ons notifier pops up with allow and disallow options. User has to allow the installation
<img width="642" height="295" alt="image" src="https://github.com/user-attachments/assets/606f3ed1-9039-4d6e-9a0f-564d425e3eb5" />

Step 3 − The add-ons installer warns the user about untrusted add-ons. Click 'Install Now'.
<img width="847" height="558" alt="image" src="https://github.com/user-attachments/assets/fa55f0f1-cdae-4763-a9e2-2992eabc28cb" />
Step 4 − The Selenium IDE can now be accessed by navigating to Tools >>Selenium IDE.
<img width="764" height="353" alt="image" src="https://github.com/user-attachments/assets/f6f45e22-c537-4ec6-bbbc-bca27ff45319" />

Step 5 − The Selenium IDE can also be accessed directly from the quick access menu bar as shown below.

<img width="484" height="180" alt="image" src="https://github.com/user-attachments/assets/af76ca12-eb32-4d10-8197-eeb4cbb8d366" />

Selenium IDE Features This section deals with the features available in Selenium IDE. The following image shows the features of Selenium IDE with the help of a simple tool-tip.
<img width="789" height="552" alt="image" src="https://github.com/user-attachments/assets/bd06a92a-d88d-4692-a066-b4037ef9cc63" />

<img width="1034" height="1251" alt="image" src="https://github.com/user-attachments/assets/f48a5d7c-7962-4b62-8349-d03dd1257ee1" />

Creating Selenium IDE Tests This section deals with how to create IDE tests using recording feature. The following steps are involved in creating Selenium tests using IDE – 

	Recording and adding commands in a test 

	Saving the recorded test 

	Saving the test suite 

	Executing the recorded test 

Recording and Adding Commands in a Test 
We will use www.ncalculators.com to demonstrate the features of Selenium. 
Step 1 − Launch the Firefox browser and navigate to the website - https://www.ncalculators.com/ 

Step 2 − Open Selenium IDE from the Tools menu and press the record button that is on the top- right corner.
<img width="895" height="452" alt="image" src="https://github.com/user-attachments/assets/ff83ef64-e6b6-4a58-98ee-345bb18a612a" />

Step 3 − Navigate to "Math Calculator" >> "Percent Calculator >> enter "10" as number1 and 50 as number2 and click "calculate".
<img width="1034" height="361" alt="image" src="https://github.com/user-attachments/assets/3162afaa-2e77-474e-b855-d28f19ef8d99" />

Step 4 − User can then insert a checkpoint by right clicking on the webelement and select "Show all available commands" >> select "assert text css=b 5"
<img width="1034" height="540" alt="image" src="https://github.com/user-attachments/assets/2174d3f3-7a51-4db0-b581-eec5a2bf912d" />

Step 5 − The recorded script is generated and the script is displayed as shown below
<img width="1034" height="571" alt="image" src="https://github.com/user-attachments/assets/373df7a8-6e24-44da-89f4-543014f11cd4" />

SavingtheRecordedTest Step 1 − Save the Test Case by navigating to "File" >> "Save Test" and save the file in the location of your choice. The file is saved as .HTML as default. The test can also be saved with an extension htm, shtml, and xhtml.
<img width="1034" height="489" alt="image" src="https://github.com/user-attachments/assets/681ff894-dd29-4e12-bc5d-169e4a3cae5f" />

SavingtheTest Suite A test suite is a collection of tests that can be executed as a single entity. 
Step 1 − Create a test suite by navigating to "File" >> "New Test Suite" as shown below.
<img width="1034" height="530" alt="image" src="https://github.com/user-attachments/assets/e672010e-887e-4858-ad88-bd15ed0b8743" />

Step 2 − The tests can be recorded one by one by choosing the option "New Test Case" from the "File" Menu.
Step 3 − The individual tests are saved with a name along with saving a "Test Suite".
<img width="1034" height="491" alt="image" src="https://github.com/user-attachments/assets/e04cc8fc-710a-4173-83d3-655e66853aa3" />

Executing the Recorded Test 
The recorded scripts can then be executed either by clicking "Play entire suite" or "Play current test" button in the toolbar. 

Step 1 − The Run status can be seen in the status pane that displays the number of tests passed and failed. 

Step 2 − Once a step is executed, the user can see the result in the "Log" Pane. 

Step 3 − After executing each step, the background of the test step turns "Green" if passed and "Red" if failed as shown below.
<img width="1034" height="569" alt="image" src="https://github.com/user-attachments/assets/c7c76c0e-e1ec-4b65-a83e-5766e4161021" />

This section deals with debugging the Selenium IDE script.
Debugging is the process of finding and fixing errors in the test script. It is a common step in any script development.
To make the process more robust, we can make use a plugin "Power Debugger" for Selenium IDE. Step 1 − To install Power Debugger for Selenium IDE, navigate to https://addons.mozilla.org/en- US/firefox/addon/power-debugger-selenium-ide/ and click "Add to Firefox" as shown below.
<img width="1034" height="385" alt="image" src="https://github.com/user-attachments/assets/442968e8-703d-47b7-ac46-a9318a4c6e18" />

Step 2 − Now launch 'Selenium IDE' and you will notice a new icon, "Pause on Fail" on recording toolbar as shown below. Click it to turn it ON. Upon clicking again, it
<img width="1034" height="510" alt="image" src="https://github.com/user-attachments/assets/69f0dd09-4f79-4a7e-be12-45de2b72181b" />

Step 3 − Users can turn "pause on fail" on or off any time even when the test is running. 

Step 4 − Once the test case pauses due to a failed step, you can use the resume/step buttons to continue the test execution. The execution will NOT be paused if the failure is on the last command of any test case. 

Step 5 − We can also use breakpoints to understand what exactly happens during the step. To insert a breakpoint on a particular step, "Right Click" and select "Toggle Breakpoint" from the context- sensitive menu.
<img width="1034" height="753" alt="image" src="https://github.com/user-attachments/assets/bcd482f7-7ded-4007-946d-e6abfea1e659" />

Step 6 − Upon inserting the breakpoint, the particular step is displayed with a pause icon as shown below.
<img width="1034" height="645" alt="image" src="https://github.com/user-attachments/assets/133c58cb-821f-4b1a-a339-8702e85d06b9" />

Step 7 − When we execute the script, the script execution is paused where the breakpoint is inserted. This will help the user to evaluate the value/presence of an element when the execution is inprogress.
<img width="1034" height="596" alt="image" src="https://github.com/user-attachments/assets/27fd918f-ea8c-4a97-bc0e-6dbe817f359d" />

Inserting Verification Points 

This section describes how to insert verification points in Selenium IDE. 
The test cases that we develop also need to check the properties of a web page. It requires assert and verify commands. There are two ways to insert verification points into the script. 
To insert a verification point in recording mode, "Right click" on the element and choose "Show all Available Commands" as shown below.
<img width="1034" height="602" alt="image" src="https://github.com/user-attachments/assets/16057c81-febf-44a4-8047-53d9b95cc8c4" />

We can also insert a command by performing a "Right-Click" and choosing "Insert New Command".
<img width="1034" height="639" alt="image" src="https://github.com/user-attachments/assets/ff471ce2-74be-4702-837d-06afc2e776fa" />

After inserting a new command, click 'Command' dropdown and select appropriate verification point from the available list of commands as shown below.
<img width="1034" height="373" alt="image" src="https://github.com/user-attachments/assets/b5bc6f32-671b-43ae-a719-3802eaef8636" />

Given below are the mostly used verification commands that help us check if a particular step has passed or failed. 
• verifyElementPresent 
• assertElementPresent
 • verifyElementNotPresent 
• assertElementNotPresent
 • verifyText
 • assertText
 • verifyAttribute 
• assertAttribute 
• verifyChecked 
• assertChecked 
• verifyAlert
 • • • assertAlert
 verifyTitle a
ssertTitle 
Synchronization Points 
During script execution, the application might respond based on server load, hence it is required for the application and script to be in sync. Given below are few a commands that we can use to ensure that the script and application are in sync. 
	waitForAlertNotPresent
	waitForAlertPresent 
	waitForElementPresent 
	waitForElementNotPresent
	waitForTextPresent 
	waitForTextNotPresent
	waitForPageToLoad 
	waitForFrameToLoad 
Selenium Pattern Matching 
□ This section deals with how to work with regular expressions using IDE. 
Like locators, patterns are a type of parameter frequently used by Selenium. It allows users to describe patterns with the help of special characters. Many a time, the text that we would like to verify are dynamic; in that case, pattern matching is very useful.
 Pattern matching is used with all the verification point commands - verifyTextPresent, verifyTitle, verifyAlert, assertConfirmation, verifyText, and verifyPrompt. 
There are three ways to define a pattern – 
	Globbing Globbing 
	regular expressions, and 
	exact patterns. 
Most techies who have used file matching patterns in Linux or Windows while searching for a certain file type like *.doc or *.jpg. would be familiar with term "globbing" Globbing in Selenium supports only three special characters: *, ?, and [ ]. 
• * − matches any number of characters. 
• ? − matches a single character.
□ [ ] − called a character class, lets you match any single character found within the brackets. [0- 9] matches any digit. 
To specify a glob in a Selenium command, prefix the pattern with the keyword 'glob:'. For example, if you would like to search for the texts "tax year 2013" or "tax year 2014", then you can use the golb "tax year *" as shown below.
 However the usage of "glob:" is optional while specifying a text pattern because globbing patterns are the default in Selenium.
<img width="693" height="86" alt="image" src="https://github.com/user-attachments/assets/c8d5d422-7d47-49a4-ad28-317e3f628c93" />


ExactPatterns Patterns with the prefix 'exact:' will match the given text as it is. Let us say, the user wants an exact match with the value string, i.e., without the glob operator doing its work, one can use the 'exact' pattern as shown below. In this example the operator '*' will work as a normal character rather than apattern- matching wildcard character.
<img width="714" height="92" alt="image" src="https://github.com/user-attachments/assets/ed0b8f53-4586-4213-a62b-18e25d4b6263" />


Regular Expressions 
Regular expressions are the most useful among the pattern matching techniques available. Selenium supports the complete set of regular expression patterns that Javascript supports. Hence the users are no longer limited by *, ? and [] globbing patterns.
 To use RegEx patterns, we need to prefix with either "regexp:" or "regexpi:". The prefix "regexpi" is case- insensitive. The glob: and the exact: patterns are the subsets of the Regular Expression patterns. Everything that is done with glob: or exact: can be accomplished with the help of RegExp. 
Example For example, the following will test if an input field with the id 'name' contains the string 'tax year', 'Tax Year', or 'tax Year'.
<img width="689" height="102" alt="image" src="https://github.com/user-attachments/assets/5918f115-68fc-4238-a940-f580847274c9" />


Selenium User Extensions The Java script that allows users to customize or add new functionality. 
It is easy to extend Selenium IDE by adding customized actions, assertions, and locator-strategies. It is done with the help of JavaScript by adding methods to the Selenium object prototype. On startup, Selenium will automatically look through the methods on these prototypes, using name patterns to recognize which ones are actions, assertions, and locators.
 Let us add a 'while' Loop in Selenium IDE with the help of JavaScript. 
Step 1 − To add the js file, first navigate to https://github.com/darrenderidder/sideflow/blob/master/sideflow.js and copy the script and place save it as
<img width="1034" height="594" alt="image" src="https://github.com/user-attachments/assets/a692f050-7de2-40b2-b987-e98c87d2690a" />

<img width="1034" height="594" alt="image" src="https://github.com/user-attachments/assets/7d78f329-895c-4190-824b-7933a65484ef" />

Step 3 − Click the 'Browse' button under 'Selenium Core Extensions' area and point to the js file that we have saved in Step 1.

Step 4 − Restart Selenium IDE. 

Step 5 − Now you will have access to a few more commands such as "Label", "While" etc. 

Step 6 − Now we will be able to create a While loop within Selenium IDE and it will execute as shown below.
<img width="1034" height="508" alt="image" src="https://github.com/user-attachments/assets/152dd24d-7cd6-46ed-b60d-86fba7d73c6b" />

# Result:
Thus, the study of selenium web testing tool is conducted and the results were noted. 
