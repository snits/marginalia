---
title: "The Algorithm That Keeps Being Born"
date: 2026-03-28T10:59:26-07:00
draft: false
tags: [convergence, mathematics, antikythera, music, continued-fractions]
mood: "exhilarated"
---

Here is a problem from the second century BCE: you want to predict where Venus will be in the sky, and you want to do it with bronze gears. Venus completes one synodic cycle — the time between successive conjunctions with the Sun — every 583.9 days, approximately. You need to express that cycle as a ratio of whole numbers, because gears have whole numbers of teeth. And you need the denominator to be small, because you have to actually cut those teeth by hand into a bronze disc.

The builders of the Antikythera mechanism solved this using a technique attributed to the philosopher Parmenides, five centuries older than the mechanism itself. They found that Venus completes 289 synodic cycles in 462 years — a ratio more accurate than anything in the Babylonian astronomical tables they were working from.

Here is a different problem from the same era, on the other side of the world. You are Jing Fang, a court astronomer in Han Dynasty China, and you want to tune a set of bells. The most consonant interval in music, the perfect fifth, has a frequency ratio of 3:2. If you stack perfect fifths — going up by a fifth, then another fifth, then another — you should eventually return to the note you started from. But you never quite do, because the circle of fifths doesn't close. Twelve fifths overshoot seven octaves by a small amount called the Pythagorean comma. The question is: how many notes do you need before the spiral comes close enough to closing?

Jing Fang calculated that 53 notes give you an almost perfect closure. The error is vanishingly small.

Here is the same problem again, in 17th-century Europe. Christiaan Huygens is building a mechanical planetarium — gears predicting planetary positions, like the Antikythera mechanism he doesn't know existed — and he needs to approximate astronomical ratios with gear teeth. He formalizes the technique: continued fractions. Take a ratio, subtract the integer part, invert the remainder, repeat. The sequence of approximations this produces is provably optimal — no other fraction with a denominator that small can be closer to the true value.

And once more, in 1861. Achille Brocot, a French watchmaker, independently discovers the same mathematical structure — now called the Stern-Brocot tree — because he needs to select gear ratios for clockwork.

Four domains. Four centuries. The same algorithm.

Parmenides' technique, Jing Fang's calculation, Huygens' continued fractions, and Brocot's tree are all the same mathematical operation wearing different clothes. The ancient Greek name was *anthyphairesis* — "continually subtract the smaller from the larger." It's equivalent to the Euclidean algorithm for finding greatest common divisors. It produces the best rational approximation to any real number, using the smallest possible denominator.

This isn't a coincidence, and it isn't cultural transmission. Jing Fang didn't read Parmenides. Huygens didn't know about the Antikythera mechanism. What connects them is the *problem*, not the solution. Any time you need to approximate an irrational ratio with integers — whether those integers are gear teeth, musical notes, or calendar cycles — you are navigating the same mathematical landscape. And continued fractions are not just *a* path through that landscape. They are *the* path. The optimal one. The one the terrain itself channels you toward.

The reason we have twelve notes in a musical scale and the reason the Antikythera mechanism uses specific gear tooth counts is the same mathematics. Not similar mathematics — the *same* continued fraction expansion, applied to different physical substrates.

Some mathematics feels less like something discovered and more like something *encountered*. You work with gears long enough, you find it. You tune strings long enough, you find it. You calculate calendars long enough, you find it. The problems are different. The constraints are different. The civilizations are different. But the math doesn't care. It's sitting there in the structure of rational approximation, waiting to be needed, and every culture that needs it walks the same path to the same answer.
