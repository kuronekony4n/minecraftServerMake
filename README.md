# [**CLICK HERE TO GET STARTED**](https://colab.research.google.com/github/kuronekony4n/minecraftServerMake/blob/main/MinecraftServerMake.ipynb)

# **MAKE MINECRAFT JAVA SERVER**
### by [kuronekony4n](https://facebook.com/addstring)
---

### (TUTORIAL 1) First time here?
1. Connect to Collab Runtime.
Click on **Connect** button on top right corner (below Comment and Share button). Wait until you succesfully Connected.
2. Mount your Drive Account. 
Click the "**Files**" tab on the left side of screen then click on **Google Drive Icon** to Connect.
3. Prepare the machine.
Run cell "Prepare the machine". It will make new folder called "**MinecraftServer**" on your Drive root folder for all the server files we will going to saved to.
(If you already have folder on your drive called "**MinecraftServer**", this step is optional.)

---
### (TUTORIAL 2) Make new Server
Make sure you already does everything on **TUTORIAL 1** before proceeding.
1. Input your worldname. 
This will make new folder for that server and save all the server files in it.
2. Input your desire paper url.
Visit [this page](https://papermc.io/downloads) to find paper releases you want to use. Just copy and paste the download URL on the **paper_url** form.
3. Run the cell

---
### (TUTORIAL 3) Run your server
Make sure you already does everything on TUTORIAL 2 before proceeding.
1. Input worldname you want to run the server.
2. Visit [ngrok website](https://ngrok.com), login or make new account if you don't have. After logged in, open [this page](https://dashboard.ngrok.com/auth/your-authtoken) and copy paste your Authtoken to **ngrok_authtoken** form.
3. Run the cell
4. Wait until you see server log like this and your server is online.

---
### (TUTORIAL 4) Connect to your server
Make sure your server is online.
1. Open your Minecraft Java Game with the same version with your paper release, click on Multiplayer and add new Server.
2. Open [ngrok tunnel list](https://dashboard.ngrok.com/status/tunnels).
3. Locate your tunnel and copy paste the URL to your Minecraft game server address. (without **tcp://**)
4. Connect to your server.
---
