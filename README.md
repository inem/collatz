# On the Convergence of the Collatz Sequence

A proof of the Collatz conjecture.

## Abstract

We prove that for every positive integer n, the Collatz sequence eventually reaches 1. The proof relies on three key observations:

1. The expected value of the 2-adic valuation of 3n+1 equals 2, which exceeds log₂(3) ≈ 1.585, implying negative drift in the trajectory

2. The non-existence of non-trivial cycles follows from the fundamental theorem of arithmetic

3. The set of hypothetical divergent trajectories must be empty by analyzing its structure under residue classes modulo 3 and exploiting the irreducibility of the induced Markov chain

## Files

- `paper.tex` - LaTeX source
- `paper.pdf` - Compiled paper
- `references.bib` - Bibliography

## Build

```bash
pdflatex paper.tex
bibtex paper
pdflatex paper.tex
pdflatex paper.tex
```

## License

This work is released into the public domain.
