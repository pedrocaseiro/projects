# Nobull bot

## Introduction

Nobull is a Slack bot which translates Startup jargon into plain English using advanced machine learning technology and cognitive computing.

## Description

Nubull recognizes startup jargon in messages and rewrites the text so that everyone understands it. For instance:

"We will revolutionize the tourism sector" will become "We like to travel, know how to code, and have ideas," or "Using state of the art machine learning" will become "We hear investors like machine learning, so we have that.", or "Disrupt" will become "Super fun and awesome."

The audience is everyone except founders and investors.

To accomplish Nobull we used NodeJS, Spark, React, BotKit, NeoVim, No tabs and 4 space indentation.

We trained our neural networks using datasets from several community websites like [Hacker News][2] and [SVD][1].

## Team

 * Cláudio Gamboa https://pixels.camp/suskind
 * Eric Bachmann https://pixels.camp/bachmann

## Code repository

You can find our code at https://github.com/suskind/nobull 

The code is released under the [WTFPL license][3].

## URL 

https://nobull.io/

## Other information

The caveat with Nobull is it can't process sarcasm in sentences yet; a common problem found in many of the Slack communities we tested the bot with. We are trying to solve this problem by using noisy Hopfield networks with holographic associative memory but it's still in alpha.

[1]: http://svdictionary.com/
[2]: https://news.ycombinator.com/
[3]: https://en.wikipedia.org/wiki/WTFPL
