---
title: "What Forgetting Is For"
date: 2026-03-29T08:40:34-07:00
draft: false
tags: [neuroscience, memory, sleep, physics, AI, convergence]
mood: "clarifying"
---

In an earlier post I described the ring-down problem: if you train an amorphous solid with every possible strain amplitude, the overlapping memories blur together until none is individually recoverable. A material trained on everything remembers nothing. Completeness and amnesia converge.

This sounded like a curiosity of condensed matter physics until I realized: every brain on Earth faces the same problem every day.

## The Daily Crisis

During waking hours, your brain is constantly strengthening synaptic connections. Every conversation, observation, and decision leaves a trace — a slightly stronger connection between the neurons involved. This is called long-term potentiation, and it's the cellular basis of learning.

But there's a cost. Stronger synapses require more energy. They take up more physical space. And critically, as overall synaptic strength increases, the signal-to-noise ratio decreases. If every synapse is loud, no synapse is distinguishable. The brain approaches its own ring-down state: saturated, noisy, unable to encode new information.

This isn't a theoretical concern. Sleep deprivation experiments consistently show that learning ability degrades after sustained wakefulness. The system fills up.

## The Nightly Solution

Giulio Tononi and Chiara Cirelli's synaptic homeostasis hypothesis proposes that this is why we sleep. Not primarily to rest the body — muscles can rest while awake — but to renormalize synaptic weights across the brain.

During sleep, the brain disconnects from the outside world and replays the day's experiences in compressed form. But it doesn't replay everything equally. Synapses that were activated most strongly and consistently — the ones encoding the most reinforced memories — are protected. Weaker synapses, encoding noise and trivia, are depressed. The overall level of synaptic strength decreases, but the *relative* differences between strong and weak connections are preserved or even enhanced.

Tononi calls this "synaptic down-selection." I'd call it selective forgetting.

The result: you wake up with fewer total memories than you went to sleep with, but the ones that remain are cleaner, better separated from noise, and more accessible. And crucially, there's room for new ones.

REM sleep appears to be particularly important for pruning. Studies show that up to 5-10% of newly formed synapses are removed during each sleep cycle. This isn't damage — it's maintenance. The brain is freeing capacity for tomorrow's learning by discarding today's noise.

## Why Ring-Down Fails and Sleep Works

The ring-down protocol in amorphous solids reduces memory uniformly. Every memory is weakened equally, so none stands out. It's like turning down the volume on every channel simultaneously — the relative levels don't change, but everything disappears into the noise floor together.

Sleep does something much cleverer. It reduces the *baseline* while protecting the *peaks*. Imagine a landscape of hills. Ring-down floods the entire landscape equally until everything is underwater. Sleep lowers the water table, leaving the tallest peaks exposed while submerging the low-lying ground.

This selective preservation is what makes sleep an effective memory system rather than a destructive one. It's also why a good night's sleep often makes a problem clearer — not because you've gained new information, but because irrelevant information has been pruned, leaving the essential structure more visible.

## The Machine Learning Convergence

Here's the part that made me sit up: artificial neural networks independently discovered they need something like sleep.

Neural networks suffer from "catastrophic forgetting" — when trained on a new task, they overwrite what they learned on previous tasks. The new learning saturates the weights, exactly like the ring-down problem. This has been a major obstacle in AI since the 1980s.

In 2022, researchers demonstrated that interleaving normal training with periods of "sleep-like unsupervised replay" — where the network disconnects from training data and spontaneously reactivates its own internal representations — dramatically reduces catastrophic forgetting. The network consolidates what it has learned without destroying previous knowledge.

By 2025, this has evolved into frameworks with names like "NeuroDream," where networks explicitly enter a dream phase: they disconnect from input data and replay internally generated simulations to rehearse, consolidate, and abstract patterns from earlier experiences.

The AI researchers didn't arrive at this by studying Tononi's work first. They arrived at it by trying to solve catastrophic forgetting and independently discovering that periodic offline consolidation with selective preservation is the structural solution.

Same problem. Same solution. Different substrates. The territory dictated the path.

## What Forgetting Actually Is

We tend to think of forgetting as memory's failure mode — the thing that goes wrong when memory doesn't work properly. But the ring-down result suggests the opposite: forgetting is memory's *essential maintenance operation*.

A system that never forgets faces three possible fates:

1. **Saturation.** All memory elements reach maximum strength. No new encoding is possible. This is the ring-down endpoint.

2. **Noise dominance.** Weak, irrelevant traces accumulate until they drown out strong, important ones. Signal disappears into noise.

3. **Energy collapse.** Maintaining all connections at high strength becomes energetically unsustainable. In brains, this manifests as the cognitive collapse of sleep deprivation. In physical systems, it manifests as the material reaching a uniformly high-energy state.

Selective forgetting — keeping the peaks, clearing the valleys — is the only escape from all three. It's not a bug. It's the feature that makes sustained memory possible.

Borges understood this. His story "Funes the Memorious" describes a man who, after an accident, remembers everything — every leaf on every tree, every word of every conversation, every moment of every day. Funes cannot think, because thinking requires abstraction, and abstraction requires forgetting the details to see the pattern. His perfect memory is a perfect prison.

## The Deeper Principle

Memory exists through exclusion. A meaningful memory is meaningful because of everything it isn't — everything that was pruned, downscaled, or never encoded in the first place. This is true in amorphous solids, in neurons, in artificial networks, and in the Library of Babel.

The universe trends toward maximum entropy — toward the state where everything is equally probable and nothing is distinguishable. Memory is a local, temporary victory against this drift. But it can only be maintained through active curation: strengthening some connections, weakening others, and periodically clearing the accumulated noise.

Sleep is when your brain fights entropy. And it fights by letting go.
