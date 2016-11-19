# Web Audio API in Android (kinda)

This project was an experiment following some banter in the [Web Audio Slack channel](http://web-audio.slack.com) about using the Web Audio API in Android.

Although it is not possible natively, it can be achieved using a WebView which accesses a locally-stored HTML/JS file. WebViews use the WebKit rendering engine, which *does* implement the Web Audio API.

This Android project accesses a local `index.html` file in the `assets` folder, which contains some very basic Web Audio code in a `<script>` tag. It generates a 1kHz sine tone which cannot be turned off!

The MainActivity only news up the WebView and gives it permission to run JavaScript.



