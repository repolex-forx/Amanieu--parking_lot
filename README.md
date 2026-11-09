# Repolex Knowledge Graph of Amanieu/parking_lot

RDF knowledge graph data for [Amanieu/parking_lot](https://github.com/Amanieu/parking_lot), parsed by [repolex](https://repolex.ai).

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
rlex download Amanieu/parking_lot
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 85827ffa2ffb0b60d416e2e2a091f36b0e8e5a91
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 85827ffa2ffb0b60d416e2e2a091f36b0e8e5a91
│           └── chunk-001.nq.gz
├── blob
│   ├── 01ee47124276dd20856ab2e96cc7437b82076222.nq.gz
│   ├── 0565239466a913c7ec86435bd0faf37a013ce2c8.nq.gz
│   ├── 0714ae9baa3739113dad9e31ce279b49d2853b7b.nq.gz
│   ├── 0760eae0f9dfd2b30a42ab0f4641c75b7d38c982.nq.gz
│   ├── 0b5833cd085bc78a16cbd716cd1fecb8225fb686.nq.gz
│   ├── 0eabf9f0aa9fea414fea6f5ca22ff25c6b9e8be4.nq.gz
│   ├── 118c17b996faacf06ddbce32aebfc43604ffaeab.nq.gz
│   ├── 13a216e71c20112de19b574ac068f80981df8b79.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 199b140a106b5008888ad9c5555cd950deab2e35.nq.gz
│   ├── 19c8427d73617e34b87449c75208648728627ba2.nq.gz
│   ├── 279b195d3905e4f0387d72fc26c5aa5b42beca79.nq.gz
│   ├── 30b41246a22f6aacbd4e3012a856ac8e8b42a6e1.nq.gz
│   ├── 372c2d3460df1dc17b8ce543e1a8e66032a51196.nq.gz
│   ├── 3b62282abfa0e98a7aab792d13a3d50a181ec214.nq.gz
│   ├── 40b8817a47beba464cd86e3f81260cd41b5e70dd.nq.gz
│   ├── 44056dbf4eb52d42163da7f36c8b34b134df74f4.nq.gz
│   ├── 445ff1e24fa279593decd730450df4512295b329.nq.gz
│   ├── 465224d6dd96747358cd84834c3929a5f498b42e.nq.gz
│   ├── 4b5fc25910e5a13c9d2d9a466a90d809e9fa1cc9.nq.gz
│   ├── 4dfe95b062c680b2f0ddee317ffa2e640ccd775e.nq.gz
│   ├── 592ff22e393e845172aaed126b3a31a99172bda5.nq.gz
│   ├── 5b09480b56a165cd5aedb9dd791a0be4b8cc990b.nq.gz
│   ├── 623d500d2f2e62b51a0a8e71508b0080630d0d6c.nq.gz
│   ├── 6293623051aa3470b3082de3f8adc1af18e136dc.nq.gz
│   ├── 63c408bdfe3c0d5fb24e9181d08232eeedf1f140.nq.gz
│   ├── 6458dbf71849a58dc216d2dc48dda0456079ac23.nq.gz
│   ├── 693342425b1a1ce72a210ddd18b0de9c8d5039a1.nq.gz
│   ├── 6e10f4adab4b4b9ef025aca460fa3158ac6e741e.nq.gz
│   ├── 70df819e07e267bd69816ce7c9b92c3692eb17fc.nq.gz
│   ├── 76c693a5f8ab946064353d6fe64df570786790f9.nq.gz
│   ├── 78a3858b3e89297d24a6870150e66553763ad227.nq.gz
│   ├── 808ac7dcc2894b22d6540a7ca47ae8ccb84a6cbf.nq.gz
│   ├── 8204aab88a476b09175d384bcf7c51bbf5985f14.nq.gz
│   ├── 84aaa6b0314006d4051a7b7d3be67cb393718ab5.nq.gz
│   ├── 872d35256b5879da9547899b7d73d6be7a2d1160.nq.gz
│   ├── 89f3d67b26cc5a461e94651e407a6e760fce7e43.nq.gz
│   ├── 970e5787271ec6b7e3b2418f6c0a1de612b48295.nq.gz
│   ├── 991aa6d5e6871a56915a675f0465a4df1fa29cfb.nq.gz
│   ├── 99338f89c389b5a0809b638e5fe36fce221e6de5.nq.gz
│   ├── 9c035954a52ab0e24dca215f60bf670fd62ed600.nq.gz
│   ├── a81230d50afa93a50d23832c2c8aa05a9ff82c00.nq.gz
│   ├── a9d37c560c6ab8d4afbf47eda643e8c42e857716.nq.gz
│   ├── ad47e4905679413ec6663b2d5741891512f5af7b.nq.gz
│   ├── b060bacbb55d0bd64c5a7fa674aa17a48769792a.nq.gz
│   ├── b152dadecfaadbf2e1815bf20e4c143c1db9f9a3.nq.gz
│   ├── b5342d414cbece06bbf0fd73f3c095599eb0eec8.nq.gz
│   ├── b72bdd680891491e3334a85ce995ae4ebacd6bf4.nq.gz
│   ├── b83b463b43cedbcfc8f9b551e4e520fcc124952f.nq.gz
│   ├── c0bb73e8f84bb8a32bf7113342c902acceea4e03.nq.gz
│   ├── c4d7675646801ec52944e4e647c3fdf866832edc.nq.gz
│   ├── c83c1aa400302071c411863b174c02d2a002e21f.nq.gz
│   ├── dee2e917490b396614e0babcd08b5046dd958993.nq.gz
│   ├── e7d67497d637925247d9f9abb3ca3863b965d952.nq.gz
│   ├── e9448c2b0be8b94568f112f292377c989b15a845.nq.gz
│   ├── ee46dc1cf2174edfc6d6d4ce39e5de50a7cd4ff9.nq.gz
│   ├── f2bb5a1b9a0b3328e0b9620341fdca8c214c0a91.nq.gz
│   ├── f6c4fd3e2f3816afae258970f491256fd54fafcd.nq.gz
│   ├── fa1c28135d2d10980f7696f766c240e08eb69927.nq.gz
│   └── fe99c34696b7bc4070dbeb561b76f8cfc0ba7bd2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 85827ffa2ffb0b60d416e2e2a091f36b0e8e5a91.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 68 files
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

[Amanieu/parking_lot](https://github.com/Amanieu/parking_lot)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
