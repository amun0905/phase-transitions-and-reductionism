---
title: "Reduction of Thermodynamics to Statistical Mechanics"
author: "Amun Govil Lie"
institution: "King’s College London"
module: "Philosophy of Physics I: Space and Time (5AANB053)"
tutor: "Caspar Jacobs; Lecturer: Dr Eleanor Knox"
date_submitted: "8 January 2020"
word_count: 2606
---

# Inconsistencies Within Statistical Mechanics

One of the supreme scientific achievements of the 19th century was the development of thermodynamics (TD). Motivated by the desire to increase the efficiency of steam engines, this branch of physics managed to establish remarkably elegant laws of universal applicability using just a few simple concepts and the relations between them. The scope and accuracy of its explanatory power are among the qualities that make TD one of the few branches of physics capable of eliciting endorsement like this from Albert Einstein:

> "[Classical thermodynamics] ... is the only theory of universal content concerning which I am convinced that, within the framework of the applicability of its basic concepts, it will never be overthrown."

However, even though TD has this universal applicability, it is only concerned with the macroscopic, large-scale quantities of a system. Meanwhile, a theory of the corresponding microscopic constituents, the particles, of a system already had its earliest developments back in the 17th century – the theory of classical mechanics. Therefore, once TD was fully developed, physicists were left with one theory describing how the individual particles in a system act, and another describing how the system as a whole acts. Intuition suggests that these two theories must be related somehow, and so began the project of reconciling the macroscopic theory of TD with the microscopic theory of classical mechanics. This project has come to be known as statistical mechanics (SM) and can only be said to be greatly successful. However, some features of TD have proved more difficult to represent in SM than others and in this essay, I examine one such feature: phase transitions (PT). I will explain what it is about PT that poses a challenge for the reduction of TD to SM and argue that, as it stands today, this challenge cannot be overcome. I argue that this problem lies not with TD or reduction itself but with SM not having a consistent account of PT – an account which cannot be made consistent without significant developments in the field. This is because current SM methods used to represent PT require fictitious systems of infinite particles, which cannot be viewed as approximations and which lack justification for being used in a counterfactual definition of PT.

## A Word on Reduction

Reductionism is the thesis that all successful theories can be reduced to one fundamental theory. However, there are many different interpretations about what it means for one theory to be reducible to another. In order to avoid getting into this finicky territory, I will assume that all these interpretations require the base theory of a reduction (here SM) to be consistent before a reduction can happen. This seems like a reasonable assumption since an inconsistent theory is one that entails a contradiction, and there would be no wish in the first place to reduce a successful, consistent theory (here TD) to an inconsistent, contradictory theory (here SM). The assumption will also certainly be valid for any model of reduction based on derivation, since nothing useful can be deduced from inconsistent premises. Therefore, in order to argue that the challenge of reducing SM to TD (with respect to PT) cannot currently be overcome, it will suffice to show that SM is not entirely consistent in its treatment of PT.

## The Problem of Phase Transitions

I will begin by looking at how TD treats PT. While potentially problematic in SM, PT are well accounted for in TD and a rigorous description can be found in Eugene Stanley’s *Introduction to Phase Transitions and Critical Phenomena* (1971). PT are most commonly used to describe a system’s transition between three states of matter: solid, liquid, and gas. The state of a system can be described by a state function called the thermodynamic free energy, which depends on the state variables used to describe the system. The feature of TD that this essay is concerned with is that for a typical choice of variables, the free energy of a system develops a singularity, or non-analyticity, as the system transitions from one phase to another.

Since SM was developed to explain TD on a micro-level, a natural view one might take is that this singularity must also be found in the SM explanation of PT. As expressed by Chuang Liu (1999):

> "In general, phase transitions as TD phenomena are shown as singularities [...], a feature that any microexplanations (or SM explanations) must recover."

So, can SM recover these singularities? For the SM explanation of PT, I refer to Liu’s description based on Toda et al.’s *Statistical Physics I: Equilibrium Statistical Mechanics* (1983). Corresponding to the TD free energy function, the partition function \( Z \) in SM is a state function dependent on state variables. However, because \( Z \) is a sum of exponential functions, it can only have a singularity if one takes the thermodynamic limit (TL) where the system’s volume goes to infinity while keeping the particle density fixed. In other words, the only way for SM to recover the singularity in the TD explanation of PT is to appeal to an infinite system.

