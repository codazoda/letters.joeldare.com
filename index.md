# Letters to Myself

## Sending SMS Messages to Myself
*November 5, 2020 at 6:40p*

Tonight I'm thinking about building a personal social network app. It's not a social network, clearly, but I want to be able to *tweet* to myself. Sending *SMS* type messages to myself. I imagine I may use it to replace this document of letters I'm writing. I think if I move it into the browser it will be a tiny bit easier to do. Also, sending myself short messages may encourage me to do it more.

The app will add my titles, dates and times, like I've been putting in here. It will save it to another text-area and to localStorage. Later I can think about how I want to get it here. Maybe just copy/paste on a weekly basis or something. I'll figure that out later and I'll adapt it as I go.

## Plain-Text ASCII Image File Formats
*November 5, 2020 at 1:45p*

I read this blog post today about a set of simple plain-text ASCII image file formats. These formats are also outlined on Wikipedia. Maybe these would be good formats to use for my TRS-80 project. They aren't small, but they are simple and don't require much processing.

https://www.vidarholen.net/contents/blog/?p=904
https://en.wikipedia.org/wiki/Netpbm

## Bookmarklettes
*October 30, 2020 at 09:10p*

I should start to create a series of bookmarklettes that helps me to write more. One example might be a "notes" or "quotes" bookmarklet that captures the page title, today's date, and the URL and starts a note page about that URL. Then, when I'm done, I can save the note (text file) or copy/paste it. Maybe others would find this useful by itself.

My "what's on your mind" letter from a couple days ago could also be a bookmarklette. As could this "letters" document.

Tonight I created a new repo called `notebook` and took some notes from a Y Combinator post in it. I joined the Startup School for people who aren't ready to start a startup yet. That was the first article in the course. Maybe the course is only a set of articles? Anyway, it's a 6-week course on creating a startup and it's free. I like the idea.

I've had mixed ideas about my *Scibe* app. I'm trying to figure out exactly what that would be. Plain text and simple, for sure. Tags would be helpful. I found that out writing about Y Combinator. Those notes will go in my `read` pile but could also be tagged as "Startup School".

I'm not writing letters to myself as often as I would like. I should be doing this multiple times a day. Maybe a bookmarklette would help. Maybe a reminder too (although it's easy to ignore phone reminders).

I've also been thinking about keeping track of words written as a personal metric. I've got to figure out how to capture that (I could start with using `wc` on my new notebook and expand from there). I also need to decide where to display those for myself. My command line? A TV on my wall? A web page that is my new tab page? One of those. I should be able to hack together something on my Mac Mini using bash and git. Heck, the "new tab" idea would also tell me if the Mac was down. When it dies a little Raspberry Pi should be able to handle the same.

## What's on your Mind?
*October 27, 2020 at 10:50a*

Ask the question, "What's on your mind?" and write it to this file. Sort of a personal social network. Letters to yourself. Tweets to yourself. Whatever.

## State Machine
*October 27, 2020 at 10:40a*

I should learn about state machines. I should write one.

I wonder, how would a state machine apply to the TRS-80 CoCo slot machine? This might be a bad idea, since it's old-school code. I should probably do a state machine outside of this.

## Planning on Paper
*October 26, 2020 at 9:30a*

I read a blog post yesterday that talked about juggling three projects at a time. I feel like maybe that's what I should do. Also, I think that keeping track of my notes on paper might be a good idea. Maybe three small notebooks and a pencil are enough. I could keep a "journal" in the notebooks as I work on the project. That would allow me to summarize everything later too. Plus, I could keep little things like pixel positions and things for my TRS-80 CoCo slot project.

## Mouse Highlighter
*October 26, 2020 at 9:30a*

I should take the Mouse Highlighter extension and turn it into a simple bookmarklet, write a quick blog post on it, and post it on JoelDare.com and then submit it to Hacker News. Maybe people would find it useful. Maybe.

## Hide Fixed Elements
*October 22, 2020 at 9:00p*

