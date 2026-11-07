# Gallery closeout data candidate — 7 November 2026

## Status

This record preserves the complete data candidate associated with [aethmodular PR #20](https://github.com/ahzs645/aethmodular/pull/20) and the strict publication workflow in [gallery PR #1](https://github.com/ahzs645/aethmodular-gallery/pull/1). The candidate remains **unpublished and not deployed**. This preservation update does not change `deploy-request.json`, publish a data release, or replace the last successful publication record.

**Preservation status: `drive_upload_and_raw_byte_readback_verified`.** All 21 uploaded scientific payload files were fetched back from Drive and matched their byte counts and SHA-256 hashes; the four split archives were also actually reconstructed and independently reread with exact matches. The private archive index records provider file identities and upload readback. The [public preservation manifest](https://github.com/ahzs645/aethmodular/blob/d8928f287043905147e90151c15f8ef2429ce32e/docs/gallery-closeout-preservation-2026-11-07.json) records portable filenames, sizes, hashes and restoration instructions. Private Drive links and account details are not stored in either repository.

## Data identity

| Item | Recorded value |
|---|---|
| Candidate archive | `Aethmodular_Gallery_Data_Closeout_20261107.tar.gz` |
| Bytes | 167,794,774 |
| SHA-256 | `accc09aa8eea12d32c9c58c2daa54f3d01658edd54dd12c82a67fc363db2f49c` |
| Suggested data tag | `data-accc09aa8eea` — not published |
| Regular files | 5,137 |
| Changed member | `experimental/continuum_baseline.json` |
| Changed member SHA-256 | `f38baa0c6756fadf92583ef3b23c018b4c6f1773efd4bf52b7ce6f56db1649a2` |
| Unchanged members | All other 5,136 files are byte-identical; no files added or removed. |
| Original base | [`data-82d701248232`](https://github.com/ahzs645/aethmodular-gallery/releases/tag/data-82d701248232) |
| Original base SHA-256 | `82d701248232b1975ea2e452bc1d682877e811103a2aa1040aff9d4adc989051` |
| Candidate verification receipt SHA-256 | `fb6640eee77739bfb5b23e4b3ef75ff65b7fc929dc9de3a5472684e86f19b5b1` |
| Full member-comparison proof SHA-256 | `483f0aa720852d1dfe798755fa7fc15207dda99c901e6fa802cef51edeeea5f0` |

The candidate and original base are preserved in the logical Google Drive archive `Aethmodular VIBES/results/closeout_20261107`, under separate `gallery_candidate` and `gallery_base` part folders. Each archive is delivered in two ordered binary parts, with at most 100,000,000 bytes per part. The original full-archive identities above remain unchanged. The archive index and portable restore utility verify the parts and reconstructed bytes before use.

The same archive set also preserves the original scientific inputs, complete continuum run, fitted research results, exact seven-page figure export and verification evidence. Repository-backed analysis code, interface changes and research documentation remain in the source repository. The [reproduction protocol](https://github.com/ahzs645/aethmodular/blob/d8928f287043905147e90151c15f8ef2429ce32e/docs/gallery-closeout-reproduction-2026-11-07.md) describes restoration and the scientific evidence boundary.

## Source and verification

| Role | Source identity |
|---|---|
| Frozen numerical implementation | `ee1c6adac64b773944ee3bbaea3aac07d60f2f13` |
| Accepted review and PDF | `2341cbbbab41b9dfde143d36aac5ea84585aea31` |
| Subsequent completion documentation | `76b369eff84dada214fb21343f43a990cb45c880` |
| Canonical publication-workflow review | Gallery source `b81c910d9c1ce9b1d6e4c2b909c87b229998f13e` |

[Run 42407030717](https://github.com/ahzs645/aethmodular/actions/runs/42407030717) verified the accepted review source with the original base archive and its separately hashed corrected overlay: 114 Python regressions, 372 Node source tests, 91 public-data tests, TypeScript, production build and three browser journeys passed. The completed seven-page PDF and phone views received visual review. Later documentation-only head `76b369ef` also passed [run 42407701722](https://github.com/ahzs645/aethmodular/actions/runs/42407701722); its receipt is archived separately and does not relabel the accepted PDF.

The full candidate is equivalent to the intended data contents of that base-plus-overlay review. **Keep the original base as the review CI input**; the overlaid candidate must not be substituted for it while claiming the original base hash. A future publication must produce its own exact source/data receipt through the canonical deployment workflow after the required source changes are available. This archival record is not that deployment receipt.

Absolute Addis EC accuracy remains unresolved. The unavailable full legacy research profile is not claimed to have passed. The archive preserves a verified research review and its limits.