This is problematic because it seems to say that only systems of infinite particles can undergo phase transitions. However, common sense tells us this is not true. The system of water in a kettle is presumably made up of a finite number of particles – yet, we see such systems undergo phase transitions all the time. This leads Liu to conclude that phase transitions are some sort of irreducible, *truly emergent property*.

## Taking Thermodynamics Too Seriously?

There appears to be one immediate way of avoiding Liu’s conclusion. This approach is advocated by Craig Callender in his paper *Taking Thermodynamics Too Seriously* (2001). Here, Callender objects to Liu’s claim that SM must recover the singularity used in the TD description of PT. He points out that:

> "After all, the fact that thermodynamics treats phase transitions as singularities doesn’t imply that statistical mechanics must too."

and that

> "We cannot endorse this knee-jerk identification of mathematical definitions across levels."

Callender is correct in pointing this out. There seems to be no fundamental reason why SM would have to use the same mathematical definitions in representing some phenomena as TD does. After all, SM and TD are two separate theories and the frameworks they work in are independent of each other.

Another way of thinking about this is in the context of Nagelian reduction. In this model, as described in Ernest Nagel’s *The Structure of Science* (1961), a target theory (here TD) is deduced from a base theory (here SM), along with some auxiliary assumptions and bridge laws connecting terms between the two theories. However, it was realized that the laws deduced from a base theory rarely turn out exactly the same as the target theory laws. Instead, the base theory provides analogue laws that are approximately the same as the target theory laws, and often only differ in the sense that they are more accurate than the target theory laws. In this framework, one could imagine SM representing PT without singularities in a way that would provide a more accurate understanding of PT in TD – perhaps involving a realization that there actually is no singularity in the TD free energy function of a system undergoing PT – it just looks like it.

However, the problem is that despite all this, the most successful approaches to representing PT in SM do represent them as singularities. These approaches include mean field theories, Landau theory, Lee-Yang theory, and methods using renormalization groups. There are some approaches that model PT without using singularities, like the approach advocated by Dieter Gross (*Microcanonical Thermodynamics: Phase Transitions in Small Systems*, 2001), but these appear to be limited in applicability. Therefore, until SM develops general methods for representing PT as non-singularities, the problem of SM requiring infinite systems remains.

## Approximations

A different plausible solution to the problem as diagnosed by Liu is to dismiss that the requirement of an infinite system is a problem in the first place. Could one not just say that taking the TL where a system’s particles go to infinity serves as an approximation for a system with very many particles? After all, these kinds of approximations are frequently used in physics.

Liu himself addresses this question in his paper. He points out that TL seems to be importantly different from approximations of finite, but large systems seen elsewhere in physics. This is because, as one lets a PT system grow towards infinity, there is no sense in which a singularity is being approximated with more and more accuracy. In Liu’s words:

> "At no stage of the process in which V, N → ∞, is a singularity of a system even roughly or approximately defined."

Because TL does not approximate the actual value in this sense, it cannot be said to serve as an approximation. With this established, the following inconsistency within SM can be explicitly stated:

- We know PT happen in finite systems.  
- General SM methods require truly infinite systems for PT to happen.

Strictly speaking, this is not an inconsistency within SM. The inconsistency only appears once SM is compared to observations in the real world. However, assuming we want SM to correspond to the real world, the first statement can be treated as a premise within SM. This then becomes the inconsistency SM must resolve before a reduction can take place.

## A Solution?

Perhaps the most promising way of resolving this is described in Paul Mainwood’s thesis *Is More Different? Emergent Properties in Physics* (2006). In this, he proposes the following definition for interpreting phase transitions:

> **Definition 1.** Phase transitions occur for a finite system in state S if and only if \( F_\infty(S) \) has a singularity.

Where \( F_\infty(S) \) denotes the SM free energy of a system in TL. This definition provides a way of avoiding the inconsistency described in the previous section. Instead of saying PT in SM happen in the truly infinite systems which develop singularities, one says that PT happen in the finite systems which *would* develop singularities if taken to TL.

At first glance, this may seem to solve all problems. The inconsistency in SM has now disappeared: phase transitions can occur in finite systems. The proposal also keeps our model of PT well-defined and is, according to Mainwood, "in keeping with the practice of physicists." This leaves us with consistent, well-defined models of PT both in TD and SM. Presumably, all one would have to do for the reduction to work now is to employ a simple bridge law making PT in TD correspond to PT in SM, and e.g., singularities in the TD free energy of a system could be deduced simply from SM and some auxiliary assumptions.

