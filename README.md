# Repolex Knowledge Graph of glyph/automat

RDF knowledge graph data for [glyph/automat](https://github.com/glyph/automat), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download glyph/automat
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1e64bf3da912e50a4eca40e7b9797cf2ab949e01
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1e64bf3da912e50a4eca40e7b9797cf2ab949e01
│           └── chunk-001.nq.gz
├── blob
│   ├── 01c42ef7956e0602cb930ebe61c49eff1009d083.nq.gz
│   ├── 0ff4dfc979b76f390949467e54bf3435becbe830.nq.gz
│   ├── 10ef15bb175f245bba492120e32fc9122a6301de.nq.gz
│   ├── 1805b5726879e0a69502667270d3408f2aa0dba0.nq.gz
│   ├── 235657d604c75d9ddac8d6837d1b89ff3a057988.nq.gz
│   ├── 26663533fd3d549aa1590197a5b699141529e581.nq.gz
│   ├── 2d679fe3c73179b6155fc65c5696e335f5c11621.nq.gz
│   ├── 2d6e1170e98be3337b3e88ca6dc0b2eab424a7c8.nq.gz
│   ├── 31dbf0d704ae126a6a14f5c1fb63ce6142bc100a.nq.gz
│   ├── 35ab174c229757b57a53b8e46a991d4d81a68e15.nq.gz
│   ├── 402b7c06137e84a8d1844cb8cc4eb7bd62126543.nq.gz
│   ├── 4ce071d6bb704951d33d59d0ecee428d84b5f243.nq.gz
│   ├── 4fea14c5f435caa4b7d07a07064d18d9ed9ee347.nq.gz
│   ├── 552059c503ecee0a49bf50abe0619bdbb12cea08.nq.gz
│   ├── 58c181cacc7358b2c9e1bdd089aaaea66c01b3f2.nq.gz
│   ├── 6533cf1cb0e6433344f8ba6c5f65a5864b6d390e.nq.gz
│   ├── 6e56b94aaee56d0510003533e1893eb9ae2495d2.nq.gz
│   ├── 768c1e3d890297591a480eb105bb2e2488e60d49.nq.gz
│   ├── 76f67acf9f0c34860f0c481323297d1ec40051b1.nq.gz
│   ├── 77868b6fbbdc3457eb63f55750f6453d1993940f.nq.gz
│   ├── 7aa504594d2ae55a33e16a69e5a81320be0a572c.nq.gz
│   ├── 7bcde5d96a3b841445c35e0a1cf3bb7cd88ddbb0.nq.gz
│   ├── 7ebc88a9da4692812b4cef2f4cdfb980a3f243db.nq.gz
│   ├── 80dec1d1e510a46d1b597d0035c4bac6df554432.nq.gz
│   ├── 90a03ff991cfb7dfac9d31ec1186e242f2339fdb.nq.gz
│   ├── 9773501b17d73f697d7d2013f0dd9fec72f72bad.nq.gz
│   ├── 9fd9898c984b2b22aded52508270ad91cebe0aa5.nq.gz
│   ├── a0592468348b56e4de295ebc6f8294561cc5bdc2.nq.gz
│   ├── a2b35e572670bb165b5a1f5fffe11174d041578f.nq.gz
│   ├── a95e1253452e2cfc9987ccc14761fded936bd61f.nq.gz
│   ├── ae1ca6e70f2388654420cd9ad1f2876c69c8a904.nq.gz
│   ├── ae92f82fc048e5d0df3f737a2d39edcddb69fc44.nq.gz
│   ├── c2e03d617e840f8f45da1e7bed2c345a698a7879.nq.gz
│   ├── c4b34e565ac9427272f7358f1c6f77074632b14b.nq.gz
│   ├── c5d9e128ed6abf1fafd3f4f716f27b71032836bc.nq.gz
│   ├── c76d69cb6f5cf9d7f3ef08ce703b861e9643ca0b.nq.gz
│   ├── c9c7409f5ab1025fe7bada7d7c6972822ff43564.nq.gz
│   ├── cc108814c2b8f3ba74abb57f960501bc1585cae9.nq.gz
│   ├── d2e19c66aea37bc33d8cd62268cfc7a33c5ce549.nq.gz
│   ├── d54fb0c41114ddf3bbbef3afbcfbac9abbefa88c.nq.gz
│   ├── e2ae8b3d159b7a7d4bfa8a11061f324fceba0d8b.nq.gz
│   ├── e433b2f9f9f7ed7283d61f77f63e4513cd22796e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eae95abb360d4368d988ed54213152030bb05cc0.nq.gz
│   ├── f2c54032b1a4362cc93d513005e6d0eb67965361.nq.gz
│   ├── f4570d907d9470be439db11802cfded9606e2701.nq.gz
│   ├── f52a1d62602cf1255e2564f8a1c8ea6b6cb3f578.nq.gz
│   ├── f6557f557ed2246100c11cd7e8bc7751f41777ac.nq.gz
│   ├── f80d27dd0ceb32e16d808a66d7e8f5fb4b305cc9.nq.gz
│   ├── f8c6d296c26be502ca23aebc2be28f18d36f9a3f.nq.gz
│   ├── f9c02a91750d18e64abab0adaf81ec3021b68d68.nq.gz
│   ├── fa0c7032a0c380dfdddc05ad208dfd898cea39cb.nq.gz
│   └── fc637b3a0f4f56224fc908b3666bfdaddd4dac7e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1e64bf3da912e50a4eca40e7b9797cf2ab949e01.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 61 files
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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[glyph/automat](https://github.com/glyph/automat)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
