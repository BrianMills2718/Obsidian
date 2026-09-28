---
title: Deleuze, Trajectory Space, and Collective Competence
date: 2026-09-28
tags:
  - deleuze
  - control
  - dynamical-systems
  - causal-inference
  - collective-competence
  - michael-levin
  - erik-hoel
  - cybernetics
  - reachability
  - coarse-graining
status: working-notes
---

# Deleuze, Trajectory Space, and Collective Competence

## Why this note exists

This note captures the main conceptual trajectory of a long discussion that began with Gilles Deleuze's Postscript on the Societies of Control and gradually translated its philosophical vocabulary into questions about causal structure, dynamical systems, reachability, multiscale competence, and experimental design.

The discussion eventually connected strongly to the BrianMills2718/collective-competence repository. A much more detailed project-facing research note was created there at research/deleuze-trajectory-space.md.

This Obsidian note is the conceptual map and conversational synthesis.

## Core trajectory

- The starting point was Deleuze's rough historical distinction among sovereignty, discipline, and control.
- The first major objection was that these are poor literal categories: killing is bodily control too; schools have always classified people; reputation, credit, and informational judgment predate digital systems; real institutions combine multiple mechanisms.
- The useful reconstruction was to treat them as idealized modalities of constraint rather than mutually exclusive social types.

## Machines as process-level coarse-grainings

The discussion challenged the breadth of Deleuze's term machine. If everything that transforms a flow is a machine, then the category risks becoming universal and weakly discriminative.

The useful reconstruction was: a machine can be treated as a process-level coarse-graining selected because it exposes a causally useful transformation.

This makes machine/object a difference of explanatory level rather than a metaphysical opposition. The same physical realization can be an object at one scale, a set of interacting processes at another, and a component of a larger mechanism at another.

## Assemblages and scale dependence

An early definition of assemblage as a temporary organization was rejected as too vague. Everything is temporary at some timescale.

The stronger formulation is: an assemblage is an organization whose coherence is relative to a declared timescale, representation, intervention family, and explanatory task.

General rule: words like stable, temporary, enclosed, persistent, fixed, and dynamic are meaningless without a timescale or resolution.

## Enclosure as a general causal boundary

Foucauldian enclosure begins spatially: prison, school, hospital, barracks.

The discussion generalized this to: physical enclosure is one possible coarse-graining, but a useful system boundary can be spatial, temporal, informational, relational, organizational, or dynamical.

This produced the idea of dynamic enclosure: a system may be usefully bounded by causal or control coherence rather than by skin, walls, or instantaneous spatial containment.

## Agency without libertarian free will

The source often framed control as erosion of autonomous agency. That was criticized because the conversation assumed no libertarian free will.

The better question became: which variables and interventions have causal leverage over future trajectories, and at what scale?

This replaces a metaphysical freedom problem with transition structure, causal sensitivity, reachability, controllability, intervention effects, and scale selection.

## Dividualization as a spectrum

Deleuze's dividual describes people decomposed into variables such as credit score, risk category, test score, watch history, or demographic profile.

The categorical version was rejected because people have always been decomposed into attributes.

The stronger version is: dividualization is the degree to which components of a representation can circulate, recombine, and exert causal effects independently of the rest of the represented person or system.

Modern digital systems increase portability, automation, recombination, persistence, and cross-context causal use. They do not invent divisibility itself.

## Mold versus modulation

- Mold: a constraint whose parameters remain comparatively fixed while cases pass through it.
- Modulation: a constraint whose parameters update with state, feedback, time, or history.

Example:

    mold: pass if score >= 70
    modulation: pass if score >= previous_score + 5

The distinction remains timescale-relative.

## The major turn: trajectory space

The most important conceptual shift was away from vague control-of-the-future language and toward trajectory-space geometry.

A constraint architecture can alter which trajectories are reachable, route costs, route probabilities, route redundancy, robustness, reversibility, sensitivity to initial conditions, controllability, and path dependence.

