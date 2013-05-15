---
layout: post
title: "Introducing GridRead"
description: ""
category: 
tags: []
---
{% include JB/setup %}

Recently I launched a beta version of GridRead, a small and simple RSS reader I built in my spare time. It isn't made to 'reinvent' or 'revolutionize' RSS reading experience. It's not designed to be a new industry standard and will never be as feature packed as its greater competitors. Instead, I created it to share a specific vision of how RSS reading should look like. It is a vision I developed over the years of using Google Reader and trying to switch to some of its many competitors, and it consists of all things I haven't found in other products as well as all things I found but didn't want. Here's a brief story of how i came to think GridRead should look the way it does.

I'd like to make it clear that the purpose of this post is not criticizing Google Reader, but showing how Google Reader eventually made me rethink my feed reading needs. GridRead is not a Google Reader successor, it's just an app inspired by my experience with it.

The key concept of Google Reader is a continuous feed which enables you to read non-stop. But I never found this design comfortable. The content is too tightly packed. Every story is immediately followed by another story. You're only half way done reading it but the next one is already there to catch your eye, which is especially easy when you scroll. To help with that, Google Reader makes sure you scroll more often by taking away a good portion of screen height for search field and switches you don't use so often.

![Google Reader]({{ BASE_PATH }}/assets/greader1.png)

All these things make reading less comfortable and contribute to shortening your attention span. Navigation dominates the content. The whole interface is about scrolling, switching tags and filtering rather than reading. I ended up using it in fullscreen list view. In this mode it displays only one item at a time. This gave me a huge boost of focus.

![Google Reader Full Screen]({{ BASE_PATH }}/assets/greader2.png)

And it isn't doing very good job at scrolling, either. It's hard to spot an item when you scroll an expanded feed view, because articles are too big for that. You need to scroll them fast enough to skip items and slowly enough to see an item you want, but you can only pick one. Long items take forever to scroll. List view doesn't give you any picture of what's inside and you can't always find what you want by title. That's especially true if you follow image feeds often having items with no meaningful titles.

![Google Reader List View]({{ BASE_PATH }}/assets/greader3.png)

This is how I figured out what I need: a compact feed that is as easy to scroll as twitter and lets you pick items that look interesting, and comfortable reading space that gives you focus by only displaying one item at a time.
Of course, this isn't new. Apps like Reeder, Feedbin, Google Currents and many others are built around similar concepts. Most of them still aren't good enough at visualizing your feed, offering only text previews, others are platform dependent or have other issues like not being able to import all subscriptions from Google Reader at once (surprisingly, this one is Google Currents).

So I decided to make my own app. I started by trying to get more from previews while keeping them compact and ended up using grid layout. Square previews don't take much more space than text previews but are much more informative and provide you with colorful visual feed rather than a dull gray text stream. They are great for reading webcomics and following photo streams from Flickr, DeviantArt, Tumblr, FFFFound! and many others.

The reading space is clearly separated from the grid and always takes 100% of window height with no panels hanging on top of it, giving the text as much room is possible to breath even on a small screen like 11" Macbook Air. In most cases, items on the left side don't get on the way of reading because you just look to the other side of screen. Of course, full screen mode is available for diving into long texts.

![GridRead and Reeder]({{ BASE_PATH }}/assets/gridread.png)

<img src="{{ BASE_PATH }}/assets/search.png" style="float: right; margin-left: 20px">

Another feature I always wanted to have is spotlight-like instant search. You only need a few keystrokes to find files on your computer, so why not your feeds? Press TAB any time to open feeds list and start typing right away. You will get instant results by any part of feed name, URL or any of assigned tags. I typically get what i want in 2-3 letters.

GridRead is still a work in progress, and I will be adding more features soon as well as improving current ones. However, I will always keep GridRead a simple and minimal app. Here is GridRead promise:

- GridRead will be always as simple and to the point as possible. Its main goal will always be to provide cleanest experience possible. GridRead will never display ads and obstruct your experience in any other way.
- We will never try to build a social platform on top of GridRead. We will never share your data with anyone or use it in any other way. Release version of GridRead will allow you to export and delete all of your data without trace.
- Web version of GridRead will always be free to use. Additional features may be provided for a fee but they will never affect other functions.<br/><small>This is new for you if you've seen GridRead before. I will make a separate blog post to explain why I initially decided to make my app paid and why I changed my mind and decided to make it free.</small>

I will publish more posts on ideology, development and growth of GridRead soon as well as share experience I got building it. Stay tuned!
