Intelligent Customer Help Desk with Smart Document Understanding

In this project,
I have created a AI powered chatbot using IBM Watson Assistant and integrated it with Node-Red.
This Chatbot helps user in efficient way to find the queries regarding the device (Here device used is Heater-"ecobee3").

At a certain point a Chatbot drain out of responses and asks user that if they want to interact with the company representative, So instead of redirecting user to the representative this AI powered Chatbot give an ease to the user by providing the information of the device.

This is made possible due to use of "Watson Discovery" during the Developement of Chatbot.
Watson Discovery keeps the tracks of keywords entered by user and find out the most appropriate Content from the document provided, and deliveres it to user.
So in this way this Chatbot help to minimize your time to go through all the manual and helps by giving a most precise information related to the query.

At the end this Chatbot is integrated to a webpage with the help of "Node-Red" where 
"Watson Assistant->Watson Discovery->Cloud Function"
use of these major resources is done 
And finally a user friendly Chatbot was built.

The ChatBot       : https://node-red-ptypv.eu-gb.mybluemix.net/ui/#!/0?socketid=cLv9WaHf_Iy0_eLOAAAC

Video demo link     : https://youtu.be/c5glteCeedg

Node_red flow    : https://node-red-ptypv.eu-gb.mybluemix.net/red/#flow/e7c89970.ad9318

As the data (Document) fed is of Heater,
Try following Questions :
"How can I turn on the heater"
"How can I access the settings"
etc...
