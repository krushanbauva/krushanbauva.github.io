---
layout: post
title: Google Summer of Code (GSoC) 2018 under CCExtractor Development
tags: [GSoC]
---
It might sound creepy but yeah, getting accepted as a student developer under the program, [Google Summer of Code](https://summerofcode.withgoogle.com/), has been one of the things on my fantasy list since the time I got to know about it.

And finally, after a semester of reduced sleep, increased caffeine, single digit marks and really low attendance, I find myself very lucky to state that I have been selected to work under CCExtractor Development for GSoC 2018.
> I've always found that the harder I work, the more luck I seem to have.

## What is Google Summer of Code?
Google Summer of Code is an international annual program focused on introducing students to open source software development. Students work on a 3-month programming project with an open source organization during their break from university.

As a part of Google Summer of Code, student participants are paired with a mentor from the participating organizations, gaining exposure to real-world software development and techniques. Students have the opportunity to spend the break between their school semesters earning a stipend while working in areas related to their interests.

## How I came to know about it?
I got to know about Google Summer of Code from my elder brother, [Pranit Bauva](http://bauva.com). He has been a successful GSoCer in the past under the open source organization "Git". I couldn't be luckier and well, this time, it wasn't me but my parents who had worked hard: P. He is the one who guided me as to how to prepare for GSoC and well, if not for him, I wouldn't have ever imagined myself writing this blog post!

## Why Google Summer of Code?
In the past, I have written code as a part of my lab assignments and have also participated in some prestigious coding contests, but I've never had any experience of writing code for a real-world software that is under development and is being used by people from all over the world.

Well, GSoC provides me that opportunity and exposure to real-world software development (for example, distributed development and version control, software licensing issues, mailing list etiquette and much more).

Preparing for GSoC introduced me to a new paradigm about building code collaboratively and it has been a really amazing learning experience as of now.

And one major reason which I'm eagerly waiting to write is "FOR THE LOVE OF CODE". After all, what better way is there to celebrate one's love for the code by participating in a summer of code?

## About CCExtractor Development
There are a lot of tools under CCExtractor Development, but the core tool that names the organization ([CCExtractor](https://www.ccextractor.org/)) is a command-line program written in C. CCExtractor is a tool that analyzes video files and produces independent subtitle files from the closed captions data. It is portable, small, and very fast. And it works on all the major platforms i.e. Linux, Windows, and OSX.

## About my project
As a part of GSoC a few years back, the capability of extracting burned-in (hard) subtitles from videos was added to CCExtractor which wasn't supported by CCExtractor earlier and was a computer vision problem altogether. This was done by [Abhinav Shukla](https://github.com/Abhinav95), a former GSoC student, who will also be mentoring my project throughout the summer. [My project](https://summerofcode.withgoogle.com/projects/#6265530407714816) is along the lines of image processing and is to improve upon the existing work, majorly, in the area of burned-in subtitles where I'll be working on to improve the color detection pipeline and also, try and add some more capabilities to CCExtractor. The exact features I plan to work on, are:
- Extract subtitles in case of moving text such as tickers.
- Automatically distinguish between different speakers in case of DVB and burned-in subtitles (i.e. the color-detection pipeline).
- Handle word by word synchronization cases.
- Add support for non-latin languages such as Mandarin.

## What's next?
So my end semester examinations have just got over and I've come back home for my summer break.

The learning curve has been surely very steep and there were even times where I felt like giving up, but isn't that a thing with whatever new skill you develop or whatever new thing you try for the first time? Well, I just see this curve getting steeper and steeper as the project advances and as time passes by, but hey, the steeper the curve, the more you learn and that's what I'm here for!

So, the coding period starts from 14th of May and I look forward to having a productive summer of code. Also, I intend to use this blog to post updates and progress with my project.

That's all folks! Stay tuned.


