# captains-log

[![CodeFactor](https://www.codefactor.io/repository/github/toddgoates/captains-log/badge)](https://www.codefactor.io/repository/github/toddgoates/captains-log)

[![Netlify Status](https://api.netlify.com/api/v1/badges/b875d253-15ba-4686-95ba-bee78ebb6d3f/deploy-status)](https://app.netlify.com/sites/romantic-swirles-43dc72/deploys)

Create your own Captain's Log in your browser with the HTML5 Speech Recognition API

## Notes

For best results, this needs to run on a server. If running from local file system, the browser will continuously prompt you for permission to use your microphone. On a server you just get prompted once.

## Future Ideas

Add actions to hit different APIs based on specific phrases. For example, "Get the weather."

```
if (transcript.includes('get the weather')) {
    // Do something with a weather API
}
```
