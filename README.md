# Repolex Knowledge Graph of UKPLab/naacl2019-argument-annotations

RDF knowledge graph data for [UKPLab/naacl2019-argument-annotations](https://github.com/UKPLab/naacl2019-argument-annotations), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/naacl2019-argument-annotations
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 67dfa69e737dfe22ee56a1c3731fbe8c3059dbe1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 67dfa69e737dfe22ee56a1c3731fbe8c3059dbe1
│           └── chunk-001.nq.gz
└── blob
    ├── 01d344ad9af49190a217c03afbf62508cc039d83.nq.gz
    ├── 01f862f8e3827d5d4483edf2569f36c79b70c5af.nq.gz
    ├── 02687143bc37a9add193cacf1791b49092c96a00.nq.gz
    ├── 028e7da4f07f569381004e6397b7d78207ed137c.nq.gz
    ├── 03a1a2f3bcfe29dcf7062f4e988cdf38936827f5.nq.gz
    ├── 050005ed4490f4df2cbde408e552fffc772b826f.nq.gz
    ├── 05460b015a956d59c8fd932d7143a2be013c600e.nq.gz
    ├── 056c537d20465318b0009830245f53b704b13e6d.nq.gz
    ├── 05fa4d7654a80b3051fbb5729c28ffa4ea4a0d47.nq.gz
    ├── 06c4345dcb1abfba355133bab9237b0dc3acfc6d.nq.gz
    ├── 06ee127ed077da941213636232fc0cac69faf1e4.nq.gz
    ├── 071f6a7506f1f11f529ce027708192f90e1ecc2f.nq.gz
    ├── 07a617db22f84ffe65ae49f12dab4d5965fc628b.nq.gz
    ├── 0a5cf0517550421e3d46161e2ab6c4f3434d9a24.nq.gz
    ├── 0a91b1c54bcf006bed2c004de0ac2c04429a9f7b.nq.gz
    ├── 0aa6dd011ca80d3c302097de42c7c39c2f43f72f.nq.gz
    ├── 0b42ff0f2dde979881163008bdbad5cf43296560.nq.gz
    ├── 0b55adbc7ba4908edde37c90a653cfaa697ca44d.nq.gz
    ├── 0b9c16d282e68a8bea86a2953870c18de6d987d8.nq.gz
    ├── 0c122be7a8a941b9bf219e965dbd812ef7c3934e.nq.gz
    ├── 0c19d345bad2fa04f9da85e87b7b68dfc4d8b3d9.nq.gz
    ├── 0cb6fb3adab031b3d7c919a12ab7745758db3e4a.nq.gz
    ├── 0d8c30b34dc0db09b0bf908c5f14e65a74031aba.nq.gz
    ├── 0ddfce5d91e9ede711541c3cfbddebd60a01ffee.nq.gz
    ├── 0eab9cf651c83a1e65c7002c3f719f338e86500a.nq.gz
    ├── 0f523ff6c462b266f3aa001bc738a4a1611190c1.nq.gz
    ├── 0ffd1ca2a773fe2939df72c22df53881816571a5.nq.gz
    ├── 10a742e145c4524b3cd5c5f79bc8690f4bc8cd91.nq.gz
    ├── 136cfd52158920893360ca4460cdd81cd5013c28.nq.gz
    ├── 14308624e932d19c628e612ee6f1f61a34ec0844.nq.gz
    ├── 14d40ee3c80c4097825b440ebc954d34b7432003.nq.gz
    ├── 1558bb31320aeb7ec24369439fb6456bc6b7578b.nq.gz
    ├── 15b94e8e6c99cb2d0ba28e53d475ed44603388a2.nq.gz
    ├── 15ca32b059dc0d12421f14b0d53c5007db777063.nq.gz
    ├── 1731e400b5e41a72eaf5776998c39ec9e7ab8c45.nq.gz
    ├── 174e0f4c582a79f97ed8edfc80ba2079848631fe.nq.gz
    ├── 184a1b28b75bd38109276a295bb781f9b1c31cd5.nq.gz
    ├── 1963a3eb8d6d66098862647229274cd1f5a840cc.nq.gz
    ├── 1989d85d9a835df4a8f0d3453ca9763f08d06ae1.nq.gz
    ├── 19c3251aa95e50c4e2e2f6553f837d6f1f5380c7.nq.gz
    ├── 1a44a9e677dc0230392b399684d38696e6775028.nq.gz
    ├── 1a6e4eb568cbfb905d26de7b42417ede79abb129.nq.gz
    ├── 1a9472f362257c85c9a862b77fd6f26c7cac64be.nq.gz
    ├── 1b308b92a040f65e30a894735378073664fd7e7d.nq.gz
    ├── 1cde5dc62d933dd472ed373cfdc34877421d6d9b.nq.gz
    ├── 1da312354b5b9d681912cc296fd3cd8966189a17.nq.gz
    ├── 1e93e8d731b1ed142054febf20ad31939332e2f6.nq.gz
    ├── 1ec4632a1b56fd31dc22dc0213ec7138d306c981.nq.gz
    ├── 20992df6308bfad8ba84affb2e3f9ddd6af4b32d.nq.gz
    ├── 20af89990cc2fd777135ce85d2dbb8ae27c3802e.nq.gz
    ├── 20b83c7552cf63f1d39f691351c0635af826ce59.nq.gz
    ├── 20c6be3dd7362664b59aefe6193f54c4e05258eb.nq.gz
    ├── 20dc8f6ca2c57cbb9f6140a4c2093feeb0dd9272.nq.gz
    ├── 2135443dca83d0681302f45780e8bcd26cdf3cd6.nq.gz
    ├── 21a27f1ba1e2b893dc783e8d8ffce1c2462a3d83.nq.gz
    ├── 23555963238b5348774f8f3e4624f17f96992e84.nq.gz
    ├── 23cacf236924fd9ccb59202a44744a0fa8da9aa3.nq.gz
    ├── 23d60117b411cb9d75b435ea8813bd8934fde315.nq.gz
    ├── 2432ee85a6274539952ce1cd350345ca7c2b0505.nq.gz
    ├── 24cef537a7e6c5df64d61e4572c736575488e503.nq.gz
    ├── 255f4c6292bd631ca684ad30b3694512cfe299e0.nq.gz
    ├── 25c29a557c13a889382a57809b579d171d364682.nq.gz
    ├── 26967e187356e83c87fa81dbf57e849dddb18090.nq.gz
    ├── 26c6f68b742d41e1e88e90a0845ab0764f2f3466.nq.gz
    ├── 2737e85f21af13710d398171edb6397850b5a425.nq.gz
    ├── 276bf31016fec1514969338c2d62c5a9d7ec369d.nq.gz
    ├── 276fbff01d97f1e2503d16bff71b6d74608a503e.nq.gz
    ├── 27c38d5f2e6f51fffd243fdd97a1aaab57e76a5a.nq.gz
    ├── 28d6edfbda582141279d5855f293826211197a03.nq.gz
    ├── 28e73c9378f427f0b35394b564a8001984948e4f.nq.gz
    ├── 295c4f4b7b08efec8a362866618821ba84c33b18.nq.gz
    ├── 298cbea35b3deb4655164c017e03eeaf732015c4.nq.gz
    ├── 2ae1e555229c391b17277bbfe53d5663b02a59e2.nq.gz
    ├── 2afb190543f3ed2107c9a8065b1586b7b3074d88.nq.gz
    ├── 2b3bce50e0ee971ca1be38b087e2931b8692f1ac.nq.gz
    ├── 2b70b04aeaf6f23b040df48eafa68acd0c0ca269.nq.gz
    ├── 2d6db4f9c09f3df19be052e88048fb4fa71b2231.nq.gz
    ├── 2d9d55625742b6ed2809d958bccecf640d2667aa.nq.gz
    ├── 2dd30626dc86ab21669cd4a77a1e17bd06c3c2e6.nq.gz
    ├── 2e5bf433ce93505cf2267fcf239efd7b73ca26e0.nq.gz
    ├── 2ee3cdaa580a7dbda0fc8d5ad191112f528264a6.nq.gz
    ├── 2ef2ea027247c8b35f484c7da5deaf8fdab65a75.nq.gz
    ├── 2f469c757d0a8d07d299fe82cf063c7180edf36d.nq.gz
    ├── 2f685ee9ce36b1410423fb594051fda4658ab75c.nq.gz
    ├── 302a3e1dff4428d16ef7d863a0484894c16133da.nq.gz
    ├── 31611c18b3977ff7e805eba95580b0414d2d5abe.nq.gz
    ├── 318ad2f1ea2043aa459080e2f08b557a4db77b40.nq.gz
    ├── 31beae8c11951074b3f204386c0cc8518de12e83.nq.gz
    ├── 31d785a21478607346cf107de38955bb1a68e450.nq.gz
    ├── 32b3f567beee152c2423c150f78c892b24d7ff0e.nq.gz
    ├── 33b916211b209eb9e6dac99bb6281b3758a01132.nq.gz
    ├── 33b9b8a3b22dd331eb2faa65bb7d30d810f478a1.nq.gz
    ├── 33d3263bd6d3500a8ecc4a2ed940793c57355fd6.nq.gz
    ├── 36fe77620efe34e15cbde415a1963345e1b3f999.nq.gz
    ├── 380e7ff058839aad8d59f824ba7b0198fe8996e6.nq.gz
    ├── 38215b8952257558afa98da5c577cb1484c2a6b0.nq.gz
    ├── 385770fbb3b22db96bbef19844133e0978f2171c.nq.gz
    ├── 38d464a4ccefacd0c720f22b436a56ec9d7c1800.nq.gz
    ├── 38e53e74f1b3919b6152ca9c53257f9b808b3786.nq.gz
    ├── 398cbbb4dff98ea107b00d0266c9f4503fcbc6c5.nq.gz
    ├── 3a73d937f6d0a400900c8ab57c6d636236e19f79.nq.gz
    ├── 3acad40b5714402d308fd4178f47f031cd542f79.nq.gz
    ├── 3ae783bec49a6ee14943d8662a96d1b9525ad3ef.nq.gz
    ├── 3b597528116e22f246371437f904a733ac16998d.nq.gz
    ├── 3c4f3de1b4fe6b3cee1aff9e12ae237b391c3992.nq.gz
    ├── 3c8a5b785c5805281c643129ff93198691b8d5e4.nq.gz
    ├── 3d5c485adec452a6fe3af5cf74a739e772168603.nq.gz
    ├── 3e79d5b0a3c7e50b942d5d0da81f876881e43026.nq.gz
    ├── 3f26f5012f23224df6803477376b897c9888c001.nq.gz
    ├── 3f49815ee6c161888b906a7ae7f772d3187875fc.nq.gz
    ├── 3facb5cfd598fec96a077e3ed960834006c523fe.nq.gz
    ├── 3fd892a0790e56a8c700c8c8572c03d809c6ea11.nq.gz
    ├── 43009ccf12d478cc2fde1c67118c54a7289c2d04.nq.gz
    ├── 43380912f572698f3552464a42125c19bc3febca.nq.gz
    ├── 435c13b9c9fcffbb2e43e144a3b4fd6c8d597b60.nq.gz
    ├── 436492274107640180d9b07f09a9ea5c235e5dee.nq.gz
    ├── 43c29ceacef0ab4c188fbab05966f1e9a953c27d.nq.gz
    ├── 43f3e543f64e4b2cfa0df3427a81dd1f4d63ed8b.nq.gz
    ├── 452d630c166eb99718a12b23c461c1c5f82c9f8d.nq.gz
    ├── 4570b09cc88a70e0c1f0313286fc8b6be3939585.nq.gz
    ├── 45b2e7e46afb257c6a12afadcdf7e8e425f6acfa.nq.gz
    ├── 475de0ebca548ee3544e59d4f354f7a5dc3e7735.nq.gz
    ├── 48a5cfb8ec74f5bd02c9b61049d7488c0ad17f20.nq.gz
    ├── 48b840fdae4bfdf3918ba9d5150205eaab93bc1e.nq.gz
    ├── 494ba493c0ec02332ebb15d56c94cf45dccc7569.nq.gz
    ├── 498f40ee7fdc7afde4815316267087c1d8e1a85c.nq.gz
    ├── 49ba4c4243fe5feb953244ad0e009ac86c9703a6.nq.gz
    ├── 4b5b3970307d972f01a8a20d6747a8169c6ee5e8.nq.gz
    ├── 4c0217ade1356aaa508ddf6b267a96641c7b0642.nq.gz
    ├── 4c8c2793e91a1fc7987a9680063060e2cca2fd02.nq.gz
    ├── 4c92ed9a526f1fe495599f53c6a7d37fddd098f6.nq.gz
    ├── 4c946c130db1e8675c0a88e3d9218a851c601bd2.nq.gz
    ├── 4cefdd53838529f26391536a2cd3da10e356723c.nq.gz
    ├── 4da22a55415f867d0b89fcfe99f89073be912ab1.nq.gz
    ├── 4dcf00d0c79e3f735e4c963a1ce787177547f867.nq.gz
    ├── 4e62687a7063dd92fe77e221df801de8a49e7ea2.nq.gz
    ├── 4ecd894b488dffb5e08477e9c1641c371c71f117.nq.gz
    ├── 4f21ca076a04e97e41f5f041993ac7a6de5e8db2.nq.gz
    ├── 50bb57fd03b477064270b3ebdc928c7efe1a57d3.nq.gz
    ├── 517d382e1b0478e18b804937ed3cfbeeb24ac1f2.nq.gz
    ├── 519ffa4de7e4e286d9432743e4b395aa2d74764d.nq.gz
    ├── 523ae1f4e6004c0bdc4e65cb6bbb60df5b907455.nq.gz
    ├── 52565cb6710fabb4c6eae12b9f2bd33d52e629ff.nq.gz
    ├── 52b51a7be1e019a458bec33467f782981e286512.nq.gz
    ├── 5341238cc04e357e1ec963cc547ea7f5e36f57e5.nq.gz
    ├── 5344a9a23b5e199bb0a5cd3dd707964c5640cf20.nq.gz
    ├── 537614fb4e0396150e09a129a599cc852cee3ec9.nq.gz
    ├── 5393c40320708fac43d133ce30d7b4be90797259.nq.gz
    ├── 547978ab90287c6145028a8fc686760104831869.nq.gz
    ├── 5524cec2cd21f66f33f47e303fd159d5e5fc588a.nq.gz
    ├── 55c6945a3928a8bf4e5279d047787087afa5c645.nq.gz
    ├── 55d0b27e652d3217c3d65d302270c1bdb0110462.nq.gz
    ├── 562d99849e01edd78dadbae4193a019891a4df85.nq.gz
    ├── 567b750077295a5b02cceb661f8a140faee6bb01.nq.gz
    ├── 56e39575dd0998291ce43a9489c5fa09d8e3ff8b.nq.gz
    ├── 570110133414d5d8a504b1b473a52d875485c05a.nq.gz
    ├── 578f78ceaf3e892fa3030a57a050af4c60415f4d.nq.gz
    ├── 57c5ac71023be33b7137e75130cb7c8cae18d7af.nq.gz
    ├── 57efa58f87ea43917dd319ddc84b13e10adaabf4.nq.gz
    ├── 582ccd66f69d9c7186893643593d6cd56ce54ee5.nq.gz
    ├── 58d75618d229753ba3377fa3a40be1bc9a372174.nq.gz
    ├── 597ee4f00e9cd8a29180587e5ab49071a08b72fb.nq.gz
    ├── 59c47459a24c0c32e354db975ae656be65110164.nq.gz
    ├── 5a7431d72f71616db248d34fa1c7fae9d4a6a995.nq.gz
    ├── 5b3e574651de1c363a768751e3696fe77bc9a9b9.nq.gz
    ├── 5b4d62ce6a1e0f2a108b8ffbd889ef25f699c9e4.nq.gz
    ├── 5b96d9c75361071cc071d95e8daac2eb427d8aa7.nq.gz
    ├── 5bf9709c399a7553f22f95deefd1cf301fb8d978.nq.gz
    ├── 5bfa98534ebf2f9bf978b5e45ccde4a1586f00a2.nq.gz
    ├── 5c7e9f831a4769d1656b61bb99d92225d5fad5e8.nq.gz
    ├── 5ca5fb30629652a8f054b261e85fde32692fbf9e.nq.gz
    ├── 5d19d64284bc89ac56f1d8065f3b0e747c3f55b4.nq.gz
    ├── 5daf45ad5b0153d5cd13d5211b9eb3f3b82abdf6.nq.gz
    ├── 5e9865db0a87df20c1c9a80ab7444abc3356f13c.nq.gz
    ├── 5f6f493429b9bdd710a8f124cab830146c7214f5.nq.gz
    ├── 6007ebfa394192dabd1fc3a5e041d3f83e821a18.nq.gz
    ├── 6008a5f3ecba9dd09478af36dbb2d94e456e26ba.nq.gz
    ├── 606e4721520d722c5f0e4169714671c0b727a8f7.nq.gz
    ├── 60bbc3c428f13583c6df54c5c0e01eb21d019fbf.nq.gz
    ├── 6122f268ce647a03c162ba685aaa24246108d6c8.nq.gz
    ├── 615c1e0e532aae4e4b6eaa25821bbb969d2ba3cd.nq.gz
    ├── 632351a4ebfca044aae6f497fd53d8cdece1ba37.nq.gz
    ├── 633025cba5d15be5ad71c1b14cbc0938b156de8c.nq.gz
    ├── 63af4ee68eac9071c375a06a7906a12d09184d16.nq.gz
    ├── 63f62ae41d7b692caf5da3b7498b9af12d9909d0.nq.gz
    ├── 6410fe82954ec652920d77f6bc86bce309f33a9c.nq.gz
    ├── 64157653dd414aa4c8a7d839e1de4064c0bef6d7.nq.gz
    ├── 648187102a572a84ae2613af18fbfb7f18cc9dc3.nq.gz
    ├── 65c2c27ba84fc95b3ce57421a3bca102a28fe0e7.nq.gz
    ├── 66704e51b727b6de321197b1a991a86a697662b1.nq.gz
    ├── 6698188d11620f794e952400c77cdd8803283598.nq.gz
    ├── 67b240ca475ce487ef49c75bf562336329a766b8.nq.gz
    ├── 67fc9d2f219d2f0d7f0cc5e2bb1bace405a8f840.nq.gz
    ├── 68f8094a12964e212dade059180f8a3500a2fdd1.nq.gz
    ├── 6a5bc0da098885fa98ea46e84a4619e9e3fc2230.nq.gz
    ├── 6aa8212f7d21526f53d7132ba41427bc56f44d12.nq.gz
    ├── 6af6dd2dbf4f8a26f570559bf610dfd054d62858.nq.gz
    └── 6b450da05d1752a022a8aa9f70fd7ddd1919f498.nq.gz

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

[UKPLab/naacl2019-argument-annotations](https://github.com/UKPLab/naacl2019-argument-annotations)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
