# AXV Interpretation of Quantum Mechanics  
### *Existence and Counter‑Existence*

> Working note / manifesto draft  
> Author: Wojtek (Dr_Paihiwo)  
> Version: 0.1 (conceptual)

---

## 1. Motivation (non‑technical overview)

Standard quantum mechanics says that physical systems are described by a **quantum state** (wavefunction) and that this state can be in a **superposition** of many alternatives at once.

Two well‑known ways to talk about this:

- **Collapse pictures** (e.g. “Copenhagen”):  
  The wavefunction evolves smoothly *until a measurement happens*, then it randomly jumps (collapses) to one outcome.
- **Many‑Worlds / Everett**:  
  The wavefunction never collapses. Instead, it **branches** into many “worlds”, and every outcome happens in a separate branch.

The AXV Interpretation keeps the **standard mathematics** (Hilbert space, unitary evolution, decoherence) but changes *how we talk about what is real*:

- There is **one actual macroscopic history** – one “world” that carries a genuine, ongoing continuum of time and events.  
- All other “branches” remain inside the universal quantum state as **counter‑existence**:  
  they are not erased or denied, but they do **not** become separate macroscopic worlds with their own time line and observers.

Intuitively:

> The wavefunction contains both **existence** and **counter‑existence**.  
> Existence = the realized branch (our world).  
> Counter‑existence = unrealized alternatives that still “weigh” in the equations and guarantee balance, symmetries and conservation laws, but do not form their own timelines.

---

## 2. Core picture in plain language

### 2.1. The tree metaphor

Imagine the universe as a growing **tree of possibilities**:

- Every quantum event that could go different ways corresponds to a **branching**.
- Before the event, you have many possible branches.
- After the event, **one branch becomes the actual trunk forward in time** – this is the world we inhabit.

In AXV language:

- The **realized branch** = **existence** (the actual macroscopic history, with time and experience).
- The **other branches at that splitting** = **counter‑existence**:
  - they *do* appear in the quantum state,
  - they are necessary for the full amplitude structure,
  - but they **do not continue** as independent macroscopic worlds with their own ongoing time.

They are like the “negative side” of numbers:  
\+5 apples is real, −5 apples is not “non‑number”, it is a *real* concept (a debt) that matters in the accounting.  
Similarly, counter‑existence is not “nothing”; it is a necessary balancing part of the quantum “accounting”.

### 2.2. Existence vs. counter‑existence

Very informally:

- **Existence**  
  - One decoherent branch is singled out as the **actual world**.  
  - It has a macroscopic time flow, history, observers, further measurements, etc.
- **Counter‑existence**  
  - All the other decoherent branches at that point.  
  - They remain in the universal state and are needed for:
    - unitarity (no information loss in the full state),
    - conservation laws,
    - the structure of probabilities (Born rule).
  - But they do *not* become separate “Everett worlds” with their own full macroscopic continuum.

In short:

> AXV keeps **all** quantum alternatives in the mathematics,  
> but grants a full “reality with time” only to one branch.

---

## 3. Informal postulates (AXV‑style)

Here is a compact, more technical statement. It is still informal, but uses standard QM language.

### AXV‑1: Universal quantum state

There is a **universal quantum state**  
\\[
|\Psi(t)\rangle
\\]
in a Hilbert space, evolving according to the usual unitary dynamics
\\[
|\Psi(t)\rangle = U(t,t_0)\,|\Psi(t_0)\rangle,
\\]
with no fundamental stochastic collapse.

### AXV‑2: Decoherence and branching

Interaction with the environment leads to **decoherence**, approximately decomposing the state into orthogonal branches labelled by coarse‑grained macroscopic histories \\(\alpha\\):

\\[
|\Psi(t)\rangle \approx \sum_{\alpha} c_{\alpha}\,
|\alpha\rangle_{\text{sys}} \otimes |E_{\alpha}\rangle_{\text{env}} \otimes |O_{\alpha}\rangle_{\text{obs}},
\\]

with \\(\langle E_{\alpha}|E_{\beta}\rangle \approx 0\\) for \\(\alpha \neq \beta\\).

These \\(|\alpha\rangle\\) can be thought of as **candidate “worlds”** or histories at time \\(t\\).

