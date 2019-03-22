# captains-log

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
