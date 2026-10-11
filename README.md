# Repolex Knowledge Graph of pydantic/reqwest-middleware

RDF knowledge graph data for [pydantic/reqwest-middleware](https://github.com/pydantic/reqwest-middleware), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/reqwest-middleware
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1485f61e20c8cd31cabb663788f06206c19cabaf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1485f61e20c8cd31cabb663788f06206c19cabaf
│           └── chunk-001.nq.gz
├── blob
│   ├── 0073ea68979779e0443c0c21fbdbee4119aa2d07.nq.gz
│   ├── 0086358db1eb971c0cfa8739c27518bbc18a5ff4.nq.gz
│   ├── 0754c15a2a661295d1bbb8c3f9289363b20bd1c4.nq.gz
│   ├── 0a87dcd3c9138f6c5a22d2b7640e965f0f22c669.nq.gz
│   ├── 0c0ec558091541897861a01c677d1045f30ab246.nq.gz
│   ├── 0c9abf9ba47e0527a4d9111149c3dcd2fbadaff8.nq.gz
│   ├── 15744a93ab8f06f033ca84a7faa837e109828e32.nq.gz
│   ├── 1b5ec8b78e237b5c3b3d812a7c0a6589d0f7161d.nq.gz
│   ├── 1cd8685bde5d604086b48970e1872f09f3a62e90.nq.gz
│   ├── 25b479281946754c9efbacae21e945793263c30d.nq.gz
│   ├── 2854cf5992d5a3ec8b67d7ff0926fded9b2c9eb0.nq.gz
│   ├── 28b7da73434ae0d0e127cc89b37732392d36b627.nq.gz
│   ├── 2de71ce791809ac371bc92a12c82d217081b6acd.nq.gz
│   ├── 36ff770f72a8e43f7a430ac9bf1257529ca305aa.nq.gz
│   ├── 3a75e4f748486711f3cdcd3876617c9b34840904.nq.gz
│   ├── 469cd726b61943ce688105b2c2a16db01af6739d.nq.gz
│   ├── 48285ec785f6cf1cede282dc4cc83c0f23babf06.nq.gz
│   ├── 54012abc2fa48d18bc8e5d2293db799b6f40c205.nq.gz
│   ├── 5a9d6ff8be23aa6296bb53c482749acc4250bfb4.nq.gz
│   ├── 76219eb72e8524f15c21ec93b9b2592da49b5460.nq.gz
│   ├── 77b228ca24e01f02ce7c1d37e36463edbb435d9a.nq.gz
│   ├── 78bd5ca72425ca1993272eef892bcfec0c6e457f.nq.gz
│   ├── 807ae9af89d645eefb9f06958f6eb0bfc44232b5.nq.gz
│   ├── 811874f7e8429b817b0f46e7ad659d44c78dd8f0.nq.gz
│   ├── 82412a68f5c1415bb8a535d4ff1d707920621154.nq.gz
│   ├── 85959d1f84f80c8cec2e7d6b44c70fae53af04a5.nq.gz
│   ├── 8a790c4ba4693af6c6e9a2f142912231c538fe65.nq.gz
│   ├── 965b606f331b51d566b46025f9ff311a7aad0c12.nq.gz
│   ├── 96ef6c0b944e24fc22f51f18136cd62ffd5b0b8f.nq.gz
│   ├── a8339c1cc6d1a71469c5af1b27ac2a2d6f093b46.nq.gz
│   ├── b6b3f304480a0b755fc44138f6a93d605eba9ad0.nq.gz
│   ├── bb7330ba195712f47047f50abd82ced4caa5e502.nq.gz
│   ├── bc1cde2abcdf949a8d7f02c741ac772e9adda05a.nq.gz
│   ├── c0ed45eb196373da0691d2d6db56b4fde75ddd2a.nq.gz
│   ├── c4bf50d53ef6fed52903fbff7a7539fdb935a838.nq.gz
│   ├── c4f1d190a97e633befe50a72e5c27229de90e644.nq.gz
│   ├── d13231a107f3d3b2a60902632125d6310e90bd20.nq.gz
│   ├── da6d249ecac48ae7342cbc3559cd6395d02c352b.nq.gz
│   ├── df106ad23a21181ceea991d5f289489a6158d991.nq.gz
│   ├── e4dda2b7442d6f7d2d053d24b87ed160e32a7bb1.nq.gz
│   ├── f034b084e35024cfbf08c9b95b0aea468d9b3bb2.nq.gz
│   ├── f242fdb8c5fc639b261d41156569702b0894c1dd.nq.gz
│   ├── f84f15973ed3caa5ec4bc818543002bd07568797.nq.gz
│   └── f8ac742c221c2b76291c3f10e465c4c7873948f8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1485f61e20c8cd31cabb663788f06206c19cabaf.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 51 files
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

[pydantic/reqwest-middleware](https://github.com/pydantic/reqwest-middleware)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
