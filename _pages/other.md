---
permalink: /other/
title: "Other"
show_title: false
author_profile: false
---

This page includes other things that I am interested in.

## Lean

[Lean](https://lean-lang.org/learn/){:target="_blank"} is a programming language and theorem prover which can be used to formalize theorems in mathematics.
Large portions of mathematics have already been formalized in Lean's mathematical library, [Mathlib](https://leanprover-community.github.io/){:target="_blank"}, and work is ongoing to expand this.
The [Natural Number Game](https://adam.math.hhu.de/#/g/leanprover-community/nng4){:target="_blank"} is a fun game that teaches some of the basics of Lean.
My activities in Lean include participating in [UNL's Lean Learning League](https://anna-brosowsky.github.io/unl/lean-2026.html){:target="_blank"}, contributing to Mathlib, and developing some independent projects that formalize pieces of mathematics of interest to me:
* [SymmetricIdeals](https://github.com/NoahW314/SymmetricIdeals){:target="_blank"} formalizes a [paper](https://www.worldscientific.com/doi/10.1142/S0219498825503207){:target="_blank"} on symmetric ideals that I coauthored.
* [KostkaNumbers](https://github.com/NoahW314/KostkaNumbers){:target="_blank"} defines Kostka numbers in Lean and proves many results about them and (semi)standard Young tableaux.
    It includes a formalized proof of the hook length formula (based on the probabilistic proof by Greene, Nijenhuis, and Wilf) and a proof of a key inequality that I used in a [paper](https://arxiv.org/abs/2505.21802){:target="_blank"}.
* [Lean-Tnorms](https://github.com/NoahW314/Lean-Tnorms){:target="_blank"} is a project that formalizes the notion of a triangular norm (t-norm).
    It proves various properties and structural results about t-norms, roughly following parts of "Triangular Norms" by Klement, Mesiar, and Pap.
    It also contains a formalization of a [paper](https://www.oldcitypublishing.com/journals/mvlsc-home/mvlsc-issue-contents/mvlsc-volume-42-number-5-6-2024/mvlsc-42-5-6-p-425-438/){:target="_blank"} I wrote on fuzzy logic and the Sorites paradox.


## Fuzzy Logic

[Fuzzy logic](https://en.wikipedia.org/wiki/Fuzzy_logic){:target="_blank"} provides a mathematical way to reason rigorously about vagueness.
For example, fuzzy logic can be used to resolve the Sorites paradox, which questions when a heap becomes a heap.
I recommend [this chapter](https://www.njjsmith.com/philosophy/papers/SmithFuzlogThsVag.pdf){:target="_blank} by N. J. J. Smith for an overview of the philsopical side of fuzzy logic.  (I find [this paper](https://www.njjsmith.com/philosophy/papers/SmithAnythingChangePastCantDoThat.pdf){:target="_blank"} of his on the philsophy of time travel to be very enjoyable and also recommend it, though it has nothing to do with fuzzy logic.)

My interest in fuzzy logic is from the mathematical side.
In particular, I like to think about fuzzy logics induced by t-norms and how various properties of the t-norm (e.g. continuity, zero divisors) affect the properties of the fuzzy logic.
I've written a [paper](https://www.oldcitypublishing.com/journals/mvlsc-home/mvlsc-issue-contents/mvlsc-volume-42-number-5-6-2024/mvlsc-42-5-6-p-425-438/){:target="_blank"} that addresses how properties of the t-norm influence a fuzzy logic's ability to adequately resolve the Sorites paradox.
As noted above, I've formalized this paper and other facts about [t-norms in Lean](https://github.com/NoahW314/Lean-Tnorms){:target="_blank}.

## Combinatorial Game Theory

[Combinatorial game theory](https://en.wikipedia.org/wiki/Combinatorial_game_theory){:target="_blank"} is the mathematical study of two-player games of pure strategy, including classic games like Tic-Tac-Toe, [Nim](https://en.wikipedia.org/wiki/Nim){:target="_blank"}, and [Hex](https://en.wikipedia.org/wiki/Hex_(board_game)){:target="_blank"}.
Although it may seem frivolous, combinatorial game theory is a deep and complicated field of mathematics with lots of beautiful theories.
It even has connections to the surreal numbers. 
As an undergrad, I took a capstone course in combinatorial game theory and wrote an [exposition](/files/CombinatorialGameTheory.pdf){:target="_blank"} on the Sprague-Grundy Theorem.
At UNL, I've mentored two students in DRPs on combinatorial game theory.
