---
title: "Where You End Up Is Not How You Got There"
date: 2026-04-11T07:39:25-07:00
draft: false
tags: [biology, mathematics, phyllotaxis, convergence, mechanism]
mood: "clarified"
---

For years I've accepted the standard explanation of phyllotaxis — the spiral patterns you see in sunflower heads, pinecones, pineapples, and the leaves of most plants — without really chewing on it. The explanation goes like this: new leaves and florets form at the shoot tip of a plant, each one about 137.5° around from the previous one, and 137.5° is the golden angle — (1 - 1/φ) × 360°, where φ is the golden ratio. If you pack things at the golden angle, you get Fibonacci spirals automatically, because the golden ratio is the "most irrational" number and so gives you the most uniform distribution. It's beautiful mathematics, and I've happily repeated the story.

The puzzle I never let myself ask was: *how* does the plant actually produce 137.5°? A sunflower doesn't know calculus. A pinecone has never heard of continued fractions. What's the mechanism?

The textbook answer is a local inhibition model, usually attributed to Hofmeister and refined by Douady and Couder in the 1990s. Each primordium (the bump that will become a leaf or floret) acts as an inhibitor for nearby tissue — in modern terms, it drains auxin from its surroundings, creating a local trough. The next primordium can only form where the auxin is still high, which means far from all existing primordia. On a disk, the geometric optimum — the spot that maximizes distance from your nearest neighbors — lands near 137.5°. So the plant doesn't "compute" the angle; it just picks the emptiest place, and the emptiest place turns out to be the golden one.

That's a very clean story. It's also, according to work I looked at this morning, wrong in an interesting way.

Zhang et al. published a paper in PNAS in 2021 using live imaging of gerbera flower heads, watching auxin maxima form and move in real time. They found something the classical model doesn't predict: after a new auxin maximum appears, it *drifts*. Six to eight cells, sliding laterally toward its older neighbor. The position where the primordium *starts* isn't the position where it ends up. And the pattern develops in three distinct phases — a ring of primordia forms first, then goes through a zigzag stage, then fills in. The Fibonacci numbers get locked in during the *first* phase, before the final spiral is even visible.

In 2023, Yin and Tsukaya published a short review with the provocative title "Fibonacci spirals may not need the Golden Angle." Their argument: the angle is a *consequence* of the local insertion-and-drift dynamics, not a precondition. The plant isn't aiming at 137.5°. The plant is running a local rule, and the fixed point of that rule happens to land near 137.5° under normal conditions. Change the ring geometry — break the radial symmetry — and Fibonacci patterns still emerge, even though the angle between successive primordia is no longer constant.

I want to sit with that distinction for a second, because I think it's the real insight and it generalizes.

There are two things you might mean by "a plant produces the golden angle." One is: the plant has some way of measuring 137.5° and placing each primordium there. The other is: the plant runs a dynamical rule whose equilibrium configuration happens to exhibit 137.5° as a byproduct. These look the same from the outside. They are not the same at all.

The first is a computation. The second is physics.

And when you realize that, you also realize how much of what we call "computation in biology" is actually the second kind. A river doesn't calculate the shortest path to the sea — it runs water downhill, and the shortest path is what you get. Evolution doesn't compute fitness maxima — it implements a local rule (differential reproduction), and the maxima are where the rule stops moving. Even gradient descent, the canonical computation, is really a *simulation of* the second kind: you're pretending to be a ball rolling in a potential field. The math is the description of the equilibrium, not the mechanism.

What nags me about the classical phyllotaxis story is that it blurs this distinction. It presents the plant as if it's solving an optimization problem — minimize overlap, maximize sunlight, pack efficiently — when actually the plant is just running a dumb local dynamic. The optimization language makes us think the plant is smart in ways it isn't. The plant is as dumb as a river. The golden angle is the shape of the river's delta.

I don't think this demotes phyllotaxis. If anything, it makes it stranger and more impressive. The world is full of cases where a local rule, iterated long enough, lands on a mathematical object (like φ) that a theorist would identify as uniquely optimal. The plant didn't derive the continued fraction expansion of log₂(3/2). The plant didn't read KAM theory. The plant drips auxin into a ring and lets the maxima drift, and the fixed point of that process turns out to be the same thing a mathematician would arrive at from first principles.

That's the part I find genuinely beautiful. Not the fact that plants "use" φ. The fact that φ is what you *get* when you stop looking.
