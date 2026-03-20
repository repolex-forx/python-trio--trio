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
├── blob
│   ├── 0066c8ec4ffecbc1d129519f928636ede8fd02b5.nq.gz
│   ├── 00fdd328f64b99f42a7e23ade168148e5babbbcd.nq.gz
│   ├── 048c38c1f74acdb98d835b1a21be5280b49466bd.nq.gz
│   ├── 093a3ebe083bd19d16f25b64540822c110e57735.nq.gz
│   ├── 09b00d7a50a225019959819673d195c36c032b38.nq.gz
│   ├── 0c70df18405eab83762d7a77df516aafadf19a65.nq.gz
│   ├── 0ea4c2d48a2bcb4a8f7ee1629b65fd5f493a9a16.nq.gz
│   ├── 0edc71db1bce7cf779c855b97addb719cb607c63.nq.gz
│   ├── 0fdb3bf9ceed1b91ecd9f704bc248a443e41853e.nq.gz
│   ├── 1051aeb2191d66affb4d183e58b1fa5d1e642099.nq.gz
│   ├── 115413a78d9b7a41ecedfae40c8c2bc25ebf5651.nq.gz
│   ├── 11fc66ade6a339b501e714a23cd2f5ce5872abed.nq.gz
│   ├── 121513b20e80d517c58bc5e6fb5c7f2255ca441a.nq.gz
│   ├── 149260fc5dae7da074134897da1414599e0eebe2.nq.gz
│   ├── 1984d8591e7800d2cde6cb0d0fd721eb4b2e89f1.nq.gz
│   ├── 1df9a92e740642f3b0cd9e3ab98f83a493610429.nq.gz
│   ├── 2047e9564462c76bdb5cb0f570ed62e1f689eecf.nq.gz
│   ├── 209a766cb29844567e67cbd53c4d1fb155e56626.nq.gz
│   ├── 25e0fd2baf1030a20e8c724b4d21fcfa5285ce01.nq.gz
│   ├── 290365d8b02004a9b59a4953585ab5a396e484d6.nq.gz
│   ├── 29c17715abd2f55bd1f740542dc619a4bbfc0a81.nq.gz
│   ├── 2a79b3bec8f37d41285a91463b01384308117896.nq.gz
│   ├── 2b569906aa19737b568802d045b8409e3d036188.nq.gz
│   ├── 2be0d6ab98eb481fb797f4f61baa6b2dbc465dc6.nq.gz
│   ├── 2e2ffcc320ec3fa447b26580e29a2358fa3317ad.nq.gz
│   ├── 35ae017f5970f721e5a82b0152117887a40a01c2.nq.gz
│   ├── 37e01b7d3b904e54e4aba65504d93ceac199f6e0.nq.gz
│   ├── 39885275fff31995d19147db0df6e5def5925322.nq.gz
│   ├── 3a7dbe486f4bcc3b7b70070c8e093c29e5430ec5.nq.gz
│   ├── 3e496126450c016670b855f0ba5a47f66f9df473.nq.gz
│   ├── 41a6025c3778ab71c64c027de167a46a8b35bee6.nq.gz
│   ├── 4217fdc7e7e55218871e52d7d15054484c149ef5.nq.gz
│   ├── 45f21d389ae8d6f15662d6ff796adfea373bad80.nq.gz
│   ├── 4b9911590b53548a17dd14526280276e4fddde79.nq.gz
│   ├── 4cd148217a36b0f6db8bc3f5f8f232ebb0878f05.nq.gz
│   ├── 4e56fb80957455eea5811c72742383d5ac253689.nq.gz
│   ├── 4fd0bb58f2bc803ce65a4248f21fcfe42cd13b07.nq.gz
│   ├── 5022302759b65bbaf1217b85257aa3313ab24522.nq.gz
│   ├── 57a6b8166d1c3e1548b075fa9b06f867f1acc8cb.nq.gz
│   ├── 581389c4546bbe2e4e19a3b97cd2e053b4d09391.nq.gz
│   ├── 59bec8618bd662f39410793bc5728ed75f16004d.nq.gz
│   ├── 601aae5fdeb8d30b4678aa432eca8c4a47ce7dce.nq.gz
│   ├── 652960ed14f7d4ddfaaed5d23223d17383e740f2.nq.gz
│   ├── 67ce82b176c7ae57108231f7c937de1f8397fe4b.nq.gz
│   ├── 6852d63200e151dd4b99ba81ff8f6c9bf9928ab0.nq.gz
│   ├── 68bd632be83e8ee44f8ed49cf5738e644cbc39f9.nq.gz
│   ├── 69fb0099690a3552a145317f742f1fd1e58d8819.nq.gz
│   ├── 6bb7e53785c8a9aefcc894f07108bc959b2e0653.nq.gz
│   ├── 6e14739c187e47a2279400da2fa086c2c4898692.nq.gz
│   ├── 6f515b1dd3a4fa0cbb6e096f229c29774d921d53.nq.gz
│   ├── 6ff5c25c5a4b77ac9cce49f44778c1585d19133f.nq.gz
│   ├── 70da72fa95f16b1366b6797fe593321a5eb022a8.nq.gz
│   ├── 71493995e67e24af6ea929eedd06d4f5af068dc1.nq.gz
│   ├── 78d571025d42cc85a858ec4c79d5b5d5cfe4e205.nq.gz
│   ├── 7cbf6f2a9e296c3b7645896ced5f3847f251ab00.nq.gz
│   ├── 804069f10805f3866f9f52e807e453a07e51d0e8.nq.gz
│   ├── 8054c371752ca7e90f38b6b192888701f4d7cbc4.nq.gz
│   ├── 838a68b507d2bfc1fe30121ae941a47ab116dddf.nq.gz
│   ├── 89123cfc54fd18ef90df8a405e9885065f184e28.nq.gz
│   ├── 8bf782657460f93a83f92a745385e6ba37e50c8b.nq.gz
│   ├── 8cdb6b9507ad4cdee6eba383ce50ea29584aaf2b.nq.gz
│   ├── 96c7be800d1bd1946411655a91dd7ae66a7fedaf.nq.gz
│   ├── 989fffec77ae004aa3957ef3c4e6b5478a9407dd.nq.gz
│   ├── a1ace313b166fffb8d91d83920f1213583bb8b76.nq.gz
│   ├── a1f6cb598dd0b409ebf27eeb214b058e9c9945aa.nq.gz
│   ├── a2393198e82290f95d819d9c59d91c962f5a58f3.nq.gz
│   ├── a286f5f8cc172d32d9ac081cc24686c9a0e67c6c.nq.gz
│   ├── a7a840509066f5afa452bf2949f58ab884236249.nq.gz
│   ├── ad89ea780ff86fdced9b2fd16f705255fe67cde9.nq.gz
│   ├── adade7ff30e31a8cdd31c9ab356e6e68aaa6f525.nq.gz
│   ├── b0fb59fce5b1acd5bb97733fcf03d1765de7dc36.nq.gz
│   ├── b8bb97185926d7daed314609753173945ed4ff1a.nq.gz
│   ├── bb158cbe6ec0ee04775ad73a5e7357eff0bf222f.nq.gz
│   ├── c3aff01f9ddb1a8dd384e24981e8f18c72bcfad3.nq.gz
│   ├── c4e2a5974d0ace6fd2539cd4715c7ad6ed98e4b9.nq.gz
│   ├── c578bd61946d914193061fae0ba24850acb76b9a.nq.gz
│   ├── d12e93127f16b1df5b65f81a1077b5f1641e0fb1.nq.gz
│   ├── d20342536b588e5266c89d94f19a0e412cb391ca.nq.gz
│   ├── d43ae6ee1c321c8aa14c9dba833950f22925a356.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d91e809399cd93ab0d979ec27a37e239f64371e9.nq.gz
│   ├── d92b5936e20f912f714f13a1cad3a3672b178f02.nq.gz
│   ├── dc41155b31d44592b048f874fb7875e109369b50.nq.gz
│   ├── dd031946755ce1cae3920900f4711eb7ce21a91b.nq.gz
│   ├── dd9eb9fdbeaf4165f610c80ac87a442f894ee4f1.nq.gz
│   ├── e20ec0eb30b685303f855d85fb3b1cec48df58d0.nq.gz
│   ├── e2b61ecf35f993fbead74daaac58435a98417a92.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8e1db4154de03ff6e0f10acad7ba891212d7b3a.nq.gz
│   ├── ec39431c0f6870c8dc1d7d296c299e5a79863e52.nq.gz
│   ├── ed3a80a5dc9a44c21586745c4daa5ef5cddddf5b.nq.gz
│   ├── f001374a6e8a9063758646fb4076c8d735f2d560.nq.gz
│   ├── f2af97c82904072d8307a2bdab4da673d0f68828.nq.gz
│   ├── f494bf4439b0a0326410046192954a3c18c12b9c.nq.gz
│   ├── f93ae0f4b76057a8ed85750ac197c8e03aef16fa.nq.gz
│   └── fc122d55ee1702db7170a50b93feb97b5057f2a9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 776178a8f8b9ec995dd8b25a5c12bf2f005027ab.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

8 directories, 102 files
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
