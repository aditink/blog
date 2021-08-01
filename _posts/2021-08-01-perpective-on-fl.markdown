---
layout: post
title:  "A Perspective on Formal Verification"
date:   2021-08-01 07:47:02 -0400
categories: formal verification
---
Formal methods help make software reliable by checking that code satisfies contracts. They compete in some sense with testing, which also checks that software behaves as intended by looking at the behavior for certain inputs.

Should enough tests be written, testing should in principle be morally equivalent to formal verification. In an infinite input possibility setting (involving, for example, real numbers as an input domain), naively one might think that the number of tests needed for complete assurance is infinite. But it turns out that since the behavior of the code itself can be analysed and in some sense, broken into pieces of similar behavior, having a _witness_ (an input case for which the code succeeds) for every piece suffices to verify the program over the entire state space. In fact, this is how formal verification generally handles hte problem of checking elementary first order logic arithmetic statements. It uses _quantifier elimination_, a process that takes in a logical statement and returns its truth value. Under the hood a similar collapse of state-space, and witness-checking is involved.

We can then see formal verification as breaking  code down to the "pieces" of monotonic behavior, where a single witness is enough and then finding and checking the test case corresponding tol the witness. In other words, formal verification is a structured way of writing test cases to cover the entire state space, ensuring that you really have an input for every branch, every reason for behavior to diverge. This perspective makes formal verification a software engineering concern, a way to obtain assurance about the quality of your testing,

A natural direction that this correspondence might suggest we explore is auto-generation of exhaustive tests at a human-readable level. Such tests may potentially be better able to help humans understand why code works - or fails - than proofs, just by presenting this information from a different, example centered perspective.
0 comments on commit a509cf2
