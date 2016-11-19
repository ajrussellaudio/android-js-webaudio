# Web Audio API in Android (kinda)

This project was an experiment following some banter in the [Web Audio Slack channel](http://web-audio.slack.com) about using the Web Audio API in Android. Although it is not possible natively, it can be achieved using a WebView which accesses a locally-stored HTML/JS file. WebViews use the WebKit rendering engine, which *does* implement the Web Audio API, with some concessions.