This became the main technical interpretation of what the earlier philosophical discussion was trying to get at.

## Territorialization, striation, and lines of flight

### Territorialization

Useful reconstruction: stabilization of a region, relation, organization, or recurring pattern in trajectory space.

Important warning: stabilization is not the same as competence. A passive attractor can stabilize a state without sensing, feedback, repair, or adaptation.

### Striation

The strongest technical translation was constraint-induced anisotropy of trajectory space: some transitions become easier, harder, robust, fragile, reachable, or unreachable.

### Line of flight

A cautious technical proxy is a trajectory that becomes available after the constraint architecture changes and that escapes the prior organization.

Experimental conclusion: do not add line of flight as a project metric when standard reachability language is clearer.

## Liberation is not the same as welfare

The discussion rejected less control = better.

More trajectories can include catastrophic, unstable, or unreliable trajectories. Support size, entropy, controllability, robustness, expected utility, and option value are different quantities.

Control should therefore be treated as normatively neutral until evaluated against a criterion.

## Utilitarianism and causal structure

A serious consequentialist already cares about causal mechanisms, uncertainty, second-order effects, variance, tail risk, model error, path dependence, option value, and intervention costs.

The clean synthesis was: dynamical/causal analysis tells us how interventions reshape trajectory distributions; utilitarianism supplies the utility function over those trajectories.

Deleuze therefore does not supply a competing optimization principle. At most, the vocabulary can act as a model-construction heuristic that draws attention to hidden causal structures.

## Michael Levin connection

The conversation found strong overlap with Michael Levin's work on multiscale competency, problem spaces, nested agents, goal-directedness without consciousness, higher-level organization shaping lower-level option spaces, morphogenesis, and regeneration.

A useful experimental translation is: manipulate higher-level organization and measure how lower-level reachable states or transition probabilities change.

## Erik Hoel and causal emergence

Hoel became relevant to the question of whether a useful macro boundary can be discovered empirically rather than assumed.

The Collective Competence repo already contains an important negative result: Q1-009 tested a chosen macro/micro partition and the tested macro did not show positive causal emergence.

Methodological warning: a macro boundary must earn its privilege empirically.

## Boundary discovery

One of the most promising directions was: can a useful collective boundary or coarse-graining be discovered rather than stipulated?

Candidate criteria include intervention-relevant prediction, causal effectiveness, compression, cross-challenge stability, transfer, and minimal sufficient state.

Important constraint: best boundary depends on what is being optimized. There may be no single privileged boundary.

## Reachability versus realization

A major formal distinction was:

1. the goal state exists;
2. the goal is reachable;
3. the system's native dynamics realize a reachable route;
4. the realization remains robust under challenge.

This was strongly supported by existing Collective Competence experiments.

## Existing repo connections

### P2-003

Immovable barriers create exact reachability partitions. This is almost a literal example of striation in a transition graph.

### P2-004

Moveable passive cells preserve a different invariant: their relative order. Different kinds of damage reshape reachable space in different ways.

### P2-005

Explicitly separates unreachable, reachable but unrealized, and reachable and robustly realized.

### Experiments 06–11

Separate target information, current-state information, reporter integrity, memory, action repertoire, and structural reachability.

### Experiment 12

The Growing NCA work adds richer failure-boundary structure: lesion amount, geometry, location, developmental timing, latent-state spatial compatibility, and action availability.

Conclusion: competence boundaries are often multidimensional surfaces, not scalar thresholds.

### Q1-009

Directly implemented effective information, causal emergence, coarse-graining, and empowerment.

Two important negative lessons: the selected macro coarse-grain did not exhibit causal emergence, and empowerment behaved more like unused unilateral capacity than a defensible general agency measure.

## Path dependence and representation sufficiency

Experiment 12's action-blackout result motivated the ruts analogy: temporary action restriction followed by persistent later divergence after normal actions return.

