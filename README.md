fh-cordova-plugin-stream
========================

Audio Streaming plugin for Cordova 3+ 


1. Add platform in command prompt:

cordova platform add android


2. Install:

In windows CMD or Terminal cd into your project folder:

cd Project

type and enter command:

cordova add plugin https://git-repository-url


3. Build project:

Run command from cmd:

cordova build android


Plugin Usage:

To play audio stream use the following in your javascript code:

window.plugins.stream.action({act:'play', path:"http://full-url-of-your-audio-streaming-server" });

Note: Audio stream must use http protocal and can be a m3u8 stream. The audio stream can also use aac codec.

To stop audio stream:

window.plugins.stream.action({act: 'stop'});



