---
title: "Reversing Imperative Parallel Programs"
collection: publications
permalink: /publication/2017-express-sos
excerpt: '<a href="https://doi.org/10.4204/EPTCS.255.4">[Download]</a>'
date: 2017-09-04
venue: 'Combined 24th International Workshop on Expressiveness in Concurrency and 14th Workshop on Structural Operational Semantics (EXPRESS/SOS)'
citation: 'J. Hoey, I. Ulidowski, and S. Yuen. Reversing imperative parallel programs. In EXPRESS/SOS, volume 255 of Electronic Proceedings in Theoretical Computer Science, pages 51-66, 2017.'
---

[Download this paper here](https://doi.org/10.4204/EPTCS.255.4)

**Abstract:** We propose an approach and a subsequent extension for reversing imperative programs. Firstly, we produce both an augmented version and a corresponding inverted version of the original program. Augmentation saves reversal information into an auxiliary data store, maintaining segregation between this and the program state, while never altering the data store in any other way than that of the original program. Inversion uses this information to revert the final program state to the state as it was before execution. We prove that augmentation and inversion work as intended, and illustrate our approach with several examples. We also suggest a modification to our first approach to support non-communicating parallelism. Execution interleaving introduces a number of challenges, each of which our extended approach considers. We define annotation and redefine inversion to use a sequence of statement identifiers, making the interleaving order deterministic in reverse.

[Back to Publications](https://jameshoey.github.io/publications/)
