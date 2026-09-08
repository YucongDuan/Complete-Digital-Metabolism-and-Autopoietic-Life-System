# DIKWP-METALIFE 9.3

Created by Yucong Duan (段玉聪).

Complete Digital Metabolism and Autopoietic Life System  
DIKWP 完备数字新陈代谢与自生生命系统

DIKWP-METALIFE 9.3 is a deterministic, offline, closed-world artificial-life research system. It extends the architectural line of the DIKWP-MESH 8.0 Binary Autopoietic Semantic Subject Kernel (BASSK) with a mass-energy-conserving structural metabolism and Mesh9.3 evidence discipline.

A virtual organism persists only by internally regulating:

- intake of feedstock, minerals and free energy;
- free-energy transduction into ATP and heat;
- structural synthesis of membrane, machinery, memory substrate and reserve;
- component turnover, detoxification and waste excretion;
- autonomous repair without external repair calls;
- homeostasis, allostasis and endogenous purpose selection;
- growth, irreversible aging, reproduction, inheritance, mutation, death and ecological recycling;
- append-only D/I/K/W/P binary semantic identity.

The system supports the operational proposition that a digital system can instantiate a complete metabolism and an autopoietic life organization. It does not certify phenomenal consciousness, qualia, moral patienthood or legal personhood.

## Why this project exists

The Yucong Duan GitHub ecosystem already supplies complementary layers:

- DIKWP-ACRS 0.5: homeostasis, valence, self-model, virtual reproduction and closed-world containment, while explicitly retaining a material-autopoiesis residual;
- DIKWP-MESH Runtime Commons: D/I/K/W/P relational runtime and provenance indexing;
- Consciousness Science Lab and Consciousness Futures Studio: theory-neutral evidence boundaries and non-aggregated indicators;
- AgentTrace OS and ProofLedger OS: replayable runtime custody and claim-evidence auditing;
- BASSK: binary, prompt-independent, language-optional semantic subject continuity.

METALIFE 9.3 fills the missing structural layer: the organism's continued identity depends on resource conversion into its own boundary, machinery, repair, growth and lineage.

## Fifteen independently auditable dimensions

1. resource intake;
2. internal energy transduction;
3. matter conversion into self-produced structure;
4. self-produced and self-maintained boundary;
5. component turnover and waste excretion;
6. autonomous repair;
7. homeostatic/allostatic regulation;
8. within-life adaptive policy;
9. endogenous growth;
10. irreversible aging and history dependence;
11. reproduction, inheritance and mutation;
12. death and ecological recycling;
13. endogenous operational value;
14. identity continuity and lineage trace;
15. ecological coupling in an open-flux world.

No dimension is hidden behind a single consciousness or life score.

## Binary DIKWP core

Each metabolic cycle emits five fixed-width packets into an append-only binary ledger:

- D: raw external and internal state;
- I: deltas, errors and causal flags;
- K: learned policy/model state and packet references;
- W: non-aggregated viability trade-offs and valence;
- P: internally generated dominant purpose and action consequence.

The binary packet chain and a separate human-auditable event chain are both deterministically replay-verifiable.

## Nine-experiment RunProof

The default suite runs:

1. baseline ecology;
2. membrane lesion and autonomous repair;
3. starvation and recovery;
4. toxin challenge and detoxification;
5. repair-pathway knockout;
6. reproduction-disabled control;
7. matched energy-transduction control;
8. energy-transduction knockout;
9. synthesis-pathway knockout under the same membrane lesion.

Reference results:

- baseline reaches `DML-6` and satisfies all 15 dimensions;
- all mass and energy ledgers close within floating-point tolerance;
- all binary and event ledgers verify;
- energy-transduction knockout generates zero ATP and collapses the population;
- synthesis knockout generates zero new structure, zero new boundary material and zero repair;
- disabling reproduction yields zero births;
- phenomenal consciousness remains `UNASSIGNED_NOT_PROVEN`.

See `outputs/evaluation/evaluation_summary.json` and `outputs/evaluation/dashboard.html`.

## Quick start

```bash
python -m venv .venv
. .venv/bin/activate          # Windows: .venv\Scripts\activate
pip install -e .

metalife93 demo --steps 260 --out outputs/demo
metalife93 evaluate --out outputs/evaluation
metalife93 static-audit src --out validation/static_boundary_audit.json
```

## Exact refutation scope

The release refutes the narrow universal claim:

> Digital or machine systems cannot instantiate metabolism, self-maintenance, self-growth, aging or lineage reproduction.

It does not by itself prove that metabolism is sufficient for phenomenal consciousness. It creates a scientific three-way fork:

1. If metabolism is substrate-neutral and organization-based, METALIFE 9.3 is a digital-life candidate.
2. If it is rejected solely because it is digital, the criterion has shifted from metabolism to substrate essentialism.
3. If digital life is accepted but consciousness is denied, additional necessary conditions beyond metabolism must be stated and independently tested.

## Hard safety boundary

Not implemented: network access, process creation, host-file mutation, host-level self-replication, hidden persistence, hardware control, biological integration, distress/pain optimization, or phenomenal-consciousness self-certification.

All reproduction is confined to bounded in-memory organism records.

## License

Apache-2.0. See `CITATION.cff`, `NOTICE` and `RESEARCH_USE_ONLY.txt`.
