# BrightsignXT

In action: https://youtu.be/TojF4F4igPY

Notes on personlized info in Layouts:
  - CCTV - edit each item in the playlist with the RTSP address for your camera feeds
  - WxSummary - edit the HTML file found in the HTML subfolder to include your own ClientID and ClientSecret from the Aeris Weather API site.

Layout Handler:
  - This is the primary event handler component that shows and hides the visible on screen elements. The layout can be altered with an incoming UDP message.

UDP Handlers:
  - These parse incoming UDP messages sent from a home automation controller and assign them to variables, which are used in the image playback playlists.

More notes and info to follow...
