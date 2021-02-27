---
layout: post
title:  One email not responded
date:   2021-02-27 18:05:55 +0300
image:  '/assets/img/thanhy-nguyen-unsplash.jpg'
tags:   [remotework, workingmodel, agile]
---
I have always thought that not answering emails is quite impolite, you can think about the trivial and naive analogy with verbal interaction: would it be normal to consciously ignore someone who is going to your desk to make a question? I don't think so.

But, lately, I am thinking that the impact is far beyond that aspect, especially ~~after~~ during the Covid disruption, I will expand my humble opinion about it in this text.

---

## Async foundations

First of all, some background about me that will contextualize the analogy: I have been working during the last years on data integration in the tech function of a big company, and I see more and more parallelism on how software communicates and how people do it. 

Second, the foundations about communication. As we learn in school, communication consist on sender, channel and recipient. And, for the sake of simplification, it has two flavours:

* **Synchronous**: where the sender needs to be the recipient actively receiving the information and typically waits for acknowledge.
* **Asynchronous**: the sender deposits the information on the channel and the recipient will eventually process it.

Data integration in IT, in essence, is the investment that the company put to gain efficiency, stability and enable value in the interaction of the different IT systems. Not having systems properly interconnected could lead to business disruptions, inefficiencies and slowness. Also, not being able to convert information into value. What are the most valuable information systems in the company? The employees, the humans, they store the most important knowledge for the enterprise. If the interface to exchange information to take decision is miss-functional... most likely it will have implications on the overall functions. Why the companies don't make the investment in improving communication proportional to that fact? 

**Important disclaimer**: to avoid loosing the track of over-analysis we need to be cautious of not creating some perverse framework to measure employee interaction... One simple eNPS can give you similar conclusions without create a potentially toxic foundation. Micro-management can be always the hidden trap in any efficiency improvement exercise.

In any case, I consider that companies could invest more on it; not by adding more and more tools that will fragment and create a noisy environment, but good practices about using the communication channels and technologies and not that much controlling the usage of it. 

I see two main reasons to take care of it

* **Talent retention**: engineers hate meetings, analytical people loves focus time and hate waste
* **Scalability**: you need to hire engineers to be a digital company, if the communication flow is not healthy, it can become the bottleneck of scalability. i.e: needs 4 meetings to synchronise one change in a system

## One email not responded

Sound harmless, right? Yes, it is, we are humans and we must be allowed in the imperfection. But the problem comes when it is systematic with some people who handle mail in "best-effort mode". Implicitly, they are degrading emails as 2nd class channel, diminishing its credibility. In other words, next time, instead of sending an email I will open you a chat or I will arrange a meeting in order to make sure that I am transacting the information. And this the first time that we can visit the nature of the different channels

* Mail - async
*  Messaging  - typically async
*  Meeting - sync

In other words, the culture of not responding emails leads to more meetings, and this isn't a joke, engineers leave companies due to the avalanche of meetings.

Following the analogy with data integration, real time integration is prevailing to the batch integration; basically, the faster the machines integrates, the more efficient you'll make your business. But, it does not apply to emails, since context switch is really expensive in human beings: you can end up by doing 'email driven development', I personally prefer to batch email management.

## Modern messaging tools to the rescue! or...

In order to minimize the humungous amount of emails, "chats from the future" tools like Slack or Teams are supposed to replace big part of the email exchange. Actually, the main commercial claim is: "start the adoption of younameit to minimize the overwhelming amount of emails!". Not bad idea as concept: native concept of thread, modern in the conception, friendliness and tons of gifs. But, the reality says that, if you don't put some guardrails about the usage of this tools, you are moving the same problem to another place. You will have millions of notifications that will eventually ignored, or muted if you want to dress elegant.

Actually, there's no consensus if messaging tools should be considered as synchronous, semi-synchronous or async. The engineering mindset is moving to the extreme on this regard with this line of thought with [nohello](https://www.nohello.com/) . I personally don't see that bad the human protocol of politeness.

If we consider it as an asynchronous way of communication, I see more natural de old but functional concept of inbox,  where new items pile at the top to be processed.

## Asynchronous way of working

In IT, typically when you want to scale a system, you try to decrease the level of coupling by making asynchronous integrations. Simple: with synchronous you need at least two actors and the same time, with asynchronous, only 1. You might struggle with transactionality - making sure that the consumer receives the information - when working asynchronous; that is a fact, if we move this to the people communication analogy... yes, you might need a meeting when you are communicating something critical that you need acknowledgement or interaction with the recipient.

Nowadays, that the companies wants to be more digital and they are hiring more and more engineers to achieve this objective, being aware of it is important. The basic hints to take into consideration the asynchronous working model:

* Usage of collaborative documentation tools, documentation before communication
* Consolidation communication channels
* Guidelines for using meetings: define agenda, purpose, actions, invite only needed people (...)
* Guidelines for using emails: be clear on the purpose (inform, request action, request information...)

Opensource movement can be a good reference about it, it started already distributed and async, and they are quite mature on creating software minimising the synchronisation points.

## Co-location

In any digital transformation of any company... agile transformation came with it, and this included the [agile manifesto](https://agilemanifesto.org/iso/en/principles.html) . Let's revisit this statement "

> The most efficient and effective method of conveying information to and within a development team is face-to-face conversation.

Basically, co-location was fostered assuming that synchronous communication was needed. This has condition hiring strategy or any working model to scale digitalization across the companies.

Obviously, this statement is quite outdated already, bearing in min how fast think changes in IT... but, now, re-think this sentence during Covid times where fully remote is becoming the new normal. I personally have strong doubts that 100% remote is here to stay, but I am clear that some part of this change will stay forever. It is funny also, how some people where defending open spaces setup in offices to foster the interaction; and now, the same people defend full remote.

My take on this, that there are two fundamental factors that are crucial to determine the importance of co-location:

* **Type of work**: it is not same a creative process - that might require rapid interactions in the iterative process to improve the result -  than one analytical process that requires focus.
* **Scope**: co-location in limited scope (team working on the same product) where rapid interaction is needed.

Also, are planned war rooms something from the past now that we observability capabilities to anticipate and alarm about the issues?

## Am I exaggerating?

Yes, most likely 🙂, at the end the intention of the post is to inspire some reflexions by being provocative.

Jokes aside, it is not only the efficiency or scalability of the company; more importantly, the happiness of engineers to increase the focus and limit the waste.

Also, the common secret to any debate: **balance** and **common sense**. Yes, we've seen other scenarios where one endless mail chain with 30 recipients could be addressed with 2 minutes meeting. But, still, more often "this meeting could have been an email".

## Humanity

Following this line of thinking, if we, the humans, act as machines... we would be more efficient, more productive and better taking decisions, without any bias involved on them. That's the paradox, excellent workers but probably not the best place to work in.

But we should not forget that in many, MANY cases the most important part of any work is how human beings establishes relationship to be happy and engaged. Purpose is connected to the feeling of belonging, and typically this is derived from relationships.

We should find the balance of being rationale and finding the science behind communication without loosing any point of humanity.

For this, small-talk in the office turns crucial to me; and this backs my idea of 100% remote will not be here to stay after Covid.

