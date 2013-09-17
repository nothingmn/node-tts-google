node-tts-google
===============

Description
-----------
A node client for google's translate service, which will automatially pipe the audio to the speaker.


Usage
-----
var tts = require("node-tts-google").tts;

tts.speak(text);  //defaults to english

tts.speak(text, 'el'); //force greek



Note:
The Speaker library will require this environment variable to be set, prior to calling npm install:

set VisualStudioVersion=11.0
