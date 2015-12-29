### Media (Audio and Video)
Text alternatives make the audio information accessible to people who are deaf or hard of hearing, as well as search engines.

- Provide text transcripts
- Synchronized subtitles for videos

<pre><code class="language-markup">&lt;video class="readable" poster="your-video-poster.jpg" controls tabindex="0" title="My Video"&gt;
    &lt;source  src="your-video.m4v" type='video/mp4; codecs="avc1.42E01E, mp4a.40.2"' /&gt;
    &lt;source  src="your-video.ogg" type='application/ogg' /&gt;
    &lt;source  src="your-video.webm" type='video/webm' /&gt;
    &lt;track src="your-video-transcript.vtt" label="English Captions" kind="subtitles" srclang="en-us" default /&gt;
&lt;/video&gt;
</code>
</pre>

Visit [the A11Y Project](http://a11yproject.com/posts/using-caption-services-with-html5-video/) for more information.
