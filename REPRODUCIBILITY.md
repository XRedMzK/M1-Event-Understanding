# Reproduction scope of the research snapshot

**Archived research; M1 NOT_FROZEN.** Integrity, executable restoration, semantic
quality and retraining reproducibility are separate claims.

## Existing portable runtime

The repository's existing `m1` API and documented CLI continue to use
[Experimental 1](https://github.com/XRedMzK/M1-Event-Understanding/releases/tag/experimental-1).
Follow `docs/EXPERIMENTAL_1.md` and `docs/FEATURE_PROVIDER.md`. The original top
checkpoint manifest commitment is
`d00f28e9f8f0591a6ee465670490f45a9de9ab15194ca2d1e886fbab41b8f63c`.
The feature donor is obtained separately:
`Qwen/Qwen3.5-2B-Base@b1485b2fa6dfa1287294f269f5fb618e03d52d7c`.
Another encoder, donor revision, layer, prefix recipe or batching geometry is not
automatically compatible with the trained basis.

Measured historical environment: Python3.12, Torch2.13.0, NumPy2.5.2,
safetensors0.8.0; provider Transformers5.15.0, tokenizers0.22.2,
huggingface-hub1.27.0, accelerate1.14.0. These exact pins describe the recorded
environment; they do not guarantee every platform combination.

## Source/evidence attachment

Obtain `m1-research-source-evidence-20261024.tar.gz` from the
[research release](https://github.com/XRedMzK/M1-Event-Understanding/releases/tag/research-snapshot-20261024).
If supplied as `.40m.partNNN` assets, download every part listed in
`M1_RESEARCH_SOURCE_EVIDENCE_SHA256.json`, verify each part, and concatenate in
numerical order to recover that single tar.gz stream. Verify its independently
published combined size and SHA-256 before extraction. The
archive contains:

- `historical/src`, `tools`, `tests`, early experiment-specific test directories,
  configurations, generated fixtures, research reports, ADRs and cited compact
  result/protocol files, all nested under `historical/` where applicable;
- `SOURCE_ORIGIN_MAP.json`: every selected original relative path, original SHA,
  public path, public SHA, size and redaction category;
- `OMITTED_OR_UNAVAILABLE.json`: omitted or missing literal paths and reasons;
- `EXPORT_SUMMARY.json`: the exact exported scope;
- public closure/history/rights documentation and explicit third-party notices.

The placeholder `<RESEARCH_ROOT>` replaces personal project paths, and
`<USER_HOME>`/`<LEGACY_RESEARCH_ROOT>` replace personal/legacy paths. These are
declared archive redactions, not working environment variables. Historical
strict custody checks can therefore reject a relocated/redacted source snapshot.
The original SHA records authenticate provenance only; the public SHA verifies
the supplied derivative. Do not claim byte-identical original execution from a
redacted file without reconstructing and validating the affected recipe.

Historical imports may require shared Foundation support or donor packages not
fully included. Their source and protocols are supplied for inspection and
reuse; arbitrary old scripts/tests are not claimed runnable from a clean clone.
The ordinary portable runtime is the separate maintained execution surface.
Any separately supplied research checkpoint restoration utility states its own
supported architecture and checks; it does not upgrade the whole archive to an
executable full-history training package.

For a small standalone check, the same release also supplies
`m1-latest-loc-recovery-portable-20261024.tar.gz` and its checksum record. Its
README and authenticated fixture demonstrate restoration/inference for the
latest c18f recovery state on saved RAW+TYPE inputs. No donor download is needed
for that fixed-fixture check. It does not measure accuracy or accept raw text.

## Owned-weight attachment

The numbered `m1-owned-weights-research-20261024.tar.gz.40m.partNNN` files form one
tar.gz stream: **86 parts, `.40m.part001` through `.40m.part086`**. The first 85
parts are 41,943,040 bytes each; the last is 1,987,508 bytes. Their concatenation
is 3,567,145,908 bytes, SHA-256
`ab71284c7730cffb5d8a302616e156fc15ffc297dec5f9154754f0bb8c92a65d`.
This is a lossless transport split of the locally restored-and-verified stream;
do not mix it with the earlier four 1 GiB transport parts retained locally.
Download every part and the asset checksum manifest; compare
each size and SHA, concatenate in numerical order, and verify the combined
archive hash before extraction. The manifest and `WEIGHTS_RESTORE.md` supplied
with the release give the authoritative instructions.

Inside, `WEIGHTS_MANIFEST.json` maps historical relative aliases and state specs
to unique `weights/<original-sha256>.safetensors` payloads. A recovery checkpoint
can be intact without being a completed fitted/qualified state. Load data-only
state arrays with the matching declared architecture. Do not automatically
execute historical modules or untrusted pickle files.

## What is not fully reproducible from the public assets

Two large historical RAW banks have additional source-level reconstruction
records in this attachment: the Am194 full TRAIN prefix bank (52,660 rows,
103 original calls) and independent clause scope RAW12 (5,376 rows, 12 calls).
The required 1,035 original nonmodel files include the original authored corpora,
complete raw-text/order/lineage inventory, token plans, layouts, source closure,
environment/donor locks and original acceptance/protocol records. Their public
representations and original/public SHA mappings are supplied, not merely hashes
of inaccessible texts. See `closure_metadata/storage_first124_reconstruction_v1.md`
and its detailed provenance/list in the source attachment.

This supports inspection and a documented path to **new source-level
regeneration**, with separately obtained compatible donor assets and a new
resource-controlled capture wrapper. It does not establish regenerated FP32 bits
equal to the old banks. Historical strict absolute-path/custody checks may require
an explicit relocation adapter, and hardware/library/batching differences can
change bits. The original measured evidence is not overwritten by a new capture.
These records alone are not an authority to delete exact historical tensors where
the claimed evidence needs their byte-exact replay. Local-only or unavailable
artifacts remain explicitly so until independently preserved and verified.

The archive is deliberately selected. RAW donor caches, some large detailed
tables/journals, shared Foundation dependencies, complete initial external data
sources, and all environments of every historical run are not bundled. Some
literal historical paths are unavailable. Compact aggregate evidence can remain
inspectable without allowing a full recomputation of that result. Those cases
remain limitations, not successes inferred from saved hashes.

Generators/configurations and authored fixtures improve inspectability and
future regeneration where their full prerequisites are available. They do not
erase consumed-DEV/final exposure or retroactively turn development into an
independent qualification. No new training, model search or qualification was
performed merely to assemble the source/evidence asset.
