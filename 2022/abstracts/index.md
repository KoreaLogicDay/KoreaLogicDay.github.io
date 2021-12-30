---
name: The first Korea Logic Day 2022
title: null
---

_Change the language to [한국어](https://korealogicday.org/2022/index_kr.html)_

# [The second Korea Logic Day 2022](https://korealogicday.org/2022), 14 January 2022

# Talk Abstracts

<p id="abstract-Yang-Eunsuk"></p>


### Thies, Holger (Kyoto University), "_An application of constructive dependent type theory to certified computation over the reals_"

In exact real computation, real numbers are treated as basic entities that can be manipulated exactly without introducing rounding errors.
This is often realized by adding a datatype for reals and arithmetic operations on them as primitives in programming languages.
In this talk, we describe some recent progress on formally verifying exact real computation.
We propose a constructive axiomatization of real numbers in a dependent type theory which formalizes real numbers in a conceptually similar way as some mature implementations of exact real computation.
We implemented our theory in the Coq proof assistant and use Coq’s code extraction tools to extract Haskell programs from proofs.
We extended the extraction to map primitive operations on constructive real numbers directly to the corresponding operation in the AERN framework, a Haskell implementation of exact real computation.
In the talk, we particularly focus on aspects of the formalization dealing with multivaluedness and non-deterministic computation.
We also present some examples of extracting non-deterministic programs from proofs.

(This talk is based on j.w.w. Sewon Park and Michal Konečný)



### Yang, Eunsuk (Jeonbuk National University), "_Implicational tonoids, embeddability, and representations_"

We investigate implicational tonoids and their representations. More precisely, we first review implicational tonoid matrices. We then introduce their representations. We in particular consider embeddability property for implicational tonoid matrices. Finally, we generalize these to assertional implicational tonoid algebras and their embeddabilty and representations.


