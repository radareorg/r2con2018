# Behind the scene of: "Unpacking the Non-Unpackable"

## Prologue

Thank you to R2CON team for having me a chance to present these slides in R2CON2018,
thanks to @trufae, @xvilka (where was @zlowram?) for the time to meet you again, and to @condret, @maijin, @jvoisin, @oleavr, 
@mrmacete, @xarkes, @wargio and @jcanto for great support to come long way from Malaga, the rest of you with a great "how do you do!".

The management of R2CON2018 is very cool, it's a hacker event made by hackers, formed by hackers to the hackers, 
so literally I met many awesome people, it's a place where I feel like being home more than my home. So, many thank's to all, we see you again soon!

## The making of the presentation

I was like thinking packers in ELF should be a boring stuff to present, so when @trufae asked me about the time to present, 
without thinking much I just say 30 minutes should be just fine!

...and that's why I was in the deep shit afterward... It turned out that I made 124 slides in the end.

So during R2CON2018, which many stuff was happening over there, I trimmed the stuff into like 96 slides with like around 80 pages of info..

So I felt a bit confident until I first rehearsed myself to talk about this slide, no matter how fast I talk it always end up in 60 minutes. 
..aaand.. to make it worst, I don't have time to trim it more too.. THAT's where the nervous started to kick in!

So, I kinda plastic surgery the contents with here and there, until I have a chance to talk w/ @xvilka and @maijin about this presentation, 
just to make sure that the command that I use is matched to the recent commands.. Well, I was like using radare2 when the name of software was 
only "radare" in FreeBSD and it was like from 2007 (or 2008??) I still have the radare0.6xx something running in my old box too.. 
So, I need to make sure the commands I use is good for its educational purpose to new users, right?

..aaand.. that turned up bringing me into more disasters, like I have to change here and there and added here and there, and I was like about to 
kill myself when @xvilka told me that: "I think you should reverse the slide's colors too.." ..well, anyway ..I tried to fix the stuff that 
I can fix (except that reversing the color.. since I don't know how to do that without risking the whole slides...), 

...then after fixing those, there is NO TIME to rehearse anymore.. so I feel like I am gonna throw up in the stage for sure..

## The presentation

Okay, to make sure the things are prepared I tested the presentation beforehand and it showed up nicely in the big screen..

..but... when the D-day is happening, you just have to meet some failures, and I had one, like... my slide didn't show up..

Struggling a bit on the stage w/ help from pancake, I restarted the OSX session, and there, it's done. Lucky to fix it, but this 
raised by heartbeat like 10 times faster.. The other stuff is the cool headset microphone, seems like the power is off. 
But that was fixed right away..  So, then, it was the moment I see audience, which the light was very bright so I couldn't see anyone well.. 
I feel so happy about it :)

At that time, I started to talk and just talk, and when was seeing @seifreed's iPad time I saw that already 25 minutes!! And 
there are more slides to go.. THAT.. is where my fingers just start clicking pages to skip some slides.. I felt so terrible about 
that had to be done for making adjustment to time.. That's why I work as my top priority to finish the slide to share ASAP.

So.. that is how this presentation goes, more or less..

## The samples

None of the sample used are from any target attack, those are publicly shared hashes, and none of the Non-Unpackable packers
unpacking analysis were posted or mentioned online before, so the R2CON2018 is the first time we announce about this new packer. See
more details in the presentation.

## The feedback

I am now available in telegram, thank's @maijin to set things up for me, people know how my handle name is. 
You can ping me there if I am online. I can not connect to telegram when I am at home due to the ISP blocking and 
still tested fail after going back home. But I can conect it via other networks. So please ping me there to throw 
some question about materials I wrote. You can always reach me in reddit, twitter, emails or others too if you know how to reach. 
I wil help you in anyway I can. 

## Some correction in presentation

- page 12, the screenshot command is correct but in the bottom I typed it wrong, it is supposed to be "pf" not "pff" 
- page 26-27 is the example on how to brute force, it is not revealing the real case
- page 43, some peeps I know is calling ELfEncrypter under different names too like ELfCrypt or ElfJunk, can't find link for it

## Please do not abuse Open Souce

This new packer I announced was used to camouflage the software that was meant to be used in non-abusive way and it also was 
messing with the donation part of that open source software with some stupid packing knowledge..and that doesn't make the author
of this packer earn my respect, and with this moral consent intact I was more than happy to reveal it to many UNX reverse engineers 
and many antivirus product engineers too who attended the R2CON2018. 

So this is for the author: "Open source is meant to be shared for better good, and its donation is the vital aspect to make Open source run. 
What's wrong with you? Please do your work in correct manner in the future and share the code so that maybe people will help
you with more positive and better productive idea."

## Abuse disclaimer

I receive many abuse every time I publish or reveal a Linux public threat new threat vectors or tools or malware, etc. So I am used to it,
so aim myself if you want to get into me. 

DO NOT ever try to affect your destructive act against radare2 community, for they are just cool team who work very hard making a cool 
reverse engineering tool with true open source spirit, and unrelated to the stuff I presented.

## Thank you r2con2018! The best CON I've ever had!

--
@unixfreaxjp
