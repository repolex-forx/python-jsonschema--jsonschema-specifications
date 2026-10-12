# Repolex Knowledge Graph of python-jsonschema/jsonschema-specifications

RDF knowledge graph data for [python-jsonschema/jsonschema-specifications](https://github.com/python-jsonschema/jsonschema-specifications), parsed by [repolex](https://repolex.ai).

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
rlex download python-jsonschema/jsonschema-specifications
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5f06612cb443edbe54fcbffd1a7f4b6ccb574ced
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5f06612cb443edbe54fcbffd1a7f4b6ccb574ced
│           └── chunk-001.nq.gz
├── blob
│   ├── 020bb073528762b6af16516129b0ff39a09a333e.nq.gz
│   ├── 05cbc22afde5ebe6ba84957ca412277bde1e4b08.nq.gz
│   ├── 09bbfdda972ca77cd26e290d70ab59db4bbe8a27.nq.gz
│   ├── 18f2555b07151cefad42c14e445eb8db49a9739e.nq.gz
│   ├── 2248a0c80bbfc51b67863f848f60466f135cdb2b.nq.gz
│   ├── 24a1cc4f4f54b5a556de93c2799853b31e78e512.nq.gz
│   ├── 28475c238a1c7266abeba611dc6789317d740a3b.nq.gz
│   ├── 2f6e056a9ac2399582eaf05985a26acf9161f213.nq.gz
│   ├── 306a6a441a5218632b367f6d6ada051a3bf095ce.nq.gz
│   ├── 327f9c7dd61c5843e4748b9c425e434159f88ca2.nq.gz
│   ├── 366649163fb50b50dd4295f0692320398913c91d.nq.gz
│   ├── 49c99cfa318afdc3fd5b39c66276fc5c90e8cfe4.nq.gz
│   ├── 51ef7ea118c34e8ac3da66c973bae02b9e8325d8.nq.gz
│   ├── 56d02a9a21358cd38ad48707f4ea62d30df65525.nq.gz
│   ├── 5ace4600a1f26e6892982f3e2f069ebfab108d87.nq.gz
│   ├── 5e73fd7571e504990f7a055da960056f07dcdb19.nq.gz
│   ├── 5f62a3ffa20be07dc813d6b8a154fa8451d0dc61.nq.gz
│   ├── 606b87ba2ec213d63b9e2035a6acc4edcb4b8357.nq.gz
│   ├── 65162728331f0fad6db32d2e5a2f206cee674c82.nq.gz
│   ├── 746cde9690134529bdcde889f72c7ad5259f24ad.nq.gz
│   ├── 794a0e3169af7c0d1a3eb78056c1c8aca50fce62.nq.gz
│   ├── 82f927558a3dff0ea8c20858856e70779fd02c93.nq.gz
│   ├── 8b26b1f89f9852e4f69f466dd7d718b21ba5b989.nq.gz
│   ├── 93cedcd122487421101d9bff69700604bae9b36b.nq.gz
│   ├── 9d1e0987bfc323000b570d680343f00c53ddbc3d.nq.gz
│   ├── 9f59677b30c238f07a358c0c8ee72c3b710dc24d.nq.gz
│   ├── a0d2bf7896c2619ae657cd3b3266660156021706.nq.gz
│   ├── a4235741bfdd251e270ce3b26fa7fb1bf4044b78.nq.gz
│   ├── ab56e1789f24dc6e33a58f3df2a817a76092cd85.nq.gz
│   ├── bcbb84743e3838fab7cbec5f0a5bcbafcfc99136.nq.gz
│   ├── bf8bfab600fc4af26622fe579224b0922531160f.nq.gz
│   ├── ca69923096f3a2e4fe5eb8152a92d87d146cf021.nq.gz
│   ├── d3526bab34071873e8dd87de2ed045a5471cc42e.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d5e2d31c3c88e61f4c204cb6616887bba7e105dd.nq.gz
│   ├── da04cff6d346f26bfe5bd21b636609fecd583628.nq.gz
│   ├── dfc092d9646e1ea89e4d771bfcf2a4ca87eeac75.nq.gz
│   ├── e67bd712b3732f20ec353ba1d8b5c806fad2c74a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6ab173033afe698f1751c9227758f949059f22d.nq.gz
│   ├── eb708a56044146bb7903fd59159725a0c693aefe.nq.gz
│   ├── f6752a8efbeb74a7b7b2e74cbb272c422a975363.nq.gz
│   └── fd2927e0c8381f3eb93029df155758c05ed5eb26.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5f06612cb443edbe54fcbffd1a7f4b6ccb574ced.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
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

[python-jsonschema/jsonschema-specifications](https://github.com/python-jsonschema/jsonschema-specifications)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
