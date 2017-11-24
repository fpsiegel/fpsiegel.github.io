"# fpsiegel.github.io" 
 raspivid -o - -t 0 -w 1280 -h 720 -rot 270 -fl -n -vf -hf -fps 30 -b 2000000 | avconv -re -ar 44100 -ac 2 -acodec pcm_s16le -f s16le -ac 2 -i /dev/zero -f h264 -i - -vcodec copy -acodec aac -ab 128k -g 50 -strict experimental -f flv rtmp://a.rtmp.youtube.com/live2/jm12-9hk5-1ayy-7rgb

CHANNEL ID

UCEleSFvJjSsaVO3gvFJxU5w 

EMBED LIVE
<iframe width="560" height="315" src="https://www.youtube.com/embed/live_stream?channel=CHANNEL_ID&autoplay=1" frameborder="0" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/live_stream?channel=UCEleSFvJjSsaVO3gvFJxU5w&autoplay=1" frameborder="0" allowfullscreen></iframe>
