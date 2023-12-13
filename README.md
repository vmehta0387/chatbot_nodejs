# chatbot_nodejs
Simple project to help you get started with your own little chatbot in nodejs

## What we need for this project?

1. NPM and NodeJS installed
2. node-nlp module

### Setting up our project
First create a folder in which you want to create your project, I created folder named chatbot_nodejs.
Initialized repo in that folder with command npm init and install modules with npm i node-nlp.
Create a file named index.js in that folder.

### Creating Intents
Create a folder named intents inside our project folder. We will create our intents in JSON, So I created two json file named greetings.bye.json and greetings.hello.json.
You can add more as you like by creating new json files and structuring your intents like this.

### Training and Saving chatbot
Create a file named train.js and index.js in our project folder. Copy the code from my repo into it!
 - train script will run the train.js file.
 - start script will run the index.js file.
 
 For training our bot run command: *node train.js*  <br>
 Now start the chatbot using command: *node index.js*
