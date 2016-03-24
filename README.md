# DocViewer_MVC_Assignment

System Requirements:

Visual studio 2015.

Windows 7 or above


Configuration Steps:

Following are the steps for application configuration.
* Download code form Github and unzip it and find folder named “AssignmentDocViewer”.This folder contains complete source code along with solution file.
* Download “GroupDocs.Viewer.dll” from http://groupdocs.com/Community/files/8/.net-libraries/groupdocs_viewer_for_.net/entry11018.aspx
* Double click the solution file named ‘AssignmentDocViewer.sln’ under folder “AssignmentDocViewer” or launch visual studio 2015 and open solution in it by clicking on File -> Open -> Project/Solution. Then navigate to the solution file and open it.
* In solution explorer window expand project named “AssignmentDocViewer”. Then go to references and check whether reference of “GroupDocs.Viewer” is missing or not. 
* If solution contains reference of above stated DLL then skip next step.
* If reference is missing for GroupDocs.Viewer DLL then add DLL reference with following steps
  * Right click on references and click “Add Reference”. 
  * Then click on Browse in left panel of “Reference Manager – AssignmentDocViewer” window.
  * Then click on Browse button and choose “GroupDocs.Viewer.dll” file from Reference folder (will be available in unzipped directory).
* Open Web.config file and navigate to <appSettings> section. 
  * Replace the value of key “directoryPath” with path of directory according to your PC (this is the path of that directory which contains document).
  * Replace the value of key “docName” with file name according to your PC (this is the file name along with its extension which you want to view). 
* Save all your changes and run the solution to see its output.
