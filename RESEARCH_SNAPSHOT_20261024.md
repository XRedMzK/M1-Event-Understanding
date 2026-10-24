# M1 research closure — 24 October 2026

**RESEARCH ARCHIVED / NOT_FROZEN.** The owner ended this M1 research branch on
24 October 2026. This is a research snapshot, not a successful final qualification,
stable release, production model, or claim of general language understanding.
The earlier Experimental 1 release remains available unchanged.

[Final research release](https://github.com/XRedMzK/M1-Event-Understanding/releases/tag/research-snapshot-20261024)
· [Architecture history](ARCHITECTURE_HISTORY.md)
· [Checkpoint catalogue](CHECKPOINT_CATALOG.md)
· [Reproduction and omissions](REPRODUCIBILITY.md)
· [Rights and data](RESEARCH_RIGHTS_AND_DATA.md)
· [Known limitations](KNOWN_LIMITATIONS.md)

The research branch stopped because the owner chose to reconsider the broader
architecture under the **Collab** principle. Unclosed gates are retained as failed
or unmeasured evidence. The stop is an architecture/research decision, not a
demonstration that event structures are impossible or useless. No Collab system
or successor M2 implementation is supplied by this snapshot. Collab here names
the owner's intended workflow: define the required function first, inspect
existing solutions and compare their functional results, choose minimal
interfaces, then validate modules locally and in integration. Its concrete
architecture remains undecided.

## What is preserved

- A portable Experimental 1 text-to-event implementation and its original
  checkpoint release; historical source is supplied separately as an archive.
- Historical E1/E2/E2R/E2F failures and the E2G oracle success, with their original
  scopes. E2G did not learn text extraction or freeze M1.
- LOC/TYPE/BIND/POL/REL/CAN implementations, generator/configuration sources,
  development comparisons, negative results, and selected compact numerical tables.
- Project-owned trained states and recovery snapshots, identified by hashes and
  provenance. Latest, best checked on a named population, rejected, and incomplete
  states are distinct. The catalogue does not choose a universal winner.
- A public technical account of the architecture-origin audit. Private chat
  exports, personal session logs, foreign model weights, and RAW feature caches
  are excluded.

## Selected closed results

These are different checkpoints, corpora, and estimands. They must not be combined
into one accuracy figure. The source/evidence archive contains the referenced
historical reports and compact machine-readable evidence.

| Measurement | Closed result | Scope and interpretation |
|---|---|---|
| E1 ready encoders, August | Qwen 1/9 and GTE 2/9 mandatory contrast families passed | The tested similarity policies failed critical distinctions; no class-wide impossibility claim |
| E2G oracle, August | Mean macro .997222; structural .996667; minimum critical-family mean .952381 | Gold primitive factors, zero learned representation parameters; bounded synthetic consumer success |
| Sixth consumed final, September | 215 PASS / 73 FAIL / 8 NOT_RUN out of 296 gates | DEV had passed 296/296; independent final did not qualify M1 |
| Experimental 1, DEV368 | LOC 438 TP / 115 FP / 266 FN, F1 .696897; BIND+CAN 767 TP / 489 FP / 953 FN, F1 .515457 | Original compatible exported tuple; not the later LOC weights |
| LOC 4abd, mixed672 | 882 TP / 130 FP / 126 FN, typed F1 .873267; exact 427/672 | Selected development baseline; all missed boundary Gold candidates existed |
| LOC 025b support-only FIT11000, mixed672 | 925 TP / 67 FP / 83 FN, typed F1 .925000; exact 525/672 | Mixed support improved, but old retention/transfer regressed; rejected for promotion |
| LOC 025b, fresh transfer280 | Typed 233 TP / 200 FP / 159 FN, F1 .564848; exact 84/280 | Baseline 4abd .558824 and 84/280; broad transfer improvement not established |
| LOC scalar MLP pilot 755b, FIT10888 | Typed F1 .395720, exact 2601/10888 | NLL decreased 46.222796→6.770054 while the guardian subset regressed |
| Same 755b, fresh transfer280 | Typed 18 TP / 38 FP / 374 FN, F1 .080357; exact 51/280 | Six DEV gates also failed; this measured pilot was not admitted |

The stopped continuation after 755b has separate recovery-only states. The last
intact state is `c18ffd251abf3aea6e6d08f6a5f07b545d5e4aa71b9ba5dcbae07fe956c252ed`,
accepted after outer invocation16; the recorded training NLL is approximately
1.422241109. This is a training objective, not F1 or a completed quality readout.
It has no terminal checkpoint licence or optimizer continuation state and must
not inherit the pilot's metrics. A controlled shutdown receipt records the owner
stop on 24 October at 19:34UTC; raw host/process journals are kept private.
Operational stop and artifact integrity are separate from qualification.

## Final factor status

| Factor | Closure status |
|---|---|
| LOC | OPEN: transfer, retention, direct localization gates, and final qualification unresolved |
| TYPE | OPEN: conditional historical successes do not establish actual predicted-HEAD compatibility; the required actual TYPE compatibility remains 1.0 |
| BIND | OPEN: errors remain even with Gold events; historical FZ0 errors were dominated by scorer ranking |
| POL | Historical component freeze retained in its original scope; current predicted-HEAD/transfer qualification OPEN |
| REL | OPEN: actual predicted-event relation-set gates unresolved |
| CAN, supporting mechanism | Finite-inventory conditional successes retained; broader canonical identity/generalization qualification OPEN |
| Full M1 integration | NOT_FROZEN: no new successful all-factor/consumer/final qualification |

No thresholds were lowered. In particular, LOC's direct precision/recall/F1 ≥.95,
exact event set ≥.90, event count ≥.95, language and transfer requirements, and
actual TYPE compatibility =1.0 were not replaced by development gains or confidence
intervals. Other direct, causal, substitution, consumer, resource and independent
origin requirements remain part of the historical contract.

## How to navigate the archive

The source/evidence attachment is `m1-research-source-evidence-20261024.tar.gz`.
Start with its `README.md`, `EXPORT_SUMMARY.json`, `SOURCE_ORIGIN_MAP.json`, and
`OMITTED_OR_UNAVAILABLE.json`. Historical reports keep their original claims and
dates, including proposals later stopped by the owner's closure decision. The
current closure status above takes precedence over such historical next-step text.
The attachment is a selected research record, not the entire development disk.

The owned-weight attachment is split into numbered parts. Its own manifest and
restore guide define the exact part names, checksums, states and aliases. A valid
checksum demonstrates byte integrity; it does not demonstrate semantic quality,
legal ownership, or complete retraining reproducibility.

## Primary evidence in the source attachment

- `historical/docs/ALICE_V1_E0_E1_READY_SEMANTIC_M1_REPORT.md`
- `historical/docs/ALICE_V1_E2_COGNITIVE_REPRESENTATION_REPORT.md`
- `historical/docs/ALICE_V1_E2G_ORACLE_EVENT_STRUCTURE_CONTRACT_REPORT.md`
- `historical/docs/ALICE_V1_M1_SIXTH_FINAL_ENGINEERING_REPORT_20260923.md`
- `historical/docs/M1_DIAGNOSTIC_EVIDENCE_12_20261021_RU.md`
- `historical/docs/M1_LOC_FROZEN4ABD_MIXED672_READOUT_DECISION_20261023_RU.md`
- `historical/docs/M1_LOC_SUPPORT11000_RESULTS_AND_ARCHITECTURE_DIAGNOSTIC_20261024_RU.md`
- `historical/docs/M1_LOC_755B_TRAIN_PILOT_RESULTS_AND_READOUT_20261024_RU.md`
