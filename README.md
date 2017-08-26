### Recovery house chatbot to find beds

This project began on Wednesday, August 23, 2017 as part of Boston Digital Health
Innovators as a away of empowering people struggling with opiate addiction to easily find
openings in addiction recovery centers.

This app comes pretty directly from Facebook's Chatbot API and, once completed as a proof of concept, will be
marketed to addiction recovery centers to plug into other Boston Digital Health Innovators-supplied EMR APIs.


### Local

* run `node index.js` to run the app (5000)
* run `ngrok http 5000`
* get the ngrok URL from ngrok and use URL + /webhook/ in the facebook webhook settings for the app

#### Problems

* Fixed issue of getting no ID for user by disabling messaging_echoes in the app configuration
