---
name: The Fourth Korea Logic Day 2025
title: The Fourth Korea Logic Day 2025
description: January 13 - 15, 2025 • Changwon, Republic of Korea
lang_target: /kr/2025/abstracts/
permalink: /2025/abstracts/
primary_links:
 - 
  link: /2025/
  name: Korea Logic Day 2025
 - 
  link: /kr/2025/abstracts/
  name: 한국어
---

# Talk Abstracts

## Tutorial Talk

### Shichang Song : _Projective Fraisse limits and profinite groups_

We show that the projective Fraisse limit of the class of finite groups is the free profinite group on a countably infinite set converging to 1. Also, we prove that its automorphism group has ample generics. Joint work with Sulin Hu.

## Invited Talks

### Carl-Fredrik Nyberg Brodda : _Some decision problems in finitely presented groups and semigroups_

I'll give an overview of some algorithmic problems in algebra, focussing on the word problem and membership problem. I'll first present some recent results in the past few years by myself and coauthors (Foniqi & Gray) on the word problem for one-relation monoids, a problem that has remained open for over a century, since 1914. Using embeddings of right-angled Artin groups and trace monoids, I will show how the first known undecidability results for one-relation monoids can be proved: the rational subset membership problem can be undecidable. Finally, I'll present some recent results by myself and Gray (East Anglia), where we fully classify which Artin groups have decidable submonoid/rational subset membership problem. This extends a result from 2007 by Lohrey & Steinberg, who classified which right-angled Artin groups have decidable membership problems.


### Seungrak Choi : _Formalizing intuitionistic negations in natural deduction system_

This talk examines how historical intuitionists have employed the concepts of negation and contradiction in two distinct senses, focusing particularly on the works of L. E. J. Brouwer, Michael Dummett, and Neil Tennant. In doing so, it reveals that within intuitionism, the notion of contradiction has also been utilized in two different ways, especially regarding the definition of negation in terms of contradiction. Building on this historical and philosophical background, the talk argues that standard intuitionistic natural deduction systems fail to capture the full spirit of intuitionism. They do not adequately formalize the intuitionistic notion of negation and thus cannot fully represent the intuitionistic stance against the principle of excluded middle—that every meaningful statement is either true or false.

More specifically, this talk contends that the classical notion of contradiction, commonly symbolized as ⊥ (falsum), is insufficient for representing the meaning of intuitionistic negations, particularly when it comes to the concept of “prooflessness.” In the standard intuitionistic natural deduction systems, the crucial difference between “a statement not being true” and “a statement being false” collapses. To remedy these shortcomings, the talk proposes an enhanced intuitionistic natural deduction system that incorporates both the classical notion of contradiction (⊥) and a new symbol (⋏), representing an intuitionistic notion of contradiction centered on the absence of proof. By integrating ⋏, this approach preserves the important distinction between statements lacking proof and those proven false, thereby ensuring a more faithful reflection of intuitionistic principles. The resulting system, which employs two kinds of contradictions and negations within a single logical framework, resonates with recent developments in paraconsistent and relevant logics, while suggesting that natural language may inherently rely on this nuanced blend of notions.

### Javier de la Nuez González 

### Hanul Jeon : _On a proof-theoretic dilator and Pohlers' characteristic ordinals_

### Dongwoo Kim : _Reference and Analysis in Frege_

I discuss Frege's definition of number. I argue that the definition is intended to preserve the references of the ordinary number terms.

### Sewon Park : _Real functions are continuous, continuously, computationally_

In this talk, I present an axiomatization and formalization of computable analysis in constructive dependent type theory. It provides an axiomatic type of real numbers where constructive proofs from mathematical analysis are extracted to certified real-number computation programs. The axioms are sound for the realizability interpretation of dependent type theory in the category of assemblies over Kleene's second algebra. To formalize interesting hyperspace computations, we further assume a general continuity principle from which we prove that all real functions are, in a sense, continuously continuous. 
This talk is based on my joint work with Michal Konečný and Holger Thies.


## Student Talks


### Yeonhong Kim : _Standard completeness of weak-u-associative uninorm logics_

In this talk, we investigate the standard completeness of weak-u-associative uninorm logics, called UWABULs, following Yang(2024). The basic idea for proving the standard completeness of a fuzzy logic is to find a method to embed the algebraic semantics of the logic into the unit interval [0, 1]. The core task of the embedding is to preserve fundamental properties of algebraic semantics, especially those of its aggregation operator.

T-norms are a well-known class of aggregation operators in fuzzy logics. They can be divided based on their properties, such as left-continuity, semilinearity, and others. Furthermore, many works have generalized the concept of t-norm. Some properties of various fuzzy aggregation operators are partially reflected in the concepts of weak-u-associative uninorms. Accordingly, in this talk, we clarify some ideas behind proving the standard completeness of major fuzzy logics and provide a strategy to understand the proof of the standard completeness of UWABULs as presented in Yang(2024).

### Jisun Baek : _Graphs on Infinite Cardinals: The Erdős-Dushnik-Miller theorem_

Exercise I.19 in Set Theory by Kunen states that any well-ordering on an infinite cardinal  $\kappa$ agrees on $\kappa$-many elements with the usual ordering. A stronger result is described using the Erd\H{o}s-Rado arrow, $\kappa \rightarrow (\kappa, \omega)^2$, which demonstrates that any graph with a $\kappa$-sized vertex set contains either a $\kappa$-sized clique or $\omega$-sized independent set. In this talk, we explore the Erd\H{o}s-Dushnik-Miller theorem, $\kappa \rightarrow (\kappa, \omega+1) ^2$ for regular uncountable cardinals $\kappa$, as well as analogous results by Shelah for certain singular cardinals.

### 서민철 : _Multi-Agent Simulative Belief Ascription_

This paper presents the outline of the model of Multi-Agent Simulative Belief Ascription, (MASBA), a novel approach to model how an agent represents other agent’s belief state, incorporating belief revision to effectively address the dynamic nature of belief changes in multiagent contexts. In MASBA, each agent’s belief is represented as a distinct compartment, allowing for the sharing of beliefs through communication while maintaining their individual integrity. A key feature of MASBA is its handling of simulative beliefs, being casually characterised as ‘what would have believed if I were the case’, which may not always compatible with the ascribee’s actual belief state. When constructing the simulative belief state, the revision occurs with respect to the ascriber’s belief state but with a priority on the ascribee’s plausibility ordering. This structure enables MASBA to provide an intuitive perspective on cognitive faculty of ‘mindreading’, representing it as a mental simulation that merges our beliefs with the shared beliefs of others, thereby enriching our understanding of multi-agent belief dynamics and cognitive processes.


### Kijeong Lim : _고전일차논리의 새로운 Coq 형식화와 건전성 및 완전성 정리의 증명_

In classical first-order logic, the soundness theorem states that syntactic entailment implies semantic entailment, while the completeness theorem asserts the converse. In this study, assuming the law of excluded middle, proofs of the soundness theorem of a Hilbert calculus with respect to Tarski's semantics and the completeness theorem for all countable first-order languages are presented. This formalisation, written in Coq, gives named quantifiers and Leibniz equality and enables one to assume an infinite number of axioms.
