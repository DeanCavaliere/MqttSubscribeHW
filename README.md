# MqttSubscribeHW
The homework for setting up mqtt subscription. 

Most of the files/folders in this repo is unnecessary. You only need to look at mqttsetup.py

*** Please observe the file mqttsetup.py ***

[Recommended]
To copy the file into a linux OS:
  1) Generate a new file in linux --> nano "filename".py
  2) Copy and paste the code from github into this new file
  3) ctrl+O --> enter to save the file
  
[Not Recommended]
To download the file straight from github: 
  1) Install git
  2) Navigate to the github repo 
  3) Click on the green clone and download button
  4) Copy the github link that appears
  5) In the linux OS, type --> git clone "The github url"
  6) Everything should be downloading :) (Although a lot of unnecessary files will be downloaded)


In order for this to work, the user will need to have python3 and the corresponding pip command installed.
Similarly, the user will need to install a dependency. 
To do this, please use the following code: 
  pip3 install paho-mqtt
  
**** The code will then need to be modified to run! ****
In the linux OS: 
  1) Open the file --> nano mqttsetup.py
  2) Edit the URL, port number, and other information for your MQTT server
  3) ctrl+O to save
  4) ctrl+X to exit 
In another OS: 
  You can edit the code in any word editor (notepad/ word for example) and simply update the users credentials.
  Then copy and paste the code into the linux file as mentioend above.

The subscription code can be ran with the following code: 
  sudo python3 mqttsetup.py 
  