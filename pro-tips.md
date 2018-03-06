ProTips
-------

Many people have built insurtech bots in the way that you're currently going about it. 
This is a collection of things that others have been caught up on before, which may waste some of your time too. 
As you go, please add anything that you pick up too.

## Bots
- We <b>highly, highly</b> suggest reading [this](https://developers.google.com/actions/design/walkthrough) about designing conversations and writing out a script for your bot.

## DialogFlow
- Remember to push `ENTER` to save rows of information in DialogFlow
- Remember to `SAVE` things before testing your changes
- Use the testing dialogue in the top right of the screen to test your conversation, and view the JSON in the bottom right to see a preview of the payload it sends.

## Root
- If you're getting errors about being in testing mode when trying to hit enpoints, make sure you're using `sandbox.root` and not `api.root` in your url requests
- You’ll auth your requests with the Basic auth using your app’s `Client App ID` as username and the app’s `Client App Secret` as password

## Endpoints
- Use [Ngrok](www.ngrok.com) to expose your local code via endpoints
- [Ngrok](www.ngrok.com) [fails to start on Windows10](https://github.com/bubenshchykov/ngrok/issues/60) --> Try using [serveo](https://serveo.net/)
- Firebase [requires you to be on pay as you go plan to make external HTTP requests](https://stackoverflow.com/questions/43415759/use-firebase-cloud-function-to-send-post-request-to-non-google-server)
