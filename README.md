# Repolex Knowledge Graph of graphql-python/graphene-mongo

RDF knowledge graph data for [graphql-python/graphene-mongo](https://github.com/graphql-python/graphene-mongo), parsed by [repolex](https://repolex.ai).

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
rlex download graphql-python/graphene-mongo
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3b174a827f7d51659ea84cc8399f70f4ce9d82dd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3b174a827f7d51659ea84cc8399f70f4ce9d82dd
│           └── chunk-001.nq.gz
├── blob
│   ├── 07b8454766936f948addd297c09f1e6bd910e112.nq.gz
│   ├── 07c3c5d31c6b393311bd5115792b04bf7c4cbfe9.nq.gz
│   ├── 0c608b02c8b2b7054c1efa101ef559b70d257c39.nq.gz
│   ├── 0decfbee23c43fc37eca21e723b35ba631e004ce.nq.gz
│   ├── 157e1c10a2a219e484db2fca508c12c0783b505b.nq.gz
│   ├── 1653cd2fffd32e2ad6ea59e14f67f33d48afc170.nq.gz
│   ├── 1707ecd9b196a423d3e520481ab1e7fca77c88f1.nq.gz
│   ├── 1fc36b4bd70b80929ef6833f769f500df5fa90b3.nq.gz
│   ├── 20f6cd000740c075d887856b8ab33e618de848a6.nq.gz
│   ├── 216750fa45f97a6d1387b60db39e406bf0c4b9d8.nq.gz
│   ├── 228eaca5c9cbb9fd588ff331402501ab6fcf53c0.nq.gz
│   ├── 2ba31a639d837a4f787124c961f5cc2c984e89bb.nq.gz
│   ├── 2c42c1739e3cea7caccb6080472f897371c55a58.nq.gz
│   ├── 2fd7842fbab048e3154fa1c94a81712fb53b68ba.nq.gz
│   ├── 2fffccbce0841d34b1d252bdefd1bc03a70c3a60.nq.gz
│   ├── 329642313a57809c2b86bf1575182075fe83ec8f.nq.gz
│   ├── 32f10a8c8e1b2acc6b10d757e90d17274f92406b.nq.gz
│   ├── 356acad8250a327431cf6be909e959e71f892978.nq.gz
│   ├── 445f00bbf86052b9224f44f0d3b13a6ac416a48d.nq.gz
│   ├── 45f001777d5247a3042a93efdd205d7569f3f323.nq.gz
│   ├── 473010b31a983065b904b3a84fd6a0340f239235.nq.gz
│   ├── 479f29f7cd1c32225b482c84007fe5057a87032c.nq.gz
│   ├── 4809c9c93c8417d0cdeb0a75808bae7636b589c4.nq.gz
│   ├── 4fdcd01410109f6d8e0894889f0da9f77f852450.nq.gz
│   ├── 50f2d614ffc40081e30ce5f7007da553d62083cc.nq.gz
│   ├── 57319e84bec805a981495d5345aa5fa4da4d97c3.nq.gz
│   ├── 625e3e343b50b60f70c38ce4632351df4de11d08.nq.gz
│   ├── 65f8e227bd0892948125e4482f2135e0d5ea2b6f.nq.gz
│   ├── 666a8c9d48b3c536bdc0dcd35b5f4dddc8f8dead.nq.gz
│   ├── 6d37c53a88f9f28a1d3ffc7e87d88bf74e3e5b2e.nq.gz
│   ├── 6ddfea6181f208ef40194f406cc3cfcdcc0f2776.nq.gz
│   ├── 734fc625e535b4553916a276489f9ab1c15437a2.nq.gz
│   ├── 73b0614e326d37c9bfe949cf4c852e98e58b515d.nq.gz
│   ├── 798096d623580de38f53b3768888b5b4a96e75de.nq.gz
│   ├── 7c3aa2072dc78a26f8e385d4da8dd7434b0e5ccd.nq.gz
│   ├── 7ec3e41ca64ee878b7030c47db03220c9470ad19.nq.gz
│   ├── 80e0def7c54becba84fd8d6484e777afeac2386b.nq.gz
│   ├── 812157898115eee2779cbf46494443807454722d.nq.gz
│   ├── 82cd6d2da3b52cce76499daa66aa04692f940ebf.nq.gz
│   ├── 85a150562ec383ff15812e74c1bb885c5688c9da.nq.gz
│   ├── 8931d14c2dacc8172a734392f4a9739d093690b6.nq.gz
│   ├── 98e30fcee21e70e2fd444b393b6599f175b0cec3.nq.gz
│   ├── 98f747f4a9d1bd0358368eb880c93f798fd438a1.nq.gz
│   ├── 99552619e88a979886dac14f1a676fbae87cd498.nq.gz
│   ├── 9e7760b3b0b868f5eac615457f775256f16c612d.nq.gz
│   ├── 9f792ef6e6403cfd0947260e8272c38bfe47e97b.nq.gz
│   ├── a1630ca62a048ea7f857b194911fca2fc777c2ee.nq.gz
│   ├── a38635ce55fc41b701819498e05b983e12b14954.nq.gz
│   ├── a52031ea59cf619c689fca537e047484056b2074.nq.gz
│   ├── a54b348ef612175fb866eda7c1aa8546a66f73e4.nq.gz
│   ├── a5e7f17031392b16fe5051734ff10f27fa661066.nq.gz
│   ├── af21ab214c4907edb040c3d089081597b2f9fa54.nq.gz
│   ├── b111e4a6a567862db0104a1d8ef56ec8fe30c19f.nq.gz
│   ├── b18e988320ce1e0d766918218d6686f40ba66171.nq.gz
│   ├── b4731ff551ec589e808f40ababa764a1d439cc23.nq.gz
│   ├── ba520ccd879d34ec93a054b49222af7f38fe80f9.nq.gz
│   ├── bd98aac0ce633851a8f222b9b01810df7e581985.nq.gz
│   ├── be86032fda7992fb149be00751a9d2ff539f7b0d.nq.gz
│   ├── c58f55135f1cd5e46bed1740177d78cace9ae248.nq.gz
│   ├── c7f1810e7685b485758ce271957693b582aa2c72.nq.gz
│   ├── c887a51b15b858de57b9b4c1f9a3255d4d583d6a.nq.gz
│   ├── cc6bfe8e1cefa3286a20447d973084732ee11db9.nq.gz
│   ├── d62f9b7d7ed04eeb55a1695fdee276a2b4fef135.nq.gz
│   ├── d7cd1131d05abb557636af9ffad1e65d505d438d.nq.gz
│   ├── da0afcb214a05c9b662e547ecc1ef3344cd92170.nq.gz
│   ├── da73fd9790365fea5a4ee5bf5197e9abb78ea1d8.nq.gz
│   ├── dc09b4e3a69981aaabed6eb3590b6ba17eca8e46.nq.gz
│   ├── dcf9c4afbe60067bf31d60d5d6ba6adaeb5b80dc.nq.gz
│   ├── deb0f8af11e8cfed777d4981961fccffb796bd74.nq.gz
│   ├── deea45e001773b7493d78917abf66bf12302e5ef.nq.gz
│   ├── e6694fd5499b8881610032d0963da3bcb6bb2a19.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e82cc58dc51ed3f80d0c59de0c03013a8353c233.nq.gz
│   ├── e8b6c5bfbe43f197d7fe9d971a9f192d867574ca.nq.gz
│   ├── edf4ba7eca26cf1c44cfb8a14e8326ba85513ddc.nq.gz
│   ├── ee2b1c1804d139a84cca421a19f85c4e5f125570.nq.gz
│   ├── f24e711608c46f8174303daee1d2fa6e76adc09b.nq.gz
│   ├── f4ef0eb6d958c23c69a07e03a2721b47a0c8bf57.nq.gz
│   ├── f700105fd5de661002b9ad2d0cbe52f24d6f38c7.nq.gz
│   ├── f912902b383260ecda0a4cc6a6172dec2686b38e.nq.gz
│   ├── fa7bfcba32320770cce52f0d18cc09fb929086de.nq.gz
│   └── ff88d5fdf3e3eaaa304432fc7962f5fbac182403.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3b174a827f7d51659ea84cc8399f70f4ce9d82dd.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 90 files
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

[graphql-python/graphene-mongo](https://github.com/graphql-python/graphene-mongo)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
