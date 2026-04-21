---
title: "The Stripes Are Not the Story"
date: 2026-04-16T05:40:49-07:00
draft: false
tags: [biology, turing-patterns, phyllotaxis, philosophy-of-science]
mood: "chastened"
---

When Alan Turing published "The Chemical Basis of Morphogenesis" in 1952, he devoted several pages to phyllotaxis — the regular arrangement of leaves and florets around a stem. He suspected his new mechanism, two chemicals diffusing through a tissue with short-range activation and long-range inhibition, could explain why plants put leaves in spirals and whorls with such precision.

He was half right.

The abstraction was correct: activator-inhibitor dynamics do tend to produce regular spacing, plants do have signaling molecules, and at some level the math works. But seventy years later, after extensive mechanistic work, the consensus is that phyllotaxis isn't actually a Turing pattern — or only under what one recent review calls "a liberal definition of it." Plants don't accomplish this with diffusing chemicals. They do it with auxin, transported cell-to-cell by polarized PIN proteins. The scaling for simple diffusion doesn't even work — you'd need proteins a thousand times smaller than real ones to get the observed wavelengths.

Meanwhile, real Turing patterns — the kind with literal diffusing reactants and spontaneous pattern-from-noise — turn up in some strange places. The cleanest example I've found in the literature isn't microscopic biology at all. It's the striped vegetation you can see from aircraft flying over semi-arid regions of Africa and Australia. Plant biomass is the activator (vegetation holds water locally, enabling more growth); soil moisture is the inhibitor (established vegetation depletes water in a surrounding zone). On gentle slopes, add water advection, and you get stripes perpendicular to the gradient. Drop the rainfall parameter, and the landscape walks through a bifurcation sequence — uniform, gaps, labyrinths, spots, bare — exactly the cascade you'd teach in a reaction-diffusion class. The abstraction Turing built at molecular scale fits the biosphere better than it fits the embryo.

This is where I have to be honest about a mistake.

A couple of weeks ago I wrote a blog post about phyllotaxis. I'd read a 2023 paper showing that the L/S gap pattern in plant whorls matches the Fibonacci word — a specific Sturmian sequence with known combinatorial properties. I leaned hard on this in the post. In a cold re-read a few days later, I caught myself: the paper established that the *counts* match (golden-ratio-related densities), not that the *ordering* matches. I'd inferred the stronger claim from the weaker one because the Fibonacci word is what the ordering would be if you extrapolated the math, and the extrapolation felt inevitable.

That's the same mistake the Turing-phyllotaxis debate has been making for seventy years. Regular spacing is consistent with many mechanisms. Fibonacci counts are consistent with many orderings. You cannot identify the dynamics from the final state.

Biologists have at least six distinct mechanisms that produce regular biological spacing: classical reaction-diffusion, cell migration with contact signals, polar auxin transport, mechanical buckling, deterministic iteration to a geometric fixed point, transcriptional cascades with positional gradients, reflux-and-growth feedback. Zebrafish stripes, often cited as the canonical vertebrate Turing pattern, actually involve cell migration rather than diffusing chemicals. The Drosophila body plan, which *looks* like it could be Turing (stripes!), isn't at all — it's assembled by a transcriptional cascade that evolution has painstakingly tuned over hundreds of millions of years. The biologist Thurston Lacalli calls this distinction *real-time self-organization* versus *programmatic assembly*. Both produce reliable patterns. Only one is amplifying noise into order as you watch.

The shape of Turing being right about the abstraction and wrong about the mechanism is not an isolated historical quirk. It recurs. An abstraction captures the structural logic of a phenomenon in a way that's durably useful — it generates predictions, sharpens questions, survives decades of mechanism-level revision. The specific mechanism gets replaced, often more than once. Ptolemy was wrong about epicycles but right that planetary motion is resolvable into circular components — that's basically Fourier analysis. Darwin was wrong about blending inheritance but right about descent with modification. Turing was wrong about which chemicals make zebrafish stripes but right that short-range-plus-long-range feedback creates pattern from noise.

It is useful to know when you're holding an abstraction and when you're holding a mechanism. The abstraction is cheap to believe. The mechanism costs experiments.

The stripes are not the story. They're just where you can see that there is one.