However, there are a few problems with this approach. Mainwood mainly defends Definition 1 against two objections – one having to do with how a counterfactual definition can tell us anything about a real system, and the other about how the procedures for taking TL essentially are up to us. These objections are mostly unproblematic (see Mainwood for why). In my view, the real reason why the solution is not satisfying is because it lacks justification in the first place. It is a play on words one can use to make the puzzle fit, but one has no other justification for using it than the wish to make the puzzle fit. Mainwood mentions empirical success as possible justification, but can this be a valid justification?

I don’t think so. To be clear, I do think empirical success is a good reason for continuing to employ Definition 1 in practice. However, I think it should be recognized that we do not have genuine theoretical justification for doing it beyond the fact that it seems to serve us well in practice. Remember, the point of Definition 1 is to remove the inconsistency that PT can only happen in infinite systems. But this inconsistency is based on a rigorous proof that singularities in SM can only happen in infinite systems. This is a mathematical proof, necessarily independent of empirical success. Therefore, empirical success cannot have any bearing on its conclusion.

This might be a case where Callender would argue we are taking TD too seriously, but I would respond that taking this result at anything other than face value would be to not take TD seriously enough. One cannot ignore or skew a result just because one doesn’t like it. If the interpretation of this mathematical proof is to be changed, this must be done based on physical or mathematical evidence independent of our intuitive wishes.

Mainwood does go on to describe how exactly this kind of evidence can be found in some specific cases. However, he admits that these justifications are not general:

> "I admit that finite-size crossover also only provides an example of how we might justify the application of our theories of phase transitions to near-critical systems — it is not a general prescription."

Based on this, there may be adequate justification for employing Definition 1 and resolving the infinite-particle-problem for some systems in SM. However, without a general justification available, the inconsistency cannot be said to be fully resolved and still prohibits a general reduction of PT from TD to SM.

## Concluding Remarks

In conclusion:

- Singularities in SM only occur in infinite systems.  
- Even though they don’t have to, current SM methods represent PT as singularities.  
- TL cannot be viewed as an approximation because a singularity is not being approximated as a system grows towards infinity.  
- Definition 1 is not a satisfying solution because it lacks general justification beyond working well in practice.

From this I conclude that there is an inconsistency within the SM explanation of PT which prohibits a successful reduction from TD to SM. This inconsistency consists of SM stating that (generally) only infinite systems can display PT even though it knows its target systems are finite, and that nevertheless PT happen in these. This is not to say a reduction from SM to TD is fundamentally impossible. It is only saying that the challenges facing this reduction cannot be solved simply by changing our interpretation of certain aspects of SM. Overcoming the challenge would consist of more substantial developments in the field of SM such as (i) finding a general, successful way of representing phase transitions as analytic, non-singularities or (ii) finding general, valid justification for Definition 1.

---

### Bibliography

Callender, Craig. “Taking Thermodynamics Too Seriously.” *Studies in History and Philosophy of Modern Physics* 32, no. 4 (December 2001): 539–553. https://doi.org/10.1016/S1355-2198(01)00025-9.

Dizadji-Bahmani, Foad, Roman Frigg, and Stephan Hartmann. “Who’s Afraid of Nagelian Reduction?” *Erkenntnis* 73, no. 3 (November 2010): 402. https://doi.org/10.1007/s10670-010-9239-x.

Gross, Dieter H. E. *Microcanonical Thermodynamics: Phase Transitions in Small Systems.* Singapore: World Scientific, 2001.

Liu, Chuang. “Explaining the Emergence of Cooperative Phenomena.” *Philosophy of Science* 66, no. (September 1999): S92–S106. https://doi.org/10.1086/392718.

Mainwood, Paul. *Is More Different? Emergent Properties in Physics.* PhD diss., Oxford University, 2006.

Nagel, Ernest. *The Structure of Science.* London: Routledge and Keagan Paul, 1961.

Norton, John D. “Infinite Idealizations.” *Vienna Circle Institute Yearbook* 17 (2012): 197–210. https://doi.org/10.1007/978-3-319-01899-7_14.

Stanley, Eugene H. *Introduction to Phase Transitions and Critical Phenomena.* Oxford: Clarendon Press, 1971.

Toda, M., R. Kubo, and N. Saitô. *Statistical Physics I: Equilibrium Statistical Mechanics.* Berlin: Springer-Verlag, 1983.

