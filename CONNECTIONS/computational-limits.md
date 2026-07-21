# Connection: Computational Limits

> Turing's undecidability, computational complexity, and the Church-Turing thesis in relation to the Impossible Object.

---

## What Turing Proved

In 1936, Alan Turing showed that there exist problems that **no algorithm can solve**:

- The Halting Problem: no program can determine whether an arbitrary program will halt
- Rice's Theorem: no algorithm can decide non-trivial semantic properties of programs

This is not about current technology. It is a **mathematical fact** about computation itself.

## The Parallel with Axiom 1

Turing: No finite algorithm can solve all problems.  
Axiom 1: No finite system can fully model the object.

Both identify a **hard boundary** for finite processes. Computation has its horizon; the object has its own. The theory suggests these are the **same horizon viewed from different angles** (Axiom 6).

## Computational Complexity

Even for decidable problems, some are **practically impossible**:

- **P**: solvable in polynomial time
- **NP**: verifiable in polynomial time; solvable in exponential time (conjectured)
- **NP-complete**: hardest problems in NP; if one is in P, all are

The P vs NP problem remains open. If P ≠ NP (as widely believed), there exist problems whose solutions are easy to verify but hard to find.

## The Speculative Claim

The theory suggests: **NP-hardness may reflect the Information Horizon**.

Not all hard problems — but those whose solution would require building a model that approaches the object's complexity. The "hardness" is not computational inefficiency. It is **structural distance** from the object.

## The Church-Turing Thesis

The thesis states: any effectively calculable function can be computed by a Turing machine.

The theory does not challenge this. It adds: **there exist structures that are not effectively calculable not because they are too complex, but because calculation itself is a projection that cannot reach them**.

## Sources

- Turing, A.M. (1936). "On Computable Numbers, with an Application to the Entscheidungsproblem"
- Sipser, M. (2012). *Introduction to the Theory of Computation*
- Aaronson, S. (2013). "Why Philosophers Should Care About Computational Complexity"

---

> *"Turing showed that some problems are uncomputable. I suggest that uncomputability is not a dead end — it is a signpost pointing to the horizon."*
> — lordekz