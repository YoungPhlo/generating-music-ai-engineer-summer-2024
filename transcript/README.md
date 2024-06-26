### TXT and SRT files available above - MD under construction
# Intro
I'm excited to be here.
I really have one main goal in mind, and that's for this talk to be, or this workshop to be interactive.
I want it to be fun, and I want you guys to walk away with something tangible.
So I, we can actually switch to the slides.
So it should be live now.
If you guys want to go ahead and go to this link that I have up on the screen or use your phone to go to the QR code, I have some notes for you guys with that URL.
But those are my statement goals for this workshop.
I want to really probably start by asking you guys some questions so I can get some interaction flowing.
But I'm glad you guys came.
Thank you for coming.
I really appreciate it.
The music stuff is something I have been
into for a long time, like lifelong musician, artist.
But the AI music stuff is something I just started paying attention to.
With regards to the tools I'm going to show you today, maybe about a month or so ago.
So basically what this workshop is going to be about is I'm going to start with the insights that I've gained by like doing all the research over the last 30 days, and then we'll get straight into the tools so you guys can, again, walk away with something tangible.
Let's start with...
Okay, by, I know it's early, and I'm still groggy myself.
So, you know, you don't have to necessarily go crazy here, but by show of hands, how many of you have ever used a music generation model, period?
Okay, nice, about half you guys.
That's dope.
By show of hands, how many of you guys use, I had someone in the crowd already say that they use Boomy.
Have you guys ever used Boomy before?
Okay, that's your OG if you use Boomy, because it was from like two years ago, but it was a music generation model that was actually pretty cool, but didn't get as complex as the music generation models that we have today.
How many of you guys have ever used Suno or Udio by showing hands?
Okay, nice.
Okay, so you guys will be familiar with what I'm gonna do today.
Hopefully I can show you guys some advanced prompting techniques at the least, but for the most part, those are the tools that we're gonna be focused on.
I was doing this earlier, asking some of the AV crew what you guys' favorite artists are.
My man right here in the middle, if you could name your favorite artist of all time, what would it be, who would it be?
Yes.
Miles Davis, okay.
And correct me if I'm wrong, because that's a little bit out of my league.
Like, blues, R&B, jazz?
OK.
OK.
I think I have something special for you today.
So let's start.
I can get into a little bit of what we're going to do as well.
And I actually would like to say, because I've already talked about my workshop goal, what I would actually like to say
I am not a classically trained musician.
I wrote my first song when I was 13.
But I welcome any discourse you guys have in terms of accuracy.
So if you guys feel like I'm actually wrong, that's cool.
I welcome that.
And I actually have something for you on that link that I showed earlier where you can submit questions or comments live while we're doing this to either correct me or submit a question or whatever.
So that was one of the main things I wanted to say.
I try to be as accurate as possible, but if I do something wrong, feel free to call me out.
I'm comfortable with that.
I'm cool with that.
And actually, let me make sure I have my stuff pulled up.

# Audience Poll
If you guys can go to this link, there's a link on there that says poll.
If you guys can go fill out that poll, I think there's like two or three questions on there.
If you guys can go to that link now and start submitting your answers, I'd really, really appreciate that.
Again, I want this to be really interactive, but I also want to tailor it to specifically what you guys want to know about AI easy generation.
Now I've done some housekeeping, I can kind of get into my journey here.

