![the output of the model](https://github.com/Sector61/SECTOR_61-IIITDM/blob/main/Screenshot%20from%202024-03-16%2006-51-21.png)
![the Map of the model is 92.87%](https://github.com/Sector61/SECTOR_61-IIITDM/blob/main/Screenshot%20from%202024-03-16%2006-51-37.png)
<h3>Insulator Defect Detection System for Power Transmission Lines<h3>

This project introduces an innovative approach for detecting insulator defects on power transmission lines using advanced AI technology.

<h3>Overview<h3>

The system utilizes the Jetson Nano platform mounted onto a drone for efficient aerial inspection of transmission lines. This setup enables high-resolution imaging and real-time defect identification.

<h3>Features<h3>

  1.Drone-based Inspection: Drones equipped with Jetson Nano conduct aerial inspections of transmission lines.
  
  2.AI-powered Defect Detection: Sophisticated algorithms accurately identify and classify insulator defects.
  
  3.Geofencing Technology: Precisely delineates inspection areas for comprehensive coverage.
  
  4.Web Portal Integration: Detected defects are automatically pinpointed and transmitted to a web portal for analysis.
  
  5.Efficiency and Risk Mitigation: Enhances inspection efficiency and ensures the integrity of power transmission lines by promptly detecting defects.

<h3>Implementation<h3>

The system combines AI technology, edge computing, drone-based inspection, and geofencing to facilitate proactive maintenance of power infrastructure.

[for training the dataset has been taken form](https://app.roboflow.com/simple-3btlb/insulator-inspection-kq32m/1)

[we trainned the model in the google colab and the link is provided](https://colab.research.google.com/drive/1PCnqLbyeMNyjEbXZ7ToCNfvQl6mShm6o?usp=sharing)

<h1>Steps to run locally</h1>
<h3>step1: clone the repostory:

step2:open the cloned repo in vscode 

step 3: first install the requirement files
run the code on the terminal of the vs code  : pip install -r requirements.txt

step 4: the following commands are used to run the model

to acess the web cam : python detect.py --weight best.pt --source 0

--weight = the trained weight file that we are using 
--detect python code that used to run the weight file
--source the resources that we are goign to use 

sorce 0 indicatest the web cam acess after opening the web cam place the insulators photos near the web cam , to see the identify the defects 

step 5: to access the folders that contains of the images that

run this code 
code : python detect.py --weight best.pt --source testing
'here testing is a folder name that contains the images of the insulaotres

step 6 : we can aslo use viedos for the model</h3>



