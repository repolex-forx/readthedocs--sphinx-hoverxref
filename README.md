# Repolex Knowledge Graph of readthedocs/sphinx-hoverxref

RDF knowledge graph data for [readthedocs/sphinx-hoverxref](https://github.com/readthedocs/sphinx-hoverxref), parsed by [repolex](https://repolex.ai).

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
rlex download readthedocs/sphinx-hoverxref
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 96ff768d56367d103056ebdc8fdaece10d0a1d99
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 96ff768d56367d103056ebdc8fdaece10d0a1d99
│           └── chunk-001.nq.gz
├── blob
│   ├── 0170576dd86771c94cc9e3c39c2f7bbb2da4338d.nq.gz
│   ├── 01ae588727190051755ee974a58146d5958dc4fb.nq.gz
│   ├── 03360d774663f94d5d630adf44164c1ac8f1beaa.nq.gz
│   ├── 04bf31626861426f29a8afe4f492290e57bed9c2.nq.gz
│   ├── 068554f89998edf8b4d7bf8de70efa0e36909519.nq.gz
│   ├── 07888999cd5a041bcc83ea51556de8ece8cf895e.nq.gz
│   ├── 08cb1eed128b98e99407a116d7d3014767e7829b.nq.gz
│   ├── 102b4b58bcf3dd209f091793204b863e6c92e62a.nq.gz
│   ├── 1a36c352d5683b427375afd35aacd89685990e35.nq.gz
│   ├── 1ece6b447c618dc34e0df9a9515d7c50bba11fd8.nq.gz
│   ├── 202319a50eea87d350ec69dd616897cd05da765a.nq.gz
│   ├── 2407d3f0702c9f1242bcf370b7ed4744a9fa8a2c.nq.gz
│   ├── 283587abc113a971ce241ad84ffa05f9052cd348.nq.gz
│   ├── 2bbdf0064b8c67a18c823e67f373e33a6c769a9a.nq.gz
│   ├── 2d4e57ce9d32b8ef8db18289ed5dbae39acbb446.nq.gz
│   ├── 2df34a06d939fbec53c3aec73eb54a8223fc30c9.nq.gz
│   ├── 2df71d31bec0c7fc9ed63fdcd6cdd7abdbcacf77.nq.gz
│   ├── 318266871038e3873353943d70d62c214b4d70c7.nq.gz
│   ├── 36d027bccc93b319bc52520e9027689e4a6ec0cc.nq.gz
│   ├── 3b48311f64cb8227eafcae7b8e0b7c646df53ca6.nq.gz
│   ├── 3d6fbfdebe0272230ea3e170383a3e616bcd447d.nq.gz
│   ├── 3ef107584278653cb30fbea4f4fe60657431aa4c.nq.gz
│   ├── 4461a286b29225d095f9be77bb04ea59d9637285.nq.gz
│   ├── 4e612d0092601dd7bf28ba26514e4609d8248e8f.nq.gz
│   ├── 4ea70a164e3853ee7bba9523335f3a9829dc704c.nq.gz
│   ├── 568bd156dfc06670a54dc169062048aae186a284.nq.gz
│   ├── 5b04be730bca4a2e56b5c3a6f446d5450e17be2d.nq.gz
│   ├── 5d54d50716c1233f5620cad90417087f455a3f9b.nq.gz
│   ├── 5d6040cf6a7b1c6181180c54b886e591015afaec.nq.gz
│   ├── 5f0a88c7ac0dc6acb45dbce607463feac56e1b25.nq.gz
│   ├── 69225ebddbec05254ce0ef4841d11d6ee8a1712f.nq.gz
│   ├── 6b804d97444d592f88add821ea9509507b7f583d.nq.gz
│   ├── 6bf55dad0f6b16b459dafd3a7a536364bb97f2c3.nq.gz
│   ├── 6e37debabf83ff46054a4670cd642f87f696cd32.nq.gz
│   ├── 6f60d97d7668a82e57fe3270b311d47133fa4855.nq.gz
│   ├── 747613a34d0e6f99f26f2ab30eb18e217af28318.nq.gz
│   ├── 79e6373ffa22d5046630dc1c3502f8971f9a81bb.nq.gz
│   ├── 7f26e7639a8832ebd30b815066e8ea4c8ee71e00.nq.gz
│   ├── 8072c7daa765280be14f214246b151da21f03b66.nq.gz
│   ├── 8294ece93053991766699536e398c07c5567a96c.nq.gz
│   ├── 86e1f17c0ec44e5f132360dac127bb53fd2f4b57.nq.gz
│   ├── 8bc54d6600c608aba8e09846f4be401cdc12f5ea.nq.gz
│   ├── 8be9d662d2132f6aeea6f4bb4f1edae585677f20.nq.gz
│   ├── 93d5354788d69d2d1e23db107130f4294926d04e.nq.gz
│   ├── 94dcbb1b5153ec2c25e9ba9b7e617c0fb386553c.nq.gz
│   ├── 964f3aa6aa8671d3174b3f56d5c5e1a3fad979a0.nq.gz
│   ├── 9a2e7e26ae896c59bfc69bbe3cde2eb23682de84.nq.gz
│   ├── 9ebbbc1c59782a3d90d828e82f0feb3a62891d66.nq.gz
│   ├── a0ffb291cb3800923df8ff412b1863ad9a78967a.nq.gz
│   ├── ae32e47a6b881c43ccf2bf645455a9de8570f801.nq.gz
│   ├── b0af5b072a85186e388b50e12db78ee4eb461033.nq.gz
│   ├── b2f330a887e025067cc823ac80778fbb9097add2.nq.gz
│   ├── bacd2b49e6da876388391ac273c4891bdd50b72d.nq.gz
│   ├── bafab7806c0321b3c38640a42aab4be3ad5d8908.nq.gz
│   ├── bffc51faf20af7778e17676d9ba5f8ad4a35bfd3.nq.gz
│   ├── cadfa74df98d8a99f39201c449cb62057481d3f3.nq.gz
│   ├── d17bbf85938bc98a7ee6d96ae8d4bccf0b97007c.nq.gz
│   ├── d3323977f5dea829563ccc777b8e2315ee126779.nq.gz
│   ├── d88f7f86c0c8a73566c068cc7eb6eb00c69d51b4.nq.gz
│   ├── d99c2a596e5ff45633404e0e22a1e3a7c7843c26.nq.gz
│   ├── e476b3bee3d2101fa9870884e61bdf92c90b67ff.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e92b23d76ddf9ca27fb98ac460a917aecc8994df.nq.gz
│   ├── ed2581e2ea3eff2609a00979fa8c6f75aadcd724.nq.gz
│   ├── f3e3b5f514e2fdb9cb73c1d7bae1a69a598f4bfa.nq.gz
│   ├── f70372a780cb2e3f2555a74d7f5606662af33b61.nq.gz
│   └── f8c052dce7cd46da3534c19115c116f78b57be52.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 96ff768d56367d103056ebdc8fdaece10d0a1d99.nq.gz
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

[readthedocs/sphinx-hoverxref](https://github.com/readthedocs/sphinx-hoverxref)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
