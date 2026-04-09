# Repolex Knowledge Graph of xiaojieluo/vlde

RDF knowledge graph data for [xiaojieluo/vlde](https://github.com/xiaojieluo/vlde), parsed by [repolex](https://repolex.ai).

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
lexq download xiaojieluo/vlde
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a5b20835639f0c6d42fc2fe1f42cbbe87d776bb2
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── a5b20835639f0c6d42fc2fe1f42cbbe87d776bb2.nq.gz
│   └── repolex
│       └── a5b20835639f0c6d42fc2fe1f42cbbe87d776bb2
│           └── chunk-001.nq.gz
├── blob
│   ├── 02ec079dbda9d6c17af2fc29131a0a25bff27837.nq.gz
│   ├── 0767d45d2a8e6cf89a7cbf2aa355d05591574884.nq.gz
│   ├── 10934c80c07ecac5ca810c16efcc298dac3eb0cb.nq.gz
│   ├── 220ed8aab7e0ba87984b4ebaf0291ef128c448c9.nq.gz
│   ├── 29a8b0fcbbf27a4be161e3c35f33cd06aca8e138.nq.gz
│   ├── 2c2961b7b4049dbfb6cd494478f47e2ce48e0d0f.nq.gz
│   ├── 3147a1c222b12b8d5155f81500323735f3284e54.nq.gz
│   ├── 34601ddbbd6b73110624cc9a3de523801f5edcaa.nq.gz
│   ├── 3757bfc3a7666beb2fee1e63766259e850cf139a.nq.gz
│   ├── 3fa7b471d1f094cd79c3dbf08991b401dcf9bef2.nq.gz
│   ├── 4307f0f72fc08560479a0e35e432406d328f5a60.nq.gz
│   ├── 43cb53341c7c9316805714d61dd8c6c40df08a9e.nq.gz
│   ├── 4d017fef1f1ce6976655df67fc411c6852fa768f.nq.gz
│   ├── 50574f68d617aeff80b9a0c112b861a84e9c12bd.nq.gz
│   ├── 515c6319328f5ef73447355d16ba2e7e1fb204b1.nq.gz
│   ├── 5263789e9bceba2eca6db0517ba881d1ec2e0cad.nq.gz
│   ├── 54bc279dfaa8ddefa93671e6cb93b11e051aa869.nq.gz
│   ├── 55c4208b60106b8954e4dbfd45f431f001565f2a.nq.gz
│   ├── 5ec19ea5e6d633bfafa79394e8f5316d6c49af45.nq.gz
│   ├── 633ec35b3a6f2304a9f421c2ca7d8ff2c2c1f1f7.nq.gz
│   ├── 650744ca86f9b1164fd4e73a6029e3f86b280ff0.nq.gz
│   ├── 667ec93d078dbb087ced006206e6c3a6ac42df18.nq.gz
│   ├── 7c547b733c54a60a3dcdd483823164a730b2a41a.nq.gz
│   ├── 7e07e9d5bdcbb11a9186a6aceab6c8dd8755d85d.nq.gz
│   ├── 8326b3e4ad4d82dca6757310a63d094e1c3f132b.nq.gz
│   ├── 852f01694c443ec47a654bbaa010ff21afb5d557.nq.gz
│   ├── 883d4f78371fcaf00a322eaa8f13b1253d075b6a.nq.gz
│   ├── 8ef0bb895857389356c9a734e2a96238678e8b8f.nq.gz
│   ├── 9bf952470c2cd5b3a927c53abb8ee0c82bfb2abe.nq.gz
│   ├── a2378baef2d3ad5089b103c3059264d3d53bb31c.nq.gz
│   ├── a5c4609028e61e9fad890e68087f1fde01091bda.nq.gz
│   ├── ba163a3b7f50561a9013bc6398fc1db2862b53cf.nq.gz
│   ├── bf94600760d6a805616b1fc56858407c7007fb63.nq.gz
│   ├── ca294b98e82ac2cf097ab53bbe48ae8b9783467a.nq.gz
│   ├── d21a2441f40dabd7ad37881e3e87e6ebe5f46f6a.nq.gz
│   ├── d35bb15a2c74bd45a19d7001765b86cdbcf8c47e.nq.gz
│   ├── d47f2716add651caac721dc53e985e44b9cefc18.nq.gz
│   ├── d626bc3b49d86ec5cb7b077da8003b5c8071359c.nq.gz
│   ├── e2714ecc08d6f1d2728933408a60bcb437a51f80.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e95b58790fac578d1d253342ea9dee8638a3a178.nq.gz
│   ├── f3c244c01e7a92fe93bab10b299ad534fe76d796.nq.gz
│   ├── f91c4b127b6caad6d110469df3f3876c5870052a.nq.gz
│   └── fa4d872b0b33166659b4d7018403564ccb0d31ee.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── a5b20835639f0c6d42fc2fe1f42cbbe87d776bb2.nq.gz
├── filetree
│   └── a5b20835639f0c6d42fc2fe1f42cbbe87d776bb2.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 53 files
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

[xiaojieluo/vlde](https://github.com/xiaojieluo/vlde)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
