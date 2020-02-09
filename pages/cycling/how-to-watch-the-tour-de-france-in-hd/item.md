---title: How to watch the Cycling in HDvisible: true---<p style="text-align: left;">
  [read to the end through some of the tech stuff to find out how to stream this to your TV in HD]
</p>

<p style="text-align: left;">
  Unfortunately, the Eurosport Player doesn't work here in Canada. Unless you are lucky enough to be at home and have cable/sat. with a channel that carries the Tour, you are stuck watching it on the computer. If you are lazy, you can go to&nbsp;<a href="http://www.cyclingfans.com/">http://www.cyclingfans.com/</a>&nbsp;and there are links to watch the Tour in your browser. However, the quality is bad.
</p>

<p style="text-align: left;">
  &nbsp;
</p>

<hr id="system-readmore" />

<p style="text-align: left;">
  While looking around for a better quality stream, I found the webpage:&nbsp;<a href="http://www.wiziwig.tv/broadcast.php?matchid=210625&part=sports">http://www.wiziwig.tv/broadcast.php?matchid=210625&part=sports</a>&nbsp;which allows for streaming Eurosport at almost 1Mbps. This is good enough for streaming to an HDTV. The stream is 720x404, so it's a bit better than standard TV but not HD. 720p is 1280x720.
</p>

<p style="text-align: left;">
  To watch the stream in good quality requires the VLC player to be installed: <a href="http://www.videolan.org" style="text-align: left;">http://www.videolan.org</a>. If you are unlucky enough to be stuck on Windows, the VLC player includes the VLC plugin which allows you to use the Wiziwig.tv VLC URL's and play it on your browser. However, on the Mac, there is no VLC playin that works well.
</p>

<p style="text-align: left;">
  Of course, playing the stream in your browser means you are limited to the size of window the browser selects. Using Chrome's developer console, I managed pull out the stream's URL from Wiziwig.tv's webpage. I then plugged this URL into the VLC player (full version), and voila! I had the stream running on my Mac and could size the window to any size I wanted. If you have the VLC player for Windows (or even Linux), it works the same. Plug in the URL and watch the stream. To play it on your HD TV set, connect the video out (HDMI/DVI) to your TV set, and you have the TDF on your big screen.
</p>

<p style="text-align: left;">
  To recap, to watch the Tour in HD:
</p>

<p style="text-align: left;">
  - Install VLC player from <a href="http://www.videolan.org">http://www.videolan.org</a>&nbsp;(and on Windows, Check the INSTALL VLC PLUGIN).
</p>

<p style="text-align: left;">
  - Open VLC and from the file menu, select Open From Network
</p>

<p style="text-align: left;">
  - Enter in this URL:&nbsp;<a href="http://149.255.39.122/aasd/8814/index.m3u8">http://149.255.39.122/aasd/8814/index.m3u8</a>&nbsp;(or hack apart the wiziwag.tv webpage to get the URL for the day. Use the View Source item from your browser and search for m3u in the web source)
</p>

<p style="text-align: left;">
  - From the Video menu, select FULL SCREEN.
</p>

<p style="text-align: left;">
  - Hook up your computer to your TV. Enjoy.
</p>

<p style="text-align: left;">
  <strong>Watch the Tour on your Smart Phone</strong>
</p>

<p style="text-align: left;">
  Well, I tried enter the esiolive2 URL above on my Blackberry Z10 on it's brower and it opened the link and displayed it. Luckly, Blackberry had the sense to put a HDMI port on their Z10, so, another way to watch the Tour on your TV is to connect your Blackberry Z10's HDMI port to your TV, and you have the Tour on your TV without a computer. You can also watch tour when you are out and about.&nbsp;
</p>

<p style="text-align: left;">
  I also tested the URL on my iPad (version 1). I opened the browser, and entered the esiolive2 URL, and the tour came up and worked.
</p>

<p style="text-align: left;">
  So, to view the Tour on your Smartphone or iPad, click on this URL from your device:
</p>

<p style="text-align: left;">
  <a href="http://esioslive2-i.akamaihd.net/hls/live/200728/AL_ESP1_UK_ENG/playlist_1800.m3u8" style="text-align: left;"></a><a href="http://149.255.39.122/aasd/8814/index.m3u8">http://149.255.39.122/aasd/8814/index.m3u8</a>
</p>

<p style="text-align: left;">
  Watching Other Streams:
</p>

<p style="text-align: left;">
  British Eurosport 1:&nbsp;<a href="http://149.255.39.122/aasd/8814/index.m3u8">http://149.255.39.122/aasd/8814/index.m3u8</a>
</p>

<p style="text-align: left;">
  British Eurosport 2:&nbsp;<a href="http://149.255.39.122/aasd/8815/index.m3u8">http://149.255.39.122/aasd/8815/index.m3u8</a>
</p>

<p style="text-align: left;">
  If the video is choppy or pauses alot there are two causes:
</p>

<p style="text-align: left;">
  - Your Internet connection isn't fast enough handle the high res stream&nbsp;
</p>

<p style="text-align: left;">
  - VLC's buffer size needs to be increased. See this article:&nbsp;<a href="http://www.groovypost.com/howto/change-vlc-streaming-buffer/">http://www.groovypost.com/howto/change-vlc-streaming-buffer/</a>
</p>

<p style="text-align: left;">
  &nbsp;
</p>