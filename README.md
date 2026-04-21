# Repolex Knowledge Graph of apple/swift-metrics

RDF knowledge graph data for [apple/swift-metrics](https://github.com/apple/swift-metrics), parsed by [repolex](https://repolex.ai).

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
lexq download apple/swift-metrics
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f17c111cec972c2a4922cef38cf64f76f7e87886
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── f17c111cec972c2a4922cef38cf64f76f7e87886.nq.gz
│   └── repolex
│       └── f17c111cec972c2a4922cef38cf64f76f7e87886
│           └── chunk-001.nq.gz
├── blob
│   ├── 0776b8a0249ee99ac98e548953e3d18b44ca64de.nq.gz
│   ├── 08891d83f67181f147fc91135bf6c0016a2bea7e.nq.gz
│   ├── 0c1dcb12fde17414c35e3cd38ae2e85971a7a8c3.nq.gz
│   ├── 0dea419a7072ab7d595ba87f9e08b93a56e23b75.nq.gz
│   ├── 1dd4ac0c9cd15294a531b5b04a1e1fb158e8f6f3.nq.gz
│   ├── 292a03741f9428473479d38afb14212633d2e224.nq.gz
│   ├── 2a7f4c623974d9366a1a4c967c8d1dd519e63fa8.nq.gz
│   ├── 2cf0bc39e888bdc943cb449105e2266219c03be6.nq.gz
│   ├── 2daa6d048b1b8803e3765d980a5024ef474eabff.nq.gz
│   ├── 32413e4d86fe76f741a65a7943f7a9a3fc62b3fa.nq.gz
│   ├── 3bced0a7df3256a7f7a05abd072f1e695b0423a3.nq.gz
│   ├── 3c29c32c0d6b751a1c11c36602c3a2ab92ce98ea.nq.gz
│   ├── 3fab86527ada211f0a36531412d90eba4dcbe8f2.nq.gz
│   ├── 4a6af0d00d41efe0778a9f9b77c398973d56a396.nq.gz
│   ├── 4a86f888b7f74b248ca59e5bea7a35ea9ba671c9.nq.gz
│   ├── 534de0306f9aa9110be99f74c305410f420222dc.nq.gz
│   ├── 5edb56e934d7762d5914a37b63fec031fbd93202.nq.gz
│   ├── 5edf8056cd9eb70d0e07629393b8f144d93acb65.nq.gz
│   ├── 60968247518d51e254d95c1dff575935eb89e887.nq.gz
│   ├── 6943556756235a7f5b8f45a881e694d9a4cfbe09.nq.gz
│   ├── 7952658575fff48a9429d1cbb4f7b723c15bd1de.nq.gz
│   ├── 7b964348473c06ccd79832c2e89d40e1c8bb64e7.nq.gz
│   ├── 7c124393a442d3d1816cb92741f5e0a3c22893ff.nq.gz
│   ├── 7e8ae739104989fc85493cc72980741dcddc259a.nq.gz
│   ├── 7f4cecb38cfbe7c3933fafa73a2263a9e95c89e9.nq.gz
│   ├── 84ce6911160d07f92dfc97b468b08b644e2cee8b.nq.gz
│   ├── 8b4c6e644d788de2ba9009b6d47be08cc06e98ec.nq.gz
│   ├── 8b791379cf082a91daa8194349c78dc51fadee95.nq.gz
│   ├── 8d90a11798c37b3a122d840d7a2afe1b830f363f.nq.gz
│   ├── 93f4827681555b758cfd8c377508e37872b2867b.nq.gz
│   ├── 96f8abdd693a1f5b7a7a41631a04895c8a7a3b59.nq.gz
│   ├── a2ed3aa11c0eef305c96ab09486761361210f678.nq.gz
│   ├── a7c63b5b15edcf0aca39c4e4185f8a01658bb002.nq.gz
│   ├── aa1f39c25c754bd1850593a9cb0af3bf6dab2704.nq.gz
│   ├── ab90c7b9a1b5dce88c606d98a41c90f1eb85805a.nq.gz
│   ├── b10b1bf927c8b7d44c2e6357becbe4c07fd25fbf.nq.gz
│   ├── b289e96a26ebda86fc0d88fbe77fcd18c466d0f4.nq.gz
│   ├── b7442b0c62567246df644adb1e20d22ca17625b5.nq.gz
│   ├── bafdc7d115e2e5d094d3d13b54340bf6f9c9662f.nq.gz
│   ├── cc77f4e46184aaf8982723114d8bfca235cdfbbe.nq.gz
│   ├── d2da2f1aca37d8ad8d75f30a8ac6eab54f827145.nq.gz
│   ├── d3a526e1859741f6e34f24dfbce87505dceeb951.nq.gz
│   ├── d4976f56e06fdca5d3aff4abe72f277b291680eb.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d8ce6c93930b61c261dd076f28260f63e9a5534c.nq.gz
│   ├── e29eb84641301518c171ed2374bf1c36f8140e5d.nq.gz
│   ├── eb94e1c12d83743e38c485b0dc85dc3ee0b8bc3e.nq.gz
│   ├── ec5a2e07dcc03b57d4e98b76dc2db772d9ce3f1a.nq.gz
│   ├── ee91c8618ec12bd6c769190f2a2dddb75de60c36.nq.gz
│   ├── f0247ec1f27c1e999798285fe93537e1ea02e190.nq.gz
│   ├── f5d2edf51a118ec803fabea7e140c28077bab2c4.nq.gz
│   └── f90455fb9ccd8f4228200ce6dcb9886b8676cafe.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f17c111cec972c2a4922cef38cf64f76f7e87886.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 61 files
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

[apple/swift-metrics](https://github.com/apple/swift-metrics)

---
*Parsed on 2026-04-21 by [repolex](https://repolex.ai)*
