# Repolex Knowledge Graph of NousResearch/axolotl-func-calling

RDF knowledge graph data for [NousResearch/axolotl-func-calling](https://github.com/NousResearch/axolotl-func-calling), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/axolotl-func-calling
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a3595793712000921a94440e8272723a733d6f57
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a3595793712000921a94440e8272723a733d6f57
│           └── chunk-001.nq.gz
└── blob
    ├── 01241c2958b14460cb5cd3ba91671fc05759dda3.nq.gz
    ├── 0269f90157b12c46a460545842d69da65afc394a.nq.gz
    ├── 02bce8a338e84118facd5e7e258a8e9107a57b3c.nq.gz
    ├── 04ce5767dd75a000007fa01b15744f4bc459595c.nq.gz
    ├── 05beda1caa348f6f6e9755d291819c740bd05096.nq.gz
    ├── 05fd63ae80dd07e2c26f7b33f8f36f4846042b09.nq.gz
    ├── 060a5c5c6c7e6452095cd0dd52c25631bc23d083.nq.gz
    ├── 07078850fbb9454b270253765e631bfcd78cf988.nq.gz
    ├── 079a8e924e2bc9189c2cba396aca80d3fffd940d.nq.gz
    ├── 0a404c79d85114359412622dbc642117a5fab7f7.nq.gz
    ├── 0a5223bcac7dd5cbe505522696e2b38aa3e81be1.nq.gz
    ├── 0b5ef767160231882f27a5c55efb071970c429d7.nq.gz
    ├── 0f5c67a1922120993bd350eb1213e2d331478b76.nq.gz
    ├── 123ffa7109a439845c88039cdcb3968da0b26a16.nq.gz
    ├── 1275906804b0f6908ef94be9b94d4a83960bf148.nq.gz
    ├── 12c55688d2aefc559e8acde1a6fc354ce863fe19.nq.gz
    ├── 143f070f2a9f826f6ed83e64305760229f535173.nq.gz
    ├── 15b280a1f03af8f14d790790fbc46acbb95009ea.nq.gz
    ├── 15bfee8c4756a51538dc2db38351d0ead650d975.nq.gz
    ├── 15cd4591041f488fcf49ce576b2cf69fa4bb6db8.nq.gz
    ├── 16af089a063880b75b8ad1451de1349b9ffdee63.nq.gz
    ├── 181e693cf95907dea33f5c337c6652e7b28bfbc1.nq.gz
    ├── 18dd86e6b432ebc497a44cb3cfd1b3088a8970ec.nq.gz
    ├── 19042639f1a3df9b73b230f2d7a97dc399de56ff.nq.gz
    ├── 19f8217e0459ce465623d3bc437eaba76c5aec60.nq.gz
    ├── 1b9e8022e33fb9392bd1ce549d8c03892e5f22e7.nq.gz
    ├── 1d727ed8bbade96c4b580376daca85d683290b0d.nq.gz
    ├── 1dd46a93ff217faabcb5be37eeaa6a6489149133.nq.gz
    ├── 1fc470da9e925bb046dbb3b2d5c0781fec28c0bf.nq.gz
    ├── 2002bbbaf1b8781e9f632856c032702151895bb2.nq.gz
    ├── 21c27db852b0c6e8e00d28a2ebe666f3663c5784.nq.gz
    ├── 24c0b041232f59e3df49b933bd1361000aa68b72.nq.gz
    ├── 263caa393b16cfada612e3f98742e37830403d2e.nq.gz
    ├── 2c27af1aa07c7c053413a5d78a3df0e9bc7e1f85.nq.gz
    ├── 2d5ac87a17c220aa4629244c2d05abef5f8d936b.nq.gz
    ├── 2d81286aee751afae8630a21986eb04f36e7e6d7.nq.gz
    ├── 2ddd711e29a34b72f34efb5745e241ca8e015675.nq.gz
    ├── 2e9364e3a5faa39a6084d259a4cb2d876a9f2e57.nq.gz
    ├── 2ec94f8684a3865d654c90f4cdeb69a4fdcb1558.nq.gz
    ├── 313dd24e8c18b0a6a3797677653f139902e8a3e4.nq.gz
    ├── 327dd9b6348159942de6d991cd7fd1730d2f5792.nq.gz
    ├── 3285e667cbc36b03e596e548c0321352b1dc25a6.nq.gz
    ├── 348a573a1c58e8112dac16c6772de5fe90bb15bd.nq.gz
    ├── 357e0ec50e1a055f28f1a26e39ca3f2c961a6954.nq.gz
    ├── 381cf21ac1323fb98cf044b1b19e7363d11d41c3.nq.gz
    ├── 39b6cb74e1c3b7876806dcbcd6c8a34df8e64e22.nq.gz
    ├── 3a9f21da0cf42558c832437f95a17bcd3ea753fa.nq.gz
    ├── 3b68a7f5477bfc96b3e79f86f5b9d4063b18f4d3.nq.gz
    ├── 3c1c808005e897d0289692223a184be76d385192.nq.gz
    ├── 3c9f03000720a16fbf17d793716d6ca4c4732cc5.nq.gz
    ├── 3d6218b308a3133b35a1507a04360f8ce094a204.nq.gz
    ├── 3d636748903ef1b6a06d81511c00d3545101ef80.nq.gz
    ├── 3e6c7fe620af2b513f2fbc1372cc19ba0fd907cd.nq.gz
    ├── 3e9501a54f61577ab8f7301b6caebc3d4802000c.nq.gz
    ├── 3ea313c838cf69e930dcbe82e268efce049ffda3.nq.gz
    ├── 400201fc97eeed5f4b96f2371b2a735c6c9d5129.nq.gz
    ├── 404302c81ea643aa841b6d1639ce6f95090ebfc9.nq.gz
    ├── 42217dca31ca758d822a97655350793fa4e4dc59.nq.gz
    ├── 4521cd07bc39e6bf8c3486ea6fdf6af258b8f3cb.nq.gz
    ├── 4529a912dc3a14fa319a5bc2c552219551715818.nq.gz
    ├── 45e31266f1a73057c2f4cc1aabe7b01749a8bc5e.nq.gz
    ├── 462c2d3e7bb167d04f4bec5da151dbc66eb8a608.nq.gz
    ├── 467c06ec87a43569560264c549332dbc00b57b7a.nq.gz
    ├── 48f22790ac50d99fd0630b9c78d832430b198985.nq.gz
    ├── 4a7ff5d5d6c1a9fee50a6d182728df3c851ee6c0.nq.gz
    ├── 4b5df167b61d26ce682651410411614ca84a7d92.nq.gz
    ├── 4b7334cc154310025e28325e249f81ab0ac65652.nq.gz
    ├── 4ba130c9dcae876770d63520c2220f2c4efa8180.nq.gz
    ├── 4c05113f55e0d796b2a7b4035b0b51768c04d769.nq.gz
    ├── 4cc6bcdcc9dbad45bc467eaea946c1f4b9241ca3.nq.gz
    ├── 4f6ea8de73a35dfec18cb813a9c23e9f09f831b6.nq.gz
    ├── 501a866b2d872adc94c09b3c864fd31c3e5bb986.nq.gz
    ├── 50f39d60f5f0a09a05796ba87592dc5f426b4446.nq.gz
    ├── 5160ee8d7e06a6d7c2dd3d0d9ae401ba3a288ef8.nq.gz
    ├── 528f9c8074842a31126e446bb8ec642b3033a9e1.nq.gz
    ├── 52d77c00cf9333a7af09c018d0126bd8fbf8a1df.nq.gz
    ├── 540c5577a0396788c6a824aa0ebf5af36aa79dd7.nq.gz
    ├── 562806287a31e70f3106c80413db395a17685c6b.nq.gz
    ├── 5738bb543cf53d64e81ad61fee3e08390fc08c39.nq.gz
    ├── 57d85e51eb9137f3032757f7da8972e9b69f779e.nq.gz
    ├── 5a42e2a9520110882a9952cd7a6bfe68185f79d7.nq.gz
    ├── 5b22d996c56b64b0221695d55b6a41dc1aac720a.nq.gz
    ├── 5be9c6425326a5e651680f410a125303449dd08c.nq.gz
    ├── 5cf332587ab829ffa5d3d512a7e60e74f8864384.nq.gz
    ├── 5f30453c18b816861c2d98b4349f5dbde0362860.nq.gz
    ├── 636a23ba522f79f739927d0cef91f4843dacd526.nq.gz
    ├── 65423065384cab8375fd49ba5e0dfdf652ebeee9.nq.gz
    ├── 65a79a8782dffa4cfa493f8828b111c4434b7d9c.nq.gz
    ├── 66a9b0a71b3a05bebc2b8ba5a34517d9e2890863.nq.gz
    ├── 6806159690c9bad8e24f4f33e88f05b3ac1880dc.nq.gz
    ├── 68ca9ed31c6c5b76d4e319aee7a7267064219f02.nq.gz
    ├── 69567c60421922d55bb6a53820946b0ebeff9d95.nq.gz
    ├── 69c441f8c646e410e01e9040708dbe6c0db50af6.nq.gz
    ├── 69ce143bb22118284eb5ae3cc68e5601fffb50ee.nq.gz
    ├── 6b3894cb532e2fad31adbe3746ba06db96119ef8.nq.gz
    ├── 6c5b8f27c2e9c0582adbe152bfca1e4b581f35b3.nq.gz
    ├── 6d4168fbd6b78a64ebf7f67015cf7765a9ff5386.nq.gz
    ├── 70e9c88c882f595b849a63e2c274f6853ccc5ec2.nq.gz
    ├── 70f56655ea14cddcecc2dd0d9f781077243ccabe.nq.gz
    ├── 723f8dfcedcea43c9cc0e027c7d0cc755c2731ea.nq.gz
    ├── 748db1a1629a70dbdc40cf8d374aae508f7afb91.nq.gz
    ├── 74edc95e6bcee7b8792590e40f68f4bc8d2a6f2c.nq.gz
    ├── 77f821e1c830787c496deeda07eab22c04d5c806.nq.gz
    ├── 787fc0d6b763617f8f98bfab1fd4547c2149f4b9.nq.gz
    ├── 79067a7c91c9364b6a26abeaa8420725f25050c4.nq.gz
    ├── 7a2d05d0189e7f2f0da4d51ec672318d287a37fc.nq.gz
    ├── 7b52c8631c166406a5a80fafc25a4c566eae9ebc.nq.gz
    ├── 7c18e7098cafbe505a97c9141378e543f42d2f13.nq.gz
    ├── 7cb07fe2583dc0bcf16ab6fc4975c7b71e00f524.nq.gz
    ├── 7e84d8124a01f58b88c1d9827cb7aa2e8ea41178.nq.gz
    ├── 7f63a92feaa3441342fdb13cc8b8e71fc406c21b.nq.gz
    ├── 802dbf0917369185b274bdd90d7a4429bf15591a.nq.gz
    ├── 8143750f0050184609ea61711c35bdf33dcbe59a.nq.gz
    ├── 834dbfb33a65dcefc1e8298d74a35bf75a6eafb8.nq.gz
    ├── 8367e7c2a981f73157ef2174b7425fe696731acb.nq.gz
    ├── 837b4734fcaf3ace0f8720cf25175d636a87bc07.nq.gz
    ├── 8384b826f1a9b32fa0db2bd38058d6843e1dd5eb.nq.gz
    ├── 8512b9408c8042717a591ac5d9cac5c7c3e6af65.nq.gz
    ├── 865b95d2a747f258c211edf28a96e9e32fa5179d.nq.gz
    ├── 86ad8409ff386ef857214207f460c22843af6be3.nq.gz
    ├── 86dde18a6a0e60721231c696a4967b5ed6c8f2f2.nq.gz
    ├── 8755fa4d51fcf45c678d6f84e94e0b82a8367b65.nq.gz
    ├── 88208f6ec4329eb550344af9048d8d61d0d4d7e9.nq.gz
    ├── 89ab023e5f9706fabc0a5e8aa49bf7e37b8b67d7.nq.gz
    ├── 8c8cc07435f9e65e5401588aded9c3791b1c6de9.nq.gz
    ├── 8e43da1110e6cc2d51211d33e5a260c2ab4e4a9e.nq.gz
    ├── 8f473aa24085943caafb99b5b9dcf3551359a049.nq.gz
    ├── 8f62a5088e297dc5a2588fb0c24a2cdf563061e2.nq.gz
    ├── 912643d17fa230421cc64f1a1326a12b03ff4f4e.nq.gz
    ├── 913da3b34af95b52a159b4b4f36c8adb9c42a317.nq.gz
    ├── 9402d7af7fd59f8aff67db13cb3bf6ddbfce3328.nq.gz
    ├── 94387e5ab88af036e82db3066ef291aeaec01e11.nq.gz
    ├── 96e00a5d26fbd3359f3d23192c396dea8d184c71.nq.gz
    ├── 975fee889e1a2168508f64611781ab9bb537b114.nq.gz
    ├── 9adbe000476592250808b229a3df3eb32ef4e630.nq.gz
    ├── 9c65b49dcd26a83319b29b6b43bbfa2d77893b3b.nq.gz
    ├── 9c97e4052134f325e5c41dd5d823f214c33c5c0d.nq.gz
    ├── 9d7573ff0a43b8f2eaf30e500d497d512dfe8eec.nq.gz
    ├── 9eec23e1a3c484063f62e8b825af901dc5f03f8d.nq.gz
    ├── 9f5ba05fdbdb83644833ffc54c7b0d2616e79245.nq.gz
    ├── 9fd19953c60190e71cc8326ec52405f26b6b9080.nq.gz
    ├── a16be726cfaa8c85e78f5abccdd33faba59028ba.nq.gz
    ├── a185afab441c3694b2dc87a81d8e9a80662384fa.nq.gz
    ├── a1f5ffefff3f941694bdb2ba7a9f3bbd9118b748.nq.gz
    ├── a4109fc3e206a455b02f9607c7f325afa71435cb.nq.gz
    ├── a5011e347283ab67b2f276de85e7fba4344bf09f.nq.gz
    ├── a56c530b219b19f2315c9868c4c19780eb27953b.nq.gz
    ├── a5986fa4ffb7d4948badb7cb5b7d69a291f0c3d0.nq.gz
    ├── a5c243f7e616266a53155bc87c70a7bda081f1d5.nq.gz
    ├── a672c7b94f46301bb6226d1ca05318681a87cff5.nq.gz
    ├── a7793dce4cbe5fcfa314ad1595db7cc84adcc5b5.nq.gz
    ├── aafdabe547b728b63c6a17587fdddbd99df4c7f1.nq.gz
    ├── ac3c6d0693af062baf245156f3a2006cf1dd4ef8.nq.gz
    ├── aceb0d1a2e26eb5ad73f56692501b7682cb847b3.nq.gz
    ├── ad1727ec598318511c9b0620ec5a85e4a243243c.nq.gz
    ├── ae6a4973918618cd66a5f4c78386dced05585388.nq.gz
    ├── b21386f7077c10f78e5062a41f4e394a2ff85dac.nq.gz
    ├── b5638a614d56d44f2749e2ceaf494a6ffda656ac.nq.gz
    ├── b5b962d859bc94804885d2fbd6aca0910413b4c3.nq.gz
    ├── b83b2db4e4aa03ffeb4b563fa82092cf72be960b.nq.gz
    ├── b98a3574f4ae089aeef65d324d43ca8a1b8a8c65.nq.gz
    ├── bb9a21c6579bb14a07be284acfa345f5ce567ed1.nq.gz
    ├── bbd9a93ecc1a548de071250edd14209c8bfedc8f.nq.gz
    ├── bcd20fb3a04bfc2c4895fbac94cbdc8c035fbbcc.nq.gz
    ├── bdfe1bd854bfcfcca571259c574e7088500c4cfb.nq.gz
    ├── be9356f9a52a1e1f3b515ce48b3bb0a140e1a245.nq.gz
    ├── bee13b62c3cab056113bc815e6c8ee16bcf7fe33.nq.gz
    ├── bffb118a4196fcaa2e629c59c51e4c2c4e127c52.nq.gz
    ├── c039e790a1123c06fbeba38008ea4420712f3fdd.nq.gz
    ├── c4f44326c2bebeb84d086447d7cdc1715375e36b.nq.gz
    ├── c5f375445816581163f2aa134f01f4e731f6a1e5.nq.gz
    ├── c69f6cf5ab96e30be7687c2be997b090058e2f48.nq.gz
    ├── c76699a7c86e373d41da46396b07267bdb6e6b3f.nq.gz
    ├── c79652bef76c8682381cac7ad9fe9eceee9464e3.nq.gz
    ├── c7b9ca3e0f12bc65382edfcf21a3305e748e83d2.nq.gz
    ├── c811a6eb30906f71846a95d451e93639fe6cf50f.nq.gz
    ├── c8ab13b9797e01ae96f8386d29c8cf43694b0679.nq.gz
    ├── cbefb966a4238508b807a0718c17733cb912230e.nq.gz
    ├── cd3f2e2ad78b3d4f75898651126db420443a5547.nq.gz
    ├── ce5a892d08d4df962070bdb07533c08a2444f5ac.nq.gz
    ├── cea39d0adf9e6efe8267c79af410a3738e676c23.nq.gz
    ├── cf47d9639b76bb2677001b238b4198ed95c2ab11.nq.gz
    ├── d2b5d661c9cf6d6a403883b86a54a6a7017234b2.nq.gz
    ├── d4a39b76ea61cf7b1cd9005dc772851e7c37dac8.nq.gz
    ├── d5bbcaf8f019b3b86733a8d70cdd6cff24b5d3a7.nq.gz
    ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
    ├── d6ee0ce16b72191ff3cc83066252bfa73af3801a.nq.gz
    ├── d74d097237f279da40e8615a02dfc6ba4adcd733.nq.gz
    ├── d822e6847068b2400c65409d41d29d667971732f.nq.gz
    ├── da4d784e0a0925c8968337ce905d8352c3c2c91f.nq.gz
    ├── da8fb7a937c37b77ac4acf034397cf49ef4bb0dc.nq.gz
    ├── dbd225f6f036eec6834e1ee40305c529893592d6.nq.gz
    ├── dc8c37d18796a13d17bda1aa2974224d2a0af15a.nq.gz
    ├── dda08a46360d6c08a6e6156d0d2abd5dc58522e3.nq.gz
    ├── df80c53a12dbe60f3e3f60c486cedad044e81ecd.nq.gz
    ├── dfe9e86252d7bccfaf8cf98d7c0d9e762e9aa774.nq.gz
    ├── dfef2538b0ce3d618b7b484990f53cd5d7166bf5.nq.gz
    └── e06bb6c250d3ab73edddc65cb3e83c713e81339a.nq.gz

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

[NousResearch/axolotl-func-calling](https://github.com/NousResearch/axolotl-func-calling)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
