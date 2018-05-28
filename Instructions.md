Step1:
Search for Advanced system settings in windows search and then click on "View Advanced System Settings"

Step2: 
Select "Environment Variables..." option.

Step3:
Note down the username, select "Path" variable and then click on "Edit..." button

Step4: 
Then click on "New" button and add the following paths to it. 

Path codes:

C:\Users\"USERNAME"\Anaconda3
C:\Users\"USERNAME"\Anaconda3\Library\mingw-w64\bin
C:\Users\"USERNAME"\Anaconda3\Library\usr\bin
C:\Users\"USERNAME"\Anaconda3\Library\bin
C:\Users\"USERNAME"\Anaconda3\Scripts

Note: Replace the "USERNAME" with the username of yours in your system.

Then you can go to the windows command prompt / Windows power shell and type python/ jupyter notebook. They should work now.
