# powerapps-teams
This project demonstrates the integration between Powerapps and Teams

Steps:
1) Create Sharepoint List - with the following columns
*Title
*Description (Rich Text)
*Technology (Categories)

2) Import the Power Apps package
3) Update the connection to point to your newly created Sharepoint List
4) From Power Apps portal, click add to Teams

Current Features:
1) Know where is the hosted application run in - whether in Teams or not Teams using Teams Context
*Param("source")
2) Send Notification to Teams Channel when a new course is added or edited
*MicrosoftTeams.PostMessageToChannelV3
