# Repolex Knowledge Graph of piccolo-orm/piccolo_api

RDF knowledge graph data for [piccolo-orm/piccolo_api](https://github.com/piccolo-orm/piccolo_api), parsed by [repolex](https://repolex.ai).

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
rlex download piccolo-orm/piccolo_api
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e1bee6cdda5435854fad7387cd4f571128b766e2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e1bee6cdda5435854fad7387cd4f571128b766e2
│           └── chunk-001.nq.gz
├── blob
│   ├── 0072fd8744eec6b131ad2aa627aed4b325ac23bf.nq.gz
│   ├── 041173433a11dae4997d953df59c3b7b151a3165.nq.gz
│   ├── 05dd9013c005f011a68373202dc1c89756901bec.nq.gz
│   ├── 06b4a0a0e90484bd19c8f3830a11a373fffa7d2b.nq.gz
│   ├── 0838adc4bfc42696b48a3ebdbe0fbb4078331315.nq.gz
│   ├── 0b29566464da2ae65e0ce621c770427712d60794.nq.gz
│   ├── 0c3e479114d74638f03db50ea698d389ca8a1626.nq.gz
│   ├── 0de84e95ce0674474a25e18ede4dfc0bbe69f4b8.nq.gz
│   ├── 100385cd7cf75bfd51f684815440d29db2cf45eb.nq.gz
│   ├── 11aab659c70a595aa25e37ee9f6f7da801f7f563.nq.gz
│   ├── 130b7d6d5a74264329382f98dedd3b1f63562e20.nq.gz
│   ├── 13f4399f3b1d7ed677036fa5e09e4c4f9e8d73b5.nq.gz
│   ├── 173bcce20163bb7d9155181a8f6682f234e7126e.nq.gz
│   ├── 17b759044dab544627c6c0a872dc33f4493d9847.nq.gz
│   ├── 17bacc8b831d7289ffd5794e465938786d251193.nq.gz
│   ├── 1ca5e39e1021e084fa183d35ea5774d4c309e368.nq.gz
│   ├── 1e78c92e7d5db98823b418c2150f6ad456bf6198.nq.gz
│   ├── 1f3c4fb699361701d9e22c61f492d8ba5cf7a1a3.nq.gz
│   ├── 2033083a01a7f2750c455bc90dbd8ab3c0770331.nq.gz
│   ├── 22bd3934b0b4ccf6345888ecb25c6d60ed940b57.nq.gz
│   ├── 236a466cfa78a505d99949c8385a998bfa51439f.nq.gz
│   ├── 236fce34ddd0d71625fceaae140dcc613d10ad1c.nq.gz
│   ├── 24b417c9342209d9e885e3335d63dbbb21062a5f.nq.gz
│   ├── 2560ece2076739dd55db9561b74d175737fa7b24.nq.gz
│   ├── 257f861e1403d8510b7b8bcd134db9843f90efbf.nq.gz
│   ├── 262360024c80d04df31d92aa71d4275a05594274.nq.gz
│   ├── 26fbed582e6af81099424ea9069b688e62fa631c.nq.gz
│   ├── 2b57d90a754f97f4708509dd808f90c91db5c7e7.nq.gz
│   ├── 2c217798802c2597082fd63e50808e2e0bfd6c92.nq.gz
│   ├── 2c5eb60ed76e3ba5c020e2c6d6a85da1d92f75eb.nq.gz
│   ├── 2cbada1a1836442aadd643b1327c6a66faa6df53.nq.gz
│   ├── 2d4d3ddf0a2c3a99208dc0e4644d14d4f25ba200.nq.gz
│   ├── 2d8e42055d1fcbff77f54a5db45ef2c4303f32e1.nq.gz
│   ├── 30d845dc05bb2c844ee4b812fd7870336261dc37.nq.gz
│   ├── 336118f13bd9e0b1907cf6deb571efd60598b2c5.nq.gz
│   ├── 34d83a7e893e93948c7f3c7bebaadc97eb8b1672.nq.gz
│   ├── 3575ea0fd928554f44da1a00336af2cf4971f4fe.nq.gz
│   ├── 370edb886415deccaf77ac1a4432e37b28ff2171.nq.gz
│   ├── 3c6609d5259c0baa231366c2183e98bc2636db7d.nq.gz
│   ├── 3f0524606b35f4d7db2054bca6d351f618bf0f84.nq.gz
│   ├── 40d30b5fafd5c3292e4622c0621f78a781be069b.nq.gz
│   ├── 42e66963e07487779211f3e1a243d12ca6b1b45b.nq.gz
│   ├── 441398b44668dc14897b3b6bb4ae6f8d961fc9a3.nq.gz
│   ├── 4750362d6bee97181ebb2c53320d53c0d2d1faff.nq.gz
│   ├── 48652e34c011f2f4f4661e49dd17f62bd08020d5.nq.gz
│   ├── 492e13ebef36d65d0724eb18c92577500a4557e4.nq.gz
│   ├── 4b33f5563e00478b78011aab0145b78cbf16e228.nq.gz
│   ├── 4f4a5a06ec60aa23502503cdeb43e3d4f6c380c2.nq.gz
│   ├── 5174a1f7995a2c9832e3c0b6f1ebdfbf5de4d9ec.nq.gz
│   ├── 51fd29eb260b3f12ce0d186b175f5acf22d331c4.nq.gz
│   ├── 525b47cfb863ffa4d365bbe93a20317c5884554b.nq.gz
│   ├── 5528c591e0c5020aac88049d0ba2917cb3fe7f34.nq.gz
│   ├── 5549d3b9a315ed9e6346d1d32a8fd48d13780c74.nq.gz
│   ├── 55bd11920d1c78a751bd792db842b4f24572f4e0.nq.gz
│   ├── 55e60debb3dcb3cc32404c692d44f602342090a9.nq.gz
│   ├── 55ed2106c3795b49543e5d41d76110ed832fb1b7.nq.gz
│   ├── 571779a8b401996a206e938a0f16f8efa30ef791.nq.gz
│   ├── 57fdf5767f0a12b6df2d67b7837d9e7149707417.nq.gz
│   ├── 58ffd9161fb6ce3e2b02663aade8c0558ed2e5c9.nq.gz
│   ├── 5918bedb7eec42479bd508aebb81aeae63a28612.nq.gz
│   ├── 5986ad4201d34faca4ee2ec262eea875531f5297.nq.gz
│   ├── 5a1dc9a11f045f4a2e327f56d879747e0f371778.nq.gz
│   ├── 5b8491b4e50f59d2e77bb01f7c0b02d7f045551c.nq.gz
│   ├── 5b9cf60a4265445d6704e84d8ee4648899ebecca.nq.gz
│   ├── 5e64fba65c04767b5de3ae4076335f81f3e63413.nq.gz
│   ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
│   ├── 6255928a7c353fc45c748398a6a207d098ef2e2e.nq.gz
│   ├── 6279723468928a0898239be50f401c4bfbd16cda.nq.gz
│   ├── 63317cc2e596edcc4dde214217f98232f0d2db43.nq.gz
│   ├── 64a41875d3d07ccb51061c35259b3e5bf502ef4b.nq.gz
│   ├── 657d451a74757352b645d7b1afb5e0be5cfb545a.nq.gz
│   ├── 669e5af4c3652fe6b6f216fcf189791dae325cf0.nq.gz
│   ├── 66b8b3d6f1011487c590d5cc76c95fef240f9770.nq.gz
│   ├── 6a4dcb1e102d9e638c4ef64e337c65855001f5fb.nq.gz
│   ├── 6aeb7b159d8244fd3dcabb94b3d66be41f2b30b0.nq.gz
│   ├── 6c52723874548218664af36d8e284ac31f6ec274.nq.gz
│   ├── 6d039306873beb211235e80b68f6172f0fa3413a.nq.gz
│   ├── 6d60ed27d5195bcf1812a931df787430ae24b922.nq.gz
│   ├── 6db38395da8017443e284ffa3357cc97575cfcdc.nq.gz
│   ├── 6f064cbe9ee97954d1c62683d36ba0c26d2b592e.nq.gz
│   ├── 6f374c7a088924e05f0c3a8e79fdf743a97aa710.nq.gz
│   ├── 742b204a4c2bdfe3f3c4657d5fb7ac560e1d7170.nq.gz
│   ├── 74d0fe4e219939730504a030cdda19a265269bf0.nq.gz
│   ├── 759b870c078a8f7666d265744d043b4826d57b58.nq.gz
│   ├── 75c829e7508f31add2a4bb08f777bf756bbf0906.nq.gz
│   ├── 78004f6d3c46da7b4c93fd72dce0f1f193a39aab.nq.gz
│   ├── 78b017f0f5f2fb24ecae96bef96ad4faae6cd653.nq.gz
│   ├── 7b622ee67be921f093d7320af05e66d193b74009.nq.gz
│   ├── 7c0e48674873776204e11939daa11aad95f3b456.nq.gz
│   ├── 7d8634ef7b8e50b9be5f17fb7c0ac41abc58c764.nq.gz
│   ├── 7db234ad306c949b82618acad9445577c5a556f5.nq.gz
│   ├── 7e3a5964f428e316f419967ad2a57803d1b22775.nq.gz
│   ├── 7e40727d2b28d12bed31605095c6c6d10ad9efb9.nq.gz
│   ├── 7e6e92178cbae5b3cd7cb9c0ef1051fe1cce7339.nq.gz
│   ├── 802a83cae4b17023448c24d2d7c2c4b30e2bb94b.nq.gz
│   ├── 84def3cbbfbafee61c3a021ec327758cc4627f25.nq.gz
│   ├── 8528bd5adfb2fcb96469caf238df581334a28a03.nq.gz
│   ├── 8551789ed9ab0f98c558320a893efe994603b8d8.nq.gz
│   ├── 85c6ef5c0d8957515fe23d37a9813e346de2ec01.nq.gz
│   ├── 86621d9639373be36545723156a5112a93da4e45.nq.gz
│   ├── 86a80803764a60acd5b7925b086018357b350079.nq.gz
│   ├── 86cdfe9666ea13c7dcf5c5055bfb365e92206474.nq.gz
│   ├── 870a0f5645e4e8b16512df3205d0a1555f2053e8.nq.gz
│   ├── 871605c5a5f45814548ebe60d0ba62a66fb82935.nq.gz
│   ├── 8825471d00db3ede651c2c4f58c955d7da6b4092.nq.gz
│   ├── 894082b674f91b95f82d89a16114bf52e53ff470.nq.gz
│   ├── 89c920a9deb0a5f30026f7901ba71f20f23c065b.nq.gz
│   ├── 8ae65be7fdfcd00435bafc4e47c06b997c1cbac9.nq.gz
│   ├── 8b62ccee59b55439e414c5f0f25104d18fc644fd.nq.gz
│   ├── 8da7550bfc64b6be1940465058167831a43cfd6e.nq.gz
│   ├── 8e31180d5bc1ecd0b36688de862f54063a16d5a5.nq.gz
│   ├── 8ebde60f05ca32dc53d8e461bda20ed31553fa3a.nq.gz
│   ├── 916a6e335a40d73583c02c43384d66c11f80be49.nq.gz
│   ├── 9322be5d316364842a83deeeaf0cb0e8ac424280.nq.gz
│   ├── 99a8fc6ccdcc7301e36a792086536d6c5873b325.nq.gz
│   ├── 9b582dbb41d99378c1391a7004be90d8ca67ceab.nq.gz
│   ├── 9bafa0fd1555a619883d44c817b09e59570c7722.nq.gz
│   ├── 9ceaa4d047d306ad8869062d54130b7c21b3d60c.nq.gz
│   ├── 9d277594cebae777411f02cd0a503888b11e6706.nq.gz
│   ├── 9da8b072f244375b701894b3480262b9519df896.nq.gz
│   ├── 9f8b139f16bc11bf4999ddb8f0b86ef5201aeaae.nq.gz
│   ├── 9fb5b4246681be1c08f92a4f44390afbdd8c7b60.nq.gz
│   ├── a054638e41ff0e15a77e31b654127fd35960b6f1.nq.gz
│   ├── a06455e19aab06400032a34be705084cfd1fe1e3.nq.gz
│   ├── a1bba93135590065ddd922ecfd26692917c53874.nq.gz
│   ├── a3f61b9bfd8b22e7f49512675a3682e564cb33a5.nq.gz
│   ├── a4deb46e767f1f1428b2db5fd736e4977cad3517.nq.gz
│   ├── a4ee526deff7d4080d3eb10286016946dd0f9de6.nq.gz
│   ├── a4fe7403feb68803462fb585fed9cec401285167.nq.gz
│   ├── a8b02e90ca2c8b6156adf3c36b4ed5c67b90b2f3.nq.gz
│   ├── a99dd743dd57740b46bbb4978b8492b6523765cb.nq.gz
│   ├── a9a82887a625eba1add4fdbb0fb6797e6a2b9b70.nq.gz
│   ├── ac75494879f071e4ef0e766115b79787afee59f5.nq.gz
│   ├── add14e2b899d4e34525a4f8df048041110f0ed1d.nq.gz
│   ├── ae3ecafc38ac93f7480404e6fe17dca80e82df48.nq.gz
│   ├── ae528e2edeb17d18d97b218ef5ad3e8f06bd6875.nq.gz
│   ├── aeb777c4e5fd0de5ceba9227e294dd35ee040a62.nq.gz
│   ├── b08014e7a8e3cb4a9261015a7b7d7af974880592.nq.gz
│   ├── b0c6a2c0ad79acf2e07eab093e1a94a01b34f28d.nq.gz
│   ├── b1d163a01495fc6a8b53ddc46ffd01a37487576c.nq.gz
│   ├── b28d2a603788c4568fb4c6b44687d9082f988525.nq.gz
│   ├── b35557d58ae8fdb81f0dac7a4a93a1290101f505.nq.gz
│   ├── b5cd0d51a06a92426e377427423e89ce2cdcdd2c.nq.gz
│   ├── b5d082b11e535d9edfff5698e0e330f8d6513277.nq.gz
│   ├── b690eb4eede0c247183589d0d3c799607ec38073.nq.gz
│   ├── b922908958922db2bc8533ca3762b2caacfc81d2.nq.gz
│   ├── b94053110a5ad5937053ec850e7da53bee91a32e.nq.gz
│   ├── ba8c2c6b1085145624a9be7455f81213bd32f016.nq.gz
│   ├── bd5c8128c121277bc8604d6cf0a52df23592c848.nq.gz
│   ├── be459dc74c53366e003f86d74ff9d425a0acc0b4.nq.gz
│   ├── be7e67c9ba7c622425581f2518b32ed73f592b5f.nq.gz
│   ├── c0797b77a24ecbb10e4b40a7a08d1247b348e582.nq.gz
│   ├── c203fa4a48f478d643dc620617e3f1b32a331075.nq.gz
│   ├── c231d0ee77b84250fc0c16ad2e5d5b69be541f28.nq.gz
│   ├── c3e82382a064be3cab0ab1753cb54d08419cb22b.nq.gz
│   ├── c497dfb5868d0791027628f2fc927f8a1f4eba8d.nq.gz
│   ├── c7653ad08e8837948afc8f672eed02f08df47715.nq.gz
│   ├── c78154964c50688293de6f85bb0301014cb3631c.nq.gz
│   ├── c82e7a706f005338de2b15fc4f19507c21486288.nq.gz
│   ├── c8ba4cf77affaa3e0034e1c22c4d728e77e5410a.nq.gz
│   ├── cb5c0d063d710dfa917b0a72b85031561c7393bf.nq.gz
│   ├── cdde48f0a6b9748f18ae2f2d2c9bec394206e95a.nq.gz
│   ├── ce09290a585c246ffe74f87f367c0a906ffcac1f.nq.gz
│   ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
│   ├── d59081604cc3e99c595f30732d3b883b32ca19e4.nq.gz
│   ├── d741b5f4592007204077d6b6551f9fc885a542d9.nq.gz
│   ├── d75703e12bd0e1914c7b3fb10a4ed8016378ea1f.nq.gz
│   ├── db058be8ef0f06ffdf16d52060dd9610d2bb25c2.nq.gz
│   ├── de8006e32036d1800205550705ef34fbeed636b9.nq.gz
│   ├── df6daa9e58fb5603ad41cc48b192df96cad4bf77.nq.gz
│   ├── e0479d45ae352e51c233f00e2ea5900ac47de423.nq.gz
│   ├── e07d08c11200992b6fc69b15cc633be6af3f186f.nq.gz
│   ├── e28a0c1ceef54e2c6157eecab360998c0b74d639.nq.gz
│   ├── e2a8a989d28953bfd364150d9647cd9e424e866d.nq.gz
│   ├── e4dfa5f0abf58f73cd11d788510e9685a31e0f29.nq.gz
│   ├── e51ea4c0f9cdf9c020d97b3a891b128cff559246.nq.gz
│   ├── e560955c45c94b5ddbc619075aacb2027cf00bfa.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea506142688990a19143192704a6f7a2faf460bb.nq.gz
│   ├── eccfc7f3527a6063d8b414b6a968706a60240642.nq.gz
│   ├── ed8a94672d1ed3324dcd086b85ec4002cca10964.nq.gz
│   ├── ef5d2ee5a5af3ccb05d997e586015e98f527bd6e.nq.gz
│   ├── efd7f666e846b5e0e09c7e8c308b80ad786f2370.nq.gz
│   ├── f039f83b0e8d0238bb1180fca8d1b45fd5a98670.nq.gz
│   ├── f0921428be61cdb0ad2a04dc4ab45facc8cc2b2c.nq.gz
│   ├── f28f4e1adfaee887128c5146a6bfffabd100d671.nq.gz
│   ├── f2edb08d366326aad35c805359e5b4c1bdb411a3.nq.gz
│   ├── f584a5e170c48b853c43fd1698f0304dee19f6d4.nq.gz
│   ├── f69d8a9173cca6846ddf2b7aca3198aa516111cd.nq.gz
│   ├── f6e5248877fffe0fa207a6cfe8ff69d26b67e658.nq.gz
│   ├── f9ee2f2acc7bc4196d90e9483106ab88f89cface.nq.gz
│   ├── fcaa73418eddadf73eedfb97dd36b6c32ce317f9.nq.gz
│   ├── fcd51bd612dc7eb9d8a1eb9f7ab60b794b157514.nq.gz
│   ├── fd4ab6ad899c6c2205f5834ee48214e8916c8f84.nq.gz
│   ├── fd58fa03ab96137d8df306398065ae26df15a514.nq.gz
│   ├── fd74da034c9a3dc3ba443aa972006cf865f39b0f.nq.gz
│   └── fe4c91ae3df8728421275742710d7ad5b7a742b2.nq.gz
└── branch
    └── branch.nq.gz

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

[piccolo-orm/piccolo_api](https://github.com/piccolo-orm/piccolo_api)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
