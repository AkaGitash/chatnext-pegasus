# Connect OpenAI to Dialogflow CX

### Things needed
* Dialogflow CX agent
* OpenAI account and API Key
* NGROK for exposing our local server to internet for testing
* Nodejs as a programing tool
    

### How to use it
* install all the required packages in the project folder
    > use the command `npm install --save`
* create a `.env` file in the folder and set two variables `PORT` and `OPENAI_API_KEY`
* run the local server `npm run start`
* start NGROK engine
    > make sure the ports are same
* set the NGROK url in Webhook section
    > `YOUR NGRK URL/dialogflow` it should be something like this
* test the connection
