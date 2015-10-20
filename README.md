# IBM BlueMix and Node-RED and Demo
Quick demo of using IBM BlueMix and Node-RED to build a simple CRUD website.

## Sign Up to IBM BlueMix

1. Go to https://console.eu-gb.bluemix.net/
2. Click the "SIGN UP" button in the top right of the screen
3. Create an account
4. Wait for account confirmation to come through

## Create a New Node-RED Starter Project

1. Go to https://console.eu-gb.bluemix.net/
2. Click the "LOG IN" button in the top right of the screen
3. Log in to the IBM BlueMix console
4. Click the "CATALOG" menu item at the top right
5. In the search box type in a search for "node-red"
6. Click on the "Node-RED Starter" item that should be displayed
7. On the boxes in the right hand side give the project a name, keep all the rest of the boxes at their default values
8. Press the "CREATE" button
9. Wait for BlueMix to set up the project for you...you might want to grab yourself a tea while this happens
10. Once BlueMix completes setting up the project click on: http://YOURPROJECTNAME.eu-gb.mybluemix.net

## Set up the Demo Database

1. Go back to the BlueMix dashboard at: https://console.eu-gb.bluemix.net/
2. Click on "YOURPROJECTNAME"
3. Click on the "Cloudant NoSQL DB" tile
4. Press the "LAUNCH" button in the top right
5. Press the "Add New Database" button in the top right
6. Call the database "blobs"
7. Press the create button


## Set up the Demo Flows

1. From http://YOURPROJECTNAME.eu-gb.mybluemix.net  click "Go to your Node-RED flow editor"
2. Click on the hamburger icon in the top right (three horizontal bars)
3. Choose import -> clipboard
4. Copy the contents of the demo flow into your clipboard:  https://github.com/davegoopot/bluemix-nodered-demo/blob/master/demoflow.json
5. Paste the file contents into the Node-RED "Import Nodes" box
6. Press "Ok"
7. Click in the main Node-RED window to drop the nodes into the project editor
8. Press the "Deploy" button in the top right of the screen

## First Time Work Around Database Link

To work round an issue with connecting to the database for the first time:

1. Double click the "Blobs" node and give it a new name, e.g. "Blobs2".  Press "Ok"
2. Double click the "Write blob" node and give it a new name, e.g. "Write blob2".  Press "Ok"
3. Press "Deploy" in the top right of the screen
4. Try out the application you have written at: http://YOURPROJECTNAME.eu-gb.mybluemix.net/readblob





