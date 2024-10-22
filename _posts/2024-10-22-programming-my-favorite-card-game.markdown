---
layout: post
title:  "Programming My Favorite Card Game"
date:   2024-10-22 13:43:03 -0400
categories: update, resume, programming, gaming
---
I have been itching to stretch my Python skills, but recently realized I never actually sit down to do anything. I spend a lot of time in tutorial hell with nothing really to show for it.

I decided to work on a Python project, but didn't know where to start because I love to overthink things when doing them for myself. The idea came to me when I was having Canadian Thanksgiving with some friends, and replicating what I use to do when I was having American Thanksgiving - cook all day, surround myself with people I love, and after the meal play cards. In particular the card game we play is called Euchre.

Euchre is a tick-taking game played with a French deck (half deck of cards) and usually with 2 teams of 2 players. After sitting down at my computer the next day, I though it would be a fun exercise to warm up with before doing some real work on a project that is more in line with industry standard work. This was just supposed to be a small project that I could finish in a couple days. I've been playing the game for over 20 years and know it very well. Such a small game shouldn't be that hard to program, right? Especially since it has half the cards missing!

Boy, was I underestimating the amount of work.

My goal for this project was to do things as clean and complete as possible with using as much knowledge as I can in my current arsenal, and learning how to do things (or do things better) along the way.

I got to work and started the project on my computer. Initialized it on GitHub, did my first initial commit and I was ready to go. But I didn't know where to start. I finally started to break down all the elements and what I needed to do.

* Have players
* Play cards
* Score points
* Incorporate Trump rank mechanic somehow

This is where I started. I'll try not to bore you with the nuance details but I though I'd share how I approached this problem. I first built the player class to do all the things it needed to do - have a name, play cards, recieve cards. Then built what a card would look like with suits, values, and ranking. I got a loop going and now I had cards and players that had cards. I didn't worry about the trump thing yet, as I wanted to get a full pass on the skeleton of how the program worked.

By the end of every day for the next few days after working, I would realize some small important mechanic of the game and the list kept growing to make the game really replicate the real thing.

* Ranking of cards
* Scoring points based on different outcomes from the cards played.
* Trump  being the highest rank of cards
* Left Bower (Jack of same color as trump) being counted in trumps and ranking.
* Playing cards filtered only legal to play depending on card played first in the round.
* Players should be able to order trump 
* Players should alternate when seated in the table
* Players should alternate when dealt cards
* Players should be able to go alone without a team mate for more points
* Player considered dealing for the round should be able to pick up the card that was revealed if trump was ordered

Two days turned into a week. Sometimes I was working 12-15 hours on this. I was able to complete most of the things that I set out to do, and I think the project is in a good spot for now. My original plan was to add a UI and other things to it for fun, but as I mentioned the project took longer than I expected for this. 

One of my favorite parts about this project was even though on days where I hyperfocused for long periods of time, I learned something valuable. I was tired and nothing was working on the problem I was trying to solve. Perhaps sleep would help - so I went to bed even though I was determined to keep grinding away on this project. After looking at the code the very next morning, I immediately saw a much simpler, and much cleaner solution. Turns out, sometimes temporarily stepping away is the best solution.

I don't really consider this project finished. Currently, the player plays all 4 hands for the entire game and can be mentally exhausing (plus you get to see what cards the opponent team has). I'd like to add a few things to make it better eventually:

* Player only has to play one hand of cards.
* Bots with logic will play the other cards.
* Build a UI so its less reading for the user

### Final Thoughts
Overall, I'm very happy with how the project came out and funny enough, I have a lot more appreciation for the design of this card game. There are still a few bugs but its in a very playable state at the moment and the amount of things I've learned along the way makes me very excited to build the next project. 

This was my first big project of building something for myself since working in VFX. I think I'm ready to work on something that actually will be helpful in a studio pipeline.

* Better estimating how long it takes to integrate something (with minimal bugs)
* How to add type hinting (something I was always curious about)
* Find useful modules in the Standard Python Library
* How powerful classes can be in a project
* Practicing a work flow of using git / GitHub
* Simple is better than complex (*this* sounds familiar)
* There is always more things to do
