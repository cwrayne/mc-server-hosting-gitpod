# mc-server-hosting-gitpod
Java and Bedrock server hosting FOR FREE thats actually really good with gitpod

# Instructions
## Make a Gitpod Workspace
Go [here](https://gitpod.io/#https://github.com/cwrayne/mc-server-hosting-gitpod) and login/create an account if you haven't already. Then, switch Standard to Large for a better machine (This is completely optional, but recommended) and then press Continue.
**YOU WILL HAVE TO LEAVE THE BROWSER WINDOW OPEN TO KEEP THE SERVER RUNNING!**
## Just... add the server files
Download the server files from whereever (and get Java)
## Share the server
**DO NOT USE THE PORTS MENU WITHIN GITPOD**, create/sign in to your account if you havent already [here](https://playit.gg/login), create a new terminal tab (the + button near the terminal name) and then install playit.gg using these commands:
```sh
curl -SsL https://playit-cloud.github.io/ppa/key.gpg | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/playit.gpg >/dev/null
echo "deb [signed-by=/etc/apt/trusted.gpg.d/playit.gpg] https://playit-cloud.github.io/ppa/data ./" | sudo tee /etc/apt/sources.list.d/playit-cloud.list
sudo apt update
sudo apt install playit
```
- Then run playit by entering `playit`, and then go to the link given to link it to your playit.gg account. Then, on the playit.gg dashboard, add a tunnel with type Minecraft: Java Edition and then create it. Then copy the server link and use it!
- For Bedrock, do the same thing as before but then create a Minecraft: Bedrock Edition type tunnel. Then copy the server link and use it!

## Using Simple Voice Chat
Use the Simple Voice Chat plugin/mod, and then setup a UDP-type-tunnel in playit.gg and set the port to 24454 (or whatever your Simple Voice Chat port is) and then copy the url with the port (something like 123123.ply.gg:1234) and go into the voice chat properties, and then set voice_host to that URL. then restart the server and it'll be good!
