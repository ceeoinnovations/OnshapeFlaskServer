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
3. Next (in your python IDE of choice, I recommend PyCharm) run something along the lines of "pip install requirements.txt." 
   1. Make sure you are inside the file that contains the code when you run this command by either using the terminal in
your ide, like PyCharm, or using the `cd` command.
   2. If you are using PyCharm, you can just open the file in PyCharm and press the "install requirement".\
4. 

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
