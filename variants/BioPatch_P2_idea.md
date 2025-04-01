# BioPatch_P2 – Fusion Variant Concept

## Objective:
Create a second BioPatch fusion with altered domain order and modified linker composition for performance comparison.

---

## Design:
**Domain Order:**
Mfp-3 (adhesive) → Resilin (elastic) → MaSp1 (strength)

**Linkers:**
Use a rigid linker (`EAAAK`) between domains instead of GGGGS for increased spacing and domain independence.

---

## Hypothesis:
- Front-loading Mfp-3 will increase adhesion and surface availability
- Rigid linker may reduce unwanted cross-domain interference
- Potential downside: reduced flexibility if too rigid under stress

---

## Next Steps:
- Generate full amino acid sequence with new linker
- Fold using ESMFold or 310.ai
- Simulate flexibility using CABS-flex
- Compare RMSF profiles with P.1
- Consider expression tests in E. coli
