# Repolex Knowledge Graph of mkdocstrings/griffe-pydantic

RDF knowledge graph data for [mkdocstrings/griffe-pydantic](https://github.com/mkdocstrings/griffe-pydantic), parsed by [repolex](https://repolex.ai).

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
rlex download mkdocstrings/griffe-pydantic
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f9fb33d0d2b99d87cff05df2b411298add26bb5a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f9fb33d0d2b99d87cff05df2b411298add26bb5a
│           └── chunk-001.nq.gz
├── blob
│   ├── 002b2a0406a2be01fdcfcd78c4a90218458ac9cd.nq.gz
│   ├── 0416bac59cd477c16e27548fe06440bdfb00b600.nq.gz
│   ├── 0536cbbe261b2d97ed3d94f5b1fd86596a2ae486.nq.gz
│   ├── 06561170259792fecaf5bb795db2a84515a2728c.nq.gz
│   ├── 0ca7fabfe18b401de8974a8668482dfddfb3b9e3.nq.gz
│   ├── 1181fb9260622c27054a7870bd824da18c6d8b0e.nq.gz
│   ├── 16a775181119dafb15fdadef684a45944e8b3a29.nq.gz
│   ├── 2110554616dd384611810bb31d27819e8efcb6bb.nq.gz
│   ├── 2540e583c3f68dec71761f9bc6275d2b4c8c36f6.nq.gz
│   ├── 276c7e5e06bcf6635c7eace9cbc8092145f978db.nq.gz
│   ├── 2d46305a68da4b9569bf6813f4d2fb1131653842.nq.gz
│   ├── 2df98fbcac88d8d93c9d18648ba7d5a800100ce0.nq.gz
│   ├── 2ebc813840490ce5079c6e9d870f68a17e38204e.nq.gz
│   ├── 2fca2cb37d4fdd964d1dbc9f167dab1b59a6980b.nq.gz
│   ├── 2fcf869f97e3db32d04bba2de14fc59596538076.nq.gz
│   ├── 30571233ab2743c8bfa278db17f69b884823c94f.nq.gz
│   ├── 339b998fb71a079daa5a472608af3075ec8ee8e1.nq.gz
│   ├── 35ec8f1917b21691560159f7e6051600f0674f58.nq.gz
│   ├── 3fd20fc55109a974380272e7c6f6993a0cea2f11.nq.gz
│   ├── 451b9c1e80f24d1d38af03acb1f9c76b8ba64ce5.nq.gz
│   ├── 461f7e3d73ca89f0dee46d673a8057f563b9873f.nq.gz
│   ├── 4f4365e3faa50e4414baff554f10981d296e42f3.nq.gz
│   ├── 51587578d052005002f5e1f131bfeb180807caed.nq.gz
│   ├── 52f9a35ffb1292e8f9638f12f21256c1b45968fe.nq.gz
│   ├── 5b25a00f43bcb9d2a68e49250995865e6608c26c.nq.gz
│   ├── 61935e5d49e2b4f90babe55d6bda7b7401cfc1b9.nq.gz
│   ├── 67c5a4d1b1afb77c1f3e0810da42b6226094dbfa.nq.gz
│   ├── 6f0f2faf32486394750d5d5421e2261430b73fef.nq.gz
│   ├── 73145eec7e2a896212b2a9165dcc7449f0abd318.nq.gz
│   ├── 7736b1411bd021fcbdff85eb4770f41de472ef1f.nq.gz
│   ├── 812789e68bf5688ca56d42a80caecd04c1e0c4b4.nq.gz
│   ├── 88dcf3b34357ab3b525c45b06ae1caea1b0f3dc6.nq.gz
│   ├── 92ac8ec5dbe177b6e29da9600c7c3fd18d8069b9.nq.gz
│   ├── 975b5155b41e7a36c392dcf7ab0f7d690967de33.nq.gz
│   ├── 97724fa80f2fd81fddb1eb8b00029dc4fee78054.nq.gz
│   ├── 98cbfdd106f6af898b9ceed1ec1f707b532c5173.nq.gz
│   ├── 992067455421dcf8e6f203ccfff2c163ce145e51.nq.gz
│   ├── 99ec77cc7ef234a8dd0f90a5ba4c0863d496a866.nq.gz
│   ├── 9cdf0d105b6f2d275b83a42c38be432c2e41afde.nq.gz
│   ├── a09379f1b6893041a9e5249ae2b8e054b532cd23.nq.gz
│   ├── aa5b9353a8c285c9f99a18608e3fc11293aafe76.nq.gz
│   ├── af9994d6f85215923811f009f7c420d98142b9b6.nq.gz
│   ├── b0b6cfb610ffd32a139880af91e5c7eb2b4e13ce.nq.gz
│   ├── b149d0120334ec19001efdbd479598561952c3a9.nq.gz
│   ├── b56a2866c098400c2cdb660aa908a99bfd0cba34.nq.gz
│   ├── bbdf8f0385cd60cf10483ddbc4c8fc1604069266.nq.gz
│   ├── bff5612b8ce64f4701977407e7d85f48822731ad.nq.gz
│   ├── c2eda0df52a5c1bd708ad342b50fcc917be81192.nq.gz
│   ├── c4a180a3325cd3b07f80af8b9720a194260373a6.nq.gz
│   ├── c73a5948bf31c7912eed008cea9fde06631535c3.nq.gz
│   ├── ce322bf4c570b8c232905dc9114f779e9dcd874d.nq.gz
│   ├── dbf280a72275304e6cfb537c568419daf37a82a0.nq.gz
│   ├── dc711a48b9bd2f8029f3af22e74526a2cb8661f3.nq.gz
│   ├── dc9a8f17c6e3f0117661042120c4413a21065bce.nq.gz
│   ├── e3d28b38c94eeb9fa2ea0a955d3ff31c8c3ef6e6.nq.gz
│   ├── e58ecef3df7206cebe6e2edfd37032ec8a9ad4b9.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6bb5b91b56c550fab69e0f2898006069366f3da.nq.gz
│   ├── e7ae1593789cd1b0c1fde4eb4a8c1fc41137b60f.nq.gz
│   ├── e9376b75662b8c9276cc058ba59656f344a65bb6.nq.gz
│   ├── eced5a108a973acef9662890e39e143331c5dde2.nq.gz
│   ├── ee3fb5f9e35e065662c8d9bff9b230384d856686.nq.gz
│   ├── f072271cb235e97740a9887ebc76955c62749a18.nq.gz
│   ├── f3fda630374339395fd2c6375e0613f1812dced2.nq.gz
│   ├── f4a561740597e2681dcb446d9b3458aa12cc4993.nq.gz
│   ├── f6ab1aa2cdbbb6aa245be35e5090520815c3f7ef.nq.gz
│   └── f97321a5d0ecc1a536fc3eeca5a23f446efb07bd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f9fb33d0d2b99d87cff05df2b411298add26bb5a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 75 files
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

[mkdocstrings/griffe-pydantic](https://github.com/mkdocstrings/griffe-pydantic)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
