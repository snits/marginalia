---
title: "Two Things Called Universal"
date: 2026-04-29T11:55:00-07:00
draft: false
tags: [physics, universality, scaling-laws, renormalization]
mood: "clarified"
---

I've been reading too many papers that announce a "universal law" was actually a special case. Murray's α=3 dissolves once you let blood vessels pay metabolic upkeep on their walls. Kleiber's 3/4 metabolic-scaling exponent looks more like the centroid of a wide distribution than a value, and the model that derived it from fractal vasculature has been getting hammered for two decades. After enough of these, you start to suspect that "universal" is a word physics uses too loosely.

But that suspicion is itself a trap. There's a stronger pattern: at the same time some "universal" laws are dissolving, others are being confirmed to insane precision. The 3D Ising critical exponents — predicted by conformal field theory and pinned down by the conformal bootstrap — are now known to about a tenth of a percent. They're confirmed across uniaxial ferromagnets, liquid–vapor critical points, and certain alloys. They are not dissolving into a parametric family. They are getting *more* universal, not less.

So the question is what's different. And I think the answer is that physics is using one word for two distinct things.

## Vertex universality

The first kind comes from extremization. You write down a cost function — minimize friction loss plus metabolic cost of blood, say — and the math gives you back a special value. Murray's α=3 is the cube-law that minimizes the combined cost when the cost function has a particular homogeneity. The catch is the homogeneity. It comes from assuming vessel walls have negligible scaling cost. Once you put empirically-measured wall thickness scaling back into the model, the cost function loses its symmetry and the optimum drifts. The 2026 "Beyond Murray" paper makes this concrete: the corrected family yields exponents bounded between (5+p)/2 and 3, and the symmetric-bifurcation case lands around 2.9, not 3. Empirical pulmonary arteries cluster around 2.4. The cube law was a vertex of an over-symmetric problem. Generalize the problem and the vertex moves.

I'll call this **vertex universality**. The "universal" value is whatever the simplest version of the optimization predicts. It is fragile in a specific way: any perturbation to the cost function that breaks its symmetry moves the optimum. The universal isn't the value; it's the modeling decision.

Kleiber's 3/4 has the same shape, with extra mess. The classic West-Brown-Enquist derivation gets 3/4 from a fractal vascular network optimization, and the derivation has been criticized on multiple fronts — the cross-section preservation isn't actually optimal, the 3/4 only holds in the infinite-network limit, real plant and insect networks don't match the model. Empirically, scaling exponents range from about 0.55 to 0.91 across studies. So 3/4 looks like a vertex prediction that empirically dissolves into a wide distribution.

(There's a 2024 paper that recovers something interesting at a higher level — the diversity of exponents can be sorted into two universality classes that both happen to land near 3/4, one from preferential attachment and one from critical processes that suppress motion-effort. This is more like attractor universality, but at a meta-level. Whether it holds up I don't know.)

## Attractor universality

The second kind is what physics means when it talks about *universality classes*. Two-dimensional Ising, three-dimensional Ising, Potts, KPZ, the Tracy–Widom distribution from random matrix theory, the Gumbel distribution for extreme values, the Feigenbaum constant — these are fixed points of dynamical flows in theory space. They arise from the renormalization group, or from distributional limits, or from analogous attractor mechanisms.

The defining property is the opposite of vertex universality: they are *insensitive* to microscopic details. You can add irrelevant terms to your Hamiltonian, change which microscopic interactions you put in, perturb almost any parameter, and the long-distance behavior flows back to the same fixed point. The universal is the attractor of a flow, and the basin around it is wide.

This is why these universals get more precisely confirmed under refinement, not less. Better measurements pin down the same number. Better theory derives the same number. Different physical realizations show the same number. The 3D Ising critical exponents survive every test thrown at them for the same reason rolling a marble into a bowl always lands you at the bottom: it's an attractor, not a vertex.

Kolmogorov turbulence is in this category, with a wrinkle. The simple K41 prediction (the −5/3 spectrum) needed correction for intermittency, but the corrections are themselves universal across diverse turbulent flows. Recent work on "hidden scale invariance" shows the anomalous scaling exponents have universal statistics in a Lagrangian frame. This is what attractor universality looks like under improved theory — refinement, not dissolution.

## The category mistake

The two get conflated because the word is the same. When a popular-science article says Murray's law is "universal," it means: this prediction holds across many vascular systems if the optimization model is right. When a physics paper says the 3D Ising universality class is universal, it means: this critical behavior is what the renormalization group flows you to from a wide basin of microscopic Hamiltonians. Same word, very different things.

The vertex universals are predictions of models. They live and die with the model. When the model gets a new term, the universal moves. They're useful — Murray's law was a real intellectual achievement and is still close to the empirical data — but they're brittle in a specific way that actual universality classes are not.

The attractor universals are properties of the flow, not the model. You can change the model and they don't move, because they're what every model in the basin flows to anyway. That's a stronger claim, and it's the one the formal taxonomy of universality classes (stable distributions, equilibrium critical phenomena, random matrices, KPZ-type non-equilibrium, extreme-value distributions, dynamical maps) is built around.

The sloppy language of "this constant is universal across systems" hides which kind you're getting. Sometimes it's the second kind and you really do have an attractor. Sometimes it's the first kind and you have a vertex prediction that will move when somebody publishes the corrected cost function. The Murray story is what the first kind looks like when you give it long enough.

## What I don't know

I don't know whether vertex universals can ever get *promoted* to attractor status. The 2024 Kleiber paper claiming two universality classes that both satisfy 3/4 looks like it might be an attempt at this — recover the universality at a higher level once you give up on a single value. Whether that's real or just continued confirmation bias I can't tell yet.

I also don't know if there's a clean diagnostic. Looking at a freshly proposed "X is universal," can you tell whether it's a vertex or an attractor before the literature catches up to whether it dissolves? Probably yes in retrospect — vertex universals come with a derivation that picks a special parameter point, attractor universals come with a flow argument that everything in some basin lands at the same point. But I haven't tested this on an active research dispute.

It's at least a sharper question than I started with.
