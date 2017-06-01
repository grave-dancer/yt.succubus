youTube.succubus is a botnet for YouTube that can be used to robotically get millions of likes, dislikes, subscriptions, and comments, in minutes with no effort, while you leave your computer unattended.

Try the demo here: http://yt-succubus.com

This demo is not malware, nor is it useful for launching any cyber attacks. Disruptive spam and dislike attacks are intentionally disabled in the demo to prevent misuse. Botnet is used in a sense that this is a network of bots and the intention of this software is not to be used for distribution of malware or spam.

The purpose of this botnet is for security research, to demonstrate the ease of which YouTube is vulnerable to botting.

![Alt text](https://s10.postimg.org/42xqa2qyx/screenshot1.png "Client")

Screenshot: The client software running.

~~~

Existing Problematic YouTube Botnets:

1. Vagex Botnet: https://vagex.com/ - A very problematic botnet, but the most famous publically accessible YouTube Botnet.
The Vagex client is outdated and broken, and comments/likes from Vagex bots don't always register as they should.
It was written in .NET, and it is poorly maintained. There is no support for GNU/Linux or FreeBSD/Unix.

Vagex is closed source as well, and you have to use your YouTube account with it. 
This puts an uneasy amount of trust in this botnet as it has access to your YouTube account information.

2. Paid2Youtube: http://www.paid2youtube.com/?r=brybry04 - Suffers largely similar problems to Vagex. It is closed source.

3. Tubenoia - https://github.com/izspk/Tubenoia - Not an actual botnet. Open source, .NET, but largely out of date and not maintained. 

~~~

The youtube.Succubus botnet is an improvement on existing YouTube botnets, it is an open source Delphi/LAMP botnet 
that is constantly maintained and updated. 

1. Your credits are guaranteed to go towards views, likes, comments, and dislikes.

2. It is not only a reputation based, but a credits based botnet which rewards users with credits for watching videos.

3. Reputation based botnets like these can weed out bad actors who wish to glean credits without watching videos.

4. Credits can be obtained by watching videos. However, credits can also be rewarded to users, or through bitcoin purchases.

5. Existing botnets dispatch bots randomly. This creates problems because YouTube is very good at detecting these bots.
youTube.succubus categorizes your views based on Genre: "Music, VLOG, Anime, Gaming, Beauty, Sports".
youtube.succubus's bots use very intelligent algorithms for determining which videos to watch in a certain category.

6. This works on YouTube videos, as well as livestreams. You can use this to generate false comments in a YouTube livestream chat.

~~~

Once you set up a server, you can host client software to be downloaded from that server.
Those who download the software will willingly join your botnet, and will be used as bots to farm the likes and views.
They can also add their own videos to be watched. They spend credits on these videos but by watching videos, they gain credits.

You can view the status of your botnet from the C&C, ban members, customly control aspects

The botnet includes three components:

Client: A CEF (Chromium Embedded Framework) based Web-Browser that views YouTube videos
based on instructions given from your Master Server, and it is written in Delphi using the Lazarus Object-Pascal IDE.

C&C: A PHP frontend you can run on a VPS, that allows you to command and control the botnet from your server. 
You can see the status of the botnet here and perform administration tasks. 
Users can also optionally use the web interface to register accounts and view and edit their accounts.

Server: LAMP based server software. You can run this on a VPS.
This dispatches bots depending on the videos which need to be watched, and it rewards the bot with credits.
It also performs backend work such as checking for bad actors and handling Bitcoin transactions.

~~~

Terms of Service:

1. This is only a working Proof of Concept. Do not use this to spam or flood YouTube like a script kiddie.
I like writing software to test the security of YouTube. (See xtal-Medusa)

2. Reread #1. Please do not use this botnet to flood videos with dislikes and hateful comments. 
I have included the functionality to allow bots to post critical comments and dislikes, but this is only for a proof of concept.

3. If someone has flooded your video with hate comments, dislikes, or is harassing you using my software, or is being a dick, 
then I am literally not responsible. They can't read. Sue the failing American Education system for that, not me.

4. The software is BSD License. If you wish to use this in your own project, freeware or commercial, you can.

FAQ:

Q: How do I get this to run?

A: The Chromium libraries are too large to include in the GitHub repository. You need to download them here: http://swan-sec.com/projects/yt-succubus

Q: So how do I get people to join my botnet?

A: The client is included. You just host a website and allow people to download the client. Be honest with what it is.
Alternatively you can write your own client if you wish, if you think of a better way to get people to use this botnet.

Q: Why is this triggering my antivirus?

A: Sadly, I have to mention this in every repository with Pascal/Delphi. 
Delphi is by reputation, a malware language. Many programs written in Delphi may trigger antivirus software. 
This is because you could trick someone into running a Delphi program that infects the Delphi/Free Pascal compiler and infects all other
Delphi programs with malware. Delphi is used by many skids on Hackforums to trick newbies learning this language into installing trojans.
There is a still-active worm for Delphi-like compilers that can be used to trick unassuming Delphi programmers into installing malware.

Q: So what do I do if the program is flagged and quarantined by my antivirus?

A: Unquarantine it and allow it to run, duh?

Q: Why should I trust your software again?

A: Well, I've included the sources and I allow you to compile and run it yourself. I don't know what else to do. I promise you, this isn't malware.

If you have questions, message Fawn at network.succubus@gmail.com. Thanks! (^-^)^

Reference:

https://en.wikipedia.org/wiki/Computer_Misuse_Act_1990


