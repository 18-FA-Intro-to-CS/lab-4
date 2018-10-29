# Introduction to Computer Science - Fall 2018

## Lab 4 - It's a mad, mad, mad, mad world.

**Purpose:** The purpose of this lab is to gain some experience with string formatting in _Python_.

**Discussion:** you may remember the popular children's activity involving fill-in-the-blank stories called MadLibs. A potentially humorous story is written down with blanks inserted in place of some key words. The storyteller asks someone else for words based on their type and then fills in the blanks. The lack of context in selecting those words can result in an entertaining story when the words are plugged into the story.

Imagine that this is the story:

> It was an __adjective__ kind of day when __woman's name__ walked out into the street. The sky was a deep __color__ and __same name__ was walking her new pet __animal__.

Imagine the following list of replies that a participant has given:

* Adjective: creepy
* Woman's name: Barbara
* Color: fuscia
* Animal: koala

If the blanks are filled in, the story reads:

> It was a __creepy__ kind of day when __Barabara__ walked out into the street. The sky was a deep __fuscia__ and __Barbara__ was walking her new pet __koala__.

**Practice:** Study the code examples from Chapter 5 of the textbook and on the [website](https://itech190.erickuha.com/python/index.html).

**Instructions:** Create a Python script called _story.py_ that serves as an interactive fill-in-the-blank story program. You should use Python code that uses the `input()` function to ask the user for a series of words. Once the program has the last word, it should print out a story using the user's chosen words.

The content of the story can be anything you like, so be as creative as you like. Though avoid being vulgar. Your story should satisfy the following requirements.

* The title of the story and your full name must appear in the program's output.
* You must get the user's input through a series of `input()` prompts
* Your code must use a separate variable for every word.
* There must be between 5 and 8 missing words.
* You should use the `.format()` function to build the string that will be the outputted story.

Your code does not have to look super beautiful. Just so long as the output makes appropriate use of white space and other formatting tricks to make the output look somewhat reasonable.
