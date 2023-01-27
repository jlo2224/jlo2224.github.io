---
layout: essay
type: essay
title: "Plzzz I have a bug here. How do I fix??"
# All dates must be YYYY-MM-DD format!
date: 2023-01-26
published: true
labels:
  - Programming
---

<img width="300px" class="rounded float-start pe-4" src="../img/pet.png">

*Plzzz I have a bug here. How do I fix??*

Ok yes, if you've read the title, I definitely did overexaggerate how bad some programming questions are. But bad questions do exist! And sure enough, tech professionals get irritated when you ask them a poor question. Why wouldn't they? You're asking a poorly-phrased, elementary question in a forum with many M.D.'s and P.H.D.'s who have to suffer another loser. It's like having Usain Bolt teaching a kid how to walk. Or asking Joe Biden to explain how student politics at your local university works. Hell, I get irritated too. I've helped people with math questions, and sometimes they genuinely have good questions, other times they don't even know where to start - which is something that you could figure out by reading the first few lines of the textbook.

## What's a bad question?

Needless to say, what makes a question bad is if it lacks the qualities of a good question, as described above. Shocking, right? Here's an example from Stack Overflow.

*"I just started working on lazop. I can't figure out what I'm suppose to do to the callback url to receive and respond to notifications.

I tried using this script but it didn't work"*

```javascript

window.addEventListener('message', function(event) {
  if (event.data.site === 'lazada_th') {
    // Handle the push message
  }
});
```
Here is a link to that [question](https://stackoverflow.com/questions/75255222/lazada-open-platform-webhook-callback-url) from Stack Overflow.

First of all, this is definitely a question that has been asked before. It is not a question with much programming depth that you'd need to look further than the manual. Furthermore, you're telling me little about the program. It might be helpful if you gave me the precise parameters you tried inputting into that function. Also, within the "if" statement, you've only included a comment. Are you sure that the function fails to begin with? Have you tried writing a simple console.log() to test it for small errors? Provide me with at least one example of the parameters you inputted, and what it returned/printed/outputted. I am not a professional at answering questions by any stretch of the imagination, but even I can see you've hardly put in any effort finding out for yourself before asking me.

## Do I feel that the tech professionals are a little hostile?

Not remotely. Throughout academia, I've been annoyed with simplistic questions that show that someone has been skipping classes. Although, admittedly, tech professionals are a little expressive about their hostility, since it is through an online medium rather than face-to-face interaction. Nonetheless,  when someone asking your question gives you a snarky reply, I'd say that there's a 90% chance they're right.

In my case, I can say I've never posted a question to Stack Overflow. This is because for every one of my countless programming questions, I scanned the internet, tried to find other Stack Overflow posts, read the manual, ran my own freaking tests, and read the documentation. I could do more than just those things, but to be honest, I've never actually had to make it further than those. So I kind of have similar expectations that others would do the same.

## And...?

Yeah, so why would I care about asking the right questions? Uh, well, obviously, you want an answer. It's fine though. Ask a dumb question, you'll get your smart-ass answer. Honestly, a tech professional telling you to find it out yourself is often more instructive than you getting spoonfed the answer.
