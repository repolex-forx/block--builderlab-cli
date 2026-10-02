# Repolex Knowledge Graph of block/builderlab-cli

RDF knowledge graph data for [block/builderlab-cli](https://github.com/block/builderlab-cli), parsed by [repolex](https://repolex.ai).

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
rlex download block/builderlab-cli
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 78f9ea0044f7265b5e72aacd822215f6621fad7b
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 78f9ea0044f7265b5e72aacd822215f6621fad7b.nq.gz
│   └── repolex
│       └── 78f9ea0044f7265b5e72aacd822215f6621fad7b
│           └── chunk-001.nq.gz
├── blob
│   ├── 00566a0836cfe17ab01432ca9bf45b3ab72815ea.nq.gz
│   ├── 014155d1536bc84f74713a919db0de290917a0ac.nq.gz
│   ├── 0367d2331a2cbfb3dadb43da08affe106a235c28.nq.gz
│   ├── 081c0bdba116d400d1bb2751a1e4a5854ff61e68.nq.gz
│   ├── 09f4648f19428e49350f0d3b56156ba533b31931.nq.gz
│   ├── 0e8eeadae8b61d92b110fb2325ee2e8934f33869.nq.gz
│   ├── 101eb97d48d6b3803ac66dbaed542749c1b28b29.nq.gz
│   ├── 10f6d1f628e8c59380ad148696afed7b35e3b12d.nq.gz
│   ├── 1134d824ac69dd9e3f1b4bbe1278996a2517d2b1.nq.gz
│   ├── 1284b794e42874c1cad78e651c358307fc32ef95.nq.gz
│   ├── 17658ec4f54a6a8138b9235328100aab3f1c723f.nq.gz
│   ├── 19805ba182f25cb9edb479c020ef5ff4efa18817.nq.gz
│   ├── 19cae2a778ca0ffeca16fdc8c021118321fcb8f4.nq.gz
│   ├── 1a37c281bb510919619338100b0667f49a479382.nq.gz
│   ├── 2240a3d2ba70fc9de94938f596958cf2ffc08518.nq.gz
│   ├── 279ecd86f0857d9ebd51b0c883840b25240ad205.nq.gz
│   ├── 2859d31872049be5b8004b5c265052b07ea2d28a.nq.gz
│   ├── 2f44ec26709fb7a3a3b0fea4d4e50970b1d83c22.nq.gz
│   ├── 30c7a2b25a24c7607db8b7c241ac401ae9d5d9f1.nq.gz
│   ├── 31d999edba9cb39c8687ed438d403078dea3c2cb.nq.gz
│   ├── 3219e0dda0981582bf650bf1e1c92e2df839f1ac.nq.gz
│   ├── 3781d506614a0f10297b60655579ff49f1611cac.nq.gz
│   ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
│   ├── 38eb0599b08e56d4fbe6175a7fe733d18a36588a.nq.gz
│   ├── 3abfc535cf2baff8121a9f9534869fd74c7543ec.nq.gz
│   ├── 3cc4d1197c7b5269277476e2f1d1c68f7fec266d.nq.gz
│   ├── 3ecd2bf284babb4ebc1f0939c3e7039d0a9a6abb.nq.gz
│   ├── 417edd8fa19db17edfdc1037b6d600ddb7ab3aaa.nq.gz
│   ├── 457b485c81c415e7aec979b74ff66ebc564e9c43.nq.gz
│   ├── 47a730be6ead5247bf89184dea5ea2cba0af466a.nq.gz
│   ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
│   ├── 49a169c532a3d577a6900452b3b3b022d2ca5d07.nq.gz
│   ├── 49e2dd593908c47b06f4b6236d3f7e0015b42c3c.nq.gz
│   ├── 4b061e8a9b857c0450afa3874052df87cb80f870.nq.gz
│   ├── 515c80e10f0a4a3f1a1f4377889736b730b1b97f.nq.gz
│   ├── 56343494d799fcc82c06f58185cbe04ccdf47214.nq.gz
│   ├── 587f1d129295ba1f7ab04cfe520915c9f900b3a7.nq.gz
│   ├── 5c13711320c9f4d744b5559eb85f6fc452a4dd44.nq.gz
│   ├── 5e87b1682ae7deaeb1682dc60eef92a8f7fd5e41.nq.gz
│   ├── 628f16cebde88c27717f87a09365e6b096070985.nq.gz
│   ├── 643274f6806bf4ee410f816eaab36c6513def07b.nq.gz
│   ├── 65056a7f9697011f96471e03ce2c54ee1b01d349.nq.gz
│   ├── 6b0dd37579734bb1153a9d50e8c37b2469e08d29.nq.gz
│   ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
│   ├── 6bd128fb3c89a7c248918c29c2a431ea62d7433a.nq.gz
│   ├── 6c1aa54e4b69684b490dd12c222f8fe225432001.nq.gz
│   ├── 6e6dff205e3faec7deba8f9dd4068a48bdd6af46.nq.gz
│   ├── 739096ee51da858560020bc065af29f344454270.nq.gz
│   ├── 7430a1d3448d18df879e7c54616ed26c16f3fffa.nq.gz
│   ├── 780dab0f0e1bf8434a79d27caddab30978c421e2.nq.gz
│   ├── 7901ba7bc7b49987630e29ef9eb60323c520f1d0.nq.gz
│   ├── 7b4e5b14dcb197bade931010098609eaab223ac6.nq.gz
│   ├── 816066f4755caecbea428ebfe33fecd477e0bb7e.nq.gz
│   ├── 81a220f59fd70d585984cf67953857d53704e68f.nq.gz
│   ├── 81c11cc5225879f20d0c7512797527f4f268768a.nq.gz
│   ├── 83c3be41747359e1964b975ff66513ca9b5b5d47.nq.gz
│   ├── 8472770f6a68064e824c1462f1f6ff6b0d1a26af.nq.gz
│   ├── 8481282121a5388fbf8c71a3a3b02c848facf616.nq.gz
│   ├── 84eee21256ace6aee19598c3fb7274134234c37d.nq.gz
│   ├── 85c8ffb4a2b3ea0d43416be34c4aac2000ac3eec.nq.gz
│   ├── 862ee3c28647e7a58801a75236855c269c1448ae.nq.gz
│   ├── 87815a578ddf961eebfab2e51878b4f0c39fa4e7.nq.gz
│   ├── 87acaadba3d3a97cd17d084637a6cdd94caf2167.nq.gz
│   ├── 8de6a004f2a89bf9e1bb2d8374978bafa11f720f.nq.gz
│   ├── 8e31e328a6d75a19450eb64043e568fce276a6b7.nq.gz
│   ├── 9582fc588754f78d9875691a3bd5e674295436b3.nq.gz
│   ├── 963737d3de387b0db431c8fcf92e5b9fcc147d3e.nq.gz
│   ├── 9686c9a5edf2c242e09caeeb90e8b3ff59dea4c4.nq.gz
│   ├── 99a0177c366264e9ee6b85ff7fdcd1da85ce8177.nq.gz
│   ├── 9b41bee3fdef389e38b5520bc69f95952634aeb2.nq.gz
│   ├── 9dc9af642d47a103da4f6de1e8eea9d1ebf15e9b.nq.gz
│   ├── 9e6fbb0b6bf8b2345da3398c158b69bf8bdc6b18.nq.gz
│   ├── a2d367b9f807f0da89814ce44d8012fd225390ec.nq.gz
│   ├── a5922d46e883f2a712a62a365520213101c18cf1.nq.gz
│   ├── a6f8c49df871bb0d7e3b441bccb11599ed8bcdb2.nq.gz
│   ├── a7ea6c72bb2bda988c9f92676d58c8e9514782c4.nq.gz
│   ├── a82d16513acc44629243db5c0a1c4d01d80ffa74.nq.gz
│   ├── abb67f05485d80de60e01be027907b8f57430d80.nq.gz
│   ├── adb263c429b2a48a6d74a06cdc6bda4105c41543.nq.gz
│   ├── b389cc4906ddff4936e6efbcf2e70db064d26e81.nq.gz
│   ├── b65a40cb8580f79f8f7c4faaa403491f3354e296.nq.gz
│   ├── b753bdb841e7d073c6ae1e3b66eabfb2eb556985.nq.gz
│   ├── bb3af8e56a05642801721ce3de67c8282cf26053.nq.gz
│   ├── bdca7ddb61902dfcc61b663f62158a48c16bcb0d.nq.gz
│   ├── c52e88af0dd792aefb39d59ab4f135d9e0beeedd.nq.gz
│   ├── cb5ed96f6e0ed9d3ecef0eb2dabe7f13460bdc1b.nq.gz
│   ├── cc8de0cd6b3ab1cd1c840451152b84983807f5f3.nq.gz
│   ├── cdeb505886c9afe0addf66dfc3abfd8ff69aef1d.nq.gz
│   ├── cf93b67858c62030d01de8ec2e0a451f321e5dfc.nq.gz
│   ├── d16ec684464e539931997421c7c671fcef864b1d.nq.gz
│   ├── d51c5970249afde0bbf20a89cb664bde056bbfb5.nq.gz
│   ├── d5ed964c15cd3fd19c673b2fdcae48b1c2b5ec36.nq.gz
│   ├── dc9566fddfd47c2943e9b3e01a487c0ab882f3ca.nq.gz
│   ├── e27a5bebbcd58894670d4b7eb322847504bb4af0.nq.gz
│   ├── e889550ba4cbc92a720527042e5f6e7a303bfcbc.nq.gz
│   ├── ea69ece31e38ea11de57652ba5de439c66af0ff3.nq.gz
│   ├── ea97fa2d3a6322f954187e4fbc706cffaacf42d5.nq.gz
│   ├── edf664d7710c44afd5b32888790b8aceb278180e.nq.gz
│   ├── f064738e1aa37896f124364be8f9aa1ccec61e8a.nq.gz
│   ├── f151a1333c46b1389406173d53b78de91ec1a1f9.nq.gz
│   ├── f40d3f0e424d3d0c5648b6957d0bb22fe98d342d.nq.gz
│   ├── f45eb9bba0aa9a1bc39bd6a7313520733c19ce23.nq.gz
│   ├── f50e718a031b791ab207d97b765d3a5221f6fa80.nq.gz
│   ├── f6e138f920c86deacb349fae32628b462d6067a1.nq.gz
│   ├── fa6b1bae8c7224bb2d268d7a6e9a43a625941e67.nq.gz
│   ├── fafbf7f73ad2a9d3bb4545afdf2dba09facd325f.nq.gz
│   ├── fcdd7477eedd9f3bee904b994343becbb1cf41f1.nq.gz
│   ├── fe28214d3352b0ed40820a4999317694c8b1ef57.nq.gz
│   ├── ff1732e98d34a3df6de86673ca497ffc34d233e2.nq.gz
│   └── ff73d2be1650efc439b1a3c50a46b77d1a377720.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 78f9ea0044f7265b5e72aacd822215f6621fad7b.nq.gz
├── filetree
│   └── 78f9ea0044f7265b5e72aacd822215f6621fad7b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 120 files
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

[block/builderlab-cli](https://github.com/block/builderlab-cli)

---
*Parsed on 2026-10-02 by [repolex](https://repolex.ai)*
