# Research snapshot: rights, data and exclusions

Prepared 24 October 2026. This extends the scope-specific Experimental 1 rights
record; it does not retrospectively certify every historical input or foreign
model. The source/evidence archive is a selected, sanitized derivative. The
project's MIT grant covers project-owned code and parameter tensors, not
independently licensed data, model assets, or dependency distributions.

## Data supplied for inspection

Most E2 and later event/argument support consists of project-authored finite
English/Russian sentence constructions, names/object task symbols, combinations,
and annotations. The archive supplies applicable generator/configuration source
and selected fixtures. These are synthetic research data, not collected personal
records or a representative sample of unrestricted language. Generated names do
not make the canonicalizer a general entity/coreference model.

**Early M1 boundary fixtures are an exception:** TRAIN320/DEV80/TEST80 examples
were selected from MASSIVE. They are not project-authored synthetic text and
must not be relabeled MIT. Attribution: **MASSIVE, Amazon.com Inc. or its
affiliates; licensed CC BY 4.0**. See the
[official MASSIVE licence](https://huggingface.co/datasets/AmazonScience/massive/blob/main/LICENSE),
[dataset](https://huggingface.co/datasets/AmazonScience/massive), and
[CC BY 4.0 terms](https://creativecommons.org/licenses/by/4.0/).
The archived subset was selected/reordered into family-held-out RU/EN pairs and
wrapped in project JSON metadata. Its original text remains attributed to its
source. Original source hashes and selection recipes are recorded in the frozen
fixture protocols. The separate HAND fixture was authored for the project.

E2PR's `qasem_protocol_supervision.json` wraps the project's E2 controlled
sentences/Gold spans using the upstream xqasem prompt/protocol; it is not a
redistribution of the upstream QASem/OntoNotes training corpus. The upstream
protocol is `JohnnieDavidov/xqasem@7a90004b7c2185501f30fb50a58edf18bbcfdcad`.
The relevant MIT notice is preserved in `notices/XQASEM_MIT_LICENSE.txt` inside
the source attachment. No entire third-party repository is vendored.

## Foreign models: references, no redistribution

| Asset used historically | Pinned revision | Licence evidence and publication boundary |
|---|---|---|
| Qwen/Qwen3.5-2B-Base | `b1485b2fa6dfa1287294f269f5fb618e03d52d7c` | [Pinned upstream Apache-2.0 licence](https://huggingface.co/Qwen/Qwen3.5-2B-Base/blob/b1485b2fa6dfa1287294f269f5fb618e03d52d7c/LICENSE), checked; separately obtained |
| Qwen/Qwen3-Embedding-0.6B | `97b0c614be4d77ee51c0cef4e5f07c00f9eb65b3` | [Pinned model card](https://huggingface.co/Qwen/Qwen3-Embedding-0.6B/blob/97b0c614be4d77ee51c0cef4e5f07c00f9eb65b3/README.md) declares Apache-2.0; separately obtained |
| Alibaba-NLP/gte-multilingual-base | `9bbca17d9273fd0d03d5725c7a4b0f6b45142062` | Historical locked model metadata and local upstream model card declare Apache-2.0; no weights/code bundled |
| Alibaba-NLP/new-impl | `40ced75c3017eb27626c9d4ea981bde21a2662f4` | Historical external-code dependency, referenced only; no implementation bundled |
| FacebookAI/xlm-roberta-base | `e73636d4f797dec63c3081bb6ed5c7b0bb3f2089` | Local upstream model card declares MIT; no weights/tokenizer bundled |
| liaad/srl-en_xlmr-base | `55387c653aba11f0025a2f7089435c11c4c583f6` | Local upstream model card declares Apache-2.0; upstream training includes OntoNotes, which is not bundled |
| sambanovasystems/SambaLingo-Russian-Base | `61e9f47f637de0092e28decca02a632b50ba4b9d` | Local upstream model card requires Llama 2 Community Licence; no weights/tokenizer bundled |
| YonatanDavidov/qasem-ru-sambalingo-lora | `d5fd35ed26d239a626d66e19145fd0a988638122` | Local adapter card declares MIT but its base retains separate Llama 2 terms; neither adapter nor base is bundled |

Exact primary web verification succeeded for pinned Qwen and MASSIVE sources.
Some other pinned URLs were unavailable to the verification tool; their rows
identify the inspected local upstream cards/locked protocols rather than claiming
a new complete independent legal audit. Excluding all their asset bytes avoids
treating these metadata findings as redistribution approval. Foreign-derived GTE
LoRA candidates are excluded from the owned-weight attachment pending separate
provenance/rights review.

## Dependencies and privacy

Core/provider dependencies retain their own upstream licences and notices. The
existing `THIRD_PARTY_NOTICES.md` and `docs/DEPENDENCIES.md` remain applicable to
the portable runtime. Historical requirements/configuration files record other
research environments, not a tested universal install set. No wheels, external
package source, donor tensor payloads or tokenizer assets are included here.

No private discussion export, personal Codex session, `.env`, credential file,
secret qualification seed file, RAW feature bank, process command dump or raw
host-control stop journal is intentionally included. Personal home paths are
redacted; the source map records the resulting public-byte hashes. The architecture
history is a technical derivative with uncertainty preserved, not a transcript.

The safety scan is bounded to the selected exported bytes and declared patterns.
It is not a guarantee of universal privacy, full upstream training-data rights,
or copyright non-infringement. Any later redistribution of excluded assets needs
its own provenance, licence and content review.
