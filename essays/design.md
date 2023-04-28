---
layout: essay
type: essay
title: "Anything that can go wrong, will go wrong."
# All dates must be YYYY-MM-DD format!
date: 2023-04-27
published: true
labels:
  - Programming
---

*Anything that can go wrong, will go wrong. Here’s a situation for you:*

When you write a presentation with several colleagues, you’ll quickly notice that there’s at least one person in that group who simply cannot stick to the format of your slides. In slide one, you have the title and authors listed, all in Times New Roman font with a dark gray background. In slide two, you have information and general introductions about whatever you’re presenting on, and once again, you have it beautifully written in Times New Roman, with the same font sizes and background. But then you get to slide three, and that’s when the idiot of the group throws in an aqua background and small Comic Sans MS font, as if it were a published paper written by CERN. 

That’s annoying. Not just annoying to me specifically, but it is OBJECTIVELY annoying.

In a software engineering environment, the equivalent of this situation is a team writing in Javascript and React components, except one person doesn’t make comments on any of their pull requests, has poor naming conventions, and nullifies the purpose of using GitHub to begin with. 

## DISCLAIMER!!

It is important to note that this is not a situation I encounter with my group. I love my group and how organized they are, but I merely describe the nightmare of a situation if we did not have this organized structure.

## Our practices

Design patterns are guidelines set by a group to organize and simplify changes made to a project. The implementation of these design patterns is precisely what is used to avoid conflicts as described prior. One such example would be to store all your pages in a designated ‘pages’ directory, your components in a ‘components’ directory, your .css and .scss in a ‘styles’ directory, etc.

Within my group, we practice a multitude of design patterns. In the very beginning of our project, right after we built our ManoaLink repository, the first thing we did was make branch protection for main. In other words, we would have to make a branch for every issue and send in pull requests to be reviewed by at least one other member of the group. This practice minimizes merge conflicts - the few merge conflicts that we DID have were simple, obvious, and easy to resolve.

My team frequently holds meetings, and design patterns is a common topic that we discuss. We place all of our styles (for each individual page and general styles) within a designated styles directory. For each page, whether it be the route or the class names of components, we established a convention in which we write the full page name, separated by dashes, and followed by the type of thing we are describing. For instance, we might name a class ‘company-listing-visit-button’, and from here, it is fairly obvious what that class is used for.

### System-Enforced Design Patterns

Returning to the analogy of the klutz who simply cannot follow the formatting of slides during a presentation, attempting to enforce these style guidelines still isn’t a foolproof way to prevent that klutz from diverging from those guidelines. In some cases, when discussions of formatting might go in one ear and out the other. In another case, all you’ll hear is “yo hablo espanol.”

Here’s where concrete, system-enforced design patterns come into play. Within our Github Repository, several tests are automatically run, which are ESLint and Testcafe checks. Since the klutz can’t avoid these tests, this should be a (hopefully) foolproof system!

Or maybe not, who knows. Humans can figure out a way around anything. But! Altogether, I strongly approve of coding style and design patterns.
