# Repolex Knowledge Graph of es-shims/Array.prototype.findLastIndex

RDF knowledge graph data for [es-shims/Array.prototype.findLastIndex](https://github.com/es-shims/Array.prototype.findLastIndex), parsed by [repolex](https://repolex.ai).

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
lexq download es-shims/Array.prototype.findLastIndex
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e037a525a28d6694481a76db2e8719542b7505e2
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e037a525a28d6694481a76db2e8719542b7505e2.nq.gz
│   └── repolex
│       └── e037a525a28d6694481a76db2e8719542b7505e2
│           └── chunk-001.nq.gz
├── blob
│   ├── 109ac788f50a83147b774ff30d49096dd899d238.nq.gz
│   ├── 1893e1df7c6f079aa238a57e780dd2e2ffd6b803.nq.gz
│   ├── 2e1a39451492e2b778072fcf28b9f03868ec7f49.nq.gz
│   ├── 335819ff93010b9ed485ee8d972da1cf9060ea10.nq.gz
│   ├── 40680dc46440def7d07ef1702e0490a87cf3a125.nq.gz
│   ├── 46b30a09e3acbc6836b4a2ae79c5e66147657c6a.nq.gz
│   ├── 4d7e3f8c7c6a77e97b68ef6597edece458721efa.nq.gz
│   ├── 5dbea324206c789fce1c811f23ea0e9784cc654b.nq.gz
│   ├── 632b5fb54f2a3e035ab5b532c686521b1ac7a2e5.nq.gz
│   ├── 765edf7976cabf5a72e6a914b149e5fa59208667.nq.gz
│   ├── 7b842f897cade8a6c74c8fd31dcf7f3ea6dde599.nq.gz
│   ├── 7fdf95b7da1a541ef76ccf4f576a323b2c97097b.nq.gz
│   ├── 8ebf606cb02ff3a8c6ef786afa37d21a19254f46.nq.gz
│   ├── 8eeca77479ec8b4f621507bd4cda44d7692366e1.nq.gz
│   ├── 8f85d0f87adf82b973f04f1db0eac61f045f32bb.nq.gz
│   ├── 903ca8873d1518418a933c0fb43d2e43d28364be.nq.gz
│   ├── aaf59dc3e4764837b4ea80332de1d3f6d249de85.nq.gz
│   ├── af04f070f9816d49988249f37e36e47cbdafe580.nq.gz
│   ├── b49ceb1f392731314cdc0ccb5251eced995cff22.nq.gz
│   ├── b9e1712fc4ff57c7474816f1b7f9d7ecfaa85a12.nq.gz
│   ├── bdd626ce91477abbdd489b79988baebadbd3c897.nq.gz
│   ├── d217f52cb70ab0d5c90c3a8b45ab2889d3d05a3c.nq.gz
│   └── f3cddd855d8a3502bea7bf76aa911f6b789f295d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── e037a525a28d6694481a76db2e8719542b7505e2.nq.gz
├── filetree
│   └── e037a525a28d6694481a76db2e8719542b7505e2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 33 files
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

[es-shims/Array.prototype.findLastIndex](https://github.com/es-shims/Array.prototype.findLastIndex)

---
*Parsed on 2026-09-15 by [repolex](https://repolex.ai)*
