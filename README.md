# Repolex Knowledge Graph of sunpy/drms

RDF knowledge graph data for [sunpy/drms](https://github.com/sunpy/drms), parsed by [repolex](https://repolex.ai).

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
rlex download sunpy/drms
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 68eec28d4d17155d8e29725f29883991b6a77dbf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 68eec28d4d17155d8e29725f29883991b6a77dbf
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ec98a87b0551eb184637eb774bd2e7b0af2470.nq.gz
│   ├── 01018791e023b798c067bcc096016f90b3ffc234.nq.gz
│   ├── 08a458b00054cbbb05b344c80cd77714e798f72c.nq.gz
│   ├── 0994c60d2411a2e3cf82073a409b01665b4bdf28.nq.gz
│   ├── 0ca7902a8e358599b3a604cc4eb2e2e9d798d217.nq.gz
│   ├── 110d24e4e7dbb2cd0df948555ee0e9cd178829ac.nq.gz
│   ├── 13ad6ba7be7b74961b49ff584cf869f1b456819d.nq.gz
│   ├── 157c265b0ab6589866495c5107c638e16452589f.nq.gz
│   ├── 15c3234fb4946fe014fc701fe8bc44117eb2c9f7.nq.gz
│   ├── 1c5944c34982578ae0279e4ae1adbe528d7ed913.nq.gz
│   ├── 1d1e82db61115c380f65673b551e3f23c3131c59.nq.gz
│   ├── 1e7c95e1f33b6a0a937f8579939ccc1d7cf87c02.nq.gz
│   ├── 201426e7415289adf6f7282bfa3e128968c5f23c.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 27120d5de13c2563dcc3f4dfe57f5675de31659f.nq.gz
│   ├── 27a99baee6e0ea78fef2636295896cf14d2925a1.nq.gz
│   ├── 3250e31d8b120511cee4fb99eba20217edfe0d31.nq.gz
│   ├── 34fb6098617358a544a4b9732dae75f81c97fa8f.nq.gz
│   ├── 3662cd5b6def8834740d9a145996fb37dcf0d3f7.nq.gz
│   ├── 382f6e7693a2a0f3d078984f7e227a8757462a84.nq.gz
│   ├── 3d1529aafb7873116bc9fcc76e0fd6a5d2810d1d.nq.gz
│   ├── 3f8a40d0e8c983746454e8a99641ae42862fd4dc.nq.gz
│   ├── 419e648a1721b85986154b68ae78bae7882656a0.nq.gz
│   ├── 492cadc3503ff9afc8ab36cd67c187f6d808f43d.nq.gz
│   ├── 4a3530fbeb043b6de3acbfd721d09ca1ef4a24bc.nq.gz
│   ├── 4d4ed0fbae99c908d3902a39fa8b7a5785e4259b.nq.gz
│   ├── 4ef7af8f142f1cfa70674ad0849494da4e215888.nq.gz
│   ├── 4f2cd5731c5fad3c05da9fbe9c54265f348ced34.nq.gz
│   ├── 500824ee0332386301a8a7a193690fc71faee66e.nq.gz
│   ├── 56aed20f1026c79efe13bd6a93f784f9e9325d43.nq.gz
│   ├── 589c6f1b73debd94bdb6428a8d7173d7b67f68c7.nq.gz
│   ├── 58fcad2675d758fd855bb41e4ce9ebe83546a124.nq.gz
│   ├── 5e0adca951be086c185f82bf41d3bc7ee165c21d.nq.gz
│   ├── 622e97b3f86ac5423c876678ab3a6e48c72f2cf7.nq.gz
│   ├── 6492c4a2fecbffff50ace4f1a41a758943dc514c.nq.gz
│   ├── 6514beb0d6589983ac61bb71fc4bb3da6b8813a6.nq.gz
│   ├── 65ea74d1e51c47579adf74def592fdf47baf7f50.nq.gz
│   ├── 6d988de173d8c28a6116aa10f4977f5899f9c34c.nq.gz
│   ├── 6f4b77856e048ee418c3d5ac5296f19e90d0ae6e.nq.gz
│   ├── 72eebcaafcdb0b9512dbf0d67ee215aa859ef95a.nq.gz
│   ├── 73872a169114f1a8920e4c24d371a0a1878db3fe.nq.gz
│   ├── 770b614fbb6acc546c19744fe41a6270b6235bc5.nq.gz
│   ├── 7863f8a5859db9441c2ec32c82284c9c7095170c.nq.gz
│   ├── 79183a10f68f0e9358958edd409f6a158a741e54.nq.gz
│   ├── 7a032cfbfd57bff7930fe03d355c5e1bfa4c2cd6.nq.gz
│   ├── 82540655ad9ed7fab9a965856b5a1d23e74f9339.nq.gz
│   ├── 8483b687c9af9137f07df7e9e57e84e57df011d4.nq.gz
│   ├── 89d4dd8a3ba6313e95500048da00594ac66f05c2.nq.gz
│   ├── 8bb126f4fac09aeb53a579607722d2bbe45e08f0.nq.gz
│   ├── 8d71fb55ef68415412045347aaf9276d9bd536f4.nq.gz
│   ├── 8e0ec59067141fcdb5bcf47c93191f2dbcd338e4.nq.gz
│   ├── 8fe09b731963a1272a62a3360bbf019ea563aef2.nq.gz
│   ├── 92ea707303e3d1f4b6fc3bb3446d173c4f8d3c10.nq.gz
│   ├── 950508545fd93cbd26036674edcc90c31b5ddd3b.nq.gz
│   ├── 9559a2f92ffc50d8b84dbdff111d741d8725dd91.nq.gz
│   ├── 979fd04895793c0bd01cad40e9546da0ee06b053.nq.gz
│   ├── 97b913b9fc0009abe6cdbb81e7b8968cc0e31e54.nq.gz
│   ├── 993876bc400153f2b47ee62d963d0048660b632d.nq.gz
│   ├── 9c4b3282d3a1aac3bc6e23ff5eedc1067b9c4fdf.nq.gz
│   ├── 9dc512b97b0b0d73f81cfc0570bc9f73bb9010cf.nq.gz
│   ├── a0f9eabfd62025a749bd38dc2a9482972278efa5.nq.gz
│   ├── a31ca21fa37a6005d37446988ee26b8594235d5f.nq.gz
│   ├── a5da52056a6e338640ba6716abc7d30f39814bfb.nq.gz
│   ├── aedc909aa66eeb5cc295adcae872d8e16a9c8aa2.nq.gz
│   ├── b1a8174711abf64c83a9e161d7b6ff1d71184ff9.nq.gz
│   ├── b60b8c75f008abf03908f72e755abbbd3410f877.nq.gz
│   ├── b66a0740e1ecc20b4121be469509704a3a06a636.nq.gz
│   ├── b82a3fdd3a03c86bac32fceef7570e5959843f58.nq.gz
│   ├── c82334553632d12caf96bd3d3d332d9683d2635c.nq.gz
│   ├── c9ec8f10e6d533bdc5e55ee43efc8afbbfc1c4ed.nq.gz
│   ├── d0c4c1f13174282ebcd4b1fcd189e1938f154179.nq.gz
│   ├── dac2b3bed8e509b02ff633ab1eef28d6d4a63a2f.nq.gz
│   ├── dd0408f94415c41523295287a425e2327e6c20f9.nq.gz
│   ├── e1463f0880c06ac9a0c3ca704743dd3bf7982fab.nq.gz
│   ├── e1cd2698369971a76d021f624cf3318b194f8f6a.nq.gz
│   ├── e5316824948983ece2bd8b0668db1f0d229b3882.nq.gz
│   ├── e68050be9930014ccb7fb56214df22a2d29127f6.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6e4fb2f3da8e52d1605f8473d281396fe11228d.nq.gz
│   ├── e7eb5331f7221271d61b460e5938d5ca32a1327a.nq.gz
│   ├── ea0c6334f1f47df552790375940c8a50537b6dd2.nq.gz
│   ├── f0c8b7d38080028896c3ce778d69da1e5b44256e.nq.gz
│   ├── f343335361004274389ba9ea46867100e3f4815e.nq.gz
│   ├── f536a3ebce624db7cd85c23c7c278582743fced8.nq.gz
│   └── f651bc72554871c6678b7868ab68dda594be2042.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 68eec28d4d17155d8e29725f29883991b6a77dbf.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 93 files
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

[sunpy/drms](https://github.com/sunpy/drms)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
