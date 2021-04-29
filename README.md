# fault-profile-tool-examples

Example Jupyter notebooks for use with https://github.com/andy22b/fault-profile-tool

This readme aims to minimize use of the terminal. 
Anyone familiar with Anaconda in the terminal should be able to implement a few useful shortcuts to the workflow.

# Requirements
The code should run on any of Windows, OS X or Linux, through Anaconda3. 
Anaconda3 can be downloaded from https://www.anaconda.com/products/individual

# Installation
1. Download the example repository (not the main code repo) from GitHub, using the "Download Zip" option from the "Code" dropdown. Unzip it.

![image](https://user-images.githubusercontent.com/16937322/116341055-543d4780-a834-11eb-810d-c494b7ac3f2c.png)

2. Open Anaconda Navigator on your computer (e.g. Start menu on Windows). If you have an option, choose a 64-bit edition of Anaconda3.
3. Navigate to the environments tab, using the button near the top left of the Anaconda Navigator.

![image](https://user-images.githubusercontent.com/16937322/116341449-0e34b380-a835-11eb-8858-714b8e780a5a.png)

4. Click the "Import" button at the bottom of the Anaconda Navigator window.

![image](https://user-images.githubusercontent.com/16937322/116341782-a0d55280-a835-11eb-97a0-ba50b6f11689.png)

5. A window like the one shown below will appear. Click the folder icon to browse and select the environment.yml file in the folder that you downloaded and unzipped in step 1. 

![image](https://user-images.githubusercontent.com/16937322/116342182-4d173900-a836-11eb-8908-d2ef5fcb8ea2.png)

6. Click "Import" and wait for the relevant modules to install. NOTE that this may take several minutes... Be patient.
7. Once installation has finished, a new `fault-profile-tool` environment should appear in the list, with a play button (triangle) next to it:

![image](https://user-images.githubusercontent.com/16937322/116504787-460f2a00-a90d-11eb-8c96-6d2ba99d3dd5.png)

# Launching the software
Now the software is installed, you launch it as follow.
1. If Anaconda Navigator is not open, open it and navigate to the environments tab (steps 2 and 3 of installation).
2. Click the play button (triangle) next to the `fault-profile-tool` environment and select `Open with Jupyter Notebook`.

![image](https://user-images.githubusercontent.com/16937322/116505000-d64d6f00-a90d-11eb-9bec-12c1c8ed6675.png)





# Updates to code
Updates to the code will unfortunately be necessary; I hope that they will become less frequent with time. To update, open a terminal using the fault-profile-tool environment in Anaconda navigator, as shown below.

![image](https://user-images.githubusercontent.com/16937322/116504551-a3ef4200-a90c-11eb-8dc8-a2aed9d56c5a.png)

In the terminal that opens, paste `git+https://github.com/andy22b/fault-profile-tool/#subdirectory=src/fault-profile-tool` and hit `Enter`. This should install the latest version of the tool. Once this is done, close that terminal and open a new notebook.

