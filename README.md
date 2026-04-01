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
    ├── 005e951595cef8b88b05964c27b59056e1065034.nq.gz
    ├── 00706797a26738f1d93e10fffa7367a4d382c402.nq.gz
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
    ├── 02a2c5318e44d66c0a24e283f15cf2c6d0c7464a.nq.gz
    ├── 02de295f88159cee6f62dd3656ffa54753ceae39.nq.gz
    ├── 030ac505fef15896b47be16f572cb54e2f45c0f7.nq.gz
    ├── 03780f28c22f7104431cf95a496bf20beeeb1691.nq.gz
    ├── 038dce5f8bc1a029043a83863d0851f358ccc848.nq.gz
    ├── 0391e5040067a7289970714e8f223e4e7ad5f522.nq.gz
    ├── 03c01b7656a364e51385d1939515a12188cb3a90.nq.gz
    ├── 03c683b844849a47584d5035302311ee718bbdc4.nq.gz
    ├── 03f5ff12813b993920aaa72f493378440bfd432d.nq.gz
    ├── 040130cc1a93e7a6819367e19fd7e0971a8e7642.nq.gz
    ├── 04498db00c17069867a2436a6994ac96773022fa.nq.gz
    ├── 045533612dcb659ad706a5270cb2bbc92ce2e6b6.nq.gz
    ├── 0484e5f9b2eec8e3eed4f92cc0c261e1509cb847.nq.gz
    ├── 0489ea81d82e628727fb768cc307f8f2e5e57ac4.nq.gz
    ├── 04d68cd26cb3cb2b9f280d715d91eb8bd2832396.nq.gz
    ├── 0504592ebb415bfdb88e30723d1be6e46cb2e6d9.nq.gz
    ├── 057e2f715e26cdf4aa7ad92bbc2f4918ba957018.nq.gz
    ├── 05d322363bf2060fafbfa5b51a4630d21c901823.nq.gz
    ├── 0611e01643a4837066c109970305b8d7f278c38a.nq.gz
    ├── 0637a088a01e8ddab3bf3fa98dbe804cbde1a0dc.nq.gz
    ├── 0656c323aeafcc3fc135f15098821ee5752f3b75.nq.gz
    ├── 067edb6f7301524db930046ebaeb0b0801184ad7.nq.gz
    ├── 069a99b2d207f477a99a4ee093bdde5d744a1f44.nq.gz
    ├── 06a886e0beb885dea12f2e8558c85790f0763441.nq.gz
    ├── 06d21bbdd48f244325f84147f7d128ccaba9fbae.nq.gz
    ├── 0700b46ea8e98461cdfd054182a88dba9fb13077.nq.gz
    ├── 073964dfac71a10989148031540d0459fec58f21.nq.gz
    ├── 0796306e07f6c70694b465e5c87606e0dd81358b.nq.gz
    ├── 0798acc7dbff6b8a20db4c3343a127104cb17604.nq.gz
    ├── 07a62a7fbe863b9ed0019f4061e96aeb25b479c0.nq.gz
    ├── 07a9bf39b78e6b20fabce01cc5687f3e7a79753b.nq.gz
    ├── 07f955a38d7dabe8d4864178371bde15190923d2.nq.gz
    ├── 08436df35572ff4505e3639556d72a7c4b87167d.nq.gz
    ├── 0873281e51bdcfd1e7eb5bbfbde3a09c4cbc943e.nq.gz
    ├── 087f3da1f7b668d3f1151fcb9d8d0b985a886ef8.nq.gz
    ├── 09026aa010405959205725735a15533aef39aa1e.nq.gz
    ├── 0916f52388b65d745f9674b1adf4a87ee2a06acf.nq.gz
    ├── 091f7f32b43e6e7ea379185a96c43f7504e4cc4c.nq.gz
    ├── 096afc4394223970b1ff047a5bd3741bbf8e4de5.nq.gz
    ├── 098bca793f9026c0cf826a8652b84e1d96b8643a.nq.gz
    ├── 09e0826b88bf04a0cc34d8af1e9749a57f0c3b65.nq.gz
    ├── 09f292e0373fe87e60d1274be3bb6341417cd9b9.nq.gz
    ├── 0a23ba79b091512af422155574042377fe7b8796.nq.gz
    ├── 0a68b82a106ce07faa61acebd7cdf278d4d1ca02.nq.gz
    ├── 0a784fa769212348b3cb42f43f2d32c54e6fff6a.nq.gz
    ├── 0ab7a72d57393414823829dcb233571f45130f7d.nq.gz
    ├── 0aef3e91c3ece2aacac7a3f587f04080d6c981e6.nq.gz
    ├── 0b133a11f2cf37ccf9c27f611f75f79fe4116075.nq.gz
    ├── 0b368f13855477e10a66cbd53e96131ed8a018b1.nq.gz
    ├── 0b82bca9c4fdb60e9d4e90efbb50a7e05b67145c.nq.gz
    ├── 0b935f1eacd04e2c6923ece763fa5d9fcfeaa9ba.nq.gz
    ├── 0bc6fe14b33274b524fb9e4a68a98a9a8eae03f2.nq.gz
    ├── 0be0984ff5a3d569aa57f9159c60afa92d132fa6.nq.gz
    ├── 0be93a20c3c36845a3242a8bae7a58f8e11eab31.nq.gz
    ├── 0c3ef57af84156e84e4ab78f02e2e752c8c7bbda.nq.gz
    ├── 0c434772f8b045d6676f1f97422dc59873df782f.nq.gz
    ├── 0c975116ef99b2698dfb4c221f048d3a0bbe770d.nq.gz
    ├── 0ca577059ee576e32a4cc200974ce85d85c7f185.nq.gz
    ├── 0d1bf557eaae837d56b8f366259fc01116bc6d0b.nq.gz
    ├── 0d2f393ef4ece1c9058a61b705150ae27e7251ea.nq.gz
    ├── 0d41b053b23ca8b4b51022c70df8a961fda2ad46.nq.gz
    ├── 0d54948bf5a21ef9dd604f0cb595ed2f537712aa.nq.gz
    ├── 0d9c68f9e0d80e89e4a0ec2df54f5a5d40d27387.nq.gz
    ├── 0dbe30d70916650ff16ed34f6677e4fb21717b9e.nq.gz
    ├── 0dce7eabc9e3e2485b358f41968cdfb578287a67.nq.gz
    ├── 0dcf6259392ed66377258f0c41035f853ced1c7a.nq.gz
    ├── 0deaf6a1783f733a5a5b3aa7b8413c08e283451c.nq.gz
    ├── 0df69aeb94e59626151b54bcea407675817c193f.nq.gz
    ├── 0e0510d707561f2c4409ef078ca224150adaa50e.nq.gz
    ├── 0e511d7360b39bb010742cca0479404354b9c1d1.nq.gz
    ├── 0e594fa5d82f7ee283c50703b3c2e29d0b9c99a5.nq.gz
    ├── 0eca3f4293db5ab24a40085eb304e473b85566a4.nq.gz
    ├── 0ed0ef481950cc16ba916f2f8c519f4fb167fbeb.nq.gz
    ├── 0eda8f02da5993011c59b6e951fc3939f41f6d45.nq.gz
    ├── 0eeb485797ce71155c3439704299dcb621d33fd4.nq.gz
    ├── 0efe779eb9f1b47fa00ecbd282804fc520945f1f.nq.gz
    ├── 0efedf3632e7ab02c998ec45d6f6cb0dd25cb424.nq.gz
    ├── 0f6634633748cc74f93f75a5ec94e12265cd53ca.nq.gz
    ├── 0faa39a6a94dcbce6c99768e38ea903b6d3c7100.nq.gz
    ├── 0fd2b7fca9502c27afdbb8ff3d97c65564b9ee14.nq.gz
    ├── 0fe55adf7eb1f4a60b42914dd89eb36a9083456c.nq.gz
    ├── 0ffd02943799aa628d2a1404fef1a4142382cce2.nq.gz
    ├── 10023a7cf6075cd7ca1bf8cbba1cedf58bfe6e32.nq.gz
    ├── 10aa163343d04b311fb69427245470405ae90d6d.nq.gz
    ├── 10add10739494376069eef8037395375e2410837.nq.gz
    ├── 10af6d032982eda127b5f8d5038f2ccbd5cdd99f.nq.gz
    ├── 111c72e7f5800f2a5ce03cb9b88610e98a7aeede.nq.gz
    ├── 1142e00d2992d461da9abc8f9dfea46da3355cde.nq.gz
    ├── 114416727639e6a79dc956657d71f40976fa7192.nq.gz
    ├── 1181d261be70b05036258bccaecc26857bdfeb8e.nq.gz
    ├── 119374c0ed651d674478364e3c701aa10f71b38b.nq.gz
    ├── 120d08d70d52dddf8ee323b6e41a3a2c2e7247ff.nq.gz
    ├── 12181fcf067f32cb7e9feb444113347881c3f477.nq.gz
    ├── 122a1890dbe8cb92da9eed110783538baeed201b.nq.gz
    ├── 122ebf20732e67068db0b24b6d65be73d9dc995e.nq.gz
    ├── 1243daef81864a64c4f8a7c144b0f9d37e3772d5.nq.gz
    ├── 130940f358b2e2957207ef89b024d970b3a03cd0.nq.gz
    ├── 135f3be84083792f685522bce29a403357232ff7.nq.gz
    ├── 1371c62eeab333993b1e1b1d275280efcbed0c4f.nq.gz
    ├── 139597f9cb07c5d48bed18984ec4747f4b4f3438.nq.gz
    ├── 13990e24afda8fa3121e58e4c1ca1a02cf38428b.nq.gz
    ├── 13d3a9d181439128da377569624c0f272bb91f40.nq.gz
    ├── 13e07f8202deef2f25bcca6fd4c9e765aed25a69.nq.gz
    ├── 1410ed7517aee329bda4a465b007d620079a24ae.nq.gz
    ├── 142931bfd6b59db447965a6324baa17ea808ee5c.nq.gz
    ├── 145bf90768622f96d710df787519425c03473dd8.nq.gz
    ├── 14605d7e7e5c9f828a9a262a0315c3c4259f3c1b.nq.gz
    ├── 148edfcbbb548da291d232bce2ff074913d016aa.nq.gz
    ├── 150bb01dc0aba8fb8e8d0ee0c639688b41540683.nq.gz
    ├── 15252b472a4483413ba4d579190ad7de63cc2a0f.nq.gz
    ├── 1541b23fb303d14054cdea7b1a568232e5cb8efc.nq.gz
    ├── 1548cfa77ed7a70df1f9b6f3bb297bad901f4bc2.nq.gz
    ├── 15a169dc378701322a709c5b5b8b75d48b7f4e85.nq.gz
    ├── 16104277c599dafa6e9efd20a9b1662bc429027b.nq.gz
    ├── 1615a73406b976bddc4036a202a4650a702c6296.nq.gz
    ├── 168a8345caa3c592647a7097abe4c232fa98cf39.nq.gz
    ├── 16bc0864ea603a05c1c6d27d6f5f6f1aa2e5cd7b.nq.gz
    ├── 16d75fd88b9d101d82d86ae85fb25d78a8f5a1db.nq.gz
    ├── 16f5f9f99019f93f04f278f8a812916503061534.nq.gz
    ├── 17213ea5b33949813cda7b79236dd68797bfb392.nq.gz
    ├── 172c1268a78cbb07e245872a14c9b70cc7e23f28.nq.gz
    ├── 172ca5271e63fc0e75aae9263d303d4860547088.nq.gz
    ├── 1763bf2523908891194bbe64767a9767c8c71815.nq.gz
    ├── 17797bb7a6e7f50f74c0e2e05c2ad417b019db2f.nq.gz
    ├── 17a600f8999b549591c8281a134b130d873f15b6.nq.gz
    ├── 17aed153b31c343e2f4b133c7f394bfac46c4436.nq.gz
    ├── 17c52861ee68f9b1d8f78398dace8a7012b3a872.nq.gz
    ├── 17daca9fd695d8e1c89f4abef1ed967c03543634.nq.gz
    ├── 17fad024e5016efa26f2fe3d37f8079296c44fb4.nq.gz
    ├── 1800d48fc366ada3935a832ca5c4f366d3f4ae1f.nq.gz
    ├── 181197a8d7b3abd127852d68df3dc549ca135174.nq.gz
    ├── 181c551c24fdacd19fa484c6da9a3a95d343038c.nq.gz
    ├── 186a0e8da993aa1331df308a8bbb34b23b766f57.nq.gz
    ├── 18aeb7f5d3898b9e8b19cfe57f51692a1de13396.nq.gz
    ├── 18afb72a93cb681b1ca431abcfd11951a0a9aa64.nq.gz
    ├── 18b8f665a53bdd15d1cc2fcbb746f25bc6136dd2.nq.gz
    ├── 18e701093c3cec3beadab2c84bc1cb2f665c7693.nq.gz
    ├── 18faa6a1305186d4e9c3d1f6772233bee70381aa.nq.gz
    ├── 19042faf94e429c5d59ff662ee3cc4f2a93b687b.nq.gz
    ├── 190cb7012875e8268504626f50aa32628de8606b.nq.gz
    ├── 1972ac72ee9de07133db5e044535c7c42aa22989.nq.gz
    ├── 19dbbd1ae44e3244257c2d423bfba43483d6cff5.nq.gz
    ├── 19e2696b931c81e1ebbf21e6cc0fe1e311d4782a.nq.gz
    ├── 19f81d601acc0230a3ebc0b0d98b6bf47cc7e1ba.nq.gz
    ├── 1a11690ab65f068eb6f0eca63cf57efadfcf3e45.nq.gz
    ├── 1a72a92caf05fd71c178bf1618afc16d277a4d40.nq.gz
    ├── 1a93f22058eb48304c172ec32ad587b5ae7680d5.nq.gz
    ├── 1a95aad2fb159dfa39cf5aee9401afcf54b0b1e3.nq.gz
    ├── 1a993b523dc08e224eb5123de9fb0f7715434447.nq.gz
    ├── 1ac2a39908796e15bda5c4b45c7cdd08ab413571.nq.gz
    ├── 1b4ee5814570885705399533f1182f8b0491c5fb.nq.gz
    ├── 1b7693eb088707693ef3fd5c2ec32109e0798a7b.nq.gz
    ├── 1b7b00a69a0d287e97e0ec900905293bcb8524cc.nq.gz
    ├── 1bdb2d4452b201a8ddb42c2d71aeb6f9127df690.nq.gz
    ├── 1bffc7d22538186f21c1fea45b597bf29b1c98e3.nq.gz
    ├── 1c210317398d632e3f2138e65c09d3dbd959ccbb.nq.gz
    ├── 1c46ccc5fc2f36cde09ec492ecb3b11585c169c7.nq.gz
    ├── 1c844164230502d7295ee654023e26270edf27c0.nq.gz
    ├── 1c8b63c61e6d914acb8cfd8446daf9a6f2621c1f.nq.gz
    ├── 1cece7c7c03b9d60ec0d0845f258e71ca2b60e45.nq.gz
    ├── 1d39e0e22b9e07aa83f8d47bef4b460b74d4d569.nq.gz
    ├── 1d765c8b1715d19890e9172a295e05685719fb07.nq.gz
    ├── 1d7d945ef73c7dbd5af0da3a842d29b424ce7c9a.nq.gz
    ├── 1da646bbda9493217d914d575a9d2521d7950294.nq.gz
    ├── 1db3cb510df06ccb42e14b2db0a9ec29ab33b637.nq.gz
    ├── 1de523dd36361e2a8347e9bbb3ab3face5547ab7.nq.gz
    ├── 1de89774d7a96820eae5d393220dcfcf32a0326f.nq.gz
    ├── 1e4c480fb91248b88d740c4d00d35ba393242cba.nq.gz
    ├── 1ea5865ea7f69244ea245a4377187cb0f14f58d5.nq.gz
    ├── 1eace25bef2b12095e9d799a29f7166eb9540c0f.nq.gz
    ├── 1eb17901329c4a02b8d99f276f6f64bb580fa591.nq.gz
    ├── 1ee8b2625828e3ce0b89a1327124aaf9823e7b10.nq.gz
    ├── 1f5abe174bd36a2cfb581e2ddeffbf10931f8f22.nq.gz
    ├── 1f5beb153d851fae1893f46f21aab8afdce04754.nq.gz
    ├── 1ff65ac31b562a12c87092b5d94c575c6fea3099.nq.gz
    ├── 200ddceae3ee4cc1e229385b7098cc5eabea782c.nq.gz
    ├── 20315c5c799e82f1fdf5fbde0fb2dd773db8794f.nq.gz
    ├── 2039bd5ddf8996907cf241ae4f5e913669bbc307.nq.gz
    └── 2049289a0b2ec5d4b8b9f1f6e8b5475f8c47336a.nq.gz

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