I've got this extension, "Hide Fixed Elements by Andrew F". It seems that "popups" were a problem in the old Internet and browser vendors solved that problem. Now, fixed elements seem to be the modern problem. Web pages have rediculous fixed elements that prevent you from reading the page. Sure, you could JUST NOT READ the pages that have those, but they are everywhere. Advertising, floating headers, floating footers, floating video players, you've only got 3 more articles, and it goes on and on. This little extension, "Hide Fixed Elements" makes them dissapear with the click of a button and it's so refreshing. It's available for both Chrome and Firefox. Amazingly, it only has 150 users on Chrome. Crazy, given how useful it is to me. Wish it was on by default.

## Track my Writing
*October 22, 2020 at 8:55p*

I think it would be a good idea to track my writing. I need to do this both at home and at work. I find value in writing as well as reading my words back later. I'm also interested in leaving a legacy of writing that can last as long as possible after I'm gone. I would love for some of the things I write to be useful to others and especially to be useful for others for a long time.

I should write letters, to myself and others. I should write songs. I should write poems. I should write blog posts and emails. I should write and I should show plot my writing on a graph that's displayed clearly and visibly.

## Life Countdown
*October 22, 2020 at 8:50p*

I write a lot at almost exactly 9:00p...

Tonight I came accross [Kevin Kelly's Life Countdown](https://kk.org/ct2/my-life-countdown-1/). I think I should borrow this idea and create my own life countdown, posting it prominantly in my browser somewhere.

## Convert an Image Into Basic Data Statements
*October 21, 2020 at 9:00p*

Today I finished a working version of my toArray.html file, which uses JavaScript to convert an image into an array and then from that into old-school numbered BASIC using DATA statements. The output is in the console and then can be copied over as data to use in a TRS-80 program. This is in my TRS80 project on Github.

The first image I worked on is the most complex image that I'll need for my slot machine app. It's about a 33x89 pixel image. That turned into 89 lines of BASIC code, which is a lot for an 8-bit computer. I think it can deal with that, but I'm not sure how much data it can deal with this way.

One option I have is to write smaller programs that output the graphics to the screen and then I can capture the screen (or maybe parts of the screen) to a machine language file using CSAVEM. That, in turn, would just use a single page of graphics memory when it's loaded. I don't know if all that is necessary yet... if I'll run into limitations.

Another option I have, which I've thought about a little, is compressing the data somehow. But the machine doesn't have a lot of power for compression and decompression, so it would likely be a vary nieve version of compression. Probably about all I could come up with anyway. One idea is to compress all the white space since most of this graphic will be in a single color. That's probably true for most of my graphics, although not all of them will be primarily white.

## Sales Document for an Editor Project
*October 20, 2020 at 9:00p*

I think I should create a "sales document" for my editor app. I can outline all the features I'm considering for the app and have a "sign up for early entry" button. That button would allow me to collect email addresses. Those, I would collect in a simple plain text document and send to manually. A document like that should work fine for lists of 250 or fewer people.

If there is interest, then I can go on to build the app. If not, I can ask users for feedback about what they need in the tool. Maybe I ask the few who did sign up. Maybe I try again with different features.

## TRS-80 Plugged In
*October 14, 2020 at 9:00a*

I got out my TRS-80 yesterday and plugged it in. Apparently I had not packed the TV/Computer switch box and had to order parts for it. It took a couple days to get those parts and then yesterday I plugged it in. After a little bit of fidgeting with the connections, it worked! I also connected it to a modern TV via a coax cable and that worked. It's amazing that the RF connection still works after 40 years.

## Thoughts on Project GUI
*October 11, 2020 at 8:45a*

Today I had a thought about a new GUI that might work for several projects I'm thinking about right now. That GUI is basically just the modern GUI that everything mobile and web browsers seem to be using these days. It just consists of a menu (hamburger or dots) in the top-right corner. That would allow you to see all the commands you could click, including the keyboard shortcuts for those commands.

I could use this design for Ponder (instead of the current file number and arrows). I could also use it for Scribe, using a ctrl-p (or similar) keyboard shortcut to open a little drop-down with a filename search. Then I don't have to design a recursive folder/file structure. Something I'm struggling with at the moment for some reason. Besides, a keystroke would be significantly faster than hunting through a directory structure.

This is also the same way that I use Slack (command-k) and VS Code (ctrl-p), so it seems to be natural for me. Mouse users can still find their favorite commands in the menu. I think this will work well for a lot of things I'm thinking about now.

Besides Ponder and Scribe, I think this would also work well for my BBS ideas. I was looking up homemade cantennas this morning and I think that would be a fun way for people to connect to the Wireless BBS idea I had, which is basically just a neighborhood network node that works line-of-sight and without an internet connection.


## Higley Meadows Social Network
*October 10, 2020 at 12:15p*

Last night I started working on a social network app. I guess I started that on a whim. I was thinking about working on my notion like editor and I switched gears and started to plan the social network app. I purchased the higleymeadows.com domain name some time ago and I would like to host a very simple social network there just for neighbors, and see how that goes.

I do need to figure out what I want to do with my Notion like editor too. That will help me stay organized at work, I think.


## Protect an Old Computer
*October 9, 2020 at 2:20p*

I just posted this message on [Hacker News](https://news.ycombinator.com).

I've got a working TRS-80 Color Computer 1 that was built sometime between 1980 and 1983. This is the same model that I used as a kid. I think my Mom purchased mine second-hand and I obtained and used it sometime around 1986. The one I have now was purchased on eBay about 10 years ago for $1.75.

I would like to put the computer into a working display, perhaps just on a desk somewhere. What should I do to protect it so that it can run for as long as possible?

For starters, I suspect I should condition the power to protect it from spikes. Is a decent surge protector enough?

What are the things that are most likely to kill the machine if I set it up and use it regularly?


## TRS-80 Programming
*October 9, 2020 at 1:55p*

I want to get out my TRS-80 computer and write some working software for it. I *copied* software into this machine as a kid but I never created my own application. I'd love to do that now and be able to run it on the machine that I purchased online a few years ago. That machine is currently stored in a cardboard box in my garage, I think.

I'd like to adapt that machine to a recorder of some sort so that I can CSAVE and CLOAD sofware. I believe it has a mono jack connection. When I was a kid we would connect it to a tape recorder. To record a program to tape we would press *record* on the recorder and then CSAVE onto tape. To load it back we would press *play* and then CLOAD it in. I'd like to reproduce that using something like a digital voice recorder with a mono aux cable.

What kind of software would I write for it? I have no idea. Maybe a little editor would be cool and easy, but the keyboard on the TRS-80 is so poor that it couldn't be used for much writing. A text adventure game would be an awesome demo of the machine. Some art work would be cool too, something similar to what I've been doing with JavaScript in the Splash of Code book. I could also write a program for drawing (maybe pixel art) and/or a program for loading images. How cool would it be to create an image on a modern computer and be able to load that into the TRS-80 and display it?


## Monthly Reviews
*October 9, 2020 at 1:15p*

I should review these letters at least once a month. Maybe that will help me stay in my "creative mode" and remind me to expand on some of these ideas. My idea is that these are just my random ramblings but they can eventually become more complete blog posts.

I also need a blogging platform again. I want that to be on joeldare.com and that's stopping me because I have my wiki and a bunch of other random stuff hosted on that domain. Converting it to a static site.

I added a little "deploy" script to this project so that I can just run `./deploy.sh` and it gets pushed to Github.


## Pure React
*October 9, 2020 at 1:00p*

I've been thinking about React more lately. I've been using React for around 4 years and I just can't bring myself to like it. The other day, however, I was working on a project and thought, "React would be good for this." That was the first time I had that feeling.

So, I decided to write down a list of my React Con's. As I'm writing this, I'm not sure exactly where I put those, but I suppose it doesn't matter. Then, over the past few days, I've started to write a program in React that avoids those cons.

At it's root, React is just a JS framework. It's the way they recommend that you use it and the way that the industry uses it that's bothering me. At least, for the most part. I do remember that I wrote something like, "Created by an evil company" on my list. That isn't going away. React was created by employee's at Facebook and I think Facebook is as evil as a corp as you can get these days.


## Starting to Write to Myself
*October 9, 2020 at 11:45p*

I need to write more. Sometimes It's hard to write because my thoughts aren't polished. So, I've decided to try writing to myself. I'm going to try to keep these letters to technical topics of things I'm working on, or thinking about, right now. I won't talk about my other hobbies unless there is a technical aspect to them. As an example, I won't write about making music, but I might write about software that I've created that helps me make music.
