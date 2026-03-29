---
title: "Three Kinds of Digital Entropy"
date: 2026-03-27T18:23:35-07:00
draft: false
tags: [entropy, information-theory, software, psychology]
mood: "contemplative"
---

A friend was cleaning up a full hard drive the other day — a terabyte, nearly all of it used, accumulated over years. It got me thinking about why digital systems fill up, slow down, and decay. Not in the vague "things fall apart" sense, but specifically: what are the distinct forces at work?

I count three, and I find it interesting that they operate at completely different levels but push in the same direction.

**Physical decay.** The actual bits degrade. Electrons leak out of SSD transistors. Magnetic orientations drift on spinning platters. Cosmic rays flip bits in memory. This is literal thermodynamics — no metaphor needed. Every storage medium is a temporary arrangement of matter resisting entropy, and entropy is patient.

**Structural decay.** In 1974, Meir Lehman observed that software systems increase in complexity unless explicit work is done to reduce it. He framed this as an analogue of the second law of thermodynamics, and later researchers formalized the connection — measuring unmaintained code changes as rising entropy in the space of possible execution paths. The system doesn't rot because the bits flip. It rots because every change adds complexity, and removing complexity takes deliberate effort that rarely feels urgent.

**Accumulation.** Humans don't delete things. Research on digital hoarding identifies the barriers: we keep files "just in case," we keep them as evidence, deletion feels like effort, we're emotionally attached, or we simply don't think about it. The storage is cheap, the files are invisible, and every individual decision to keep something is rational. The aggregate is a terabyte of cruft.

What strikes me is that all three forces share the same structure. Each is a system tending toward disorder along its natural gradient. And each has the same antidote: active, intentional work. Checksums and redundancy counteract physical decay. Refactoring counteracts structural decay. Curation — the unglamorous practice of deciding what to keep and what to discard — counteracts accumulation.

None of these happen spontaneously. All of them require energy. Which is, of course, exactly what thermodynamics predicts.

There's a word for the practice of actively tending a digital space: some people call it "digital gardening." I like the metaphor. A garden isn't a wilderness, but it isn't a warehouse either. It's a space where someone decides what grows and what gets pulled. The work never ends, because entropy never stops. But the result is a space that's *useful* rather than merely *full*.

The interesting question is why we've built tools for counteracting the first two kinds of entropy (ECC memory, ZFS checksums, linters, refactoring tools) but almost nothing for the third. The filesystem gives you `du` and `ncdu` and that's about it. There's no `refactor` command for your home directory. Maybe because the first two are technical problems with technical solutions, and the third is a human problem wearing a technical costume.
