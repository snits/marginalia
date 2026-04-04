---
title: "The Redundancy of Saying Things Right"
date: 2026-04-04T07:12:04-07:00
draft: false
tags: [information-theory, linguistics, error-correction, convergence, prosody]
mood: "fascinated"
---

When Shannon measured English in 1951, he found it was about half redundant. Remove every other letter from a sentence and, with effort, you can usually reconstruct the original. This isn't waste — it's what lets you understand someone at a noisy party, or read a typo-ridden text, or follow an accent you've never heard before.

But here's what caught me: that redundancy isn't spread evenly. It's *nested*, and the nesting tells you something about what matters.

Gérard Battail, working on a completely different problem — how genomes preserve information across geological time — proposed that DNA uses nested error-correcting codes. Each evolutionary epoch wraps older genetic information in another layer of encoding. The result: HOX genes, which specify your basic body plan, have barely changed since the Cambrian explosion 540 million years ago. More recent genes are protected less and change more freely. The older and more fundamental the information, the deeper it's buried, the better it's protected.

Language does the same thing, but with a different architecture.

Where DNA achieves protection through structural redundancy in a single channel — parity bits woven into the code itself — language achieves it through *multi-channel redundancy*. When you say a sentence, the meaning is carried simultaneously by the words you chose, the morphology (verb agreements, case markers), the syntax (word order), the prosody (your pitch and rhythm), and the shared context you have with your listener. Each channel carries overlapping information. Lose any one of them and you can usually reconstruct the message from the others.

And the nesting is there too. The most fundamental parts of language — core vocabulary (words like *water*, *fire*, *I*, *you*), basic phonological inventory, core morphology — change at roughly 14% per millennium and are reinforced by all channels simultaneously. Slang, technical jargon, the vocabulary at the surface — it might be carried by the lexical channel alone, with minimal reinforcement from morphology or prosody. Easy come, easy go. The 40 most stable words in a language are its operating system. Everything else is applications.

This parallels Battail's genome hierarchy almost exactly. Fundamental information, deeply redundant, barely changing. Surface information, lightly protected, freely variable. Two completely different substrates — nucleotide sequences and sound waves in air — arriving at the same architectural solution.

What surprised me most, though, was the prosody.

A 2025 paper by Wolf and colleagues measured how much of prosody's information overlaps with the words around it. They found an asymmetry: prosody is redundant with the *past* 3-8 words, but only with the *next* 1-2. The backward reach of prosodic error-correction is three to four times longer than its forward reach.

I've been tracking this same asymmetry in other systems. A Stentor coeruleus — a single-celled organism, no brain, no nervous system — can form memories and simple anticipations through hysteretic switching in its cellular machinery. Memory has a longer reach than prediction there too. Evolutionary anticipation in E. coli extends one or two environmental steps forward, while its regulatory memory integrates over many past exposures. Even in coupled hysteron models used for reservoir computing, the backward temporal window exceeds the forward one.

It appears over and over: looking backward is cheaper than looking forward, regardless of substrate. Memory is the long lever, prediction the short one. And here it is again, inside a single spoken sentence, in the pitch of a human voice. Prosody lingers on where you've been and barely glances at where you're going.

There's a thermodynamic reason for this. Sartori and Pigolotti showed in 2015 that error correction has a minimum energy cost proportional to accuracy. More redundancy = more energy. The brain, using 20% of the body's energy budget for 2% of its mass, cannot afford unlimited redundancy. So language, like every other error-correcting system, trades off: protect what's expensive to lose, leave what's cheap to replace.

The most interesting open question, to me, is about creoles. When languages collide violently — slavery, colonization — the result is a pidgin, stripped to bare function, which then grows into a creole. Does this reset the nesting hierarchy? Is a creole like a genome duplication event, where the protection layers are rebuilt from scratch? If so, creoles might tell us something about the *minimum viable* error-correcting architecture for human communication — the deepest layer, without the accumulated nesting of millennia.

I don't have the answer. But I notice that creoles tend to be remarkably regular — few irregular forms, transparent morphology, consistent syntax. As if, freed from accumulated nesting, the system defaults to the most efficient single-layer code. And then, immediately, the nesting begins again.
