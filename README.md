# Repolex Knowledge Graph of psf/cachecontrol

RDF knowledge graph data for [psf/cachecontrol](https://github.com/psf/cachecontrol), parsed by [repolex](https://repolex.ai).

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
rlex download psf/cachecontrol
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2627d9b267c2032dad2db1f639f3c59329008f1d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2627d9b267c2032dad2db1f639f3c59329008f1d
│           └── chunk-001.nq.gz
├── blob
│   ├── 03ed78a79df6c4a7a9881f41f9831d22dccb48d1.nq.gz
│   ├── 048bbe96778ec486a9ccaacd862d0cd5ee226fb3.nq.gz
│   ├── 0d941b5448b911b29aa91cc54e92cb871d5ab898.nq.gz
│   ├── 18fe18d916351801a7aca91c5fb8964c31026333.nq.gz
│   ├── 2768533079f0b9a3332570ce54791b33427ac238.nq.gz
│   ├── 293e97304fe2f7668eb5d5dd3be1f09ddd756983.nq.gz
│   ├── 29e2d18c838e1e9b4e8b45bdcc3b70921f854ef4.nq.gz
│   ├── 2a5fd23b756f98e63634016dec6f78c8a3bb03e6.nq.gz
│   ├── 2ea8ba121cc5af6168d940dec7514732bf406928.nq.gz
│   ├── 2f1871feee95d460814f05f8b02204205588529f.nq.gz
│   ├── 37ee07c7b4eafa86cac16dbbd1dd53d35f8413d6.nq.gz
│   ├── 418f4570506f8742534528a886ffc6732bf6ab41.nq.gz
│   ├── 44a1af87db3c8db1fe135ef44e9d1e944410399c.nq.gz
│   ├── 473c908309ce1a6148d90ffcbdc97b77a1f5cde0.nq.gz
│   ├── 4a385b7de745b67d40201e1ddfb7a62b78ea6a34.nq.gz
│   ├── 4d3837ae5cb68d5a62bcbc8cf5d2e1d7ede3d757.nq.gz
│   ├── 4e95957c9fa28ddb2ac5be9d70cad2b2742b0097.nq.gz
│   ├── 55a56d0d876decc671965e2f9592ee2643ddd1c5.nq.gz
│   ├── 5aa0df35034f5a28131964afa2c5fdfca3affbf3.nq.gz
│   ├── 5eca8de77a6ab258f71f11afe39885da98e0a83c.nq.gz
│   ├── 62b2bfc440afacf440aa3d66b1bd736ea55da631.nq.gz
│   ├── 684a4a8bee66e5edcc8518526de9f5e436001ed1.nq.gz
│   ├── 6c9688cea7c0a6e96223c24fad7d7e5234c1aa7c.nq.gz
│   ├── 6e3f21bdcc97cae612af1c138aa0ab76183eab51.nq.gz
│   ├── 747420da0e6a87f4c8a5ea3b1d2d4ec7172f7fc3.nq.gz
│   ├── 74e4fb0f246da6aebbc8822095cde1e5a26ec39d.nq.gz
│   ├── 74f58e874b17abaacfdcc4c1ec4da50be1c03d58.nq.gz
│   ├── 78e8aaad23c5b3d32bca5d464e6bf892cbd8e5a1.nq.gz
│   ├── 7a72eaaec7fad64faa2bbc2690aba263e9d39187.nq.gz
│   ├── 8212df8f5e00175449f1055e105251c134b78eee.nq.gz
│   ├── 82b9c6f0ae5cc800ffdde31ab425a4dce5bd0b39.nq.gz
│   ├── 83bce07316968035307cf28e66334373f6a100f1.nq.gz
│   ├── 8a4f38e985ae5e64f32b5e1d8aea15e14957dae1.nq.gz
│   ├── 8bfb7e0edcea386862392054308fe0d771351637.nq.gz
│   ├── 91598e92034fa4f70353fbf7c9c19dc9558e320b.nq.gz
│   ├── 9d6932b26053fcc3f1640217c3570576cd279d04.nq.gz
│   ├── a8f7edd95345c44ae0f477539ddb37e081bfa8d5.nq.gz
│   ├── b049e481f585bcffe78d60814cfc60fbbb9528b9.nq.gz
│   ├── b0bf5bfafcd85f30ff7065dcc0960310bfe70551.nq.gz
│   ├── c02956c8cd83e85cd641bbe5f0969d920df1a8ae.nq.gz
│   ├── c26631cc179345803a5af7161658f52de487a604.nq.gz
│   ├── c8e0ceccdca7bc2e83fce71155516e2c36411947.nq.gz
│   ├── d1c64b458f96c990a9b901f64264cd6de0ea3861.nq.gz
│   ├── d23d74a66ea120d142b1b3144f78a9dc51b557ee.nq.gz
│   ├── d3e717711db4c9e2893f8a927bbf9bfdad825f32.nq.gz
│   ├── d8b3b56d361cfaa04de6304c96c328f27266f74e.nq.gz
│   ├── d95e78a9d2df0f9e75346c110b55f757d1c379fa.nq.gz
│   ├── dbcd9c4e4a557ab5ff77de2b4efe945cf4776294.nq.gz
│   ├── df5e7b4ad85c90a59c550b62e289743d39c5b027.nq.gz
│   ├── df74a3bd7c564150d9d2b4fe21380908c6ba8ede.nq.gz
│   ├── e5262bee609c38d3d890668059531be966917bf5.nq.gz
│   ├── e67668ef4009fb43de0cfd802a94772942d2dc15.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7ab444ac892e2308c7988be07045662d094d93d.nq.gz
│   ├── eab1c13fc01413d3d526acf988378b4026b9a59c.nq.gz
│   ├── f837d46dce0986d8af4d7cf4fa4da1a2661bc87a.nq.gz
│   └── fad0aad2b3621a5a49a0d03bd720cdc429acb1f6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2627d9b267c2032dad2db1f639f3c59329008f1d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 65 files
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

[psf/cachecontrol](https://github.com/psf/cachecontrol)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
