# OnshapeFlaskServer
Python-based Flask Server for communicating with Onshape

Lead developer: Alexander Koppel

---
## Description:

This project creates a flask server that can be accessed within Onshape as an "*Integrated Cloud App*" through the 
"*App Store*" as an app called "*[Tufts CEEO Flask App](https://appstore.onshape.com/apps/Design%20&%20Documentation/L2TGY3UQFV4RPW7XMYDTQ76QXIK6NYLFUBT7NSI=/description)*"
(which is private to the Rogers Onshape Enterprise at the moment). This flask server uses Onshape's REST API to edit and 
display information about the current workspace in real time. 

For more information about Onshape's REST API you can:
- Look at Onshape's [integration guides](https://github.com/PTC-Education/Onshape-Integration-Guides)
- Read their documentation provided on [Glasswork](https://cad.onshape.com/glassworks/explorer/#/)
- Check out example API calls through PTC's [API playground](https://github.com/PTC-Education/PTC-API-Playground)

This project started using Onshape's [*Heat Sink Design Project*](https://github.com/PTC-Education/Heat-Sink-Design) 
as a base along with Onshape's [*Four Bar Mechanism Design Project*](https://github.com/PTC-Education/Four-Bar-Mechanism) 
as inspiration for the "*CEEO Rotate & Graph*" extension.

This project contains three separate tools:
- CEEO Rotate & Graph
- CEEO Image Maker
- CEEO GIF Maker

---
## How To Run:

***IN PROGRESS***
1. Download python
   1. Make sure the PATH is correctly setup and PIP is also installed
      1. To check python is installed, run `python --version` or `py --version`
         1. I used Python 3.10.5 - 64 bit
      2. To check your python PATH works, run `python` or `py` in terminal.
         1. You can exit with `exit()` or `^Z` (Ctrl-Z)
      3. To check pip is installed, run `pip --version`
         1. I used pip 22.0.4
2. Download/clone this repository! The easiest method is to "Download Zip", and then unzip the file.
3. Next in the terminal (in your python IDE of choice, I recommend PyCharm) run `pip install -r requirements.txt`
   1. Make sure you are inside the file that contains the code when you run this command by either using the terminal in
your ide or using the `cd` command.
   2. If you are using PyCharm, you can just open the file in PyCharm and press the "install requirement" button.
4. Next follow the instructions [here](https://github.com/PTC-Education/Onshape-Integration-Guides/blob/main/API_Intro.md#2-generating-your-onshape-api-keys)
to create your Onshape API Keys. Only create the keys, next step is how to use and save them.
5. Once you have your two API keys, save them in the file called "OnshapeAPIKey.py", replacing "ACCESS" and "SECRET"
with the new respective keys you created.
6. Next make sure you are on the "Rogers" Onshape enterprise, then subscribe to the app found here.
   1. If you are not on the "Rogers" Onshape enterprise, follow the steps below in making your own Onshape App.
7. Make sure your browser accepts the certificates provided in this GitHub following [these steps](https://github.com/PTC-Education/Onshape-Integration-Guides/blob/main/Flask_Intro.md#3-configure-flask-as-https). 
   1. You do not need to make your own certificates. Skip the first step and instead start at: "_Then, you need to add 
this newly created certificates to be a trusted certificate of your computer system._"
8. To start the Flask Server run `$env:FLASK_APP = "OnshapeFlaskApp.py"; $env:FLASK_ENV= "development" ; flask run --cert=cert.pem --key=key.pem`

---
## Review of Tools: 
Instructions of the different tools this project creates and how to use them.
***IN PROGRESS***

#### - CEEO Rotate & Graph:
This is a tool for Onshape's **Assembly**.

#### - CEEO Image Maker:
This is a tool for Onshape's **Part Studio**.

#### - CEEO GIF Maker:
This is a tool for Onshape's **Assembly**.

---
This project created by the Tufts Center for Engineering Education and Outreach (CEEO).

For more innovations from the Tufts CEEO, visit: https://www.ceeoinnovations.org/
