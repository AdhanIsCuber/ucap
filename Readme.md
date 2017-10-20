# Ucap

AI Chatbot Web Speech API usng NodeJS

### Preview
![previe](/public/img/preview.png)


### Prerequisites
Supported Browser :
 - Google Chrome 33+ (Tested)  
 - Mozilla Firefox 49+ (Tested) - Permission web speech not run.

Before run you need additional tools installed on your local :
  - NodeJS 4+


### Technology Stack
- NodeJS
- ExpressJS
- Socket.io
- Dotenv
- Web Speech API
- SASS
- API.AI (now DialogFlow)

### Installing and Run
1. Install dependencies.

```
npm install
```

2. Make `.env` file.

```
touch .env
```
3. Fill out your API.AI TOKEN
```
APIAI_TOKEN='8eefxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx'
APIAI_SESSION_ID='thisisword'
```
4. Run
```
node index.js
```
App will run on PORT 5000.

### Reference
- [Building A Simple AI Chatbot With Web Speech API And Node.js by **Tomomi Imura**](https://www.smashingmagazine.com/2017/08/ai-chatbot-web-speech-api-node-js/)
- [Web Speech API by **Mozilla Developer Network**](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API)