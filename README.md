# Repolex Knowledge Graph of zopefoundation/zope.pagetemplate

RDF knowledge graph data for [zopefoundation/zope.pagetemplate](https://github.com/zopefoundation/zope.pagetemplate), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/zope.pagetemplate
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f0915eb8e0eb8fe2419a3021f54eed8075fa986a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f0915eb8e0eb8fe2419a3021f54eed8075fa986a
│           └── chunk-001.nq.gz
├── blob
│   ├── 0db0317ac6aadfd1d9f2735db9f3f3eb8adfaab3.nq.gz
│   ├── 0f68e50f520f477e61a0acd1f66a5aa55654e6e5.nq.gz
│   ├── 104f02be12735a2d9fe4f797a44346429ba3e739.nq.gz
│   ├── 1e18d235c9a8f5a53c79565abae329656df88aba.nq.gz
│   ├── 21827ba02e6839b6b28d456b9b68ae1c0d061d0c.nq.gz
│   ├── 2596a596db536ea35996d5d7cabb3da57d8bb7d0.nq.gz
│   ├── 360c6f9ebb1db2b20f1eb1bcf9e929d4c77c1b4d.nq.gz
│   ├── 37ff47a4287c3376da5c365fb8651a26bcc32755.nq.gz
│   ├── 4c2d0344d60722b4e686a2a548f8f8c005cdf9d4.nq.gz
│   ├── 4dbb723020f580c9a9da3fd3db06a5e6ebe493c2.nq.gz
│   ├── 56fecdb72a75c4118ba880431beb7a936ff2cef0.nq.gz
│   ├── 5b421c59a832e21f5f5b8add6e7e05605366a1d7.nq.gz
│   ├── 5cd2f27cfb96edb1751ffbb115717917eb9312d1.nq.gz
│   ├── 64bea915b349d0fdada719b04a8303e998abda5c.nq.gz
│   ├── 75ef47f0d6a37545b85976e5585fe6555a77530f.nq.gz
│   ├── 7639d3c3a0e7a415382fe3b6d40afd1f720c8f44.nq.gz
│   ├── 78ed9118cf4461d445db475c254d37f100669a4b.nq.gz
│   ├── 79859e06010bf4967c5b4b044afea6ef39742938.nq.gz
│   ├── 7c68916d36f15e9573b7e528eaeef2ea005b2212.nq.gz
│   ├── 8a1cde635fcfe005cc4438d504940505395236a7.nq.gz
│   ├── 8a804a46851363246667ca7b70b36699bb064b78.nq.gz
│   ├── 9372f642828d0b95819bda66bb6eb05fca08cc82.nq.gz
│   ├── 9f87ef321ae6301285dbc67a988e46be7927a106.nq.gz
│   ├── b5a0a91bf621796a34e2bc6940afad73a1b08b52.nq.gz
│   ├── b711d3609fdefd7664f2982d225d96f5e53be9c0.nq.gz
│   ├── b717a32cc6b3347a3b373fe8e0f895e96f7428ab.nq.gz
│   ├── c439cb706a10855ee8def726875468894acc047f.nq.gz
│   ├── c634bd6257977ab9c6d5de4c242f1f303d0ed4e8.nq.gz
│   ├── c63d6b8233c59907349e579220dfcf1707571c29.nq.gz
│   ├── c8cf99c367411872bfb721526600818e06a00e65.nq.gz
│   ├── ca517f4eb0cec1c691c0c2b54cd5eb85e906f11b.nq.gz
│   ├── ced592cead50ca882d4d3e21286df9cb5ea2c947.nq.gz
│   ├── cf3918170c5bad61e2f8b06719a21c878159e990.nq.gz
│   ├── cf71106df32df075f546c2055873e86457446590.nq.gz
│   ├── d6e501094746fee76bc5b0798f4ec0ece531077a.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── ddfa1d35c385452c6c1e1612a37efc815d98bd71.nq.gz
│   ├── de08f17bac9d8c77e1a768b0aeddcc3a46850fd3.nq.gz
│   ├── e11f6befba3523a8101d3a010bc6ff5a0603b7ef.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e4b867329e05886a4818f86b117fca2102bc84bf.nq.gz
│   ├── f354046c5bab170f767f08d0fd846c60106e9589.nq.gz
│   ├── f81cabf053fb4487bb3496afbc276556076bc3f2.nq.gz
│   └── fc9c7934df5b1b64da57ee706daaaaa7cf4054ef.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f0915eb8e0eb8fe2419a3021f54eed8075fa986a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 52 files
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

[zopefoundation/zope.pagetemplate](https://github.com/zopefoundation/zope.pagetemplate)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