But apparent history dependence can result from omitted hidden variables.

The useful research question becomes: at what representation does history cease adding predictive information?

A representation ladder could compare visible state only; visible plus latent summaries; visible plus spatial latent compatibility; and full state.

## Constraint-induced topology of competence

The strongest overall synthesis was: competence should be analyzed relative to the geometry of admissible trajectories.

Potential quantities include reachable-set size, shortest route, route cost, route redundancy, realization probability, robustness, reversibility, basin structure, and history dependence.

The discussion rejected inventing a single striation score without evidence.

## Cross-scale competence conflict

A collective can become more competent while restricting its components.

Example pattern:

    collective competence increases
    component option space decreases

This suggests cross-scale competence tradeoffs. The same architecture can help one scale while constraining another.

## Causal coarse-grains are not automatically agents

A useful macro-description may be causally coherent, predictively useful, or interventionally sufficient without being an agent.

The conversation separated causal coherence, control coherence, goal coherence, and competence.

## Goal equivalence and mechanism equivalence

The repo already treats candidate goals as equivalence classes when evidence cannot discriminate them.

The discussion generalized this to observational equivalence, interventional equivalence, and mechanistic distinction.

Competence may sometimes be best represented as an equivalence class of counterfactual behavior under a declared intervention family.

## Option value under uncertainty

Future information may change which choice is optimal, so optionality can have instrumental value even if freedom has no intrinsic value.

This provides a consequentialist reason to care about reversibility, avoiding lock-in, and route diversity.

## Measurement becoming causal

One of the strongest descendants of the original society-of-control theme was:

    measurement
      -> policy/selection
      -> behavioral adaptation
      -> new measurement

Once a metric affects access or reward, it becomes part of the causal architecture.

This connects to Goodhart effects, metric gaming, algorithmic scoring, and adaptive measurement systems.

## Endogenous modification of the problem space

A highly competent system may do more than navigate a fixed state/action space. It can change available actions, sensors, communication, morphology, environment, representations, or institutions.

Conceptually:

    (S_t, A_t, G_t)
      ->
    (S_(t+1), A_(t+1), G_(t+1))

This was considered one of the most interesting directions because it is not reducible to ordinary fixed-graph reachability.

## Observability–controllability–policy decomposition

A clean taxonomy of failure emerged:

1. cannot distinguish states requiring different responses;
2. cannot reach the required state;
3. can distinguish and reach, but native policy fails.

This may become a useful general architecture for interpreting competence failure.

## Competence composition

A central Collective Competence question is: under what conditions do component competencies compose into whole-system competence?

There is no reason to expect K(A + B) = K(A) + K(B).

Possible regimes include weak parts -> strong whole; strong parts -> weak whole; coupling creates a new competence; adding a capable component creates interference; or collective robustness comes at the cost of component flexibility.

This was identified as one of the most fundamental open directions.

## Robustness versus plasticity

Strong stabilization may improve recovery under familiar perturbations while reducing adaptability to novel ones.

This gives a possible tradeoff:

    canalization up
      -> familiar robustness up
      -> adaptability may go down

This should be treated as a hypothesis, not a universal law.

## Endogenous goal change

Need to distinguish policy adaptation, belief/environment estimate change, representational change, and genuine goal change.

This is especially relevant to Goal Discovery.

## Multi-objective competence

Real systems often face multiple incompatible criteria. Competence may therefore form a Pareto frontier rather than admit a single scalar ordering.

## Causal bottlenecks

A small component or relation can have disproportionate leverage over future trajectory space.

Useful question: how much does intervening on component i change reachability, route redundancy, recovery, or robustness?

## Timescale-dependent boundaries

The best agent/system boundary may depend on the horizon.

    B_star = B_star(T)

A boundary useful at milliseconds may differ from one useful at developmental or social timescales.

## Adversarial competence

