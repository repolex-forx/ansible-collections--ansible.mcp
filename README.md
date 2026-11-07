# Repolex Knowledge Graph of ansible-collections/ansible.mcp

RDF knowledge graph data for [ansible-collections/ansible.mcp](https://github.com/ansible-collections/ansible.mcp), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/ansible.mcp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 903eea71f148ac6891f9d3d31f8fc467c8ffbb60
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 903eea71f148ac6891f9d3d31f8fc467c8ffbb60
│           └── chunk-001.nq.gz
├── blob
│   ├── 0167c3bc67c241552f5f921ba2920a8ff2dbddf8.nq.gz
│   ├── 031c5ce9446daa374f153bf5051088942549083f.nq.gz
│   ├── 0324f5a566143f65e01e9d6a1387157c7aaeb80b.nq.gz
│   ├── 06d1cb7c85755612ac0c7f3203b1d017c9f197d2.nq.gz
│   ├── 0791ef5b64e51b85bb23459d8507b8777d49cc7c.nq.gz
│   ├── 0a23fa8967df15e4920b54396432ac4d3dccc2d8.nq.gz
│   ├── 0b34efbae11e83da51f2034fefea4f47a360e4fa.nq.gz
│   ├── 0e1c5c67c804f64d56c299ac55e815cb0c82fa69.nq.gz
│   ├── 0f816a8258c64370da34efc6d495130a086ddff2.nq.gz
│   ├── 113fc5294c530ec429bef14781ffb5d182302969.nq.gz
│   ├── 11cfdad628d1483901119663e5c01cdf49c2f006.nq.gz
│   ├── 123c95072d9907be81bd361c0158110ecae5c677.nq.gz
│   ├── 16b7fca25b3ca87711467f1069676cfa8ac528d2.nq.gz
│   ├── 1b93a4a74ecce758e6ee1c20fb50d8106bab958b.nq.gz
│   ├── 1c5a3e5b7e7f9a9ad15d0169bf3c9db161ea3b0f.nq.gz
│   ├── 1e15f606dd8ed8f5173f096b0b289c1a76c2a93e.nq.gz
│   ├── 20f27c7978339db0ff175dcb4af5822b26550660.nq.gz
│   ├── 211baaea46c413968098c66f0e7edc40e1c9b5b0.nq.gz
│   ├── 23b997b3196385367952059cecf3fa8b9fff591a.nq.gz
│   ├── 25471b5ffe7385fd143e15bffa53f6c6c397ccf2.nq.gz
│   ├── 26a29ac155635c165ec6a523300b86df39937500.nq.gz
│   ├── 28c4f0f74a961d2e6b3bb4985359f58c40fe7dc5.nq.gz
│   ├── 2ff8394587d142501f4646e0b195e7ad843cb124.nq.gz
│   ├── 31c58dcf3e0ed116bea339f0da1f91144545c452.nq.gz
│   ├── 359fabe45d9bbe471f8d9101ed3f71cd539f27fb.nq.gz
│   ├── 35c80095c02d18603f1db829bf4c35824b6989a6.nq.gz
│   ├── 368668832572f213351a0ef9797bbebdc86eaa5d.nq.gz
│   ├── 376d12e9783f317809f064ae69cea1e8d6cec7ba.nq.gz
│   ├── 3995e2da707991badf73b14a058966ea15e1580d.nq.gz
│   ├── 39d019a30b5185d6e7297698fae185955bce927e.nq.gz
│   ├── 3aa3f1bb8fa51899b9a79236a44543f2dde2aaf2.nq.gz
│   ├── 3b065ec630cde5856d9cdcca74d560dd16b2d9cd.nq.gz
│   ├── 3f5f5fff9a3fda15b66e0bcb788b72b4caac3cfe.nq.gz
│   ├── 4172e01839a06dcc0131412d0177ce606b90bbf0.nq.gz
│   ├── 4247867d02e2cfc16fb7cfd3403fa7df1d7d8aa0.nq.gz
│   ├── 49c7554d4b2efff8e88120c51a2ac96526c1dba7.nq.gz
│   ├── 4c76cee8ced4b845b71e6491bee9d7ee82b8b494.nq.gz
│   ├── 4da90041338592cacaffe2b13e2f95c738dc6857.nq.gz
│   ├── 4e7c94a3996f8805b85e857ec8e28048acc15eb6.nq.gz
│   ├── 4ef4b2067d02bc467864b47795b10b7b8672c60e.nq.gz
│   ├── 5347ac456d0cc16e11f3e131726c120cd3808acb.nq.gz
│   ├── 57db52711aa32e0f4e31bc9c9d1eadcc04e53138.nq.gz
│   ├── 5c4b109783f2bd9e151a4d61ef4b2711caff5a85.nq.gz
│   ├── 5cae24f9438285bb0cd854d9e42b61299f333dad.nq.gz
│   ├── 611281b315323c8d5db6bcc8ea65fade42aa2f01.nq.gz
│   ├── 64b305fa9a013abd4ba8271aef7a83746a55de0a.nq.gz
│   ├── 67651f68d29c2f7d9c294e0a8e6849eed4dfd079.nq.gz
│   ├── 718f5a5f443688065656c80e4eb297ef6d6027dd.nq.gz
│   ├── 72abd4d4eaa8c820346fc9e199db1ceefa852b8f.nq.gz
│   ├── 7612a85a4ef2d459df15e003f42921cb38e7309b.nq.gz
│   ├── 76bad9c40d19feff41661b78959daac260f9f6a2.nq.gz
│   ├── 77ba543150a6c5e07e9d09dd5ce407d05d37ea4a.nq.gz
│   ├── 7a2fb8a25d5d24170737c6a88997fe21a81aece9.nq.gz
│   ├── 7a40c243e7bdd98851b2ef3532bf641cb7463c28.nq.gz
│   ├── 7a68b11da8b136187d66cb2bed84c89208189324.nq.gz
│   ├── 7ab5045d1efda2aa41cf3c411fbca7f3418fdbc9.nq.gz
│   ├── 7c1c77b4f1facb378b3bb8e247ebf59eca4f0ef1.nq.gz
│   ├── 7c603082e5776bdf5a39aacf273a21d5997d6fc7.nq.gz
│   ├── 7f4737fe5a854005ec696f7f7b46496d4cf31b36.nq.gz
│   ├── 82d0d40ece200cc8e424c089bdaf754d5d3667e1.nq.gz
│   ├── 844d8379c376f368c1f62c3c0296a7be9a2411ff.nq.gz
│   ├── 8486c69c3c53c5a9a66e113ad1c55209b267e5e7.nq.gz
│   ├── 856508812341e87c9d00f7f5c4f5bec99c9beb3f.nq.gz
│   ├── 85e9f25a77a727af932c26678d47d66f381b20ee.nq.gz
│   ├── 86518a2b9b946d3a583ba3b6a40a877b45f1020c.nq.gz
│   ├── 86f560aa3a5346d98330573468cb63c4ef49cfbe.nq.gz
│   ├── 883732b673e7bc88bba729516c82813eb72e5ba5.nq.gz
│   ├── 88ed69b317f136a584201ca66a54da40e392fd70.nq.gz
│   ├── 8c84d0b5c1ac00ec3de14a6414dca050153a6c17.nq.gz
│   ├── 8eac3177aae45916170a6c8cbf9cc084172ec992.nq.gz
│   ├── 91070ae4c44d644d98c2c45b3b3b890b51499c3f.nq.gz
│   ├── 92ed1a607a9262c0dfa60270565d84bb80d1e077.nq.gz
│   ├── 932dfb0748302edb13d7fecd0a305e0140e815c3.nq.gz
│   ├── 9ae2e66ca16a16ac21b266b4cb7d1fa8d15acebe.nq.gz
│   ├── 9e402bda748804fc72d5204d25787d4336c9ac16.nq.gz
│   ├── a056a90e5819e018af1cf914f42fb88a8e819c11.nq.gz
│   ├── a2a909c50ef592ba73956128f81a6ba8cf41a014.nq.gz
│   ├── a36183046b2aab4ce990d62d9593aa87dcf4ce3c.nq.gz
│   ├── a39f7f80fd3b42bf64261d57be4ef073e7a47ab9.nq.gz
│   ├── a6f1d4f17065c70287ae9855356872d172ce9b96.nq.gz
│   ├── a9c86e958364deb256066b49c9b67e210bec1114.nq.gz
│   ├── aae9d851632616e2c5421f839296df1d9b1e82c2.nq.gz
│   ├── ae183e6e67577822c7a427e47a3108428689263b.nq.gz
│   ├── b2d258277d2535cc674871b7add0091d6ff408d6.nq.gz
│   ├── b761c7a3f1b150620201744f006d1b99f52d864c.nq.gz
│   ├── b78575ca1a808e8045fc0324df5960f448b55e1e.nq.gz
│   ├── b7f06b8167a48270ad4ffbbab7cdf204ad47db00.nq.gz
│   ├── bbe68cc8180b23a4eb59121c95c31e124ca696e1.nq.gz
│   ├── bd97536d20884cdd71c8ab7f359a2cecf9f8a7a6.nq.gz
│   ├── bf829d82bab7a9d578922492a450dbc8d7d75f1b.nq.gz
│   ├── c57b637459742af0e0124a9b60f0acdee1864b42.nq.gz
│   ├── c8e11e0671346c426553689170aa34a0f5f47998.nq.gz
│   ├── c99d52910315cd6dd58c243d76f57f0115514b95.nq.gz
│   ├── cbd4d9cda6656262b5864c40716a8db8a220dc91.nq.gz
│   ├── cff57e55cf39d80d8ce7f199edf75619c8c9cdd2.nq.gz
│   ├── d0d78a7f7f2b072babce3fd81d9d03ce49316d66.nq.gz
│   ├── d82d272064a1aaf6c0d677a90455bbceb468d0e6.nq.gz
│   ├── da6c019dbdd6db18dc8e4320e2357f094e6b255b.nq.gz
│   ├── ddd0bc4459eb3530ab65749239a789421c1ecae9.nq.gz
│   ├── dfad0b5fb02a65193ac29ad3548150c5f05dcac7.nq.gz
│   ├── e1594e309373121aa70425014ef46aa1cad04133.nq.gz
│   ├── e17296783f7833a4aacaf1a48ac33ee3f831e960.nq.gz
│   ├── e390f1f3fb0d48c62a9906eb165561ed4944b194.nq.gz
│   ├── e3bf2d918dd8f567039220c464b28986ae929460.nq.gz
│   ├── e4a6736bf6089ae983a9fafbdb0cce54fd381409.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e99149f775a5fa195350f1b33611e1dc00fe27dc.nq.gz
│   ├── ea1472ec1f38b2d1410951194a02f8fb9f1c820a.nq.gz
│   ├── ed67ea8fe88f6f042404bbb85df25523a9a8b2a3.nq.gz
│   ├── f034f8cba4a3e98d4636559b01672b0607c2e316.nq.gz
│   ├── f24f0086051cfdfe2711e5b7559726cccf162587.nq.gz
│   ├── f288120b3c4780f2f577b7296edb988f545f85ed.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f5b998669235b5669fc21de0b51fc197ac829eb5.nq.gz
│   ├── f64ac4413f3115e7d8c910e490afc7677c8fbb80.nq.gz
│   ├── f7359baf57c49ccc1b4e4135798f312ff0b8b1c8.nq.gz
│   ├── f8bce3fe150bfacb1d9274f5e0f5f2bf96c326f1.nq.gz
│   ├── fb30b8b8db7b83e388d3b624ee7193393db6251c.nq.gz
│   ├── fc375c971b4f2ad0b084c4176625b9a8c5973a6d.nq.gz
│   └── fc7f9e3594a08aff23074b6081dfe7e307bbc2b1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 903eea71f148ac6891f9d3d31f8fc467c8ffbb60.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 128 files
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

[ansible-collections/ansible.mcp](https://github.com/ansible-collections/ansible.mcp)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
