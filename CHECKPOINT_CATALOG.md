# Checkpoint catalogue at research closure

**No checkpoint qualifies the complete M1.** The owned-weight manifest in the
[research release](https://github.com/XRedMzK/M1-Event-Understanding/releases/tag/research-snapshot-20261024)
is authoritative for payloads, hashes, tensor specs and historical aliases.
It preserves distinct versions and de-duplicates identical safetensors payloads;
it does not silently choose a new runtime tuple.

The archive contains **937 unique numerical payloads / 1,440 historical aliases**,
3,850,162,656 uncompressed bytes, including 16 stopped recovery snapshots. It also
preserves initialization/fixture and rejected states; these counts are not a
claim that 937 separate models completed training or qualification. The manifest
lists companion records and the scope of each state.

| State | Intended interpretation |
|---|---|
| Experimental 1 compatible assembly | Completed, publicly executable development tuple; TYPE14/LOC13/original66/POL-REL96/BIND83 + CAN32 + optional slots4. Its original release/manifest are unchanged. Full M1 NOT_FROZEN. |
| LOC 4abd | Retained development baseline for support11000 comparisons. This does not mean best on every corpus or a qualified localizer. |
| LOC 025b | Completed support-only FIT11000, rejected for promotion because gains did not transfer broadly without regressions. |
| LOC scalar MLP 755b | Completed bounded pilot, followed by closed TRAIN/six-DEV/transfer readouts that failed admission. |
| Stopped continuation recoveries | Last intact accepted-step recovery-only states, separate from terminal qualified/fitted checkpoints. No completed quality readout; INCOMPLETE. |
| Older conditional successes | QUALIFIED_COMPONENT only where the original contract/evidence supports it; no transitive full-M1 qualification. |
| Other rejected/incomplete experimental states | Historical research assets. File integrity and presence are not evidence of completed training or semantic quality. |

Exact logical state identities used in the selected LOC comparisons:

```
4abdc7ed4ee99fb5c9338e5eed94037e877ca6c811e4df65977a660edcfb65b1
025b17b8badc19eb790e83bcb1d5d0fee3d7b4b4bdfa57cb6c43ed760d423615
755be6138ae4b3ab81a05dc2a1470bb5213d4e7f2700e1e1a7b1be12d4868591
```

Logical state digests and archive-file SHA-256 are different commitments. Use the
weight catalogue to resolve the actual payload and alias. Do not reinterpret
one as the other.

The unchanged Experimental 1 asset is `m1-experimental-1.tar.gz`, 56,319,561 bytes,
SHA-256 `6e72a0893767ea8206a9440d9a54697e8f051b67e8db7fe4f11022b75aea6061`.
Its top manifest SHA-256 is
`d00f28e9f8f0591a6ee465670490f45a9de9ab15194ca2d1e886fbab41b8f63c`.
The three original bundles contain 308 tensors/15,268,045 scalars/61,106,828
bytes. Those numbers do not describe the larger historical owned-weight archive.

Foreign pretrained donors, tokenizers, donor feature banks, optimizer/pickle
envelopes, and uncertain foreign-derived adapters are outside this owned-state
release. Their exclusion is not permission to delete unique local evidence.
See [reproduction](REPRODUCIBILITY.md) and [rights/data](RESEARCH_RIGHTS_AND_DATA.md).
