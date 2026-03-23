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
│   │   ├── 11a7fc6c3b483bac1c39a170d0c1f0284cdf9505.nq.gz
│   │   ├── 27e211402b4780888e4e1d297244ef04908932c1.nq.gz
│   │   ├── 36f3a37bb236356bf3ba45764df389a0e24e3933.nq.gz
│   │   ├── 5d8fc470563fad959ffced897e8320d997993f4d.nq.gz
│   │   ├── 60172de0c37a0d87c341cef3ef13f565ace343e9.nq.gz
│   │   ├── 6947901ef0da402d83d967a01351df3df95e6a00.nq.gz
│   │   ├── 70b1df9b006d5fee134076e4c8b085c0814aa111.nq.gz
│   │   ├── 776178a8f8b9ec995dd8b25a5c12bf2f005027ab.nq.gz
│   │   ├── 79dc7af4ad3d00031ea45968294a5ed3b61d9994.nq.gz
│   │   ├── 7ef6f09f79ec3ce3ba8c3658cfa79457c55952ed.nq.gz
│   │   ├── 7fa11bdbcfee1c65d0bff590337ed4355ebbe44b.nq.gz
│   │   ├── 84d550d21ea59e54b0ae60676e53b9f1ff92fc8e.nq.gz
│   │   ├── 87ea87018da2085180138bd952abcac67961be62.nq.gz
│   │   ├── 8bff294b2aaca16fda5a8928ddda041541fa3fc4.nq.gz
│   │   ├── 993e67a7af2b337125c17f63783c703504497324.nq.gz
│   │   ├── 9f4b571141c15a41860e09570865fd7a041a4e5d.nq.gz
│   │   ├── b9851229f095ea4aa38c470b425c1a5341fe512f.nq.gz
│   │   ├── c49507856005763d9391c7044a7e0a7a5bd1548f.nq.gz
│   │   ├── d0362a1a0c1d765f2e2f0e3db22df7ffe5d4380d.nq.gz
│   │   ├── e2e05210fea0f7db1c0225a3c46a77c58d98e025.nq.gz
│   │   ├── eef24cb9787aa8f4f1707b4889ccd2a71419e3ce.nq.gz
│   │   ├── fa94d4cc1bf1a1619a09268cb06364a17bc6edbb.nq.gz
│   │   └── ff0ede5d79902e1c886e8804f6d9a74b42f031c4.nq.gz
│   ├── lsp
│   │   ├── 069bdd03cafdf3824c81ddf8fddc8c1359bf1ee1.nq.gz
│   │   ├── 077e8fc3f1634b42ef5024814898439d8a8430d4.nq.gz
│   │   ├── 0b8d3e2435ca9cb00a1aab72bf98da334dec2b1c.nq.gz
│   │   ├── 0cb25fae4248263dd14bc84586207bfc7ec776dc.nq.gz
│   │   ├── 11a7fc6c3b483bac1c39a170d0c1f0284cdf9505.nq.gz
│   │   ├── 27e211402b4780888e4e1d297244ef04908932c1.nq.gz
│   │   ├── 36f3a37bb236356bf3ba45764df389a0e24e3933.nq.gz
│   │   ├── 5d8fc470563fad959ffced897e8320d997993f4d.nq.gz
│   │   ├── 60172de0c37a0d87c341cef3ef13f565ace343e9.nq.gz
│   │   ├── 6947901ef0da402d83d967a01351df3df95e6a00.nq.gz
│   │   ├── 70b1df9b006d5fee134076e4c8b085c0814aa111.nq.gz
│   │   ├── 776178a8f8b9ec995dd8b25a5c12bf2f005027ab.nq.gz
│   │   ├── 79dc7af4ad3d00031ea45968294a5ed3b61d9994.nq.gz
│   │   ├── 7ef6f09f79ec3ce3ba8c3658cfa79457c55952ed.nq.gz
│   │   ├── 7fa11bdbcfee1c65d0bff590337ed4355ebbe44b.nq.gz
│   │   ├── 84d550d21ea59e54b0ae60676e53b9f1ff92fc8e.nq.gz
│   │   ├── 87ea87018da2085180138bd952abcac67961be62.nq.gz
│   │   ├── 8bff294b2aaca16fda5a8928ddda041541fa3fc4.nq.gz
│   │   ├── 993e67a7af2b337125c17f63783c703504497324.nq.gz
│   │   ├── 9f4b571141c15a41860e09570865fd7a041a4e5d.nq.gz
│   │   ├── b9851229f095ea4aa38c470b425c1a5341fe512f.nq.gz
│   │   ├── c49507856005763d9391c7044a7e0a7a5bd1548f.nq.gz
│   │   ├── d0362a1a0c1d765f2e2f0e3db22df7ffe5d4380d.nq.gz
│   │   ├── e2e05210fea0f7db1c0225a3c46a77c58d98e025.nq.gz
│   │   ├── eef24cb9787aa8f4f1707b4889ccd2a71419e3ce.nq.gz
│   │   ├── fa94d4cc1bf1a1619a09268cb06364a17bc6edbb.nq.gz
│   │   └── ff0ede5d79902e1c886e8804f6d9a74b42f031c4.nq.gz
│   └── repolex
│       ├── 069bdd03cafdf3824c81ddf8fddc8c1359bf1ee1.nq.gz
│       ├── 077e8fc3f1634b42ef5024814898439d8a8430d4.nq.gz
│       ├── 0b8d3e2435ca9cb00a1aab72bf98da334dec2b1c.nq.gz
│       ├── 0cb25fae4248263dd14bc84586207bfc7ec776dc.nq.gz
│       ├── 11a7fc6c3b483bac1c39a170d0c1f0284cdf9505.nq.gz
│       ├── 27e211402b4780888e4e1d297244ef04908932c1.nq.gz
│       ├── 36f3a37bb236356bf3ba45764df389a0e24e3933.nq.gz
│       ├── 5d8fc470563fad959ffced897e8320d997993f4d.nq.gz
│       ├── 60172de0c37a0d87c341cef3ef13f565ace343e9.nq.gz
│       ├── 6947901ef0da402d83d967a01351df3df95e6a00.nq.gz
│       ├── 70b1df9b006d5fee134076e4c8b085c0814aa111.nq.gz
│       ├── 776178a8f8b9ec995dd8b25a5c12bf2f005027ab.nq.gz
│       ├── 79dc7af4ad3d00031ea45968294a5ed3b61d9994.nq.gz
│       ├── 7ef6f09f79ec3ce3ba8c3658cfa79457c55952ed.nq.gz
│       ├── 7fa11bdbcfee1c65d0bff590337ed4355ebbe44b.nq.gz
│       ├── 84d550d21ea59e54b0ae60676e53b9f1ff92fc8e.nq.gz
│       ├── 87ea87018da2085180138bd952abcac67961be62.nq.gz
│       ├── 8bff294b2aaca16fda5a8928ddda041541fa3fc4.nq.gz
│       ├── 993e67a7af2b337125c17f63783c703504497324.nq.gz
│       ├── 9f4b571141c15a41860e09570865fd7a041a4e5d.nq.gz
│       ├── b9851229f095ea4aa38c470b425c1a5341fe512f.nq.gz
│       ├── c49507856005763d9391c7044a7e0a7a5bd1548f.nq.gz
│       ├── d0362a1a0c1d765f2e2f0e3db22df7ffe5d4380d.nq.gz
│       ├── e2e05210fea0f7db1c0225a3c46a77c58d98e025.nq.gz
│       ├── eef24cb9787aa8f4f1707b4889ccd2a71419e3ce.nq.gz
│       ├── fa94d4cc1bf1a1619a09268cb06364a17bc6edbb.nq.gz
│       └── ff0ede5d79902e1c886e8804f6d9a74b42f031c4.nq.gz
└── blob
    ├── 0010c7a2b4aacd15a99ed0e27e0939ce70a69e77.nq.gz
    ├── 001d83c4a1b6628a523941fad729d0a49b53614d.nq.gz
    ├── 003f6c41dfb9f544ebcfe6628576cedef3a38ba1.nq.gz
    ├── 00669e883ea71ea55e0187e6b5355389dfd5b823.nq.gz
    ├── 0066c8ec4ffecbc1d129519f928636ede8fd02b5.nq.gz
    ├── 008caaabea550d3edf48f19df1da3dc596c2afcb.nq.gz
    ├── 009f9fa8f7d0ac9469cf49896346c62028094d66.nq.gz
    ├── 00b7d24ef6c31276b95d02b4f7d395ed131c5eca.nq.gz
    ├── 00ba2707644d25f5ec1fcb58b393aa1583561365.nq.gz
    ├── 00fdd328f64b99f42a7e23ade168148e5babbbcd.nq.gz
    ├── 012c42b4d80495f0f07ef86ce8bad3598cd23adb.nq.gz
    ├── 0142b09eeb7353165874c9e2591f11a36737a3d3.nq.gz
    ├── 015065863ebc828a20eef7539570f0de29782183.nq.gz
    ├── 01582944dbdd48ea9ce835fb45de8ac279c76600.nq.gz
    ├── 016e0fd3e1c08875e7e7342a3973cc05b52e15c6.nq.gz
    ├── 0178993e375cc2dbae16f0c281325512a6705f30.nq.gz
    ├── 017c5ea0599da5cb83b8a5acc3cbcc0799eef5e2.nq.gz
    ├── 01ab0728e13b780dc5d84b7aaddc998bba9be6f1.nq.gz
    ├── 01c5f696a340d4be6c13cc241ab35ddd336ff409.nq.gz
    ├── 01ce03ce594d7c79534cd432ea99bc31ede65d4d.nq.gz
    ├── 0233938058b226f8bb9bf728ee8c463943ca47db.nq.gz
    ├── 023b2b240f35216ff4d01161f71e3534070e42a7.nq.gz
    ├── 024dce39accbc260abf8c54ae3cfcff3beacbfad.nq.gz
    ├── 0251f087331d7f94b673898d0e54a695cff470b7.nq.gz
    ├── 0280b6068b07ecc3b8df9bd6d1fa108891945bc5.nq.gz
    ├── 02f1b7f0c263d6ccde58cc0d068c7c968ddcc8b7.nq.gz
    ├── 030c546f886fa66b69411e3a5e58f1ab047df9d4.nq.gz
    ├── 03173da00bec6473fb3dc2c2d4151da59a0b2cdc.nq.gz
    ├── 031dd1cda00a00ca984b4b39cf321e0f4fc92996.nq.gz
    ├── 034792b35dc5b92b0dafe0f056c898619349afa1.nq.gz
    ├── 03562c9edbbbe838526aac5cf0dac6cc8d32a121.nq.gz
    ├── 03918b0e1fd3d03c993dc2be72ba9bfdb2124256.nq.gz
    ├── 039dfbef0152026d97ec240f8821a4a6ff7f0a3e.nq.gz
    ├── 03b79065e25ceb8ab2ab71b84506142c015add86.nq.gz
    ├── 03d518aab9a9b5d961db9a23710606ebaabe7a22.nq.gz
    ├── 04098c8c607fbfdfbf5c7b87a279a4279f514702.nq.gz
    ├── 0414d43423f96d75e693d2e126e8024aabd7e3b9.nq.gz
    ├── 041a684c626895183df81c145aa09c7e9502d2bd.nq.gz
    ├── 0459ed8f71191041fa1610375078d906a4952034.nq.gz
    ├── 046412d3ae41f215d6c636216f94a9cfbb89e41c.nq.gz
    ├── 048c38c1f74acdb98d835b1a21be5280b49466bd.nq.gz
    ├── 048c69a7ec0af805dafa2459a449f4860a916cf8.nq.gz
    ├── 04a96c495c93d1e5280ebce387ee9f02a4d03685.nq.gz
    ├── 04bcdc71004a7a44fcebf0b073108e5abc0cbc9d.nq.gz
    ├── 05037d81314d7e46a6dba20a315374558eb86b4f.nq.gz
    ├── 054cd9eac0989d6cf3af33745102af959acf0c34.nq.gz
    ├── 0579d4420d0f08f36c7f90217411cc8ab4cb4dfd.nq.gz
    ├── 057e28568e798058a85f08e883e3f7fcdee8ba4c.nq.gz
    ├── 0585fa516f1433994ce94a907fe29b8136062d47.nq.gz
    ├── 058b5e0a49bc029b6e5a87d58df13c1e2affc06e.nq.gz
    ├── 058e9d0609623f7f67ca83150a07514b82d6c7db.nq.gz
    ├── 059a8a95d1b2b54254d86f2ed1461042f9b23743.nq.gz
    ├── 05ac69d3f2babc07ccd3facf4e060174175a1ebc.nq.gz
    ├── 061a715104cc7c759583158f3e9a2a8bf571d160.nq.gz
    ├── 061cc093676b70a89b0202931d350c690b2e5648.nq.gz
    ├── 063fa1dd80bbec610eb0bfc6495a05e6319685f2.nq.gz
    ├── 064689898309d01c04754a9a7568d7f351bcbf52.nq.gz
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
    ├── 074943ec6383448fcc2452f790dae6b8de34bd96.nq.gz
    ├── 0775a107fdb8b2bd0604fb79716712edebf69dcf.nq.gz
    ├── 07797937e939e360d9c62a769ea9578fbde75cbe.nq.gz
    ├── 077f21cd2753eebf69b622859b0e8e1de6e285b2.nq.gz
    ├── 07a755872063ee474eb18aee773a1cf8804231a4.nq.gz
    ├── 07ab6a5a3a00b5febdd1f8e9a4031d49e5261619.nq.gz
    ├── 07bba9407de6e424c7a4eef2ad54e4c74c2c0d40.nq.gz
    ├── 07c0461429f72bbe463fa37c23a3dfcded16c5ec.nq.gz
    ├── 07cc84a559e8854694d0aa94f91884a7109ace05.nq.gz
    ├── 07ea83075330832c9f2cebb73b17b8d482bb83f4.nq.gz
    ├── 07fceb31125a2b66468fdccfcba3a7c82c95637d.nq.gz
    ├── 0811d9121c81b57a5f7f38177b3ab28ef53acc98.nq.gz
    ├── 08206569f55b6af9ea4ecb50903b379356f1affd.nq.gz
    ├── 085bff9a345c3688fe421ecfcbde3d5a81f732ed.nq.gz
    ├── 085ce8f1dc284c2c4779d786d8143b44ba6d9223.nq.gz
    ├── 088ffa25413a36a0b6325e5c8aeba743707cba47.nq.gz
    ├── 093a3ebe083bd19d16f25b64540822c110e57735.nq.gz
    ├── 093beb41029539ad2022481255d9cf1405d8d8f3.nq.gz
    ├── 093d3a202a97268a5774fbc484e44e021f646103.nq.gz
    ├── 095bdc779f385acbc4c0731cfd0a357c6253a003.nq.gz
    ├── 097cb5ce0aec47edb69710a9fe5fdfa38bf5883f.nq.gz
    ├── 09a2b8d927a95760a611b2f1a903178ac560637c.nq.gz
    ├── 09a57ce7459ed14cad0e2c2a81623a2ef9a80922.nq.gz
    ├── 09b00d7a50a225019959819673d195c36c032b38.nq.gz
    ├── 09e5274d4bfa536490913c0da4c6eba40915cc10.nq.gz
    ├── 0a3bd1cba1983ace82d5e867b9694e69496e9bb1.nq.gz
    ├── 0a46be780a84532fa3b0d465b59e345412b08044.nq.gz
    ├── 0a6b3516b0e57bee0175751d871eaf799c7cf6ef.nq.gz
    ├── 0a6c6858175f43810b9411a6ea97f520512487b9.nq.gz
    ├── 0a70e7a9749ee3c977d113949b6eb1f1344b511f.nq.gz
    ├── 0a8179f88f034a63a3dde77cea9518258019b65a.nq.gz
    ├── 0a9553b854900b5d741a0efc2a7dfc632fea0f16.nq.gz
    ├── 0aa78fcd3c71488c116278720d16d9cf03f6ac7c.nq.gz
    ├── 0ad11630113023f9309217203ca9c02a089667a1.nq.gz
    ├── 0ae84d61e3bbafd070580282c57bdf0e14f432e4.nq.gz
    ├── 0b10ae71e1698da0199f9d35ea0b75660620710c.nq.gz
    ├── 0b66ca227b1283bd4c602a146dca7694280ec418.nq.gz
    ├── 0bbd47fada46fb6c33306e4ae4774332c46170fa.nq.gz
    ├── 0bc3b33378ce3e4946257361b59f08376e5c0d54.nq.gz
    ├── 0bcfcb6e8ff5851e9de1e9705f15b82abb77adc6.nq.gz
    ├── 0beb1ef1d847da3d3e53d2adb1ca3c67d3d1263e.nq.gz
    ├── 0bf619e3b8e7739872e3355cba7af4c735ab38ad.nq.gz
    ├── 0bff66ddb005817e277ad600580ff325aba063ef.nq.gz
    ├── 0c144c37f02dbe15a873b395176026ccdc0a7722.nq.gz
    ├── 0c28450e5e1e1abc21913693a6d1e6f6be9b248b.nq.gz
    ├── 0c2930b1206408c36631e54921f8c16df7ac683c.nq.gz
    ├── 0c37928a550a6bd34b09cf59e0411432ee2d77a8.nq.gz
    ├── 0c4e043b59dbc4eef0245cd948feb7930df1935b.nq.gz
    ├── 0c70df18405eab83762d7a77df516aafadf19a65.nq.gz
    ├── 0d012a0af7e787391e6f5d8e383c34929af84146.nq.gz
    └── 0d29e393b08bdbdb61959e368fd9b094c967de84.nq.gz

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
