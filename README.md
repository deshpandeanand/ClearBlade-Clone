# JavaScript Tutorial for ClearBlade

This tutorial uses the ClearBlade JavaScript API to communicate with the ClearBlade Platform. This tutorial will help you get familiar with the ClearBlade Platform and give a brief explanation of concepts like Collections, Code Services, Libraries, Triggers, Timers and Messaging.

The [full tutorial is found here]( http://docs.clearblade.com/v/2/3-Developer_Reference/JavaScript/Tutorial/)

### Setup

#### Clone this repository 

- Do a ``` git clone https://github.com/ClearBlade/Tutorial-JavaScript.git ```

#### Editing part1.js to add the SystemKey, SystemSecret, PlatformURL and MessagingURL

-Navigate and open the file **Tutorial-Javascript/js/part1.js**  Update it with your systemkey, systemsecret, platformURL and messagingURL

EX (public cloud): 
   - URI : "https://platform.clearblade.com",
   - messagingURI : "platform.clearblade.com",

```javascript 
var initOptions = {
	URI : "YOUR_PLATFORMURL",
    messagingURI : "YOUR_MESSAGINGURL",
    messagingPort: 8904,
    useMQTT: true,
    cleanSession: true,
    systemKey: "YOUR_SYSTEMKEY",
    systemSecret: "YOUR_SYSTEMSECRET"  
}
```
- Save the file

If you are using a local instance try platform_url = "http://localhost:8080"; messaging_url = localhost;
  
  

Then open index.html in a browser and enjoy the tutorial!

