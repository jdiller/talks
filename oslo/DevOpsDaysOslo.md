autoscale: true
#[fit] Complaining is not A Strategy
### OR
##[fit] How to make things better, even if you're not the boss.

---
# Hello, I'm Jason Diller

* From Toronto, Canada
* 20 years in the software business.
* 13 as a developer
* 7 as manager.

Currently Engineering Manager: Incident Management at PagerDuty
@jdiller on Twitter

^ Hello everyone. My name is Jason. I'm an engineering manager at PagerDuty working out of our Toronto office. 
I come here today to talk to you about how YOU can make improvements in your own life. I've been on both sides of the worker/manager divide and have always cared about making how we make software better. I've tried a lot of things and I've made a lot of mistakes. I've also had some successes.  I'll share with you what has worked for me and what hasn't. I'll explain how to pitch me if I ever end up being your manager.

---
# So You Want To Make Things Better...

^ I'm going to go out on a limb and make a big assumption. The assumption is that there's something about your job that, if given a magic wand, or just some time and autonomy, you'd make better. If that's not you and everything with your technolgy and culture is perfect, please come find me after, I wish to learn about this magical wonderland where you work. 

^ If that IS you, I'm going to further guess that you're dealing with one or more of the following situations..
 
---
# Complicated Code Base
![](complicatedwires.jpg)

^ The team works on a complicated code base. Maybe it's a ball of mud. Maybe it's a monolith. However, it's shiny. It's a product, it's in the market, it has customers, but its engineering is kind of a mess. It was originally hacked together by the founders or the early employees and sort of grew orgaincally from there. Over time it's had features and bug fixes bolted on and now it's grown to the point that it's getting pretty hard to work with. 

^ To make it easier for you for and your colleagues, you'd like to address this. Spend some time refactoring, adding tests, whatever...

---
# The Processes Hurt
![](waterfall.jpg)

^ The project management practices you use, if any, aren't a good fit for your team. Maybe it's waterfall, maybe it's "agile" but poorly implemented. Maybe, like a lot of companies, you started without any formal processes and it was great but you've grown and now that's starting to hurt too. You have ideas on how it could be better.

---
# Silos and Walls
![] (silos.jpg)

^ You've got communication problems. You've got silos. You're still throwing things over the wall and you want to stop.

---
# Something else is wrong
![] (brokenbulb.jpg)

^ Maybe it's not one of those things, maybe it's something else. It doesn't really matter. The point is, you want to make things better.

---
![] (manager.jpg)

^ But, in order to do that, you need to convice someone. They may be your direct manager, or a product person, or even the CEO, but one way or the other, you need to make your case. How can you do that?

^ I'm making the assumption that the person isn't this guy, that they're at least somewhat reasonable and not a complete buffoon.

---
# Flex your empathy muscle

^ DevOps is about empathy. We talk a lot about it, but we often limit the conversation to empathy for our technical peers. Agile talks about empathy for the customer, but we often don't think about the business as a whole.

^ Each product owner, engineering manager, sales person, support person has a job to do. We might think they're clueless, non-technical dolts but they're experts in their area and they have objectives of their own to think about.

^ They're probably not actually trying to stop you or get in your way. They don't wake up in the morning and think "How can I ruin Jason's plans" or "I'm sure glad we have a monolithic code base and I intend to keep it that way!"  They simply don't see the world the same way you do. That's important for you to think about when you're talking to them. They have different contexts, goals, and objectives.

---

## Build your case - but don't ignore the needs of the one you're convincing
* What are their current objectives?
* How does your proposal impact them?
* How can you find a way to get them what they want?
* Why should we do this instead of something else?
* Can you prove it's worth it?

^ If we're making a case to someone, it's important that we don't just talk about ourselves and what we want. We have to try to understand what our stakeholder has on their plate. Remember that whoever they are, they're answerable to someone for some kind of deliverable. Even the CEO is usually answerable to the board of directors. It's important not to ignore this.

---
# Win-Win
## Literally one of the Seven Habits of Highly Effective People
 
^ Trying to find a win-win scenario where we can give our stakeholder something that they want while we accomplish our objective will go a long way to convincing them. 

^ Whatever it is your company does, it's almost a certainty that you are not selling your customers a not a nicely factored set of microservices. Your product is not a continuous delivery pipeline. Your customers do not care about how well you're following the Scrum Guide. Those things are a means to an end. They are important practices, but they are not what gets you paid.

^ Your stakeholder has to think in terms of business priorities. That's their job. While it's not your primary job, you have to think about those too. It may not be what gets you up in the morning. You might say "Jason, I just want to leave business to the businesspeople". That's fair. But, I assure you, the better you understand their world, the more you can speak their language, the more effective you will be at making positive change.

^ This isn't easy and it won't always be possible, but win-win should be the first place you look.

^ Let me give you an example. I once managed a business intelligence team who had inherited a cobbled together mess of a BI infrastructure. Changes were really hard and customer requests ended up taking forever. The team was swamped with requests so there wasn't really time to get out from under and make improvements. I was trying to shield the team from the complaining so I had all requests go through me. I put a senior developer on the team and they very quickly came up with a proposal to refactor out the most frequently changed report into a new to make it easier to change and faster to run. They knew that I was getting a lot of hassle from our internal customers about that report and that I would appreciate it being easier to change. It wasn't the job that took the longest to run or used the most disk space or anything like that. It was the most frequently changed report and thus the biggest pain in MY behind as the public interface for the team. I turned my attention to making space for the changes to happen. When they did, it was quite successful and we ultimately used the code that was written for that one report as the seed for an entirely new BI component that replaced the old and janky system entirely.

