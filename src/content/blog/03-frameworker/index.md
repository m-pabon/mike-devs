---
title: "How to Stop Being a Frameworker"
description: "Break free from the shackles"
date: "Dec 07 2024"
---
In my software engineering class in college my teacher gave a speech at the end of our very last class that I didn't quite understand at the time. In hindsight, well into my career, it finally clicked and made sense to me. The speech he gave essentially described two kinds of software engineers: 

- *Those who sew the pieces together*
- *Those who sew the pieces*

I'm probably butchering the speech he gave, but I wanted to write a little bit about my journey regarding this topic.

My first full time role in the industry was exciting. I got to work on some cool stuff like audio watermarking technology, metering tech, and even got to build windows/android apps as a means of utilizing some of that stuff. Eventually I moved onto a team that was spearheading the initiative to move teams on to **Docker, Kubernetes, Infrastructure as Code, and etc.** This was a bit earlier on in the DevOps movement so a lot of these tools were unknown to people in the company so I kind of felt like I was on the bleeding edge of tech being on this team.

## Becoming a Frameworker
It was cool, I felt like I was learning so much reading the Kubernetes docs, or learning about building ci/cd pipelines, deployment, and etc. I fell in love with it actually, and gravitated towards mastering these tools and found it fun. This was the start of what I now consider a terrible trend for me. You see, as an early career software engineer 

> The mastery of "developer tools" should really be the least of your concerns

At least, this is a belief I subscribe to now. As my journey continued in my career I went on caring more about the tools that helped me help my company accomplish what it wanted. I started becoming an "Apache Airflow" master, an "AWS" master, a "Spring Boot" master, the "Kubernetes" guy, and etc. 

The reason I described this as a disturbing trend, is because the more involved I got with those tools, the less involved I became with **building software***. You might be thinking that knowing how to deploy an app on Kubernetes in AWS developed using your framework of choice is "building software", and you could be right...but that's not what I mean. What I mean by building software is actually solving a problem using the **ONLY** tool that matters in a computer scientists toolbox, the *programming language*. Believe it or not this is an insanely easy skill to lose.

Fast forward to 2024 when I made this realization I realized there was a whole bunch of things that I couldn't do that I used to be able to back in school.

Here is a few things I noticed about what came of me:
- I couldn't code without "help"
	- StackOverflow
	- AI
	- Aggressive googling
	- Intelligent autocomplete, etc.
- When I managed to muster up the motivation to actually build a side project, the only thing I could possibly dream up were CRUD apps...They were all I knew! And in the modern enterprise a lot of things can actually end up just being CRUD apps.
- I struggled a LOT with basic leetcode problems.
	- Moving onto my next role I knew I had to study leetcode so I started
	- I'm not saying you have to be a pro at these or anything but I do think you should be able to handle leetcode easy's and produce brute force solutions without help.
- I knew how nothing "REALLY" worked
	- API request? Got a basic idea but not really sure about the networking
	- Database drivers? Don't know really...the framework just provides that for me
	- API Endpoint? I mean...the tool I'm using just provides @GET and @POST decorators
	- The list goes on and on
- Any problem I could think of, I just throw my tool/framework at it.
	- I never "designed" anything. I just repeated what other enterprises did to solve their problems.
- I forgot many things from my basic programming 1 course and never thought to use them when trying to solve a problem
	- An example of this was forgetting basic object oriented features like polymorphism, inheritance, etc. Then when I encountered them later in my career in a codebase, I literally didn't know what was going on and had to go back to google to re-learn these things.

I think symptoms like these are the symptoms of being a *frameworker*. A.k.a I became someone who could only *sew the pieces together*...just like my teacher warned me about.

## How to Break Free
Before I continue, I want to mention that I think there is an important distinction between *application programmers* and *systems programmers*.

Both are necessary in the world of software and one group is not "better" than the other. I will argue though that, in the domain of application developers, I think there are too many frameworkers. I think the best app developers, are actually people with solid fundamentals who *choose* to be application developers because they like it.

After finally coming to my brutal realization the question then became...what now? How do I fix this? The truth is I don't have one right answer but I want to share what I think is the answer, and some things I've been doing in the second half of 2024 to address my problem with myself. You can agree or disagree, these are just the principles I'm working towards.

### Learn your programming language
Wait I already "know" a programming language?!?! No, I mean learn it learn it. Yes you can just understand concepts and look them up. This is more so about reducing the friction between problem solving and putting pen to paper. I'm not saying you need to have every feature memorized and every syntactic sugar down, but you should be extremely comfortable with the basics and have a good grip on the language's standard library.

### You have a problem? Solve it.
I think the best projects don't come from cloning other projects. They come from you having a need and using your trusty tool (your programming language) to solve it. And remember not everything has to be a CRUD web app. Plenty of problems don't need a web GUI and a database.

### Learn Fundies
The best way to learn you programming language is to *build with it*. But the best way to learn your fundamentals is to well...learn your fundamentals. Believe it or not, solving real problems does sometimes require the use of data structures and algorithms and some of those other things you might have skipped or breezed over.

I used to say back when I was in school "oh when I encounter a problem that requires graphs I'll just KNOW that and then just google Djikstra's algorithm. It turns out this is so much easier said than done. It can be a true challenge to even recognize that your problem suits a graph focused approach and even harder if you manage to realize that to then apply the theory. This applies with every computer science fundamental.

Anyways there's this nifty [site](https://teachyourselfcs.com/) . It's been a great resource for diving deep on foundational topics in computer science. My approach was to start with the [nand2tetris](https://www.nand2tetris.org/) course they mentioned. It covers building a computer from scratch and my thought is that maybe during the journey I'll find a niche that I'll hit that I may want to dive deeper on, like compilers, or operating systems, or etc.

### Don't Get Overwhelmed
Doing all this in the first place is hard enough, don't make it harder by thinking you need to tackle too many things at once. Pick one of the strategies I mentioned and just tackle that one day at a time. Ignore the noise you hear on twitter like "if you're not doing X you're falling behind". If your goal is anything like mine and you want to "break free" from being a frameworker, it happens little by little. You will become unrecognizable to your former self if you tackle this stuff little by little and look back. 

Remember, [it's more fun to be competent](https://world.hey.com/dhh/programmers-should-stop-celebrating-incompetence-de1a4725)