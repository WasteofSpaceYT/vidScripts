# Making Twitch in a week

## Introduction
Twitch is a multi-billion dollar streaming platform developed by a team of professionals and currently owned and operated by trillion dollar corporate giant Amazon. Every day, 15 million people log into Twitch to tune into their favorite streams, and about 9 million people host streams every month. It took four years for the project to finally enter a public beta. I'm going to make it in like a week.

# RTMP Server
The first step to any service like this is the backend. More specifically, the server that the streams go to. This is done thorough a thing known as RTMP or Real-time Messageing Protocol. I'm not showing that because it confused me to make.


Unluckily for us, It was made for Adobe Flash and Adobe shut down Flash Player so we can't just go streight from rtmp to browser. We need to convert the stream.


## Converting the stream
It's one line to convert the stream to HLS or Html Live Stream.

# Setting up Viewing Page
The best place to start any project is dead in the middle. That being said, we're starting with the viewing page. It's just a table with a video player and some divs. The chat code is pretty simple, just talks to firebase which is our database. From there it just updates the chat div.

# Auth
Any good service needs authentication to know who's using it and so does mine. All we need is a simple login page and some code to talk to firebase auth.

# Account settings
Every user has their information and you should be able to change it. Profile picture, name, email, and chat color.

# Stream Manager
The stream manager is the same as the viewing page but you can edit the stream title.

# Discovery
Finally, we have the discovery page. Who's live, who's online of the people you follow.

# Outro
That's twitch in a "week". I know what you're not thinking. Can I use this? No. You can't. Bye.