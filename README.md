# Repolex Knowledge Graph of python-trio/trio

RDF knowledge graph data for [python-trio/trio](https://github.com/python-trio/trio), parsed by [repolex](https://repolex.ai).

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
lexq download python-trio/trio
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 069bdd03cafdf3824c81ddf8fddc8c1359bf1ee1.nq.gz
│   │   ├── 077e8fc3f1634b42ef5024814898439d8a8430d4.nq.gz
│   │   ├── 0b8d3e2435ca9cb00a1aab72bf98da334dec2b1c.nq.gz
│   │   ├── 0cb25fae4248263dd14bc84586207bfc7ec776dc.nq.gz
│   │   ├── 27e211402b4780888e4e1d297244ef04908932c1.nq.gz
│   │   ├── 36f3a37bb236356bf3ba45764df389a0e24e3933.nq.gz
│   │   ├── 60172de0c37a0d87c341cef3ef13f565ace343e9.nq.gz
│   │   ├── 6947901ef0da402d83d967a01351df3df95e6a00.nq.gz
│   │   ├── 70b1df9b006d5fee134076e4c8b085c0814aa111.nq.gz
│   │   ├── 776178a8f8b9ec995dd8b25a5c12bf2f005027ab.nq.gz
│   │   ├── 79dc7af4ad3d00031ea45968294a5ed3b61d9994.nq.gz
│   │   ├── 7ef6f09f79ec3ce3ba8c3658cfa79457c55952ed.nq.gz
│   │   ├── 7fa11bdbcfee1c65d0bff590337ed4355ebbe44b.nq.gz
│   │   ├── 84d550d21ea59e54b0ae60676e53b9f1ff92fc8e.nq.gz
│   │   ├── 87ea87018da2085180138bd952abcac67961be62.nq.gz
│   │   ├── 9f4b571141c15a41860e09570865fd7a041a4e5d.nq.gz
│   │   ├── b9851229f095ea4aa38c470b425c1a5341fe512f.nq.gz
│   │   ├── d0362a1a0c1d765f2e2f0e3db22df7ffe5d4380d.nq.gz
│   │   ├── eef24cb9787aa8f4f1707b4889ccd2a71419e3ce.nq.gz
│   │   ├── fa94d4cc1bf1a1619a09268cb06364a17bc6edbb.nq.gz
│   │   └── ff0ede5d79902e1c886e8804f6d9a74b42f031c4.nq.gz
│   ├── lsp
│   │   ├── 069bdd03cafdf3824c81ddf8fddc8c1359bf1ee1.nq.gz
│   │   ├── 077e8fc3f1634b42ef5024814898439d8a8430d4.nq.gz
│   │   ├── 0b8d3e2435ca9cb00a1aab72bf98da334dec2b1c.nq.gz
│   │   ├── 0cb25fae4248263dd14bc84586207bfc7ec776dc.nq.gz
│   │   ├── 27e211402b4780888e4e1d297244ef04908932c1.nq.gz
│   │   ├── 36f3a37bb236356bf3ba45764df389a0e24e3933.nq.gz
│   │   ├── 60172de0c37a0d87c341cef3ef13f565ace343e9.nq.gz
│   │   ├── 6947901ef0da402d83d967a01351df3df95e6a00.nq.gz
│   │   ├── 70b1df9b006d5fee134076e4c8b085c0814aa111.nq.gz
│   │   ├── 776178a8f8b9ec995dd8b25a5c12bf2f005027ab.nq.gz
│   │   ├── 79dc7af4ad3d00031ea45968294a5ed3b61d9994.nq.gz
│   │   ├── 7ef6f09f79ec3ce3ba8c3658cfa79457c55952ed.nq.gz
│   │   ├── 7fa11bdbcfee1c65d0bff590337ed4355ebbe44b.nq.gz
│   │   ├── 84d550d21ea59e54b0ae60676e53b9f1ff92fc8e.nq.gz
│   │   ├── 87ea87018da2085180138bd952abcac67961be62.nq.gz
│   │   ├── 9f4b571141c15a41860e09570865fd7a041a4e5d.nq.gz
│   │   ├── b9851229f095ea4aa38c470b425c1a5341fe512f.nq.gz
│   │   ├── d0362a1a0c1d765f2e2f0e3db22df7ffe5d4380d.nq.gz
│   │   ├── eef24cb9787aa8f4f1707b4889ccd2a71419e3ce.nq.gz
│   │   ├── fa94d4cc1bf1a1619a09268cb06364a17bc6edbb.nq.gz
│   │   └── ff0ede5d79902e1c886e8804f6d9a74b42f031c4.nq.gz
│   └── repolex
│       ├── 069bdd03cafdf3824c81ddf8fddc8c1359bf1ee1.nq.gz
│       ├── 077e8fc3f1634b42ef5024814898439d8a8430d4.nq.gz
│       ├── 0b8d3e2435ca9cb00a1aab72bf98da334dec2b1c.nq.gz
│       ├── 0cb25fae4248263dd14bc84586207bfc7ec776dc.nq.gz
│       ├── 27e211402b4780888e4e1d297244ef04908932c1.nq.gz
│       ├── 36f3a37bb236356bf3ba45764df389a0e24e3933.nq.gz
│       ├── 60172de0c37a0d87c341cef3ef13f565ace343e9.nq.gz
│       ├── 6947901ef0da402d83d967a01351df3df95e6a00.nq.gz
│       ├── 70b1df9b006d5fee134076e4c8b085c0814aa111.nq.gz
│       ├── 776178a8f8b9ec995dd8b25a5c12bf2f005027ab.nq.gz
│       ├── 79dc7af4ad3d00031ea45968294a5ed3b61d9994.nq.gz
│       ├── 7ef6f09f79ec3ce3ba8c3658cfa79457c55952ed.nq.gz
│       ├── 7fa11bdbcfee1c65d0bff590337ed4355ebbe44b.nq.gz
│       ├── 84d550d21ea59e54b0ae60676e53b9f1ff92fc8e.nq.gz
│       ├── 87ea87018da2085180138bd952abcac67961be62.nq.gz
│       ├── 9f4b571141c15a41860e09570865fd7a041a4e5d.nq.gz
│       ├── b9851229f095ea4aa38c470b425c1a5341fe512f.nq.gz
│       ├── d0362a1a0c1d765f2e2f0e3db22df7ffe5d4380d.nq.gz
│       ├── eef24cb9787aa8f4f1707b4889ccd2a71419e3ce.nq.gz
│       ├── fa94d4cc1bf1a1619a09268cb06364a17bc6edbb.nq.gz
│       └── ff0ede5d79902e1c886e8804f6d9a74b42f031c4.nq.gz
└── blob
    ├── 0010c7a2b4aacd15a99ed0e27e0939ce70a69e77.nq.gz
    ├── 00669e883ea71ea55e0187e6b5355389dfd5b823.nq.gz
    ├── 0066c8ec4ffecbc1d129519f928636ede8fd02b5.nq.gz
    ├── 009f9fa8f7d0ac9469cf49896346c62028094d66.nq.gz
    ├── 00b7d24ef6c31276b95d02b4f7d395ed131c5eca.nq.gz
    ├── 00ba2707644d25f5ec1fcb58b393aa1583561365.nq.gz
    ├── 00fdd328f64b99f42a7e23ade168148e5babbbcd.nq.gz
    ├── 0142b09eeb7353165874c9e2591f11a36737a3d3.nq.gz
    ├── 015065863ebc828a20eef7539570f0de29782183.nq.gz
    ├── 01582944dbdd48ea9ce835fb45de8ac279c76600.nq.gz
    ├── 016e0fd3e1c08875e7e7342a3973cc05b52e15c6.nq.gz
    ├── 017c5ea0599da5cb83b8a5acc3cbcc0799eef5e2.nq.gz
    ├── 01ab0728e13b780dc5d84b7aaddc998bba9be6f1.nq.gz
    ├── 01c5f696a340d4be6c13cc241ab35ddd336ff409.nq.gz
    ├── 01ce03ce594d7c79534cd432ea99bc31ede65d4d.nq.gz
    ├── 0233938058b226f8bb9bf728ee8c463943ca47db.nq.gz
    ├── 024dce39accbc260abf8c54ae3cfcff3beacbfad.nq.gz
    ├── 0251f087331d7f94b673898d0e54a695cff470b7.nq.gz
    ├── 02f1b7f0c263d6ccde58cc0d068c7c968ddcc8b7.nq.gz
    ├── 030c546f886fa66b69411e3a5e58f1ab047df9d4.nq.gz
    ├── 03173da00bec6473fb3dc2c2d4151da59a0b2cdc.nq.gz
    ├── 031dd1cda00a00ca984b4b39cf321e0f4fc92996.nq.gz
    ├── 034792b35dc5b92b0dafe0f056c898619349afa1.nq.gz
    ├── 03562c9edbbbe838526aac5cf0dac6cc8d32a121.nq.gz
    ├── 039dfbef0152026d97ec240f8821a4a6ff7f0a3e.nq.gz
    ├── 03b79065e25ceb8ab2ab71b84506142c015add86.nq.gz
    ├── 04098c8c607fbfdfbf5c7b87a279a4279f514702.nq.gz
    ├── 041a684c626895183df81c145aa09c7e9502d2bd.nq.gz
    ├── 0459ed8f71191041fa1610375078d906a4952034.nq.gz
    ├── 046412d3ae41f215d6c636216f94a9cfbb89e41c.nq.gz
    ├── 048c38c1f74acdb98d835b1a21be5280b49466bd.nq.gz
    ├── 048c69a7ec0af805dafa2459a449f4860a916cf8.nq.gz
    ├── 04a96c495c93d1e5280ebce387ee9f02a4d03685.nq.gz
    ├── 04bcdc71004a7a44fcebf0b073108e5abc0cbc9d.nq.gz
    ├── 054cd9eac0989d6cf3af33745102af959acf0c34.nq.gz
    ├── 0579d4420d0f08f36c7f90217411cc8ab4cb4dfd.nq.gz
    ├── 057e28568e798058a85f08e883e3f7fcdee8ba4c.nq.gz
    ├── 0585fa516f1433994ce94a907fe29b8136062d47.nq.gz
    ├── 058b5e0a49bc029b6e5a87d58df13c1e2affc06e.nq.gz
    ├── 058e9d0609623f7f67ca83150a07514b82d6c7db.nq.gz
    ├── 059a8a95d1b2b54254d86f2ed1461042f9b23743.nq.gz
    ├── 061a715104cc7c759583158f3e9a2a8bf571d160.nq.gz
    ├── 061cc093676b70a89b0202931d350c690b2e5648.nq.gz
    ├── 065322788d6d1502374fbbf351c96a7e1c65b6de.nq.gz
    ├── 068a5684f408e34153f7512dbe788a27bf5e309b.nq.gz
    ├── 06adc5da97706967939e5eb0a0c8f1b0b801b0bf.nq.gz
    ├── 06b0b155a9f7a5bc2ce85bc5ee06c0318c3f4a2f.nq.gz
    ├── 06bf86b66bda215802195b879b35dca49af32ce3.nq.gz
    ├── 06ee7900699fafbb2aa47839199d1879c1518b89.nq.gz
    ├── 06f6a81e7e5689708082a34813db4ba37ef300a1.nq.gz
    ├── 06fba43a87b558434387882d9817db1cb69d1b4c.nq.gz
    ├── 070068015c05b822a986acb57d5b9f19837c4cff.nq.gz
    ├── 0705c99035082ad97bf997f8e222af4f9a808c18.nq.gz
    ├── 071be8f2b388ccfc9dbf8db561d87e28c35c488a.nq.gz
    ├── 0775a107fdb8b2bd0604fb79716712edebf69dcf.nq.gz
    ├── 07bba9407de6e424c7a4eef2ad54e4c74c2c0d40.nq.gz
    ├── 07c0461429f72bbe463fa37c23a3dfcded16c5ec.nq.gz
    ├── 07ea83075330832c9f2cebb73b17b8d482bb83f4.nq.gz
    ├── 0811d9121c81b57a5f7f38177b3ab28ef53acc98.nq.gz
    ├── 08206569f55b6af9ea4ecb50903b379356f1affd.nq.gz
    ├── 088ffa25413a36a0b6325e5c8aeba743707cba47.nq.gz
    ├── 093a3ebe083bd19d16f25b64540822c110e57735.nq.gz
    ├── 093beb41029539ad2022481255d9cf1405d8d8f3.nq.gz
    ├── 093d3a202a97268a5774fbc484e44e021f646103.nq.gz
    ├── 095bdc779f385acbc4c0731cfd0a357c6253a003.nq.gz
    ├── 09a2b8d927a95760a611b2f1a903178ac560637c.nq.gz
    ├── 09b00d7a50a225019959819673d195c36c032b38.nq.gz
    ├── 09e5274d4bfa536490913c0da4c6eba40915cc10.nq.gz
    ├── 0a3bd1cba1983ace82d5e867b9694e69496e9bb1.nq.gz
    ├── 0a46be780a84532fa3b0d465b59e345412b08044.nq.gz
    ├── 0a6b3516b0e57bee0175751d871eaf799c7cf6ef.nq.gz
    ├── 0a6c6858175f43810b9411a6ea97f520512487b9.nq.gz
    ├── 0a70e7a9749ee3c977d113949b6eb1f1344b511f.nq.gz
    ├── 0a8179f88f034a63a3dde77cea9518258019b65a.nq.gz
    ├── 0a9553b854900b5d741a0efc2a7dfc632fea0f16.nq.gz
    ├── 0ae84d61e3bbafd070580282c57bdf0e14f432e4.nq.gz
    ├── 0b10ae71e1698da0199f9d35ea0b75660620710c.nq.gz
    ├── 0b66ca227b1283bd4c602a146dca7694280ec418.nq.gz
    ├── 0bbd47fada46fb6c33306e4ae4774332c46170fa.nq.gz
    ├── 0bcfcb6e8ff5851e9de1e9705f15b82abb77adc6.nq.gz
    ├── 0beb1ef1d847da3d3e53d2adb1ca3c67d3d1263e.nq.gz
    ├── 0c28450e5e1e1abc21913693a6d1e6f6be9b248b.nq.gz
    ├── 0c2930b1206408c36631e54921f8c16df7ac683c.nq.gz
    ├── 0c37928a550a6bd34b09cf59e0411432ee2d77a8.nq.gz
    ├── 0c70df18405eab83762d7a77df516aafadf19a65.nq.gz
    ├── 0d012a0af7e787391e6f5d8e383c34929af84146.nq.gz
    ├── 0d29e393b08bdbdb61959e368fd9b094c967de84.nq.gz
    ├── 0d2d11c53c9a42d64f573aec1fc9af7effdff4d9.nq.gz
    ├── 0d38168d57674e927448e06500ee50b37ba0946b.nq.gz
    ├── 0d9dbc0e92891186cba3dcb02e30f5bf5d793a67.nq.gz
    ├── 0dd7953086f8c3fa5465a151ec735ba5b39edf58.nq.gz
    ├── 0de0023941684f92b214d3bee57b5dabaffc5d97.nq.gz
    ├── 0de76aa54fb820a442166ea97dbe2c5d6547ec01.nq.gz
    ├── 0e0655c5aa0395ab033509ce144ea17c79030184.nq.gz
    ├── 0e26fea83a28be9c29ea924fe5fb1c532fd6ebdb.nq.gz
    ├── 0e46f37e17e16d8ca25eff4049eed9323efa400a.nq.gz
    ├── 0e4db4af49840fc3d0e280b4c250a9d369e90cfe.nq.gz
    ├── 0e814ba376c2b7b551c4a6908ff2d1652dab2ebe.nq.gz
    ├── 0e95e4e5c533970fee6e679713dc39eeb00da661.nq.gz
    ├── 0ea34619b50d72c8d68146c8ca95ea8ca3044ad0.nq.gz
    ├── 0ea4c2d48a2bcb4a8f7ee1629b65fd5f493a9a16.nq.gz
    ├── 0ebad58a80606857a714508bef92ee90ff09792c.nq.gz
    ├── 0edc71db1bce7cf779c855b97addb719cb607c63.nq.gz
    ├── 0eead76b76ac71c166e81bab1d684b0f7da4e976.nq.gz
    ├── 0f1e4771c5e9027357b5cb8fbbc368d104d4a5a0.nq.gz
    ├── 0f2778dc158124939ecee2c7c6d7219718109205.nq.gz
    ├── 0f3b6a0bafb4ed464a6e022cb842a6431ff77fbb.nq.gz
    ├── 0f40f558c00f8f8d77f63009bcc3c9936398eed3.nq.gz
    ├── 0f6e0a0715a3fa625ea476b99b3d1c3310855d19.nq.gz
    ├── 0f90b170e16b528b26a1fa393733742021ccf44c.nq.gz
    ├── 0f968e26ced7b79e0669ecf9af47dc72545d52c7.nq.gz
    ├── 0fdb3bf9ceed1b91ecd9f704bc248a443e41853e.nq.gz
    ├── 0fe51370d573245f1518053bc79a429bc6e2ac9e.nq.gz
    ├── 0ff11209a74722ff0b63ebd8c3a1c656d32ff303.nq.gz
    ├── 0ff4babb990bf9b3342551f01ba8c85019542cb7.nq.gz
    ├── 1036e557f0ad7b232171a0506bba29ce1b15b4b9.nq.gz
    ├── 103984739e406843f1205155711ea14abd0597c3.nq.gz
    ├── 104c402ebf17ef55f9cdca2114f0a4449f6dd039.nq.gz
    ├── 1051aeb2191d66affb4d183e58b1fa5d1e642099.nq.gz
    ├── 10c14ae6625ca0b8627ee6511aaf4221fe340f1d.nq.gz
    ├── 10e6c13d8fd61b45ba50e4ee24dc3251efd86807.nq.gz
    ├── 112ed04d7af6331f536723ddf49388c8d19ab3e3.nq.gz
    ├── 115211934cd246ab93877d1eff2f1fa2a9a3feef.nq.gz
    ├── 115413a78d9b7a41ecedfae40c8c2bc25ebf5651.nq.gz
    ├── 11594b7cc738060a2649392c4551186a176408c3.nq.gz
    ├── 1180f1b3124e8ad9b75266069967361be5b5269b.nq.gz
    ├── 118969f83d09d5bd1f16be8dc520c1b5a933f95e.nq.gz
    ├── 11a1e1846f02db54a674983727127787d8b611f4.nq.gz
    ├── 11eda8e96fc041437dd01d1e81b419bcd3eb90a7.nq.gz
    ├── 11fbed45f2f2156d13169525b46cdf777608f055.nq.gz
    ├── 11fc66ade6a339b501e714a23cd2f5ce5872abed.nq.gz
    ├── 121513b20e80d517c58bc5e6fb5c7f2255ca441a.nq.gz
    ├── 121724446aad4af53b5e7dc80585d4687f17e0e2.nq.gz
    ├── 12182c58af4f8e1938d6db6f0cd81ffd359ca9d9.nq.gz
    ├── 121cec584e1691521173e420cdd6c7e194e75dbe.nq.gz
    ├── 124392656b926dcf4caf81315363c8e64fee916a.nq.gz
    └── 1271f6b765d360b1af0bb70253a4264ac3171a8c.nq.gz

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

[python-trio/trio](https://github.com/python-trio/trio)

---
*Parsed on 2026-03-23 by [repolex](https://repolex.ai)*
