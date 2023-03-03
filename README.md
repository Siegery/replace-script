# replace-script
A script that searches a directory and all its contents for a specific string, and replaceses it with another string.
This repository also includes a built in test command

Replace Script:
  To use the replace script call: {replace \<path> \<old pattern> \<new pattern>}.
    This should replace all occurences of the old pattern in all files beneth the one you specified, with the new pattern.
 
Replace Test Script:
  To create a test enviorment call: run-test setup
    This will create a chain of containted directories with multiple files included as test subjects.
    It is recommended that you then try: {replace test DevOps WebApp}.
      And then check to see if it works
  
  Once you are done testing call: {run-test teardown}.
    This will clean up all the test files

NOTE: Script does not work with spaceses
NOTE: It might be nessisary for users to first make the scripts executable before running them (chmod 700 replace)