The environment may itself adapt strategically. Competence may therefore need to be evaluated under co-adaptation, strategic obstruction, deception, arms races, and responsive opponents.

## Counterfactual identity

Regeneration creates an identity question: if components are replaced but counterfactual organization and competence remain, in what operational sense is the system the same?

A scientific treatment would focus on invariants such as response to intervention, competence profile, goal-equivalence class, and causal organization.

## Resource-bounded reachability

Binary reachability is often too permissive.

A more useful object is R(s ; T, E, I), where T = time, E = resources/energy, and I = information budget.

This captures practically reachable rather than merely graph-reachable states.

## Ashby's requisite variety

This became one of the strongest established-theory connections.

Core idea: a regulator requires enough effective response variety to handle the disturbance distinctions relevant to its goal.

This can unify sensing, action repertoire, and challenge complexity.

## Minimal intervention bases

Rather than asking only which intervention distinguishes rival explanations, ask what is the smallest sufficient intervention family that separates the surviving equivalence classes.

This connects Goal Discovery to active experimental design, model discrimination, fault diagnosis, and information-efficient science.

## Critical competence transitions

Competence may sometimes collapse sharply rather than degrade smoothly.

Candidate signals near a boundary include slowing recovery, increasing variance, perturbation sensitivity, and shrinking route redundancy.

The discussion explicitly rejected claiming a phase transition without dense evidence.

## Temporal abstraction of competence

A lower-level competence can become a higher-level action primitive:

    micro actions
      -> reliable skill
      -> macro action

This provides a possible constructive mechanism for multiscale control.

## Meta-competence / self-diagnosis

A more advanced system may diagnose why it is failing.

Possible classes include sensor failure, actuator failure, structural unreachability, memory failure, resource depletion, and model mismatch.

Then:

    failure
      -> diagnosis
      -> targeted reconfiguration
      -> restored competence

This was considered a major step beyond ordinary robustness.

## Competence universality classes

Different substrates may share abstract failure architectures even when mechanisms differ.

Candidate classes include observation-limited, action-limited, barrier-limited, memory-limited, resource-limited, plasticity-limited, and diagnosis-limited.

The key requirement would be cross-system predictive transfer.

## Morphological and environmental computation

Some apparent controller intelligence may actually be implemented by body structure, morphology, or environmental regularities.

Moving the system boundary may change where the apparent computation resides.

## Early-warning signals

A useful extension of failure-boundary mapping would be to predict impending loss of recoverability before failure occurs.

Candidate signals include slower recovery, rising intervention cost, reduced route redundancy, increasing sensitivity, and increasing dependence on a bottleneck.

The result must be prospective, not retrospective curve fitting.

## Overall synthesis

Conversation trajectory:

    Deleuzian political philosophy
      -> critique of vague categories
      -> coarse-graining and causal boundaries
      -> dynamical systems and trajectory geometry
      -> Levin-style multiscale competency
      -> Hoel-style macro causal structure
      -> reachability / controllability / identifiability
      -> Collective Competence research questions

The most important conceptual shift was from who controls whom? to what causal structures shape the distribution of future trajectories, at what scale, and under what constraints?

The strongest scientific lesson is: philosophical vocabulary is useful when it generates a sharper hypothesis. Once the hypothesis is clear, use the most precise available language from control theory, dynamical systems, causal inference, cybernetics, or experimental design.

## Most promising research directions

- boundary discovery rather than boundary declaration;
- constraint-induced topology of competence;
- cross-scale competence conflict;
- competence composition;
- observability–controllability–policy failure decomposition;
- endogenous modification of problem/action space;
- requisite variety;
- minimal intervention bases;
- meta-competence and self-diagnosis;
- resource-bounded reachability;
- cross-system competence universality classes.

## Related notes

- [[00 Indexes/Conversation Map]]

## Related repositories

- BrianMills2718/collective-competence
- BrianMills2718/collective-competence/research/deleuze-trajectory-space.md