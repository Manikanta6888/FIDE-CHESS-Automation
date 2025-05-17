Here's a clean and structured way to present and explain how to execute this FIDE automation project in Tosca, including both the process steps and execution method using a .tsu file:

✅ Project Workflow Steps
Open FIDE Website

Navigate to the official FIDE (International Chess Federation) home page.

Verify Navigation Links

Check whether all Main Links (e.g., Ratings, News, Players) and their Sub-links are present and clickable.

Top 100 Men's Rankings (USA Players Count)

Navigate to the Top 100 Men’s Player Rankings.

Apply a filter for Country = USA.

Count all players listed under USA.

Buffer Indian Players Data & Export to Excel

Filter the same ranking list for players with Country = IND (India).

Buffer (store temporarily) the Name and Rating of these players.

Export this data to an Excel file for further analysis.

▶️ How to Execute the .tsu Test Case in Tosca
Step 1: Import the TSU File
Open Tosca Commander.

Go to Project → Import.

Select and import your Fide.tsu file.

Step 2: Run Test Case (ScratchBook Execution)
In the TestCases section:

Locate the FIDE test case.

Right-click on the test case.

Click "Run in ScratchBook" to execute the test interactively.

Step 3: Run Test Case (Execution List)
Go to the Execution section (ExecutionLists).

Locate the ExecutionList where the FIDE test case is linked.

Select the FIDE test case under the ExecutionList.

Click "Run" to execute the test in batch mode.