### AXV‑3: Single actual macroscopic history

At any time \\(t\\), **exactly one decoherent branch**  
\\[
|\alpha^\*\rangle_{\text{sys}} \otimes |E_{\alpha^\*}\rangle_{\text{env}} \otimes |O_{\alpha^\*}\rangle_{\text{obs}}
\\]
is **ontologically actual** as the macroscopic continuum: this is *the* world in which time flows and events “really happen”.

The choice of \\(\alpha^\*\\) is not specified by a new dynamical equation here; it is treated as an **extra ontological postulate**: “one branch is actualized”.

### AXV‑4: Counter‑existence of all other branches

All other branches \\(\alpha \neq \alpha^\*\\):

- remain present in the universal state \\(|\Psi(t)\rangle\\),
- are necessary for:
  - unitarity of the overall evolution,
  - the full structure of amplitudes and interference (especially **before** decoherence),
  - global consistency with conservation laws and symmetries,
- but they **do not** generate separate macroscopic timelines with additional observers.

We call the realized branch **existence** and the unrealized branches **counter‑existence**.

Symbolically:

\\[
|\Psi(t)\rangle
= c_{\alpha^\*}\,|\text{existence}\rangle
+ \sum_{\alpha\neq\alpha^\*} c_{\alpha}\,|\text{counter‑existence}_\alpha\rangle.
\\]

### AXV‑5: Born rule and empirical equivalence

Probabilities for measurement outcomes in the actualized branch obey the standard **Born rule**:

\\[
P(\alpha^\*) = |c_{\alpha^\*}|^2.
\\]

The AXV Interpretation **does not change**:

- the Schrödinger equation,
- the Born rule,
- or any empirical predictions of quantum mechanics.

It only adds a specific **ontological reading** of branches:

> One branch is “world with time”; the rest are “necessary unrealized alternatives”.

---

## 4. Toy example: spin‑1/2 measurement

Consider a single spin‑1/2 particle in an equal superposition:

\\[
|\psi_{\text{sys}}\rangle = \tfrac{1}{\sqrt{2}}\big(|\uparrow\rangle + |\downarrow\rangle\big).
\\]

An apparatus measures spin along \\(z\\). After interaction and decoherence, we get:

\\[
|\Psi\rangle
= \tfrac{1}{\sqrt{2}}\,|\uparrow\rangle\,|E_{\uparrow}\rangle\,|O_{\uparrow}\rangle
+ \tfrac{1}{\sqrt{2}}\,|\downarrow\rangle\,|E_{\downarrow}\rangle\,|O_{\downarrow}\rangle,
\\]

with \\(\langle E_{\uparrow}|E_{\downarrow}\rangle \approx 0\\).

- **Everett (Many‑Worlds)**:  
  Both terms are equally real worlds. In one world the observer \\(|O_{\uparrow}\rangle\\) sees “up”, in the other \\(|O_{\downarrow}\rangle\\) sees “down”. Each world continues with its own future.

- **Collapse picture (Copenhagen‑style)**:  
  The state randomly collapses to one term, say “up”, with probability 1/2, and the other term is removed.

- **AXV Interpretation**:  
  - The full superposition remains in \\(|\Psi\rangle\\) (no modification of the math).  
  - One term, say  
    \\(\tfrac{1}{\sqrt{2}}\,|\uparrow\rangle\,|E_{\uparrow}\rangle\,|O_{\uparrow}\rangle\\),  
    is **actualized as existence** – this is the branch that owns the macroscopic time line.  
  - The other term  
    \\(\tfrac{1}{\sqrt{2}}\,|\downarrow\rangle\,|E_{\downarrow}\rangle\,|O_{\downarrow}\rangle\\)  
    remains inside \\(|\Psi\rangle\\) as **counter‑existence**:
    - it does not generate another macroscopic world with its own flowing time,
    - but it is part of the full quantum book‑keeping that guarantees unitary evolution and the correct probabilities.

So for the observer:

- They only ever experience **one** outcome and one history.
- The “other possibility” is not deleted; it lives on as a non‑actualized component of the universal state.

---

## 5. Relation to other interpretations

This section is deliberately brief and qualitative.

