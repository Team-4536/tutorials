PhotonVision

Set Up
Get a micro sd card and follow the instructions at https://docs.photonvision.org/en/latest/docs/quick-start/quick-install.html and follow the instructions to install the latest build of PhotonVision on to your raspberry pi 5.

Once you have your device with PhotonVision installed you need to set its IP address.
To set its IP address follow these instructions
Connect it to a keyboard and monitor
Sign in using the default username of pi and the default password of raspberry
Run the command: nmtui
When the NetworkManager TUI has popped up select: Edit a connection
Select dhcp-eth0
Select the show button that is next to IPv4 configuration
Next to Addresses select <Add…>
Enter a custom IP address in the field, we use the format of 10.45.36.## with the ## being a two digit number that is greater than 30
Hit <OK> then <Back> then <OK>
Once you have set the IP address connect both the laptop you are using and the raspberry pi you just set up to a properly configured radio and power them all.
Then go to http://IP ADDRESS HERE:5800/#/dashboard
It should bring you to a page that looks like this
<img width="512" height="260" alt="image" src="https://github.com/user-attachments/assets/a307e7b8-d6f6-4885-9442-36f29edc3b02" />
Once you do open the client connect a camera to the raspberry pi 
Then go to the Camera Matching page and click activate on your camera
<img width="512" height="254" alt="image" src="https://github.com/user-attachments/assets/39b129cc-48a3-4150-93ed-f04644a2e5e3" />
Once you 





