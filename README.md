# Repolex Knowledge Graph of jaraco/jaraco.text

RDF knowledge graph data for [jaraco/jaraco.text](https://github.com/jaraco/jaraco.text), parsed by [repolex](https://repolex.ai).

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
rlex download jaraco/jaraco.text
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 080a0367127ed86c2e1982ae4bd3c1086084927f
│   │   │   └── chunk-001.nq.gz
│   │   └── 3c3aa2c70e85fd25d0157d5699f0b1c72d57b349
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 3c3aa2c70e85fd25d0157d5699f0b1c72d57b349.nq.gz
│   └── repolex
│       ├── 080a0367127ed86c2e1982ae4bd3c1086084927f
│       │   └── chunk-001.nq.gz
│       └── 3c3aa2c70e85fd25d0157d5699f0b1c72d57b349
│           └── chunk-001.nq.gz
├── blob
│   ├── 05007d63000b38e98b8da451a11a1dff5ca08932.nq.gz
│   ├── 0b4d6d262b502e93ba5b1e928f9cfe434e3bd64e.nq.gz
│   ├── 12ca363b32d11fcff92c0d81fd4f2bb0adaf0267.nq.gz
│   ├── 1f2aa7533b0423a8eb943f6f4ec02498e39581a0.nq.gz
│   ├── 2a91f7bc2915bb1a51d396a6d24bee207bbb4809.nq.gz
│   ├── 2e3f4dd791a6372b427d618eb0baa8c4dc58e5f0.nq.gz
│   ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
│   ├── 34254d0cc98530f1de7e8ebe6819964daa380b68.nq.gz
│   ├── 3e25d8de74ab8fda6ab52f5738a715fc54cf3a99.nq.gz
│   ├── 4afba03b3f502d52af013a3a9ed67a4314bc1c3d.nq.gz
│   ├── 4b823871994a584ea3576aba213fbd24e5819fb1.nq.gz
│   ├── 53513eee9b3a2f4df50df1febd59a5206718995a.nq.gz
│   ├── 54c9000ec94341dd65c2053251b85b124017b9b5.nq.gz
│   ├── 54cc8303b22089e12053e552d4e6cb852a865b8a.nq.gz
│   ├── 54f99acbfac68c2be8283174ea64f1730a795e49.nq.gz
│   ├── 577e87a793a20e413f7321f4f17ec1eba2ea1962.nq.gz
│   ├── 5bdc232005af9be104a00437ae9bc64417a4c1cc.nq.gz
│   ├── 5c05f9e27d57a4b7a3c3a9fdfecf8cddb8be499f.nq.gz
│   ├── 5fab99b9997adc7ae142c1bd1077bd84de9526ae.nq.gz
│   ├── 63c0825f6bd49615f4f386b95463111f7992f6bc.nq.gz
│   ├── 6f8fd4602d72d721486a591fd907a6a9ceba8b58.nq.gz
│   ├── 6fd2eb2be6c6883b471190e8483564a9ca03c29e.nq.gz
│   ├── 700235be57c1b2872455c0be5333f59cf568e252.nq.gz
│   ├── 724370638fc188317bbc7dc868f1a571995fd796.nq.gz
│   ├── 755fef77ce4a9218833d5525f09f1e8b02ed320a.nq.gz
│   ├── 7ad0cd4262483c0e21544257f3a06bf09c9384a8.nq.gz
│   ├── 7db7b688e0d6f04190d3c514bdb410e1ccf8f543.nq.gz
│   ├── 7ea90682eaf9c4951209b3a5615569ada6efefe2.nq.gz
│   ├── 8f563a05fbaaddb3a72f75b6a69e85e21dc967e8.nq.gz
│   ├── 986f944b60b9900c22464a0c027d713854cc204e.nq.gz
│   ├── 9a0f3bce1395ae3819030b822e5d9076c85068ea.nq.gz
│   ├── b4e0a957c5e891016a5fa5811686a45c51184515.nq.gz
│   ├── c51aa20de3b84d443ab926416f10df3247213676.nq.gz
│   ├── cb5539992daae716e410d868b77086f7adf3fc16.nq.gz
│   ├── ccaba91b505b2432b9e8858659b8268bd32cc6e6.nq.gz
│   ├── e43cdd1abeecd02a36b7f97cdb222a22767a2b26.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e95f59bddb1b664468cb5f9007b8165b1e9a127a.nq.gz
│   ├── f21f54251159188a430dc212d9e06f4ba66e2be4.nq.gz
│   └── fa5592412f13835ef19d2517513c9f5c4af96ead.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 3c3aa2c70e85fd25d0157d5699f0b1c72d57b349.nq.gz
├── filetree
│   ├── 080a0367127ed86c2e1982ae4bd3c1086084927f.nq.gz
│   └── 3c3aa2c70e85fd25d0157d5699f0b1c72d57b349.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 53 files
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

[jaraco/jaraco.text](https://github.com/jaraco/jaraco.text)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
