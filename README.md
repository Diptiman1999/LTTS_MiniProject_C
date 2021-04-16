# Library management System
![Library](https://github.com/Diptiman1999/LTTS_MiniProject_C/blob/master/1_Requirements/library.jpg)


|Build| Code Quality | Unity | Git Inspector |
|-----|--------------|-------|---------------|
|[![Build-Windows](https://github.com/Diptiman1999/LTTS_MiniProject_C/actions/workflows/build_windows.yml/badge.svg)](https://github.com/Diptiman1999/LTTS_MiniProject_C/actions/workflows/build_windows.yml) [![Build-Linux](https://github.com/Diptiman1999/LTTS_MiniProject_C/actions/workflows/build_linux.yml/badge.svg)](https://github.com/Diptiman1999/LTTS_MiniProject_C/actions/workflows/build_linux.yml) | [![Code Quality - Static Code - Cppcheck](https://github.com/Diptiman1999/LTTS_MiniProject_C/actions/workflows/cppcheck.yml/badge.svg)](https://github.com/Diptiman1999/LTTS_MiniProject_C/actions/workflows/cppcheck.yml) [![Code Quality Dynamic Analysis](https://github.com/Diptiman1999/LTTS_MiniProject_C/actions/workflows/dynamic_analysis.yml/badge.svg)](https://github.com/Diptiman1999/LTTS_MiniProject_C/actions/workflows/dynamic_analysis.yml) [![CI-Coverage](https://github.com/Diptiman1999/LTTS_MiniProject_C/actions/workflows/code_coverage.yml/badge.svg)](https://github.com/Diptiman1999/LTTS_MiniProject_C/actions/workflows/code_coverage.yml)| [![Unity](https://github.com/Diptiman1999/LTTS_MiniProject_C/actions/workflows/unity.yml/badge.svg)](https://github.com/Diptiman1999/LTTS_MiniProject_C/actions/workflows/unity.yml)|[![Contribution Check - Git Inspector](https://github.com/Diptiman1999/LTTS_MiniProject_C/actions/workflows/git_inspector.yml/badge.svg)](https://github.com/Diptiman1999/LTTS_MiniProject_C/actions/workflows/git_inspector.yml) |



## Folder Structure
Folder             | Description
-------------------| -----------------------------------------
`1_Requirements`   | Documents detailing requirements and research
`2_Architecture`         | Documents specifying design details
`3_Implementation` | All code and documentation
`4_TestPlanAndOutput`      | Documents with test plans and procedures

## Contributors List and Summary

PS No. |  Name   |    Features    | Issuess Raised |Issues Resolved|No Test Cases|Test Case Pass
-------|---------|----------------|----------------|---------------|-------------|--------------
264725 | Diptiman Senapati  | F1,F2,F3,F4,f5,F6,F7,F8    |      |    | 10   |10 


Feature ID | Features
-----------|---------
 F1 | Added books details to file
 F2 | Delete book according to their Id
 F3 | Search Book according to their name
 F4 | Display Books
 F5 | Add days to issued date
 F6 | Update Credentials like username and password
 F7 | Check for valid name
 F8 | Check for valid date
 
The idea and logic was used from [Library Management](https://aticleworld.com/library-management-system-project-in-c/). I changed it to multifile programming, added error enum values to avoid confusion, added new feature to add 30 days to issued date so to know the return date and made the code comparatively easier to understand.  
 
## Challenges faced and How was it overcomed
| No. | Challenge | Solution|
|-----|-----------|---------|
| 1 |Writing test cases was difficult because the program usually takes user input | All the user input was stored in test_input.txt file and then run the test cases |
| 2 |Date issues was generated while calculating return date | It was solved using date addition algorithm |
| 3 |After Deleting the book no message for deletion status was shown | There was an error which was returning SUCCESS directly without printing the message, so I changed the return status after only displaying the message |
| 4 |Search result was not showing while search is completed | There was error generating automatically which the compiler couldn't find it. it was solved using gdb |



## Resources Used
* [Library Management](https://aticleworld.com/library-management-system-project-in-c/)
* [Project Report of Library Management System ](https://www.daitm.org.in/wp-content/uploads/2019/04/Gr.-06library-project-report.p)
* [File using C](https://www.programiz.com/c-programming/c-file-input-output)
 
 
 
 
