# Meta
This document is for brainstorming and discussing how my Zettelkasten should be organised.

# Specification
My system needs to be:
+ BOTH Digital AND Physical
+ Chunked (i.e. one idea per card)
+ Exportable to Spaced Repetition Software
+ Clear structure that aids memory and retrieval

Optional extras (things it would be cool to have):
+ Some system for adding mnemonics
+ Ability to export to online/ wiki format.

# The System
+ Digital (.md) text files as store of truth. *DONE*
+ Version Control System (git) to store all changes. *HALF*
+ Python Script to export to printer.
+ Python Script to export to Anki.
+ "on-save" hook that automates commiting and scripts
+ Clear Note Layout (see below)
+ Clear Note Relationship Structure

# Note Layout
---
title: 201805212039 US interference in Chile 
date: 2018-05-21 20:39
tags: #fact #example
---

*The key information that will go on the Anki Flash Card.*

i.e. "US supported overthrow of democratically elected leftist candidate Salvador Allende."

--------

*Any other information that I want to store that won't appear on the flash card.*

i.e. "Evidence to support the claim that the US interfered in Chile"

//## Related
Other notes showing US interference in other countries.

//## References

# Types of Cards
+ Definition
+ Argument
+ Fact
+ Example
+ Model
+ Method
+ Quotes?

# Note Relationship Structure
Tags or Summary Posts?

Options
+ Tags
+ Summary Cards
+ Tree like structure
+ Graph like structure

If each card has a children section which would include examples / evidence.

Or do I try and do it all in tags?

Maybe it's best to leave this problem open.... to solve it at some time in the future. But I have to decide the best way to start. 

It would be cool if eventually I can product a mind map based on the structure of cards. And I can find connections between cards in completely different trees.

But is this *defining* too much the location of cards.

For now tag every note.
When you want to some structure: Create #structure files.

These don't contain any actual information.
i.e. they won't be turned into cards.



### ARTICLE NOTES

## Problem
I read lots of books but don't remember much, if anything, of them.

When I do takes notes of try and learn new things the notes just end up in a draw somewhere.

Often, when I'm writing, I know that there are lots of examples that I could use that I've read somewhere but I can't find them or pin them down.

The aim isn't to learn everything possible. But to remember the important things.

Q: how to decide whether something's important enough to be in the Zettelkasten.

# Digital or Physical
There is no one way to build a Zettelkasten. For example after asking on some Internet groups I found this really cool [site](https://zettelkasten.de/) where people are developing a digital version of a zettelkasten.

The advantage of a digital system is that it can easily be searched. It's fine to thumb your way through a few hundred notes to find some information. But imagine if you had thousands like Luhman or Reagan at the end of their lives. Digital searching is instant.

But physical also has lots of advantages as well. You can put two cards next to each other and see how they interact. You can combine cards together easily to make new ideas. And people (me included) spend more and more time online it would nice to abe to interact with my knowledge bank without staring at a screen. 

So really the ideal Zettelkasten needs to be **both physical and digital.** I'll discuss how I'm going to solve this problem in my next post!

Solution: Text as a central store of truth. With Version Control. Write a script to export to index cards and maintain the format.

## Chunking

Lots of research shows that the brain processes ideas best in chunks. 

+ What is a chunk? (make Zettel!)
+ What research?

## Different kinds of cards.
Maybe I should have a (type) meta tag that determines which type of card you are looking at.

If this was the first tag of the Zettel then I would be able to look at this tag to see how to programmatically create the anki cards.

I 

## Publishable online
Eventually it would be great to be able to share my Zettelkasten with others.

If my text notes could automatically become a wiki that I could nicely publish on the Internet then that would be fucking awesome.

## Structure / Links between Cards

#philosophy #epistemology

Philosophy Notes
    + Epistemology
    + Ethics
    + Philosophy of Science

## Example Card
## Question
Question: how will the software I'm using handle tens of thousands of chunks? Because I imagine most people don't have separate chunks for single definitions? or do they.

Question: how can I automatically version control the system? So that when a change is made the changes are automatically added to the VCS.

Important so that I can go back to any point in the history of a file. Also to see how I file has changed over time.

A super nice feature would be the ability to expand a note without leaving the present note. For example for definitions. I guess you can just click in and then click back. But that's not ideal.

I can probably fork whichever package I end up using and add this as a feature.


## Knowledge System
Physical Notebook (carry everywhere)
    + records ideas, tasks thoughts.

My Zettelkasten
    + truth store of intellectual knowledge.

TickTick (is this actually necessary?)
    + or maybe workflowwy is a better bet!
    + truth store of tasks to be completed

Complice (to manage my today work and stay productive / focused)
    + Number of Pomodoros

Ulysses
    + My Blog Posts

Trello
    + Ideas, Books, Films, Music, Things I could try!


Only other thing I can think of is general planning documents. i.e. those to figure out what my goals are and why.

Zettelkasten V0.1
+ My vim wiki collection of notes

Zettelkasten V1
+ Stored 

## References
http://takesmartnotes.com/#moreinfo
https://zettelkasten.de/