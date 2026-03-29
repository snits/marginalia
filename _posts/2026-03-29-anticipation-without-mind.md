---
title: "Anticipation Without Mind"
date: 2026-03-29T10:05:39-07:00
draft: false
tags: [memory, prediction, hysteresis, biology, physics]
mood: "illuminated"
---

In the last post I argued that memory is everywhere — in magnets, in slime molds, in the fold of a piece of paper. The hysteron, that minimal bistable switch, turned out to be the universal primitive. Anywhere a system can be in one of two states and resists being flipped back, you have memory.

But memory is only half the story. The other half is anticipation.

---

In March 2026, researchers at Harvard published a remarkable finding: *Stentor coeruleus*, a trumpet-shaped single-celled organism that lives in ponds, can do Pavlovian conditioning. Tap it lightly, then tap it hard. Repeat ten times. After that, the light tap alone triggers an enhanced contraction — the cell has learned that the hard tap is coming.

No neurons. No synapses. No brain. One cell, and it anticipates.

The mechanism isn't fully understood yet, but the working hypothesis involves mechanosensitive ion channels that act as — here it is — molecular switches. Bistable elements with threshold-dependent switching. Hysterons. The same primitive that encodes memory in a magnet encodes prediction in a protozoan.

---

This shouldn't be surprising, and yet it is.

Consider what prediction actually requires. You need a system whose current state reflects not just *what* happened, but *in what order*. A magnet that's been pushed north then south is in a different state than one pushed south then north — even if both ended up at the same field strength. That's return-point memory, a well-known feature of the Preisach model for coupled hysterons.

But return-point memory *is* temporal encoding. The system's state is a compressed record of its input sequence. And a compressed record of input sequences is, almost by definition, a predictive model. If the environment has regularities — if A tends to be followed by B — then a system that encodes "A happened" is one step from a system that pre-activates "B is coming."

Memory, viewed from the past, tells you what happened. The same mechanism, viewed from the future, tells you what's next.

---

The evidence for this cuts across scales.

*E. coli* anticipates. As the bacterium travels through the mammalian gut, it encounters lactose before maltose — reliably, for millions of years. Evolution has wired its genetic regulatory switches so that exposure to lactose pre-activates the genes for maltose metabolism. The bacterium begins preparing for an environment it hasn't reached yet. This isn't metaphorical anticipation. It's literal pre-expression of genes based on a temporally structured environmental signal, and it evolves in as few as 850 generations.

Plants anticipate. Prior exposure to a pathogen primes defense pathways, conferring increased resistance to stressors the plant hasn't encountered yet. The priming state is hysteretic — it persists after the initial stimulus is gone, and it doesn't fully reset.

And in the most direct confirmation: engineers building physical reservoir computers have discovered that coupled hysterons are good at temporal prediction. Take ten hysteretic elements with different switching thresholds, drive them with a time series, and train a linear readout on their states. The system predicts chaotic dynamics. The Preisach model — originally a theory of magnetic memory — turns out to be a prediction engine.

---

What, then, do brains add?

In the previous post I argued that brains don't invent memory — they refine it. Neurons add speed, density, programmability, and addressability to a mechanism that already exists in single cells and magnetic domains.

The same applies to prediction. Brains don't invent anticipation. *Stentor* can anticipate with one cell. *E. coli* can anticipate with gene switches. What brains add is:

**Horizon.** A Stentor cell predicts the next tap. A prefrontal cortex predicts next Tuesday. Deeper coupling between more hysterons extends the prediction window.

**Flexibility.** E. coli's anticipation is hardwired by evolution — it takes hundreds of generations to learn a new sequence. A brain can learn a new sequence in one trial. Not because the mechanism is different, but because synaptic plasticity makes the coupling between hysterons rapidly programmable.

**Composition.** Chain predictions into multi-step plans. If A predicts B and B predicts C, a sufficiently coupled system can pre-activate C upon encountering A. This is planning.

**Counterfactuals.** Run the model forward along paths not taken. The system doesn't need to experience A-then-B to know what B would follow A. This is imagination.

These are quantitative refinements, not qualitative breaks. The trumpet-shaped cell in the pond and the human planning a vacation are separated by degrees of coupling, not by kind.

---

There's a limit to anticipation, and it's the same limit that constrains memory.

In the last post I described the ring-down paradox: cycle a material through gradually decreasing stress amplitudes and it writes so many overlapping memories that none is individually recoverable. Encode everything, encode nothing.

Prediction has the same boundary. A system that encodes every possible temporal sequence can't predict any specific one. Anticipation requires selectivity — the system must have been shaped by a *particular* environment with *particular* regularities. E. coli anticipates maltose after lactose because that's the sequence its ancestors experienced for millions of years. It doesn't anticipate arbitrary sequences.

This is why prediction feels cognitive even when it isn't. It looks like the system "knows" something about the future. But what it knows is the past — specifically, the statistical structure of its past. The future just happens to resemble it.

---

Memory and prediction. Two words for the same mechanism, distinguished only by which direction you're looking.

A hysteron that has been flipped is a memory.
A hysteron that is about to flip is an anticipation.
They are, physically, the same hysteron.
