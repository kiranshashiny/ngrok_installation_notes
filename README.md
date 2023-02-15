# ngrok_installation_notes


Install ngrok



- mkdir ngrok
- cd ngrok
- scp or get the ngrok executable for Rpi 
- untar the zip file. 
- install the auth token as listed in their page, It's ok if you dont have the auth token, but installing helps. I did.
- ./ngrok tcp 22
 
 ![image](https://user-images.githubusercontent.com/14288989/218654923-952361e0-8033-434b-97ed-6eea002049ea.png)



- ./ngrok http 80 // will work if you have Apache installed on the Rpi.



https://medium.com/@gaelollivier/connect-to-your-raspberry-pi-from-anywhere-using-ngrok-801e9fd1dd46

```
ssh pi@0.tcp.ngrok.io -p <port number>

ssh pi@0.tcp.ngrok.io -p 15233 << this is the port number listed in the ngrok console.

ssh  shashi@tcp://0.tcp.in.ngrok.io -p 17896 

```