# Personal Journey
I would say I'm way more of a, first of all, my name's Flo as you guys may or may not know.
I'm way more of a songwriter than like a software engineer.
But I have a lot of respect for what you guys do.
I know enough Python to be dangerous, but beyond that, I'm not really that good at software design or engineering.
But I, over the pandemic, took a lot of time out to learn how to write scripts, and I'm really moving into automation, so I need Python for automation for a lot of my stuff, daily, personal, life stuff, and stuff for work as well.
The other thing I would say is,
I'm really, really big into experimentation.
Phlo is actually my artist name, and if you go on Google or YouTube or Spotify, Apple Music, you can actually look me up and find my music.
But the truth is that I have a very eclectic taste, and I have experimented in a lot of different genres.
A couple years ago, I decided that I wanted to do some split testing, which is pretty odd for an artist.
But I did want to do some split testing.
And what I really found out was that the same song under two different artists can perform while we debut.
So I literally would take the same recording, like I'm a self-taught engineer, would record it at my home or other studios, and upload it under two different artists' names.
And depending on the cover art, the marketing, who you try and target when you're posting online in terms of the daily content, I would see that songs would perform differently.
So what I basically did was start creating these quote unquote pin names and putting out music that way.
And I actually have a pin name that has way more streams than my actual artist name.
So if you look at me as an artist, I don't have many streams, but I have a couple pin names that have been viral.
I have one that's got like five million streams over the last couple months.
And it's just instrumental music.
So I'm an artist that does R&B and hip-hop, but I experimented with EDM.
I actually have a song with some country influence, believe it or not.
So I've just been experimenting a lot.
And that's kind of how we got here today.
I like to say I was experimenting with multiple genres way before AI music got here.
But I love AI music for that reason.
And this workshop will cover AI music generation and demystifying it.
I kind of like distilling better.
But you know, Taji P.T.
gave me this word, so I put it in the slides.
And we're going to get hands-on with Suno in the video and talk about turning ideas into song.
And then, actually, I have a question about this later on, but I really want to talk about opportunities for using AI music.
I'm super passionate about distribution and for regular, everyday artists to be able to make an income from their music.
So if any of you guys are actually artists, I would love to get into those type of discussions.
Let's see.
Have you guys, did anybody actually fill out the email I was asking about?
Let's see.
I'll just connect it.
All right.
Because I really can start throwing in little tidbits here and there about what you guys want to learn about.
I put like, one of the options that I put for the poll is like an advanced option where we can like actually pull down some of the music that Suno is generating, get stems for that music, and start to like mix and master it.
So I don't know if any of you guys would actually be interested in that, but I put that as.
Yeah?
Okay, awesome.
Yeah, that was the hardest thing about preparing for this.
I just don't know exactly who's going to be in the crowd and what level they're at.
So I tried to come up with a couple of different tracks just for this presentation alone.
But yeah, I just needed you guys' feedback.
So we did do a bunch of solutions.
And it looks like content needs, OK, tweaking, a lot of content needs.
OK, cool.
I have this guy that I call the Pomp Master.
If I show up, how many of you guys are in the Suno Udio Discord server?
Oh, you're in there?
OK, nice.
Even for you, I think I'll have a treat.
Because there's a couple of people in there that have posted since the beginning of Suno Udio.
And this is one guy who's been able to do some really, really cool banjo music and bagpipe music.
That's insane.
But the pomps are very unintuitive, in my opinion.
So you have to see it to understand what it's doing.
So with that being said, I'll make sure that I include a lot of content.
So thank you for everyone that just came in.
I appreciate you guys coming in.
Right, so this actually gets into, you might notice that it's, you might notice that it's okay.
It did actually work, but I still might play with my computer.
This is where we start with the insights that I've learned by studying AI music and how it got to this point over the last couple months.
And then I'll get into, it's kind of painful, but I have to play some videos for you guys to catch up to where I'm at in terms of understanding and how this whole thing developed.
So we'll have some videos to watch, maybe five or six minutes of videos.

