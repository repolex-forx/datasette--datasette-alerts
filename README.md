# Repolex Knowledge Graph of datasette/datasette-alerts

RDF knowledge graph data for [datasette/datasette-alerts](https://github.com/datasette/datasette-alerts), parsed by [repolex](https://repolex.ai).

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
rlex download datasette/datasette-alerts
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c0a5fe7fbccf2bfd9694d517d821c5d52775fb96
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c0a5fe7fbccf2bfd9694d517d821c5d52775fb96
│           └── chunk-001.nq.gz
├── blob
│   ├── 05dafbf81ff42c67310cfac9a72f312abd383e36.nq.gz
│   ├── 0c23d19567c2252d02ab62e43d55627dd8710e21.nq.gz
│   ├── 0c52cea6f2033898af1da26f10a85509d30708ac.nq.gz
│   ├── 0e6a787f84765d93270b8e7689513b24626b7e45.nq.gz
│   ├── 1037bc7a6d6597413de2276d119cfd7576010ca2.nq.gz
│   ├── 12f5d2323c4d6b6668ed9ff10cd928a35d246292.nq.gz
│   ├── 131bfca37d8a3ff64b46d0449ae97200977e130e.nq.gz
│   ├── 215bfb82b9519add728eb5faf60d462ff04c3644.nq.gz
│   ├── 217a6d44d4aaea59cab6a82416693c7cca19d626.nq.gz
│   ├── 21dd77ba603458a652120c6dc42b545213e4e20b.nq.gz
│   ├── 2266b4048ca434770c643228d3fd5af666615553.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 268c735c45e797a7caf7946e103fa1f7cd28f9f1.nq.gz
│   ├── 26bf77b166684fd00f3b250048ab444a62c56d76.nq.gz
│   ├── 29f28c77f7d5ceddb3984750f906e289769b0005.nq.gz
│   ├── 2d9f49d5227ded5f423e3f3ad69836109074f315.nq.gz
│   ├── 345423335bad21caf2dcaa023b894948a0bac28b.nq.gz
│   ├── 3628b8327288c75c67c1fc7f3528ce5fc7741abc.nq.gz
│   ├── 386600c3bc2728cbe922d1e11ff37c23c4b6eb24.nq.gz
│   ├── 3c6cf862bca55ad1bbcf19f7b0219f4202ff1df6.nq.gz
│   ├── 3ddef9c81cf3a811baf06c5855b81171ff5246d6.nq.gz
│   ├── 445e70b951ea5e34075e7219b6a72fc93552a921.nq.gz
│   ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
│   ├── 4cee2e1ec116bfeb0f92d1043bc0597ad39cda08.nq.gz
│   ├── 4e485e77f20af3365450cb5c45bdb9af8c5a42de.nq.gz
│   ├── 553bed3a97b98973141285cfba8f4182672edd68.nq.gz
│   ├── 5fd5e980102e41baa2aa7f0152ba119bdea7094a.nq.gz
│   ├── 60da773662132c2e3689774cdf7ab2e99e196408.nq.gz
│   ├── 6fe7b5e2ae538dd745e2edc75b402209f0fe7f43.nq.gz
│   ├── 70e523996fde873bef4a1e58e1a7446d69f30d47.nq.gz
│   ├── 7122ad79b1e42abb6dc6371e8af71a861f6f43d4.nq.gz
│   ├── 72f3312c8bfda70d90be79dca25320dce420af57.nq.gz
│   ├── 730f8d2b3720472e26bfd379b7d713098b1ffb3b.nq.gz
│   ├── 74196800649a8235a749f5b4fe0624925e1d5f71.nq.gz
│   ├── 74d66753edc4dbb4e84b31c6b415b601b9d0e43c.nq.gz
│   ├── 79c1912babebec1ba7fe7548586e0a99a38e70d7.nq.gz
│   ├── 7d31eaaa850e29748e44aa381f9b30e4301f3934.nq.gz
│   ├── 7da3ff2560595f0c41bfcba3674d1c7bfa737b7c.nq.gz
│   ├── 80bf3279be848f09cdf79103568454c066b90b8b.nq.gz
│   ├── 84121d6638e91290e23422720eceb238435a32fa.nq.gz
│   ├── 86966a16f21ceaedf80936481e7f8f5af9e56cbb.nq.gz
│   ├── 8abe4369b8151310c0f1aecab0e22b6b45fd4c5e.nq.gz
│   ├── 8f4c3aa8ab6dd58eae2d83b92f9adbbcf5f45397.nq.gz
│   ├── 922127673f65025fe1caaef68a42005cc7b07b4b.nq.gz
│   ├── a0ff59452d0ba299bb78aa01731c1512fd325a55.nq.gz
│   ├── a35cd896b35306532e6310809b75ef6ddd29bc39.nq.gz
│   ├── ad4e48e65e2b8f9bc8021f1634b0799f79994ecc.nq.gz
│   ├── b03db76948a173087533db227769ecab324ad022.nq.gz
│   ├── b87c1bb1d6ceecc380f4575017afe708bc35b381.nq.gz
│   ├── c1a3c2c4a9c4dccb255eb69838aaff15c2f92ec7.nq.gz
│   ├── c3389e84a870a6d125ada80a3e6059f75ef11927.nq.gz
│   ├── c646ffcd5991e0c978e70671c255cb39c5ef46f5.nq.gz
│   ├── cbb997f25219632f4d12347352783f94f86717e5.nq.gz
│   ├── cbbd434edf04ebc0d16397f7f9657c9a5250182b.nq.gz
│   ├── ccb9a638b61f9f317889d62ce3b67260fdd7a718.nq.gz
│   ├── ce44d70cb6cd5666f2d111e6281b08cc268adec7.nq.gz
│   ├── d1ee31f86e1a4185af5fe096568f49c0528eec0b.nq.gz
│   ├── d4f4d2acf85169ee07aff62f423a6c8135c0473f.nq.gz
│   ├── d61a70f1ce6c8bc88dda30f13a907665fd6d1129.nq.gz
│   ├── d727887601172a33e97caa888d8a77c8be308227.nq.gz
│   ├── dcee6e56d2a9d9b18513c8490cbb7526551a41c5.nq.gz
│   ├── df94f43a9ddc1c7bfe5ec7ca61d6475c0b11b5b9.nq.gz
│   ├── e1dc3c86a29ac5faf4f69209371375d0287ab6f3.nq.gz
│   ├── e6e1bdc29e92380d040a8065ed0efe915752fe35.nq.gz
│   ├── e7263e4fc2452702bd71ab7b91068099181abeb3.nq.gz
│   ├── eaf9d7be87cc56f56c2575d6cf0e6d7804029ccf.nq.gz
│   ├── ec2c570c9af481c9b5424476a541a7972e68174e.nq.gz
│   ├── ee0b18b04ad2df01bf4d917e00ce7d9cfb6c374f.nq.gz
│   ├── fc0dc7b3eb84346efdef88aaf4aa3cb339b830ae.nq.gz
│   ├── fc724abccab288b625a6493566a8b646e1eee915.nq.gz
│   ├── fc8889901c89190ee7ea44fd581177c3b1cf4d00.nq.gz
│   └── ff9c0d010eb48c5de934c7bfaf6e060f2e6f57e9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c0a5fe7fbccf2bfd9694d517d821c5d52775fb96.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 79 files
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

[datasette/datasette-alerts](https://github.com/datasette/datasette-alerts)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
