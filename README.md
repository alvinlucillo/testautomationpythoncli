**DESCRIPTION**
This is a script to automate the testing process of assignment #3.

**INSTRUCTIONS**
1. Download the files and place them all in your Python script's directory.
2. Modify main.py
* Update the absolute path for TC #9 in testcase array with the correct path: "C:\\Users\\username\\PycharmProjects\\interpol\\testcase\\tc9_absolute_path...
* Modify the script variable with your Python script to be tested
3. Open your command line interface (CLI) and change directory to the location of your script
4. Enter py main.py

**ADDITIONAL NOTES**
1. Test case success is based on the comparison of your script's output and the contents of the test result text file. A test case may fail due to difference in spacing and formatting. If that is the case, you may want to modify the test result text file.
2. PyCharm removes trailing whitespaces in source files. This may cause a test case to fail. For example, a symbol with spaces may get trimmed by the IDE. To fix this, open the Settings window (CTRL+ALT+S), type in and search for 'trailing', and look for 'Strip trailing spaces on Save for'. Choose 'None' from the dropdown.

**Sample output from the CLI:**
````
************
TEST CASE #1 - In Specs
************

SUCCESSFUL: True

************
TEST CASE #2 - In Specs
************

SUCCESSFUL: True

************
TEST CASE #3 - In Specs
************

SUCCESSFUL: True

************
TEST CASE #4 - In Specs
************

SUCCESSFUL: True

#####################################
Successful cases over total cases: 33/33
#####################################
````

Thanks to @ervicsangel for the additional test case files
