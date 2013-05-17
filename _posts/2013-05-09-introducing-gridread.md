---
layout: post
title: "Introducing GridRead"
description: ""
category: 
tags: []
---
{% include JB/setup %}

Recently I launched a beta version of GridRead, a small and simple RSS reader I built in my spare time. It isn't made to 'reinvent' or 'revolutionize' RSS reading experience. It's not designed to be a new industry standard and will never be as feature packed as its greater competitors. Instead, I created it to share a specific vision of how RSS reading should look like. It is a vision I developed over the years of using Google Reader and trying to switch to some of its many competitors.

I'd like to make it clear that the purpose of this post is not criticizing Google Reader, but showing how Google Reader eventually made me rethink my feed reading needs. GridRead is not a Google Reader successor, it's just an app inspired by my experience with it.

The key concept of Google Reader is a continuous feed which enables you to read non-stop. But I never found this design comfortable. The content is too tightly packed. Each story is immediately followed by another story. You're only half way done reading it but the next one is already there to catch your attention, which is especially easy when you scroll. To help with that, Google Reader makes sure you scroll more often by taking away a good portion of screen height for search field and switches you don't use so often.

![Google Reader]({{ BASE_PATH }}/assets/greader1.png)

All these things make reading less comfortable and contribute to shortening your attention span. Navigation dominates the content. The whole interface is about scrolling, switching tags and filtering rather than reading. I ended up using it in fullscreen list view. In this mode it displays only one item at a time. This gave me a huge boost of focus.

![Google Reader Full Screen]({{ BASE_PATH }}/assets/greader2.png)

Of course you can customize Google Reader using custom userstyles but it doesn't solve all problems. I never had many subscriptions because at some point they started to overwhelm me. You can't just scroll the feed and pick items that you want to read, because most articles are too big for that. You need to scroll them fast enough to skip items and slowly enough to see an item you want, but you can only pick one. Long items take forever to scroll. List view doesn't give you any picture of what's inside, and you can't always find what you want by title, especially if you follow image feeds often having no meaningful item titles.

![Google Reader List View]({{ BASE_PATH }}/assets/greader3.png)

This is how I figured out what I need: a compact, easy to scroll feed that lets you pick items to read and separated reading space that lets you focus on only one item at once.

Of course, this isn't new. Apps like Reeder, Feedbin, Google Currents and many others are built around this concept. But I never found a perfect app to switch. Most of them still aren't good enough at visualizing your feed, offering only text previews, others are platform dependent or have other issues like not being able to import all subscriptions from Google Reader at once (surprisingly, this one is Google Currents). I wanted a basic online app with simple and clean look. I wanted navigation that doesn't get on my way. I wanted it to look good on my phone and tablet so I can read from any device and keep everything in sync.

Square previews don't take much more space than text previews but are much more informative and provide you with colorful visual feed rather than a dull gray text stream. They are great for reading webcomics and following photo streams from Flickr, DeviantArt, Tumblr, FFFFound! and many others.

The reading space is clearly separated from the grid and always takes 100% of window height with no panels hanging on top of it, giving the text as much room is possible to breath even on a small screen like 11" Macbook Air. In most cases, items on the left side don't get on the way of reading because you just look to the other side of screen. Of course, full screen mode is available for diving into long texts.

![GridRead and Reeder]({{ BASE_PATH }}/assets/gridread.png)

<img src="{{ BASE_PATH }}/assets/search.png" style="float: right; margin-left: 20px">

Another feature I always wanted to have is spotlight-like instant search. You only need a few keystrokes to find files on your computer, so why not your feeds? Press TAB any time to open feeds list and start typing right away. You will get instant results by any part of feed name, URL or any of assigned tags. I typically get what i want in 2-3 letters.

GridRead is still a work in progress, and I will be adding more features soon as well as improving current ones. However, I will always keep GridRead a simple and minimal app. Coming are versions optimized for tablets and smartphones. 

The app is free until the end of beta stage, but after that it will cost a small fee of $0.99 monthly or $10 per year. I consider it essential to provide the best service for only those who are happy enough with it to support it and I'd like to be absolutely honest about it rather than relying on donations or trying to 'monetize' large auditory of users having very different needs. GridRead will never have a large team or a marketing departement, and will never show ads or bullshit its users in any other way.
Every new user will get one month of a free trial after sign up. Everyone who signs up during beta stage will get a month of free trial staring the day GridRead goes out of beta. After the end of paid or trial period you will still be able to read your feeds but won't be able to add new subscriptions.

I will publish more posts on ideology, development and growth of GridRead soon as well as share experience I got building it. Stay tuned!
