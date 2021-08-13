# Twitter Bot
I am working on a raspberry pi twitter bot.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Vickie Chen | Monta Vista High School | Artificial Intelligence | Incoming Senior

![Twitter Icon](https://images.pexels.com/photos/5417837/pexels-photo-5417837.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260)
  
# Final Milestone
coming soon

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1628882530/video_to_markdown/images/youtube--iQRRl868OeA-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=iQRRl868OeA "Final Milestone")


# Second Milestone

My second milestone consisted of fixing some of the code I wrote before and tweeting out images. I was also able to automate the Twitter bot and post tweets  with specific time intervals or different times of the day. I had to fix some of my previous code because in order to automate the Twitter bot, I can't manually authorize the app every single time I post a tweet. To tweet out photos and videos, I used the same function as tweeting out plain text posts, but added '_with_media' and defined the media (<i>photo</i> in my code). 

<img src="images/twitterbot2.png" width=500 align=center style="float:center; padding-right:10px">

For automating the Twitter bot, I used cron job commands. I imported datetime in my code and to print out the timestamp of the times the tweets posted to keep track. I tested out multiple time intervals, like one minute, five minutes, and even having it run all the time. 

| importing datetime | crontab file| 
|    :----:      |    :----:   | 
|<img src="images/twitterbot3.png" width=500 align=center style="float:center; padding-right:40px"> | <img src="images/twitterbot4.png" width=500 align=center style="float:center; padding-right:10px"> |

[![Second Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1628884074/video_to_markdown/images/youtube--gCzjCQgVddc-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=gCzjCQgVddc "Second Milestone")



| **One minute** | **Five minutes** | **Every minute** | 
|:---        |    :----:   |          ---: |
| <img src="images/one minute.png" width=200 align=center style="float:center; padding-right:10px"> | <img src="images/five minutes.png" width=200 align=center style="float:center; padding-right:10px"> | <img src="images/every minute.png" width=200 align=center style="float:center; padding-right:10px">|





# First Milestone
  

My first milestone was setting up and connecting the Raspberry Pi with my computer with VNC Viewer for more effecient coding. I downlaoded Raspberry Pi OS (Mac version to be compatible with my laptop) on my SD card and uploaded to a LCD monitor. I connected my keyboard and mouse wirelessly to the monitor, then downloaded VNC Viewer on my MacBook. Using VNC Viewer, I casted my monitor to my Mac so that it would show on my Mac everything that was happening on the monitor. All my coding is done on my Mac since it's much easier. I had to make a Twitter Developer App account to link my code to my the Twitter account I was posting on. I created my Twitter bot using Python and importing Twython to use the packages it came with. I had to generate API and authorization keys from my Twittter developer account and set those to constants in my code. Another part of my first milestone was being able to finally send out a tweet on my account using Raspberry Pi. There was a 401 authorization error that took me a few days to fix, and I found code that worked to authorize the app manually with a link everytime I ran the command line to post a tweet. 

<img src="images/pi setup.png" width=500 align=center style="float:center; padding-right:10px">

<img src="images/twitterbot.png" width=500 align=center style="float:left; padding-left:10px">

[![first milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1627933036/video_to_markdown/images/youtube--dtM57HFt8QI-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=dtM57HFt8QI "first milestone")

