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

