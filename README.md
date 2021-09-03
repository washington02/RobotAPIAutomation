# RobotAPIAutomation

Precondition
1. Install python
2. Using your favarite IDE e.g PhyCharm
3. To run the test cases, double click to open TC1 and right click then select Open in Terminal
4. Depending on where you saved the code type: robot TestCases/*.robot  -- this will execute all the test cases. 
5. To run single test case e.g test case 1: robot TestCaess/TC1_Get_All_Breeds.robot 
6. You can view the report on file: report.html by right click on it then Open in Browser then chrome
7. You can view the log on file: log.html by right click on it then Open in Browser then chrome

Public API - https://dog.ceo/dog-api/
API perform the following calls.
o Perform an API request to produce a list of all dog breeds - TC1_Get_All_Breeds.robot
o Using code, verify “retriever” breed is within the list - TC2_Verify_Retriver.robot
o Perform an API request to produce a list of sub-breeds for “retriever” - TC3_Sub_Breeds.robot
o Perform an API request to produce a random image / link for the sub-breed “golden” - TC4_Random_Image
