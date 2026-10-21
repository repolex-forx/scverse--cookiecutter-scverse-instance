# Repolex Knowledge Graph of scverse/cookiecutter-scverse-instance

RDF knowledge graph data for [scverse/cookiecutter-scverse-instance](https://github.com/scverse/cookiecutter-scverse-instance), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/cookiecutter-scverse-instance
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1e6d88555a09624a3d12b5bf3b38a97ce613bea5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1e6d88555a09624a3d12b5bf3b38a97ce613bea5
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ad6a6ea9418df96256615a564065e38c8332ea.nq.gz
│   ├── 04d594a89e747bbbcc411f422dca28c0ef88b3bd.nq.gz
│   ├── 1172c9cecd4e0b91c1543a63f84f5bee1063282d.nq.gz
│   ├── 199a50db86430f7faaa2640b334c2cc94e4ade15.nq.gz
│   ├── 1ed034700560543d00714a53af40ae2958fad583.nq.gz
│   ├── 322793040792b8440f6bb6db6e29660b8e54b266.nq.gz
│   ├── 34667562e06e9d6503b94a22bc983a3f0fa63970.nq.gz
│   ├── 36d1874618b1d0099c4d192c8a90500d69bcc723.nq.gz
│   ├── 4423c40fcf9874a65e88d7b260c486438e6eab29.nq.gz
│   ├── 46afebf75e721524fe68a2a327461714b1d88e10.nq.gz
│   ├── 527c6ab20a443ed9395539122d276ead53072b35.nq.gz
│   ├── 5b62547f9aef3da3a38806baf365ea8c059675d6.nq.gz
│   ├── 6313b56c57848efce05faa7aa7e901ccfc2886ea.nq.gz
│   ├── 66678e378b55a7e2b28d2087164af8999aff39cb.nq.gz
│   ├── 67eb948d72ad9ee53fd1cbe38e72bcccaa753334.nq.gz
│   ├── 6cca7d4d7e6abb71f96dcedb6fb5ebbb8ea0eb66.nq.gz
│   ├── 79f3159d158459e1b44ff47c1e6361b405b0cb82.nq.gz
│   ├── 947e6e7c86aaa40dc797018b4f5ad833a94011a1.nq.gz
│   ├── 95a32cd2c8cc28355df1eb4333bcae2521214552.nq.gz
│   ├── 9ce99e12c9d15d87eb2b5df430d8b75c37b786e2.nq.gz
│   ├── 9f5bed44ec106502c159a68e71e8308abddeb4f9.nq.gz
│   ├── 9f8f2208c4bdc0f0b0cafb4c0d0b5c79d32c32da.nq.gz
│   ├── a8a9b7a0d84f0f968edd20b37a6c9334ae1f0b4b.nq.gz
│   ├── b34d99cd977aa2c4506e8c17b4e344e687e1eeb5.nq.gz
│   ├── b626025a0eab85e35729d667d142e19b8fc87a09.nq.gz
│   ├── b8980c8552b3e905768d3b8e297250eaa49776e6.nq.gz
│   ├── b8c8d47fa0a99101c675af913b08144664399119.nq.gz
│   ├── bb3332d2277f5b392be89811a00f828d6674f8ff.nq.gz
│   ├── c2315dd043af11f4285f69ecbf7a506fddab1ec1.nq.gz
│   ├── c5f407cd5fd161a8344ac8d73a680a846d660fab.nq.gz
│   ├── c6bde623315959380d68df59b68f8202d552069a.nq.gz
│   ├── caaeb4f73220343cf55564c4b747c6434c231fd8.nq.gz
│   ├── cc32eda8a90cc20e1e9fdc7039b83be81e3d1445.nq.gz
│   ├── d0c0e2917651ab1d38f689317e32f463c392c3d2.nq.gz
│   ├── d215ade4fc570018fd911291a70622e9136dcc46.nq.gz
│   ├── d3781c1f1efccb26c4358437fded9aaf4c8265fd.nq.gz
│   ├── d6683e3a77bdeeafdcae8ca9be082318e7c2a4f0.nq.gz
│   ├── d9e79ba64848091a9bccd21dc241c61c669dad7f.nq.gz
│   ├── e034b91f7a78ad40b1349f103363131423841d61.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8d141e51d0cee6b072bebb3d97698c9ece8c8f4.nq.gz
│   ├── e9c82b9b44a22344e633c15d0e450ee02aa1f033.nq.gz
│   └── f08dcb3b06812df9e5941b8496c6afb8366299e9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1e6d88555a09624a3d12b5bf3b38a97ce613bea5.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 50 files
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

[scverse/cookiecutter-scverse-instance](https://github.com/scverse/cookiecutter-scverse-instance)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
