# Repolex Knowledge Graph of pysal/esda

RDF knowledge graph data for [pysal/esda](https://github.com/pysal/esda), parsed by [repolex](https://repolex.ai).

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
rlex download pysal/esda
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2054740124386cd694c410a48622fcd92efe7289
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2054740124386cd694c410a48622fcd92efe7289
│           └── chunk-001.nq.gz
├── blob
│   ├── 0045e48cdb808505543dfa1b8feed49fcba08a37.nq.gz
│   ├── 01da39727c465dc782594925894a961308e29512.nq.gz
│   ├── 09d2529e0c009089674834f13417cf47f5a9151f.nq.gz
│   ├── 0b91549fde3722e850a0afc35d4bd904e6d973dc.nq.gz
│   ├── 0bca6fa2567eee9afa092494e37f7dd7e48bff1a.nq.gz
│   ├── 0c655f842aa14ff8103cf22a26e5b1dee98164e6.nq.gz
│   ├── 0e08c66951ffd7cadd67fee9780777855232f0d1.nq.gz
│   ├── 0f9d5e9ef38c283e7f265038a71f353d09e85ccc.nq.gz
│   ├── 107c97230f489cffe820971a35c53cca707ae2b6.nq.gz
│   ├── 109362cafb0af73d9d89ac91c01efcc5a654302c.nq.gz
│   ├── 113b82d585d5760029e76b5aa0c1f8bf1a45d6ff.nq.gz
│   ├── 129388ca80c913dece2f401f5a681196f3f59621.nq.gz
│   ├── 148f464cc1ce7644c9623684f80f90960a09eb0b.nq.gz
│   ├── 168bcb3319b08ca68f1cdb355b62d17d5faa9e28.nq.gz
│   ├── 182f57397a9b70c56c7a1c6b118d9a8c734be4eb.nq.gz
│   ├── 1874c2326e7ab55c21e30dec2a6eae2363b76f9e.nq.gz
│   ├── 1f7341c568c42d0f051d53e34169f33ef448a357.nq.gz
│   ├── 21e5d8945641ecabaad967bd55da20fd1ea661f2.nq.gz
│   ├── 239d17f87754c88769cb932e2246d76adca7169e.nq.gz
│   ├── 242f006f0e965399849903c6c679f49efc90e2c1.nq.gz
│   ├── 2455c47b347ac4440bd7391f73a2f53466fd13d1.nq.gz
│   ├── 25811f5a8b27fd053ee600d4b8eb28618decca7f.nq.gz
│   ├── 2668b715808d56351af62ed34fbc43416ad46aad.nq.gz
│   ├── 26d074bfd3838abac89c4dd53d69113293f86f8c.nq.gz
│   ├── 27286739884e06bdfa5a0e91f35440c22f0fe1d7.nq.gz
│   ├── 27ffdba49d1c89d8fe97c7195a0e44d318d8e0f5.nq.gz
│   ├── 2b92d9e7d30b08246789edfee4c507525cafe33c.nq.gz
│   ├── 2f765113e9379ed65a73929534df38fe97a2b541.nq.gz
│   ├── 305e94b7bc118e82ebca5363da4d5657df26ad0e.nq.gz
│   ├── 317047b27fc22424ba724744b678d1aee71086d3.nq.gz
│   ├── 330de10dd9e93f9c4379c6e9e1641ea01905c820.nq.gz
│   ├── 37cad32dc8d97a4ce4bbd01dd17aac2da40f8eb3.nq.gz
│   ├── 38a78a0d35e72dfcb8b501e44be4eee724c5a912.nq.gz
│   ├── 3926d34081d6905e15e0977737c368634950399b.nq.gz
│   ├── 3aae546bcc626823f4ebad662b8e34e7716796bd.nq.gz
│   ├── 3e6dd2920e96d59cf4eaeabf755079bb37083a2d.nq.gz
│   ├── 3ee3f2c926f722836cb91f3b84dfe844801705a5.nq.gz
│   ├── 3efa79664d678374b3070687257caebdda728a01.nq.gz
│   ├── 4506341b7a46888039eb73585de399e4266c44a1.nq.gz
│   ├── 47eb378b5cd49e08edd6859fbd7af408e0ed42b7.nq.gz
│   ├── 48937ce0e30d7c8b25c8610f99378df1b96f404c.nq.gz
│   ├── 4ad8468adb445ca63bedddbbeeb7d311089759dd.nq.gz
│   ├── 4ca992502923429bf06eeb21fda144d0676c8685.nq.gz
│   ├── 4d987cfc4f2cb915273692c862492b2ba6827026.nq.gz
│   ├── 524e1c9731a6b9d7e7832465f3c8a0ca5a5099c1.nq.gz
│   ├── 53120af6c054011c03a95b0216b7e4ff71a58ab8.nq.gz
│   ├── 54f333a3b4acc7b9f1b1c07488c9ee93ac6e6401.nq.gz
│   ├── 551576c8f834bc36ac8e7ad72c92196a61dc4c7f.nq.gz
│   ├── 551c24c3bf68363407ce027049a65cbd371ea27b.nq.gz
│   ├── 58c05d4420e7437cfdfe7325bffd344f255e5d98.nq.gz
│   ├── 5977612831b1fc4972b7af6c6b99f96ea4e96e32.nq.gz
│   ├── 6010863553136bc906f739c79004605960a4ad24.nq.gz
│   ├── 60b345f20dcb9f6c9b5feec54646bfa3303ddff0.nq.gz
│   ├── 60ec639af71d9d5e1250b771c9777301d56c8c04.nq.gz
│   ├── 6176b06ca92a25ae24bcbec0c7d9bf45360cf644.nq.gz
│   ├── 63541372966ef2cb10d8bb622aec385f49294932.nq.gz
│   ├── 63fb8c286b37a3fe84e3aa29ce675b72d7ba76ab.nq.gz
│   ├── 6655f9c6cd033b4674059ee2ee15992b566cea30.nq.gz
│   ├── 6726d8d9596aff7a4a967c98f1873fc691758d7c.nq.gz
│   ├── 6bedc13487c4c53e013e46a1482552b9f12d8d19.nq.gz
│   ├── 6cbd659793b7de8ace5ce10c437b87dcfeae5eee.nq.gz
│   ├── 7113575cf382a345585ebd2c26374f077f0f6eb2.nq.gz
│   ├── 75ce74649e919245d9441df6b8e9fa7e69d4833d.nq.gz
│   ├── 7893f6a0a41eb63df241dc500690ecb89e3ff986.nq.gz
│   ├── 7aae58b53c4c3119fbaa63db4ff57bc6c36cf335.nq.gz
│   ├── 812ab05ffa398d7071fab297fbb9a7bfe54a6f2f.nq.gz
│   ├── 81e42cce224238ec2c706687a921962b85094374.nq.gz
│   ├── 8289538a2c8eaba600180de693b38a8066ced33d.nq.gz
│   ├── 8370f5df78ab4d366509f0dfcbe723e60abf3a8f.nq.gz
│   ├── 84557391b3bd23da2ae9b7883321f4e7faabdba2.nq.gz
│   ├── 8699fa6b89cb2fd5f54d6dbd8cb07f0d0d327f39.nq.gz
│   ├── 86a0dd631be2cfbb198af2641206b303bbf56477.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8b31c10d65e892229d476a8f34b0aa9368e83b49.nq.gz
│   ├── 8d2cb5acefb3587ef116af960b947a38df412f95.nq.gz
│   ├── 8f5a2c45ad3fe74d33258e840fc5f4ec69bfd1e2.nq.gz
│   ├── 8f9a394328c7c76be37e8fd1facc2775dcf4e9e6.nq.gz
│   ├── 9028c12bda8f7313d646460c4426a9aed117f01d.nq.gz
│   ├── 911372664222870c9dcae24754bbda8b8c3f2117.nq.gz
│   ├── 9329c792c4447885030d9a30f61abd300a344375.nq.gz
│   ├── 93693dd99b11666a0a7628feb326b59522e3cfe9.nq.gz
│   ├── 9416ea22531e35e1f6555ac57a210dce421fd7de.nq.gz
│   ├── 94487cd94104933f45ee20ddf482f44a6ea344dc.nq.gz
│   ├── 96ae9c42def92078bee48a801330a0dbacb89015.nq.gz
│   ├── 98f0f372f1b04fcf822ac1e85d449c22d7a3f1d8.nq.gz
│   ├── 99802eccff0148574de7e1ca386e389e34092739.nq.gz
│   ├── 9b04f8792cabec40fd08315acb4743da4755b677.nq.gz
│   ├── 9c9f9c3c44bc8b56d188fb81133b0baf46172028.nq.gz
│   ├── 9feb65f936f456e3ad6371650093a723d05a3cf9.nq.gz
│   ├── a1d18c549b24a057a7959918ed9b305365cd5eb3.nq.gz
│   ├── a48bbb334179f4aad6ab4483a41988f23897969e.nq.gz
│   ├── a5380ce32d6c5c0fb2be4331fa5ddd35f6b5fcac.nq.gz
│   ├── a68829481ce41fa6c7ff496494729be97d0eec65.nq.gz
│   ├── aafa1e2ba27f0fa95e8ae13940d33faeb0323474.nq.gz
│   ├── ab2e89552fa0a05cf937d2e3701547a7493f9cde.nq.gz
│   ├── adb52310f270b3ff54890f3c85b0b8c53ef914bc.nq.gz
│   ├── b28960dad6bf32e53639f8006a1452c35b990a23.nq.gz
│   ├── b2c1ec93bb3d8b47a9455d408c9e2fc8e4e4ed47.nq.gz
│   ├── b3739d37ebf16a26f4ade45ac5137414176b27ba.nq.gz
│   ├── b47c4ab7152c04d2cbd92e7b59b1e51c79ba5e4f.nq.gz
│   ├── b54cc17d8972b9c5ffc58773b34f2192f459ce8d.nq.gz
│   ├── bf07119a39c9f54de5062b3d2260b77996bbcec7.nq.gz
│   ├── c2ff3a1c28321c0ba6fafef6734807029446de6f.nq.gz
│   ├── c382d52b4c9457d0959d7b382f5a9f27a60dff5f.nq.gz
│   ├── c413c6fdf0c33fe6829211660edf0bc8511d09dd.nq.gz
│   ├── c50045548dc04201eb5b2cfb4b84470183a5a56d.nq.gz
│   ├── cab25d8d6ee49a6b649a167b0a374f40dbb2e812.nq.gz
│   ├── cb5ed2bdbf901633b44af4e5a6f833bd0ac7a6d7.nq.gz
│   ├── cb8cea34f806890a5756c18cb46411f664baef73.nq.gz
│   ├── cc419948c94ed9e4337b9429a82a87afb1bbcc3f.nq.gz
│   ├── cd89cb9758e84c59b13399a25325d366af87e4f8.nq.gz
│   ├── ce72652ca102a51c3a43a52aad924a51fb5bdea4.nq.gz
│   ├── d02b199822e004f3bc2e2c0da4865471722583d3.nq.gz
│   ├── d1eb7f17e4adbc996e3161bd18dbf8d78e19daa7.nq.gz
│   ├── d3123a762dfdfa708bd4921c6fed6232dcd5eed9.nq.gz
│   ├── d43256bdacd895cfca52bb683d1506f3e0c93740.nq.gz
│   ├── d79dc1934255c0023c25d13e98d852ef02f7c392.nq.gz
│   ├── d8cd14990ffb08cca237ff28379bb7e27e89baab.nq.gz
│   ├── db28305206458cf55f3bd3d9e2e80bd478a5d761.nq.gz
│   ├── db2df684aa00549d27ea4c9b238ce4b39cb00794.nq.gz
│   ├── dbc61f18dbb15bf2ad33de9f324c32798f0a3056.nq.gz
│   ├── de5214e8629987d46efbe77bd3946ee0f7d79e27.nq.gz
│   ├── de61320d437be1aee4b3d880414e556b971034f6.nq.gz
│   ├── e0320c3fad1895a43c203ad08e0bf4da1b66a3de.nq.gz
│   ├── e0516a63a931d2b6a564d27600bc446d979265eb.nq.gz
│   ├── e11d9eab1eb48a77dd0f2dbc1f24d42e234b0ed8.nq.gz
│   ├── e1dd68010fcdd0e1142a97e18edf493a4977363e.nq.gz
│   ├── e21161f86bb648f08aa206bc61f769b3df3e1bc7.nq.gz
│   ├── e3c2504122b3834dad4cba45f613e24590dabcc9.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f3a2c25d3fde8c326c2cabcda05995a621a90850.nq.gz
│   ├── f54354496e0c4488ad7b8721987907d94374858f.nq.gz
│   ├── f5a099aeb2a7c7982ea4bd88655f254b34306e87.nq.gz
│   ├── f712816da3dd2acb1f0f0ab7a8beec8abadf3378.nq.gz
│   ├── fd8220bfe639eaf34b52741ac4a8c6a069d8e419.nq.gz
│   └── fde0f45ebbcc974598cce72d01239d167a88d5ac.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2054740124386cd694c410a48622fcd92efe7289.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 144 files
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

[pysal/esda](https://github.com/pysal/esda)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
