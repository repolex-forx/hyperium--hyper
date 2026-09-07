# Repolex Knowledge Graph of hyperium/hyper

RDF knowledge graph data for [hyperium/hyper](https://github.com/hyperium/hyper), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download hyperium/hyper
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0d6c7d5469baa09e2fb127ee3758a79b3271a4f0
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 0d6c7d5469baa09e2fb127ee3758a79b3271a4f0.nq.gz
│   └── repolex
│       └── 0d6c7d5469baa09e2fb127ee3758a79b3271a4f0
│           └── chunk-001.nq.gz
├── blob
│   ├── 00642f83799e7c7a2b997c26cea2e7fa04fded37.nq.gz
│   ├── 0412aa775c23593664bc3c4575cf84dd3604f13d.nq.gz
│   ├── 0452109c3c7a2932a278e43711d7a4f6e4678b2d.nq.gz
│   ├── 07f08c186bb60d3ca3fbb7a782e5c5e9555cc152.nq.gz
│   ├── 0af623b1bf915b5f87f3ae56d2747eeb0146d4d5.nq.gz
│   ├── 0c49936c6ecc79e2db17e07414ab14b67ad24030.nq.gz
│   ├── 0df7d73658939967b041a23cc79f2f501a60c03c.nq.gz
│   ├── 0eb266974f7b3324a02317676f633eeeed07e091.nq.gz
│   ├── 0f26efb8bb8a08cea4dbdb4a73162d9764fccd80.nq.gz
│   ├── 144349e5d7c193dd97da10060c0820c594e01588.nq.gz
│   ├── 14c3d243c804db7798a6e19bee2de2c21a5d2792.nq.gz
│   ├── 17284a7542ceaaa88d8b23581fe4e8d92110aa7d.nq.gz
│   ├── 1dd57de319ebb0e51e1b560536bc413f390c72f5.nq.gz
│   ├── 23a83c1f024f8c7a031512dbc372a584923d29ce.nq.gz
│   ├── 23abc6275d7e405192cdff53178294559d6e8124.nq.gz
│   ├── 24e9557830f59f4a4ad34994ab8c878e45579950.nq.gz
│   ├── 28ffaddbabb27ac14aaef7dc0cf8a7a998f7ada1.nq.gz
│   ├── 2deee443f8fa7941da92ce7ee4da6008600c48bc.nq.gz
│   ├── 32b8d2852852c91e458cc34e3f59a77d94100bac.nq.gz
│   ├── 3373021bf744f8e61e3f6da3cd5bde27759599c9.nq.gz
│   ├── 34769cf930601a0df3e3298034cd0b4b6350d285.nq.gz
│   ├── 38b2df1701a00f4e2c8c858d18ec407869fb4ad9.nq.gz
│   ├── 3c436edbe4a8cc2ec915ffe9b9e06100b3052f59.nq.gz
│   ├── 3e017a782cf87feae0cb3ffd8f78d78500b04f0d.nq.gz
│   ├── 40a98de08a402fd4c60363867340545c89934024.nq.gz
│   ├── 4683fd65977a4bf228ee847f1d062875a738d076.nq.gz
│   ├── 47fbb8da20e8628fbb342386796d624a23212376.nq.gz
│   ├── 483ed96dd9eb051759763dd05e61297a9469cb60.nq.gz
│   ├── 4952e3851898038ee168563bc9eb213580384800.nq.gz
│   ├── 4a326d913b64e9700e6e0bf641a587df4d0a90e2.nq.gz
│   ├── 4b73437203a9904e0c99f174c514e9ffcc90e509.nq.gz
│   ├── 4bf44e6513fcb0ef7673e3d2f2665e3e299490fc.nq.gz
│   ├── 51e6c39ca7196933eab2755f7376dfd638c54488.nq.gz
│   ├── 520743884039942265e39d2386ecb0febcb9a24d.nq.gz
│   ├── 5263efdadcc9d7e0ff9a0c6f6d181331d25acbec.nq.gz
│   ├── 54b309e88e97fd4dc2be852fb2f745061a69abd5.nq.gz
│   ├── 57a3e7b6c71044a2a093af73c0933dd7977828c3.nq.gz
│   ├── 58712b0f27fb0f648f867843f50058878f688aea.nq.gz
│   ├── 59837cd60ec721824d39c0df03b78ab8ec9fe652.nq.gz
│   ├── 598d240b606014f3087c34fd26fd708154c3024e.nq.gz
│   ├── 5b6f48c6fae4580045308bf7d1c1523ac41b21dc.nq.gz
│   ├── 5daeb5ebf691d5537ec51ec29de13fc5ae531924.nq.gz
│   ├── 60d03b368d612ad3f9561b1bdb81dfb7f8d5b6b1.nq.gz
│   ├── 63b03d874ad75eeab5fd897531e6ff154c478d4a.nq.gz
│   ├── 651fbdf40d12f8baa75faae0c5512a55fe31fa41.nq.gz
│   ├── 66043e1cb3382f7ff262f2447f62c63ddebcd290.nq.gz
│   ├── 67d88988f8daabad4a991d1a294ce888807e8a2a.nq.gz
│   ├── 6a30d73c84bf0265cf51e4b98f01d3b4f869992d.nq.gz
│   ├── 6a6753528c3ecb14f66b9828d785b2fdc9277ed7.nq.gz
│   ├── 6dbc8672e0edc7dd655c0d87538fabf46b52e432.nq.gz
│   ├── 6e9d3742cff1cd62e698704d004525eab5d308ec.nq.gz
│   ├── 70752c91381164ad196b0372fb24f1bf59753bc8.nq.gz
│   ├── 71a5351d213fdc1e12c009ac9726c22cb026d7fa.nq.gz
│   ├── 72d0bd7a208b7d567e3501ea7398ba8de5dbf472.nq.gz
│   ├── 750c86ec2daae645a5b938767f3a5406faf32217.nq.gz
│   ├── 75b103d0990c537bade8bf0e22e4d6a69dfc6c40.nq.gz
│   ├── 77907e671662795ddf628644917e8fe8f128fa7a.nq.gz
│   ├── 7b71d98be4aa9ef972f69c0d569efe0a3fead22e.nq.gz
│   ├── 7c0c2586fd17094c05ad7a235c9c9af0ce5773c3.nq.gz
│   ├── 7dbf7104f7c69f3044da1fd666e65dabf206cadd.nq.gz
│   ├── 7e6024557ae25550855ecc4d58d9df65a62db9ba.nq.gz
│   ├── 810ca7e64b41d96aa12b10b234ccdd20b013d8a2.nq.gz
│   ├── 81acd5df70463218c9c634c503fedfc0135879e8.nq.gz
│   ├── 85c1fdc66592bda87a7b80aa10c8dc27ce089daa.nq.gz
│   ├── 86e3897388299f62e9ec881720ad6bcbbbb4ea91.nq.gz
│   ├── 88f9a243a0736e632bbb496d84bd554cad3bc79e.nq.gz
│   ├── 89978b9e57309e0ac4a23a6f765d3426d40bb47d.nq.gz
│   ├── 8b3858525c2fbdc20c6236b64238e9f4f278afab.nq.gz
│   ├── 8bebdb9bfa80eb69bc75d04e1a0eda3b37ba87a6.nq.gz
│   ├── 8c7c6ff67ead6807f24cd1ad714ead28469041c6.nq.gz
│   ├── 8e293c5e8d32c5e16436ae4b4378b7160890cc1c.nq.gz
│   ├── 90c64008aba5932c448ff3cb340f3bccda30d2cd.nq.gz
│   ├── 951c99fe62f6645df34f5b7c4fc611305fec3652.nq.gz
│   ├── 980553e5e9679d5d468da371b2d0caeed4c27020.nq.gz
│   ├── 98c297ca1485a3f24a0466aa3c9f9bcedf2aa4fb.nq.gz
│   ├── 9d23a29081fc7d12fa7a8082fd80ccb45f3053f0.nq.gz
│   ├── 9d4826152e1027e25a0db8ecddf8d078c65b324d.nq.gz
│   ├── a0a6bba00f86c9f1ff40b1f13a4faa62380c8410.nq.gz
│   ├── a23664e31c6a711917e9841a785781a9b835021c.nq.gz
│   ├── a2fa5e1d6d06a6b1f04580522a88e972a3a23663.nq.gz
│   ├── a8f36f5fd97c98b40ad1523f9b6c7be71670d748.nq.gz
│   ├── a9633ca8e876a299280fde5e7bdcc9ad0b9d9e04.nq.gz
│   ├── a9d37c560c6ab8d4afbf47eda643e8c42e857716.nq.gz
│   ├── aa5ac773bfbca6181909161244a0965cf138f241.nq.gz
│   ├── ad88cb3cdea51808a1b889f6c45f66c65328e279.nq.gz
│   ├── adb4363689d2b90280f8155e53709fa761c311e7.nq.gz
│   ├── af535d942f9f0e0828670c7fd8b6020c63f40864.nq.gz
│   ├── af810e8d82b1c2ffbcbe710a351550a2b7d050ba.nq.gz
│   ├── b1adf4acccb3ea54fa4fcc86da517f3b673e2a8d.nq.gz
│   ├── b5460d96c94c083af41857e1c4747b133611cda4.nq.gz
│   ├── b59d809deab8b09fb441d0a97c3a7ce5125a9d3d.nq.gz
│   ├── b692f438ee785d83525e9dd027ef1c2b43c80c5b.nq.gz
│   ├── becd57862f3446bbe1300e2c228befddfa8ad7ce.nq.gz
│   ├── bf154e4580112e829413c86bf8b168a9c974eff5.nq.gz
│   ├── bf4c1db1aaf40b139040ba1956c3d3c5561af77f.nq.gz
│   ├── c0a8f9b0e67bd6ffe239b7e77e2f0841d178d029.nq.gz
│   ├── c2e921cb7ab2016322753a8ce0d19499bb8e73b5.nq.gz
│   ├── caded3f752232b24f65a39572c6fb8f3ff7e1df3.nq.gz
│   ├── cc289ed7b772f0c3c74737ec48af9ee20020aef8.nq.gz
│   ├── cdcbc4822d70f24b14fed7b24522c1f790c5d568.nq.gz
│   ├── cf3f1bc3661a57f09943f0b71290d644332090df.nq.gz
│   ├── d00071551b8550a1095686cdf973afe624b05cb2.nq.gz
│   ├── d026b6d38b8ff6554f87496073cc1fd53ceab062.nq.gz
│   ├── d36f054a6cdcc2791ec18a09b5834d52142ed824.nq.gz
│   ├── d3dc115a5d2feec1f4f6689ca674ea4552a2cac4.nq.gz
│   ├── d410b9522c4caf65c2240a300c4bd5e4b6cc3370.nq.gz
│   ├── d7de2e7a09d0209df0c47983878d3f1f7f8bd3d2.nq.gz
│   ├── db1698a9d0dcbdd4a1f70d20fdae0c533cffcf22.nq.gz
│   ├── de38911e9cd019278bf434beea55b99d40e29448.nq.gz
│   ├── e19dcb4400a2ccdfe2b6bc43fd6a0cf1c34db0d7.nq.gz
│   ├── e29e678b5769f7dd9b3b223eed01f64587220750.nq.gz
│   ├── e2d6b7f75ff03407ac7d49da149e5a90f47ebe3a.nq.gz
│   ├── e5a09e577b0a212399c065085d8813f494c27b1f.nq.gz
│   ├── e5eab7449f8a03365190b9fef1213e5ebba94f01.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e728580fa5febeb1d6471052640629acf78db4cc.nq.gz
│   ├── e80459327a105f3b7e8774ed7f1725dd12224fad.nq.gz
│   ├── ea1a499bbf1d6cfc829a998c542850a907d1af89.nq.gz
│   ├── ed9f526ab621a18d1466b46472c272d1ca89201b.nq.gz
│   ├── f3894fa0bb355860bbb861e4b732960de5b30be7.nq.gz
│   ├── f7ae3a7107420217f1d1f993163103a68daacb71.nq.gz
│   ├── f92092e5a9fd8f47fb98625b73ec41d367ded576.nq.gz
│   ├── f982ae6ddbf67aa53c23a689025a21a298337a0b.nq.gz
│   ├── fa9eaf989e9707629ece99d5957ed6d64658de84.nq.gz
│   ├── fcdf2b97c0ed1a1a459500312fa37a4e07b9b2ee.nq.gz
│   ├── fe1a5d5481466e1f603413f8314961b045c9d539.nq.gz
│   ├── fef98b12581627e37e06f8a3e0e82a81b282eff7.nq.gz
│   ├── ff2ea90b3d364886f566479fc10f73fd2d09994d.nq.gz
│   └── ff8f21fdf560781a9e43ccfb4472ad2c5fcbdb0b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 0d6c7d5469baa09e2fb127ee3758a79b3271a4f0.nq.gz
├── filetree
│   └── 0d6c7d5469baa09e2fb127ee3758a79b3271a4f0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 139 files
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

## Source repository

[hyperium/hyper](https://github.com/hyperium/hyper)

---
*Parsed on 2026-09-07 by [repolex](https://repolex.ai)*
