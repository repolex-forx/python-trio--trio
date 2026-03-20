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
│   │   └── 776178a8f8b9ec995dd8b25a5c12bf2f005027ab.nq.gz
│   ├── lsp
│   │   └── 776178a8f8b9ec995dd8b25a5c12bf2f005027ab.nq.gz
│   └── repolex
│       └── 776178a8f8b9ec995dd8b25a5c12bf2f005027ab.nq.gz
└── blob
    ├── 0066c8ec4ffecbc1d129519f928636ede8fd02b5.nq.gz
    ├── 00fdd328f64b99f42a7e23ade168148e5babbbcd.nq.gz
    ├── 0142b09eeb7353165874c9e2591f11a36737a3d3.nq.gz
    ├── 017c5ea0599da5cb83b8a5acc3cbcc0799eef5e2.nq.gz
    ├── 030c546f886fa66b69411e3a5e58f1ab047df9d4.nq.gz
    ├── 048c38c1f74acdb98d835b1a21be5280b49466bd.nq.gz
    ├── 054cd9eac0989d6cf3af33745102af959acf0c34.nq.gz
    ├── 059a8a95d1b2b54254d86f2ed1461042f9b23743.nq.gz
    ├── 06adc5da97706967939e5eb0a0c8f1b0b801b0bf.nq.gz
    ├── 06f6a81e7e5689708082a34813db4ba37ef300a1.nq.gz
    ├── 07ea83075330832c9f2cebb73b17b8d482bb83f4.nq.gz
    ├── 093a3ebe083bd19d16f25b64540822c110e57735.nq.gz
    ├── 09a2b8d927a95760a611b2f1a903178ac560637c.nq.gz
    ├── 09b00d7a50a225019959819673d195c36c032b38.nq.gz
    ├── 0b66ca227b1283bd4c602a146dca7694280ec418.nq.gz
    ├── 0bcfcb6e8ff5851e9de1e9705f15b82abb77adc6.nq.gz
    ├── 0c70df18405eab83762d7a77df516aafadf19a65.nq.gz
    ├── 0e814ba376c2b7b551c4a6908ff2d1652dab2ebe.nq.gz
    ├── 0ea4c2d48a2bcb4a8f7ee1629b65fd5f493a9a16.nq.gz
    ├── 0ebad58a80606857a714508bef92ee90ff09792c.nq.gz
    ├── 0edc71db1bce7cf779c855b97addb719cb607c63.nq.gz
    ├── 0f1e4771c5e9027357b5cb8fbbc368d104d4a5a0.nq.gz
    ├── 0f40f558c00f8f8d77f63009bcc3c9936398eed3.nq.gz
    ├── 0fdb3bf9ceed1b91ecd9f704bc248a443e41853e.nq.gz
    ├── 104c402ebf17ef55f9cdca2114f0a4449f6dd039.nq.gz
    ├── 1051aeb2191d66affb4d183e58b1fa5d1e642099.nq.gz
    ├── 115413a78d9b7a41ecedfae40c8c2bc25ebf5651.nq.gz
    ├── 1180f1b3124e8ad9b75266069967361be5b5269b.nq.gz
    ├── 11fc66ade6a339b501e714a23cd2f5ce5872abed.nq.gz
    ├── 121513b20e80d517c58bc5e6fb5c7f2255ca441a.nq.gz
    ├── 124392656b926dcf4caf81315363c8e64fee916a.nq.gz
    ├── 13a75fd0291362099c74e06b69d5b6f922a90b55.nq.gz
    ├── 14905b506836e0528c0d2e89f00422492a4adca8.nq.gz
    ├── 149260fc5dae7da074134897da1414599e0eebe2.nq.gz
    ├── 1625efae175c7a1edf06baea8d67debe9d34d434.nq.gz
    ├── 1984d8591e7800d2cde6cb0d0fd721eb4b2e89f1.nq.gz
    ├── 1a7df59910764b52fc7097e09db046c903826593.nq.gz
    ├── 1ddbfc2dcfb0394e4f5ccd56ff260b344ebd60c6.nq.gz
    ├── 1df9a92e740642f3b0cd9e3ab98f83a493610429.nq.gz
    ├── 1e8597ba42cb4305e9b05d4a1710dfff7240d08d.nq.gz
    ├── 1ec20bf8a49972877dd2a5651dd8f0f28680c656.nq.gz
    ├── 2047e9564462c76bdb5cb0f570ed62e1f689eecf.nq.gz
    ├── 209a766cb29844567e67cbd53c4d1fb155e56626.nq.gz
    ├── 212c9eef00e0f07665ad9e01012d0ae9bb273e55.nq.gz
    ├── 2216692df4cbd0d6c29d40c79743dc6cde3ab57f.nq.gz
    ├── 2477596f726247eab40054e67807e67fcdc543e7.nq.gz
    ├── 24a9c52111a40d1463836c8b29ec60d8b4bfca6b.nq.gz
    ├── 25788617d55f87923ba754f4f91b4deba392e729.nq.gz
    ├── 25cef08d0d0bf39c7efc2747c1a4397f6ac013b7.nq.gz
    ├── 25e0fd2baf1030a20e8c724b4d21fcfa5285ce01.nq.gz
    ├── 265ba191d0044721096bee0bb7b518312e4938b1.nq.gz
    ├── 28fac173ffddd643cc90961916e966c26da91a14.nq.gz
    ├── 290365d8b02004a9b59a4953585ab5a396e484d6.nq.gz
    ├── 29683cafea5e6437a9a9e45dc3608dcea606bde4.nq.gz
    ├── 296a5a89eafc415d09bf7eae7230fad4ecb36f3e.nq.gz
    ├── 299a401df53eb4321e1980e45e5e0aafdfb082c9.nq.gz
    ├── 29c17715abd2f55bd1f740542dc619a4bbfc0a81.nq.gz
    ├── 29d44adc4a5c62934cc91de3d5bac12e66d31066.nq.gz
    ├── 29ece9d9b6a1a938b41176c59a4bd7b3b214a479.nq.gz
    ├── 2a755acba31096357c1f9cd18c1e71a369799539.nq.gz
    ├── 2a79b3bec8f37d41285a91463b01384308117896.nq.gz
    ├── 2b569906aa19737b568802d045b8409e3d036188.nq.gz
    ├── 2be0d6ab98eb481fb797f4f61baa6b2dbc465dc6.nq.gz
    ├── 2bee358ee52dbd896f66d8bcd74f86641764701c.nq.gz
    ├── 2c19bd81ad5163d640da8b4679194e5fd2f4fc47.nq.gz
    ├── 2d25ca401c007dbf7af6089b093da50018d61be7.nq.gz
    ├── 2e2ffcc320ec3fa447b26580e29a2358fa3317ad.nq.gz
    ├── 2ebb4a0a5a6ea832ee6f485323e4cfce0fe45f6f.nq.gz
    ├── 304c44b9f6850aa7a77b0d4496eddb939f094f7c.nq.gz
    ├── 3092f18212c7e893809b851bdb0af57ace7bff6e.nq.gz
    ├── 30a9fff4da1a9bed9c9015a8ed51f7f518bf21ba.nq.gz
    ├── 30c868de57b6128c423430a73e13c818cf0b5ec4.nq.gz
    ├── 31d69ab77dfe5d466de1e8c62ea9df1eb2974f2c.nq.gz
    ├── 32a68e1495d901a07e2400f14d81875a9f6b5086.nq.gz
    ├── 332b1a8dbf49a6a25732d09eb8bfce6f99d8f8fd.nq.gz
    ├── 35a5619e4264c005da88c3d76f81f85811131b91.nq.gz
    ├── 35ae017f5970f721e5a82b0152117887a40a01c2.nq.gz
    ├── 361e062ab0e88ed75fd9e4d93d51746119a8b6c0.nq.gz
    ├── 36de1acd8b60903ae9021c6d3fcfb5d7c570950f.nq.gz
    ├── 37e01b7d3b904e54e4aba65504d93ceac199f6e0.nq.gz
    ├── 382c015b1d2ffc3a7655ad4e8c37572807f31e58.nq.gz
    ├── 38a1ffe862134d73f449e5cea8567b8abcb3b5e1.nq.gz
    ├── 39581e1ac6d3b130d8a89d8e52d65421b9c1fb32.nq.gz
    ├── 39885275fff31995d19147db0df6e5def5925322.nq.gz
    ├── 39ffeb5a4bb2b2548643b735ad9bf4e32c41ce03.nq.gz
    ├── 3a7dbe486f4bcc3b7b70070c8e093c29e5430ec5.nq.gz
    ├── 3a83e454e07efc838132a1c37285c7b8186ab2c9.nq.gz
    ├── 3b382eb466e4da0355fbb1197d7209c0742da870.nq.gz
    ├── 3c3830ea398bfcbeebefb9a423a0cf9f1418b7cd.nq.gz
    ├── 3c3b6bf1f5100e2f04a70f5c54efc3febed42cfb.nq.gz
    ├── 3ca395b7d5353b8516d2a25990b2dd68c7dc569c.nq.gz
    ├── 3d54e1f2539c31e2a029abe6b46d909aa7b20263.nq.gz
    ├── 3e496126450c016670b855f0ba5a47f66f9df473.nq.gz
    ├── 41a6025c3778ab71c64c027de167a46a8b35bee6.nq.gz
    ├── 41bf502611cb05733b2cad0255950e512a31d504.nq.gz
    ├── 4217fdc7e7e55218871e52d7d15054484c149ef5.nq.gz
    ├── 429ba9d9f7de537c527e1b101a34546155db2580.nq.gz
    ├── 429ed2a4e25e1d2c1e40659e062b47dd64fe15d4.nq.gz
    ├── 42de594ac8364c7d2c2f80eff6e5275645a92141.nq.gz
    ├── 42ee79060de317e307de3e11d6f72682a9617095.nq.gz
    ├── 434772ddb6ac75aed018ff1f79b3a49fddcd3a38.nq.gz
    ├── 441f579f7c0051049c71a9b94b110900b949988c.nq.gz
    ├── 4494af7d6b0c0385c335ea9ee54b35d9d710f30b.nq.gz
    ├── 44db8cc8739a172973069e991d84478a12166935.nq.gz
    ├── 451aa1b777082aa48ffe1610e4ba44fb02105221.nq.gz
    ├── 45d8b8c5c5797771226e8e3f309f919b2a897c12.nq.gz
    ├── 45f21d389ae8d6f15662d6ff796adfea373bad80.nq.gz
    ├── 46f28d5471adc8b0a5a89519c8cd193f51f18a7e.nq.gz
    ├── 47296b7678381b86bfe3fbce17a7fa4db4a90a85.nq.gz
    ├── 47e253e79943d8aa987af1aea40f518acd3601cf.nq.gz
    ├── 48f19074aed3939c2b0733ab8d571e5f16d91d7f.nq.gz
    ├── 4b1de91b36452f88e39dd5986f36dffe74c2829b.nq.gz
    ├── 4b9911590b53548a17dd14526280276e4fddde79.nq.gz
    ├── 4bdbf69131959e6c4db0204caba741f011fa37a2.nq.gz
    ├── 4c4ac6987920e8ef53c8e820cfaca68008c4e6f1.nq.gz
    ├── 4cd148217a36b0f6db8bc3f5f8f232ebb0878f05.nq.gz
    ├── 4e3673167280f33dfca2114823dfde7a4891ddbf.nq.gz
    ├── 4e56fb80957455eea5811c72742383d5ac253689.nq.gz
    ├── 4fd0bb58f2bc803ce65a4248f21fcfe42cd13b07.nq.gz
    ├── 5022302759b65bbaf1217b85257aa3313ab24522.nq.gz
    ├── 50ac67f20afc069557c09f725a19f1de40e12300.nq.gz
    ├── 514636a1b421b138ce6341bd7009baff9586fc93.nq.gz
    ├── 535d62d3b2c3087b05b989d762fe530330ec3e32.nq.gz
    ├── 5419a0bce29b62a2b96276d13cf7c38df2900aa7.nq.gz
    ├── 541e9a687d3b5bbe4840a1b976a0e991173a895b.nq.gz
    ├── 551e65045651dfb76d1d76ad837297578010027a.nq.gz
    ├── 555e03c6e87b38372bf775c631daea83ab8beb1f.nq.gz
    ├── 564c5833b2e66cec76d25de0600cb9c4024ce902.nq.gz
    ├── 57a6b8166d1c3e1548b075fa9b06f867f1acc8cb.nq.gz
    ├── 581389c4546bbe2e4e19a3b97cd2e053b4d09391.nq.gz
    ├── 5871ed8eef2f90304e1f64c12ba17e1915250724.nq.gz
    ├── 5896933871d9e0b2eba39af6f55c77ff59ddf92f.nq.gz
    ├── 5992c4f73e49c5d2197dc100a93a6fbf1724f08b.nq.gz
    ├── 59a447d32a85cd8cc1e82509aa1a1940634a20b9.nq.gz
    ├── 59bec8618bd662f39410793bc5728ed75f16004d.nq.gz
    ├── 59e70dd147d74efa580b4d5be7ee42ba6ac17f3d.nq.gz
    ├── 5b150671b7add36ae84709dabd6a2a22792c093b.nq.gz
    ├── 5bd950f0ab05a0316a760e93bc26a09de1c1a319.nq.gz
    ├── 5c333bbcb164a60cbc1cdf3a1822d5020da1d539.nq.gz
    ├── 5dd61bdd73b62bc2463d3aa09275a9414a1de688.nq.gz
    ├── 5eb4ec8ef47b6a0e1b423460481b4e765c710cbe.nq.gz
    ├── 5fe32c03d915d41880e45578b163a3d8080dc15b.nq.gz
    ├── 601a8ff437727bad5226ce3e7f059a1ec2913127.nq.gz
    ├── 601aae5fdeb8d30b4678aa432eca8c4a47ce7dce.nq.gz
    ├── 63ac754bcc5739a4b530aba74889e6436054d113.nq.gz
    ├── 64430a0f92bb6f9bc31033e574aa6e8af7ab2882.nq.gz
    ├── 652960ed14f7d4ddfaaed5d23223d17383e740f2.nq.gz
    ├── 677b760f4ca484e51dfb79011288d35f8976d8a3.nq.gz
    ├── 67ce82b176c7ae57108231f7c937de1f8397fe4b.nq.gz
    ├── 6852d63200e151dd4b99ba81ff8f6c9bf9928ab0.nq.gz
    ├── 68bd632be83e8ee44f8ed49cf5738e644cbc39f9.nq.gz
    ├── 68f47622217ab6e3f8549c2b176bf4722628e204.nq.gz
    ├── 69fb0099690a3552a145317f742f1fd1e58d8819.nq.gz
    ├── 6a83ddea77ce5bf7fb1926e312c9c1d319831815.nq.gz
    ├── 6aa12493b00314cb5809963d43e490c0467c1c11.nq.gz
    ├── 6b4302e398647a89333ce4cb0c5d5ce37cc48146.nq.gz
    ├── 6bb7e53785c8a9aefcc894f07108bc959b2e0653.nq.gz
    ├── 6be10daa9984e0a92d090e0037d866ca18533749.nq.gz
    ├── 6c1fb0d6682cdeaac9a925226d16e3583b68ec0a.nq.gz
    ├── 6e14739c187e47a2279400da2fa086c2c4898692.nq.gz
    ├── 6e9035d8fdefa1a2aa3a982e664baf6b02757a28.nq.gz
    ├── 6eba7bb5b812b98a0bb92a0e9a384567b0870e97.nq.gz
    ├── 6ecd00003efc16b1a3d7695f0d888ecbb39c7e01.nq.gz
    ├── 6eec7b36c73ae17dcaf7d33d02f4b11e38cc5e9f.nq.gz
    ├── 6f515b1dd3a4fa0cbb6e096f229c29774d921d53.nq.gz
    ├── 6f62121ccc6b9fc72761864f46a909da0d486e8c.nq.gz
    ├── 6ff5c25c5a4b77ac9cce49f44778c1585d19133f.nq.gz
    ├── 700e2e7e81ac8746de9e251fadc62404da0e13ba.nq.gz
    ├── 70da72fa95f16b1366b6797fe593321a5eb022a8.nq.gz
    ├── 71493995e67e24af6ea929eedd06d4f5af068dc1.nq.gz
    ├── 716260893bcfa6d154a3aef651a1afac96904b8e.nq.gz
    ├── 71a75d67bf57b261449e3f29ab99c1597ba2b8d1.nq.gz
    ├── 7251f7970cb7cff4340efae3bb5e0c8048ec472e.nq.gz
    ├── 73a394c3c3496cc4229cfca564ac202c8f39b280.nq.gz
    ├── 73b27f3467088ff118f46dd705066222ef92c669.nq.gz
    ├── 7455e07d21f900c051e36a949df969c0e428891a.nq.gz
    ├── 745ec88d70ebdef06bb953303386572c9ff755c7.nq.gz
    ├── 75e7d88d37054e848f14730439167eb1c0e78f0b.nq.gz
    ├── 768a4766ebecbd6979e3d19e339cf6bf8d724602.nq.gz
    ├── 76eabc0f815ab9cc112ceaa2b36b9ca2d6dd5bde.nq.gz
    ├── 772486e1eb4779aa5d3621ebf95a9f4515471dce.nq.gz
    ├── 7728a57fae711409f31fc02c5f199f0dcdbf8e4b.nq.gz
    ├── 777273600f0daa58c6ff1d0e383bea01d0d425eb.nq.gz
    ├── 77fde1d412db5318d2a1282ba67aca45ce9363e8.nq.gz
    ├── 78d571025d42cc85a858ec4c79d5b5d5cfe4e205.nq.gz
    ├── 792344de029eddca6012adc1debf918b29a63d01.nq.gz
    ├── 797e3500a9f124401c058965ea87225564e2a906.nq.gz
    ├── 7ae930403c9210f95d91cba01b9438f8e51322c1.nq.gz
    ├── 7af3b97aeb72266d0dfb4c54902fef008084d27c.nq.gz
    ├── 7b98355f90a291be81bdd3f2f84adf33133294d0.nq.gz
    ├── 7bcf8ecddc1b7923b89d1787b037db9d3c774a67.nq.gz
    ├── 7cbf6f2a9e296c3b7645896ced5f3847f251ab00.nq.gz
    ├── 7d51678dab39a359bbae4971d81b436a672dee5c.nq.gz
    ├── 7d8d6ae4a93dd5dacbad0686e599520ffba096da.nq.gz
    ├── 7e6c2d44a0ddad984d6313f0631c65aa5ae751ec.nq.gz
    ├── 7f403168ea6c210b08d8cdb4c103d4efae57d050.nq.gz
    └── 7f6333f51480376dee23aaf021e1f45c44277b79.nq.gz

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
*Parsed on 2026-03-20 by [repolex](https://repolex.ai)*
