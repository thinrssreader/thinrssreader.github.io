---
layout: post
title: "Introducing Thin RSS Reader"
description: ""
category: 
tags: []
---
{% include JB/setup %}

Thin is a minimalistic RSS reader designed to help you concentrate on reading by taking distractions away.

Many people consider RSS obsolete nowadays, claiming it is too hard to use. And they are right, but of course, RSS itself is just a format and has nothing to do with this. What makes using RSS so hard?

First of all, any web app is hard enough, because it is already three levels of abstraction away from you: it is open in a browser tab which is open in a window on your desktop, which is on your computer screen. Crossing these levels requires some effort from the brain. In fact, three levels are already enough to puzzle people without special training known as common computer knowledge. And we didn't even get to RSS yet.

Most modern RSS readers are more or less similar to Google Reader. When you open it, you immediately see that reading is just a small part of it. Everything tells you that RSS is so much more than just updates from a few sites stacked together. The interface is complex and multi-layered itself, so you have to dive even deeper to get to reading.

And while you read, you are constantly tempted to jump one level back and switch focus to navigation. Text is tightly packed inside a box and doesn't look like anything worth reading. So once you lost your focus, you don't really want to go back. As a result, it is very hard to read in such environment.

Since Google Reader is dead, I'll illustrate this with a screenshot of [TheOldReader](http://theoldreader.com), which reproduces classic Google Reader interface including its flaws.

![TheOldReader](/assets/theoldreader.png)

After Google Reader's death, its successors improved its design but basic structure of the interface didn't change. As a result, many people still find it hard to use RSS. No wonder they switch to tools that provide better results, like Twitter and Reddit. The reason these apps work better may be because they force you to follow the link and open actual article, so your reading experience is up to the content providers. And if they are smart enough, their page will provide you with comfortable reading experience so you can read the whole article and feel like you didn't waste your time. Only when you are done with the article, you return to the app, which is hidden away until you need it, to get another link. And all that happens in a familliar context of your browser window. Much easier.

Can RSS experience be improved to match? Thin Reader is a result of my efforts to answer this question. It is designed to help you maintain focus by removing distractions and making text comfortable to read. Every interface element was rethinked to make sure it doesn't get in the way of reading but remains easily accessible when you need it.

![Thin RSS Reader](/assets/thinrssreader.png)

Thin Reader is a fully standalone and independent app powered by its own RSS engine. It provides basic set of features for working with your feeds. You can organize subscriptions using tags or quickly jump to any of your feeds using instant search.

Thin Reader is currently in early alpha stage. It will be significantly improved over time and new features will be added, but it will always be a minimalistic app with focus on distraction free reading experience. Please stay tuned for updates.