# Repolex Knowledge Graph of PyCQA/bandit

RDF knowledge graph data for [PyCQA/bandit](https://github.com/PyCQA/bandit), parsed by [repolex](https://repolex.ai).

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
rlex download PyCQA/bandit
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 68ebe11ef79263be27ec223184b94a4fc394a622
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 68ebe11ef79263be27ec223184b94a4fc394a622
│           └── chunk-001.nq.gz
└── blob
    ├── 00c931417875ba30536d81a1675e1f43df838652.nq.gz
    ├── 0204d32b4fc90e37c2760b2fd15e0103971d240c.nq.gz
    ├── 024e873a781e386ae158b8bd601cd6c4aa16ac3b.nq.gz
    ├── 07e6bd0b480ba9a5d988377cbf9669c45ebbad21.nq.gz
    ├── 089e1ac1c6fb91ebba294e530325696b82f3f072.nq.gz
    ├── 08b1c5c5b7eaaf1a6cd65b11718edbdcb286979d.nq.gz
    ├── 0d0d3d1e553bf4947dab177f4151a5a9ca09e934.nq.gz
    ├── 0d207471585f1fac5322a664acae664d91e681c9.nq.gz
    ├── 0dce14d90251ef47c9d1fef3d7e9475ec8d5269f.nq.gz
    ├── 0f111cbe89efd2c4ab6f1d9a9b876da3d21ed699.nq.gz
    ├── 0f454395017c213870f782af96bf209063f6200c.nq.gz
    ├── 0f6e67b572813f864e4748ae873e6ebf81bee2e0.nq.gz
    ├── 0fb5b3349e0d3abbd8f626ccb5f06c083f87fcf5.nq.gz
    ├── 10f4b1d90dd31f6d6b3a5945b2ac76e624a48295.nq.gz
    ├── 11791ed1e293e5e3ba8506b95d41dca071570548.nq.gz
    ├── 12e6f965c2eccd97e01f02893b82497ab389e656.nq.gz
    ├── 13d7f6cce1ccb31653b4b016f5e6effa108117d2.nq.gz
    ├── 166e4bf52ceefb956eea4d9b4f04b55a7316b704.nq.gz
    ├── 16aed0788ca586193da08d7747e502a6e1727b1d.nq.gz
    ├── 16b5defd950a923ccea6bae7b744c63579edf3a4.nq.gz
    ├── 16fe25fe4b5f75fd74b6c3a48b1a98b05952aac3.nq.gz
    ├── 17952a2cc0ff9ed97c36db44cf98bd6f8c966712.nq.gz
    ├── 17ac83a2731212f5957f0bad0d8eceebe1aa5b3a.nq.gz
    ├── 185d6aecacdcd0e45c326ed3e91ba5b7ada32e8c.nq.gz
    ├── 19cd1868b6f653d5a5e1a973028b107598eb4e23.nq.gz
    ├── 1a0958a80ade85b4c39a626bd55220736a8fce2f.nq.gz
    ├── 1ab180995c5eb695a43546195ef7226107c983ca.nq.gz
    ├── 1ac01e6c6e9710dd0088a6eefd1257b0b47475df.nq.gz
    ├── 1de4803ce4799cae9d80a321593fc11f08d06b41.nq.gz
    ├── 1deb8575ccd80026ee48df8a42029d452b7dd0dd.nq.gz
    ├── 1e7dd0d8cbb3ebf5ab899f74db28ee9a351926cc.nq.gz
    ├── 1fc22f24af41627c4df05de57e6f433b33c814c1.nq.gz
    ├── 21e815105fa10ec125b181232c4b52bb666aa47a.nq.gz
    ├── 2234bb3dee7a18426dbc3511e5b9fcbffeb7457a.nq.gz
    ├── 2304c1d7d2e7e13f55f552fa9bc037fcb3c5adf1.nq.gz
    ├── 23215f85f9ce3875bdf3c62764e613fd097cb797.nq.gz
    ├── 23ee14705a9f8c5677110c962aafe160ef2f2a55.nq.gz
    ├── 2549485262c1114e270474bc13d69ec0e4ad691a.nq.gz
    ├── 2738ff9590a0c23165b9c8dc27316a65bd886986.nq.gz
    ├── 2747eef58d092bbc80120b3736b7f3d693f45329.nq.gz
    ├── 278a3e43c5701f0df262d90be48ff67f85a80c29.nq.gz
    ├── 28429d7393f72d24bee7d46522e4a7deec2b7072.nq.gz
    ├── 2891f7a82bc703450d9c332799758adbdc7aee56.nq.gz
    ├── 29dd38c9f7ebc0b0ca5fd06bd6c880cbdfbcc657.nq.gz
    ├── 2a0f8b74da6f89e8182fe58c86de5ad40c1a69c2.nq.gz
    ├── 2a8247b173decbd96283f57ad98d0a009e3ad348.nq.gz
    ├── 2ae44c000dd030dec5393ac9d9ee8863395169a7.nq.gz
    ├── 2b077d4bacfe18820ba84e401e17a3937e964964.nq.gz
    ├── 2be183a8cfd179de66f973925a82fc635cc2e4cb.nq.gz
    ├── 2c40053c0165b3e47c3728f7f10a4d6e906f5dcc.nq.gz
    ├── 2c838d4740ccd840854c0491f2f020b927576684.nq.gz
    ├── 2d9f659d9cccd8956e9ae038b7f88049faf985ec.nq.gz
    ├── 2ebda5580a52bc9b60b6223be62dd09cdbe4d839.nq.gz
    ├── 2efdc4dc235410293df2d666c501febd2a06c1bc.nq.gz
    ├── 2f18aca45d7c7578ea8af2301c89b7e76a671225.nq.gz
    ├── 2f668e24ffa138ce4a578e83ef6deac9134af453.nq.gz
    ├── 319abcf1fd95e856eb76131c8c13ab94e8db2360.nq.gz
    ├── 32642a5f9e3bae7579a671be9363d5eec6ead95f.nq.gz
    ├── 3276c68ad41d5f799b68da1cc5223a198d20cffa.nq.gz
    ├── 32dff63dfe422f154fba028f087f7cac54d6786f.nq.gz
    ├── 3374205fe6d487901560b56f022394e8c2fe0ebf.nq.gz
    ├── 33a81ca99211e470b1e7cf9977b76b62d58896c9.nq.gz
    ├── 352c171596e11f822ae40c483abaed24b842e455.nq.gz
    ├── 357a71e132315a5c9165288292c96145e121062d.nq.gz
    ├── 35f2e953f0811b0a4119a642f58fda2dfcdfe02c.nq.gz
    ├── 363b022271605b2f1bad56286f92b6cb68c0658f.nq.gz
    ├── 366e6658a4191b8644a90f8d5558a460c1dd1059.nq.gz
    ├── 36a77bc3bd51d7f590dc3f383f5d9b386a11dd76.nq.gz
    ├── 38944d5faf88a54267d920f9458c45c734925384.nq.gz
    ├── 39b05fab532829155e6a1a7174097a6a4ba0c1f6.nq.gz
    ├── 3a817d62f75e4d27f31cb12d49be1b47ce9774d8.nq.gz
    ├── 3a954a4dd87b469518b46899fa3390a3bf514c1f.nq.gz
    ├── 3b06e8d92a437722eb3372d8cf80fd76d35dee56.nq.gz
    ├── 3b18996fe2b63a0f095d9139ea9175c9f9de056c.nq.gz
    ├── 3bc89154a11d36e12959dbcd2d2b71b2c9ff381f.nq.gz
    ├── 3c56c80492a023e3e85a0663d8c443302c3de580.nq.gz
    ├── 3d05fbaa97e29535ef3ae82a7cb7fc072c5827a8.nq.gz
    ├── 3db4d200072e4e263ad5bb5f48a7ec6266df23c9.nq.gz
    ├── 3de2169ae4d2a9e1df3688c327f8ced893ebfb80.nq.gz
    ├── 3de259cc9978edeffd2e6bbe63d4a5ee106b2af7.nq.gz
    ├── 3e46247804bcb540db270120d4ab710bee50cb61.nq.gz
    ├── 406c0c776757703239cb2fd642319878e8a5464c.nq.gz
    ├── 40b03925dcdbc9f6ae8f2350f7885f4bedcb20c1.nq.gz
    ├── 40c605579ea7994e6f22dcf85fb36b50cd65516c.nq.gz
    ├── 40e7aea2d84b10bf68cb0d1cadc1e6903b0ff015.nq.gz
    ├── 421109078fad0a3ad3e3a16facc381213d674e5c.nq.gz
    ├── 422ed10c7730461d6982ae96ab0843c5b7059236.nq.gz
    ├── 4345a879b770472c168368fe9d50927a37a05c34.nq.gz
    ├── 44db12480cb2e8251811f0eb4aab5f5bfd66d306.nq.gz
    ├── 44eb197acacf6ab3437f3232d8f71d86ece7164e.nq.gz
    ├── 46f6b5b6ceaffbc40a4d6390f213fb4b52656f3e.nq.gz
    ├── 499a6678915a757ce5c88d34369a99ef62e2be7c.nq.gz
    ├── 4b63de1e9a45bc6652db533c50601c3ce4ea9a1f.nq.gz
    ├── 4df534f16e58776f1b862acc06c578009d2b3129.nq.gz
    ├── 4eb5b87a64dbb631d63b7db736ce367a7f0bc89c.nq.gz
    ├── 4f4202bb0c791c13844dc708ff7948934cc2a0ec.nq.gz
    ├── 5001ccbfe8da5971d3cf4d362ef593f0cac80cba.nq.gz
    ├── 51be2eb4a01245f10074daf92f0e1b3308e0733f.nq.gz
    ├── 51c232c33cb3b06c74c6c2f8489e99bf1bce794c.nq.gz
    ├── 5306f881400a8f0d5388e1fa18a12bd22e070558.nq.gz
    ├── 5481b71a85415d96dd8b049174e17b9506951fde.nq.gz
    ├── 580c084256f818a5debb767752371485b8f64a76.nq.gz
    ├── 5834cbd2a3f7c85d50fc9d766b294e4079a3f104.nq.gz
    ├── 588d445aa9932b02d77a2fc31205ce56d3a30556.nq.gz
    ├── 58b840e86b678f5a2aa106b61c892975227fb08e.nq.gz
    ├── 5a5575b5e28152a35893455235f099f2b2e8f667.nq.gz
    ├── 5a8e50928c326efbc778a67132275e4032dc67cf.nq.gz
    ├── 5b06ce71da92b64672f8ddb5935b08593c111866.nq.gz
    ├── 5b51f4d2a8d6c10e4dbb9f3ec429ed113923f12b.nq.gz
    ├── 5d20c56f839d115bd5b4aec826be32a678ba77d2.nq.gz
    ├── 5e177602a5b5918d830e83687c52f9b2783be1ab.nq.gz
    ├── 61174f678bc7ad1d2802f17fa5a81556715747e0.nq.gz
    ├── 629c501fee13870bb1a667482719761e4894be59.nq.gz
    ├── 63c3c82c62eac64c3da57642796f1e58164f3dfa.nq.gz
    ├── 65e8ba65c0a5d0f70fd6b1b049c0a9b74da551d5.nq.gz
    ├── 663446ec552333debedda887654f79530b0b6798.nq.gz
    ├── 6664ed0014b14952545dd0ae3cbd83dc826b42ea.nq.gz
    ├── 667cbb0d15abda3d02161c3c0fa626e4c7903a0d.nq.gz
    ├── 674fe0b9bc44617020f950e7ea3219698e5baaab.nq.gz
    ├── 67db8588217f266eb561f75fae738656325deac9.nq.gz
    ├── 67e8a09c4b8dec6961cebcd6a90364a4a08eff3f.nq.gz
    ├── 69f4398d546fd4534d6987903d366b18c104fcdb.nq.gz
    ├── 6ac72a3f9a754d467ca56e8459079f75e9b84da2.nq.gz
    ├── 6b613871be68328ab69b144878e49cbf08011142.nq.gz
    ├── 6b94c8dad49ce8dda650e632d59ac22f2c2b330e.nq.gz
    ├── 6bfde58d377920ba14be5d2e02baddb4d4b9f4a0.nq.gz
    ├── 6cde187f5b3553d65c578647d370e69b6c05c3f5.nq.gz
    ├── 704022a91bec37a26d99b6a0288aafbefa61abdf.nq.gz
    ├── 72a8174ef7a5a39d5649ab1e115e62eb273464d8.nq.gz
    ├── 72dde9c143b11754581eab884e111bb65268a574.nq.gz
    ├── 733b505ac1aafed3f4f4eda72d89160085e32daa.nq.gz
    ├── 7421c3ea8b9d25f52357f26068b976f388b0b228.nq.gz
    ├── 748fc66904792866c2bcf361be21aaf8ba8e17fe.nq.gz
    ├── 7564db4f1c8ce05932e11d55a0b03b18448a3c13.nq.gz
    ├── 77c5f88af7163250e6f638e043e965cd708bdc96.nq.gz
    ├── 7903048cb97d4d601b4f027fedda272a57825a7a.nq.gz
    ├── 79615fffc3e851a1d5a4bc50bd377d3ae7be569b.nq.gz
    ├── 7a07df926c822f8bdce0ed97288da7acead098c4.nq.gz
    ├── 7ac651d06ca59014e32fbb70252a271e5f56b732.nq.gz
    ├── 7ae76d6c6cb8372e9d279bbd4377405e6bc73810.nq.gz
    ├── 7bcd7f8bab2ed1f061a0a005c8f430ffc8e75f94.nq.gz
    ├── 7c11963f6614b74888d6874f8b58242769357370.nq.gz
    ├── 7c7bf00a83541b428266719ca8de9b939706208e.nq.gz
    ├── 7d3fce4dfdba8b07ffb7f35d629db0ab68aa08e2.nq.gz
    ├── 7eae90509ab0e7ab2e2d98e859a0e44ed65cf04d.nq.gz
    ├── 7eddf08ce0f913bf93a3656df95a05e90c1d90e1.nq.gz
    ├── 7eea55ff1d872e17a9efc5e9ea41d7e5bc4ecd9e.nq.gz
    ├── 7feb214df6bc279e855b602f94145d257005c007.nq.gz
    ├── 80879cab49346441693d39cb5674a0eb2fe3aeb2.nq.gz
    ├── 80d6e48f29f2858d690803497f3cac7162bb5455.nq.gz
    ├── 82186af14be6ba29ee9c503bc6ff7be6a4f9375e.nq.gz
    ├── 821e8e593c21bcc57b1cdf956e987f88496bf245.nq.gz
    ├── 83ead901dbb676801982c27bd5545979864810d8.nq.gz
    ├── 85f1d2273fa87220135e3c5abc84b8fe2a092680.nq.gz
    ├── 89f83c952fa6d9d3e8ee0c1453139bb1b9ea60a7.nq.gz
    ├── 8a6b1be83540141be5f76df20f13b6dd2691439c.nq.gz
    ├── 8b20282d0d555d08fa4e0451a7f74cabaaff129a.nq.gz
    ├── 8b60c5dab720d2620145ac570bd7ce9cefb76e4c.nq.gz
    ├── 8cbe39131ea11f2d60d49e2e1889e29079152267.nq.gz
    ├── 8de21b26da62f856fdc73a021303b65d60b4f825.nq.gz
    ├── 8feea28a5a3ea47b49273bf34fd54ed22c7cebe2.nq.gz
    ├── 91cf666f739531ff0d9d8effcf3124ac36536af7.nq.gz
    ├── 9324918057c2f69dcf23d9d7632504cd64fafa84.nq.gz
    ├── 95519ece8daffc7f32375cd37524dbb37bb5aa60.nq.gz
    ├── 95b8934b4107f4a3329af8718a4f693c2a247ca7.nq.gz
    ├── 96815f03631d89dc0afc13b05e6456362aef1991.nq.gz
    ├── 97077bff9232800615c60997189f0ebaa0f8cba7.nq.gz
    ├── 97667d8c6ad4220977370298eec21c22366089ff.nq.gz
    ├── 97d534221abc703f886fc0402abd9d3f702fb7d4.nq.gz
    ├── 98385e773738f4dd0d841de20fab3825ce3ba674.nq.gz
    ├── 9850b55e39034cca26a975c3976c28d799bf80e0.nq.gz
    ├── 98b95ec016e475fe4128459cd57fd0cbf311171a.nq.gz
    ├── 98dfdbdabda8eb9d8e30cf11fa16d591dfcae375.nq.gz
    ├── 9912ad42f27de9542a2e5579e8f3b8da93cdcf4d.nq.gz
    ├── 9951ff7465582dca7f248f589e6606b8f91d809f.nq.gz
    ├── 99602049f5eca13d9b9f48ddf1af776a087d1983.nq.gz
    ├── 99f4c4b530402ae796bc10104bb43b6beb6dd1bf.nq.gz
    ├── 9a2a76f60ab3100f1259f8b148481438405ce0f3.nq.gz
    ├── 9b8f882cc5cb7d1d6453ecbd77821de4cddf367a.nq.gz
    ├── 9d7bfc6fe6d2f71210200bce5e6bb6365ae33895.nq.gz
    ├── a210b38be928ca68d14d82eed3e9bd563ad37424.nq.gz
    ├── a24a90b9b8dcc916dbc15e9878cf3606eb988f85.nq.gz
    ├── a5306fa8125de865909618ed3893a4bd8c4ea161.nq.gz
    ├── a627e5f8e1917670ad14ec232c2f8b46ef97d762.nq.gz
    ├── a6a2eb164027ba7fa7494b12de4aaeb7a920f751.nq.gz
    ├── a7831ac3a9339f101dfcf15f624cd6bdd4039a75.nq.gz
    ├── a83c18b0c438435458f3f171d838d316a41efe91.nq.gz
    ├── a868c3468d89021dafd3bf41c1fe84112cf7d754.nq.gz
    ├── a915ed8986b52a83fabfcc4610ceb54a24aa3fe2.nq.gz
    ├── a944d1cc9e2d41a7e1c9f9ff154b00875df59553.nq.gz
    ├── a9eb2160801cb6a02232b7432ccdbf9a5c94f622.nq.gz
    ├── ab33e870927d0822943179d558f6a09ee05774e0.nq.gz
    ├── abce4f81375544730b3fa5056cf6bd506aac0a0f.nq.gz
    ├── ac503972f2a753344d731918f6af02037f28a706.nq.gz
    ├── af3080111cd156de0bc8c5edd33af7bc32245d3d.nq.gz
    ├── af8bf54c95bc28b7467228c401b44384bf78ccf0.nq.gz
    ├── b091c29bf24ca0b63a6e73944bcc46fb8438add4.nq.gz
    └── b13f12b8938dd571569ce6378cdf30ab30e88ee6.nq.gz

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

[PyCQA/bandit](https://github.com/PyCQA/bandit)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
