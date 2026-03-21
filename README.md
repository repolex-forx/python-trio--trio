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
│   │   ├── 27e211402b4780888e4e1d297244ef04908932c1.nq.gz
│   │   ├── 70b1df9b006d5fee134076e4c8b085c0814aa111.nq.gz
│   │   ├── 776178a8f8b9ec995dd8b25a5c12bf2f005027ab.nq.gz
│   │   ├── 7fa11bdbcfee1c65d0bff590337ed4355ebbe44b.nq.gz
│   │   ├── 84d550d21ea59e54b0ae60676e53b9f1ff92fc8e.nq.gz
│   │   ├── 9f4b571141c15a41860e09570865fd7a041a4e5d.nq.gz
│   │   └── ff0ede5d79902e1c886e8804f6d9a74b42f031c4.nq.gz
│   ├── lsp
│   │   ├── 27e211402b4780888e4e1d297244ef04908932c1.nq.gz
│   │   ├── 70b1df9b006d5fee134076e4c8b085c0814aa111.nq.gz
│   │   ├── 776178a8f8b9ec995dd8b25a5c12bf2f005027ab.nq.gz
│   │   ├── 7fa11bdbcfee1c65d0bff590337ed4355ebbe44b.nq.gz
│   │   ├── 84d550d21ea59e54b0ae60676e53b9f1ff92fc8e.nq.gz
│   │   ├── 9f4b571141c15a41860e09570865fd7a041a4e5d.nq.gz
│   │   └── ff0ede5d79902e1c886e8804f6d9a74b42f031c4.nq.gz
│   └── repolex
│       ├── 27e211402b4780888e4e1d297244ef04908932c1.nq.gz
│       ├── 70b1df9b006d5fee134076e4c8b085c0814aa111.nq.gz
│       ├── 776178a8f8b9ec995dd8b25a5c12bf2f005027ab.nq.gz
│       ├── 7fa11bdbcfee1c65d0bff590337ed4355ebbe44b.nq.gz
│       ├── 84d550d21ea59e54b0ae60676e53b9f1ff92fc8e.nq.gz
│       ├── 9f4b571141c15a41860e09570865fd7a041a4e5d.nq.gz
│       └── ff0ede5d79902e1c886e8804f6d9a74b42f031c4.nq.gz
└── blob
    ├── 00669e883ea71ea55e0187e6b5355389dfd5b823.nq.gz
    ├── 0066c8ec4ffecbc1d129519f928636ede8fd02b5.nq.gz
    ├── 009f9fa8f7d0ac9469cf49896346c62028094d66.nq.gz
    ├── 00fdd328f64b99f42a7e23ade168148e5babbbcd.nq.gz
    ├── 0142b09eeb7353165874c9e2591f11a36737a3d3.nq.gz
    ├── 017c5ea0599da5cb83b8a5acc3cbcc0799eef5e2.nq.gz
    ├── 030c546f886fa66b69411e3a5e58f1ab047df9d4.nq.gz
    ├── 048c38c1f74acdb98d835b1a21be5280b49466bd.nq.gz
    ├── 04a96c495c93d1e5280ebce387ee9f02a4d03685.nq.gz
    ├── 04bcdc71004a7a44fcebf0b073108e5abc0cbc9d.nq.gz
    ├── 054cd9eac0989d6cf3af33745102af959acf0c34.nq.gz
    ├── 057e28568e798058a85f08e883e3f7fcdee8ba4c.nq.gz
    ├── 0585fa516f1433994ce94a907fe29b8136062d47.nq.gz
    ├── 059a8a95d1b2b54254d86f2ed1461042f9b23743.nq.gz
    ├── 068a5684f408e34153f7512dbe788a27bf5e309b.nq.gz
    ├── 06adc5da97706967939e5eb0a0c8f1b0b801b0bf.nq.gz
    ├── 06f6a81e7e5689708082a34813db4ba37ef300a1.nq.gz
    ├── 0705c99035082ad97bf997f8e222af4f9a808c18.nq.gz
    ├── 07c0461429f72bbe463fa37c23a3dfcded16c5ec.nq.gz
    ├── 07ea83075330832c9f2cebb73b17b8d482bb83f4.nq.gz
    ├── 0811d9121c81b57a5f7f38177b3ab28ef53acc98.nq.gz
    ├── 093a3ebe083bd19d16f25b64540822c110e57735.nq.gz
    ├── 09a2b8d927a95760a611b2f1a903178ac560637c.nq.gz
    ├── 09b00d7a50a225019959819673d195c36c032b38.nq.gz
    ├── 0a46be780a84532fa3b0d465b59e345412b08044.nq.gz
    ├── 0b66ca227b1283bd4c602a146dca7694280ec418.nq.gz
    ├── 0bcfcb6e8ff5851e9de1e9705f15b82abb77adc6.nq.gz
    ├── 0c28450e5e1e1abc21913693a6d1e6f6be9b248b.nq.gz
    ├── 0c37928a550a6bd34b09cf59e0411432ee2d77a8.nq.gz
    ├── 0c70df18405eab83762d7a77df516aafadf19a65.nq.gz
    ├── 0d29e393b08bdbdb61959e368fd9b094c967de84.nq.gz
    ├── 0e4db4af49840fc3d0e280b4c250a9d369e90cfe.nq.gz
    ├── 0e814ba376c2b7b551c4a6908ff2d1652dab2ebe.nq.gz
    ├── 0ea4c2d48a2bcb4a8f7ee1629b65fd5f493a9a16.nq.gz
    ├── 0ebad58a80606857a714508bef92ee90ff09792c.nq.gz
    ├── 0edc71db1bce7cf779c855b97addb719cb607c63.nq.gz
    ├── 0eead76b76ac71c166e81bab1d684b0f7da4e976.nq.gz
    ├── 0f1e4771c5e9027357b5cb8fbbc368d104d4a5a0.nq.gz
    ├── 0f40f558c00f8f8d77f63009bcc3c9936398eed3.nq.gz
    ├── 0f6e0a0715a3fa625ea476b99b3d1c3310855d19.nq.gz
    ├── 0fdb3bf9ceed1b91ecd9f704bc248a443e41853e.nq.gz
    ├── 104c402ebf17ef55f9cdca2114f0a4449f6dd039.nq.gz
    ├── 1051aeb2191d66affb4d183e58b1fa5d1e642099.nq.gz
    ├── 115413a78d9b7a41ecedfae40c8c2bc25ebf5651.nq.gz
    ├── 1180f1b3124e8ad9b75266069967361be5b5269b.nq.gz
    ├── 118969f83d09d5bd1f16be8dc520c1b5a933f95e.nq.gz
    ├── 11a1e1846f02db54a674983727127787d8b611f4.nq.gz
    ├── 11fc66ade6a339b501e714a23cd2f5ce5872abed.nq.gz
    ├── 121513b20e80d517c58bc5e6fb5c7f2255ca441a.nq.gz
    ├── 12182c58af4f8e1938d6db6f0cd81ffd359ca9d9.nq.gz
    ├── 124392656b926dcf4caf81315363c8e64fee916a.nq.gz
    ├── 12e7fb085190235f7a94d6df346bbeae26b6b065.nq.gz
    ├── 132fdff09741552ee67dab6fd4fb5234f53eeb6a.nq.gz
    ├── 133b615d85b49753172b0cc62291d28a7397b716.nq.gz
    ├── 1340d049a2e3866a94b29c039ed965a72d4bd4eb.nq.gz
    ├── 1386e15280afe54b2c0ce7fb4ea9be4cdb4352ce.nq.gz
    ├── 13a75fd0291362099c74e06b69d5b6f922a90b55.nq.gz
    ├── 13ffe0c066c77f2a214b6e1b6e0b84fa2540abef.nq.gz
    ├── 14905b506836e0528c0d2e89f00422492a4adca8.nq.gz
    ├── 149260fc5dae7da074134897da1414599e0eebe2.nq.gz
    ├── 14eab22df7dbbb1e445dd594125721dee4b0b68a.nq.gz
    ├── 1583f4cd54bbc36c2b72567c1f29aa32626de198.nq.gz
    ├── 1625efae175c7a1edf06baea8d67debe9d34d434.nq.gz
    ├── 16a869f8efb24d6163437af4417d5ee31e5fbfe8.nq.gz
    ├── 16b323e98b8f545ed3f186d3abfb970e6381bf1b.nq.gz
    ├── 16ee8023319c800250080246b9868128e6d25a7a.nq.gz
    ├── 18403962d2fedb9ff395cdb708563782c3dcba33.nq.gz
    ├── 1984d8591e7800d2cde6cb0d0fd721eb4b2e89f1.nq.gz
    ├── 1a18141e17640b254e1ec42a3367135e93730156.nq.gz
    ├── 1a7df59910764b52fc7097e09db046c903826593.nq.gz
    ├── 1b209ddb263194baa05d3e9f45bdd6cade4b7b93.nq.gz
    ├── 1b4da0c00a717412afa755d8d29f0f44780af151.nq.gz
    ├── 1d0665f3476d71de930866a7af8684e4340fa0dc.nq.gz
    ├── 1d079ae8f8a4f06db97d4e8cf85d49ea62e84f6b.nq.gz
    ├── 1d3508875e1bbead60b97b3034f56404240c46e2.nq.gz
    ├── 1ddbfc2dcfb0394e4f5ccd56ff260b344ebd60c6.nq.gz
    ├── 1df9a92e740642f3b0cd9e3ab98f83a493610429.nq.gz
    ├── 1e8597ba42cb4305e9b05d4a1710dfff7240d08d.nq.gz
    ├── 1ec20bf8a49972877dd2a5651dd8f0f28680c656.nq.gz
    ├── 1f886e11abf3cfb424ee4ca5b3a780af153da44c.nq.gz
    ├── 1f90268aa0ce6f8404802509609b1b5f87e8009b.nq.gz
    ├── 2047e9564462c76bdb5cb0f570ed62e1f689eecf.nq.gz
    ├── 20821b40f231a574af30bde7bfb7472d3fe9442e.nq.gz
    ├── 209a766cb29844567e67cbd53c4d1fb155e56626.nq.gz
    ├── 21093b54dce1a27a238f08a95ad4cd68974234d2.nq.gz
    ├── 211aff3e7089ea44d2d23ee07aed4eece719ffdf.nq.gz
    ├── 212c9eef00e0f07665ad9e01012d0ae9bb273e55.nq.gz
    ├── 21fc492dff1367e5851f5138aac08e57732b840a.nq.gz
    ├── 2216692df4cbd0d6c29d40c79743dc6cde3ab57f.nq.gz
    ├── 229dea301c007367dc23bd758c0224f54be96a78.nq.gz
    ├── 235772f900b7e69f92d82364c0b0d98806ac9777.nq.gz
    ├── 23a1b0f6520f2ea22e7a743fd1d3381ce7bb901a.nq.gz
    ├── 2477596f726247eab40054e67807e67fcdc543e7.nq.gz
    ├── 24a9c52111a40d1463836c8b29ec60d8b4bfca6b.nq.gz
    ├── 25788617d55f87923ba754f4f91b4deba392e729.nq.gz
    ├── 25cef08d0d0bf39c7efc2747c1a4397f6ac013b7.nq.gz
    ├── 25e0fd2baf1030a20e8c724b4d21fcfa5285ce01.nq.gz
    ├── 2625238803b99100afacd8f71cd86cb00230ac6c.nq.gz
    ├── 265ba191d0044721096bee0bb7b518312e4938b1.nq.gz
    ├── 266fc0dbda82c7a2b033206cd1f799ce5e756b23.nq.gz
    ├── 27fd4d187de428076064fedde2c3af5e6af76a32.nq.gz
    ├── 284bcf82dd7221f85918d83b986afbbfb81c3336.nq.gz
    ├── 28fac173ffddd643cc90961916e966c26da91a14.nq.gz
    ├── 290365d8b02004a9b59a4953585ab5a396e484d6.nq.gz
    ├── 29683cafea5e6437a9a9e45dc3608dcea606bde4.nq.gz
    ├── 296a5a89eafc415d09bf7eae7230fad4ecb36f3e.nq.gz
    ├── 299a401df53eb4321e1980e45e5e0aafdfb082c9.nq.gz
    ├── 29c17715abd2f55bd1f740542dc619a4bbfc0a81.nq.gz
    ├── 29d44adc4a5c62934cc91de3d5bac12e66d31066.nq.gz
    ├── 29ece9d9b6a1a938b41176c59a4bd7b3b214a479.nq.gz
    ├── 2a32d6c9b5ea9709877bac54bd2796dff21bd451.nq.gz
    ├── 2a755acba31096357c1f9cd18c1e71a369799539.nq.gz
    ├── 2a79b3bec8f37d41285a91463b01384308117896.nq.gz
    ├── 2adb3f9a65abe9e99df40f9ec66703910f12f2d1.nq.gz
    ├── 2b569906aa19737b568802d045b8409e3d036188.nq.gz
    ├── 2bd0c74e679b0dd34e37542de5eb2385b2ee2435.nq.gz
    ├── 2be0d6ab98eb481fb797f4f61baa6b2dbc465dc6.nq.gz
    ├── 2bee358ee52dbd896f66d8bcd74f86641764701c.nq.gz
    ├── 2c19bd81ad5163d640da8b4679194e5fd2f4fc47.nq.gz
    ├── 2d25ca401c007dbf7af6089b093da50018d61be7.nq.gz
    ├── 2e2ffcc320ec3fa447b26580e29a2358fa3317ad.nq.gz
    ├── 2ebb4a0a5a6ea832ee6f485323e4cfce0fe45f6f.nq.gz
    ├── 2fb8a97092d5fa49ca973ba0c462243e7cf2d5fb.nq.gz
    ├── 304c44b9f6850aa7a77b0d4496eddb939f094f7c.nq.gz
    ├── 3092f18212c7e893809b851bdb0af57ace7bff6e.nq.gz
    ├── 30a9fff4da1a9bed9c9015a8ed51f7f518bf21ba.nq.gz
    ├── 30c868de57b6128c423430a73e13c818cf0b5ec4.nq.gz
    ├── 30e42da97e4a84ed5073a92765325592dd6d1546.nq.gz
    ├── 3124c20d4afbc9427725f521daf805d040180d65.nq.gz
    ├── 31940d56942160bc2b9eb9397b36660625371217.nq.gz
    ├── 31d69ab77dfe5d466de1e8c62ea9df1eb2974f2c.nq.gz
    ├── 31eeef1cd0c672c3582636ac614540de690722a0.nq.gz
    ├── 32468af46bfcb44c0ef031fbd4a52aa94eb5b04e.nq.gz
    ├── 32a68e1495d901a07e2400f14d81875a9f6b5086.nq.gz
    ├── 332b1a8dbf49a6a25732d09eb8bfce6f99d8f8fd.nq.gz
    ├── 349e67eec0c2158a0ba08215d6116431451ef27b.nq.gz
    ├── 352caa5682681c3f69e85de12ed5eccecb0b6087.nq.gz
    ├── 3593793fe14f8da55a9907b25350aa95646efb1d.nq.gz
    ├── 35a5619e4264c005da88c3d76f81f85811131b91.nq.gz
    ├── 35ae017f5970f721e5a82b0152117887a40a01c2.nq.gz
    ├── 35d22f49f4170ba413e536d49a5f77aa6f6945f4.nq.gz
    ├── 361cd64ce2f51279641c150cd5dd140d55ee0aea.nq.gz
    ├── 361e062ab0e88ed75fd9e4d93d51746119a8b6c0.nq.gz
    ├── 36aacecd961a11c9728eff0a321f3a3855a6bc65.nq.gz
    ├── 36b37e3e376038d44bf44f83890d5469212a3ec1.nq.gz
    ├── 36de1acd8b60903ae9021c6d3fcfb5d7c570950f.nq.gz
    ├── 37797424abc94e3789803a8d2646b66a4b377bed.nq.gz
    ├── 37e01b7d3b904e54e4aba65504d93ceac199f6e0.nq.gz
    ├── 381d966f8109dbd266e9055874fe90d478476dc1.nq.gz
    ├── 382c015b1d2ffc3a7655ad4e8c37572807f31e58.nq.gz
    ├── 38a1ffe862134d73f449e5cea8567b8abcb3b5e1.nq.gz
    ├── 38acfa802d2e1a2da6fa09bc3907bc6a25eaea9a.nq.gz
    ├── 38e545853ed55a9b71e383090b3fd4086dd2e827.nq.gz
    ├── 39581e1ac6d3b130d8a89d8e52d65421b9c1fb32.nq.gz
    ├── 397375503d2889aa52d351bc9f9fc599d07c01bf.nq.gz
    ├── 39885275fff31995d19147db0df6e5def5925322.nq.gz
    ├── 39ffeb5a4bb2b2548643b735ad9bf4e32c41ce03.nq.gz
    ├── 3a7dbe486f4bcc3b7b70070c8e093c29e5430ec5.nq.gz
    ├── 3a83e454e07efc838132a1c37285c7b8186ab2c9.nq.gz
    ├── 3b382eb466e4da0355fbb1197d7209c0742da870.nq.gz
    ├── 3b9255b23651588e8da12925b1eba166984c2d2a.nq.gz
    ├── 3c3830ea398bfcbeebefb9a423a0cf9f1418b7cd.nq.gz
    ├── 3c3b6bf1f5100e2f04a70f5c54efc3febed42cfb.nq.gz
    ├── 3ca395b7d5353b8516d2a25990b2dd68c7dc569c.nq.gz
    ├── 3cdaa2ca8e51c056beeafef11a1fef368cf88754.nq.gz
    ├── 3d54e1f2539c31e2a029abe6b46d909aa7b20263.nq.gz
    ├── 3ddfa5d524581d9a795bfb59903c2c3667430989.nq.gz
    ├── 3e496126450c016670b855f0ba5a47f66f9df473.nq.gz
    ├── 3ec404a8a2455e156118d2ac799b962dcc38c841.nq.gz
    ├── 40a275bbebfa8502f476a40e30917da932953195.nq.gz
    ├── 40c15865786942e25a10e4e6811d6f6c82cad536.nq.gz
    ├── 412ccf87320de407cbc7c97f02aba08d3730e413.nq.gz
    ├── 41a6025c3778ab71c64c027de167a46a8b35bee6.nq.gz
    ├── 41bf502611cb05733b2cad0255950e512a31d504.nq.gz
    ├── 4217fdc7e7e55218871e52d7d15054484c149ef5.nq.gz
    ├── 429ba9d9f7de537c527e1b101a34546155db2580.nq.gz
    ├── 429ed2a4e25e1d2c1e40659e062b47dd64fe15d4.nq.gz
    ├── 42de594ac8364c7d2c2f80eff6e5275645a92141.nq.gz
    └── 42ee79060de317e307de3e11d6f72682a9617095.nq.gz

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
*Parsed on 2026-03-21 by [repolex](https://repolex.ai)*
