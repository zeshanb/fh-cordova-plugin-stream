fh-cordova-plugin-stream
========================

Audio Streaming plugin for Cordova 3+ 

<ol>

<li><h2>Add platform in command prompt:</h2>
<pre>
cordova platform add android
</pre>
</li>

<li>
<h2>Install:</h2>

In windows CMD or Terminal cd into your project folder:

cd Project

type and enter command:
<pre>
cordova add plugin https://git-repository-url
</pre>
</li>

<li>
<h2>Build project:</h2>

Run command from cmd:
<pre>
cordova build android
</pre>
</li>
</ol>

<h2>Plugin Usage:</h2>

<h3>To play audio stream use the following in your javascript code:</h3>
<pre>
window.plugins.stream.action({act:'play', path:"http://full-url-of-your-audio-streaming-server" });
</pre>
Note: Audio stream must use http protocal and can be a m3u8 stream. The audio stream can also use aac codec.

<h3>
To stop audio stream:
</h3>
<pre>
window.plugins.stream.action({act: 'stop'});
</pre>


