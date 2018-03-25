# Questions and answers

## Question: [Why is Firebase and JS suggested as being avoided as prep for the day?](https://offerzen-make.slack.com/archives/C8CRG1G5S/p1522002850000092)

_Mihow Bogucki [Make Team Lima] 8:34 PM 25 March 2018_

## Answer

_Ben Blaine [Make Community Manager]_

Changes take long to deploy and you need to use credit card. ngrok has raving reviews :slightly_smiling_face:

_Dan Davey [Make Platform Developer]_

also logging sucks

## Question: [Are there any examples/tutorials with ngork and node?](https://offerzen-make.slack.com/archives/C8VD9AS84/p1521626669000084)

_Liam Coetzee [Make Team Juliett] 12:23PM 21 March 2018_

## Answer

_Jiaan [Make Master] 1:19 PM 21 March 2018_

There's a handy NPM package that integrates ngrok directly into you node app. https://www.npmjs.com/package/ngrok Alternatively you can download the ngrok binary from their website and start it with the command `ngrok http 3000`, where 3000 is your service port on your localhost. Once ngrok is started you'll see a URL that looks something like this `https://369e2a75.ngrok.io`, this is your public URL that you can now use to fulfill actions. Take a look at this tutorial for more how-to's on integration https://github.com/RichardOB/root-chatbot-webhook-nodejs#5-connecting-your-chat-bot-to-the-root-chatbot-webhook
