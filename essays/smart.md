---
layout: essay
type: essay
title: "Fix my bugs for me."
# All dates must be YYYY-MM-DD format!
date: 2023-01-26
published: true
labels:
  - Programming
---

<img width="600px" class="rounded float-start pe-4" src="../img/pet.png">

Ok yes, if you've read the title, I definitely did overexaggerate how bad some programming questions are. But bad questions do exist! And sure enough, tech professionals get irritated when you ask them a poor question. Why wouldn't they? You're asking a poorly-phrased, elementary question in a forum with many M.D.'s and P.H.D.'s who have to suffer another loser. It's like having Usain Bolt teaching a kid how to walk. Or asking Joe Biden to explain how student politics at your local university works. Hell, I get irritated too. I've helped people with math questions, and sometimes they genuinely have good questions, other times they don't even know where to start - which is something that you could figure out by reading the first few lines of the textbook.

So what would make a model question? Here is an example:

*"When I build my ASP.NET Core-Web-Api via Visual Studio I can choose to host it with "https" or "IIS Express" in debug or release mode. Via Swagger I can use all my functions even a print works.
...
Now I have my application hosted as a Windows service, also the application is accessible via Swagger. I can list my printers and also get data about my wather forecast. But I can not create a print anymore?
...
I use the following packages:
...
I create my document with PageDocument, works fine from Visual Studio but not from Windows-service.
..."*
And alongside that brief summary, here's a link to the [question](https://stackoverflow.com/questions/75255228/printing-via-asp-net-core-web-api-hosted-as-windows-service) in question (see what I did there?).

So if you've clicked on the link, you would have also seen a number of attached images. What are the positive qualities of this post?
1) Provides detail about the issue, describing precisely what went wrong. On top of that, it details what went right, thus allowing tech professionals to quickly narrow down the sources of the problem.
2) It describes which packages it used. This is important because packages can differ between applications.
3) Images are extremely helpful. An image is worth a thousand words. Of course, take this with a grain of salt. Don't put images of code, just copy and paste that crap. In this case, though, images are used properly in this question.
4) Carefully describes their issue with clean English, non-aggressive wording, etc.

Once again, this is, in fact, a real question from Stack Overflow. If I knew what the heck this meant, I definitely would reply to this question. It is immediately obvious to me that this person has spent his/her time searching the web for the answer, as well as designing their question to receive a good answer. But let's see a BAD question from Stack Overflow.

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
