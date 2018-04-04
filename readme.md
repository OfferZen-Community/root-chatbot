
## Welcome

We’re building a chatbot that can query the Root Insurance API, and can be made available across multiple different chat interfaces, like Facebook, Slack and Google Assistant, using Natural Language Processing (NLP).

<img src = "/readme_images/components_diagram.png">

<b>The aim of the day is to learn new things. You do not need to complete the full app.</b> The agenda of the day caters for varying levels of experience and different people will learn different things by playing with the same tools.

## Prep Checklist 

Before you come to the Make Day, there are a couple of basics you need to have under your belt. Complete the items on this checklist and you’ll be ready to take on the challenges of building Insurtech bots at the Make Day. If you get stuck on any of these, please shout in Make Slack. 

### Admin
- Join [Make Slack Team](https://join.slack.com/t/offerzen-make/shared_invite/enQtMzA0NzkzODYyNTQ1LTA5OTY4MzI2OWM5NThmODM1MWYyYmJiMThhMWNlMmM1ZTRkZGM0NDBkNTQzYTFkYjY3MTQ4YTljMmYwOWY3ZWY)

### Tech Prep
- Watch [this 15 Minute Video](https://www.youtube.com/watch?v=ZvyrvowZ4wQ) on Dialogflow Basics (Dialogflow used to be called API.ai). You don't need to follow the build as you'll do the tutorial next. 
- Do the Silly Name Maker [tutorial](https://developers.google.com/actions/dialogflow/first-app) on Dialogflow (the example uses Firebase and JS in the build fulfillment section, but we highly suggest avoiding this and using [ngrok](https://ngrok.com/) or your preferred way to expose an endpoint)
- [Create an Organisation](http://recordit.co/AySoISRAKM) in Root and ensure the [insurance module(s) are enabled](http://g.recordit.co/XXetTnitPt.gif) for that organisation 
- Have a look around the [Root Insurance API docs](https://app.root.co.za/docs/insurance/api) to understand what you can do with the Insurance API
- Successfully query the Root API for a quote using [Postman](https://www.getpostman.com/) or similar tool and get a response (note that you need to use `sandbox.root...` in your request urls while testing, not `api.root...`) 
- Check out the [Pro Tips](/pro-tips.md) from previous Make Days
- Have a look around the [Example Apps](/example-apps.md) made by previous Makers and Root Devs

### Meta
- Write down one thing thing you want to figure out on the Make Day 
- Be awesome :)

## Other Important Docs for this Make Day
[Pro Tips](pro-tips.md)

[Agenda and Location](make-day-agenda.md)

## Some Useful Resources

### DialogFlow

- [Basic Tutorial](https://developers.google.com/actions/dialogflow/first-app) 
- [Website](https://dialogflow.com/) 
- [Sample Apps](https://dialogflow.com/docs/examples/) 
- [Starter example with API integration](https://dialogflow.com/docs/getting-started/basic-fulfillment-conversation) 
- [Crafting a Conversation](https://developers.google.com/actions/design/walkthrough#write_dialogs) 

### Other NLP solutions

- [Wit.ai](https://wit.ai/) 
- [Rasa](http://rasa.com/) 

### Root

- [Root Insurance Overview Video](https://youtu.be/Du_CNpF_mLU) 
- [Root Insurance API Docs](https://app.root.co.za/docs/insurance/api) (requires Root Login) 
- [Create a Root Organisation](https://s3.amazonaws.com/img0.recordit.co/Rq0ikoafCR.mp4?AWSAccessKeyId=AKIAINSRFOQXTN4DT46A&Expires=1520069298&Signature=Ndmc7UQSH4Jc6m4ZaluoGFfR4wE%3D) 
- [Enable insurance modules for an Organisations](http://g.recordit.co/XXetTnitPt.gif) 

### Other

- [ID number spoofing](https://chris927.github.io/generate-sa-idnumbers/)
- [South African ID generator CLI](https://github.com/tiaanduplessis/sa-id-gen)
