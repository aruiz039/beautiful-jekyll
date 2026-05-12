---
layout: post
title: "Code: Playlistodon" 
subtitle: Striping Youtube links in social media posts into a playlist
#cover-img: /assets/img/hero-image.webp
thumbnail-img: /assets/img/hero-image.webp
share-img: /assets/img/hero-image.webp
tags: [Python, Mastodon, Coding]
author: Alfredo Ruiz
---

Some time back a friend of mine started a local social media website running out of his house just for us. He used Mastodon. One of the things we would do is share music with each other by posting a link and using using a hashtag #TuesdayTracks to mark the song. Much fun was had with it. 

I am normally in serious need of projects to practice my scripting and coding or it leaves me due to lack of practice. So I decided there should be a good way to scrape the page for every YouTube link with a hashtag #TuesdayTracks and send it to a newly created playlist on YouTube. 

For the first part luckily there was a library called Mastodon.py that had the exact feature that would let me pull all the YouTube links from a specific hashtag. 

The next part was authenticating to YouTube which wasn’t as simple and left me reading documentation and watching YouTube videos to figure out how to get that part to run. I had set up the token in google cloud website but was still working on coding it into my script. 

Later in the week I went to an event in where people get together, code and present. There the concept of vibe coding the rest of the solution was presented to me. The phrase had been popping up a lot so I decided to give it a try. At the very least I would be able to see what it suggested and look up references from there to see where to go.

I decided to use GitHub Copilot as my assistant which was easy to integrate into VS Code. I presented a prompt asking for copilot to do the authentication and that is exactly what I was given. A near complete working concept of what I was looking for. It was my first time using a coding agent and it was a little scary to me how it was able to provide a solution so quickly but I was grateful. 

In the end I am glad I got the project to work and appreciate some of the things I learned about using coding agents to make end goals happen. 

### Some of the more technical details i leave for Github
[Playlistodon](https://github.com/aruiz039/Playlistodon)  
