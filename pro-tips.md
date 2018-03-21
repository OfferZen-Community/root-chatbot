ProTips
-------

Many people have built insurtech bots in the way that you're currently going about it. 
This is a collection of things that others have been caught up on before, which may waste some of your time too. 
As you go, please add anything that you pick up too.

### Bots
- We <b>highly, highly</b> suggest reading [this](https://developers.google.com/actions/design/walkthrough) about designing conversations and writing out a script for your bot.
- Check out [this example](https://offerzen-make.slack.com/archives/C92LH0067/p1518527314000245) of how previous Make Day Alumni have set up their bots

### DialogFlow
- Remember to push `ENTER` to save rows of information in DialogFlow
- Remember to `SAVE` things before testing your changes
- Use the testing dialogue in the top right of the screen to test your conversation, and view the JSON in the bottom right to see a preview of the payload it sends.
- For testing, use the “Try it now” input box in the top right of your screen. This allows you to debug the context of the conversation piece, as well as view the JSON created. <b> Stay away from testing with the Google Assistant test bed as this seems to be buggy</b>
- There is an agnostic chat emulator called "Web Demo" that you can turn on in the integrations section in Dialogflow which is useful to test conversation with your bot.

### Root
- If you're getting errors about being in testing mode when trying to hit enpoints, make sure you're using `sandbox.root` and not `api.root` in your url requests
- You’ll auth your requests with the Basic auth using your `API Key` as username and a blank password
- If you need to generate ID numbers for life insurance, you can use [this link](https://chris927.github.io/generate-sa-idnumbers/)

### Endpoints
- Use [Ngrok](https://www.ngrok.com) to expose your local code via endpoints
- [Ngrok](www.ngrok.com) [fails to start on Windows10](https://github.com/bubenshchykov/ngrok/issues/60) --> Try using [serveo](https://serveo.net/)
- Firebase [requires you to be on pay as you go plan to make external HTTP requests](https://stackoverflow.com/questions/43415759/use-firebase-cloud-function-to-send-post-request-to-non-google-server)
- For those coding in [Node.js®](https://nodejs.org/en/), you can use [glitch](https://glitch.com) to host and deploy your code instantly instead of exposing from localhost.
