# Repolex Knowledge Graph of open-i18n/rust-unic

RDF knowledge graph data for [open-i18n/rust-unic](https://github.com/open-i18n/rust-unic), parsed by [repolex](https://repolex.ai).

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
rlex download open-i18n/rust-unic
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 89f5f55f9cf8da4e2a697a1fd5018284c2b1eb0f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 89f5f55f9cf8da4e2a697a1fd5018284c2b1eb0f.nq.gz
│   └── repolex
│       └── 89f5f55f9cf8da4e2a697a1fd5018284c2b1eb0f
│           └── chunk-001.nq.gz
└── blob
    ├── 0073d7537851df62d0501927f1fdb88de5f23f8a.nq.gz
    ├── 00ac6ded9bb076519b51263f7eda773bb49e4388.nq.gz
    ├── 00bf1841deff422359a1e44bd85b55d918106aea.nq.gz
    ├── 01031ff532b7e9ac22c2fee060e3e259d972dc47.nq.gz
    ├── 01fac8d18709889ea8b0fa5c9c9b595224f95ba0.nq.gz
    ├── 027404dcae0a9568b91527c6608de5ffa9664441.nq.gz
    ├── 0322ceec0b8f15aa2d74a6173c07cc8c6f3764b3.nq.gz
    ├── 039a863184fbf9e7e7b4516a9aef9db9da3490d1.nq.gz
    ├── 039bfc1bb88d6b7a48a3fd54c691d4165922144d.nq.gz
    ├── 0558599dde8555020b089c5cc91d60a6169e0c97.nq.gz
    ├── 056461626876b58e468964a68bc3e8e66ac4b625.nq.gz
    ├── 05febcc5e5094a352f76af0779dc6ebf4cedc487.nq.gz
    ├── 0627f16f270913d8d87c4452bbfc03347146ca71.nq.gz
    ├── 06c9cfbbb36d1d0648c40d5b9182bbf4fe2033ee.nq.gz
    ├── 079da2c4a67eb2b5dc5cbf3f3c7a9726dc710644.nq.gz
    ├── 07d1b378fbc1c8297ac38f689ddaa114eb5cdf43.nq.gz
    ├── 083690451e542ea4f0be4af7373d9966076cf98b.nq.gz
    ├── 08f737a9e688a92ba7b39cb2ba13b40eb08eb209.nq.gz
    ├── 0b66c7169be8fe68cef6bc9617e1943ec3cc84b4.nq.gz
    ├── 0cdb76cc8adad1faf0b591346dc73f708756329c.nq.gz
    ├── 0ce4f213e991612a19c5ed61111f33f85c078d75.nq.gz
    ├── 0dd50a90514a4b1038270faf9888a9c512665dd9.nq.gz
    ├── 0ddd8c3056147e797f2cb84bc1869dfa2a194462.nq.gz
    ├── 0fa9b108d4c1524c0585326cdb094e5f53b8bbc0.nq.gz
    ├── 1036d4db503384611bf989ea6188992b74fd3bc1.nq.gz
    ├── 107965194fd8df3ecaa4355ef6b333a6b1a8f23c.nq.gz
    ├── 1140edd9e825a89cf8607d90adc4ebeb7d8aa1f0.nq.gz
    ├── 11e9cf39706903447fb018b6b5f72ec81d6ecbbb.nq.gz
    ├── 13251dea3a392968ca7cf58f8342aaac5e2cffd4.nq.gz
    ├── 13ad877be9b2c8bb47cecbca16a2502ca9f98ccd.nq.gz
    ├── 1442e61c7969efafcf0f34b8b893d1405b7abf7d.nq.gz
    ├── 144a635e1131671d227449bc80069dcaf573e680.nq.gz
    ├── 144b4e952c77be2b8a07b1809c1e992440f54aa9.nq.gz
    ├── 145280f0a12f0ec5d2796171767f39a054ac79fa.nq.gz
    ├── 14b1af164e9f0850824b9a392d1e04e1ecaf70a8.nq.gz
    ├── 1615501f64a60d03b47a3a35d8ec2c64b0d77990.nq.gz
    ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
    ├── 1849478b49480a1598010dc495fb39fdff35ca86.nq.gz
    ├── 193f061da5caeccf6b6024ce520484f226209b51.nq.gz
    ├── 19a60608b2c4481feed23f963bbd3bdf86058547.nq.gz
    ├── 1a06cacebf63b8de3dbc13a46319de64c4f356f5.nq.gz
    ├── 1a0ec94b76886ad6e99c5fe97234c09bf501ddb9.nq.gz
    ├── 1a916fd430d2ed3448d7638f89266e1bac24c3c6.nq.gz
    ├── 1af4e20a0a503a6fe9fc0dfe800f5dd7b3be1a22.nq.gz
    ├── 1b2865672709c7a4cd828320f0bd125eed68eae7.nq.gz
    ├── 1b6f49613d5fd7a3fc27d79c3b226563409407d6.nq.gz
    ├── 1bdd3b8865ff63c2b087c95dc189e49fa73421d8.nq.gz
    ├── 1c4f3d2a492b357770b8f9c6d863c244b7361075.nq.gz
    ├── 1d379d3e6e153b3a3ed9512d761a2b151bd01dbe.nq.gz
    ├── 1e5388bcf479d55587df09f8c6e7418fa0fe171b.nq.gz
    ├── 1eeabc61b7bc0449cea925124b251b6f6d96672a.nq.gz
    ├── 1f6e82c47470e79c267a4ad19dc3d73715777a2b.nq.gz
    ├── 2092b0c5550df60551599118a900872fe8b96265.nq.gz
    ├── 21c8b4f6562cd3f506c9c0734868d77aed442ba7.nq.gz
    ├── 223c338946933629718a13bdcedf535f5bd492ea.nq.gz
    ├── 223ed6130c3594aaba7812113ba05a98226ce742.nq.gz
    ├── 22b224f97a06cebc54221582c0ed2665a1f883b5.nq.gz
    ├── 238e2f5b94a054fb330d6070b8df3e5ff3db54d7.nq.gz
    ├── 24cb40138ef3191463a71a9e3a02e20696218050.nq.gz
    ├── 2516c91a01a12b18994ea70a9799b41c2979116c.nq.gz
    ├── 25d3c943afff997659260677e7acfaa0f1d3dc77.nq.gz
    ├── 25e9e4cd85ce7f1b9800defe3a98d95429553a8c.nq.gz
    ├── 275586558162aa77dc0247257d4876c72b34707e.nq.gz
    ├── 280654c6a96782e352267b6c947ffedb15abb86a.nq.gz
    ├── 283dfe52fd409f883a75db07921cc491bd5021c3.nq.gz
    ├── 28d30ec6863070388b836d4f111a784e7b18acfb.nq.gz
    ├── 293937eaf404eb041f391e5decb0fc3e7d361c5d.nq.gz
    ├── 2946ae1497c4028e727f42cc339b254c3b374020.nq.gz
    ├── 2996f2b9944a3fb99fa286111a50b4b82b11824c.nq.gz
    ├── 2a45b0e791ca13830b069d3cf6ee7d03bf01c839.nq.gz
    ├── 2f5bffff31aaaa89d8d493df1ce9e76f5a27d140.nq.gz
    ├── 2fbfcffb59f95992a9e9372823e34d202930a9df.nq.gz
    ├── 2fd96cc936654e14483185c7d007afa0609a0cce.nq.gz
    ├── 2ff0fabf73b86d8cca79b9430cf7c15a0c2cdbb2.nq.gz
    ├── 3165bf67587275e3223bdf38faebe7c63d2e1217.nq.gz
    ├── 31aa79387f27e730e33d871925e152e35e428031.nq.gz
    ├── 335976e0cd36ad6a75b3d1d2049eeb5c74034475.nq.gz
    ├── 360a67165a3bf042f941c910dd41504eb98334bf.nq.gz
    ├── 365d065e63fcd94932fefdaffaaa9f55f3544cf6.nq.gz
    ├── 375ce194eef53c8b1b668ee753dc0a973fbe2cd4.nq.gz
    ├── 3856801249ac4bd42aa258f4a1470a313d7ea3c5.nq.gz
    ├── 3877f04d7d6095bd590fcd1ba2ea18d5f4fce01c.nq.gz
    ├── 38be971692a36ee419453d75c6f09eb80776547b.nq.gz
    ├── 3928e4d090c1d4def1a0e64f02396d220885b02e.nq.gz
    ├── 3aef772914fee4fa986ea9c0efd8e24cff2a18e5.nq.gz
    ├── 3bc112d07ade96887d7ac275fa310957237d380e.nq.gz
    ├── 3da055d086673f0cf6795888a65ac9ddf5a95acb.nq.gz
    ├── 3df4df11cc016926e4d0d5743cb947acab9b31de.nq.gz
    ├── 3eb3f248ccaa9a8020ddeed7bc0a8d063dc61c16.nq.gz
    ├── 3fca4b7ab0bb0b7b61381fd63d6b518c3473dc01.nq.gz
    ├── 40f05ac07c06cbc7437a3342933d4a6140224a5c.nq.gz
    ├── 41b604227945138aba6f1bd0f083ca8eeea22d68.nq.gz
    ├── 42d814067ec60f7cb3bac7d4bcd05377a6515245.nq.gz
    ├── 435e52c8a56bf278b40560b6a4fd26476a7cda1b.nq.gz
    ├── 44901dfe3c0139b5cb9835acd6b6431b3d6e45e4.nq.gz
    ├── 44e389f17e114dca008b4bc1e083740a0b8326c1.nq.gz
    ├── 454944e8a3d615896055e2f2dcdfa27bfff318be.nq.gz
    ├── 46384458a97b9c25b65723978d706197e6fdbfa0.nq.gz
    ├── 470766180ebb4579f4ea920e256dc8b1e723dfd2.nq.gz
    ├── 47d1771b7dfcd7a4ceec84b16d83b220e8e26490.nq.gz
    ├── 47d367f4ddb6869c850d10153ff035b64abd0d60.nq.gz
    ├── 47e1637a40081600a31453d74f728f44c97642c7.nq.gz
    ├── 488ecbd148f470f55e25b0f032eae5a3802def0b.nq.gz
    ├── 48b33d7b704f71e2b360a6860ff92baa846c2fac.nq.gz
    ├── 4b7f17c59f1ce36e3623b92cc17107d3f64ccac4.nq.gz
    ├── 4c2c3d6009d19f3c4995be688038b27508f5e543.nq.gz
    ├── 4c381ddcc16271bfb48c9897c3880909f88fbcab.nq.gz
    ├── 4d630d120a2b29962de9e518373f585161b9d885.nq.gz
    ├── 4d7fbe2f7788655b8902d890d90b008c78ea9873.nq.gz
    ├── 4e6e85f45fe607f5e5910370a8c8e4a526ba02ce.nq.gz
    ├── 4f5aaba869e5118c836b8dffb0c80849de6e2c20.nq.gz
    ├── 519b544a3be44110703cd1cbd3c066845694f0ba.nq.gz
    ├── 5207195cd555cb1e225e1d207c6487d8227a1c57.nq.gz
    ├── 52ea00564c70161156517e0b11ecdf8c85352619.nq.gz
    ├── 52fd786343a1047d2d1a2d4cc7e7077ef2cc0de5.nq.gz
    ├── 54d6aa20bd640e4b3845b686ea8c05b2eb6fb346.nq.gz
    ├── 57b7721d26dc736178f2c32eb3425c4f911622e1.nq.gz
    ├── 57dfe2b575b9e6b56eaf3be526f535f9bd84ac4e.nq.gz
    ├── 5a67167dce5c8a9c325d426cdca54f12507da7bd.nq.gz
    ├── 5a6af0264884ccbf4c2561617955c355de2bbe8e.nq.gz
    ├── 5acebcc881c2fb957b5304d00db0dd4876429668.nq.gz
    ├── 5b40d221a0b7ad5150024845c71b1ac30406f589.nq.gz
    ├── 5bd3fcfbf1177db9e0c320c51d80e86facf74075.nq.gz
    ├── 5c42704e4c11083084f4243c299582c907c0ae44.nq.gz
    ├── 5d8a0be3e6bb34fc6503da11e511094d37e6628f.nq.gz
    ├── 5db57c302a83010c12a3bb128043b0eb054b184e.nq.gz
    ├── 5dcffcc9f17c0a9662fbaee8e4d0e606b9d20f30.nq.gz
    ├── 5e594f1e923796ac01d9671d6e551ac0be43f003.nq.gz
    ├── 60392516ad3241bb003bd3f03b727bf7906ca1cb.nq.gz
    ├── 620aca301d20944301946bd4a3f7c9602b09fee4.nq.gz
    ├── 62a419626d6f4e2a4e7d53db6c101a1ecd739241.nq.gz
    ├── 62a637f50bcdd97b27e0dd0073234f842570e832.nq.gz
    ├── 62df2be7f7d1c5067708d386ec71586cc44dc5d3.nq.gz
    ├── 6357dbccb6ca33aef60c6ad37424fdeb29500e9a.nq.gz
    ├── 63d0ef15783dd142392620acbdc42fc7563ec9c5.nq.gz
    ├── 65b1f60ce0a71873019bfd52dff89f02984ff910.nq.gz
    ├── 65ba633ea35a0eb407b86eeea40a5bc692919987.nq.gz
    ├── 6685d0ffcfb352aaa4823556e8883213fdaa3ac6.nq.gz
    ├── 66edfee7a93c75971fc1af4d07039c7ba9e2c379.nq.gz
    ├── 67d306c18685ef110d8d265b5a8436602f0395e1.nq.gz
    ├── 6b6181efd35f89259c9d4e507d7652ad49703428.nq.gz
    ├── 6bff7ed525c8ee611a03df19fdaa6d578536c61f.nq.gz
    ├── 6d65f54277e6fc6ad9be91783a9bb21c9b10187e.nq.gz
    ├── 6d7273eabcf8e1385d76d95e8fbfab44e4089adf.nq.gz
    ├── 6faf7def0ecd30657678aadfa8c14329cc26ca6e.nq.gz
    ├── 6fb4a8606edcadb377c9dec9e5099f582b4bfa72.nq.gz
    ├── 7035fa27240b8c63af6c95a78df0aefa39630d07.nq.gz
    ├── 704b78e736ea551126356466707ad8418a5b7aba.nq.gz
    ├── 712b832c75c29324d9e8aeeb60012cd7b4698039.nq.gz
    ├── 7157f05caa202e8bcf962740a1a621438d6e0c10.nq.gz
    ├── 735994322364eb821ad7cdbbcb96d04ec4a4e069.nq.gz
    ├── 751f93ae3e3f0e99604cf64f80eb9343f4b7ecad.nq.gz
    ├── 758dd5e4b9124fba2fdffb527347e37e74f8eeb2.nq.gz
    ├── 75b2007e4725e85714ff36af9bc1d0795c7878af.nq.gz
    ├── 7707b6881eb14f40c05369a0ab8f583a43bd7ac5.nq.gz
    ├── 772bd49ba1e66d17ee839a0f000df093c0d921b9.nq.gz
    ├── 77356cfd0a8e1081ee08f414d2a48cc5185f5388.nq.gz
    ├── 78b77e196a3ad76a95d8433753413b9dd604fb31.nq.gz
    ├── 79634f98278b5d5afb6f0182f617dba59113270f.nq.gz
    ├── 7a689ae942f320035d594d0b13d729c6cbcc0a45.nq.gz
    ├── 7ab99bc1020bc4343946fabfad2925d9f882c633.nq.gz
    ├── 7b06d410101016ae98bbe2cfcd44b782d5264f24.nq.gz
    ├── 7b452eea92dc35f63a35f816d132b33b773b4681.nq.gz
    ├── 7cb88c466da967153276f1814f0e2a1b08fe3e44.nq.gz
    ├── 7db0a707ddaa538dad17de86472de47f6a5c4987.nq.gz
    ├── 7e2886cdd1b0556e154d59247cb8cbca1df4a937.nq.gz
    ├── 7e4050e1155f219f26389ddeb06cc7273cbde338.nq.gz
    ├── 7f0522acd4b52bfbe97806613634515ebb195d13.nq.gz
    ├── 7fa1c1f77233b1310ddde092ecb7bb49c0cb00e1.nq.gz
    ├── 81c445a64a668ed4b08fcafa67b0b15cb301bf6b.nq.gz
    ├── 82a9194eedc4e96e71ec1045026573f994e03b4b.nq.gz
    ├── 830af7298fce681b16531479a6750dc26d80785a.nq.gz
    ├── 83897b9654bcd33bb1ed7b7c973e61d5dcdd86b0.nq.gz
    ├── 83dc896e6ff4a3e316d5be8646c6cc9f6599531f.nq.gz
    ├── 843b90ada39b08a4d627e4575233e4aad05315b9.nq.gz
    ├── 8565f4aa355e2697a52fac2dd9f2bd0c5dd2f3c3.nq.gz
    ├── 856d5a8976c79de9a334fa661cb2959802e3f546.nq.gz
    ├── 85b66752f18dc06ef214a7f8694b71a64e73043d.nq.gz
    ├── 85fe26f1308f0e9163b5159f05fd0c63ec45d230.nq.gz
    ├── 863370ab189404130e4f2e03087acc2e7bd8f45a.nq.gz
    ├── 86a713b3552e2e39c22dfb6d1f168c902165c2ba.nq.gz
    ├── 870a1d32043f03f05a228b25d598f75f1f0dcfe7.nq.gz
    ├── 87b3deedea4e7e3da76bc36953797d174045d16f.nq.gz
    ├── 8aea706218455f6185f9e1f06f2f832075776755.nq.gz
    ├── 8b34df016cbe5fea8466d5da6a0efe4869133833.nq.gz
    ├── 8b9c3795f0246e6d404b73512c7b58c269681ad5.nq.gz
    ├── 8cbf083e76e6d15bee6935c5f72c9a15f490c6ab.nq.gz
    ├── 8cc2141e0526a5f3e54db324961151afe1c1697c.nq.gz
    ├── 8d72f3641fb81b7a91873a0ca901183adce58c39.nq.gz
    ├── 8db3bab570d8f8627f5a873c02bf58c5faca645e.nq.gz
    ├── 8e342f317d179d11485e9e10699b6aaac086bf90.nq.gz
    ├── 8e96e7f0a49aeeb1b41ce8dcc7ea73acc19e339e.nq.gz
    ├── 8ed23a0b08adb84daa6fbaf160d78e8d183091dc.nq.gz
    ├── 8f1df0b4d42cc0791773ef47e3028d1629feaa01.nq.gz
    ├── 8f1ffc2b7e1853e11be6abaf37c357cbe8068966.nq.gz
    ├── 8fa494a12786dcac3e6733fcbc2ade2aad47ef51.nq.gz
    └── 8ff298bbe327d516d2784a6953126af724e113a8.nq.gz

8 directories, 200 files
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

[open-i18n/rust-unic](https://github.com/open-i18n/rust-unic)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
