# LB Twitch Get Clips
 LioranBoard extension to retrieve Twitch clips from any broadcaster. Can specify amount of clips to retrieve (max 15). Super useful for shoutouts!   


**Variable format:**    
If amount of clips = 1 --> variable    
If amount of clips > 1 -->  adds all clip ids to a stack named variable    

If something goes wrong retrieving the clips or streamer does not have any clips, your variable value will be set to "error".    
If streamer has less clips than the amount you specified, you will receive all available clips.    
   
Base URL for Twitch clips is `clips.twitch.tv/<CLIPID>`   

I also recommend installing **Clip Length** extension which retrieves the length of the clip and automatically starts a timer to send an extension trigger. Useful for auto hiding your OBS browser source once the clip has finished playing.    
Link: https://github.com/christinna9031/LB-Twitch-Clip-Length   

**URL for embed Twitch clips** is `https://christinna9031.github.io/Twitch-Clip-Embed/?clipid=<CLIP ID>` (needs to be hosted on a server since Twitch does not allow it to be embedded locally).    

**IMPORTANT**: Please follow the instructions in the premade buttons that are provided after you install the extensions.     




**How to install an extension:**
1. Download the .lbe extension file from **Releases** section (please do not right click and save) 
2. Click on Install Extension in your LioranBoard Receiver
3. Select the extension file you downloaded 
4. Select your default Transmitter you are using. Make 100% sure it is the correct one. 
5. Refresh your Transmitter or close and reopen Lioranboard Receiver. 
6. Most extensions include a premade deck with buttons. If you do not see one, create a new button, add "Send to Extensions" command and select the extension you just installed. If you can only see the extension name with no input fields, it means it was not installed correctly. Repeat steps above.  

[![](https://github.com/christinna9031/LioranBoard-Files/blob/main/img/paypal.png?raw=true)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3YWXYQE3HKWHQ)

DISCLAIMER: The extension is provided as is. The developer has no obligation to provide maintenance and support services or handle any bug reports.
Feel free to edit the extension for your own use. You may not distribute, sell or publish it without the author’s permission.
