# Repolex Knowledge Graph of jupyterhub/jupyterhub

RDF knowledge graph data for [jupyterhub/jupyterhub](https://github.com/jupyterhub/jupyterhub), parsed by [repolex](https://repolex.ai).

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
rlex download jupyterhub/jupyterhub
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 10c37af3bfe6aad9676c6decde14a6f6b2dd11d0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 10c37af3bfe6aad9676c6decde14a6f6b2dd11d0
│           └── chunk-001.nq.gz
└── blob
    ├── 005f15a8da8aa2d66f35fe171b840805a20e1139.nq.gz
    ├── 00826502d6b26499ab791ed59987da71c65c7523.nq.gz
    ├── 0087679148f4e97d7624b4ec0dc1e426ba306101.nq.gz
    ├── 01d212fb8215cb1909ddd760a370a43185f2fdaa.nq.gz
    ├── 02355f9e1d18f43568c282e86bdca39ec84f9840.nq.gz
    ├── 0298e76357558c25a78e6f54cb989bb088769643.nq.gz
    ├── 02fdeb212cb163c76a435e934ee1b93d587f835b.nq.gz
    ├── 034499ece8e1cc9399ee850121bdd23b1248ce55.nq.gz
    ├── 03b906d40164fdbf96bf2d05d933208782430146.nq.gz
    ├── 0415a720e6f643add6cfd61d412251849236c518.nq.gz
    ├── 068afc47fc62a983de17ff237271084fbc4577e6.nq.gz
    ├── 06b2e6dbbe9c95ce017b54ebfc866013e91f5d90.nq.gz
    ├── 06eb154d0c07090c4756fe615c1cee191e06b6e4.nq.gz
    ├── 079e0f2a9126af168ffd5354e4d95e2ba491f2f2.nq.gz
    ├── 080892065628dabf3abeb5c0277616a46ef977bf.nq.gz
    ├── 080eb44e67af7f661276b8f8864bc23d794d4a5f.nq.gz
    ├── 0858baaa134268b77b2fe014e7df007b8ab40306.nq.gz
    ├── 094d5953f027062f6e9873a6001fea4958ab24c1.nq.gz
    ├── 0995b019595f0fcd9864bb2cf8490463de803b1e.nq.gz
    ├── 0a90d33b8dd6e8414918daea23a7070a9e932bc9.nq.gz
    ├── 0a9ae3105a2a0cdd6f787038b6e392fb6337cf63.nq.gz
    ├── 0b6186fa73a61d451a7a68fe06342e458a0aaef9.nq.gz
    ├── 0b8ab38e6876ef4cabb5cc08ed8a9ae60fd0e119.nq.gz
    ├── 0b9b2553e9f60757b428998eacb31bb5e2fbcef0.nq.gz
    ├── 0bd21b278f9544f9aabbc01dcd16a7f36759e9be.nq.gz
    ├── 0d26d37ec0abed6e85adea99009f395a9a939fa2.nq.gz
    ├── 0dd8ce92332268f40adbfbb189e7dd8438feffa9.nq.gz
    ├── 0f607808234ca57b2938c23b8128a040fff84b7c.nq.gz
    ├── 112d0237f01c9b2116c569112aa23fbaaa9bd936.nq.gz
    ├── 11cdf2602f0e3cf7a0b0cca29e51a4b4f6b32106.nq.gz
    ├── 1253849702db2a8fce84cff4ea2f9c94d5fce848.nq.gz
    ├── 12d406b7a7136a1fceb1a2a71076871a119d5b95.nq.gz
    ├── 1361dd6946aaceaa039236dae37f6e37397da95f.nq.gz
    ├── 14c66d2b399baa9c0e97e4225bbfb0ad87d98d0f.nq.gz
    ├── 15e2a0ac47ce8fc043e70f3b28d52175126a1704.nq.gz
    ├── 15eea647f3066137e8151cbb99b0a2d7065aab31.nq.gz
    ├── 16d221b360cda3aaf80a93d327bae0a90a28f921.nq.gz
    ├── 177c86d5a128f74ac6bb80491bfd248a5c11cad9.nq.gz
    ├── 1797cbfff3f4ee3d3188fa1d959676907c8e899f.nq.gz
    ├── 1932f9e51fe4b9851d92c79691d3e824d36d0b43.nq.gz
    ├── 1a3e5f2b7caef6d879f08d8333fcda018142fb93.nq.gz
    ├── 1a46d38040454b24dad56459bbfd9cc911c3b59d.nq.gz
    ├── 1c3aa0de8bfc76e788e7684dff6fe5c88b88118c.nq.gz
    ├── 1c51f3bd0cb7d7ab0ae819370d8e4b0d966213c4.nq.gz
    ├── 1c9fc8f1b5f348dbea0c45e51e7107420e24acd1.nq.gz
    ├── 1cd53dfc5126cc8879ed7f2879fc71860c47553d.nq.gz
    ├── 1d723d27638bd3e59a7f32fa9e1619ffb21bd780.nq.gz
    ├── 201100d6ba59d4fe8ba389e6cb5265bccbdef5b8.nq.gz
    ├── 20898d169cc2cc6745cca1bc7a89892bb4468689.nq.gz
    ├── 21238f6477d2fc030ce033bc046afee2161cb725.nq.gz
    ├── 21bf470fd34f9e7c10f6e8128b170c1efd1d7a2f.nq.gz
    ├── 2392f48af23d09d47ad78ff964da8d7c767713d7.nq.gz
    ├── 257763777796e923b268c6b123b360ed19142dc5.nq.gz
    ├── 25897a374eb2572dd8736998ccbfc6e8a66e80b3.nq.gz
    ├── 25e23d15e00d6d0617f231be74db46083af2d601.nq.gz
    ├── 260aebd5f02da52305b83141c487e34149ef7c9e.nq.gz
    ├── 2611640b17d955c9bb67f049ca71e6ac6fbef694.nq.gz
    ├── 2674871bce5a823546d169d72b9dbdea4a6847cf.nq.gz
    ├── 26b832a303478842734b5d82cf7bee41ca3e6caf.nq.gz
    ├── 26d064fcc22ff38b788434578a3cc0f8b27dbc6e.nq.gz
    ├── 270248b5bdea61d2c7449fe8c6d778e911066465.nq.gz
    ├── 2831d8c1dbdfc7fe495a8b0f54fbf277e15b4c55.nq.gz
    ├── 293c92fe179267a5e47e4afb54803327ef77479f.nq.gz
    ├── 29882c4c4f91595f3003da97c32cfbaaa68eaf6d.nq.gz
    ├── 2a1db98838cad994d01b074bca56c83b03138fe7.nq.gz
    ├── 2a40e5984099ad10a7984ea3a6690f9520f5fc4a.nq.gz
    ├── 2af1421954297dfb4a2325b2aa11c35d68a69ed8.nq.gz
    ├── 2c6f1b264012389ea93651377381f0f1b82b5098.nq.gz
    ├── 2cba9f3968f7b261b527646812742ece1a50c2df.nq.gz
    ├── 2e443ef402005d090e0ec3fff18b53e1cc3f4b38.nq.gz
    ├── 2e6d8b789d7780eba7aa2a4821650c19f4a4e857.nq.gz
    ├── 2fc7adba0b84eaf86f626bf3ae8c7763274ebd8c.nq.gz
    ├── 305707c9a37681dcff94c8ea95df17a1104dd7d6.nq.gz
    ├── 3091adc8612531b76ad09c79374ea01f213136b7.nq.gz
    ├── 32355013cda380d5eb92d7084d8c200e88a5fe53.nq.gz
    ├── 32468a56311177f82e9270ef75863c6f14c298f7.nq.gz
    ├── 32632919ff96dc0dc5de69db98004450a62bfe39.nq.gz
    ├── 32dd45c1d52413e7241249d40d27c8a1f71f69c2.nq.gz
    ├── 33d080c590672a8c66d1da2b029f0a74e005c719.nq.gz
    ├── 33d27db21b5586cdd98c5421ca1b542a95fbc0bb.nq.gz
    ├── 34189ccc4b25a872073a0d8bd9502fb76a69e057.nq.gz
    ├── 34f275ed3c9d7894766f1b188d9d5e13327f24bb.nq.gz
    ├── 350f8ad10c917390fb8e3e6dbbd3d4b722eea890.nq.gz
    ├── 362f0a321daa5c6e59e406766b73446d157e5add.nq.gz
    ├── 3675877ab31a66b66861e34d2434f5680b0482e1.nq.gz
    ├── 368b1ca133bd6eef18111e13a2e016a039776f85.nq.gz
    ├── 36bec2bfaaf1e124d098a88a7317b6a1f36449de.nq.gz
    ├── 372bb6f68e05412abda219442b2601338fac8da2.nq.gz
    ├── 384e0f7d81e9e674968bb13947036164a4b0490a.nq.gz
    ├── 38d111a54c32be6b0b413fb55758832bbadf1812.nq.gz
    ├── 3a24d542a15ddc1499b634c41a3a170734050183.nq.gz
    ├── 3ae120ff8513cd1b1dcce1e85d5f8370230479e7.nq.gz
    ├── 3b98298ed80d1f7de6196fe9dd8b3bbcc754399f.nq.gz
    ├── 3c00b9cc1ac230cbcece37531be3af1cfbea4381.nq.gz
    ├── 3cb58860cd43b5bf3bf4bebbc0437d5f7bf6d881.nq.gz
    ├── 3cd4e963050d4e9b779fb59432d90a733c7115f2.nq.gz
    ├── 3daf97e7089863e7ba4bfa88e1ba3a43886962dc.nq.gz
    ├── 3efc076e47127cdcaaea39027175fde3fcb9f9b3.nq.gz
    ├── 3f3f57ff39432a80c15dabceb99141bc7ec4318e.nq.gz
    ├── 3fbb94a7b718255dc864d8ee2ffa3e626eb2fc9a.nq.gz
    ├── 4147adb6416ae6b5dcf7b7ab513ce4006d334878.nq.gz
    ├── 416106c45206be3a40a50302709abd78ce18b27a.nq.gz
    ├── 41852dd2ca9bc83f6c0b4cf0b66bb36d1b44470e.nq.gz
    ├── 4242992e0de922b1df110f6ef45bcfb26c031165.nq.gz
    ├── 42f68f7e37577dac5dab5602f48a5fcd969727b9.nq.gz
    ├── 436776428059a5ddc591c2696138af922a7d1ae0.nq.gz
    ├── 43c09401bc839adc93c2bbb41fb1407b09ce7718.nq.gz
    ├── 446900eacd1713a66ed631df0d0ba5e6775111f8.nq.gz
    ├── 44793d510d81ed0e4e29331badb5e158e7075433.nq.gz
    ├── 447d9228a15a58b1ddfd6153ac7f891f10162bb7.nq.gz
    ├── 45021cf633f758d1f30ecd02c3384cc20f7eba13.nq.gz
    ├── 45d5b56db7d5ec7f037317d2adbe93dc6ecdca04.nq.gz
    ├── 465ef3045832a921b14dd4bc480d039bba0d67c9.nq.gz
    ├── 475374e57c7f971702798c14aba6f22c5f8f6a71.nq.gz
    ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
    ├── 48c4b602fd9c4f1bd36677e0d2f190e39cb40d71.nq.gz
    ├── 4a0b1659f797320d39102efe88005fa1b88fe6d9.nq.gz
    ├── 4a49ee8e84459aed8978bc481c7a7519abeeed6b.nq.gz
    ├── 4a7c557d96ccb1d4f7a472aeb2461a1460938d00.nq.gz
    ├── 4bab159bffad82f52f96870a8ed5c46c804aa8d3.nq.gz
    ├── 4cb3311d76ff7badcd6d3b89ae1986aae7c34b77.nq.gz
    ├── 4ceaaf0f6814a3fb786ee8274b6a9acadddbfa5d.nq.gz
    ├── 4daa8201f6fffca9e909fd06748be4bcb87b6703.nq.gz
    ├── 4e53f192057b9c306c4733619e29b01ecd25e184.nq.gz
    ├── 4ecd28a19ae3126793e9c17f3610477ca830ea52.nq.gz
    ├── 4f3162ad508cab26d0fe52d62e9070a61aabaef9.nq.gz
    ├── 4f49b7c407bf3ede49441ac535140bc8045ba4e6.nq.gz
    ├── 4febb64d45618979aceb4e70658a28b6a3d1b8e9.nq.gz
    ├── 50e15993e2c4f03322cfadcf7eddc7f641469939.nq.gz
    ├── 51f3b5fbd56b81bd16baed4fec1715615fd316a9.nq.gz
    ├── 522828f91129937573f4207ad1cac7c5ace109dd.nq.gz
    ├── 5354c70cc018f27bf6774d783a6a92c54dd9f978.nq.gz
    ├── 536d230ec5ebd23b3ada951521971e673ef4fe04.nq.gz
    ├── 53fcf4ade5435f870c15f527dfebd901d6c077fc.nq.gz
    ├── 5416a9ffc5b53178f9a3c14c29b0a26b62883e1e.nq.gz
    ├── 54b9a5b3ba97bd4ae09d72f78ea8f0c0cbe52d55.nq.gz
    ├── 5503bf1450f18d4bc0d13a99de65756ecfb3ec6b.nq.gz
    ├── 555948695c8927947fe0e2cb8df1a96357c916a1.nq.gz
    ├── 56573758c02ead4671c8a173d495c2f8073b49bd.nq.gz
    ├── 56c21625120f611d19c7cedd1904e882fca20e44.nq.gz
    ├── 5788c84bca213b566b3b9b6d5acde45f88cbc0c9.nq.gz
    ├── 57b07a68a2ccdcb1a8bbe9df072f947d4307958b.nq.gz
    ├── 57be344aec28c37199fc06f7cc13037778991948.nq.gz
    ├── 587a1f19ef22fd170206ccba29a6ea744362f632.nq.gz
    ├── 59b5260ee7bbc31994145558d4caf814af56c5c6.nq.gz
    ├── 5af21a5993bdcb40d09b3a2c4e625008298aefe1.nq.gz
    ├── 5bab63356ae1d32d37a579e5d52170b40613a8c0.nq.gz
    ├── 5cb10ec6426b8c3a5ad935f42144f3773dc340d4.nq.gz
    ├── 5cceee30af7db96542bcd84972b2a307b2efbe32.nq.gz
    ├── 5d9851cd29bdddada60dfe20c00b7b43ec758ed9.nq.gz
    ├── 5db6efe7f41e4896edae4a733e1b6b2b5aaf96e3.nq.gz
    ├── 5ef91c1bcd322f3ce4bd33d4e1c98b0c0d5b17a5.nq.gz
    ├── 5f752ba95d8bff26493aac1b54e229371dde7855.nq.gz
    ├── 5ff26d1b943eb2a5bc8bc07ad5a2455ab229b341.nq.gz
    ├── 6082dad7c8207d8aa53c6bcdd2cff24b2878018c.nq.gz
    ├── 60dccbf0519ded59dcc68e575730d19c0e61f6a9.nq.gz
    ├── 61c24f77225c269ce3f2d62572469ab068772f93.nq.gz
    ├── 61c7a096a6cd7676a1f24762af265ffe009ed7e5.nq.gz
    ├── 621184b13e371ffb4c8512d91b26fd64683712b7.nq.gz
    ├── 62dd2ffaa46c82d82825ad1fcb82a9fe669d8cc9.nq.gz
    ├── 634bb6567ade634d73f828ad13dc56c8cc1337ab.nq.gz
    ├── 637f25f509930ba4e18b0b5e60d12cc3f8bd0b76.nq.gz
    ├── 64716c7929690815d856ea59568193caf4f42797.nq.gz
    ├── 64b782d1fd240f75cf47d7529e8ce4e12ba32cbf.nq.gz
    ├── 65081d45b797c168f39c0de404797b8823314d5a.nq.gz
    ├── 657484c68ec21c7c71dc074dd4c16faa53f64e20.nq.gz
    ├── 65d231abc97e17a48cdd9ac6321e50252f75bddf.nq.gz
    ├── 66487ea513ec07938ea26434fcc3e2540ec62e18.nq.gz
    ├── 679829afbe68a2ab20b9eccc73de9a18918a95e9.nq.gz
    ├── 6815407a0d5cacdb3dae0312bb6b28ce2bc77274.nq.gz
    ├── 68502bf78eaf68227caa1968da1ba71569112ae3.nq.gz
    ├── 686c48d4e35897e0d9666ec003c3c60bc459e30e.nq.gz
    ├── 69126a38820957e767e700042bd6e951f67fcc04.nq.gz
    ├── 69d615130503b26e800f2d97b3fcda56c707a5c8.nq.gz
    ├── 6a541026c9557aa29c57941653d3083dd583f318.nq.gz
    ├── 6abc6fed5b706c782dded441399c1d65772475ef.nq.gz
    ├── 6ac3e84dec14f2303057dd0b99e8d407059a4628.nq.gz
    ├── 6c2c2301361dc1e3b14b26ed3df589beaaba365b.nq.gz
    ├── 6c52f6b087573882df9f7077a401c67cc6aac4ff.nq.gz
    ├── 6d4afbae047934f2602fbe9281788f7c68c17644.nq.gz
    ├── 6fc4d3845bc75b2c29a7f1a5682fdee9d7bfe519.nq.gz
    ├── 6fcc0dd1df547cb85c5dcfcc0ff3e7fb9483dce9.nq.gz
    ├── 6fd3de012416f7ad44f35f9360e33aaae9b1b2eb.nq.gz
    ├── 6fda532a94ca3cadd715f7b221fef2867af8d650.nq.gz
    ├── 70d1e5d106d53806570957c52a30ba5632878530.nq.gz
    ├── 715e4d0bb68d3f9fe77277691cbf3a4c6d8ebe76.nq.gz
    ├── 724ca5cc3bac48b3fe80392ed733b3e59f927931.nq.gz
    ├── 74ffc5f1142f6dcb39333c984e588403c42cd11c.nq.gz
    ├── 754dcad481fc958f35f150fe0db6def19e4659a7.nq.gz
    ├── 75b95a2b6486a5465bdd1ad8211a957060942540.nq.gz
    ├── 75dcdcec081019860fe46daa6c3e15f0ca92b84c.nq.gz
    ├── 76a6be01dcc8a827ecb0a6e7beb7bc5d982ce852.nq.gz
    ├── 7702d0056dd88ed68cc9f9bbf8af0d6e132f2fcb.nq.gz
    ├── 77d6ef8d9539837a6bd0ba9c607d67068a636490.nq.gz
    ├── 784995d88c5fce1bddad26b0d8fb0d923e9eab64.nq.gz
    ├── 79f3ea87c169bc4c72e53c7395192012e21bb43b.nq.gz
    ├── 7c5ac7ad0ec66999ce8f4d54f7ed3ce8a39b35e6.nq.gz
    └── 7c914fcfcac0e0ca444e66779bf3030380c73903.nq.gz

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

[jupyterhub/jupyterhub](https://github.com/jupyterhub/jupyterhub)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
