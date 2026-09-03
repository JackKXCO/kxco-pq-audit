# Changelog

## 1.2.3

### Corrected

The README claimed `@noble/post-quantum` was audited by Cure53 in 2024.
**It was not, by Cure53 or anyone else.** It is self-audited by its maintainer
(v0.6.1, April 2026), and this package has had no third-party assessment
either.

The other Noble packages were audited separately and at different dates, and
none of those engagements reached the post-quantum package:

| Package | Audited by |
|---|---|
| `@noble/post-quantum` | **nobody** |
| `@noble/hashes` | Cure53, Jan 2022, v1.0.0 |
| `@noble/curves` | Trail of Bits Feb 2023; Kudelski Sep 2023; Cure53 Sep 2024 |
| `@noble/ciphers` | Cure53, Sep 2024, v1.0.0 |

Dates from `kxco-post-quantum/audit/dependency-review.json`, which is generated
by `audit/run-audit.mjs` rather than written by hand.

Documentation only. No code changed and no behaviour changed.

`.socket.yml` said `@noble/hashes` was audited by Cure53 in 2024. The audit
was real but the date was wrong: January 2022, at v1.0.0.
