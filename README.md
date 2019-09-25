# PiMustangScouter
Quick n' easy Pit scouting system 

## Structure

/templates/main.html contains the main file that opens when you run the server. This page will contain the link to the pages of
all teams and user can open anyone of them to input or change the input for a specific team

/teams contains folders for all teams. Each folder/team contains a capabilities.txt with all the things that the team's robot
can do and a summary.txt with a summary of the robot. It'll also contain an image that user inputs while uploading to the server

server.py is the file that runs a flask server on pi that many people can connect to

## To-Do (Claire)
 
Template for team pages and markdown for reducing duplicate code & adding new teams easier
JS Code for saving text to txt files and reading it from another html page



