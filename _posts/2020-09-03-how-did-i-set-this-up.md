---
layout: post
author: bora
category: how-did-i
tags: [jekyll,]
---
I was thinking about it for a long time but now I'm actually taking action and making it happen. It just took a while, like 2 years.. I first thought to have a blog in 2018 when I was a sophomore in university and full of all sorts of crazy ideas. I wanted to make lots of applications and shot lots of videos for YouTube, and eventually gain some online presence. Unfortunately, I'm lazy.. That's why it took years for me to setup a simple website :/

I want to make music videos. I play the guitar and sing songs. But I'm lazy. I'm out of practice and do a lot of mistakes when try to play something decent. That's because I should have spent at least 30 minutes every day practicing the guitar. But I watched YouTube videos with that time instead.

Still, I am not completely useless... I do programming, sometimes. I am not consistent about practicing it either but I know how relatively complicated things work, like rendering and simulating physics for a game or removing noise from an image. I just didn't do any of them myself. This is because, well, I'm lazy. You probably must have got that by now. However, I don't want to be lazy anymore. This is partly why I started this blog. Because being lazy is just the first part that I don't do useful things. I actually don't do much because I know that I will not do well in my first a few tries at a new subject and I don't want to do work that ultimately be thrown out. But if I write about my experiences somewhere, I will be less likely to do same mistakes twice and all the work I do won't be wasted, it is just going to transform into blog posts as experience. 

So this is sort of me starting an online diary. I do it mostly for myself, but if it happens to help some people on the internet someway, I'll be delighted.

Rest of the post is about how did I setup the blog, like technically. So feel free to leave if you're not interested.

---
{: data-content="the technical bit"}

First of all, I didn't want to use anything that uses relational databases or server-side scripting languages. These technologies are driving the internet for sure but do I need them? As a hobbyist who  wants to just put something on the internet, no not the slightest. I only need a way to put plain text articles that I'll be writing on Notepad into a template HTML code and save them as individual HTML files that I'll be publishing on the web. Easy enough. _Someone must have thought about an out-of-the-box solution for a task that easy,_ I thought. Yet I haven't found any tool to do it for me on Windows. I tries a couple of these tools but most of them have so many dependencies and I don't want to install all these dependencies just to have some text files to pasted in a template.

At some point, I thought about writing my own tool but I quickly realized that I'm getting carried away. So, I stopped thinking too much and installed Windows Subsystem Linux, which is a just neat way to run Linux kernel in Windows. I installed Jekyll on it, which is a static site generator. That was the thing I was trying to do.

At the beginning, all I wanted was to read blog post from a .txt file and paste it in place of some marker text like `<<INSERT CONTENT HERE>>` in the template to form a complete document for that blog post. Well, Jekyll does better. It gives me the tools to build and test a website more quickly. There's loads of ready-to-use Jekyll themes which are serves as sort of a template for your site, but I preferred to write all the code myself like I would do otherwise.

So I opened the Linux shell and typed this code:
```
jekyll new boraozdogan.com --blank
```

That gave me a basic setup. No themes, no pre-decided stuff like how my pages should look like. That is what I wanted. Because I hate when websites take ages to load and I don't want to have one of that sites. I think the developers would be lazy to do these slow sites that sometimes it doesn't even worth waiting them to load. And I also want to go through the whole process of designing and coding. Maybe along the way I'll have a better understanding of why devs do what they do.

