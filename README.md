# desktop-remote-access-on-nvidia-jetson

 ## Installing NoMachine 
 First of all download and intall NoMachine on desired device from this [link](https://www.nomachine.com/download/download&id=3)
## Setup Ngrok
Download [Ngrok](https://ngrok.com/download)

unzip the file ``` unzip /path/to/ngrok.zip ```

create a account in ngrok and connect with auth token ``` ./ngrok authtoken <your_auth_token> ```

``` cd ngrok ```

check local ip addr of NoMachine ``` sudo /etv/NX/nxserver --upnpmap``` 

``` ./ngrok tcp <local ip addr of NoMachine>:4000```

