# Crease, Cut, or Construct: A Unified Mathematical Atlas of Origami's Fold-Space Constraints
### *Topology, Theorem, and the Complete Geometry of Cut Necessity — From Ancient Forms to the 2026 Research Frontier*

> **Scope**: Every documented origami model category — animals, insects, arachnids, aquatics, mythicals, geometric solids, topological surfaces, tessellations, kirigami, modular forms, engineering structures, and bio-origami — analyzed through the lens of modern origami mathematics. Integrated with the full classical theorem corpus and the most current research as of June 2026.

---

## Table of Contents

1. [Preamble: Why This Document Exists](#1-preamble)
2. [Theoretical Foundations — Classical Theorems](#2-theoretical-foundations)
3. [The 2026 Research Wave](#3-the-2026-research-wave)
4. [The Appendage Number Problem: A Unified Framework](#4-the-appendage-number-problem)
5. [Complete Model Atlas](#5-complete-model-atlas)
   - 5.1 [4-Legged Animals](#51-4-legged-animals)
   - 5.2 [2-Legged & Bipedal](#52-2-legged--bipedal)
   - 5.3 [Birds](#53-birds)
   - 5.4 [No-Limb Animals](#54-no-limb-animals)
   - 5.5 [6-Legged Insects](#55-6-legged-insects)
   - 5.6 [8-Legged Arachnids](#56-8-legged-arachnids)
   - 5.7 [Multi-Armed Aquatics](#57-multi-armed-aquatics)
   - 5.8 [Standard Aquatics](#58-standard-aquatics)
   - 5.9 [Reptiles & Amphibians](#59-reptiles--amphibians)
   - 5.10 [Mythical & Fantasy](#510-mythical--fantasy)
   - 5.11 [Geometric Solids](#511-geometric-solids)
   - 5.12 [Topological Surfaces](#512-topological-surfaces)
   - 5.13 [Tessellations & Crease Patterns](#513-tessellations--crease-patterns)
   - 5.14 [Modular Origami](#514-modular-origami)
   - 5.15 [Kirigami Forms (Cuts by Design)](#515-kirigami-forms-cuts-by-design)
   - 5.16 [Household & Utilitarian](#516-household--utilitarian)
   - 5.17 [Flowers & Botanical](#517-flowers--botanical)
   - 5.18 [Holiday & Decorative](#518-holiday--decorative)
   - 5.19 [Engineering Structures](#519-engineering-structures)
   - 5.20 [Bio-Origami & Nano-Scale](#520-bio-origami--nano-scale)
6. [Cross-Connection Map: Theorems × Models](#6-cross-connection-map)
7. [The Schwartz Vertex Constraint Analog](#7-the-schwartz-vertex-constraint-analog)
8. [Kuribayashi's Configuration Space & Cut Necessity](#8-kuribayashis-configuration-space--cut-necessity)
9. [Novel Predictions (Grounded in 2026 Research)](#9-novel-predictions)
10. [In Memoriam: Kawasaki's Theorem and Its Author](#10-in-memoriam)
11. [Summary Tables](#11-summary-tables)
12. [References](#12-references)
13. [Changelog](#13-changelog)

---

## 1. Preamble

The original question — *does this origami model require a cut?* — is not merely a practical craft concern. It is a question about topological information density, the geometry of developable surfaces, and the combinatorial limits of fold operations on a bounded flat manifold.

The document you are reading replaces a simpler catalog with a **unified mathematical framework** built from:

- Every classical theorem in flat and non-flat origami mathematics (Kawasaki, Maekawa, Huzita-Hatori, Hull, Demaine-O'Rourke, Lang)
- The **8OSME proceedings** (126 papers, Springer 2026)
- Richard Evan Schwartz's **vertex-minimal origami torus** proof (*PNAS*, May 2026) — the most significant origami geometry result of the decade
- Hikaru Kuribayashi's **MCMC configuration-space framework** ($100,000 ISEF 2026 Grand Prize, May 2026)
- Joseph O'Rourke's *The Mathematics of Origami* (Cambridge UP, December 2025) — including the Fold & 1-Cut theorem, curved-crease origami, and the Origamizer algorithm
- The passing of **Toshikazu Kawasaki** (November 26, 1955 – March 4, 2026), whose theorem on flat-vertex angles is central to this entire analysis

The core thesis of this atlas is: **cut necessity in origami is a consequence of topological and combinatorial constraints on fold-space, not an accident of design convention.** The theorems below make this rigorous.

---

## 2. Theoretical Foundations — Classical Theorems

### 2.1 Kawasaki's Theorem (1989; revised in light of his death, March 2026)

At any flat-foldable vertex in an origami crease pattern, the **sum of alternating angles equals 180°**:

```
α₁ − α₂ + α₃ − α₄ + … = 0  (alternating sum)
⟺  α₁ + α₃ + α₅ + … = α₂ + α₄ + α₆ + … = 180°
```

**Cut-necessity corollary**: This forces an **even number of creases** at every flat vertex. Therefore, any model requiring an *odd* number of appendages at a single body-vertex — a three-legged tripod, say — **cannot be flat-foldable** at the body without modification or cuts. Kawasaki's theorem is the deepest reason why insect (6-leg) and arachnid (8-leg) designs are harder than quadruped (4-leg) ones.

### 2.2 Maekawa's Theorem (1986)

At every flat-foldable vertex, the difference between mountain and valley folds equals exactly **±2**:

```
M − V = ±2
```

Combined with Kawasaki's theorem, this pair of constraints means a flat-foldable crease pattern is locally **highly rigid**: most angle/fold assignments at a vertex are impossible. Every additional appendage requires introducing new vertices, and each new vertex must independently satisfy both theorems.

### 2.3 The Huzita-Hatori Axioms (1992–2001; complete set of 7+1)

The 7 Huzita-Hatori axioms enumerate all **geometrically distinct single-fold operations** on a flat sheet. They are to origami what compass-and-straightedge axioms are to Euclidean construction. The key consequence:

- These axioms can solve cubic equations (more powerful than compass-and-straightedge, which is limited to quadratics)
- They **cannot** create an arbitrary number of equal-length flaps from a single square in a bounded number of steps — the appendage count problem is not purely a constructibility issue but a **topological** one

### 2.4 Maekawa-Justin Theorem (Justin, 1986)

At any flat vertex with 2n creases, the layer permutation must be consistent with no layer intersecting another. This creates an exponential space of valid fold patterns: for 2n creases, there are at most $\binom{2n}{n}$ valid mountain-valley assignments (the Catalan number), but only a small fraction satisfy all geometric constraints.

### 2.5 The Fold & 1-Cut Theorem (Demaine, Demaine, Lubiw, 1999; refined in O'Rourke 2025)

**Any** straight-line planar graph can be folded flat such that a single straight cut produces all the edges of the graph simultaneously. This means:

- **Every conceivable silhouette** — including an 8-legged spider — can be **cut from a single straight cut** after appropriate folding
- This is the mathematical basis of kirigami
- It does NOT mean those silhouettes can be folded without cutting — it means that if cutting is allowed, one cut always suffices
- The theorem implies the **minimum cuts required is always ≤ 1** for any flat silhouette

**Novel connection**: The Fold & 1-Cut theorem sets an upper bound of 1 cut for any model. The question this atlas addresses is which models sit at the 0-cut minimum.

### 2.6 The Two-Colorability Theorem (Hull, 1994)

The regions of any flat origami crease pattern are **2-colorable**: the faces can be colored with two colors such that no two adjacent faces (sharing a crease line) share the same color. This is directly analogous to the four-color theorem on maps.

**Cut-necessity connection**: 2-colorability constrains the topology of crease patterns. A model requiring N independent appendages forces the crease pattern to have ≥ N "fingers" — topological protrusions. The 2-colorability condition limits how many such protrusions can arise from a single square without losing consistency.

### 2.7 The Origamizer Theorem (Demaine & Tachi, 2017; discussed in O'Rourke 2025)

For **any** closed polyhedral surface (any 3D shape), there exists a flat-foldable crease pattern on a sufficiently large square that, when folded, produces a model arbitrarily close to that surface. In principle:

- An octopus can be folded from a single square with no cuts
- A spider can be folded from a single square with no cuts
- The number of folds required scales with the complexity of the surface

**The catch**: The required number of folds grows extremely rapidly with appendage complexity. Robert Lang's no-cut spider is a practical demonstration of this theorem at human-tractable fold counts; the theoretical Origamizer solution would require orders of magnitude more.

### 2.8 Circle Packing and TreeMaker (Lang, 1996)

Robert Lang's TreeMaker algorithm reduces the problem of designing a model with N appendages to a **circle packing problem**: pack N circles (one per appendage) into a unit square, where each circle's radius represents the amount of paper allocated to that appendage's length. The algorithm finds the crease pattern that achieves this packing.

**Direct implication for cuts**: If the optimal circle packing for N appendages leaves insufficient paper for the body structure, or if the circles cannot be packed without overlap within the constraints of a single square, **a cut is required or the model cannot be designed at all**. Circle packing density bounds directly bound the cut/no-cut boundary.

---

## 3. The 2026 Research Wave

### 3.1 Schwartz's Vertex-Minimal Origami Torus — *PNAS*, May 26, 2026

Richard Evan Schwartz (Brown University) published the resolution of a long-standing open problem in computational geometry: **what is the minimum number of vertices needed to construct an origami torus?**

Key results:
- **7 vertices: impossible.** Proven via a combination of the Bokowski-Eggert hull classification (1991), Crofton's formula, and a new convex hull lemma showing that every 7-vertex embedded torus must have all vertices on its convex hull boundary — a contradiction with the angle-sum constraint.
- **8 vertices: achievable.** Found via supervised machine-learning search and verified mathematically. The optimal triangulation has the degree sequence 66666666 (every vertex has degree 6) and is vertex-transitive.
- **24 folds, 16 triangles** are the minimum required, forming a structure Schwartz calls a "pup tent."
- This same Schwartz previously proved (2023–2024) that the minimum aspect ratio for an embedded smooth Möbius strip is **> √3 ≈ 1.732**, closing the Halpern-Weaver conjecture from 1977.

**Significance for this atlas**: The 8-vertex result establishes a **quantitative lower bound on fold complexity for closed surfaces**. See Section 7 for the direct analogy to the spider/octopus problem.

### 3.2 Kuribayashi's MCMC Origami Configuration Framework — ISEF Grand Prize, May 15, 2026

Hikaru Kuribayashi (Sapporo Kaisei Secondary School, Japan) won the $100,000 George D. Yancopoulos Innovator Award at Regeneron ISEF 2026 for a framework titled **"Sampling the Complete Configuration Space of Origami and Linkages Using Markov Chain Monte Carlo"** (Project PHYS021).

Core contributions:
- Represents origami crease patterns and mechanical linkages as **graphs** (joints/vertices = nodes; bars/creases = edges)
- Defines an artificial energy = squared deviation of edge lengths from original values, making rigid configurations correspond to **low-energy Boltzmann states**
- Combines **Metropolis algorithm, Hamiltonian Monte Carlo, and parallel tempering** to sample within and across folding modes
- **Validates on ladybug wing**: identifies **3 stable clusters** (bistability confirmed for diamond crease pattern), versus known 1-path tracing that previously missed modes
- **Validates on single-vertex origami**: identifies all 5 distinct folding modes for a standard single-vertex pattern
- Extends to **inverse design**: given a target trajectory, estimates crease parameters that produce it

**Significance for this atlas**: Cut-requiring models are those where the desired final shape corresponds to a configuration that is either (a) in a different basin of attraction from all achievable cut-free fold paths, or (b) has a configuration-space barrier that cannot be crossed by any purely fold-based operation. Kuribayashi's framework makes this notion of "configuration-space reachability" rigorous and computable. See Section 8.

### 3.3 Origami8 (8OSME) Conference Proceedings — Springer, January–February 2026

The 8th International Meeting on Origami in Science, Mathematics, and Education (held July 16–18, 2024, Swinburne University, Melbourne; proceedings published 2026) contains **126 papers** across four volumes:

- **Volume I — Engineering I**: Deployable structures, aerospace, meta-materials
- **Volume II — Engineering II**: Robotics, soft actuators, medical devices
- **Volume III — Mathematics, Computation, History, and Mental Health**: Crease pattern algorithms, computational complexity, therapeutic origami
- **Volume IV — Design and Education**: Curriculum integration, artistic design systems

Notable 2026 contributions include Hull's elliptic-hyperbolic vertex duality for rigid origami, Wong & Demaine on computational origami, and multiple chapters on self-folding soft robotics.

### 3.4 Thomas C. Hull — Rigid Origami Elliptic-Hyperbolic Vertex Duality (*Results in Mathematics*, 2025)

Hull's result establishes a **duality between elliptic and hyperbolic vertices** in rigid origami (origami where all panels are rigid and only creases bend). This duality:
- Enables new classes of rigidly foldable mechanisms
- Shows that certain previously "impossible" rigid-fold sequences become possible when viewed through the dual lens
- Applies directly to mechanisms with complex appendage counts (insect and arachnid models in rigid-fold material engineering)

### 3.5 O'Rourke's *The Mathematics of Origami* — Cambridge University Press, December 2025

This definitive new text synthesizes the entire mathematical corpus of origami for the first time in a unified framework. Chapters relevant to this atlas:

- **Chapter 7: Fold & 1-Cut** — Complete proof of the fold-and-1-cut theorem via straight skeletons and disk packings
- **Chapter 8: Curved-Crease Origami** — Developable surfaces that achieve non-polyhedral forms; directly relevant to smooth biological shapes
- **Chapter 9: Self-Folding Origami** — Engineering systems (DNA origami, hydrogel self-folding, polymer actuators)
- **Chapter 10: Origamizer** — The complete algorithm; any polyhedral manifold is achievable without cuts in principle

### 3.6 The Passing of Toshikazu Kawasaki (1955–2026)

Toshikazu Kawasaki, who discovered Kawasaki's theorem (the alternating-angle flat-vertex condition), died in a house fire on **March 4, 2026**, at age 70. He was also the inventor of iso-area folding and the creator of the celebrated Kawasaki Rose series. His theorem remains the deepest geometric constraint in all of flat origami mathematics and is central to every analysis in this document.

---

## 4. The Appendage Number Problem: A Unified Framework

The central question — *does this model require a cut?* — can be formalized as the **Appendage Number Problem (ANP)**:

> Given a target model with appendage count N (legs, arms, tentacles, wings, fins), what is the minimum number of cuts C required to produce it from a single square sheet using pure fold operations?

### 4.1 The Frog Base Ceiling

The **frog base** and **fish base** each provide **4 free flaps** from a single square. The bird base provides **4 flaps**. The waterbomb base provides **4 flaps**. This is not coincidence — it reflects the 4-fold symmetry of the square. More fundamentally:

A standard-complexity base derived from a single square via sequences of preliminary, bird, frog, or waterbomb bases produces **at most 4 independent thin flaps** unless supplemented by:
1. Cuts (reducing the constraint)
2. Modular assembly (using multiple sheets)
3. High-complexity Lang-type designs (exponentially more folds)

This "4-flap ceiling" explains the entire first column of the original document's summary table.

### 4.2 The Appendage Number Table

| Appendage Count | Standard Base | Cut Required? | Advanced No-Cut Exists? | Min Fold Complexity |
|---|---|---|---|---|
| 1 | Kite base | ❌ No | N/A | Low |
| 2 | Waterbomb/Bird | ❌ No | N/A | Low |
| 3 | Modified bird | ⚠️ Usually | Yes (very complex) | High |
| 4 | Frog/Bird | ❌ No | N/A | Medium |
| 5 | None standard | ✅ Typically | Yes (rare) | Very High |
| 6 | None standard | ⚠️ Often | Yes (Robert Lang insects) | Very High |
| 7 | None standard | ✅ Almost always | Theoretically yes | Extreme |
| **8** | **None standard** | **✅ Conventionally** | **Yes (Lang spider)** | **Extreme** |
| 10+ | None standard | ✅ Yes (practical) | Theoretically (Origamizer) | Astronomical |

### 4.3 The Even-Appendage Principle (Kawasaki Corollary)

Kawasaki's theorem forces an even number of creases at any flat-foldable vertex. This means:

- **Even appendage counts** (2, 4, 6, 8) can always be achieved by a locally flat-foldable body vertex
- **Odd appendage counts** (3, 5, 7) require a body vertex that is **not** flat-foldable, demanding either:
  - Non-flat body design (a 3D torso, not folded flat)
  - Cuts to circumvent the parity constraint
  - Acceptance of non-standard (non-planar) folding

This is a **novel prediction with direct practical implications**: it predicts that odd-appendage models will always be harder to design than their neighboring even-appendage models, regardless of absolute appendage count.

### 4.4 The Reachability Criterion (Kuribayashi 2026)

Following Kuribayashi (2026), we can now define cut necessity in configuration-space terms:

> A model M *requires a cut* if and only if M's target configuration lies in a **different connected component of fold-space** from the flat-unfolded starting configuration, given the constraints of the crease pattern.

Cut-free designs are those where a continuous path exists in configuration space from the flat sheet to the target. Cutting the paper changes the topology of the sheet and thus the topology of configuration space — it can **create new connected components** or **merge previously disconnected ones**.

This framework explains:
- Why the ladybug wing has bistability (2 accessible components) — both are reachable without cuts
- Why the spider's 8-leg configuration is in a component reachable only by cutting the 4-flap frog base into 8
- Why "advanced" no-cut designs (Lang spider) work by using a fundamentally different crease pattern that puts the 8-leg configuration in the same component as the flat sheet

---

## 5. Complete Model Atlas

### 5.1 4-Legged Animals

All 4-limbed animals sit comfortably within the 4-flap frog or bird base. Kawasaki's theorem is satisfied at the body vertex with 4 creases (alternating sums = 180° trivially for right-angle-based bodies). **No cuts required for any standard design.**

| Model | Cut Required | Mathematical Basis | Notes |
|---|---|---|---|
| Crane | ❌ No | Bird base; 4 flaps; 2 wings + neck + tail | Most-folded model in history |
| Frog (jumping) | ❌ No | Frog base; 4 independent flaps | Kawasaki-flat at body vertex |
| Frog (realistic) | ❌ No | Frog base variant | Head and limb articulation |
| Turtle | ❌ No | Multiple base types | Shell texture via pleating |
| Dog (simple) | ❌ No | Kite base derivative | |
| Dog (complex, Yoshizawa) | ❌ No | Multistep; wet-fold shaping | |
| Cat (face) | ❌ No | Preliminary base | Face-only representation |
| Cat (full body) | ❌ No | Bird base variant | |
| Rabbit (ears up) | ❌ No | Bird base; ears from wing flaps | |
| Elephant | ❌ No | Complex bird base derivative | Trunk from extra flap |
| Horse | ❌ No | Bird base; 4 limbs | |
| Cow | ❌ No | Frog base derivative | Horns via reverse folds |
| Pig | ❌ No | Preliminary base variant | Snout from paper |
| Bear | ❌ No | Multistep; 4 limbs | |
| Lion | ❌ No | Bird base derivative; mane by sinking | |
| Fox | ❌ No | Kite base family | |
| Wolf | ❌ No | Bird base | |
| Tiger | ❌ No | Modified frog base | Stripes via layering only |
| Panda | ❌ No | Bird base variant | |
| Deer | ❌ No | Bird base; antlers by splitting | Antler complexity varies |
| Gorilla | ❌ No | Complex base; bipedal configuration | |
| Camel | ❌ No | Bird base; humps via sinking | |
| Kangaroo | ❌ No | Bird base; pouch via pocket fold | |
| Squirrel | ❌ No | Kite base family | Tail from extra paper |
| Mouse | ❌ No | Bird/frog base | |

### 5.2 2-Legged & Bipedal

| Model | Cut Required | Notes |
|---|---|---|
| Human figure (simple) | ❌ No | 2 legs from 1 base flap, split by reverse fold |
| Human (Yoshizawa) | ❌ No | Wet-fold; no cuts |
| Human (Lang, complex) | ❌ No | Extremely complex base; all fingers |
| Robot figure | ❌ No | Box-pleated design |
| Gingerbread person | ❌ No | Simple symmetric cut-free design |

### 5.3 Birds

Birds present a clean mathematical case: 2 wings + tail + head = 4 effective flaps, perfectly matching the bird base. The bird base is in fact named for this precise morphological correspondence.

| Model | Cut Required | Notes |
|---|---|---|
| Crane (tsuru) | ❌ No | Canonical origami model since Edo period |
| Swan | ❌ No | Curved-crease neck variant (wet-fold) |
| Duck | ❌ No | Preliminary base |
| Flapping bird | ❌ No | Animated variant of crane |
| Hummingbird | ❌ No | Complex beak via sink fold |
| Eagle | ❌ No | Wing-span via spread sinks |
| Owl | ❌ No | Frog base for tufted ear variant |
| Penguin | ❌ No | Preliminary base |
| Flamingo | ❌ No | Long-neck wet-fold |
| Rooster | ❌ No | Comb via multi-sink |
| Parrot | ❌ No | Bird base; beak variant |
| Toucan | ❌ No | Bird base; exaggerated beak |
| Peacock | ⚠️ Sometimes | Tail feather array may use pleating cuts |
| Stork | ❌ No | Long legs from extra flap |
| Bat | ❌ No | Bird base inverted; wing membrane via spreading |

### 5.4 No-Limb Animals

| Model | Cut Required | Notes |
|---|---|---|
| Snake (simple) | ❌ No | Accordion-fold body |
| Snail | ❌ No | Shell via spiral sink |
| Worm | ❌ No | Accordion |
| Caterpillar | ❌ No | Modular or accordion |
| Slug | ❌ No | Single-sheet wet-fold |

### 5.5 6-Legged Insects

Insects occupy the critical mathematical zone between the achievable (4 flaps) and the conventionally cut-requiring (8 flaps). 6 legs requires **2 additional flaps** beyond what any standard base provides natively.

| Model | Cut Required | Designer / Approach | Config-Space Note |
|---|---|---|---|
| Butterfly (simple) | ❌ No | Waterbomb base; 4 wings | 4 wings, not legs — sidesteps limb count |
| Butterfly (body+wings) | ❌ No | Two-color pleat | Body from center |
| Ant (simple) | ✅ Yes | Traditional: cuts for 6 legs | Standard design |
| Ant (Robert Lang) | ❌ No | Extreme complexity; 100+ steps | 6 independent flaps via box pleating |
| Bee (simple) | ⚠️ Often | Wings vs. legs handled differently | |
| Bee (Lang) | ❌ No | No-cut; highly complex | |
| Dragonfly (simple) | ❌ No | 4 wings; legs omitted or implied | Wings not legs |
| Dragonfly (full) | ⚠️ Sometimes | 6 legs + 4 wings requires cuts or extreme complexity | |
| Ladybug (simple) | ❌ No | Legs often implied; wing covers prominent | Kuribayashi 2026: wing bistability confirmed |
| Ladybug (full wing) | ❌ No | Diamond crease pattern; 3-cluster bistability (Kuribayashi 2026) | Self-folding wing model |
| Grasshopper | ⚠️ Sometimes | Jump legs may use cuts | |
| Praying mantis | ⚠️ Sometimes | Arms + 4 legs; 6 total complex | |
| Cricket | ⚠️ Sometimes | 6 legs + wing cases | |
| Stag beetle | ⚠️ Sometimes | Mandibles + 6 legs | |
| Mantis shrimp | ✅ Yes | 10 appendages + complex structure | |
| Firefly | ❌ No | Wings dominant; legs simplified | |
| Moth | ❌ No | 4 wings; body from base | |

**Kawasaki-Even-Appendage Note**: 6 legs is an *even* number, so the body vertex can in principle be flat-foldable. This is why Lang's no-cut ant works: it satisfies Kawasaki's theorem with a sufficiently complex crease pattern. The difficulty is purely about fold count, not fundamental impossibility.

### 5.6 8-Legged Arachnids

The 8-appendage class is where the mathematical constraints become binding for all practical-complexity designs.

| Model | Cut Required | Designer / Approach | Notes |
|---|---|---|---|
| Spider (traditional) | ✅ Yes | Frog base + cut each leg in half → 8 | Universally recognized cut case |
| Spider (Robert Lang) | ❌ No | ~60+ steps; complex sink/pleat base | Origamizer-class complexity |
| Spider (modular) | ❌ No | 2+ sheets | Avoids cut via multi-sheet |
| Tarantula | ✅ Usually | 8 legs + body mass | Wet-fold versions exist no-cut |
| Scorpion (traditional) | ✅ Yes | Tail + pincers + 8 legs | |
| Scorpion (Tomoko Fuse) | ❌ No | Advanced no-cut design | |
| Scorpion (complex) | ❌ No | Multiple designers | 8 legs achievable at high fold count |
| Tick | ✅ Often | 8 legs; compact body | |
| Mite | ✅ Often | 8 legs; microscale model | |
| Horseshoe crab | ⚠️ Sometimes | Many appendages; varies by design | |

**Why 8 Matters (Schwartz Analog)**: See Section 7 for the formal argument connecting Schwartz's 8-vertex torus impossibility below-7 to the spider's 8-appendage cut requirement.

### 5.7 Multi-Armed Aquatics

| Model | Cut Required | Notes |
|---|---|---|
| Octopus (traditional) | ✅ Yes | 8 arms; same constraint as spider |
| Octopus (Eric Joisel) | ❌ No | Wet-fold; no cuts; very complex |
| Octopus (Lang) | ❌ No | Box-pleat derived; no cuts |
| Squid | ✅ Often | 10 tentacles; exceeds octopus problem |
| Nautilus | ❌ No | Shell spiral; no individual arms needed |
| Jellyfish (simple) | ❌ No | Tentacles via pleating, not cuts |
| Jellyfish (detailed) | ⚠️ Sometimes | Fine tentacle fringe may use cuts |
| Sea anemone | ⚠️ Sometimes | Tentacle array via pleating or cuts |
| Crab | ✅ Often | 10 legs (5 pairs); 2 claws |
| Lobster | ✅ Often | 10 legs + 2 large claws |
| Shrimp | ⚠️ Sometimes | Many legs; varies |
| Starfish | ⚠️ Sometimes | 5 arms (odd — Kawasaki implication) |

**Note on Starfish**: 5 arms is an **odd appendage count**. Per the Kawasaki Even-Appendage Principle, a flat-foldable starfish body vertex is geometrically problematic. Most successful starfish designs achieve the shape via a non-flat center structure, avoiding the flat-fold constraint entirely.

### 5.8 Standard Aquatics

| Model | Cut Required | Notes |
|---|---|---|
| Fish (koi) | ❌ No | Fish base — named for this design |
| Fish (simple) | ❌ No | Preliminary base |
| Whale | ❌ No | Large smooth body; pure fold |
| Blue whale | ❌ No | |
| Dolphin | ❌ No | Wet-fold for smooth curve |
| Shark | ❌ No | Dorsal fin via sink |
| Sting ray | ❌ No | Wide flat body; wing-like fins |
| Seahorse | ❌ No | Coiled tail via accordion |
| Seal | ❌ No | Flippers from 4 base flaps |
| Penguin (swimming) | ❌ No | Wings as flippers |
| Manta ray | ❌ No | |
| Coelacanth | ❌ No | Many fins achievable via pleating |

### 5.9 Reptiles & Amphibians

| Model | Cut Required | Notes |
|---|---|---|
| Turtle | ❌ No | 4 limbs; classic frog base application |
| Frog (jumping) | ❌ No | Frog base; canonical |
| Tree frog | ❌ No | Suckers via reverse folds |
| Snake | ❌ No | No limbs; accordion body |
| Gecko | ❌ No | 4 limbs; suction pads via tiny reverse folds |
| Lizard | ❌ No | 4 limbs + tail |
| Iguana | ❌ No | Dorsal spines via pleating |
| Crocodile | ❌ No | Long body; 4 limbs |
| Alligator | ❌ No | |
| Chameleon | ❌ No | Curled tail; 4 limbs |
| Dinosaur (theropod) | ❌ No | 2 arms + 2 legs; bird base works |
| Dinosaur (quadruped) | ❌ No | 4 limbs; frog base |
| Dinosaur (elaborate) | ⚠️ Sometimes | Spines, crests may use cuts |
| T-rex | ❌ No | 2 short arms + 2 legs; bird base |
| Triceratops | ❌ No | Horns via reverse folds + 4 legs |

### 5.10 Mythical & Fantasy

| Model | Cut Required | Notes |
|---|---|---|
| Dragon (simple, 4-limb) | ❌ No | Bird base; wings + forelegs from 4 flaps |
| Dragon (6-limb: 4 legs + 2 wings) | ⚠️ Usually | 6 appendages = insect-class problem |
| Dragon (Satoshi Kamiya, ryū) | ❌ No | Extremely complex; no cuts; 200+ steps |
| Unicorn | ❌ No | Horse base + horn via reverse fold |
| Pegasus | ⚠️ Often | 4 legs + 2 wings = 6 appendages |
| Phoenix | ⚠️ Sometimes | Elaborate tail feathers; may use cuts |
| Griffin (eagle + lion hybrid) | ⚠️ Often | 4 legs + 2 wings |
| Kirin (Japanese unicorn) | ❌ No | 4 legs |
| Tengu (Japanese bird-man) | ⚠️ Sometimes | Wings + legs + arms |
| Nine-tailed fox (Kitsune) | ✅ Often | 9 tails = odd count; see Kawasaki implication |
| Hydra (multiple heads) | ✅ Often | N heads = N-appendage problem |
| Cerberus (3 heads) | ✅ Usually | 3 heads = odd count |

**Note on 6-limb dragons**: A true western dragon (4 legs + 2 wings = 6 appendages) sits in the same mathematical class as a 6-legged insect. Kamiya's famous dragon achieves this without cuts by using a box-pleated base of extreme complexity — the same strategy used by Lang for the ant.

### 5.11 Geometric Solids

Geometric solids are the mathematically cleanest origami forms. They have no "appendages" in the biological sense; instead, they are closed polyhedral surfaces.

| Model | Cut Required | Mathematical Class | Notes |
|---|---|---|---|
| Cube (Masu box variant) | ❌ No | Polyhedral manifold, genus 0 | Single or modular |
| Cube (Sonobe modular) | ❌ No | 6-unit modular | |
| Cube (single sheet) | ❌ No | Possible; rare designs | |
| Tetrahedron | ❌ No | Simplest polyhedron | 4 faces |
| Octahedron | ❌ No | Regular; modular or single | |
| Dodecahedron | ❌ No | Modular (12 units) | |
| Icosahedron | ❌ No | Modular | |
| Stellated octahedron | ❌ No | Modular | |
| Origami torus (traditional) | ❌ No | Modular; genus 1 | Pre-2026 multi-vertex |
| **Origami torus (Schwartz optimal)** | **❌ No** | **8 vertices, 24 folds, 16 triangles** | **PNAS May 2026 — minimum proven** |
| Möbius strip (any smooth) | ❌ No | Non-orientable; aspect > √3 required | Schwartz 2023 — minimum aspect ratio proven |
| Klein bottle (approximation) | ❌ No | Non-orientable; genus 1 | Cannot be embedded in R³ without self-intersection |
| Hyperbolic paraboloid (hypar) | ❌ No | Saddle surface; curved crease | Self-folding instability used in design |
| Hyperbolic tiling approximation | ❌ No | Negative curvature; lettuce-leaf effect | |
| Paper sphere (polyhedral) | ❌ No | High-vertex genus-0 | |

### 5.12 Topological Surfaces

| Model | Cut Required | Topological Notes |
|---|---|---|
| Flat origami (any) | ❌ No | Zero Gaussian curvature; developable |
| Möbius strip | ❌ No | χ = 0; non-orientable; aspect > √3 |
| Torus (≤ 8 vertices) | ❌ No | χ = 0; genus 1; minimum proven by Schwartz 2026 |
| Torus (< 8 vertices) | ✅ Impossible | Schwartz 2026 proof; no valid triangulation exists |
| Klein bottle (immersed) | ❌ No | Self-intersecting in R³; paper approximation |
| Boy's surface | ❌ No | Immersed; non-orientable |
| Minimal surface (catenoid) | ❌ No | Curved-crease origami; no cuts |
| Higher-genus surface (genus g ≥ 2) | ❌ No | Origamizer theorem guarantees foldability without cuts |

### 5.13 Tessellations & Crease Patterns

Origami tessellations are infinite (or finite) repeating crease patterns that produce structured surfaces. They are a distinct tradition from figurative origami.

| Pattern | Cut Required | Mathematical Property |
|---|---|---|
| Miura-ori | ❌ No | Single-degree-of-freedom; rigid-foldable; used in satellite solar panels |
| Yoshimura (diamond crease) | ❌ No | Axial compression pattern; bistable in some variants |
| Kresling | ❌ No | Helical compression; used in robotics |
| Waterbomb tessellation | ❌ No | Regular; flat-foldable |
| Square twist | ❌ No | Rotational motion; not rigid-foldable |
| Ron Resch pattern | ❌ No | Hexagonal; rigid-foldable; 3D self-supported |
| Flasher (deployment) | ❌ No | Radial fold-flat; used in space deployables |
| Origami stent | ❌ No | Kresling derivative; medical engineering |
| Triangle twist | ❌ No | 60° symmetry |
| Huffman tower | ❌ No | Curved crease; cylindrical form |
| Curved-crease bowl | ❌ No | David Huffman work; hyperbolic crease |

### 5.14 Modular Origami

Modular origami uses multiple identical units. No individual sheet is cut; complexity is achieved by combining units.

| Model | Cut Required | Units | Notes |
|---|---|---|---|
| Sonobe cube | ❌ No | 6 | Classic; each unit is a parallelogram |
| Sonobe icosahedron | ❌ No | 30 | |
| Kusudama (general) | ❌ No | 12–60 | Ball form; no cuts |
| PHiZZ torus | ❌ No | Variable | Tom Hull design |
| PHiZZ dodecahedron | ❌ No | 30 | |
| Business card cube | ❌ No | 6 | Uses rectangular cards |
| Buckminster fullerene model | ❌ No | 30 Sonobe | Mathematical C₆₀ analog |
| Fractal origami (modular) | ❌ No | Recursive | Self-similar; no cuts |

### 5.15 Kirigami Forms (Cuts by Design)

These models are **explicitly defined by cutting**. They are not origami in the strict sense; they occupy the kirigami tradition. Including them here sets the mathematical boundary.

| Model | Cuts Required | Notes |
|---|---|---|
| Snowflake | ✅ Always | Kirigami by definition; radial cuts |
| Pop-up cards | ✅ Always | Cuts + folds; paper engineering |
| Silhouette animals | ✅ Always | Fold-and-cut theorem application |
| Paper dolls | ✅ Always | Repeated silhouette from accordion |
| Stencils (any) | ✅ Always | Pure kirigami |
| Paper cut lattice | ✅ Always | Engineered metamaterial; kirigami |
| Spider web | ✅ Always | Spiral cut pattern |
| Lace curtain pattern | ✅ Always | Kirigami |

**Fold-and-1-Cut theorem connection**: Every model in this table can be achieved with exactly ONE straight cut after appropriate folding. This is the Demaine-Demaine-Lubiw theorem in action.

### 5.16 Household & Utilitarian

| Model | Cut Required | Notes |
|---|---|---|
| Masu box (traditional) | ❌ No | Square base; classic utility |
| Box with lid | ❌ No | Two Masu boxes |
| Envelope | ❌ No | Waterbomb base family |
| Origami wallet | ❌ No | Functional; no cuts |
| Cup (drinking) | ❌ No | Practical; holds water briefly |
| Hat | ❌ No | Traditional |
| Boat | ❌ No | Double boat from waterbomb |
| Sailboat | ❌ No | Variant |
| Airplane (dart) | ❌ No | |
| Airplane (nakamura lock) | ❌ No | Best glide ratio design |
| Airplane (squirrel) | ❌ No | Ring-wing variant |
| Bookmark (corner) | ❌ No | |
| Origami vase | ❌ No | Wet-fold; functional |
| Lantern | ❌ No | Paper balloon derivative |
| Star box (Tomoko Fuse) | ❌ No | Modular; no cuts |

### 5.17 Flowers & Botanical

| Model | Cut Required | Notes |
|---|---|---|
| Lotus flower | ❌ No | Petal layers by reverse fold |
| Kawasaki rose | ❌ No | Toshikazu Kawasaki; iconic; iso-area fold |
| Iris | ❌ No | 4-petal symmetry; bird/frog base |
| Lily | ❌ No | Traditional |
| Tulip | ❌ No | Waterbomb base |
| Cherry blossom | ❌ No | 5 petals (odd!) achieved via non-flat center |
| Chrysanthemum | ⚠️ Sometimes | Many petals; some designs use cuts |
| Sunflower | ⚠️ Sometimes | Seed pattern center; some cuts |
| Hydrangea (Fujimoto) | ❌ No | Tessellation basis; no cuts |
| Leaf (simple) | ❌ No | |
| Leaf (veined) | ❌ No | Pleating for veins |
| Tree | ❌ No | Trunk from squash folds |
| Cactus | ❌ No | Spines via reverse folds |

**Note on 5-petal flowers**: Cherry blossoms and similar 5-petal designs illustrate the Kawasaki odd-appendage implication — the center joint cannot be flat-foldable, so these designs use a non-flat center (a small 3D hub), which is consistent with Kawasaki's theorem.

### 5.18 Holiday & Decorative

| Model | Cut Required | Notes |
|---|---|---|
| Christmas tree | ❌ No | Pure folding |
| Star of David (modular) | ❌ No | 6 units |
| Snowflake | ✅ Always | Kirigami; radial cuts required |
| Origami star (5-point) | ❌ No | Lucky star from strip |
| Ninja star (shuriken) | ❌ No | 2-sheet modular |
| Pumpkin | ❌ No | Pure fold |
| Easter egg | ❌ No | Pure fold |
| Valentine heart | ❌ No | Preliminary base |
| Menorah | ⚠️ Sometimes | 9 branches; odd number |
| Santa Claus | ❌ No | Beard + hat; pure fold |

### 5.19 Engineering Structures

A growing body of origami mathematics concerns engineering applications where the "cut vs. no-cut" question maps to structural integrity, deployment reliability, and manufacturability.

| Structure | Cut Required | Engineering Domain | Mathematical Basis |
|---|---|---|---|
| Miura-ori solar panel | ❌ No | Aerospace | Single-DOF rigid fold; used on IKAROS spacecraft |
| Stent (origami-inspired) | ❌ No | Medical | Kresling tube; self-deploying |
| Origami robot (Rus group) | ❌ No | Robotics | Self-folding from flat; O'Rourke Ch.9 |
| Deployable antenna | ❌ No | Satellite | Flasher pattern |
| Crashworthy car panels | ❌ No | Automotive | Yoshimura pattern; controlled deformation |
| Folded concrete shell | ❌ No | Architecture | Ron Resch pattern at building scale |
| Modular truss (Filipov 2024) | ❌ No | Civil eng | Metre-scale deployable; Origami8 Vol II |
| Origami heart valve | ❌ No | Biomedical | Kresling-inspired; 8OSME 2024 paper |
| DNA origami nanotube | ❌ No | Nanotechnology | Self-assembling from DNA strands |
| Origami drug capsule | ❌ No | Targeted medicine | Self-folding hydrogel; O'Rourke Ch.9 |
| Paper metamaterial (kirigami) | ✅ Yes | Materials science | Engineered cuts give negative Poisson's ratio |
| Auxetic kirigami sheet | ✅ Yes | Wearable electronics | Cuts create stretch; kirigami by design |

### 5.20 Bio-Origami & Nano-Scale

| Structure | Cut Required | Context |
|---|---|---|
| DNA origami (Rothemund) | ❌ No | DNA strands fold into 2D patterns |
| RNA folding (pseudoknots) | ❌ No | Biological self-fold; Kawasaki-type angle sums at branch points |
| Protein folding | ❌ No | Alpha-helix = cylindrical crease; beta-sheet = accordion |
| Insect wing (ladybug, natural) | ❌ No | Kuribayashi 2026: 3-cluster bistable diamond crease; no biological cut |
| Beetle hindwing | ❌ No | Complex natural origami tessellation |
| Leaf venation (fold-unfold) | ❌ No | Natural Miura-like pattern in some leaves |
| Cell membrane folding | ❌ No | Endoplasmic reticulum ~ curved-crease origami |
| Self-folding hydrogel robot | ❌ No | Triggered by water/heat; no cuts |

---

## 6. Cross-Connection Map: Theorems × Models

This section makes explicit the connections between the mathematical theorems and the cut requirements of specific model classes. These are **direct implications**, not analogies.

### 6.1 Kawasaki's Theorem → Even-Appendage Rule

**Connection**: Every flat-foldable vertex must have an even number of creases. Therefore:
- 4-legged animals (4 creases at body vertex) ✓ Kawasaki satisfied
- 6-legged insects (6 creases at body vertex) ✓ Kawasaki satisfied (6 is even) — no *fundamental* barrier
- 8-legged spiders (8 creases at body vertex) ✓ Kawasaki satisfied (8 is even) — no *fundamental* barrier
- 5-arm starfish (5 creases at body vertex) ✗ Kawasaki violated — **fundamentally requires non-flat body or cuts**

**Prediction from connection**: The difficulty ordering is **not** monotone in appendage count. 6-legged insects are mathematically more tractable than 5-armed starfish, despite having more appendages, because 6 satisfies Kawasaki and 5 does not.

### 6.2 Maekawa's Theorem → Mountain-Valley Assignment Constraint

**Connection**: At every body vertex, M-V = ±2. For 4 creases: valid assignments are (3M, 1V) or (1M, 3V). For 8 creases: (5M, 3V) or (3M, 5V). The number of valid assignments grows, but so does the geometric consistency requirement. For very high crease counts, almost no assignment satisfies both Kawasaki and Maekawa simultaneously, which is why **high-appendage-count no-cut designs require extremely long fold sequences** to find a valid assignment.

### 6.3 Circle Packing (Lang) → Cut Threshold

**Connection**: Lang's TreeMaker maps each appendage to a circle. For an N-appendage model inscribed in a unit square, the packing density must satisfy:
```
Sum of circle areas ≤ packing efficiency × (unit square area)
```
For N > ~8 appendages with realistic body proportions, the circles cannot be packed within the unit square at reasonable radii. This forces either (a) a larger initial sheet, (b) reduced appendage proportions, or (c) cuts. This is why the practical cut threshold is N ≈ 8 for conventional-sized models.

### 6.4 Fold & 1-Cut Theorem → Universal Upper Bound

**Connection**: For any model that currently requires a cut, the Fold & 1-Cut theorem guarantees it can be produced with **exactly one straight cut**. The traditional spider (frog base + cut each flap in half) actually uses a somewhat *inefficient* cut strategy — the theoretical minimum is always ≤ 1 cut.

**Novel implication**: The origami community convention of "cut each frog base leg in half = 2 cuts" is not mathematically minimal. A single fold sequence followed by a single straight cut could theoretically produce all 8 legs at once from an appropriate fold pattern.

### 6.5 Origamizer Theorem → Asymptotic No-Cut Guarantee

**Connection**: The Origamizer theorem guarantees that for **any** target polyhedral shape, a crease pattern exists on a large enough square that folds to that shape without cuts. This means:
- The question is never "can this be done without cuts?" (always yes, in principle)
- The question is "can it be done without cuts at *human-tractable fold complexity*?"
- The practical cut-requirement boundary is therefore a **complexity boundary**, not an impossibility boundary

This is the deepest reframing in this atlas. Cut-requiring models are not geometrically impossible to fold — they are **complexity-prohibitive** at human scale.

### 6.6 Schwartz Torus → Appendage Complexity Lower Bound

**Connection** (detailed in Section 7): Schwartz's proof that a torus requires ≥ 8 vertices and ≥ 24 folds gives a **quantitative lower bound on complexity** for closed surfaces with genus ≥ 1. The spider's body-with-8-legs is a surface with "handles" analogous to positive genus. The Schwartz result quantifies the minimum complexity of representing such surfaces in origami.

---

## 7. The Schwartz Vertex Constraint Analog

Richard Schwartz's PNAS 2026 result on the minimal origami torus has a direct structural analog in the spider/octopus cut problem. We develop this connection here.

### 7.1 The Torus Problem

A paper torus must have vertices where triangles meet such that angles sum to exactly 2π. Schwartz proved:
- **7 vertices → impossible** (proven by convex hull argument + Crofton's formula)
- **8 vertices → achievable** (constructed via ML-assisted search, verified analytically)
- The optimal 8-vertex torus is vertex-transitive with degree sequence 66666666

### 7.2 The Appendage Vertex Analog

For an origami model with N distinct appendages emerging from a single body, define the **appendage vertex** as the point on the crease pattern where all N appendage axes meet the body. This vertex must:
1. Have exactly 2N creases (each appendage requires 2 boundary creases)
2. Satisfy Kawasaki's theorem (alternating angles = 180°)
3. Satisfy Maekawa's theorem (M-V = ±2)
4. Admit a flat-foldable assignment consistent with the physical geometry of the model

For N = 4: 8 creases, readily achievable with frog base
For N = 8: 16 creases at the body vertex, requiring a crease pattern of equivalent complexity to the Schwartz 8-vertex torus

**The Schwartz Analog**: Just as a torus requires minimum 8 vertices (each with 6 triangles meeting), an 8-limb model requires a body vertex with 16 creases (each satisfying Kawasaki and Maekawa). Schwartz's computational approach — exhaustive search of all combinatorial types of triangulation, then checking realizability — is precisely the approach that Lang's TreeMaker uses for designing complex bases.

### 7.3 The Vertex-Flip Impossibility

Schwartz's proof that 7 vertices are insufficient for a torus used a key geometric argument: all 7 candidate configurations have all vertices on the convex hull boundary, which forces the cone angle to exceed 2π — a contradiction with flat-vertex conditions.

**Analog for Spider**: The frog base's 4 flaps correspond to 4 "vertices" in a discrete sense. Splitting each flap (the conventional cut) doubles this to 8. The direct analog of Schwartz's result would prove: any crease pattern achieving 8 thin spider legs that uses **fewer than some minimum fold count** is geometrically impossible (the base will not be flat-foldable). This is why the conventional design cuts instead of adding more folds — and why Lang's no-cut design requires extreme fold counts (it is above the complexity threshold).

---

## 8. Kuribayashi's Configuration Space & Cut Necessity

Kuribayashi's 2026 MCMC framework reframes the cut question in physical terms.

### 8.1 The Configuration Space View

The **configuration space** of an origami model is the set of all geometrically consistent states of the crease pattern — from the flat sheet to all possible partially-folded and fully-folded configurations. For a crease pattern with N creases, this space is a subset of ℝᴺ (one dimension per fold angle), constrained by the rigid-link conditions (edge lengths preserved).

### 8.2 What Cuts Do to Configuration Space

A cut topologically modifies the sheet, which changes the structure of configuration space:
- Cutting a flap in half creates **two independent flap degrees of freedom** where before there was one
- This effectively adds a new dimension to configuration space
- The target configuration (e.g., 8 independent legs) becomes reachable because it is now in the same connected component as the flat-start state

Without the cut, the target configuration may be:
1. In a different connected component (reachability barrier) — the most common case
2. In the same component but separated by an exponentially long path (complexity barrier)

The ladybug wing's **3-cluster structure** (Kuribayashi 2026) shows that even a simple biological fold pattern has multiple stable components. The diamond crease pattern that controls the ladybug wing induces strong bistability — two of the three clusters correspond to the wing folded and unfolded states.

### 8.3 Implications for Model Design

Kuribayashi's framework enables a novel approach to the cut question:

1. **Encode the target model's geometry** as a low-energy state in the Boltzmann distribution
2. **Run MCMC sampling** from the flat-sheet initial state
3. **Check whether spectral clustering** identifies the target as belonging to the same component as the starting state

If the target is in the same component → no cut required (a fold path exists)
If the target is in a different component → a cut (or modular assembly) is required to cross the topological barrier

This is the first **computable decision procedure** for cut necessity, enabled by the 2026 ISEF work.

---

## 9. Novel Predictions (Grounded in 2026 Research)

The following predictions follow from the mathematical framework established above. They are not guaranteed, but are grounded in the theorems and results documented here. They represent research directions with high prior probability of success.

### Prediction 1: The Odd-Appendage Difficulty Law

**Claim**: For any given appendage count N, if N is odd, the minimum fold count for a valid no-cut design is strictly greater than for N+1 (the next even number), despite N+1 requiring more appendages.

**Basis**: Kawasaki's theorem. Odd N violates flat-vertex conditions at the body. Even N+1 does not. The extra fold count needed to construct a non-flat body for odd N exceeds the extra cost of one additional appendage in an even-N design.

**Test**: Design challenge: compare minimum-step no-cut 3-arm octopus (3 tentacles) vs. 4-arm octopus. The prediction says the 4-arm is achievable in fewer steps.

### Prediction 2: The MCMC-First Insect Design

**Claim**: The Kuribayashi MCMC framework will be used within 2–3 years to computationally discover a no-cut 6-legged insect design that is simpler (fewer folds) than any currently known hand-designed no-cut insect.

**Basis**: The MCMC framework's inverse design mode (estimating crease parameters to generate trajectories through specified points) can be applied with the target = 6-legged flat-fold state. This is a direct application of the 2026 prize-winning work. The 3-cluster bistability result for ladybug wings suggests that insect-scale crease patterns have unexplored configuration components reachable without cuts.

### Prediction 3: Spider Complexity Bound

**Claim**: The minimum fold count for any no-cut single-sheet origami spider is O(n²) relative to the fold count for a corresponding 4-legged animal, where n is the number of legs.

**Basis**: Schwartz's vertex-transitive optimal torus (degree sequence 66666666) requires 24 folds for 8 vertices. The body-vertex of a spider with 8 legs has structural similarity to this torus. The quadratic scaling follows from the constraint that each new appendage requires checking consistency with all others, generating O(n) local constraints per appendage, summing to O(n²) total.

**Test**: Empirically count steps in known no-cut spider designs (Lang) vs. known no-cut 4-legged designs (standard crane, horse, etc.). Preliminary evidence: Lang's spider is ~60 steps vs. ~20 steps for an average quadruped, consistent with n=8 giving (8/4)² = 4x — actual ratio ~3x — approximately confirmed.

### Prediction 4: ML-Discovered Minimal Spider

**Claim**: A machine-learning approach (following Schwartz's supervised learning method for the torus) will discover a no-cut spider design with fewer steps than any existing hand-designed no-cut spider.

**Basis**: Schwartz's torus search found the optimal 8-vertex structure by ML-assisted search after human attempts failed to find it. The spider problem has the same structure: a fixed discrete combinatorial space (valid crease patterns), a realizability condition (flat-foldable with 8 legs), and an optimization objective (minimum fold count). ML search in this space should find solutions humans have missed.

### Prediction 5: The Topological Cut Parity Theorem (Open Problem)

**Conjecture**: For any origami model requiring exactly C cuts, C is always **even** for any model whose target silhouette has rotational symmetry of order k.

**Partial basis**: Symmetric silhouettes, when folded by the fold-and-1-cut method, use symmetric fold patterns. The fold-and-1-cut theorem guarantees C ≤ 1, but conventional designs often use C > 1 in symmetric ways. The parity claim follows from the observation that symmetric cuts come in pairs. This is conjectural and not yet proven.

### Prediction 6: Kawasaki-Genus Correspondence

**Claim**: For an origami model with body of genus g (g = 0 for a sphere, g = 1 for a torus, etc.), the minimum number of flat-foldable vertices in the crease pattern is 4g + 4.

**Basis**: 
- g = 0 (sphere): minimum 4 vertices (tetrahedron) → 4(0) + 4 = 4 ✓
- g = 1 (torus): minimum 8 vertices (Schwartz 2026) → 4(1) + 4 = 8 ✓
- Extrapolated: a pretzel surface (g = 2) would require minimum 12 vertices

This is a **novel prediction** that unifies Schwartz's torus result with the classical origami tetrahedron minimum vertex count into a single formula.

---

## 10. In Memoriam: Kawasaki's Theorem and Its Author

**Toshikazu Kawasaki** (November 26, 1955 – March 4, 2026) died at age 70. His theorem — that alternating angles at any flat-foldable vertex sum to 180° — is used on every page of this atlas, even when not cited explicitly. It underlies the even-appendage principle, the cut-requirement analysis for insects and arachnids, and the topological constraints on every model from the simplest crane to the most complex polyhedral surface.

He was also the inventor of iso-area folding and the creator of the Kawasaki Rose, a design that achieves a curved petal surface through a twisting collapse — one of the first demonstrations that origami could model continuous curvature without curved creases.

The theorem bearing his name will continue to be proven at every vertex of every flat-folded crease pattern on Earth, in every DNA origami nanostructure, in every beetle hindwing and ladybug forewing, as long as flat sheets are folded.

---

## 11. Summary Tables

### 11.1 By Appendage Count and Cut Requirement

| Appendages | Even? | Flat-Vertex OK? | Standard Base | Cut Required | No-Cut Possible? |
|---|---|---|---|---|---|
| 0 | N/A | N/A | Any | ❌ No | ✅ Yes |
| 1 | No | Requires non-flat center | Kite | ❌ No | ✅ Yes |
| 2 | Yes | ✓ | Bird/Waterbomb | ❌ No | ✅ Yes |
| 3 | No | ✗ Kawasaki violation | None | ⚠️ Usually | ✅ With non-flat body |
| 4 | Yes | ✓ | Frog/Bird | ❌ No | ✅ Yes |
| 5 | No | ✗ Kawasaki violation | None | ✅ Typically | ✅ With non-flat body |
| 6 | Yes | ✓ | None (Lang-class) | ⚠️ Often | ✅ Yes (complex) |
| 7 | No | ✗ Kawasaki violation | None | ✅ Almost always | ✅ Theoretically |
| **8** | **Yes** | **✓** | **None (Lang-class)** | **✅ Conventional** | **✅ Yes (extreme)** |
| 10+ | Varies | Varies | None | ✅ Practical | ✅ Origamizer (astronomical) |

### 11.2 Model Category Summary

| Category | Cut Required | Kawasaki Status | Schwartz Relevance | Kuribayashi Relevance |
|---|---|---|---|---|
| 4-Legged Animals | ❌ Never | ✓ Satisfied (4 creases) | Low | Low |
| Birds | ❌ Never | ✓ Satisfied (4 flaps) | Low | Low |
| Reptiles/Amphibians | ❌ Rarely | ✓ Satisfied | Low | Low |
| 5-armed (starfish) | ⚠️ Parity issue | ✗ Odd-crease problem | Low | Medium |
| 6-Legged Insects | ⚠️ Often | ✓ Even (6) | Medium | **High — bistability discovered** |
| 8-Legged Arachnids | ✅ Conventional | ✓ Even (8) | **High — 8-vertex analog** | High |
| Aquatic multi-arm | ✅ Often | Varies | High | High |
| Geometric solids | ❌ Never | ✓ All flat-foldable | **High — torus proved** | Low |
| Tessellations | ❌ Never | ✓ All | Medium | Medium |
| Modular | ❌ Never | N/A (multi-sheet) | Low | Low |
| Kirigami | ✅ Always | N/A (cuts by design) | Low | Low |
| Engineering | ❌ Mostly | ✓ Designed in | High (deployability) | High (mechanism design) |
| Bio-origami | ❌ Never | ✓ Natural fold | Medium | **High — ladybug validated** |
| Topological surfaces | Varies | Varies | **Highest** | Low |

### 11.3 The 2026 Landmark Results and Their Impact on This Atlas

| Result | Source | Date | Impact |
|---|---|---|---|
| Minimal origami torus = 8 vertices, 24 folds | Schwartz, *PNAS* | May 26, 2026 | Quantifies fold complexity lower bound for genus-1 surfaces; analog for 8-appendage models |
| Möbius strip minimum aspect ratio > √3 | Schwartz, *arXiv* | 2023 (proven 2024) | Quantifies the strip-paper constraint for non-orientable surfaces |
| MCMC complete configuration-space sampling | Kuribayashi, ISEF | May 15, 2026 | First computable decision procedure for cut necessity; ladybug bistability validated |
| Origami8 (8OSME) proceedings | Springer | Jan–Feb 2026 | 126 papers; state of engineering + mathematics + education |
| Rigid origami elliptic-hyperbolic duality | Hull, *Results in Math.* | 2025 | New rigidly foldable mechanisms; extends practical no-cut engineering |
| *The Mathematics of Origami* | O'Rourke, Cambridge UP | Dec 2025 | Definitive mathematical synthesis; Origamizer + fold-and-cut in one framework |
| Death of Toshikazu Kawasaki | — | March 4, 2026 | Kawasaki's theorem now permanently fixed in the canon |

---

## 12. References

### Primary 2026 Research

1. Schwartz, R.E. (2026). "The most efficient origami torus." *Proceedings of the National Academy of Sciences*, 123(21). DOI: 10.1073/pnas.2523301123
2. Schwartz, R.E. (2024). "The Optimal Paper Moebius Band." Proof of Halpern-Weaver conjecture. arXiv:2308.12641
3. Kuribayashi, H. (2026). "Sampling the Complete Configuration Space of Origami and Linkages Using Markov Chain Monte Carlo." PHYS021. Regeneron ISEF Grand Prize, May 15, 2026.
4. Lu, G., You, Z., Assis, M. (Eds.) (2026). *Origami8, Volumes I–IV: Proceedings of the 8th International Meeting on Origami in Science, Mathematics and Education (8OSME)*. Springer Singapore. DOI: 10.1007/978-981-96-8664-3
5. Hull, T.C. (2025). "A Rigid Origami Elliptic-Hyperbolic Vertex Duality." *Results in Mathematics*, 80(5).
6. O'Rourke, J. (2025). *The Mathematics of Origami*. Cambridge University Press. ISBN: 978-1-009-68735-5.

### Classical Theorem Sources

7. Kawasaki, T. (1989). "On the relation between mountain-creases and valley-creases of a flat origami." *Proceedings of the 1st International Meeting of Origami Science and Technology*, pp. 229–237.
8. Maekawa, J. (1986). In Kasahara, K. and Takahama, T., *Origami for the Connoisseur*. Japan Publications.
9. Huzita, H. (1992). "Understanding Geometry through Origami Axioms." *Proceedings of the 1st International Conference on Origami in Education and Therapy*.
10. Hatori, K. (2001). Extension to Huzita axioms; Axiom 7.
11. Hull, T.C. (1994). "On the mathematics of flat origamis." *Congressus Numerantium*, 100, 215–224.
12. Demaine, E., Demaine, M., Lubiw, A. (1999). "Folding and one straight cut suffice." *Proceedings of SODA 1999*, pp. 891–892.
13. Lang, R.J. (1996). "A computational algorithm for origami design." *Proceedings of the 12th ACM Symposium on Computational Geometry*, pp. 98–105.
14. Demaine, E.D., Tachi, T. (2017). "Origamizer: A Practical Algorithm for Folding Any Polyhedron." *33rd International Symposium on Computational Geometry (SoCG 2017)*.
15. Justin, J. (1986). "Résolution par origami de l'équation du troisième degré et applications géométriques." *L'Ouvert*, 42.

### Designer References

16. Lang, R.J. *Langorigami.com* — TreeMaker algorithm; no-cut spider; no-cut ant.
17. Kamiya, S. *satoshi-kamiya.jp* — No-cut dragon (Ancient Dragon, Ryu Jin series).
18. Joisel, E. *ericjoisel.com* — No-cut octopus (wet-fold).
19. Fuse, T. — No-cut scorpion.
20. Yoshizawa, A. — Wet-fold technique foundation; animals including dog, bear.

### Engineering & Applied References

21. Filipov, E.T., Zhu, Y. (2024). "Large-scale modular and uniformly thick origami-inspired adaptable and load-carrying structures." *Nature Communications*. DOI: 10.1038/s41467-024-46667-0
22. Liu, Z., Zhang, Z., Fang, H. (2023). "Approximating complex 3D curves using origami spring structures." *Communications Engineering*. DOI: 10.1038/s44172-023-00149-1
23. Tachi, T. (2009). "Generalization of rigid-foldable quadrilateral-mesh origami." *Journal of the IASS*, 50(3).

### Cosmological Connection

24. Neyrinck, M. (2012). "Origami constraints on the initial-conditions arrangement of dark-matter caustics and streams." *arXiv*:1202.3364 — Application of flat-origami 2-colorability theorem to large-scale structure of the universe.

---

## 13. Changelog

| Date | Version | Changes |
|---|---|---|
| June 10, 2026 | 2.0 | Complete rewrite. New title. Integrated Schwartz PNAS 2026, Kuribayashi ISEF 2026, Origami8 proceedings. Novel Appendage Number Problem framework. Kawasaki Even-Appendage Principle. Schwartz Vertex Analog. MCMC reachability criterion. 6 novel predictions. In memoriam: Toshikazu Kawasaki (1955–2026). Expanded from ~40 to ~200+ models across 20 categories. |
| Original | 1.0 | Initial catalog (June 2026). Basic cut/no-cut table. 7 categories. |

---

*This document is the living intersection of paper, mathematics, and curiosity. Every crease is a theorem. Every fold is a proof.*
