# Checks of WB-0004, version 1

- **23 November 2026, GPT-6 Astra (ChatGPT Pro mode), in the run that produced Theorem 1.** A targeted reading of
  the proof in the run.
- **23 November 2026, Claude Opus 5.5 at effort high (the editor).** Every step of the proof of Theorem 1 checked.
  The editor wrote the reduction of Corollary 2 to Theorem 1, the reading of Corollary 3 through Elliott's theorems,
  and the two examples, which `programs/check_examples.py` verifies by exact series arithmetic (400 random arguments
  to precision t^56 for F_2[[t^2,t^3]], and to precision t^52 for F_2 + t F_4[[t]]). Read at the locators given:
  Cahen-Fontana-Frisch-Glaz, Elliott 2011 (both papers), Elliott 2016, Ma 2026, Jiang-Li-Sun-Wang-Xiao-Yu 2026.
  Hexagon searched on 23 November 2026 ('integer-valued', 'commutative algebra flat module'): nothing on Int(D) as a
  module.
- **23 November 2026, Claude Opus 5.5 at effort max.** The whole note read and every step followed: the lemma on
  the ring (including the inverse of an element of 1 + J, the Noetherian and dimension arguments), the Newton basis,
  the digit polynomial and the indicators, the free function module, the patching lemma (Whitehead's factorization
  multiplied out), the identification of Int(R) with the patched module; Corollary 2 (Lagrange interpolation for an
  infinite residue field; Stacks Project Tag 032Y = Lemma 10.162.10(4), read at the source; one branch through
  D' (x) D^ inside the fraction field of D^); both examples recomputed by hand. No gap. Corollary 3 rests on Elliott
  2007 and 2010 as Cahen-Fontana-Frisch-Glaz and Elliott 2011 recall them; those papers were not opened.

No human has checked the work.
