# Repolex Knowledge Graph of scikit-hep/particle

RDF knowledge graph data for [scikit-hep/particle](https://github.com/scikit-hep/particle), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-hep/particle
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9c259efc258f033bde578a1f086b7e0cfe4c750c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9c259efc258f033bde578a1f086b7e0cfe4c750c
│           └── chunk-001.nq.gz
├── blob
│   ├── 011a1f390433bc0ffbe1a8b20c58532234ece94b.nq.gz
│   ├── 0183e9f9e1d6c35ba2f1d0b1fcc8c3e1f9b7ae37.nq.gz
│   ├── 055187d36bed5cf007981b0d354d37b5292bb51a.nq.gz
│   ├── 07c537923510c05baeee83111aa86629356e969f.nq.gz
│   ├── 0c2c625648e59f2323a889f2b497ccaa09798904.nq.gz
│   ├── 0c86c99339fe7109e0cb45a7331e0a5f2f59b44d.nq.gz
│   ├── 0fb2e265f55a0c48cafd42e65f1538611a6d8afb.nq.gz
│   ├── 13c01a81b159897ee15e6dfbf44fdc851ea3e43c.nq.gz
│   ├── 16c8914c1c3ae9fe00b2ad3b8fba655d51ca2fd6.nq.gz
│   ├── 19de110fb72b12a5b9178f6b1b899f4d7c43db6f.nq.gz
│   ├── 1b8d1a3f640a2e19cb25145f819a91db5d60cdcd.nq.gz
│   ├── 21c6468cb50e9a6803d8de39eb45ad4b1fed2af1.nq.gz
│   ├── 21d4b635731b63c97da1338efa07df94e9154c06.nq.gz
│   ├── 2771b77d0324b7c7fa4de4fadcb0234aef093955.nq.gz
│   ├── 28a1172882b55ba901244f1a6625e036b5276041.nq.gz
│   ├── 2931171c2860ed7fba89c5e18cc78feec2ed404a.nq.gz
│   ├── 294089568fe4dae913cbf4afac65a6ed72807793.nq.gz
│   ├── 2964fb9ec1f4359f856ba3dfdcd52ea744d67c85.nq.gz
│   ├── 2efdbb2318b00e41705172c4fd38a56a4291fd02.nq.gz
│   ├── 3054a6767355badfd64844f1bd7365ee51b15d44.nq.gz
│   ├── 30c226068487f976fcd41bce707dab9953c6c7b0.nq.gz
│   ├── 3230062227c0eaa0be568626f83865296530e529.nq.gz
│   ├── 3267bf4bce7dc5a0ea7d0567ab2026b2f78b55fc.nq.gz
│   ├── 362aee5d95f902eeb3ce4ee27db1c2bde048df98.nq.gz
│   ├── 3634544cc0eddeae7d4d6c66e27aeebf2826e340.nq.gz
│   ├── 3ae790d9553f39f1eda15b1721f9665707918c6f.nq.gz
│   ├── 3d80fd2f9cc09a65d2b734a649e84eae28e0f355.nq.gz
│   ├── 3f4265729713c1a73053d8608f02e2628739b4d5.nq.gz
│   ├── 4256947cb4a1a62fb354b024980141abe4431f47.nq.gz
│   ├── 4372bad1101c304311284d2d3e0013c2ea39256d.nq.gz
│   ├── 4486f84810889800e868882a778fc59cd5662c80.nq.gz
│   ├── 55f96a0c91a7f2313601f4d5ece0aa9646fbe621.nq.gz
│   ├── 5bb2b22f78faec68eeed9a623c15cad2747c9eba.nq.gz
│   ├── 5c1a1e1710c9d5497ae152449755775044508855.nq.gz
│   ├── 5e6ccd8ca4830a84eb2f0f0cabed7be0a36ab53a.nq.gz
│   ├── 607b520a53b9f2a6f914fb890e740a13de2c8e9d.nq.gz
│   ├── 627af873ef2dc4f049c61dbb2d66b49cb2edeb13.nq.gz
│   ├── 6512655488671db21dd8be652b4e622e0dcc028f.nq.gz
│   ├── 66d9b478d61031209f3154c420023d833adb3a5e.nq.gz
│   ├── 66ffa5881aaef288cfb6c59521ca5895e9a58fd2.nq.gz
│   ├── 6735726211070c7a7c6b31b9ef48d5f6e65564ca.nq.gz
│   ├── 6826e7dfbf72a060c17105f3273df2c296afe2b2.nq.gz
│   ├── 6ad04962b9b3f9d1808ee345d9a0ea81b64d27bf.nq.gz
│   ├── 6e826002077d2db64e1e359fef987e1d0eef72e7.nq.gz
│   ├── 72c1c293528fdcd0558adefa1b1fa21b827c2258.nq.gz
│   ├── 759d0769d3ab9604f58727f439faea8f776a2b7a.nq.gz
│   ├── 7bd96afa56a565b8c3ba517b50367d53cc2a662f.nq.gz
│   ├── 7f402b1e848b2409c154300e28a6d5278c3931e2.nq.gz
│   ├── 8106a15eb0ce3ccde1f6449ccc1191aea8c8cdbb.nq.gz
│   ├── 8820c48ae49594e821ff99035e73e503dbcb7a2d.nq.gz
│   ├── 88d0fe95bcde8484d40020928b4433a454f74f5a.nq.gz
│   ├── 89e15d14b5ccebe8ab243ea534c4a090490b9af1.nq.gz
│   ├── 8b13673c14657c63f5a23c7b514f9fca0725174f.nq.gz
│   ├── 9134b864d18eb21d5a59002d3ac8868ed396065a.nq.gz
│   ├── 9331fb9f235265f080f83e4009b8f6a75396b02b.nq.gz
│   ├── 9660e2ff69268ebac52eb5d1c247d8d69b614f40.nq.gz
│   ├── 9793f6040410f851965038bf188b9fd6e51f7f3c.nq.gz
│   ├── 9a7359195e6a56c7d3b206e6d431626318185994.nq.gz
│   ├── 9bbeffc329b6f768a11c795f9538636ed51b71d9.nq.gz
│   ├── 9e5507679dba835dfe5d628e85928a677f55feb3.nq.gz
│   ├── 9f88a09bad7639c2ea225d647519b67898505c01.nq.gz
│   ├── 9fb287a39195b72fd0a97441152d106b43a57bd6.nq.gz
│   ├── a40a1d8f2dc66ea9c888c759da6a3ff81bc6c0f9.nq.gz
│   ├── a8c11e8252ebaa9a398bc24c9487d11a3ed1086d.nq.gz
│   ├── ae39b8afac6162e6d2d267de880d56480c980d7c.nq.gz
│   ├── b82154eb00af7f81479a05fcea8bf938cb08e187.nq.gz
│   ├── bd9f2449ab4d65481b1626363335d7ca930f9ec4.nq.gz
│   ├── c1753f1599b88203f5c6f72ac3835775ae9796ef.nq.gz
│   ├── c1da8567a575534ff81c795bb86e9cf3e2cae815.nq.gz
│   ├── c442ba9b030db272244e57d24a82c30b013ebf1c.nq.gz
│   ├── c471bbfc16c0f7bb3dc84f34f6bac1b5a071f507.nq.gz
│   ├── cdb5c61df3597bd2974d4e65181f2ec7c4d7a160.nq.gz
│   ├── d5d55f581337aaaf172be7606e78f6b6bf8a946f.nq.gz
│   ├── ddf4c1f6e1c788db4086a2f93485e09a7495d418.nq.gz
│   ├── e0267604092178a73260e9d33401ad445a79ae48.nq.gz
│   ├── e07ac567378698a9388a44493efbe31a006d767e.nq.gz
│   ├── e1760e6dff95deedfd0387ec96b0754a4eb84356.nq.gz
│   ├── e3d04b9d7d02ecedf16406d36e8a3e8ec6e6b9d3.nq.gz
│   ├── e5c4a52492191b6269ca9f7f51371d3b5cfc97a6.nq.gz
│   ├── e69d077e2daa324e9017e37e0dda7b29ebb72ca6.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e76cdecf70a2dfd6caf4b32aa7b41e48599a73b9.nq.gz
│   ├── e90cbccb9666a933546afd2d6fd07a83854c906d.nq.gz
│   ├── e9f28f107de9120a519a84aafcd44ff0a6d67062.nq.gz
│   ├── eab92902598391f1034ad5f0e1834fb7653870f0.nq.gz
│   ├── ec394bf45231558d4d074a42511db47ca62f4ce2.nq.gz
│   ├── f156f47fd85b19d2fcff6f709c762bcd152d2247.nq.gz
│   ├── f481cd8ebbf583918f031df715b086254e299d24.nq.gz
│   ├── f6a9caf127e9caa52d33a601ef369a494fad8c3a.nq.gz
│   ├── f8cf556cc2db90c8dce51d5c4fc795d7ac7e5eec.nq.gz
│   ├── fada7adce9df23118ea6b0b70e58126b871db43c.nq.gz
│   ├── fb09e6b437874ce9e0d90598db9d7e8d4002fdc1.nq.gz
│   └── fbd444126af8db0129520295da6f6dc5ba7396f3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9c259efc258f033bde578a1f086b7e0cfe4c750c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 101 files
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

[scikit-hep/particle](https://github.com/scikit-hep/particle)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
