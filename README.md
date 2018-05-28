# Environment variables setup for Anaconda in windows10
List of Environment Variables need to be added to the path to access packages in anaconda using windows command prompt or windows power shell

<b>Step1:</b>
<br>Search for Advanced system settings in windows search and then click on "View Advanced System Settings"</br>


<p align="left">
  <img width="489" height="776" src="https://github.com/VVRChilukoori/Environment-variables-setup-for-Anaconda-in-windows10/blob/master/img/Advanced_system_settings.JPG.jpg">
</p>


<b>Step2:</b> 
<br>Select "Environment Variables..." option.</br>

<p align= "left">
  <img width="547" height ="554" src="https://github.com/VVRChilukoori/Environment-variables-setup-for-Anaconda-in-windows10/blob/master/img/Environment_variables.jpg">
</p>


<b>Step3:</b>
<br>Note down the username, select "Path" variable and then click on "Edit..." button</br>

<p align= "left">
  <img width="749" height ="792" src="https://github.com/VVRChilukoori/Environment-variables-setup-for-Anaconda-in-windows10/blob/master/img/path.jpg">
</p>


<b>Step4:</b> 
<br>Then click on "New" button and add the following paths to it. </br>

<p align= "left">
  <img width="749" height ="788.5" src="https://github.com/VVRChilukoori/Environment-variables-setup-for-Anaconda-in-windows10/blob/master/img/Variables_for_anaconda.JPG">
</p>



<p>
<b>Path codes</b>
<br>C:\Users\"USERNAME"\Anaconda3</br>
<br>C:\Users\"USERNAME"\Anaconda3\Library\mingw-w64\bin</br>
<br>C:\Users\"USERNAME"\Anaconda3\Library\usr\bin</br>
<br>C:\Users\"USERNAME"\Anaconda3\Library\bin</br>
<br>C:\Users\"USERNAME"\Anaconda3\Scripts</br>
</p>


<b>Note:</b> Replace the "USERNAME" with the username of yours in your system.

Then you can go to the windows command prompt / Windows power shell and type python/ jupyter notebook. They should work now.
