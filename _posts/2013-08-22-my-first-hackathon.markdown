---
layout: post
title:  "My first hackathon"
date:   2013-08-22 16:04:10
categories: blog
tags: hackathon
---

Last Saturday participated in my first hackathon. It was the MoDev hackathon - part of the MoDev Tablet Conference 2013 in Seattle.  I decided it would be a good first hackathon because it was only from 9-5, no crazy 24 hour coding marathons! Plus it was at Amazon in South Lake Union - so a good location.

Some of the other ladies from my CodeFellows Ruby on Rails boot camp also attended - so I wasn't alone. Of course, being a former program manager - I had some options planned out:

**Plan A:** try and join a team of experienced developers - to learn from them.

**Plan B:** join up with some of the other CodeFellows attendees.

**Plan C:** build an app on my own (as a last resort if plan A or B didn't work out)

As we were waiting for the hackathon to begin - we talked with the event organizer and some of the sponsors. The organizer encouraged the Codefellows attendees to split up into multiple teams (giving us a better chance to win prizes).

At the beginning of the hackathon - the different sponsors demoed their products and announced the prizes they were awarding for winners of mobile applications that used their products. The overall prize was a trip to CES in Las Vegas and a spot in competing at the hackathon at CES for a grand prize of $100,000.

The sponsors included Buddy (giving away prizes for using their back-end services), Mashery (prize for using one or more mashery API's), Amazon (prize for developing for Kindle or using Amazon services) and Microsoft (giving away a surface for Windows 8 Surface of Phone apps).

After I heard about the Surface as one of the prizes - I decided to move to **Plan C** and build a C# app targeted for Windows Phone 8. I know that Visual Studio has a great IDE for building out the UI and I should be able to plug in code for API's into the app - should be a piece of cake!

The coding began and I mapped out some user stories for a social running application - which allows people to find training partners for long runs as they train for marathons. I planned to use the Mashery Active.com API to pull in the marathon information. And use Buddy for the user info and leaderboard.

First step was to install the Visual Studio phone SDK. Since my laptop was running Windows 7 - I had to install the sdk for Windows Phone 7.8 - which would also run on Windows Phone 8. The coding deadline was 5pm and it took me until ~1pm to get my dev tools installed. It had been a while since I coded in C# .net (and then I had only built prototype apps - and no phone apps) - but I decided to dig in and see how far I could get before the 5pm cut-off. For the next hour or two I tried to integrate in with Buddy for the user api - but ran into issues because of the SDK version I was using wasn't compatible with the Buddy SDK. So I decided to move onto the Active.com API. I was able to get access to the API and build out a call to retrieve marathons, although I ran out of time before figuring out how to integrate in the phone app. I moved on to mocking up the UI for the app - so I could have something to demo on the emulator. I was running out of time, so in the last 1/2 hour coded up enough for a demo. And built out a PowerPoint slide - for the 2 minute demo at the end. At the last minute I decided on "To the Finish" as my application name.

At the end after the coding cut-off each of the teams demoed their applications. There were some great applications. There were 3 fathers who brought their children and built applications with the kids - they all did a great job. There were 4 applications total built by the Codefellows women - so we had pretty good representation. I quickly demoed my application - focusing on the user experience and the problem I was trying to solve.

At the end of the demos - the judges went off to select the winners of the different categories. I ended up winning a Microsoft Surface RT from Microsoft - I was very excited and am excited to build my app targeting the surface.

##Here are some key lessons I learned from my hackathon:
* don't be afraid to try and build something if you are a beginning developer - due to the short amount of time, most people won't have a fully production ready application. And everyone is very supportive of new developers.
* come prepared with your development environment setup - that took a large amount of time
* use some of the technologies before the hackathon - you can't actually write code that is used in the hackathon before the start - but you can practice and become familiar with your dev tools.
* make sure you pace yourself and watch the time - make sure you have a cut-off point so you have something working to demo. They key points seem to be demoing functionality from a user perspective (but you don't need to have details like login, etc. figured out).
* be sure to have fun! It is stressful because you are working under very tight deadlines - but remember it is something you are doing for fun. It won't be the end of the world if your app isn't perfect.
