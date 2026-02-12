# Zenodo Metadata

## Title
On the Convergence of the Collatz Sequence

## Authors
Nemytchenko, Ivan

## Description
We present a proof of the Collatz conjecture, one of the most famous open problems in mathematics. The conjecture states that for every positive integer n, the sequence defined by C(n) = n/2 if n is even, and C(n) = 3n+1 if n is odd, eventually reaches 1.

The proof proceeds in three stages:

1. **Negative drift**: We establish that the expected value of the 2-adic valuation k = v₂(3n+1) equals 2, which exceeds log₂(3) ≈ 1.585. This implies that trajectories decrease in level on average by approximately 0.415 bits per step.

2. **No non-trivial cycles**: Using the fundamental theorem of arithmetic, we prove that no cycles exist other than the trivial cycle 1 → 4 → 2 → 1. This follows from the impossibility of 3^c = 2^m for positive integers c and m.

3. **Empty exception set**: We prove that the set E of integers with divergent trajectories is empty. The argument partitions E by residue classes modulo 3 and shows that the interplay between forward iterations and preimages creates an impossible infinite descent.

The key technical innovation is the analysis of transitions between residue classes modulo 3, combined with the irreducibility of the Markov chain induced by the Collatz map on residue classes modulo 48.

## Keywords
Collatz conjecture; 3n+1 problem; number theory; dynamical systems; Markov chains; ergodic theory; 2-adic valuation

## License
CC-BY-4.0

## Related identifiers
- IsSupplementTo: https://github.com/inem/collatz

## Subjects
- Mathematics
- Number Theory
- Dynamical Systems

## Resource type
Preprint

## Version
1.0.0

---

## Upload checklist
- [ ] paper.pdf
- [ ] paper.tex
- [ ] references.bib
