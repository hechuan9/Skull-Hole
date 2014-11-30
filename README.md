# README #

### How do I get set up? ###

* Drag the .app to your Application folder
* Go to Application, right click on fiji.app, then "show package content"
* Go to plugins, then the "3D_View-master" is the project. Use any IDE, recommended Eclipse

### How to run it ###

* open Fiji as an application
* go to File -> import -> Image Sequence, then select the DICOM folder.
* go to plugins on the top bar.
* on the bottom of the dropdown, click into the 3D_View-master option
* should see a 3D model of the child's head
* Go to Edit -> Adjust Threshold , then adjust the threshold to show the skull

### How to edit ###

* Go to the opened plugin project, make edits to .java files.
* Make sure Maven is installed and can be used as command line tool
* After modifications, run command "mvn clean compile"
* Restart Fiji