### 5.1. Relation to Everett (Many‑Worlds)

Similarities:

- Keeps the **universal wavefunction** and **unitary evolution**.
- Uses **decoherence** to define quasi‑classical branches.

Differences:

- Everett: *all decoherent branches are equally real worlds*, each with its own time and observers.  
- AXV: *only one branch is actualized as a world with time*; the others are “counter‑existence” – real in the state, but not realized as separate macroscopic histories.

AXV can be seen as a **“single‑world Everett”**:
- mathematically close to Many‑Worlds,
- ontologically closer to a single actual history.

### 5.2. Relation to Copenhagen‑type collapse views

Similarities:

- Only **one world** is taken as the actual experienced reality.
- We do not see branching universes.

Differences:

- Copenhagen (in its simple form) introduces a **physical collapse** of the wavefunction.
- AXV **keeps unitarity** of the universal state and treats “actualization of one branch” as an ontological postulate rather than a new dynamical law.

### 5.3. Relation to modal and histories interpretations

AXV is very close in spirit to:

- **Modal interpretations**:  
  The quantum state encodes *possibilities*, and a subset of them is actual.  
- **Consistent / decoherent histories**:  
  Quantum mechanics is formulated in terms of sets of histories, with probabilities assigned to whole histories.

AXV adds a particular **narrative**:

- The actual world is one consistent history (one branch),
- All other consistent histories remain in the state as **counterfactual but dynamically relevant** components.

---

## 6. On “balance” and the role of counter‑existence

The intuitive picture behind AXV is that:

- Quantum theory is full of **balances**:
  - plus/minus contributions in path integrals,
  - particle/antiparticle symmetry in quantum fields,
  - zero‑point fluctuations in the vacuum,
  - conservation laws enforced at every interaction.
- The **unrealized branches** are not “nothing”; they are more like the **negative side of a balance sheet**:
  - without them, the amplitudes would not add up correctly,
  - interference patterns would not arise,
  - and the conservation and symmetry structure would be incomplete.

In this sense:

> “Something exists here *because* something (in a complementary way) exists there” –  
> not as another classical universe, but as a **counterpart in the quantum state**.

This is a philosophical reading of standard quantum structure, not a new empirical claim.

---

## 7. Status, open questions and limitations

- **Empirical status**  
  AXV is currently an **interpretation** of standard QM, not a new theory.  
  It makes **no different experimental predictions** compared to ordinary quantum mechanics with decoherence.

- **Open questions / to‑do**:
  - Can the “actualization” of one branch be connected to a precise rule, beyond “one branch is actual”?  
  - Is there a way to derive or motivate the Born rule inside AXV without simply assuming it?  
  - Can this view be embedded in a relativistic QFT framework without conflict with locality / covariance?

Because of this, AXV is best viewed as:

> A way to talk about quantum mechanics that keeps  
> – one real world with time,  
> – a fully quantum, unitary universal state,  
> – and a meaningful role for unrealized possibilities as **counter‑existence**.

---

## 8. Short glossary for non‑specialists

- **Hilbert space** – a kind of mathematical space where quantum states live. Think “very large vector space of possibilities”.
- **Wavefunction / quantum state** – the object (often written as \\(|\Psi\rangle\\)) that encodes all quantum information about a system.
- **Superposition** – a state that is a combination of alternatives, e.g. \\(|\psi\rangle = a|0\rangle + b|1\rangle\\).
- **Decoherence** – the process by which quantum alternatives become effectively separate, because the environment “records” which alternative happened, and interference between them disappears for all practical purposes.
- **Branch** – one decoherent alternative (one coarse‑grained history) inside the universal state.
- **World (in AXV)** – the *single* branch that is actualized as a macroscopic continuum with time.
- **Counter‑existence** – all other branches that remain in the universal quantum state, necessary for the full quantum balance, but not realized as separate macroscopic worlds.

---

*This document is a conceptual draft. Feedback from both physicists and non‑physicists is welcome. The aim is not to replace standard quantum mechanics, but to offer a way of speaking about it that preserves:*

- *a single experienced world,*  
- *the full quantum formalism,*  
- *and a meaningful role for unrealized possibilities as part of the physical “balance sheet”.*
