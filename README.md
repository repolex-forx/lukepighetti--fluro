# Repolex Knowledge Graph of lukepighetti/fluro

RDF knowledge graph data for [lukepighetti/fluro](https://github.com/lukepighetti/fluro), parsed by [repolex](https://repolex.ai).

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
rlex download lukepighetti/fluro
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c2bc0592ee4a3bfe9a9875f6f1debed1a0ad63a6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c2bc0592ee4a3bfe9a9875f6f1debed1a0ad63a6
│           └── chunk-001.nq.gz
├── blob
│   ├── 01b5058a9bcd834937546376d783e42cdec22dca.nq.gz
│   ├── 09d4391482be68e9e4a07fab769b5de337d16eb1.nq.gz
│   ├── 09eae35c8bb7c6207573da006007f0f2082b533f.nq.gz
│   ├── 0a741cb43d66c6790a2a913fa24c8878fb1ab7b5.nq.gz
│   ├── 1247ec5838c4dbc5332480320fa3cf2a51bec041.nq.gz
│   ├── 135987b3deef43a81de820c4cce3cacaa1763160.nq.gz
│   ├── 17987b79bb8a35cc66c3c1fd44f5a5526c1b78be.nq.gz
│   ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
│   ├── 197cdbaf1e4d033a34ec861b08b7349e07b9a20a.nq.gz
│   ├── 1985397a2cb27cc8073d7f6e8d03b82bff16adb9.nq.gz
│   ├── 1b4b85bb2ebafb7c9933101c90218ceaf9e03c9a.nq.gz
│   ├── 1d526a16ed0f1cd0c2409d848bf489b93fefa3b2.nq.gz
│   ├── 1f83a33fd4f2c45c5ffa5b6c1b729c431fd445fc.nq.gz
│   ├── 20788993193cfccf0d34a56eddc21c38523db128.nq.gz
│   ├── 21ecba29c404f89ce5d3892b8a1c08d6fd343085.nq.gz
│   ├── 28c6bf03016f6c994b70f38d1b7346e5831b531f.nq.gz
│   ├── 296b146b7318dd58663296dbb7555df9ff328ec2.nq.gz
│   ├── 2ccbfd967d9697cd4b83225558af2911e9571c9b.nq.gz
│   ├── 304732f8842013497e14bd02f67a55f2614fb8f7.nq.gz
│   ├── 308a2a560b42f17aaf3c36e4e9c8cd07182fbb7e.nq.gz
│   ├── 3100ad2d55532e58ed44b53dd3c2a04c5bcaf160.nq.gz
│   ├── 315dfea28f70cd4d7e8bcf63eea8e442f2a9d0d7.nq.gz
│   ├── 358a854ef8af37f8183dedd23b7ade4ea649c146.nq.gz
│   ├── 360f387059805097f4777a64c4050f990b0bacdb.nq.gz
│   ├── 369779cced75202d2830d9169b74a08b9d4c09c8.nq.gz
│   ├── 389b97dfe111e9e29ec3cf8f6a9bbf163337302b.nq.gz
│   ├── 3a0563351a09000c6d4d931fcb59e73adedfbfdc.nq.gz
│   ├── 3c5f5583d727456d31854cc4f192c1e6ca78065d.nq.gz
│   ├── 44e62bcf06ae649ea809590f8a861059886502e8.nq.gz
│   ├── 4cb5bbd6b9bdfb287617dc93cbd85e28feb83178.nq.gz
│   ├── 4cde12118dda48d71e01fcb589a74d069c5d7cb5.nq.gz
│   ├── 4d6372eebdb28e45604e46eeda8dd24651419bc0.nq.gz
│   ├── 4fe34fe74ab4afd60f83db290b9c289f5ce5ad0f.nq.gz
│   ├── 510d55ebff0d21a42cb7b4e2f2b94faa46164e2a.nq.gz
│   ├── 5432655d76bf31325e0b2db3b37b6aadc6d246cc.nq.gz
│   ├── 592ceee85b89bd111b779db6116b130509ab6d4b.nq.gz
│   ├── 63a4faa8a7f893c86264344a8cef72b588866f65.nq.gz
│   ├── 6a84f41e14e27f4b11f16f9ee39279ac98f8d5ac.nq.gz
│   ├── 6ad4656b014b71e85d47597c864e56da83ae4ace.nq.gz
│   ├── 6c57d455f98230f1022e9d8b4458c57d18ab0645.nq.gz
│   ├── 70693e4a8c128fc4350b157416374ca599ac8c7b.nq.gz
│   ├── 75b2d164a5a98e212cca15ea7bf2ab5de5108680.nq.gz
│   ├── 76d7e5b2fafff95c5b64e9b3b0c37e6795977818.nq.gz
│   ├── 78b4d33e3150ac6edb9fea6e862707600951b492.nq.gz
│   ├── 873bdcd446eada760a13f367402ee30dd697a319.nq.gz
│   ├── 88cfd48dff1169879ba46840804b412fe02fefd6.nq.gz
│   ├── 89c2725b70f1882be97f5214fafe22d27a0ec01e.nq.gz
│   ├── 8aaa46ac1ae21512746f852a42ba87e4165dfdd1.nq.gz
│   ├── 919434a6254f0e9651f402737811be6634a03e9c.nq.gz
│   ├── 940af6c28d16b9c21cad14ba55131fab67cb95bb.nq.gz
│   ├── 94adc3a3f97aa8ae37ba567d080f94f95ee8f9b7.nq.gz
│   ├── 97e05174704b2d18fa93d81f6370b389021ec51f.nq.gz
│   ├── 9910180837fbfffc392647fc32cb5e1786d34656.nq.gz
│   ├── 99bf1e73d6d8a954232183da8fcba7cf63eeae3d.nq.gz
│   ├── 9caa6a3178a24f5cd7167814abcce93a95f6d401.nq.gz
│   ├── 9d532b18a01fe4462df8fb637bb52d8dca822aa8.nq.gz
│   ├── 9da19eacad3b03bb08bbddbbf4ac48dd78b3d838.nq.gz
│   ├── 9f21567d6a330656ccc280661f4274d8fd0035c5.nq.gz
│   ├── a060db61e461d48fdefe09420ec872d06398cf3d.nq.gz
│   ├── a089fd6f23b79876c5d6cfc14b4f37b3da9c63d1.nq.gz
│   ├── a135626028224aae68d394c2da60bd48bb50aeea.nq.gz
│   ├── a28140cfdb3ff9b7a11a9497b84546d615db2afa.nq.gz
│   ├── a6d6b8609df07bf62e5100a53a01510388bd2b22.nq.gz
│   ├── a9a9d6c48cb218916c23afc4d99231f66879bd90.nq.gz
│   ├── af151396069794d9515c8559c6ac1cc2ea18d05b.nq.gz
│   ├── b46136a218767024824f2068e9109bda923eceb2.nq.gz
│   ├── b749bfef07473333cf1dd31e9eed89862a5d52aa.nq.gz
│   ├── bfe0dfd55b2829247bc402a00300de4ea17131f8.nq.gz
│   ├── c4df70d39da7941ef3f6dcb7f06a192d8dcb308d.nq.gz
│   ├── c6cd45965c1ef2d67e380f5518073632b1cb1fe9.nq.gz
│   ├── c718378c128441857f1267681fa52856e43ef7ed.nq.gz
│   ├── c8f9ed8f5cee1c98386d13b17e89f719e83555b2.nq.gz
│   ├── c979128a6724eb97a9595ed26af48dbfb2a5ca4e.nq.gz
│   ├── d0e1f58536026aebc4f1f70e481f6993c9ff088d.nq.gz
│   ├── d0ef06e7edb86cdfe0d15b4b0d98334a86163658.nq.gz
│   ├── d27071f7ee3e410035112b1ae2bb63da0299d580.nq.gz
│   ├── d4bc1b28c7ad09bc24c2c61d81a31579bb1b97f6.nq.gz
│   ├── d5f1c8d34e7a88e3f88bea192c3a370d44689c3c.nq.gz
│   ├── db77bb4b7b0906d62b1847e87f15cdcacf6a4f29.nq.gz
│   ├── dc9ada4725e9b0ddb1deab583e5b5102493aa332.nq.gz
│   ├── dcdc2306c28505ebc0b6c3a359c4d252bf626b9f.nq.gz
│   ├── dd70f59946021a7b85e6cbaf1a2b9aa4cdb8a4ea.nq.gz
│   ├── e18ca3073c2ba5b7eb0c93ee68eba9404aaaebf4.nq.gz
│   ├── e96ef602b8d172f7cd28ba656aac097f741c736d.nq.gz
│   ├── f091b6b0bca859a3f474b03065bef75ba58a9e4c.nq.gz
│   ├── f2872cf474eee0cc0439d4012e1a653ac08e9d0f.nq.gz
│   ├── f2e259c7c9390ff69a6bbe1e0907e6dc366848e7.nq.gz
│   ├── f3c28516fb38e64d88cfcf5fb1791175df078f2f.nq.gz
│   ├── f5a05560ba84ced8730d35ebf32c8e39a95a5e6f.nq.gz
│   └── f9b0d7c5ea15f194be85eb6ee8e6721a87ff4644.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c2bc0592ee4a3bfe9a9875f6f1debed1a0ad63a6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 98 files
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

[lukepighetti/fluro](https://github.com/lukepighetti/fluro)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
