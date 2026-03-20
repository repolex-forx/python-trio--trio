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
    ├── 048c38c1f74acdb98d835b1a21be5280b49466bd.nq.gz
    ├── 06adc5da97706967939e5eb0a0c8f1b0b801b0bf.nq.gz
    ├── 07ea83075330832c9f2cebb73b17b8d482bb83f4.nq.gz
    ├── 093a3ebe083bd19d16f25b64540822c110e57735.nq.gz
    ├── 09a2b8d927a95760a611b2f1a903178ac560637c.nq.gz
    ├── 09b00d7a50a225019959819673d195c36c032b38.nq.gz
    ├── 0bcfcb6e8ff5851e9de1e9705f15b82abb77adc6.nq.gz
    ├── 0c70df18405eab83762d7a77df516aafadf19a65.nq.gz
    ├── 0ea4c2d48a2bcb4a8f7ee1629b65fd5f493a9a16.nq.gz
    ├── 0ebad58a80606857a714508bef92ee90ff09792c.nq.gz
    ├── 0edc71db1bce7cf779c855b97addb719cb607c63.nq.gz
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
    ├── 1984d8591e7800d2cde6cb0d0fd721eb4b2e89f1.nq.gz
    ├── 1ddbfc2dcfb0394e4f5ccd56ff260b344ebd60c6.nq.gz
    ├── 1df9a92e740642f3b0cd9e3ab98f83a493610429.nq.gz
    ├── 1e8597ba42cb4305e9b05d4a1710dfff7240d08d.nq.gz
    ├── 1ec20bf8a49972877dd2a5651dd8f0f28680c656.nq.gz
    ├── 2047e9564462c76bdb5cb0f570ed62e1f689eecf.nq.gz
    ├── 209a766cb29844567e67cbd53c4d1fb155e56626.nq.gz
    ├── 212c9eef00e0f07665ad9e01012d0ae9bb273e55.nq.gz
    ├── 2477596f726247eab40054e67807e67fcdc543e7.nq.gz
    ├── 25788617d55f87923ba754f4f91b4deba392e729.nq.gz
    ├── 25e0fd2baf1030a20e8c724b4d21fcfa5285ce01.nq.gz
    ├── 265ba191d0044721096bee0bb7b518312e4938b1.nq.gz
    ├── 28fac173ffddd643cc90961916e966c26da91a14.nq.gz
    ├── 290365d8b02004a9b59a4953585ab5a396e484d6.nq.gz
    ├── 299a401df53eb4321e1980e45e5e0aafdfb082c9.nq.gz
    ├── 29c17715abd2f55bd1f740542dc619a4bbfc0a81.nq.gz
    ├── 29ece9d9b6a1a938b41176c59a4bd7b3b214a479.nq.gz
    ├── 2a755acba31096357c1f9cd18c1e71a369799539.nq.gz
    ├── 2a79b3bec8f37d41285a91463b01384308117896.nq.gz
    ├── 2b569906aa19737b568802d045b8409e3d036188.nq.gz
    ├── 2be0d6ab98eb481fb797f4f61baa6b2dbc465dc6.nq.gz
    ├── 2c19bd81ad5163d640da8b4679194e5fd2f4fc47.nq.gz
    ├── 2d25ca401c007dbf7af6089b093da50018d61be7.nq.gz
    ├── 2e2ffcc320ec3fa447b26580e29a2358fa3317ad.nq.gz
    ├── 30a9fff4da1a9bed9c9015a8ed51f7f518bf21ba.nq.gz
    ├── 31d69ab77dfe5d466de1e8c62ea9df1eb2974f2c.nq.gz
    ├── 332b1a8dbf49a6a25732d09eb8bfce6f99d8f8fd.nq.gz
    ├── 35a5619e4264c005da88c3d76f81f85811131b91.nq.gz
    ├── 35ae017f5970f721e5a82b0152117887a40a01c2.nq.gz
    ├── 361e062ab0e88ed75fd9e4d93d51746119a8b6c0.nq.gz
    ├── 37e01b7d3b904e54e4aba65504d93ceac199f6e0.nq.gz
    ├── 38a1ffe862134d73f449e5cea8567b8abcb3b5e1.nq.gz
    ├── 39581e1ac6d3b130d8a89d8e52d65421b9c1fb32.nq.gz
    ├── 39885275fff31995d19147db0df6e5def5925322.nq.gz
    ├── 39ffeb5a4bb2b2548643b735ad9bf4e32c41ce03.nq.gz
    ├── 3a7dbe486f4bcc3b7b70070c8e093c29e5430ec5.nq.gz
    ├── 3a83e454e07efc838132a1c37285c7b8186ab2c9.nq.gz
    ├── 3ca395b7d5353b8516d2a25990b2dd68c7dc569c.nq.gz
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
    ├── 45d8b8c5c5797771226e8e3f309f919b2a897c12.nq.gz
    ├── 45f21d389ae8d6f15662d6ff796adfea373bad80.nq.gz
    ├── 47296b7678381b86bfe3fbce17a7fa4db4a90a85.nq.gz
    ├── 4b1de91b36452f88e39dd5986f36dffe74c2829b.nq.gz
    ├── 4b9911590b53548a17dd14526280276e4fddde79.nq.gz
    ├── 4c4ac6987920e8ef53c8e820cfaca68008c4e6f1.nq.gz
    ├── 4cd148217a36b0f6db8bc3f5f8f232ebb0878f05.nq.gz
    ├── 4e3673167280f33dfca2114823dfde7a4891ddbf.nq.gz
    ├── 4e56fb80957455eea5811c72742383d5ac253689.nq.gz
    ├── 4fd0bb58f2bc803ce65a4248f21fcfe42cd13b07.nq.gz
    ├── 5022302759b65bbaf1217b85257aa3313ab24522.nq.gz
    ├── 50ac67f20afc069557c09f725a19f1de40e12300.nq.gz
    ├── 514636a1b421b138ce6341bd7009baff9586fc93.nq.gz
    ├── 535d62d3b2c3087b05b989d762fe530330ec3e32.nq.gz
    ├── 551e65045651dfb76d1d76ad837297578010027a.nq.gz
    ├── 555e03c6e87b38372bf775c631daea83ab8beb1f.nq.gz
    ├── 57a6b8166d1c3e1548b075fa9b06f867f1acc8cb.nq.gz
    ├── 581389c4546bbe2e4e19a3b97cd2e053b4d09391.nq.gz
    ├── 5871ed8eef2f90304e1f64c12ba17e1915250724.nq.gz
    ├── 5992c4f73e49c5d2197dc100a93a6fbf1724f08b.nq.gz
    ├── 59a447d32a85cd8cc1e82509aa1a1940634a20b9.nq.gz
    ├── 59bec8618bd662f39410793bc5728ed75f16004d.nq.gz
    ├── 59e70dd147d74efa580b4d5be7ee42ba6ac17f3d.nq.gz
    ├── 5bd950f0ab05a0316a760e93bc26a09de1c1a319.nq.gz
    ├── 5c333bbcb164a60cbc1cdf3a1822d5020da1d539.nq.gz
    ├── 5dd61bdd73b62bc2463d3aa09275a9414a1de688.nq.gz
    ├── 5eb4ec8ef47b6a0e1b423460481b4e765c710cbe.nq.gz
    ├── 601aae5fdeb8d30b4678aa432eca8c4a47ce7dce.nq.gz
    ├── 63ac754bcc5739a4b530aba74889e6436054d113.nq.gz
    ├── 652960ed14f7d4ddfaaed5d23223d17383e740f2.nq.gz
    ├── 67ce82b176c7ae57108231f7c937de1f8397fe4b.nq.gz
    ├── 6852d63200e151dd4b99ba81ff8f6c9bf9928ab0.nq.gz
    ├── 68bd632be83e8ee44f8ed49cf5738e644cbc39f9.nq.gz
    ├── 68f47622217ab6e3f8549c2b176bf4722628e204.nq.gz
    ├── 69fb0099690a3552a145317f742f1fd1e58d8819.nq.gz
    ├── 6a83ddea77ce5bf7fb1926e312c9c1d319831815.nq.gz
    ├── 6b4302e398647a89333ce4cb0c5d5ce37cc48146.nq.gz
    ├── 6bb7e53785c8a9aefcc894f07108bc959b2e0653.nq.gz
    ├── 6e14739c187e47a2279400da2fa086c2c4898692.nq.gz
    ├── 6f515b1dd3a4fa0cbb6e096f229c29774d921d53.nq.gz
    ├── 6f62121ccc6b9fc72761864f46a909da0d486e8c.nq.gz
    ├── 6ff5c25c5a4b77ac9cce49f44778c1585d19133f.nq.gz
    ├── 70da72fa95f16b1366b6797fe593321a5eb022a8.nq.gz
    ├── 71493995e67e24af6ea929eedd06d4f5af068dc1.nq.gz
    ├── 7251f7970cb7cff4340efae3bb5e0c8048ec472e.nq.gz
    ├── 73a394c3c3496cc4229cfca564ac202c8f39b280.nq.gz
    ├── 745ec88d70ebdef06bb953303386572c9ff755c7.nq.gz
    ├── 768a4766ebecbd6979e3d19e339cf6bf8d724602.nq.gz
    ├── 76eabc0f815ab9cc112ceaa2b36b9ca2d6dd5bde.nq.gz
    ├── 7728a57fae711409f31fc02c5f199f0dcdbf8e4b.nq.gz
    ├── 777273600f0daa58c6ff1d0e383bea01d0d425eb.nq.gz
    ├── 77fde1d412db5318d2a1282ba67aca45ce9363e8.nq.gz
    ├── 78d571025d42cc85a858ec4c79d5b5d5cfe4e205.nq.gz
    ├── 797e3500a9f124401c058965ea87225564e2a906.nq.gz
    ├── 7af3b97aeb72266d0dfb4c54902fef008084d27c.nq.gz
    ├── 7b98355f90a291be81bdd3f2f84adf33133294d0.nq.gz
    ├── 7cbf6f2a9e296c3b7645896ced5f3847f251ab00.nq.gz
    ├── 7d51678dab39a359bbae4971d81b436a672dee5c.nq.gz
    ├── 7e6c2d44a0ddad984d6313f0631c65aa5ae751ec.nq.gz
    ├── 7f403168ea6c210b08d8cdb4c103d4efae57d050.nq.gz
    ├── 7f6333f51480376dee23aaf021e1f45c44277b79.nq.gz
    ├── 801c34ce461182ec70980526b940ddd82cbe331f.nq.gz
    ├── 804069f10805f3866f9f52e807e453a07e51d0e8.nq.gz
    ├── 8054c371752ca7e90f38b6b192888701f4d7cbc4.nq.gz
    ├── 81d875be6ac8e67a47989d76e4343489168ab2b5.nq.gz
    ├── 824d667a572605985967aaab34bbff7ba5579d49.nq.gz
    ├── 837b556fed67c54483a2211e30e3d3d7f8b32d31.nq.gz
    ├── 838a68b507d2bfc1fe30121ae941a47ab116dddf.nq.gz
    ├── 89123cfc54fd18ef90df8a405e9885065f184e28.nq.gz
    ├── 8aad4547e638689022aa5bd37f9f129fd67dbf9b.nq.gz
    ├── 8b0a7d74267c2bcf54f5ca8ca82db3ec10d40203.nq.gz
    ├── 8b6752a5aea4ac892b74e5d4261089dbd98cccaf.nq.gz
    ├── 8bf782657460f93a83f92a745385e6ba37e50c8b.nq.gz
    ├── 8cdb6b9507ad4cdee6eba383ce50ea29584aaf2b.nq.gz
    ├── 8d139b1f75c28a25a9570284eaf2f06e2390c92e.nq.gz
    ├── 8f7fc5611869d45674adeea2b38ebdfb43bf3aa3.nq.gz
    ├── 9010898bdaa0caa4191cd3d2c139c95a18c291d4.nq.gz
    ├── 90f8ebd0774bf852c0ade8483feb8c3f5a35b508.nq.gz
    ├── 910def397c185f33c4f6f26b9a24f53d3de5c805.nq.gz
    ├── 91c10798dc85885307e66af0e0572df4ea1f790c.nq.gz
    ├── 9215084955e04bdd155540ac1d498b4efdbe6703.nq.gz
    ├── 9360d4c5751225358fd2a3143de45a4adb036970.nq.gz
    ├── 942672898e87aa92136b64e2f23e53c6dd606a46.nq.gz
    ├── 95681622c11a9bee6abff1f08e312961db0da07d.nq.gz
    ├── 958624a6f40850a8b9bbf5e9ab5403b8999a69ae.nq.gz
    ├── 958be8675c9f992b886ebdb9246de6275f508844.nq.gz
    ├── 95e4a96b5004c6b577d57ebdb0da42da8933d139.nq.gz
    ├── 960bc4ebfaed10ed9174bf3ab7ee574cba3dfc71.nq.gz
    ├── 96c7be800d1bd1946411655a91dd7ae66a7fedaf.nq.gz
    ├── 9790cd61f99989bde3ff8b85d3d2e5b79473e3e7.nq.gz
    ├── 989fffec77ae004aa3957ef3c4e6b5478a9407dd.nq.gz
    ├── 998fec9bd27967e4099d47de16ea81c9b84ab6c7.nq.gz
    ├── 9af1b7222d74719f9a97a58e401c6ab26993347a.nq.gz
    ├── 9b2f86f7528d69f16e88b97ab8f7ee003705c0ed.nq.gz
    ├── 9bf34001b2c0ff403f4113e5b6e8cd4f513b095f.nq.gz
    ├── 9c58d8e65bc12bf7a3f0f32aa86df9543e8798b7.nq.gz
    ├── 9e080e8e9183c1e7d5c1978de86605ea3382f054.nq.gz
    ├── 9f316a3ed0a719709f2e885ccf7381f5476ce0c4.nq.gz
    ├── 9f893590bd49f8f23e9273cc8f9b58cb6c072759.nq.gz
    ├── a0c1b773f9c5611a9ed23f45303d724e95da53ad.nq.gz
    ├── a0fc80589d34f0da60a8f50bd11cc59d33badc15.nq.gz
    ├── a1ace313b166fffb8d91d83920f1213583bb8b76.nq.gz
    ├── a1f6cb598dd0b409ebf27eeb214b058e9c9945aa.nq.gz
    ├── a2393198e82290f95d819d9c59d91c962f5a58f3.nq.gz
    ├── a286f5f8cc172d32d9ac081cc24686c9a0e67c6c.nq.gz
    ├── a2873f80d85456767a6c4c2ad09c052948be9a8d.nq.gz
    ├── a316cb933d17848f70e37199ecf44c958e2dc915.nq.gz
    ├── a3e7044fe785adc5186f30d94ee2793517d43543.nq.gz
    ├── a719d6b8079625e85227e3b2d42609011b26e48f.nq.gz
    ├── a7a840509066f5afa452bf2949f58ab884236249.nq.gz
    ├── a93e159b42de5330c51b0c01b75dbca4894205b2.nq.gz
    ├── aadd7668804db5db5f0517bfbd06e2f0f8d86b0a.nq.gz
    ├── abade0ea8dd18b03a43cf4edb706de90d40ef5e9.nq.gz
    ├── abaf9f7ee06339a4fed2c3f781af4967f7a0abc9.nq.gz
    ├── ac712aa1efd8a5f02286fe3da29033e6d1b78cb1.nq.gz
    ├── acd4d726afcf32a72d9ba9c42c46330ad28b494f.nq.gz
    ├── ad89ea780ff86fdced9b2fd16f705255fe67cde9.nq.gz
    ├── adade7ff30e31a8cdd31c9ab356e6e68aaa6f525.nq.gz
    ├── b0b14552d8e7eaac901507f4e7cbc716ebf62d34.nq.gz
    ├── b0fb59fce5b1acd5bb97733fcf03d1765de7dc36.nq.gz
    ├── b115d3b270f891e6289652f36217c6f49298cce8.nq.gz
    └── b2eb133e008435342f04ad1c220c948c513f9766.nq.gz

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