# AI Music Definitions
When people say AI music,
I think that can mean a lot of different things.
And when I first started doing my research, it was really frustrating that everyone meant something slightly different.
So what I've tried to do is compartmentalize the definitions of AI music and tidy up the definitions.
Because there was a lot of blurred lines when I started doing the research.
And the way that I compartmentalized this was to say that we have text to music.
where you're generating short samples and full songs using text prompts.
You have audio to music, and this is where you're taking an existing sound and transforming it into actual music.
And you have style transfer, which is basically voice conversion.
And voice conversion is actually the first thing that came across when I found AI Music last year, actually.
So it's been a long time coming, but I didn't really start doing the research until recently.
But I think what most people call AI music is really actually just voice conversion.
It's hard to say that now, but maybe when I started doing research, it was.
But I would say that the general consumer, what they call AI music is mostly just style transfer, where someone puts their voice and converts it to another voice.
And that actually leads into the first video, and I'll go ahead and play it now.
You guys may have seen this video.
It's actually pretty cool.
You might notice that I sound like Kanye West.
No easy.
Could we turn it up just a little bit?
He gets a little louder later.
You might notice that I sound like Kanye West.
No easy to record a voiceover for me for this video.
I didn't learn how to do impressions.
This is AI.
So let me come back to my original voice for a second because this is crazy.
Today on Metaverse, I posted AI Kanye covering a popular song.
Here's an example of him singing.
That's clearly crazy, and I started thinking, you know, what are the implications of this for the music industry?
Now all you have to do is record reference vocals and replace them with a trained model of any musician you like, which is exactly what I did.
I found this Kanye style beat on YouTube.
I wrote eight bars, and I'm gonna record them now, and then I'm gonna have A.I.
Kanye replace me.
I got a fantasy that's beautiful, that's dark and twisted.
But I attacked a whole religion all because of my ignorance.
What was I thinking?
That was submission.
I lost Adidas, but I'm still Yeezy.
Back in the kitchen, man, I'm a genius.
Boys in the hood, just like I'm easy.
Kanye Weezy, South Side of Chicago.
Life ain't easy.
All praise be to Lord Jesus.
Donna, please rest easy.
All right, let me cut it there.
Let me cut it there.
So let's hear those vocals I just recorded now with Kanye.
I got a fantasy that's beautiful, that's dark and twisted.
But I attacked the whole religion, all because of my ignorance.
What was I thinking?
That was some bitching.
I lost some leaders, but I'm still easy.
Back in the kitchen, man, I'm a genius.
Boys in the hood, just like I'm easy.
Kanye Weezy, South Side of Chicago.
Life ain't easy.
All praise be to Lord Jesus.
Donna, please rest easy.
All right, let me cut it there.
Let me cut it there.
Yo, that knew you.
So you guys kind of get the gist of what he was doing there.
But I think a lot of times when we do AI music, that's what it is.
It's like someone taking the regular songwriting process where you go get production or do the production yourself, you write the lyrics and then record your own vocals, and then
What people are calling AI music is really just style transfer or voice conversion where they're taking that voice and turning it into someone else's.
So this is actually the first shout out to this guy's name, Roberto Nixon, if I'm not mistaken.
And I saw this video and it kind of, I think it just definitely changed the trajectory of what I was doing at the time.
I dropped everything and was like, I have to figure out how the heck he can do this Kanye West voice thing.
So I pretty much followed the steps in this video.
I dove into some Discord servers and some subreddits and that's how I really figured out how to do this for myself.
So I think that's one compartment that I've kind of like created for AI music and put it to the side.
The other one, well actually I have a couple more examples of this as well.
I think the next one is,
How many of you guys with a big bunch of other hands, how many of you guys heard that Drake, A.I.
song from the garden last year?
Okay, we got a couple people, nice.
So I'll play it, I don't want to play the whole thing, but again, this is another example of voice conversion.
And a lot of people were saying, oh my god, he pressed a button and generated a whole Drake song, and that's not really the truth.
This kid, his name is Ghostwriter, the person behind the song, and he did an interview where he talked about the process of creating the song, and it was all him, except for the actual vocals.
He changed his voice to sound like Drake in the beginning.
I'll play a little bit of it.
Just
That's actually my favorite part but I'm gonna cut it off.
So the Drake song was interesting to me because I kind of saw an unravel.
Like I think I found the video or heard the song and it was like under a thousand views.
for being posted in some of those subreddits that I was talking about, but it went super viral.
I think he got like 9 million streams in the first 24 hours.
He was on his way, that ghostwriter was on his way to charting, of course, before the RIA got ahold of him and was like, we're shutting this down.
So he got DMCA'd and the song got wiped from everywhere.
You can still find it on the internet, but it pretty much got wiped from everywhere.
And I just thought, man, this is really going to change everything.
But again, everybody was calling it and saying it was AI music without being specific about what kind of AI music it was.
So I have a couple more videos to show you guys, but I just wanted to go over the Drake one, because I thought that was pretty cool.
This next one is actually my favorite example of voice conversion that I've seen to date.
Let me backtrack a little bit.
These two songs that I just played, or videos that I just played, are from roughly a year ago, I think March of last year, April of last year.
Since then, the voice conversion tools have gotten 10 times better, and when I was listening to the Kanye West one back then, it literally blew my mind, no joke, a lot.
And today, I kind of listen to it, and I'm like, oh, it sounds really artifact-y, it's bad, it doesn't exactly sound like a natural human Kanye West.
But today, they have stuff that sounds almost exactly like Kanye West.
And I say the kids because when I joined the Discord server, it was literally a bunch of like 14, 15, 16 year olds doing these conversions.
But the kids have gotten a lot better at like training these models, these voice models.
So the next one is actually my favorite example of voice conversion.
How many, by a show of hands, how many of you guys in here are familiar with Brandy Travis?
Yeah, I knew I was gonna get y'all back there.
Yes, sir.
Yes, sir.
Okay, so Randy Travis, and forgive me, because I'm not exactly sure how this happened, but he lost his voice some time ago.
And Randy Travis and his team kind of saw this AI thing unraveling, or unfolding, and decided to sit down, write a song, produce a song, and then use this voice conversion technique for Randy to sing the song without him actually singing the song.
This is one of my favorite examples.
I think also in the last year or so, the, maybe temperament is not the best word, but the general public opinion about A.I.
music has shifted a little bit.
It hasn't gotten too much better.
It's really taboo, honestly.
I was a little bit nervous about doing this conference, because people just do not like A.I.
music at all, don't want it in their lives.
But since then, this Randy Travis song came out a couple of months ago, or a couple weeks ago, I think it was.
And when I looked at the YouTube comments of this video, the feedback was overwhelmingly positive.
People were in the comments saying, I'm a 75-year-old man.
I'm bawling tears right now listening to this Randy Travis song.
They were like, we don't care how you get Randy, as long as you get him back, we'll take AI or not.
You know what I mean?
So it just was a really cool example of, I think, how voice conversion can be used in the right way by the original artist.
So I'll go ahead and play some of this as well.
They had eyes like diamonds, and caught the light Oh, but they were dark and deeper
Hello, hello, okay.
Sorry, I apologize to the Randy Travis fans in the back.
I'm gonna cut him off a little bit.
I just wanna keep it going.
Even though I'm not super into country music, I thought it was really touching that he was able to get with his team and use AI to create new original music.
I thought that was really cool.
So that pretty much takes care of the style transfer stuff.
I've showed you guys some examples.
The next thing I wanna get into is text to music.
And I'll go over full songs as opposed to
The short samples that I was talking about, if you go, I just want to remind you guys, if you go to the link, AITalk.com slash music, and submit a question on there, I can see a pop-up on my screen, so I can answer it in motion.
I also want to repeat it out loud for the transcription and all that good stuff.
Okay, so.
Text-to-music, text-to-music, text-to-music.
I'm gonna show you guys a couple examples.
I broke text-to-music down even a little bit further by having, I have a couple folders here, and I think the way I did text-to-music was, yeah, meme songs and samples.
Okay, by show of hands, how many of you guys have heard about this Drake and Kendrick Lamar meme going on?
So for anyone who hasn't been paying attention, just know that one man said very disparaging words about another man, and then the internet ran with it.
So I don't have to catch you up on.
18 million songs that these men have recorded now.
I couldn't even keep up with myself to be honest with you.
Basically the internet ran with this whole concept of BBL Jersey and Kendrick Lamar set a lyric in one of these songs that they had back and forth over the last couple of weeks where he called Drake BBL Jersey.
I don't want to explain BBL to y'all.
So I hope hopefully you understand what a BBL is, and they call it BBL Jersey.
And it's funny because it can be taken a couple different ways.
But I'll just play the music.
I'm not rambling too much.
BBL Jersey.
BBL Jersey.
My grandma would probably cut me off if I turned that off early, but I'm gonna cut it there and basically say that
This song was, to me, this is really what gets to what AI music is, because there's a comedian named King Willonius who logged into Udio, one of the tools I'm going to tell you about, typed in a prompt, I think typed in some lyrics, if I'm not mistaken, and generated this song.
He didn't get in the studio, he didn't record his vocals, there was no voice conversion, he just typed in some words and got this BBL Drizzy song.
This is like a monumental moment in music as well because it was one of the first times I saw something like this go viral.
And I think, we'll get into, I mean we can if you guys are interested, we can get into some of the legality of AI generated music and the copyrights around it.
But I think this moment where he created this BBL Jersey song and went viral, it's been used in a bunch of different songs now.
It's like monumental.
But this is text to music.
There was no prior recording.
He just generated this song on one shot, a pomp to a song.
I think I might have one more good example for, you know, I'm going to play this for a little bit.
Eleven Labs is another AI startup that has now entered the text-to-music space, and this is a song that they generated.
Again, no prior recordings.
This is just text.
Music came out the other end, and it went viral on Twitter.
Programming young, dreaming that one day we'd make it work.
Lines of code we'd write all night, hoping that one day we'd get it right.
Can we teach them?
Oh, he was about to get into it.
I cut off a little too early.
But basically, this is a sort of meta song because it's an AI model singing about GPUs.
I thought that was pretty cool.
But yeah, another text to music song that I would kind of put into the meme song category.
That being said, I think I had, oh yeah, so audio to music.
These are actually the most interesting samples, examples, and also assurances, if I'm not mistaken.
So I'll get into some of these.
These are really cool.
I think the people who are like musicians or artists who have a lot of talent already, like musical talent already, are into, let me play this, into this style of music generation because it takes an existing sound and turns it into another song.
An existing sound and turns it into music, sorry.
This is using stable audio.
It's another tool.
It's not Suno or Udio, but it is called stable audio.
And I think this was the first tool I saw that had this feature publicly available where you could put audio in and get a song out or get music out, maybe not a full song.
But I really like this because I think it unlocks a lot of different ways to create music.
So I think that's, I might have one more example to show you guys.
This one was cool, this is also from the Suno team.
Has a post-distable audio.
This one.
Nice, okay.
So I thought that was pretty cool because literally all he recorded was his fingers drumming like that on the desk and then out came this full song with the guitar and all these other instruments.
So I think that's, you guys kind of get the gist of like what audio to audio model generation or music generation can be like.
And I want to say with that, we can get directly into actually generating some songs ourselves.
Okay, we can talk about how it works, but you guys didn't really seem so much interested in the technical side when I was looking at the poll, so I could briefly touch on it, but I think, by a show of hands, how many of you guys saw that Suno and Udeo have been, are getting sued this week?
You guys saw that?
Yeah, the RIAA just filed a complaint against both services.
So, and what they're alleging is that these AI models are trained on massive music data sets that are copyrighted and we are--
Well, not me, don't put me on no indictments.
That's another thing I didn't mention at the beginning, but I have no affiliation to Suno, Udio, Sable Audio, Boomy, no one.
I just like this stuff and learned it and figured it out and wanted to do a presentation on it.
But what they're alleging is that Suno and Udio are infringing on their copyrights by training on this music.
Yeah, we had a comment from the audience saying that the last generation sounded like Tom Petty.
If you are more interested in how these models actually work, the architecture, transformers versus diffusion, I have a link on the page that I mentioned earlier.
If you click on the notes button and scroll all the way to the bottom, I've compiled a list of all of the music model papers.
So if you guys are interested, you can find it there.

