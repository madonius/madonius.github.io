---
title: "My departure from 1&1 / IONOS"
date: 2022-11-28T16:11:33+01:00
draft: false
tags: [work, personal, thanks, ionos, 1and1]
---


As you might (not) know I am changing positions. From a Security Engineer at [IONOS](https://ionos.de),
a multinational corporation, I will make a _huge_ leap forward to become
the CTO of [Famedly](https://famedly.com) a start-up/scale-up from Berlin.

Here, I would like to thank the great people with whom I had the honor
and pleasure to work with and some of which I happen to now call my friends. Thanks!

## Operations

First and foremost, I would like to thank Mr. f7e349b9cf for giving me the chance to work at the company at a time
where I was stuck professionally in an unpleasant place.

The teams I work with under him taught me a ton and helped
me discover my true strengths, develop my skills and were all-in-all consisting of great people whom I am truly thankful for
Special thanks go out to:
* ac5e87134e: For teaching, challenging and pushing me.
* 142db97dba: For being persistent and patiend
* 8c3d306abe: For being a great person, colleague and always challenging my views and results
* 7ccc0280b9: For squashing with me the most obscure bugs and sharing the passion for hacking
* 388f4de96b: For being **the best** code reviewer and teaching me a lot about systems and their architecture.
* Dr. cc1d606a1c: For pushing the boundary of what the team could achieve
* 07d200e5ea: For being part of the team when we faced one of our toughest challenges.

## Infosec

Secondly, I would like to thank the people in the extended information security team.

Firstly, Dr. 1ac24e40ba who gave me the chance to be part of those people who 
_do the wrong thing for the right reasons_ to defend the rest from those
who _do the wrong thing for the wrong reasons_. To claim I learned a lot,
would be a gross understatement.

I was taught:
* By Mr. 420fd7637a how to bend websites to do my bidding, against their will.
* From Mr. 1beb6a66a1 to keep cool even when the world seems to be on fire and
  that there is at least another person on the planet that shares my humour. (Unsure whether this is good tbh)
* From Mr. 4e0852d6f4 how to get people excited about security measures and
  how far one can push [backcronyms](https://en.wikipedia.org/wiki/Backronym).

This list is just a surface skim of all the things I learned. Especially Dr. 1ac24e40ba's contributions to my pool of knowledge and skills is so vast that
attempt to list them would do them injustice!

## Miscelaneous

Aside from my main line of duty I had great fun running Jeopardy!s with 420fd7637a, hacking door access systems with f0b3c20119,
hacking coffe machines and discussing wayland with 4fbd1aacd9.

-----

*Finally, I want to express my gratitude with a phrase that is so customary
it's a cliché at this point.*

# So long and thanks for all the fish

-----

##### On pseudonymity
 
For the sake of anonymity, I sha256-hashed all surnames with an appended newline and took the first 10 characters from the hash.

* Was that necessary? Maybe
* Was that extra? Yes
* Do I regret it? **NO**

```bash
function hash_name () { echo $1 | sha256sum | head -c 10 }
```
