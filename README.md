# Repolex Knowledge Graph of aio-libs/aiohttp-asyncmdnsresolver

RDF knowledge graph data for [aio-libs/aiohttp-asyncmdnsresolver](https://github.com/aio-libs/aiohttp-asyncmdnsresolver), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiohttp-asyncmdnsresolver
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 238407713ace89a2efe4a50aafb2067cc77f5de4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 238407713ace89a2efe4a50aafb2067cc77f5de4
│           └── chunk-001.nq.gz
├── blob
│   ├── 07873b4f88e47560c860f4d4b0bd30c4900de980.nq.gz
│   ├── 07c839d0e4f38a9de3922c328a4063c7430667d3.nq.gz
│   ├── 08ea1436e80d95c13e2da21fbd81bae866f9dc16.nq.gz
│   ├── 09c21c0ed5ce3f09bef5f26e5fbd69b81058ecfa.nq.gz
│   ├── 0c5486590ed63013aa730e0f1bffc5950a3a3179.nq.gz
│   ├── 0f2804da83f0405e8c415932b52accf5529d077d.nq.gz
│   ├── 1194b906ef38680cc3a11b459b8feed8a83fff26.nq.gz
│   ├── 19702ba9d7f83290ebfb996006af3371f3c751c6.nq.gz
│   ├── 1a60db35d67cab99619d541b53591a625be9127e.nq.gz
│   ├── 1d66ccb0f99c10e09981443945ebdeb1af55464c.nq.gz
│   ├── 22645a5feac17773ad4c78c06fe7d1d0b1c309f8.nq.gz
│   ├── 23b0b96d8258b39a305e43d9a19151c9f8ae31aa.nq.gz
│   ├── 2879ab2fdd3580dd4a1f12acccefd0b9bdc09cc9.nq.gz
│   ├── 2a4069d37c4d37a33a62efd30c3a22f8e8857fb3.nq.gz
│   ├── 2acfb720f362432f1c935c68d3f8046d6816ebdc.nq.gz
│   ├── 2f4db689c135087e1df3ba7f17dbb5b0d011b1a9.nq.gz
│   ├── 38999593439fa47650ef8dc893469def97204f08.nq.gz
│   ├── 3ae7b535a49b57cc2943af836e087b7961bf8bc1.nq.gz
│   ├── 3c120040b4c52a1ce34b38dbbc16854f80eb8f5e.nq.gz
│   ├── 3c577fb0e0f7e6f41fcfc1322e43d7bcd2e59c60.nq.gz
│   ├── 43753d8c316e8aba7cf4606d1768dff2c4709a75.nq.gz
│   ├── 45d3b7303e191e4edc046904968c4f1d84907a08.nq.gz
│   ├── 493e5f09efb147e7fe1c75dfeb6cc95bf373561a.nq.gz
│   ├── 4af295010535fc95f92280fceff06c8842ad5e6d.nq.gz
│   ├── 4ff4630a70cc31dd3ff54cebc88c213eaf59f149.nq.gz
│   ├── 50812a4f909b00d8f66df6c71942faf3fbb1f876.nq.gz
│   ├── 59e3851dbaa9242e07e91825ae71ba3115842efb.nq.gz
│   ├── 60c742942316deb22607da9af51a35609ec54d46.nq.gz
│   ├── 640cf8a67ccdc99d7636b5654790582ded490ada.nq.gz
│   ├── 691e54d3ef6474226ffe5f74a4892a43eeefe73e.nq.gz
│   ├── 6dd107faab02eb6cc0d9edc058ffe6bbfc9879cd.nq.gz
│   ├── 6ec1c76f4f1b85332f022bafd2e729227d167227.nq.gz
│   ├── 798d143802a1439e718a15064729875815692815.nq.gz
│   ├── 8029a7678c3a9864931fa9ca11e4e1a384d8a77c.nq.gz
│   ├── 82cb77f057c170d7ad1dabad8f112596859f0198.nq.gz
│   ├── 8b71397bf1d018327930485a0e4a87d282147d33.nq.gz
│   ├── 8dfddea2483560b696f6dd3512d0305867cce53c.nq.gz
│   ├── 9409d1afad2ef37a12300c990857d058f3b6f5e7.nq.gz
│   ├── 9d011eb9ecd66d577f487cc37ef2c1eebbb472c3.nq.gz
│   ├── a371acb7094b812646af8abdee21f99457f7e728.nq.gz
│   ├── b0209721654bdc9ff7766f7757672a43e35c954e.nq.gz
│   ├── b261ca8e723ced7c7b8097486991b9952f61e9c2.nq.gz
│   ├── baccf40829b2887753d1c1e31d5151cf0d054172.nq.gz
│   ├── bb46e174b36cc419c615e4719f9f54066a628ec2.nq.gz
│   ├── c08a3922595a5d4fa5328d24b5bfff6edc9f1752.nq.gz
│   ├── ca4e630349b66b618f06e050af62e5057ca88ab6.nq.gz
│   ├── cbf45a5b8bb77bb2777884a4ad7728a1776a8342.nq.gz
│   ├── d3c25a7b7e7841f13e0ac4b926c031b19a48244a.nq.gz
│   ├── d41aa8df97f789ebd9791b6189f66c7d59ece258.nq.gz
│   ├── d4d721e121b16d76f5c2b4f371a6df2651c28deb.nq.gz
│   ├── d6409a0dd82d0c0350c0faed16e26120efb5adef.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── dcf2c804da5e19d617a03a6c68aa128d1d1f89a0.nq.gz
│   ├── ddf883c64bd5cd3ce8b2892470a2890db44ebb20.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9f94ad20698846283373e0c3b479f61cb325d7d.nq.gz
│   ├── ea8422775d2ebb42155a78bb74ee0a3c957f36d8.nq.gz
│   ├── f0413b8df561a9a49d8e0190fbca30dfc1f3b309.nq.gz
│   ├── f779f0457b1bfd6ec7d2827405e78a92080b781d.nq.gz
│   ├── fa6b74c8204cf405f744c469ad429c9606414f07.nq.gz
│   ├── fac2ffafe2ac48b3e5d3671482a14ae745a2ac92.nq.gz
│   ├── fd2df87043a1d49e83f0eb18d2a9053bd021317b.nq.gz
│   └── fecbaee691fcd93696bab72fdf9472051ef9ff08.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 238407713ace89a2efe4a50aafb2067cc77f5de4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 71 files
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

[aio-libs/aiohttp-asyncmdnsresolver](https://github.com/aio-libs/aiohttp-asyncmdnsresolver)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
