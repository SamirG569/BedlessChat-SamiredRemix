# BedlessChat
A (somewhat) lightweight instant messaging client that i am making (its bad)

Has to have a TCP port at the end.
Eg, my-server.mydomain.xyz:19923
If doesn't have a TCP port, will default to 2267.

TO DOWNLOAD (Important)
Go to https://github.com/SamirG569/BedlessChat-SamiredRemix/releases
And go to the first zip.

TO START A SERVER
Download the ZIP file and edit the file wherever you want to, whether it be in vs code or notepad++, it doesnt matter.
Find the variable "port", where it shows "port = 2267".
The "host" variable tells the server to host it on localhost, so do not modify that
Change "port" to whatever port you want.
Run the server.py file now.
You will now have the server running on 127.0.0.1:your port number.

TO MAKE THE SERVER ACCESSIBLE TO USERS OUTSIDE OF YOUR LAN
First, you will need to decide whether you will be port forwarding, or tunnelling.
If you are an advanced individual with a public IP, port-forward your port you opened it on, eg, 2267, with TCP protocol.
Then, your server will be hosted on something alongst the lines of "82.648.2.1:externalportyouforwardeditto".
Congratulations, you have made your own server!

TO MAKE THE SERVER ACCESSIBLE WITH TUNNELLING
If you do not have access to your router settings, or do not have access to a public IP, then follow these steps.
Download NGROK (or similar with tcp protocols) via this link: https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-windows-amd64.zip
Then, unzip the folder and run "ngrok.exe".
After that, in the console it just opened, write: "ngrok tcp [port you opened on]", replacing port you opened on with the port you opened on.
It will provide you with a link, that if you or any other people outside or inside of your lan type it correctly in mainnew.py Server IP input, will let you join thus server, and chat with other people.
