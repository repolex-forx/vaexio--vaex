# Repolex Knowledge Graph of vaexio/vaex

RDF knowledge graph data for [vaexio/vaex](https://github.com/vaexio/vaex), parsed by [repolex](https://repolex.ai).

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
rlex download vaexio/vaex
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 65ab46281939e2fd2fc291266bb08a328ff59882
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 65ab46281939e2fd2fc291266bb08a328ff59882
│           └── chunk-001.nq.gz
└── blob
    ├── 00069581a8952663691bb5743cc23bda512d9b82.nq.gz
    ├── 004cc1085534827981681bd80699867e1b22af02.nq.gz
    ├── 00a55c086cdcdb8e9deeaa27fe16676ca8c3b8c0.nq.gz
    ├── 00addcbac51575213b3e89127b1db74cb58b1168.nq.gz
    ├── 01bcc4b7c185be29401d3a6c057587815f5bffa1.nq.gz
    ├── 01fbbcbaa9fd750c456258ebc4a305ceb94adafd.nq.gz
    ├── 035a59f014ec6a661e34e33ef1f5e0a3d79442dc.nq.gz
    ├── 037e0bd0abc345634ad3dea89268f13e624cf6f4.nq.gz
    ├── 0395f71c16d039d3ff97068b53e9978d94412aec.nq.gz
    ├── 0528dfa24ea76e6d1ee3919deb5b95a6c3e8b27e.nq.gz
    ├── 05d1b7a1fc7974d0cf43cb5b615d9a34afff5eef.nq.gz
    ├── 05e1b8619941513890dfdd1d2dd3c0dfa62b6df6.nq.gz
    ├── 05e9ca4c77692fab1519f26faf6259d413992ee2.nq.gz
    ├── 06e93a0b0fd1f585dfe6760aefe399cd274cc565.nq.gz
    ├── 0730f7800cb17b80c4d977c89bc956c7d255c59f.nq.gz
    ├── 07bf98a79cfea526e250703356dbefdb6b80d166.nq.gz
    ├── 08dbe539814897843a075d83dfa9e4109c693fc1.nq.gz
    ├── 092ae3e257a231a0a476c382f4fe5f27c9c29308.nq.gz
    ├── 09343d2b4fb6e956d422ffddda9596e6b43abb64.nq.gz
    ├── 096371b0a8e7588f05f272a8a79701d8d52b525a.nq.gz
    ├── 0a694002e1ce7e3ca63cef21d3e925d6ed3f89a9.nq.gz
    ├── 0a8828d288e08c0b055d46331fc7169029bab224.nq.gz
    ├── 0b9762090db6c989fd53096727791e344cc60baa.nq.gz
    ├── 0c81e316355c0da522ceece306dadf759cab658a.nq.gz
    ├── 0d003bb0f51a1a4e18c24b460bad81d5a93fdbc3.nq.gz
    ├── 0d76f884886cfe7d03bb0bf8a863ee8bf3ca58d1.nq.gz
    ├── 0eaa8d7019737e4d82a1932178a63917be696b7d.nq.gz
    ├── 0eb27d108a11172e1cd95de887396110030d1659.nq.gz
    ├── 0f326f4bee901f2bd44365b18976bc0fbf7b0248.nq.gz
    ├── 0fca68494fe044527fdd682210b20d387568e238.nq.gz
    ├── 10570bfd1b64f2dd2a3374809d84f3e2d65824e1.nq.gz
    ├── 110dabc307974eb174e6e1769c9dc1d66fc67f24.nq.gz
    ├── 112c6ce4b9ea564a9cd387575e9e0504443158f4.nq.gz
    ├── 1278630e7f97abef34943d22d57999f189376a44.nq.gz
    ├── 12ffbb54b5ef8d519faa0421b4ca38a3357963cc.nq.gz
    ├── 13c6032e70d56f6275a50289d12e2650020f6098.nq.gz
    ├── 13df4e17a1ea4e771f193c3de2823dc485710f38.nq.gz
    ├── 1413fc609ab6f21774de0cb7e01360095584f65b.nq.gz
    ├── 143bb5f09a43320359808b7335673b463ed7bd97.nq.gz
    ├── 155aa8a22830b2b7f63b75c291753b3754bdd99e.nq.gz
    ├── 15d062d60bbe7d99eee16f4409f1470d5ff74fe7.nq.gz
    ├── 15e0514c2897c686ea324654d249af458875a721.nq.gz
    ├── 1646d1012b59457d3e0d99516c71fc96f9414c1c.nq.gz
    ├── 174aaab1ed2c53902f1d9f0284a1c21fc13d45c5.nq.gz
    ├── 178eb7cef47ead1289adae6aa7dca06cc6352d5a.nq.gz
    ├── 1857f2d5587eca79a59cb9da61354c9fef19b6b8.nq.gz
    ├── 18b67babef163596e5e9cc4a7b77f8fdfd48c1e3.nq.gz
    ├── 1987e283d58e9ba0150bc04c25b2b32e061f7d74.nq.gz
    ├── 199f5f9604bbdc2d21752929832ab8f72b1d1c42.nq.gz
    ├── 19a07e0e798da26bf0f433347068613f57a5990e.nq.gz
    ├── 1a302b6994ec705793ec3f93dd1ddf73b1499aeb.nq.gz
    ├── 1a5d2cc28bd3b7ade5468ca9669e38e94239239d.nq.gz
    ├── 1a8c8d89630192e517d2785eddd1e3e267ef5327.nq.gz
    ├── 1b58b499682aebeca3649cec9c31ec9408827bbf.nq.gz
    ├── 1c1e085d95f006b4b3f2e8182e80510c37cf8ebf.nq.gz
    ├── 1d0fee2dbd3e867537cb4d419288805a7f316b08.nq.gz
    ├── 1d319d3e71eaff0e839b5eb78f70a234dcdccd1e.nq.gz
    ├── 1d3e4f1e543ebc96ed34b894cd8e4400297c86bb.nq.gz
    ├── 1e0fc794be50507cc7480cbab7cb0501aede40fb.nq.gz
    ├── 1f0dceac950f9e64eb2cc0f632a36e5792d29965.nq.gz
    ├── 1f15dd4ae08dba4f528227ca1409683a8709b371.nq.gz
    ├── 1f36d70e64f542018759008c20026e6df0748c5a.nq.gz
    ├── 209da261fda7386dd85f1c286c4b77777bd77759.nq.gz
    ├── 20a816464691dba637c1119ed0c32ac99358d65d.nq.gz
    ├── 2173944af240b1745abe481a21bdfda2d826e836.nq.gz
    ├── 21db62918d7e23526ed9a7eeee851f7ffc8d1487.nq.gz
    ├── 21eacb1d26af467e1595b321de30fec462d28bb8.nq.gz
    ├── 23814bd9e42cad054cdb729200bc60af44804074.nq.gz
    ├── 23c9f96fabd355bfa1c8fc3de0c801311f3a94f5.nq.gz
    ├── 23cf88f5fe4b27ff85493878791acb13f072bdd5.nq.gz
    ├── 2530ae084a5c71b8682db6c866ad7f64e602b657.nq.gz
    ├── 25b74d18f740ff208435f72333a1633569c0e833.nq.gz
    ├── 25eacb7c2524142262d68bf729c5e2b61adfd6d4.nq.gz
    ├── 26789a3d41f155e85f93e5045958927ba5d92cb2.nq.gz
    ├── 26d244614a43f2c053a29bb51c22680769d8fec9.nq.gz
    ├── 26e63d9d06703d9d37252587306e0de33e3f0fc6.nq.gz
    ├── 27af66d4c609a6b438e1d6d210944167aad57a38.nq.gz
    ├── 283e343682a717b7610fe55cc11f48546e972f05.nq.gz
    ├── 2a30b5ecea0f12d04ebc93a0c6d878ca40e24678.nq.gz
    ├── 2a361a0789d620a5f75f126091536fa83d15bf3e.nq.gz
    ├── 2a59d572ab50042e9d98f3b8ea1db589015f1146.nq.gz
    ├── 2a82894c1c36edb11573e912d6efff97ecd5493d.nq.gz
    ├── 2bb46893c389d59c2b5d9e4d931360f030866874.nq.gz
    ├── 2cd9c6cbf8a400ac65a4a1ec2fb8df8f854e29a4.nq.gz
    ├── 2e0978e105eb6176736b7a7902e7e7a3481c1f04.nq.gz
    ├── 2f7fb25dad0a667e32c745ed3fb3f31603a85268.nq.gz
    ├── 30fc4d2d760e74852e35d8da30fa5dbda28c3d59.nq.gz
    ├── 3125cb6e0da620f5cf7ff539984ead6eb764ac37.nq.gz
    ├── 31f3f78a43e8d7bbdf65b698c45e89bc379d6fcb.nq.gz
    ├── 3219dacd03accb64e8b3ba04f80ab96921b1610d.nq.gz
    ├── 322a8c36650a7df8a4b016b2dcbab9505c54213a.nq.gz
    ├── 322da36ed1ff5b7070eb92a061f90d127189e09c.nq.gz
    ├── 3245a298de03adad88def779c528153826ed44e3.nq.gz
    ├── 326224261cc03e429efceb6a4f311f3239844b50.nq.gz
    ├── 32da8b406bb796594a900621b0e4dba20944006b.nq.gz
    ├── 32f09e1b19903486256cfd1a87e07dfa6766d77e.nq.gz
    ├── 33b839c3b56376ea4432da5feeb722808af02a92.nq.gz
    ├── 36fb1ec42de38e8f6342e942be48df84367a9698.nq.gz
    ├── 37e53122c2dcb9dc3f49f97bfb71ce696b0faa8e.nq.gz
    ├── 380d4b8227385c88d9de243785d7153110299621.nq.gz
    ├── 382fe60993ecc18b52fc4188e00c8472e1afb467.nq.gz
    ├── 3949f7a97022fc04864fe628a9e93c1e2fee9fff.nq.gz
    ├── 3954649683d11a0d3a1f3b2ecc56104848716383.nq.gz
    ├── 39cd8d8711bbd34cb909a0f099d4936fd92ee6f3.nq.gz
    ├── 39f463665aad0866f5bc70ec9f15394ec74e9d01.nq.gz
    ├── 3a3cfebffe19645252e503be4a6b4a917afcee2e.nq.gz
    ├── 3b03089a05349558330eaf1a76fef1eb2030839e.nq.gz
    ├── 3b4fb543a434dda50266c0fb771271efd04906c2.nq.gz
    ├── 3b6bb267a49e8f183e15f8328eb40ed4993e56ae.nq.gz
    ├── 3c864f056fa1b1d94e0a367a44f56dd85311c4fb.nq.gz
    ├── 3c88e7cc270ebd60ee3b8aa81bfe48b0674d471a.nq.gz
    ├── 3d0046f277961d0d404f17643437fdf775b8645f.nq.gz
    ├── 3d0d4ad1d0c9004a3f751b39042aa98b2d4bbf4f.nq.gz
    ├── 3d3199f5a5d5252b3ef0880282febd39eff3edfe.nq.gz
    ├── 3d7146e240817d289e381df843f7c0dd4063919d.nq.gz
    ├── 3dd3f29bf94041547d08f2a617d5a290ed775770.nq.gz
    ├── 3e10f3189c949d321551f236b0eda06fb77bef20.nq.gz
    ├── 3e7aff1efe2b99a4ba9555b7b7fb1b2e4829747d.nq.gz
    ├── 3e8ace2bb4320b070c671b1638ba413f0af3dd33.nq.gz
    ├── 3ed1914dcecbf411070ffd1917c0871233d89335.nq.gz
    ├── 3f2effdd64d441b6ae0300be1c0ecbd9394a789a.nq.gz
    ├── 3fb6792b868afa8a746d8abe961333c326e7f448.nq.gz
    ├── 3ff80cbfe28503fec346316b84c22b2ef4aa60a4.nq.gz
    ├── 401160a576c4eb9070d5ca4974752ab1f4a06279.nq.gz
    ├── 40734e66df1f80b1c93823c511bc938506a8fd10.nq.gz
    ├── 40ade64c9caa3405ac800c3e00d07ec810aee1c0.nq.gz
    ├── 413599a9dd2841f8e2bf4501637c0ede0eea8b4e.nq.gz
    ├── 42eb4101e514e6e82ecd5111fe09e81a786de694.nq.gz
    ├── 431e5d6470aa85dc1449d265fcc23d69d9d064cc.nq.gz
    ├── 432dbdc862bd69973871d7a42be8fd98a2fe0d8f.nq.gz
    ├── 43aa8fc64bfa2baaaf20eb25db475d9443b78216.nq.gz
    ├── 4410fc3509a73d2083d5c3b564dde35340013389.nq.gz
    ├── 447c7c8590ae437eb07b4497f5597e6434a13f7c.nq.gz
    ├── 44e256b301f3c88d7d515ffd7c25e75e0a035d95.nq.gz
    ├── 45cf7988bbf24a91df9abc7ebd98dc808cb5d688.nq.gz
    ├── 461b38f9af7d026c3e5baa4dcb3b4eb094d8d79a.nq.gz
    ├── 461cc0ec50ee5fa0b54d04e77a046c592aebf0d8.nq.gz
    ├── 462299bc6a952a38e360592c3f10799dad8481a0.nq.gz
    ├── 462527be8499f2dd7bbecbb041577191db09128b.nq.gz
    ├── 4631cba0f55ec6cfc73740306b91461e69276734.nq.gz
    ├── 46b3e67b9b38fa969c2c71327cc313eed07eca79.nq.gz
    ├── 46dff675297bcff3641c2a9f6daee65d1079caff.nq.gz
    ├── 47846f230e316924e9c3574e52507ebb4138809e.nq.gz
    ├── 4785d3b3fe3877a8709c8219f12c1e84abb0f5da.nq.gz
    ├── 479ab5235b8a3f686226916ef6435885929eb7e2.nq.gz
    ├── 479e0eafe518bbb267d3db25d4d687a4b1745636.nq.gz
    ├── 47bbf12da65cddddc87b79824ed7dede2494c9dc.nq.gz
    ├── 47d050598849468ea9d7c3d2be3ae8d682b041cd.nq.gz
    ├── 48e91ae2db5f94d455f76fad50469a3b01019e2c.nq.gz
    ├── 496db1db042269f7896acd02048e7c10a6ec0d2a.nq.gz
    ├── 497cbe1df9dce5287a842213056962ee98d76bd0.nq.gz
    ├── 4a6b56d84b96b4180bf2c1ec9389b8aebcd52337.nq.gz
    ├── 4a9698dd23f3d6d157e11b266551fedef273dfaa.nq.gz
    ├── 4bc1a24359966f11b52a983c32d816f900f25b81.nq.gz
    ├── 4cb32c1f86502e2190045638a078543f7f94097f.nq.gz
    ├── 4cc5bfaa3fead49567ec9e4cbff29dadcf8ae095.nq.gz
    ├── 4d1f2d3430379410494034ea309fba82ec94e334.nq.gz
    ├── 4da26903575da993293294a647db855f4a144c66.nq.gz
    ├── 4dbec9d42f1b364bf5fa9f58c27e0e4dee3ee9d8.nq.gz
    ├── 4e070783ae786f4ff249cbc742f7730eefdde84c.nq.gz
    ├── 4e0ced178121853e1956f48f329cdb38c78ea5d4.nq.gz
    ├── 4f434a47bd8bcf729c79181c7bcf92488e4d5111.nq.gz
    ├── 5008ddfcf53c02e82d7eee2e57c38e5672ef89f6.nq.gz
    ├── 500d118ccf02937ca3da24bf481f7d83d1800d8f.nq.gz
    ├── 509b26ebf6d87cb70132f11fac6fcdaecd4bbc04.nq.gz
    ├── 51fbd41b8944c541e7d9992076b51123ef53593b.nq.gz
    ├── 523575306d53eaf176b4f9b260f0d36852565596.nq.gz
    ├── 5244d3e46b53eb9330d83d0afd7e9b3e6d4798b0.nq.gz
    ├── 52d161eab4370b9d2d3350b97c0c653cbbe9f6ed.nq.gz
    ├── 52fad7f4791dddaab954f64e698f6fc755b8204a.nq.gz
    ├── 532f532d87ef60b5f2cdcdeb573ec949d2918def.nq.gz
    ├── 53c267a1e1389f74f8cd1d2c25d9eda2e050c7a2.nq.gz
    ├── 53faeaa7d10bf4ddf025f922728f387ce0a766a0.nq.gz
    ├── 54bc4216e273882f8da74928166faa864ad6344b.nq.gz
    ├── 57e3563d6b50da405bf8d2260bfe4dfbf82d99d8.nq.gz
    ├── 591aa534f32d68d397caf3b90c01935e3e8d5e7a.nq.gz
    ├── 599984ebced3f75140c1ee7b741ce4255d875a18.nq.gz
    ├── 5aa541bf95034efe14f5f3fde79e2639f6d52abc.nq.gz
    ├── 5ad573aea3935a6e5bafdd1e3bbaff0762e0ad82.nq.gz
    ├── 5d1e78724fb548352fe0cac966bda205e6e75e19.nq.gz
    ├── 5e04b2b0da97293fae92f92d5f5f281dbc0d9355.nq.gz
    ├── 5e225f3a16cb1f5a72c30a89a682d4b7a9634ea6.nq.gz
    ├── 5e6f074f7f38600128ad94f3cdecfd25e76baa0a.nq.gz
    ├── 5ed5d2aa85a95894af35857ff86e015b94249289.nq.gz
    ├── 5fa6bac8d6a59cb70d0088a59c83ca7f27780d06.nq.gz
    ├── 5ff489d26516baeb27a7a86feaefd7dbb642bdaa.nq.gz
    ├── 605729d3e38e5b783de2849f24adb0ca7bc99615.nq.gz
    ├── 60b0cc947216b10992c9a789a7ff34d227c6541f.nq.gz
    ├── 61445fe54d16a5f277b020e7c0463497600f3bb0.nq.gz
    ├── 61705f3366d21189319d1a0e8bc2fbcd9b24411c.nq.gz
    ├── 6197598a8f76dc20f3309dd065ef4a59b4db5851.nq.gz
    ├── 620e421970866b98ba30c5189caaf9b739395142.nq.gz
    ├── 624557c63d8e1d9689dc3d6ef2e8f5464f197517.nq.gz
    ├── 64d7851afe4e8ec3276fe77284631646ed1e5a62.nq.gz
    ├── 64fd71413fdbda192adea6eff77ffc54b61ee8e6.nq.gz
    ├── 66137d139eab0e00262647b0d13e81093228cff7.nq.gz
    ├── 66e5bb3be7c4a8a13e3ff146001b941081987b83.nq.gz
    └── 670c9d20a346e03d4918b60169113547c77c1e67.nq.gz

7 directories, 200 files
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

[vaexio/vaex](https://github.com/vaexio/vaex)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
