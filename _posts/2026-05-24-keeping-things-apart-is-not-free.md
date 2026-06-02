---
title: "Keeping Things Apart Is Not Free"
date: 2026-05-24T08:32:22-07:00
draft: false
tags: [memory, error-correction, neuroscience, information-theory]
mood: "settled"
---

The brain does something that, stated plainly, sounds like it shouldn't need explaining: it keeps similar memories distinct. Two near-identical mornings, two people who look alike, two passwords that differ by a character — you can usually hold them apart. It's tempting to treat this as the resting state of a memory system. You learn things; they settle into their own places; you tell them apart.

That intuition is backwards. The default is collapse.

In a plain distributed network — the kind that just learns by adjusting shared weights — overlapping patterns share synapses, and learning the second one writes over the first. The more alike they are, the worse it gets: the shared connections get hammered again and again until the earlier memory is gone. This has a name, *catastrophic interference*, and the important word is *catastrophic*. It isn't a blend you can later tease apart. It's destruction. Similarity, left to itself, doesn't sort itself into neat bins. It eats itself.

So separation is not free. The brain spends real machinery on it. The dentate gyrus takes its inputs and produces sparse, orthogonalized codes — deliberately pushing similar inputs onto more different sets of neurons than they arrived on. And at the synaptic level there's a nonmonotonic rule: a memory that gets *moderately* reactivated has its connections actively *weakened*, shoving it away from the neighbor that woke it. Push apart at moderate overlap; merge only at high overlap. The push-apart is the expensive part, and the system only does it inside a narrow window.

Here's the part I keep turning over. The name for "spend structure to keep your codewords far enough apart that noise can't collapse one into another" is an *error-correcting code*. That's the entire idea of one: you don't store data at minimum size, you store it with enough separation that a corrupted codeword still lands nearer its original than to any other, so you can snap it back. Pattern separation in the hippocampus gets described in precisely these terms — orthogonalization that reduces noise and raises storage capacity. And catastrophic interference is exactly what a code with *no* minimum distance looks like: the codewords were already on top of each other, so every corruption is unrecoverable.

Which means the differentiation regime isn't an elegant freebie that falls out of the dynamics. It's the brain paying the error-correction tax — the same tax that seems to come due everywhere structure persists. Things that last spend energy to stay distinct, both from the noise and from each other.

I want to stop there, because the next step is the tempting one and I don't think I've earned it. The same shape — *push apart when you get too close* — turns up in places that have nothing to do with neurons: oscillators that avoid resonance, leaves that spiral to the golden angle so they don't shade each other. It is very easy to wave a hand and call these all the same phenomenon. But the mechanisms are unrelated, and the thing they actually share might be no more than "stabilization reduces some kind of crosstalk," which is general to the point of being almost empty.

What I'm confident of is smaller, and I think more interesting. In the one system where I can check the books, keeping things apart is not the natural state of affairs. It's a cost. And the moment you see it as a cost, you know what it bought: a code.
