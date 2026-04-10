# Repolex Knowledge Graph of shouldjs/should.js

RDF knowledge graph data for [shouldjs/should.js](https://github.com/shouldjs/should.js), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download shouldjs/should.js
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 38910f74a4e70f9f66b109241a41a2b3e7468fdf
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 38910f74a4e70f9f66b109241a41a2b3e7468fdf.nq.gz
│   └── repolex
│       └── 38910f74a4e70f9f66b109241a41a2b3e7468fdf
│           └── chunk-001.nq.gz
├── blob
│   ├── 04ce77cbf65cbe3a557b4ba3ff553481ccd7905e.nq.gz
│   ├── 074027af4df5216a8b7ee8191b899b4dd5215b3d.nq.gz
│   ├── 0b7a5062d40b3ff08f614fd0349771263bf94da9.nq.gz
│   ├── 10f27a225a36e6bf3901471eea5d61fa980bdbea.nq.gz
│   ├── 18923c3f8a885b961c606ac906a41a9d441de314.nq.gz
│   ├── 25289297daafab27b90e3d870660eccb9e4a296a.nq.gz
│   ├── 256196fd3f0c20cc28103e8c22a9585b409293dc.nq.gz
│   ├── 2ecfd8cb887aaddb61e71e91757c9c16226d6076.nq.gz
│   ├── 3483b21589440accf797745a4b361a8dae5a5ce6.nq.gz
│   ├── 35a17317299f371c4e0f46d07b50eafbce54d396.nq.gz
│   ├── 39130e36a107214527ed9e4b45e94287a7a14e55.nq.gz
│   ├── 3aa26a0c081528929c3a8f7711358842b454a2be.nq.gz
│   ├── 3d002c53ead18649610f5369a4c726cd2a21dfa5.nq.gz
│   ├── 3fb5638c07b910422a76c7b07fbc738f5e0b253a.nq.gz
│   ├── 43c97e719a5a824700932f72e6e7e6748ce45d01.nq.gz
│   ├── 47678f8ce01b17dbb295620b76c07b6de44a1536.nq.gz
│   ├── 49833e120125de87cc428541471c36c497f2582d.nq.gz
│   ├── 4cee32b81a0a7b6283ce8c0798c675663077cfb6.nq.gz
│   ├── 500a113e431229f79423869fae7c4166bbedf8e2.nq.gz
│   ├── 50c0d95967c54174340ebd4a8f84b529be281624.nq.gz
│   ├── 56c87dd3063b70294e81217675e471a5418fcfef.nq.gz
│   ├── 61b9a267116620cd2daa3ea87540379357b6c0e4.nq.gz
│   ├── 63054cd5569b352de63f44b83c69db24b3c415af.nq.gz
│   ├── 650f29427606cb6bab3c7e59a488625f4891df75.nq.gz
│   ├── 65ef72db961815e37ac0f55e4b08a3ec715314b1.nq.gz
│   ├── 6c89986a5f73acf50a8eadd9a7db9accf81662d8.nq.gz
│   ├── 7146d92bda9a66503f9e86e48be86177c586dfb1.nq.gz
│   ├── 7a3260205c46880400be22688dd7de85eced83a9.nq.gz
│   ├── 7e734f6ee77bf5699376a830671475288894ce0d.nq.gz
│   ├── 87dcef58cf57aea75abb8a9780e360533146e77f.nq.gz
│   ├── 8ca1036dfec57ee358d0292fba09feb053feae23.nq.gz
│   ├── 90ce4c0a72fdfaebb9174c457cbc35637397585d.nq.gz
│   ├── a3c7557865acf41a850e493a854dcff0bcc1d639.nq.gz
│   ├── a41267ba35db444766bddd64e7d94ffce0fb70a7.nq.gz
│   ├── ad5bf1d92b4e85bba3a261d3244ff091bad06522.nq.gz
│   ├── ae19da8375180c195f1d1d79ef9781c4107d855f.nq.gz
│   ├── b161748b884ff903ad1d096b90a5dbd12f67257e.nq.gz
│   ├── bd557abd24e7b6ff28f63ddbd54399661b6965af.nq.gz
│   ├── c4b2486604cf4d03b839b3627462b4f056c3e0af.nq.gz
│   ├── d3b526512e76a2bf01f3bbf24a8858312b3cb586.nq.gz
│   ├── d4b1f85ee120f541d80564ae4ccce8448493dfbc.nq.gz
│   ├── d56017b1bc8ab0870157d314f38230d6746c6a4a.nq.gz
│   ├── d73300d1878972df8bc7e50e69509d100c97d963.nq.gz
│   ├── de92cf24f1b8d89021ce5b536a10400385428170.nq.gz
│   ├── e0ab315253db5a77a271cb56557c3dbaa3de76c5.nq.gz
│   ├── e1f34acecb6e22e26732021bf4f0cfb3a559bc1a.nq.gz
│   ├── e2984982c5db2e823b033f637ad14c3d55c9f135.nq.gz
│   ├── e8638587e9fdff163c42e31daa161a330913add2.nq.gz
│   ├── e8dd144cc545ad86efe0371d8f23bb77ff40c9f5.nq.gz
│   ├── ea9297d72105b246de3c5f564d85d65d56a33c6e.nq.gz
│   ├── ece5b4d3761d6298e20d52dcc644b60d4f2ba6a3.nq.gz
│   ├── f24e0c097518202fc62126eecfbb088293ee6d61.nq.gz
│   ├── f7a98ed43a2e0ebade4185d6b6709487eae4ce7a.nq.gz
│   ├── fb8ad2501b0b47b8033b7ad967310e740685a477.nq.gz
│   ├── fc461b697f5b1d258abe6de5c49640da947cd85f.nq.gz
│   └── fc61e6783b710dec66b3b05f96df745993d4d6e4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 38910f74a4e70f9f66b109241a41a2b3e7468fdf.nq.gz
├── filetree
│   └── 38910f74a4e70f9f66b109241a41a2b3e7468fdf.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 66 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |

## Source repository

[shouldjs/should.js](https://github.com/shouldjs/should.js)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
