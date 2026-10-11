# Repolex Knowledge Graph of jazzband/django-summernote

RDF knowledge graph data for [jazzband/django-summernote](https://github.com/jazzband/django-summernote), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-summernote
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8b17863d44ad1a588ea46d79203461275456e654
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8b17863d44ad1a588ea46d79203461275456e654
│           └── chunk-001.nq.gz
├── blob
│   ├── 00b0d129e159a39419ae3be1a50df8a564d67b54.nq.gz
│   ├── 05a135b387f4de862ab3e9121cac29a8d50feb7e.nq.gz
│   ├── 05fef57e00aa4734193bd50edb17c31d476e950b.nq.gz
│   ├── 0c0def5584a589d8b719f3ef463b4ed51f8ee008.nq.gz
│   ├── 0d1a258e3d2bd0551d35e1cb3ad4c5a1ca720610.nq.gz
│   ├── 115770c11d01f9c04558bc59778ce8f9048c9494.nq.gz
│   ├── 176fa645b41767759cc8dc1add3d1f2eb9e6ce4c.nq.gz
│   ├── 200f04bd7013664596d9e5581b72c08aa5949200.nq.gz
│   ├── 2619c70a31a241e2841e5904e5e1b213b2dc3e94.nq.gz
│   ├── 2e603d96c71a4ec256b0591e9a7b771864f1f723.nq.gz
│   ├── 35f6038f77bcf4134656c51836684e205779ffb7.nq.gz
│   ├── 41a615d45207f909545ec9acdc22e198e6c0be9d.nq.gz
│   ├── 49be6bd0d43712d7378a37fe44e93572e0c09b77.nq.gz
│   ├── 4fc4e91aeed39a2921c40199b8672d37609ab1f5.nq.gz
│   ├── 60fb4107e4d46235db6bd002c930d9cb19818803.nq.gz
│   ├── 610c49c1b9548df0093456404bee9bdd9bf3323c.nq.gz
│   ├── 61e4400fa74549e6c61fc9c38f1d922c6979bf26.nq.gz
│   ├── 637116137b370edb4f3b9a727472963648851f59.nq.gz
│   ├── 67580535ec6e1760d3c97aafd7d178071994cae2.nq.gz
│   ├── 69cda61403f2e22aa4ecfaf190759cbb66aa3e20.nq.gz
│   ├── 6a6d2d46a69b454f968cabf156fc07b9144ea76c.nq.gz
│   ├── 700f9013c9a1197ba328fcd6693d2d31f7a530da.nq.gz
│   ├── 739783f3d530b5009bf005c2d6d6582e50001d5d.nq.gz
│   ├── 73a0615ca502a93232e9c11e2a75ab72e035ab77.nq.gz
│   ├── 75036d03894c7ec8763a12e8e765d71d1aabe264.nq.gz
│   ├── 76537ce84aeaa215015d76b97d828569e1cf3cbf.nq.gz
│   ├── 768b6fbae1f1c357cc321ef3a8cad9aa44fa4608.nq.gz
│   ├── 7ce503c2dd97ba78597f6ff6e4393132753573f6.nq.gz
│   ├── 7cf3926f681a477484ef1272d76cf5982c9474aa.nq.gz
│   ├── 80ef8442bbe4e583f5017844189ad23e5044ea5d.nq.gz
│   ├── 82271cc4c542c013f419474328eb45f4c0ed23b1.nq.gz
│   ├── 84a858568279b01bc5253d25e59044ba5cc196b0.nq.gz
│   ├── 8d25c46415bf740195209d6291222e609324ae66.nq.gz
│   ├── 914b8ffb816d27035d854374af94c5fd3074830a.nq.gz
│   ├── 91ee803930b71d988b8d83320401ec7a967b3eb7.nq.gz
│   ├── 9473e5669233ec67543683486374134788fc5f64.nq.gz
│   ├── a159e4f49b0bd246d9a0e29c5b42bbc383640c48.nq.gz
│   ├── a3c11cca4946380453a9fc242e9f8a5ba0eb2457.nq.gz
│   ├── b5b65a5898eb7999ea7b5d63726d8f051739e293.nq.gz
│   ├── bd5e561df9fdc135ae3b9dc49dc42d8842fc34a5.nq.gz
│   ├── bf64729878ff865dd6ecc2018c100cd1e6c87f93.nq.gz
│   ├── c7677f5986dbaed8cba0446795c317fbb04b8b17.nq.gz
│   ├── cc342846a43af411a284b3672f51ac709dcd762f.nq.gz
│   ├── db585e6058bc5c60618a694cfc66b642e2a5614a.nq.gz
│   ├── dc74b663f24fe852749c59c185349ec5ed132afa.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6e4756dcdc456bfaa16c201d85152d61c2248cc.nq.gz
│   ├── e9fa7aad3da1da0eda42e7f29b90e168ccce4d61.nq.gz
│   ├── ef9757c67d86e9df712e3cfceb0193bc9e7f93a4.nq.gz
│   ├── f498c96db888844b32b9ef52f5c66f80c93b6336.nq.gz
│   ├── f79d0a454a66880edd1ab77b21e9e258277d2b37.nq.gz
│   ├── f9ec3628b5f22bc1f0e0da4fea7b75137dac593e.nq.gz
│   └── fb5d7a5fabd777d3c82016c5e8e5cc42f967acec.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8b17863d44ad1a588ea46d79203461275456e654.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 59 files
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

[jazzband/django-summernote](https://github.com/jazzband/django-summernote)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