---
# Educate and Evangelize

^ Your stakeholder probably isn't at DevOps days. Even if they are, their boss probably isn't. It's important that we don't assume the person we're trying to convince has the same context as we do and will see the value of what we want immediately and enthusiastically embrace it. We're probably going to need to do a little teaching. This is also an opportunity to do some selling.

^ This is where the empathy and understanding your stakeholders' goals is going to help you the most. When you're explaining what continuous delivery or containers are all about from a technical standpoint, your stakeholder will be thinking "what's in it for me". Make sure you address that too.

^ When continuous delivery was a new and novel concept, I got pretty excited about it. I read the book, I want to talks and I came in to work and said "we should do continuous deployment - every commit gets automatically deployed" and a bunch of people freaked out because that seemed really weird and scary to them. A younger version of me might have though "what a bunch of idiots, they should get with the times like I did" but I realized what needed to happen was they just needed to go through the process of learning about it. So teach, spread knowledge, don't assume that anyone knows what the heck you're talking about, especially your boss.


---
# Think Big, Start Small
![] (sky.jpg)

^ In product development we talk a lot about delivering small increments. Minimum viable, minimum testable, minimum lovable. We usually talk about these thing when we're talking about products or product features.

^ When we take on improvement projects we need to have that mindset too. We can't take on a project with the scope of taking a 5 or 10 year old monolithic web app and turning it into microservices in one fell swoop.

^ Nor can we go from releasing every quarter or every month to releasing continuously. The first milestone can't be the promised land you want to get to. You have to take a baby step, re-assess, incorporate whatever lessons you've learned, then take another baby step.

^ It's not that exciting, I know, but whatever it is you want to do, think about the smallest step you can do to work toward that. It will make things better and whenever you do that you build trust and capital you can use to continue the initiative.

---
## Have Clear Objectives, Measure Outcomes

^ Any potential improvement initiative must have a clear, testable hypothesis behind it. You want to release more often. Why? Is it because releasing is fun? No. You want do it to reduce production bugs. Is the number of production bugs you have now somewhere easily accessible so you can watch to see how your improvements are impacting it?

^ If you want to get all your components into containers. What is the tangible benefit of that to your organization? Fewer configuration related bugs? Fewer bugs in general? Faster deploy times? Lower infrastructure costs? It's not enough to point to an article that lists these benefits or to show someone a talk. Does your org actually have these problems? Can you quantify the cost of the problems? 

^ Once you have that hypothesis, and you know what number you're trying to move. Take the smallest step you can that will impact that number.  Containerize a single service. Continuously deploy one small code base.

^ It can be tempting to use other people's metrics or "common sense" to justify these kinds of initiatives. We can read articles and go to talks and hear other people talk about how this or that change made a big impact at their organization, and we can imagine a similar impact at our company. Be careful there. We're all prone to letting our own enthusiasm for technology bias our thinking so we can justify to ourselves doing something we think is cool.  It's important to build the discipline to be as rational as possible. Metrics help us do that. 

---
## Use Language Of Experimentation

^ Be clear with everyone that you're try these improvements out as an experiment. Be clear about what your hypothesis is and what outcomes you think you're going to get. Not everything works out and this sets that expectation accurately.  You can screw up the implementation, or you can get it perfectly right and find out that it didn't have the impact you expected. That's why we start small and that's why we use the language of experimentation. Big bang releases are a bad idea when doing feature work and they're a bad idea when doing technical improvements too. Don't promise revolution, even if you're sure you can deliver.

---
# Ask for Trust

^ You can't please everyone and you can't address every fear. Some people will resist change no matter what. Ask these people for their trust. Assure them that you've heard their fears and you're open to the possibility that they are right and you are wrong. But ask them to trust you to give it a try.


---
# What not to do.

![inline] (doomsayer.jpg)

^ First of all. Don't be this guy. Running around saying we're all gonna die is fun and gratifying, but it's proprobably not true, and nobody takes you seriously. I'm joking, but one thing to remember is this guy actually thinks the end is coming and that we're all doomed. You may someday find yourself in that situation. Kneck deep in some technical problems that seem insurmountable. You may want to declare bankruptcy on technical debt and flush the whole code base down the toilet and start over. You may truly feel like that's the right thing to do. It almost always isn't. 

^ Lots of people have written about why giant ground-up rewrites are a bad idea so I hope I'm not telling you anything that's news. Nevertheless, I've had several developers tell me that a code base is unsalvegeable and needs to be rewritten. I haven't fallen for it yet.


## Beware the Developer Productivity Justification

^ If someone tells me we should re-do our front end code in a new framework or port a service to Elixir and Phoenix because after doing that developers will be more productive I'm going to have a hard time with that justification. 

^ It can be enticing. You hear about a new framework and spend a weekend coding a todo list app or something and when it's done you've got a nice, beautifully factored app you can reason about easily, everything fits in your head. Then you think about the convoluted mess that your work code base is and wish it was as nice and tidy as this. Early in my career I made this mistake and falsely attributed the neat and tidy nature of the new code base to the framework or language itself rather than the seemingly obvious fact that it's just a very small code base. 

---
# Image Credits
* ![inline](complicatedwires.jpg) - (c) Bill Abbott - CC-BY-NC 2.0
* ![inline](waterfall.jpg) -  (c) Simon Koopman - CC-BY-SA 2.0
* ![inline](silos.jpg) - (c) Diego Delso - CC-BY-SA 3.0
* ![inline](brokenbulb.jpg) - (c) George Becker - CC-0

