---
template: BlogPost
path: /2017/08/26/seven-things-i-learned-making-a-chatbot/
date: 2017-08-26T12:12:39.632Z
title: Seven things I learned making a chatbot
metaDescription: >-
  I work at for a book publisher based in London. We recently developed a
  chatbot for Facebook Messenger and I wanted to share a few useful lessons I
  learnt from developing and deploying it.
thumbnail: /assets/c3482-1omksnab6z6shhwsunt8zxg.webp
---
#### I work at for a book publisher based in London. We recently developed a chatbot for Facebook Messenger and I wanted to share a few useful lessons I learnt from developing and deploying it.

The chatbot is focused on helping users find their next book to read our a gift for someone else. It’s still early days and we are constantly refining and improving as we go.

Whilst we’ve developed a custom chatbot CMS with the[very talented guys at BAM](http://bam-mobile.com/)that allows us to updated it theses lessons are equally valid for chatbots built upon other platforms like Chat Fuel.

#### Don’t forget about the chat

It’s is very easy to forget that users will want to chat with your chatbot. Even though Facebook is moving towards a button driven interface, many of our users are typing in sentences about what they are looking for and it’s more conversational than I’ve seen in search.

When we started internal testing we were all typing in keywords that we knew would work. As soon as we went started beta testing and opened it up to users they were typing in sentences and chatting with the bot. We made a small tweak and added an extra 130 keyword triggers which have improved this.

The one exception to this rule is competitors, they almost always use the buttons and one keyword. It’s super easy to spot them 😉

![Image: Tomy Chatbot, Michele M. F.](/assets/f3f79-1ar8huvi8rb0jsa6rnkkxnw.webp "Image: Tomy Chatbot, Michele M. F.")

<!--StartFragment-->

#### Focus on one task

The most successful chatbots are all very focused on one useful task. Our task is helping users find a book to read or a gift for someone else. The workflow for finding a gift is very well suited to a chatbot interface as it can be button driven or users can type in what they like.

Chatbots are a new interface and although quite simple it’s very easy to lose people if they don’t know what to do. The opening message you send a user should give them a very obvious cue to what they can do, before you progressively lead them towards using text.

I still don’t think we’ve nailed this yet, but we keep testing and learning.

#### Test early and build in several rounds of changes

Like every other product you build being as agile and data driven as possible is key to improving.

Depending on how you’ve built your chatbot and the platform you use it might be cheaper in the longterm to build the tools that allow you do this yourself. We’ve built a pretty flexible framework ourselves and make good use of our APIs.

#### APIs are very helpful

I don’t think this would have been as easy or even possible if we didn’t have APIs to use. This includes both internal and external APIs. The inernal APIs allow us to serve up bespoke custom collections of books, but also give access to our entire catalogue for boarder searches.

For external APIs we make use of Goodreads and Tastekid. They are both really useful and help provide a fuller experience for our users.

#### Dropping people directly into a chatbot from advertising isn’t always ideal

One of these first things we did to drive traffic to our chatbot was to use advertising on Facebook to drop users directly into messenger asked using our chatbot. This was a step learning curve!

Most users aren’t used to chatbots yet so it can be really confusing to drop them in with no setting of expectations or a clue of what they need to do.

We soon learnt that were needed to give users clear signposts in there form of quick links (buttons) and reality obvious copy.

Facebook has added new functionality that allows you to drop people into a deeper part of your chatbot. Whilst we haven’t experimented with this yet it’s a nice way of getting users to the part of your chatbot you want them to visit.

![](/assets/88a7d-1hmwh2aryohzc6jru9jz_jg.webp)

#### Keep it on rails

You have two choices when it comes to deciding on what type of chatbot you want to build, AI driven or on rails. If suggest that unless you have a lot of time and a reality great internal development team that on rails is the way to go.

It allows for a more controlled user experience and you can to a degree’fake’ AI with smart word recognition and responses.

An on rails experience can lead a user into deadends which is frustrating and often results in them abandoning your chatbot. You need to plan to avoid this by carefully constructing your responses to unknown queries with open questions to get them to try again.

#### Add moments of magic

We have added in a bunch of responses to random words users might type in. These responses can result in some very magical moments when the user is given an almost perfect response.

Having these responses also helps you avoid deadends…

#### No dead ends

Nothing frustrates more than hitting a deadend in a chatbot. As a user you are either left to go back a step, or even worse to the beginning.

Trying to avoid this is far harder though and sometimes you can only make the experience better for the next user.

#### Analytics

I don’t think anyone has completely nailed chatbot analytics yet. We are using a combination of custom and FB Insights. Most of my actual learnings have come from actually checking conversions and understanding what users are trying to do.

In the long term I don’t think this is going to be that scalable so I’m on the hunt for a better solution.

Building a chatbot has been a very hard, but rewarding experience. The conversational interface presents some unique challenges but has really made me think about what users are want, which isn’t always that obvious when you look at heatmaps or analytics.
