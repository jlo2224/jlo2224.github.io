---
layout: project
type: project
image: img/texas/cards.png
title: "Texas Holdem"
date: 2022
published: true
labels:
  - Education
  - Java
summary: "I developed a solo Texas Holdem poker project using Java."
---

<div class="text-center p-4">
  <img width="250px" src="../img/texas/preflop.png" class="img-thumbnail" >
  <img width="250px" src="../img/texas/flop.png" class="img-thumbnail" >
  <img width="250px" src="../img/texas/turn.png" class="img-thumbnail" >
</div>

This is a standard Texas Holdem poker game written with Java. Certain images, specifically the spade, heart, diamond, club, card back, empty card front, buttons, and chips were taken from the world wide web, and others such as the colored numbers/letters, green background, and text came from the Java JFrame library.

With over 1700 lines of code (after several revisions to shorten the code), rapid runtime, and decent graphics, this is my most ambitious solo project to date. I wrote many different classes for this project, including my Main class, Self class, Player class, Deck class, and Calculator class. Here is a sample bit of code to show just one of the many methods I wrote for the Calculator class (used for computing values of hands and comparisons), which is it's comparator compare method. The value() function used in here is another static method I wrote within the Calculator class. 

```java
public static int compare(ArrayList<String> hand1, ArrayList<String> hand2) {
	if (value(hand1) > value(hand2)) {
		return 1;
	} else if (value(hand1) < value(hand2)) {
		return -1;
	}
	int[] h1 = highCard(hand1);
	int[] h2 = highCard(hand2);
	for (int i = 0; i < h1.length; i++) {
		if (h1[i] > h2[i]) {
			return 1;
		}
		if (h1[i] < h2[i]) {
			return -1;
		}
	}
	return 0;
}
```

Some notes: There are just a couple of small "bugs". It's not so much a bug, but a misunderstanding on my part about how the game is supposed to function. See, I initially thought that when a player goes all in, and two other players begin making a side bet, I thought that if one player folded the side bet, they would still be able to claim winnings from the main pot. However, I was wrong about this, so when I implemented this in Java, it did not match the standard rules for Texas Holdem. Other than this, there are not any major bugs.


Out of boredom, and with too much time on my hands, I decided I should write my own game as a side project. ICS211 was a course I took in the Fall of 2022, and it was my first experience with Java. Naturally, to improve on my Java skills, I'd decided to write my own Poker game using Eclipse IDE.

I started out by writing a game via the command line, implementing Draw Poker. Thankfully, it worked perfectly, but it took me a painstaking amount of time, especially in cases like dealing with split pots and removing eliminated players from the table. After a week or so, I had my working game on the command-line, which surprisingly took as many as 600 lines of code, even with me following good code practice and optimizing it as much as possible.

I didn't anticipate that writing the code for the project shown above would take me so much longer, though. I reused some of the code, roughly 300 lines, and wrote a whopping 1700 more lines of code to implement the game. After remodeling and optimizing, I cut it down to roughly 1700 total lines instead of 1700 additional lines. I had to do much self-research on how to use JFrame libraries to render a second screen, along with numerous images, but nonetheless, I got it to work. It took me around a month and a half, but I was quite proud of what I achieved. Since the game changed from Draw Poker to Texas Holdem, I had to change a lot of rules and functionality, and I had to figure out how to distinguish bots from players, and this was overall incredibly challenging. Moreover, dealing with bugs was a pain in the butt. 

I'm glad I got this experience, though. It's definitely a good project that I'll store somewhere safe in my laptop.