# Generating Music with Udio and Suno
Okay, so what I want to do now, as we get into Udio and Suno, there is a lot less people than I thought there was going to be, so this will work well, hopefully.
But there's a business card on the table in front of you, and that business card has a secret code on it.
It's a little PVP, survival of the fittest, like may the best man win.
But if you take that secret code,
go to the link that I showed earlier, let me put it on the screen again, and click on the gateway button, there should be a green gateway button that looks like this, and you put in that code, what will pop up is a username and a password.
If you use that username and password to sign into any of these services, let me try and make it a little bigger than that,
If you want to get into Oudio, you can use Google, Discord, Twitter, Apple.
I've signed up for all the services.
If you want to get into Suno, you can do Discord, Google, or Hotmail, Microsoft, whatever they're calling it now.
And then you can sign in.
So what I did for this presentation, so you guys could generate music freely.
Because I know in the show notes for this workshop, I put that you guys should have your own account.
But I also thought it would be cool if we could do unlimited generation as opposed to what they give you on the free account.
So what I did was I signed up and paid for a Premier account for Oudio and Suno and gave you guys a login just now.
So if you go log in, you can generate music as we're talking about the next couple steps.
Just know that, I think 2FA is on Apple, if I'm not mistaken, so there might be some difficulty getting in, but just try and get into one of these services, then log into Udio or Suno, and then the URL for that, I think I have it here, is udio.com, once you've signed into one of the other authorization services, or suno.com will get you into one of these sites.
Works?
Nice.
Awesome.
We got somebody in?
Oh, another person.
Awesome, awesome, awesome.
Hey, PVP.
Some of you guys might not make it.
But yeah, I just wanted to do that so you guys had a... And actually, what I'm going to do as well, when you guys are in your seats generating songs, there's another link on this aietalk.com slash music page where it says submissions.
What I want to do, we might be tight on time,
But what I want to do is have everyone who generates songs here in person to submit to this link.
It's basically just a Google form.
So you generate some music, take the share link to that music on either service, click on this link here, submissions, and submit your song.
And I think what I'm going to do at the end is just take a random number generator, and two people will be selected to keep access to these two accounts that I set up.
So one of you guys will walk away with like a Suno account, one of you guys will walk away with a Leo account.
And I decided, I paid for the premiere.
I didn't pay for the whole year.
After they got sued, I was like, yeah, I might not want to invest.
So I just went ahead and did 30 days.
OK.
So we can get into some of the techniques.
While we're on this topic, and you guys are hopefully generating in your seats as well, does anyone here have a birthday this week?
Nice, my man, crazy Travis.
What's your name?
Patrick.
Patrick.
OK, I think what we're going to do is generate a birthday song for Patrick.
And I'm going to do that from my account.
Immortalize Patrick.
One more time?
I'll be immortalized.
Yes, absolutely.
Patrick, my man.
Randy, Travis.
Oh, they're going to block that fan.
And music.
I'm not even going to try.
Usually, you can just write it.
There you go.
Yeah, they just, I don't know.
Udio may not be as bad about this.
But if you put artist names, and obviously, now because they're being sued,
But if you put artist names, they have a content filter, you know what I mean, they don't.
Yeah, but I try to put a payment in, because I'm just adding it, you're giving me some info, and then like Detroit style, it always put it.
Absolutely.
I'm going to talk about that as well, like ways to kind of get around the filters.
But yeah, that definitely works.
We had a comment from the audience that basically said, if you change the spelling up a little bit, and then put like the style of music that the artist is related to, you can reduce the scale.
An attorney.
He's a patent attorney, so put that in there.
Oh, shit.
Oh, you're the one suing us.
Let's put in some... Patrick, what do you like?
What kind of music do you like?
Pretty eclectic.
Okay, the band.
Rockabilly is the band.
Which is what genre?
Rockabilly.
One more time.
Rockabilly.
Rockabilly.
I'll be honest with you, I'm lost.
You said the band?
The band.
The band, yeah.
Let's go ahead and generate a song for my boy Patrick.
And then I'm going to take the same prompt.
I'm kind of getting into some of the prompting techniques here.
But you guys are able to see this screen, I hope, and see what I'm doing.
And then we'll play a song.
Couldn't generate that song description name, Rainy Travis.
What about Tandy Ravis?
I think like four or eight.
Who is Ravis?
Listen, brother, just give me my song.
All right.
All right, so I'm not monologuing the whole time.
I'm going to wrap it up.
But the way I think of these two different services is that Oudio is more like a songwriting partner.
They have an experimental model that you guys have access to if you log into that premier account that I paid for.
But the default audio experience is that you generate 30 seconds of music at a time.
And you can either extend that idea, remix that idea, or there's a third option I didn't write here and you can scrap it because a lot of times you get weird stuff when you're not great at prompting.
You can also use in-painting to modify specific sections of a song, like if you want to change or tweak one or two little things.
And then now they have this feature within Udio where you can do the audio to audio and it allows you to upload music.
So if you are an artist and you write songs or have written a song before or spoken word or anything,
I would urge you to try to take one of your creations, especially if you've recorded it, it gets crazy.
If you've recorded some music before, you should take the tempo, the key that that song is in, and your lyrics, and put it into Udio and see what comes out the other end.
It's blown my mind a couple times.
I've taken a couple of my own songs and put them in, and it gets crazy what comes out the other side.
Like, Udio does me better than I do you sometimes.
Honestly, so it's a really cool experience if you have like a pre-existing music you can really play with it a lot.
And in a way that I think about Suno is your in-house music producer.
I like to describe it in a way that I feel like
Somewhere in the system prompt of Suno's model, they have like top 40 music in there.
Because it always comes out really polished and clean.
And maybe it's the way that the data that they put into the model in the first place.
But my experience with Suno has been that it just comes out really, really clean.
Top 40-ish.
One thing it's gotten really, really good at lately is like a side note.
is that when I first, I personally have onboarded like I think a dozen or so people over the last couple weeks because I wanted to understand what is the actual use case for these services.
So I just started onboarding friends and family, some of my music friends, people that are not into music at all.
And what I found a couple weeks ago was that like when I would generate songs, if you're not super specific in counting the syllables in each line of the song when you're getting into the custom mode of Zuno,
The timing of the beat and the artist, quote unquote, the vocals, lyrics, gets super off, really, really, really off.
But they've gotten really good about this lately.
The last couple songs I've generated from Suno aren't off.
The song structure's a lot better, because that's another tip we'll get into.
The song structure really has improved a lot in Suno over the last couple weeks.
But it's more or less the same, just the outputs are a little bit different from what we have.
And now we can listen to it.
So have you guys, anyone submitted any songs yet?
Let me see, let me check.
I was just generating some music for my boy Patrick.
We're going to play that in a second.
But that was the basic tutorial.
It's about as simple as it gets.
It really, really lowers the barrier to entry for creating music.
We can get into some other stuff about like more conversations about that, but I think for now I'll just say that it lowers the barrier.
It makes it easier to create stuff for, you know, specific situations.
Okay, nice, we have a couple submissions.
We have a couple submissions.
But the gist of it is you go to video.com, you log in, you go to this, oh, they used to have, oh, I guess here at the top, it always says recreate.
Then you can type in, oh, what's another one?
The AI Engineer World's Fair.
I'm sorry, a song about the AI Engineer World's Fair.
And I know the organizer Benjamin Dunphy really likes old school hip hop.
So I'll generate a song.
So you come in, you type in your prompt, you hit create.
There's a couple of different options out here.
Again, if you have a free account, you won't need to see this experimental longer song.
You'll be defaulted to the UDIO32 model, but you can come in and write your own lyrics on top of this prompt that you just put in.
Or you can select to only have an instrumental generated as opposed to a full song with lyrics and everything.
So at its core, that's how it works for pretty much all these services as well.
There's not so much beyond that that you need to know to start generating music.
I would argue that there's a lot more that you need to know if you want to get good at it, but that's pretty much how we generate music on both services.
And what I like to do, just to get a nice even comparison and choose the same exact prompt, I'll refresh the page.
Because for some reason, they're really buggy sometimes, where if you generate song after song without refreshing the page, you get extensions of songs as opposed to a brand new song.
But I will go ahead and create based on this prompt.
And then I'm going to come back, because we've now gone through the basic tutorial.
I'm going to come back and look at some questions, because I know some questions came in.
Nice.
And in the meantime, while I'm getting my thoughts together, I'm going to play my song, the song that was created for Patrick.
Wishing him a happy birthday.
Oh, moderation error.
They didn't like your, my Randy Travis.
Let's go ahead and play this one.
It's your day, Patrick, we're singing loud for you Oh yes, oh yes, it's true It's your time, Patrick, celebrate the whole day through
We know, Patrick, you love that rock and roll.
Oh, yeah, yeah, oh, yeah.
And country hits you feel in your soul.
Oh, yeah, oh, yes.
Patrick, what you think?
It's great.
Thank you.
It's a theme song for my sitcom now.
Patrick said it's the theme song for his sitcom.
I'm going to play these other two quick.
I just want to hear what they sound like.
Real quick, if you click on the actual song name, you can see the lyrics on the Suno side.
Birthday candles flame so bright For a connoisseur of music's life Rocking through the day and night Patrick's world is pure delight
I'm going to try the other version and see if, was that more your speed, Patrick?
No, they were both great.
Oh, awesome.
OK, all right.
We've got five minutes left.
OK, so either they generated the same song twice or, yeah, maybe.
Yeah.
Let's see what the AI engineer world's here is on.
And actually, let's address these questions, because we only have a couple minutes left.
And then I'll get into the notes real quick, because I did want to show you guys some of the prompt stuff.
The truth is that I have everything under the notes section, pretty much everything I talked about today.
Also, when the recording becomes available, you can come back to the same page, get access to the recording, and then I'll hopefully have the transcript up in an hour, because I recorded it myself.
But if you come here to this page, aietalk.com slash music, and click on the notes section, and you want to now listen to me talk about the prompts, you can find the prompt stuff yourself.
Not quite all the way at the bottom, but here close to the bottom.
And this is a GPT prompt, meaning you literally can go to chat GPT, use this prompt.
It got a little bit weird, like for some reason when I use these closing brackets in GitHub, it like basically disappears the whole, you won't even see lyrics anymore.
But basically what you can do is, I think even this would work, like GPT-4 is now smart enough to do this.
You can take and you can put in this template, and then actually fill in the top here where it says song description, and GPT will actually produce some coherent lyrics.
And it allows for better music generation when you
come in with the lyrics as opposed to giving it a general topic and hoping it comes up with the lyrics itself, you can kind of tweak the lyrics yourself before you start to generate it.
So that's the GPT prompt.
And then for the music model prompts, these are pretty much just examples of what we just did with Patrick and the AI Engineer World's Fair song.
It's just like a general description of a song that you want to hear, that you want to generate, and then it pops out the other end.
Super pressed for time.
There are some official Oudio and Zuno tips that are very useful as well.
And then here, I kind of want to get into the prompt matching thing, actually.
Philip asked, is there a way to do voice transfer of a more generic voice rather than a specific voice, referring to the voice conversion stuff that we talked about earlier?
And I think the end of that question got cut off.
As you said, like.
Are you talking about doing voice conversion training, like training models yourself, like going to one of the services or downloading the tools?
You literally can just take and blend multiple voices.
So the way that it works is like you need, depending on what service or model you're using or what training tools that you're using, you need like minimum six seconds of someone's voice to start training.
and you get like a kind of coherent model after that.
But what you can essentially do is just six seconds of your voice, six seconds of his voice, six seconds of Eminem, and it kind of blends it together.
Or you can just go to a TTS service and get like an actual robot voice, like a voice that doesn't belong to a real person, and then use that to train on.
So yeah, for copyright purposes, yeah, you can do that.
Okay, what recommendations do you have to help advocate for the responsible and ethical use
Yeah, sorry about that.
I don't know why the questions are getting cut off.
Ethical use of AI music.
That's a good one.
I'm going to be honest.
I'm going to plead the fifth because I'm not a lawyer.
I'm going to be completely honest.
I'm going to be completely honest.
Ethics have nothing to do with law.
Oh, yeah, yeah.
Good point.
What tool generates the best clone voice that can match emotional tone like Kendrick Lamar's Euphoria?
Three switches.
What's the best clone voice?
I would definitely look into RVC.
If you can, you can use RVC in the cloud.
You don't have to, like, when you Google RVC, there comes up a bunch of tutorials on how to run it yourself locally.
You do not have to do that.
You can run it in the cloud because you need some decent hardware to do, like, computer hardware to do it.
But definitely look into RVC.
It's the best right now.
Can we have access to the slides?
Yeah.
And my time is up shortly.
Oh, oh, did my thing go to sleep?
It did go to sleep.
Oh, it said log into, who do you want to know?
Really?
Oh, okay, okay, sorry.
That's my blunder.
That was pretty much it.
Rate Your Music is something you should definitely check out.
What someone basically reverse engineered is that these models were trained on labels from Rate Your Music, so you can almost reverse engineer exactly what sound you want by going to Rate Your Music, typing in an artist name, typing in a genre, or
We're really just typing in what you want to hear and then using whatever labels they put on that music you put it back into the model itself sooner or later.
Stable audio sometimes I think and you can get like very very close to a specific sound.
I don't want to say specific artists but yeah you can get pretty close.
Yes and I was going to get into like the law thing.
You want me to differentiate between ethics and law, and I understand.
But I was going to get into it a little bit, but we kind of ran out of time.
So I apologize for that.
If you guys would like, I love to talk about this stuff all day.
If you want to approach me after the workshop, and we chop it up all day about this stuff, I love it.
Yeah.
And then what I'll do for giving away the accounts, maybe I'll do like a live stream or something like that, and do like a grab everybody's email we submitted.
Because I think we had 12 submissions.
Let me refresh.
I think we had 12 submissions.
And I'll pick somebody and just send you guys.
I'll change the username and password so everybody can't log into your stuff.
And then I'll give you the accounts.
But yeah, I appreciate you guys for coming.
I hope you guys got something out of this and walked away with some music, generators, and stuff.
And I think I'll play a song to go out.
Walking through the fair, copper wires in the air, coders in the screen.
I wonder what we have generated.
Oh, oh, first, because I just saw the question that someone said, stems, how to like pull the stems out and like edit them.
There's a tool, again, not a, like I have no affiliation with them, but you just go to, actually the easy way to do this is let's say we just take this happy birthday song by Patrick, we go to suno.com, all you have to do is suno.com,
sunodaw.com, like literally go to the link where you just generated the song, type in DAW, Digital Audio Workstation, at the end of the URL, not the end of the URL, but the end of the domain name, and hit enter.
And I think it takes anywhere from 30 seconds to, let's go ahead and sign in real quick.
to 90 seconds, I've had to wait longer for some of the songs because it's more complicated to do.
Sorry, guys, I forgot to mention this, but yeah, like if you go and do that, type in DAW at the end of the suno song, it'll pull that exact song that you just generated into this digital audio workstation and give you stem by stem and then let you control the volume of each specific stem.
And by stem I just mean each specific instrument.
They do all the different instruments and then the vocal itself.
So this is a really, really cool tool that I think is like a startup
But it's a really, really cool tool for like being able to get more control out of your generations.
So I just wanted to.
So digital audio workstation.
And you can like.
And let's say I don't like the vocals, but I really like the music.
And this is just vocal.
It's the bass.
Rock tunes flowing in his veins.
Patrick exits through the rain.
Happy birthday, Patrick dear.
Let the music keep you near.
So yeah, that's pretty much how you use Wave.
It's called a Wave tool, that service.
So that's how you can get the stems.
There's also another tool called UVR5, but it gets really involved.
You do have to have like decent hardware, but you can also use like, instead of using like an online service where, I think all the accounts on Wave tool right now are free, but you can use UVR5 locally forever.
It's like an open source software project that allows you to pull stems just like this, literally.
And that's not just AI-generated music.
Any song you can put into UVR5 and get, like, the stems from it is actually pretty cool.
I know.
Yeah.
Appreciate it.
I know they want you guys to go over to the, what was it called again?
Yeah, the general session.
So I'm going to shut up now.
Yeah, I appreciate you guys.
Thank you.
Thank you for coming.
