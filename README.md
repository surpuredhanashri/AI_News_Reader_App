# Voice Controlled React News Application - Alan AI Voice Assistant


## Introduction

In this Project, we're going to build a Conversational Voice Controlled React News Application using Alan AI. Alan AI is a revolutionary speech recognition software that allows you to add voice capabilities to your applications. It allows you to control absolutely everything in the app using your voice. Another huge benefit is that it's extremely easy to integrate it.

### Tech-Stack

- React Hooks
- Alan AI Voice Assistant - @alan-ai/alan-sdk-web
- MaterialUI - @material-ui/core
- classnames
- words-to-numbers

### Introduction

- Alan AI is a revolutionary speech recognition software that allows you to add voice capabilities to your applications.
- It allows you to control absolutely everything in the app using your voice.
- Another huge benefit is that it's extremely easy to integrate it
- So Im going to build a Conversational Voice Controlled React News Application.

### Deploy

surge.sh/

### Function

- Using Voice Assistant to choose type of news:
  - Latest news.
  - News by Categories : Business, Entertainment, General, Health, Science, Sports, Technology in U.S
  - News by Terms: Corona, PlayStation 5, Smartphones,...
  - News by Sources: CNN, ABC News, BBC News,....
- You can choose
  - Read news by yourself
  - Or Alan AI Voice Assistant can help you to read that
- Gives responses to casual conversation

### Resources

- Alan AI Studio: https://alan.app
- API news: https://newsapi.org/

### Screenshot

<img src="https://i.imgur.com/DwMT1.png" />


### After this project

I have improve for myself about

- Material-UI
  - Create Card component
  - styles component
  - Write CSS by makeStyles
  - Responsive App with Grid, Grow
- Merge different className to one with `classnames`
- Fetch API

I have understand about

- Fetch API in Alan Studio
- using voice to get data from API
- `words-to-numbers`
  - convert words string to number
  - guess the word has same sound to the true number (such as: for ~> 4)
- Scroll window to article currently reading
- Opening the new URL by use Voice Assistant
- Make casual conversation that we didn't set up in our original script


### Set up

- `npm install`
- run ```npm i && npm start``` to start development server
- Replace: `[API_KEY]` and `[alanKey]`
  - `[API_KEY]` is login in https://newsapi.org/
  - `[alanKey]` is login in https://alan.app
- Copy code in `alanStudio.js` to Alan Studio
- Create new script in Alan Studio
  - Copy code in `alanStudio-SmallTalk.js` to new script
- `npm start`
