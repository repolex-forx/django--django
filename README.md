# Repolex Knowledge Graph of django/django

RDF knowledge graph data for [django/django](https://github.com/django/django), parsed by [repolex](https://repolex.ai).

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
lexq download django/django
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 42ef6557a9b88cfc277eb79ddb980e1c62add144.nq.gz
│   ├── lsp
│   │   └── 42ef6557a9b88cfc277eb79ddb980e1c62add144.nq.gz
│   └── repolex
│       └── 42ef6557a9b88cfc277eb79ddb980e1c62add144.nq.gz
└── blob
    ├── 003aeca59fc46a07be968f351d75aa6e22e75f93.nq.gz
    ├── 0058689657b13dd5e8a19da4ef3852254173cba1.nq.gz
    ├── 005e951595cef8b88b05964c27b59056e1065034.nq.gz
    ├── 00706797a26738f1d93e10fffa7367a4d382c402.nq.gz
    ├── 007a7079b7ab01752a4fe2fa0187c4fcfc75c3b1.nq.gz
    ├── 008aeeb72b4890f6079227fcac7b401d3776305c.nq.gz
    ├── 00c482b3dda337ba8f76919cd810e6886fd1c9ab.nq.gz
    ├── 00df558c2370fa6b8d880949df2656cd32aa450e.nq.gz
    ├── 00e1f88dabb3ddc201ab665f7e700c56bca181e0.nq.gz
    ├── 00e2d6017b734e844501c8b8567a6e13c0bcfba2.nq.gz
    ├── 010e9b0d9f7cdb417d3144cb6b167fd51f9eeb7a.nq.gz
    ├── 011490ff3a0100bea63eca7d8a3f821edecf6d3f.nq.gz
    ├── 014ef71adc56b0c0ea1031170f3aea39e11fcc84.nq.gz
    ├── 016ef397b2b645eb3a7e9365f57dfc4bc1150423.nq.gz
    ├── 01b40d7535078df298e12382317d1726ed445c25.nq.gz
    ├── 01c002e9e0e3878edd15a03a3d997c0e5124ef33.nq.gz
    ├── 01c9e73379e2e6423305ebfdd3b0f094259b0d81.nq.gz
    ├── 01f3f9786f3615e63bea30393ba9f3db1c533014.nq.gz
    ├── 01fa52430f551439fe8f3250c29be2908a69679f.nq.gz
    ├── 02363a075b4495227fc4637b47b50edc65c3ef8b.nq.gz
    ├── 0257c63d8c233e5685badaf01bd61c8748f30242.nq.gz
    ├── 026ba1b1f8e905529ce495b81045d14d527c501f.nq.gz
    ├── 026e4268625b9f96df6079731fe31662cb5f4510.nq.gz
    ├── 027d34e740b5bacc950895fc0cdd8684c63e0645.nq.gz
    ├── 0280698aaeadd4a0b1050cf8173d675a2c021346.nq.gz
    ├── 02a2c5318e44d66c0a24e283f15cf2c6d0c7464a.nq.gz
    ├── 02a4f02320a0a3626710928a6a55646cf24c2820.nq.gz
    ├── 02de295f88159cee6f62dd3656ffa54753ceae39.nq.gz
    ├── 030ac505fef15896b47be16f572cb54e2f45c0f7.nq.gz
    ├── 035da37dcc8b8dd4ca182a9020382d0cd86484de.nq.gz
    ├── 03780f28c22f7104431cf95a496bf20beeeb1691.nq.gz
    ├── 0383c60fc1205767d5758b4b6027cd3d6d706d3e.nq.gz
    ├── 038dce5f8bc1a029043a83863d0851f358ccc848.nq.gz
    ├── 0391e5040067a7289970714e8f223e4e7ad5f522.nq.gz
    ├── 03c01b7656a364e51385d1939515a12188cb3a90.nq.gz
    ├── 03c683b844849a47584d5035302311ee718bbdc4.nq.gz
    ├── 03cc1e3c11413bff4fdf730085bc4f549721b5a0.nq.gz
    ├── 03f5ff12813b993920aaa72f493378440bfd432d.nq.gz
    ├── 03fc3ff7cd9091f16ac85e4789bce8026eaf30e6.nq.gz
    ├── 040130cc1a93e7a6819367e19fd7e0971a8e7642.nq.gz
    ├── 04099be16ee61b489e0a0d92ad57a2e2470b985a.nq.gz
    ├── 04498db00c17069867a2436a6994ac96773022fa.nq.gz
    ├── 045533612dcb659ad706a5270cb2bbc92ce2e6b6.nq.gz
    ├── 046743323c26ff18f246ecfb77452852c83ee485.nq.gz
    ├── 0479b0773e4d90505e27a87e17806499274175db.nq.gz
    ├── 0484e5f9b2eec8e3eed4f92cc0c261e1509cb847.nq.gz
    ├── 04878b272a53aef5efaac181bf8607059f633bef.nq.gz
    ├── 0489ea81d82e628727fb768cc307f8f2e5e57ac4.nq.gz
    ├── 04d68cd26cb3cb2b9f280d715d91eb8bd2832396.nq.gz
    ├── 0504592ebb415bfdb88e30723d1be6e46cb2e6d9.nq.gz
    ├── 05097b7e59d37549e81fc6247a3050fd194b905d.nq.gz
    ├── 05532da0b0276cc5965afd3b2f6ab973ea401b57.nq.gz
    ├── 057e2f715e26cdf4aa7ad92bbc2f4918ba957018.nq.gz
    ├── 05b824b95d241f943a59aa214f46e916686477b0.nq.gz
    ├── 05bb4a2a0aff6b828f0c189a6b96af93ca772fab.nq.gz
    ├── 05d322363bf2060fafbfa5b51a4630d21c901823.nq.gz
    ├── 05f98358b7c63e0292b873a50e1bce60c738d4f3.nq.gz
    ├── 0611e01643a4837066c109970305b8d7f278c38a.nq.gz
    ├── 0637a088a01e8ddab3bf3fa98dbe804cbde1a0dc.nq.gz
    ├── 0656c323aeafcc3fc135f15098821ee5752f3b75.nq.gz
    ├── 067edb6f7301524db930046ebaeb0b0801184ad7.nq.gz
    ├── 069a99b2d207f477a99a4ee093bdde5d744a1f44.nq.gz
    ├── 06a854009bcef5dd425f9ca50b6239a60cd09b7f.nq.gz
    ├── 06a886e0beb885dea12f2e8558c85790f0763441.nq.gz
    ├── 06d21bbdd48f244325f84147f7d128ccaba9fbae.nq.gz
    ├── 06ebe62a3c26988fc4d8285dfadd68711ae52885.nq.gz
    ├── 06f11e35f3ea05130a1f3faa74f3ecb2769e8afc.nq.gz
    ├── 0700b46ea8e98461cdfd054182a88dba9fb13077.nq.gz
    ├── 070ccf6d5f71e38dda6e26e96b12053cd0f862f5.nq.gz
    ├── 071b708f7f9806985d1c4b4d1a292d4013324f67.nq.gz
    ├── 07263cbe80a1142a0bdd60ec09fc837ec7d86e91.nq.gz
    ├── 073190657c5edb4f32e9ca86f3f2da2287f90998.nq.gz
    ├── 073964dfac71a10989148031540d0459fec58f21.nq.gz
    ├── 07713c9ec3fb74a3260136fd2282a04162bbde2c.nq.gz
    ├── 078c83a49223eec9589cce28172b3201fe6c8d9a.nq.gz
    ├── 0796306e07f6c70694b465e5c87606e0dd81358b.nq.gz
    ├── 0798acc7dbff6b8a20db4c3343a127104cb17604.nq.gz
    ├── 07a62a7fbe863b9ed0019f4061e96aeb25b479c0.nq.gz
    ├── 07a9bf39b78e6b20fabce01cc5687f3e7a79753b.nq.gz
    ├── 07f955a38d7dabe8d4864178371bde15190923d2.nq.gz
    ├── 0815d9ef3c2d78fc14150db3ddeaa7fd340f1b58.nq.gz
    ├── 08436df35572ff4505e3639556d72a7c4b87167d.nq.gz
    ├── 0873281e51bdcfd1e7eb5bbfbde3a09c4cbc943e.nq.gz
    ├── 087f3da1f7b668d3f1151fcb9d8d0b985a886ef8.nq.gz
    ├── 088549f2503cd714d84e0b3c7778164dc90e26a8.nq.gz
    ├── 0900b4e3d9c1dd423a58215dd9f45647139f4ba1.nq.gz
    ├── 09026aa010405959205725735a15533aef39aa1e.nq.gz
    ├── 0916f52388b65d745f9674b1adf4a87ee2a06acf.nq.gz
    ├── 091f7f32b43e6e7ea379185a96c43f7504e4cc4c.nq.gz
    ├── 09307335a0d7322629dfd8d68ff1b7944578b4e5.nq.gz
    ├── 094fc5815f3871c461837e27da5bf345942047db.nq.gz
    ├── 096afc4394223970b1ff047a5bd3741bbf8e4de5.nq.gz
    ├── 098bca793f9026c0cf826a8652b84e1d96b8643a.nq.gz
    ├── 09ae670daf8e21f883df332a4057b4bbdc08ca30.nq.gz
    ├── 09b8c3039885470ed4d44c35e0fb608df4c54e76.nq.gz
    ├── 09e0826b88bf04a0cc34d8af1e9749a57f0c3b65.nq.gz
    ├── 09f16c785b8b1e06ef3d0f7cd8bd583517a90ced.nq.gz
    ├── 09f292e0373fe87e60d1274be3bb6341417cd9b9.nq.gz
    ├── 0a23ba79b091512af422155574042377fe7b8796.nq.gz
    ├── 0a68b82a106ce07faa61acebd7cdf278d4d1ca02.nq.gz
    ├── 0a784fa769212348b3cb42f43f2d32c54e6fff6a.nq.gz
    ├── 0ab7a72d57393414823829dcb233571f45130f7d.nq.gz
    ├── 0aba8163d6347e17ea3afaef4f8248a0f5696377.nq.gz
    ├── 0ad809a45daf31b47c91c73bf57046cd3a4b182b.nq.gz
    ├── 0aef3e91c3ece2aacac7a3f587f04080d6c981e6.nq.gz
    ├── 0b133a11f2cf37ccf9c27f611f75f79fe4116075.nq.gz
    ├── 0b2257cefe6454d30004180006280aa4e4f7d46e.nq.gz
    ├── 0b368f13855477e10a66cbd53e96131ed8a018b1.nq.gz
    ├── 0b3d4ad0bd24f3424926798f11013f6ef97db70c.nq.gz
    ├── 0b4f61a3603ea906d21321783ace6be4937b0b71.nq.gz
    ├── 0b82bca9c4fdb60e9d4e90efbb50a7e05b67145c.nq.gz
    ├── 0b935f1eacd04e2c6923ece763fa5d9fcfeaa9ba.nq.gz
    ├── 0bc6fe14b33274b524fb9e4a68a98a9a8eae03f2.nq.gz
    ├── 0be0984ff5a3d569aa57f9159c60afa92d132fa6.nq.gz
    ├── 0be93a20c3c36845a3242a8bae7a58f8e11eab31.nq.gz
    ├── 0becfeb96e3ee5b9da5be1ceb8b02b0a0b210587.nq.gz
    ├── 0c0b62f51ff16ce69cd5ac145dd21fb04f0cb2f2.nq.gz
    ├── 0c3ef57af84156e84e4ab78f02e2e752c8c7bbda.nq.gz
    ├── 0c434772f8b045d6676f1f97422dc59873df782f.nq.gz
    ├── 0c81ed3119ddf21650b828623627f2bffc4781f7.nq.gz
    ├── 0c94d2e27646126a5b6f037584edd81c3aa410c2.nq.gz
    ├── 0c975116ef99b2698dfb4c221f048d3a0bbe770d.nq.gz
    ├── 0ca577059ee576e32a4cc200974ce85d85c7f185.nq.gz
    ├── 0cd393756d1eb3b7595882c4b57f308fb17a1ed1.nq.gz
    ├── 0d0a8eca9e2b637943ccec6797a1df4336214dd2.nq.gz
    ├── 0d1bf557eaae837d56b8f366259fc01116bc6d0b.nq.gz
    ├── 0d28926149e92820f0629a2a53a306b111967a3c.nq.gz
    ├── 0d2f393ef4ece1c9058a61b705150ae27e7251ea.nq.gz
    ├── 0d41b053b23ca8b4b51022c70df8a961fda2ad46.nq.gz
    ├── 0d54948bf5a21ef9dd604f0cb595ed2f537712aa.nq.gz
    ├── 0d9c68f9e0d80e89e4a0ec2df54f5a5d40d27387.nq.gz
    ├── 0dbe30d70916650ff16ed34f6677e4fb21717b9e.nq.gz
    ├── 0dce7eabc9e3e2485b358f41968cdfb578287a67.nq.gz
    ├── 0dcf6259392ed66377258f0c41035f853ced1c7a.nq.gz
    ├── 0de5a6b8cbdcd899a49221dab2984d2bd02a6c00.nq.gz
    ├── 0deaf6a1783f733a5a5b3aa7b8413c08e283451c.nq.gz
    ├── 0df69aeb94e59626151b54bcea407675817c193f.nq.gz
    ├── 0e0510d707561f2c4409ef078ca224150adaa50e.nq.gz
    ├── 0e511d7360b39bb010742cca0479404354b9c1d1.nq.gz
    ├── 0e591e799c7903da17835613dbedd1ee3861461c.nq.gz
    ├── 0e594fa5d82f7ee283c50703b3c2e29d0b9c99a5.nq.gz
    ├── 0e5b778af843185ab64f09ac58bb5388ce671c68.nq.gz
    ├── 0e6aa0ece6abe1ec5e15c82e5906b72174795352.nq.gz
    ├── 0eca3f4293db5ab24a40085eb304e473b85566a4.nq.gz
    ├── 0ed0ef481950cc16ba916f2f8c519f4fb167fbeb.nq.gz
    ├── 0eda8f02da5993011c59b6e951fc3939f41f6d45.nq.gz
    ├── 0eeb485797ce71155c3439704299dcb621d33fd4.nq.gz
    ├── 0efe779eb9f1b47fa00ecbd282804fc520945f1f.nq.gz
    ├── 0efedf3632e7ab02c998ec45d6f6cb0dd25cb424.nq.gz
    ├── 0f0c41f61890b37bc73949baf52779b3b2cf3123.nq.gz
    ├── 0f3bd0610c9d04a9cb121eb468d9021de85d4d94.nq.gz
    ├── 0f6634633748cc74f93f75a5ec94e12265cd53ca.nq.gz
    ├── 0faa39a6a94dcbce6c99768e38ea903b6d3c7100.nq.gz
    ├── 0fb2f30e20effbc999317ab87e64261874770773.nq.gz
    ├── 0fd24c18ad262b931aa18a66012441197b57bf8a.nq.gz
    ├── 0fd2b7fca9502c27afdbb8ff3d97c65564b9ee14.nq.gz
    ├── 0fe55adf7eb1f4a60b42914dd89eb36a9083456c.nq.gz
    ├── 0ff0da32ae992ce0e06f98bdd18d5459baf28597.nq.gz
    ├── 0ffd02943799aa628d2a1404fef1a4142382cce2.nq.gz
    ├── 10023a7cf6075cd7ca1bf8cbba1cedf58bfe6e32.nq.gz
    ├── 105cbfbec50dd5db82bbd46512eb5ed34ba40326.nq.gz
    ├── 10702f75a1b6b450a6a91a69f187b30e7f87f3aa.nq.gz
    ├── 10aa163343d04b311fb69427245470405ae90d6d.nq.gz
    ├── 10add10739494376069eef8037395375e2410837.nq.gz
    ├── 10af6d032982eda127b5f8d5038f2ccbd5cdd99f.nq.gz
    ├── 10ccdb8e2ce5c66e5a8162fbb4dbc1e40789d207.nq.gz
    ├── 1116f05158f3309ddd71a996c97be190d0746b76.nq.gz
    ├── 111c72e7f5800f2a5ce03cb9b88610e98a7aeede.nq.gz
    ├── 11271c9d5bf7e41bd99416db937f4dc760644b08.nq.gz
    ├── 11339831750b72d669f0fb23aa37d4f726c44e0e.nq.gz
    ├── 1142e00d2992d461da9abc8f9dfea46da3355cde.nq.gz
    ├── 114416727639e6a79dc956657d71f40976fa7192.nq.gz
    ├── 1181d261be70b05036258bccaecc26857bdfeb8e.nq.gz
    ├── 118d0a2ae9c16d03abba954d3ad78952a9de31aa.nq.gz
    ├── 119374c0ed651d674478364e3c701aa10f71b38b.nq.gz
    ├── 11c61b28a3b33d9fd0184bf82fa886c5fce46313.nq.gz
    ├── 11e2b079f0ed7fa98cc22792dc792775e5254c5b.nq.gz
    ├── 120d08d70d52dddf8ee323b6e41a3a2c2e7247ff.nq.gz
    ├── 12181fcf067f32cb7e9feb444113347881c3f477.nq.gz
    ├── 122a1890dbe8cb92da9eed110783538baeed201b.nq.gz
    ├── 122ebf20732e67068db0b24b6d65be73d9dc995e.nq.gz
    ├── 1243daef81864a64c4f8a7c144b0f9d37e3772d5.nq.gz
    ├── 125b07de9af7404c1d381faa054ff57f232f0c93.nq.gz
    ├── 1272f96f0355a4edce76c4ffcbd51121a5f42d09.nq.gz
    ├── 12de53f53d5f9f7260c8de520618c7e84b8b81d5.nq.gz
    ├── 1303532372ad26e0c6a91ff716ab848a38e94cb3.nq.gz
    ├── 130940f358b2e2957207ef89b024d970b3a03cd0.nq.gz
    ├── 13273b9fb58d69905e31b1ec0dfa24841baee6ea.nq.gz
    ├── 135f3be84083792f685522bce29a403357232ff7.nq.gz
    ├── 136a833f05b557b8792887ff1ee9573e2d5d13d3.nq.gz
    ├── 1371c62eeab333993b1e1b1d275280efcbed0c4f.nq.gz
    ├── 1394e1be0c16d8c8529bfa628985a0517f1c51d8.nq.gz
    ├── 139597f9cb07c5d48bed18984ec4747f4b4f3438.nq.gz
    ├── 1395cb23ea3ecbd0e4abd26dfc74e43ff3285f53.nq.gz
    ├── 13990e24afda8fa3121e58e4c1ca1a02cf38428b.nq.gz
    ├── 13b724ec9e6e8feffc769074f244c1284de92ce7.nq.gz
    └── 13d3a9d181439128da377569624c0f272bb91f40.nq.gz

6 directories, 200 files
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

[django/django](https://github.com/django/django)

---
*Parsed on 2026-04-01 by [repolex](https://repolex.ai)*
