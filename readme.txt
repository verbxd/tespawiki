
TeeBoard requires the Adobe Air Runtime. 
https://get.adobe.com/air/



TeeBoard beta
=========================================================================================================

Check the patch notes via the system tray right click menu.

Expect things to be broken and others to not work as expected. This is work in progress :)



=========================================================================================================

WIDGETS

=========================================================================================================

TeeBoard comes with a number of widgets for your stream. 
The first time you start TeeBoard, the widgets are copied to your user documents folder (e.g. C:\Users\[USERNAME]\Documents\TeeBoard\widgets).

- Chat: show your Twitch chat on stream.

- Follower notification: displays a message on your stream whenever there's a new follower

- Subscriber notification: displays a message on your stream whenever there's a new subscriber

- Donation notifications: displays a message on your stram when you receive a donation (via ImRaising or streamdonations.net)

- Poll: conduct a poll from within TeeBoard and display it on your stream. People in chat can vote by entering the correspoding keyword.

- Clock: displays your local time (default) or UTC time + timezone

- Countdown: displays a countdown timer countdown

- Spectrum: plays one or more mp3 files and displays their spectrum

- Media: plays one or more video files (mp4/flv).


=========================================================================================================



For OBS users:

All widgets require the CLR Browser Source plugin.
https://obsproject.com/forum/threads/clr-browser-source-plugin.12608/

Once installed, add a CLR Browser plugin source and browse to the html file in the widget's folder.

To display a widget across multiple scenes, add them as a "Global source" and then add the global source to the required scenes.
It is not recommended to resize widgets in the OBS preview (edit scene). You should define the desired dimensions in the 
CLR Browser source properties.

The following widgets however can be scaled down in OBS:

- Clock
- CountDown
- Spectrum
- Media

=========================================================================================================

For XSplit users:

Add a "Media" source and browse to the .swf file in the widget's folder 
(e.g. C:\Users\[USERNAME]\Documents\TeeBoard\widgets\clock\teeboard-clock.swf).

Certain (html/javascript based) widgets such as the Media and Poll widget 
can be added to XSplit 2.0 (beta) by adding the html page instead of the swf.


=========================================================================================================

