## A local as well as remote control plugin that runs as a html page to control Projection linup inside Disguise Designer! 
<img width="1917" height="945" alt="image" src="https://github.com/user-attachments/assets/e9fb4923-8583-479e-8ce1-d0eae0be2126" />

# What it does:
- Connects directly to Disguise Director machine on network
- Reads all projectors, names, resolutions, surfaces and lineup points refrenced to quickcal configs, 
- allows users to move lineup points in realtime "in projector"  as well as nudge by, 1,5,10 pixels
- allows users to toggle betweem content and lineup mode output per projector, 
- Users can also manually type in a coordinate for lineup point to be referenced to!

# Omnical RigCheck (r32.4 onwards):
- allow users to start camera discovery
- excecute a plan and get live progress report fedback, 
- RMS scores and errors fed back instantly to UI, users can either persist or decline changes, 
- basecd on response, either falls back to previous capture or saves as persists as new fallback result! 
- users can choose to restart the rigncheck again is RMS is too high! 

# How to use:
- download the HTML page as a html file, either on laptop, phone or tablet, 
- make sure device is on same IP range as Director IP, 
- auto discovery only works if running locally inside deisgner, otherwise specify the IP and port and click connect!

# How to use Inside Designer:
- rename HTML file as "Index.html" paste it into the plugins folder location, inside a folder (you can name the folder whatever its what it will appear as in Disguise plugins draw)

# NOTES:
- when using the hold and drag option for lineup, the system sends out post API commands, while the code is made to limit the amount of send requests, it will however use some bandwidth, do not use in a live setup (not that you would anyway). other than that it will function fine! 
- When first connecting you should need to click onto the fullscreen button in the top right og the quickcal visualiser in order to view the lineup points! this will be fixed later. 

### please note this has been made with the assistnace of claude and Aid3n, please feel free to modify the code to add more functionality, and if you do please share with the rest of the comunity :) 
any feature requests please email Dylan.law@disguise.one
