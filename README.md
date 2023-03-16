# Lab5_202001216
Static Analysis using mypy tool.

-> Doing the static analysis of a random git repository using the ‘mypy’ tool. 

-> The reference link of random git repository:
 https://github.com/qxf2/wtfiswronghere.git

-> The command to install mypy: python -m pip install mypy 

-> The command to find errors in the repository: python -m mypy <file_path>


### Step 1: Clone git repository that you are using as reference:
![image](https://user-images.githubusercontent.com/108628176/225574906-453a6334-70da-4ad4-b7a7-e9a7f46f21e2.png)

### Step 2: Installation of mypy tool.
![image](https://user-images.githubusercontent.com/108628176/225575258-2de67347-92f9-45d6-94b9-748923825ac7.png)

### Step 3: Static analysis of some sample files to find errors.
![image](https://user-images.githubusercontent.com/108628176/225575111-eb813bcb-01e6-4b07-b0c5-9f00fccbdc13.png)



-> In the first file(02_challenge) there is only one error[Missing positional argument in calling function] in the file as after checking the whole source file 1 error was detected.

-> In the 01_challenge, 04_challenge, 05_challenge[Synatax errors] there may be more than one error in the files as further error checking has been stopped due to the 1st detected error.

-> There are also a few files(03_challenge, 06_challenge) that do not contain any errors. 


#### Analysis of the Tool (mypy) : 
-> This tool identifies a few different types of errors like the syntax errors in most of the files.

-> It also identifies a few call-arguments errors in a few files.

-> It displays a comment which almost defines the error and is also understandable which helps us in debugging the code.
