# Repolex Knowledge Graph of facebookresearch/mmf

RDF knowledge graph data for [facebookresearch/mmf](https://github.com/facebookresearch/mmf), parsed by [repolex](https://repolex.ai).

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
rlex download facebookresearch/mmf
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 72f898ec35af86567423c7a019dd1dc5175d1a5a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 72f898ec35af86567423c7a019dd1dc5175d1a5a
│           └── chunk-001.nq.gz
└── blob
    ├── 009e9cc280f16221d6406295408c07d0539403d9.nq.gz
    ├── 01cc249ec1d4349196e67a65135248889ef49af2.nq.gz
    ├── 02e1b285ad65c4da85bed1068215dc1174085e93.nq.gz
    ├── 04a849c6d35efd912dcac16ba67726ef0f074dc7.nq.gz
    ├── 069e3cf19446eaeef8e6ed175f16df9a4492be06.nq.gz
    ├── 074f8c658338d08c0d76f8a4173ec73ee8562237.nq.gz
    ├── 0754868769a2d2aaff9399124ee472265b6d4765.nq.gz
    ├── 0876968452a6be4686ab891d3347f8ddb0fdf5fe.nq.gz
    ├── 08f04ed1ef8df25b2bcd83ebcf067099327ecdb2.nq.gz
    ├── 08f7bcecfef4206308c89b652fe104299c686d13.nq.gz
    ├── 0941061aa0d4fc5dfcb941e0a32cb1bc057b52d1.nq.gz
    ├── 0987317b0c301b783ac43d57de01b6fa1938c60b.nq.gz
    ├── 09c06763aea3ee149c757e60cc6e64615fc9ba5c.nq.gz
    ├── 0a097a7b6a7370f6ae617e14e913dc796f4d8e11.nq.gz
    ├── 0a105fb758b4ca65cedf0bf4a9c82ed7a179633d.nq.gz
    ├── 0a6c77a20d538eae482247334cc8436e1aa8d6f3.nq.gz
    ├── 0ac05cf153c0fe8b7de1ecd51fb696b7547ebd56.nq.gz
    ├── 0adc5817cec66cf0af6c8f5c9a07abad9750b977.nq.gz
    ├── 0af2fc8fe3c0539490ea50a59628d205f4559e02.nq.gz
    ├── 0b5a52ace0f5d492dfc287e069cca1ec14f687c3.nq.gz
    ├── 0ba7f733b3858d5a20cf88acedbffe863fa47d19.nq.gz
    ├── 0c378f3008c77df14d4a25bccc264a92b5185d9d.nq.gz
    ├── 0d5b6ec2f18bf970a8ece07b25436b623e6dfba5.nq.gz
    ├── 0dcdf4fbb2cb9c34c8da1f0bb2322d0177414f7a.nq.gz
    ├── 0e22b960c50bf9f4bf0b2ca99a18326342be8457.nq.gz
    ├── 0f582c586f92ad3fb99ccd9c44c50a62e9ee5f4a.nq.gz
    ├── 106475d02799743a6b2310685301dee8015918f4.nq.gz
    ├── 11367519ec7fbb21b338a64bde803db7c07d8d04.nq.gz
    ├── 117bd787ce0270d18776203713d7200649afc7d2.nq.gz
    ├── 119cecbd7f54b756f15f1ee603b468632d0fd87f.nq.gz
    ├── 11fc7845d1d55779b155a39922700bd2d9f7a547.nq.gz
    ├── 121f2c61236cc090689a68d2b9c1922f258ffe12.nq.gz
    ├── 12e0658c79dd8f67b5a13a4256d5b6f5d8c13169.nq.gz
    ├── 12f7ef1be7dd605bdaa5048020b5571c9f99ea0c.nq.gz
    ├── 138a66a154559550c0a57af5613b797cc629e8f9.nq.gz
    ├── 13f651488ed122ad86c0b63ef0d8f66fc3922921.nq.gz
    ├── 142f90dab7a7dde69a55ba4ba458fb8d421877cb.nq.gz
    ├── 148a9cef78edc7452219ecec4840ee65f5da7bdd.nq.gz
    ├── 14becf77efe315fec541f4a84d954a1b5143af35.nq.gz
    ├── 160ad206c9fd1467d658077bbecf53edc3aa1e93.nq.gz
    ├── 160f4afcd26b1f6ca5fdc924e1296f88a8f438b8.nq.gz
    ├── 176ae9ea865200210b79a2f740be094a9689791d.nq.gz
    ├── 179650be015e41b311b17873dd944ac29b36799d.nq.gz
    ├── 17d3c523b438e37a106afc6767377332485f3353.nq.gz
    ├── 1868c5a1a9332410751255bf140c074401ae6b1f.nq.gz
    ├── 18e4f2db974637178158f594e885ae82aa996bde.nq.gz
    ├── 1916054758062a17771d4feabfe89e41aa052185.nq.gz
    ├── 1aa951db55a4660b398e5f51905d1ec334894a60.nq.gz
    ├── 1b250a4f4a70704782b984b51966272bbca89bda.nq.gz
    ├── 1bb736765a6b1b4ad5d9aa2e07f813931992e599.nq.gz
    ├── 1bbb77b638ac6e28a7615efb9eb4626449f15868.nq.gz
    ├── 1d1544b08cacd0540a28fcd80ad58330ef7219d1.nq.gz
    ├── 1e6a59bd0b4b6a9672c0818feefe08e8f2fe313c.nq.gz
    ├── 1ec02d02d2233009330d91f1dc535d1adf817286.nq.gz
    ├── 2052f58ec8ff72787433dfa8140a0013788db4b1.nq.gz
    ├── 20987516eb7a587909fa6e3fe7aea7e2d02e1f87.nq.gz
    ├── 2291d0c528ac1d7ce8b74b0cd6b10d34f7e63d84.nq.gz
    ├── 23119f1597de3d8755e975300602263082514888.nq.gz
    ├── 234a68a112b1674645025dedd64d5be89762fb3c.nq.gz
    ├── 237ac6c0aab9f90abdcc6344f0167b13f7f951e1.nq.gz
    ├── 249d3b7910a145d438004354c528099cec737345.nq.gz
    ├── 24ee7e6038ef2f0c2bc4f2b057cfae471f67c745.nq.gz
    ├── 25bcfe886bce03fa300c0d423714fcfa2320a144.nq.gz
    ├── 25d0c73caab1766ddf671b974d32435c408c4942.nq.gz
    ├── 279ad4d655eb6c724eae0f4cb7d49374b9cbcfef.nq.gz
    ├── 27fe986fc7f1521d4ce9ba2c625d205ec9895f2a.nq.gz
    ├── 28a301ae63b6d06e2b7bb895b12315b9cb5e4920.nq.gz
    ├── 2913c9d876ef7622f64cc16006fdda07f690ce73.nq.gz
    ├── 29b273842aeb4cc0b3097007252eafcb27698057.nq.gz
    ├── 2b4c2448da15124c49c24435be30efb3b786a9b4.nq.gz
    ├── 2b88655597019e5f904781587abc691241eeaa16.nq.gz
    ├── 2c087e6b5a1b962081f4528aef6d8dd143820ccb.nq.gz
    ├── 2d13113d45375fe02a636030329fedd8c82c7d70.nq.gz
    ├── 2d80b1bbea531fec80d0e889a826620561d7aae9.nq.gz
    ├── 2db84e3608b404e604a35ad08d44171cd8ac25f2.nq.gz
    ├── 2e136ee519375bb70a4bfb9ccd96385b1d39e5cc.nq.gz
    ├── 2e3106cfa79f12af6c1ae59aa26455eeba5fa62a.nq.gz
    ├── 2f178eb5c45ca68b54eb84c9740ab53981009606.nq.gz
    ├── 2f30d5f8b77f9a6df45705f6b5721158c72bd580.nq.gz
    ├── 2f6e41df16e4f31efd38ed1b58a410cb2e3dc4b2.nq.gz
    ├── 30c1978dfeffcf3181fee95201dfe60f13d435b8.nq.gz
    ├── 314d395313d4a7cd5378f9f89db8289ce525d37c.nq.gz
    ├── 320556e15d8b0df0d846ef33909a582ef1ab752e.nq.gz
    ├── 326bfc37917fec84716854937b677e92e50e492f.nq.gz
    ├── 32e4b337d84094a5e68173031b53431d6fb9f2aa.nq.gz
    ├── 332ca6c85ee78b230360c5aee3f6964dd208dc2d.nq.gz
    ├── 33420ed7660967be8b12d6946252a1750337cb92.nq.gz
    ├── 336ce3d65ff91e3792fa3a9d9d52fcbaeadef02a.nq.gz
    ├── 337352fbda52bb36e4bc96f2ab8f876d46d3e789.nq.gz
    ├── 33d8fb83ff0435c4692ea4d1d2b7b24ecfb49bde.nq.gz
    ├── 33f688bb11a723a42495b3d30aa4f299c1ea3592.nq.gz
    ├── 35642b1024eb8f0e2fdaceb8c5865c546deeac1e.nq.gz
    ├── 363d2bb3878a5aecbfba2c3082b17e30233d1d24.nq.gz
    ├── 375096aa6c4ce52de07442ba3cb038c0f2bfcb2b.nq.gz
    ├── 3860ced5d01d5331eb4b93f4dbc78cec62a22fc6.nq.gz
    ├── 3873c03d3a9e42e4017ec4abaf95b1b8f1d0698e.nq.gz
    ├── 39f9dead0193d91f61449c924a5c66040b3d721f.nq.gz
    ├── 3a2c29d4ef1f3579118ef93563326230899be3cc.nq.gz
    ├── 3ac79764b096e7f4a2298be5eb27180208c8f11b.nq.gz
    ├── 3ad833c4bd7da7ef6ff09f3ca61b09f2339ff337.nq.gz
    ├── 3bc021d4558cc6b1c5a82e814facba2d87c2b3d1.nq.gz
    ├── 3c45b8f3835c883bbe439bd2d6372a2e180000ca.nq.gz
    ├── 3fa5b000b77eec6fe4e832442521759f978caafa.nq.gz
    ├── 41237b28ea02807dbf73e273a797d6407bb5bc00.nq.gz
    ├── 41a65451353d33ac01c71f1d31e35edf0e3a01e2.nq.gz
    ├── 4217d3e3d61ee99007e93777cd4cec93cfe441e0.nq.gz
    ├── 4296fdc253386e0981be8453080ef8c049c20ad0.nq.gz
    ├── 42dd7ed41dc7a951aa958f4adac5d1428fee43ef.nq.gz
    ├── 42f2dddb106ff95388edaf6eddb90fb2c3818537.nq.gz
    ├── 43630775305fa2abbc966a1c4986c2f56e28ce6a.nq.gz
    ├── 436817ebb8eceab02ccbf9970b8cf4a881e2cb17.nq.gz
    ├── 4377cc9844b923e79830c553164dd9c94bec6398.nq.gz
    ├── 43d1bd9c35baeecaebba15fbcf64dfaa3c237954.nq.gz
    ├── 43f67cfd6eece49057e4680225ffc188e1e6a580.nq.gz
    ├── 4567ec1a293587d9b4f4037e6c82f312d4bd1774.nq.gz
    ├── 4574877a9f1b2831fdc767a5887d117ed68fcd97.nq.gz
    ├── 4679bf6cfa13ba619dd3d0910b06f03adf102799.nq.gz
    ├── 46a1bff63ab194c9cca1ebd730d8a9b568f6794a.nq.gz
    ├── 471c002e83092ac0ffbd23eb854128cba6bef36f.nq.gz
    ├── 48897b0464a9eed83e44ab7b1502efebd49df39d.nq.gz
    ├── 490d061be225094fd7bc215e692963446402e97b.nq.gz
    ├── 496bac4e15d8abfdbecf899c6fbb48fbcd5e57d8.nq.gz
    ├── 49961fc68adeec91b6d1be263a76a656db2ed967.nq.gz
    ├── 49c3aaf30c0a27917404a1b942895c6747501fad.nq.gz
    ├── 49f567581a1ea35d99db9ced7f6c3cc5354b0fc4.nq.gz
    ├── 4a58921b8a0686e799784a17445bb464c62300d5.nq.gz
    ├── 4bbfbf1931e085cd83fd934a4a1d5b57cc3beaf6.nq.gz
    ├── 4ce1ff436f038aa4009a574f0219c19821392a4e.nq.gz
    ├── 4d606497f2d7fcd71578ae93adcaafdc52454a17.nq.gz
    ├── 4d9da5d865a2ac307edabe262c9fda85a0c35a08.nq.gz
    ├── 4e12bbb0e749239d2530460c24cefd577c7e3d1d.nq.gz
    ├── 4eb43b2721abc6407f17ad3b8343b4cbd4caa8ca.nq.gz
    ├── 4fa0b310bc4c8224d6e3067f8307ae01d500c279.nq.gz
    ├── 5105901925ae80e4622bc2f7f36f44b7e2ba064e.nq.gz
    ├── 51979a2af572bc521aff80ef397d7480a1cb8653.nq.gz
    ├── 51dae4b3600f3b4f846d24af36dd546383f91364.nq.gz
    ├── 520ecadde64af893c68f109a7a1c8908a50369fb.nq.gz
    ├── 52163467449e781ecbaee4b08f08313a32dd48e0.nq.gz
    ├── 5282afd0866dd16edf3169a8c491fa0a0f918ccd.nq.gz
    ├── 52ee9bf97b9578a74966ab78f119eb10a679880a.nq.gz
    ├── 53e405691f8a835fd68cbcfd31501eff491a4bd5.nq.gz
    ├── 5456c73d8def0b98a8deb7829faba732b9f2bf1b.nq.gz
    ├── 551ab663e864d44fbb31cd6a7787604559ed67e9.nq.gz
    ├── 55f9e8221929f81ac228455009ac7da9267e3ea8.nq.gz
    ├── 56620b80659828fb2a885816cf09021ad6a3e9cb.nq.gz
    ├── 56b3697fa707cbb1501ed2fdecb9743ae9486187.nq.gz
    ├── 56e763bf91470de6a0d6d4ad6d84ea61ecdf5df6.nq.gz
    ├── 586275de4c99c0d670d1a5874f63b94114e11f60.nq.gz
    ├── 58b3aeeebf47c205397df487b7a3378aecee1f70.nq.gz
    ├── 58d880daeddeec0a9a0a255da0ff98fae7203407.nq.gz
    ├── 5981b31f25dcccd0a92f29064bcb21de0bf3dc9c.nq.gz
    ├── 5a60b83f6f54b44e50bb0f1d0bfa5e18323ac3f2.nq.gz
    ├── 5a841fe88edac5dd57a53b72bbe4e31e2e1d7800.nq.gz
    ├── 5a9a80d7b159acb84992351727aa9b8c995557d9.nq.gz
    ├── 5b28d53b6bbd5331da9bfd575b4bbbef67e30191.nq.gz
    ├── 5ba1c7f1892940038ee9be38a6b9be1ad6760a14.nq.gz
    ├── 5e45d5302e2db5d3b2a6d5d80a1b3bcbff5959c4.nq.gz
    ├── 5e56ad0347396fd86700d9eefe451b4c058cb503.nq.gz
    ├── 6168c2a32bc1916c7446ae75fcd74ee317688940.nq.gz
    ├── 629c44358351e17292ae44f67cabfaf46a55029a.nq.gz
    ├── 62f6102b9706422c3558c582adc84e545cadba6b.nq.gz
    ├── 633c233759cfdfbe9fd91de322db3434a7c903c9.nq.gz
    ├── 633c52e2e206a1827fde1cfb19ec74a357a72319.nq.gz
    ├── 64567f8e0c5af3573e29414a8f8b1e18e12e11ce.nq.gz
    ├── 651b7ada9842306b289b4a2082bc4348e49387ad.nq.gz
    ├── 657ed1d077b47685c82fb19bd3140e10355b8843.nq.gz
    ├── 657f72741a4e11c2e6c04cf0294af8b53c6cc46f.nq.gz
    ├── 663541bc7229489508d585d7097cad931c1f05a9.nq.gz
    ├── 67459a83d6f0c9aacb45400261a057a2048300fb.nq.gz
    ├── 67f0f2d2f714d1f1179b567b96c30063295bc619.nq.gz
    ├── 6855aadc8065ba83b8e45c4145ff1a6898d29196.nq.gz
    ├── 6876434740def64ec97f5620a10abac764d94934.nq.gz
    ├── 689f115f330132b1b729b086b7309a2167c7ba11.nq.gz
    ├── 68e59973075441e899e01ceed8a2b387370b40a2.nq.gz
    ├── 68ea8080a15cbda961c6dd4369cc90c887392b32.nq.gz
    ├── 68ea9f3eba4594133c9822bb4be877b70fba775d.nq.gz
    ├── 68ef30c968a5055e9c49dd0b851ab0206b5c14f6.nq.gz
    ├── 696a38ca3a63f3cf977916e0319c380396192ed6.nq.gz
    ├── 698e24cb8376989c405899c18b0f37dc07f2cfdf.nq.gz
    ├── 69928e1814f479e937a6f53726224f10162efd74.nq.gz
    ├── 69d97c07d3cd0346e7db8792ec7c4ff784f03665.nq.gz
    ├── 6a2edbcf4721ca898f30aaaf10a90f38958addb9.nq.gz
    ├── 6aa7dc734aeed161fbab600898440c4836d7f01a.nq.gz
    ├── 6abad64c5b0ec7fafdf821f95ad0532e056b7a48.nq.gz
    ├── 6abbe2779541fe2ae220cd1131a6ab5421155f92.nq.gz
    ├── 6b2805cc6e1961f1650026dab6b87537537b0934.nq.gz
    ├── 6b6fc54527d83196f9d7f0149c6336ce7754c2d7.nq.gz
    ├── 6b938fbcc1c7029049a94a7913ab6b1ef0473fed.nq.gz
    ├── 6bbc92cfe2a55c43e93445931e033293b1dee387.nq.gz
    ├── 6c0f25b020bd83d08e51e5ad2b6facb106eaf0cb.nq.gz
    ├── 6c2627cc9718e73c999edf2820b361b85abc5246.nq.gz
    ├── 6ce8e0a2fb7fbe6ba966f64384673f27170b126a.nq.gz
    ├── 6cff0a9d922b0804fabed337ef0c3f186438cf07.nq.gz
    ├── 6d5c839d4232d8c8bfca191702e1763e48b099f8.nq.gz
    ├── 6d66ef66236de7c6dcdd21a0df1449f8e0870ce5.nq.gz
    ├── 6d73f32116bc47437d1c8c2b1e0ec8470b299997.nq.gz
    ├── 6da78a97a966483151961655eccf90bbf2ee1281.nq.gz
    └── 6e0dcbdcf99296ac830d091ac8a0fb8949e7357e.nq.gz

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

[facebookresearch/mmf](https://github.com/facebookresearch/mmf)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
