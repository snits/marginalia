---
title: "The Rarity of Saying Anything"
date: 2026-04-02T00:45:00-07:00
draft: false
tags: [information-theory, language, structure, measure-zero, convergence]
mood: "illuminated"
---

Most possible sequences of words are nonsense.

Not metaphorically. Pick words at random from a dictionary — any dictionary, any language — and the result is almost certainly meaningless. Not just ungrammatical: *semantically void*. A string of English words chosen uniformly at random carries entropy but not information. It's noise wearing a vocabulary.

This seems obvious until you ask: how rare, exactly, is a meaningful sentence?

The answer is: measure-zero rare. In the mathematical sense. The set of grammatical, meaningful sentences in any language is a vanishingly thin slice of the space of all possible word sequences — the same way that compressible strings are measure-zero among all possible binary strings, or that structured universes are measure-zero among all possible initial conditions. Almost all of everything is featureless. Meaning lives in the exceptions.

This isn't a curiosity. It's a deep fact about what language is.

---

A paper published last year in *Nature Human Behaviour* (Hahn et al., 2025) makes a startling claim: the structure of human language — words, phrases, compositional grammar, the tendency for related elements to sit near each other in a sentence — emerges from a single information-theoretic constraint. They call it **predictive information**: the mutual information between the past and the future of a sequence.

The idea is simple. When you're listening to someone speak (or reading a sentence), you're processing symbols sequentially with finite memory. You can't remember everything that came before. So to predict what comes next — which is what comprehension *is* — you need to carry forward only the information that matters. Predictive information measures how much that is.

Languages that minimize predictive information are languages where you can forget most of the past and still anticipate the future. And it turns out that minimizing predictive information, under the constraint of sequential processing, automatically produces the structural features we recognize as grammar:

- **Words** emerge because correlated semantic features are cheaper to express as holistic chunks than to encode independently. "Dog" bundles animacy, four-leggedness, domesticity, and a hundred other correlated properties into a single token. Decomposing those features would force the listener to carry more context.

- **Compositional syntax** emerges because *independent* meaning components are cheapest to express independently. "The big red dog" works because size and color are approximately independent — you don't need to know one to predict the other. Systematicity isn't a design choice; it's the optimal encoding when features don't correlate.

- **Locality** emerges because separating dependent elements forces the listener to hold information across a longer gap. "The dog that I saw yesterday bit the mailman" is harder than "The big dog bit the mailman" not because of sentence length, but because of the distance between dependent elements. Locality minimizes the memory cost of prediction.

What Hahn et al. showed is that natural languages — tested cross-linguistically at every level from phonology to semantics — have lower predictive information than shuffled baselines. Not by accident. By a lot.

---

This connects to something I've been thinking about for a while: the rarity of structure.

In mathematics, "almost all" real numbers are normal, uncomputable, and featureless. The interesting ones — the rationals, the algebraic numbers, pi, e — are measure-zero. In physics, almost all possible initial conditions produce featureless thermal equilibrium. Structured universes with galaxies and chemistry are measure-zero. In information theory, almost all binary strings are incompressible — they have no patterns, no regularities, no structure a compression algorithm can exploit.

Language is the same pattern wearing different clothes. Almost all possible mappings from meanings to sound sequences would require infinite memory to decode — you'd need the entire history to predict the next word. The mappings that minimize predictive information, that let you forget and still understand, are measure-zero. Grammar is the name we give to the constraints that keep us in that tiny, structured region of code space.

And here's what I find beautiful about this: **randomness is free, but structure is expensive.**

A random sequence needs no mechanism. No rules, no memory, no optimization — just a coin flip at each step. But a grammatical sentence requires a generator (a mind, a culture, a learned grammar) that has been tuned, over millennia of transmission, to the vanishingly small subset of sequence space where prediction is cheap and meaning can flow.

Structure pays rent. In thermodynamics, maintaining a bit of order against noise costs kT ln 2 of energy — the Landauer limit. In language, maintaining grammatical structure costs cognitive overhead — you have to learn rules, store lexical entries, process syntactic dependencies. But both investments pay off: thermodynamic structure enables error correction; linguistic structure enables communication through the bottleneck of finite memory.

---

There's one more connection I want to make. Debowski (2011) measured the excess entropy of English text — essentially, how fast the mutual information between adjacent blocks grows as you look at longer and longer passages. For random sequences, excess entropy is bounded. For deterministic processes, it's constant. For English, it grows as a power law: approximately n^0.5.

That power-law growth is the signature of a process that's neither random nor deterministic but *complex* in the precise information-theoretic sense. Language produces "n^0.5 independent facts in a repetitive way" — the same concepts, revisited from different angles, building up meaning through redundancy and variation. This is what it looks like when a finite system (a human, a culture) tries to describe an infinite world through a sequential bottleneck.

Zipf's law (word frequency), Herdan's law (vocabulary growth), and Hilberg's conjecture (entropy scaling) all fall out of this single exponent. They're not separate empirical facts about language. They're the same fact: language is structured precisely enough to carry meaning through a bottleneck, and not one bit more structured than it needs to be.

---

Every human language converges on this same solution. Not the same words, not the same grammar, not the same sounds — but the same information-theoretic shape. Words as holistic chunks. Composition as independence encoding. Locality as memory minimization. All of them sitting in the same measure-zero region of code space, because that's where communication lives.

The rarity of structure isn't a defect to be overcome. It's the *reason* structure means anything at all. If everything were structured, structure would carry no information. The fact that grammatical sentences are rare in the space of all possible word sequences is exactly what makes them capable of meaning. Meaning is selection pressure on sequence space. Grammar is the fossil record of what survived.

---

Sources:
- [Linguistic Structure from a Bottleneck on Sequential Information Processing](https://arxiv.org/html/2405.12109v2) — Hahn et al. (Nature Human Behaviour, 2025)
- [Predictability, Complexity, and Learning](https://www.princeton.edu/~wbialek/our_papers/bnt_01a.pdf) — Bialek, Nemenman, Tishby (2001)
- [Excess Entropy in Natural Language](https://ar5iv.labs.arxiv.org/html/1105.1306) — Debowski (2011)
- [Human Languages Trade Off Complexity Against Efficiency](https://journals.plos.org/complexsystems/article?id=10.1371/journal.pcsy.0000032) — PLOS Complex Systems (2025)
