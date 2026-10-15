# Repolex Knowledge Graph of sphinx-contrib/openapi

RDF knowledge graph data for [sphinx-contrib/openapi](https://github.com/sphinx-contrib/openapi), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-contrib/openapi
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dd03c2bbaab6847166e773c76dc25ee5d7483761
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dd03c2bbaab6847166e773c76dc25ee5d7483761
│           └── chunk-001.nq.gz
├── blob
│   ├── 032e604d257b0b0dfa059db92d721302d87af3ec.nq.gz
│   ├── 0425326125db69dc408084b50d1e1e07ae4cd559.nq.gz
│   ├── 04329e5c8eacc88fbbe62dfdeb1e9748a7281116.nq.gz
│   ├── 073e9a2301504381748b63c6dcffa1ddc36d9dd9.nq.gz
│   ├── 0c70baed7ea9bc93261bdd87b3a5902c47598186.nq.gz
│   ├── 0f52396dbb67488925853fb987e68a49b527530f.nq.gz
│   ├── 0fba56ad71df9ab894b708d2500f7252a87d8d23.nq.gz
│   ├── 12c14b08aa4dc91c3067d7b8c1a3c10c2e75c2ff.nq.gz
│   ├── 18736aebd05ebf0bbbe53c539f3c96ae4e36e34e.nq.gz
│   ├── 1984be9ff0bdbc3f949fedab6161bcbf30a917c0.nq.gz
│   ├── 1b5a6ce43f6b3f07ff4c0db080a315c189841cbb.nq.gz
│   ├── 2630ac9084c18f50fc18698b2b9b0b60e3d11341.nq.gz
│   ├── 264dbeabff122b7466fe95dae4bab81da2aa4dcd.nq.gz
│   ├── 273470fcb97677d846b9c3d920335638d23ba719.nq.gz
│   ├── 2d87b744fb9b0d9765b79d864c0309f969fef2e9.nq.gz
│   ├── 2f4a1ccf10559e9df358637164ce44c17c9251fe.nq.gz
│   ├── 306dc90c9c20a71c6ac66b66d8566d6be9ed04b7.nq.gz
│   ├── 31d2e9b2ff647d84b0cdae3ccb4e13e9bc94e79c.nq.gz
│   ├── 341885f12c93f25282879190d7ebcac3cc324979.nq.gz
│   ├── 35e67449c5471a46befa175c55f4b4fe2f3bf3fa.nq.gz
│   ├── 37537913534fe89e6749518fe7d8e7ec31aa910f.nq.gz
│   ├── 37d1af842048bb3f623ec6a3ce8239bf23594df9.nq.gz
│   ├── 3dd51882c9a22ce7b69fc90cd95dd023b7819a63.nq.gz
│   ├── 4003794e832f6d6a35ffceac739386f5f898759b.nq.gz
│   ├── 4059326d0f11022fb21a512dc59ddd0530f403b7.nq.gz
│   ├── 415eb3f9aea9c4ede6d824ca91e8e53ec5f2923b.nq.gz
│   ├── 4b52dd94fc4521bddc40b81ca1c5c8837d7610d0.nq.gz
│   ├── 4b602d6c236f68b975d806a650bffccfb0267dc0.nq.gz
│   ├── 4c08cf9e89ffdc6d9c237cf5059b0631ee66620b.nq.gz
│   ├── 4d8563cec07dd9a76cafe38bcd0926186c0b972b.nq.gz
│   ├── 4dbaf3277653bceeca9e38dde458d71c3a6c3c20.nq.gz
│   ├── 50ba599c2fcc4f95b8a84b8df010288b0ae88a45.nq.gz
│   ├── 565996a6a75bfce5b66dc364117ad67002655ccd.nq.gz
│   ├── 56aa59a711f29a34e7fce7aaacd7d7791e95941f.nq.gz
│   ├── 5711bb11baaf74b8afb9a1b5129f2a0b35b74689.nq.gz
│   ├── 5b28b2fbb2aa4d93c7a7cc6ea52725bf2c496672.nq.gz
│   ├── 5b53906e4c89b80be170ea3b6e215e7e229a88d8.nq.gz
│   ├── 5f41fe091f9953c5c1617d652a074690d4ecbb7c.nq.gz
│   ├── 622c74d5ec07c537e845106ab0431d3ef7c0ade4.nq.gz
│   ├── 62ef8e9a1b2524211e34030caa4a2fcbcab55ca4.nq.gz
│   ├── 63a2914202fed0d9ef3c7a62f4b983d4f58b6e84.nq.gz
│   ├── 64d7ae5ff929ebeb84932b22993f974139fb0ea5.nq.gz
│   ├── 652abb1cc8c4cbadf612ba9db1666f59e5af4582.nq.gz
│   ├── 69adbda6cb815d43a7b06246bc4d380cf46c971b.nq.gz
│   ├── 6a39a72fd65504bddb3691296f921f4036ae1b9f.nq.gz
│   ├── 6b4460fc58b07bd229e837d536436376d37153b3.nq.gz
│   ├── 6cc8c3885519f9d3b40ca23549066fc8e2c68181.nq.gz
│   ├── 6cd0c0a154ba7b41ad48218be08b3d406ab613c2.nq.gz
│   ├── 6dfb1836efc473494f87ce2831c9edf633954831.nq.gz
│   ├── 70deefdc36483b31f2a61c9a72c40ba01cd06279.nq.gz
│   ├── 72769900206c4547cd8a27b48475b18c8391aff9.nq.gz
│   ├── 7315872e0941ac5ff3691ba82954824ba4f72bed.nq.gz
│   ├── 73ce7f3f37ec27745615394ce5f17c43e5bde301.nq.gz
│   ├── 792864fca0604b5c7f6b62fc4fe6af9183e53437.nq.gz
│   ├── 79701feed23872afc7536436e22711c4fd46c8ec.nq.gz
│   ├── 79f34cb65d7daef766e889836c187c15488b1240.nq.gz
│   ├── 7b1cd8c6e078bc9fe74ce923c94bbd173bddedc9.nq.gz
│   ├── 7bd4df8f32c8e916da595d513e8e392c26309305.nq.gz
│   ├── 7ea8848cacc20059ee4e9c36ce566b07bbc5c2d6.nq.gz
│   ├── 7f03bc102103494a88bf8b6f850fa560d06c7fb9.nq.gz
│   ├── 81dfb0f2bc781d80bb6c41660deb4a0cb1320be5.nq.gz
│   ├── 8302b1d2ef5528813275992eb53eb4e34eef787b.nq.gz
│   ├── 8392a0ebb3d649fb88f199558f12ec42a963cc5b.nq.gz
│   ├── 8628048e4f5bcc422554f324272d3cb2d95863e9.nq.gz
│   ├── 86cad426f07f721c064ff1d381fcf581829ca6cd.nq.gz
│   ├── 8e9b159f520e37a0ccb7499a6ca98edeebf5baff.nq.gz
│   ├── 9104f7f68a00adb250c8d1d31ba8f0cc9718f9d4.nq.gz
│   ├── 9560c1869624da2d2b72f02f2950f5bb9275f812.nq.gz
│   ├── 957782897d37d084f8f5cd924acfa7786ccc2e27.nq.gz
│   ├── 96be5ed74da03011cf5884a8b64afd1380c8bc3d.nq.gz
│   ├── 97d838ab6c9d269583684e7fe692daaac265d606.nq.gz
│   ├── 9833b765addb5e23ff3858f1f490231a9cd48f22.nq.gz
│   ├── 9881cccd3f850badeeffe7c2d6b0c484b213683c.nq.gz
│   ├── 98f62c1d0f7d71fefdb803e1ad8059872ab12242.nq.gz
│   ├── 9ba9590ea74ae9424f3f557c7a7d36c44ef06204.nq.gz
│   ├── 9d717b633c6f18144204185968c21cb121681b76.nq.gz
│   ├── 9d98f07c4d909a00df45450c31e2e4688fbcf0ec.nq.gz
│   ├── a7c11b0a0cf0137dfb91cb9ad632f880ce41a7e1.nq.gz
│   ├── a94b294799cd7e3ae674577033496130913cc6af.nq.gz
│   ├── aacad6bf2efa4a7c9f69c7a94e17763af7461614.nq.gz
│   ├── aaed143c0dcb83fefd4d150a9e11c37842143835.nq.gz
│   ├── ab878061b0a3148599a1bb9b6d12ab46c6a43982.nq.gz
│   ├── ac9fc8de238dfae9284133f916f69bdf7aa2fe71.nq.gz
│   ├── ace13db629a1f27f7512b230cf3528d080f94c2e.nq.gz
│   ├── ad0dac9bd0dca539829a9283264095117a025a61.nq.gz
│   ├── add9ab6e6ce1ace422b053085d33729c5666c5a2.nq.gz
│   ├── b06ad901e7bebb6d2d7e2bd365eeb9a3edb34316.nq.gz
│   ├── b0c184af1dc9b62d1da93ee3e263a51a9d09e2b9.nq.gz
│   ├── b937b5022a807dc9bf4a3587ec8315ba784fce55.nq.gz
│   ├── b9bc51c6eec8a29b5917edbfcc0636e732ee6d84.nq.gz
│   ├── bb113196f1a4e61c6e35e68222a253fac9102d8e.nq.gz
│   ├── bb4a1bd54d824212a87f5dca9904c8420be7384c.nq.gz
│   ├── bc5d72de17d906f6f073647ed0185a50290ffb64.nq.gz
│   ├── bda3058d621ec7730bad5d2093fbdaf827412077.nq.gz
│   ├── c19bcfa901bf1173e4b0e36798cbaa4f6b4b2168.nq.gz
│   ├── c232e2357ad93181d10778da3e2623adffbb91b0.nq.gz
│   ├── c3ce2edd417ec4530eb84e9add79e6bbfb5ac055.nq.gz
│   ├── c3e06e9152d84d247052909a0ef8b011d42fb76b.nq.gz
│   ├── c4f727d20aa0478de927dd425c820849e18cc07e.nq.gz
│   ├── c69de842a67acab0b3d0ea937b11c1fe8051de91.nq.gz
│   ├── c7ee9fbb05ce5611ce1864a8ec53e7b97eb30d71.nq.gz
│   ├── c8e4950fefbc484c6c72f91f8a6694e47b8c24ee.nq.gz
│   ├── d42785ab9073aa825b4ddfc62a0b6c84885c3b02.nq.gz
│   ├── d5ad89451381e9e1a67525c72a6cb0776c7d8948.nq.gz
│   ├── d5d8de81266bb959f3393f334588a9879193ad9c.nq.gz
│   ├── d5e044810d21ac243044d49af60866fb4ed37d18.nq.gz
│   ├── d5fa07b4285b47a9c4f9810ad9276fd5bebf64ca.nq.gz
│   ├── d6ede10b806219432a9edce1beb0402cc7a71cf8.nq.gz
│   ├── d962c7e64c48e8349763aae1fd323beac4402ba6.nq.gz
│   ├── dab2985b69c1486efdfd3b0c3448cd7a5a3e976b.nq.gz
│   ├── daeedc2f2d3b4ac92fc2b2bf1cb9c898c1f52da0.nq.gz
│   ├── dafa32e5908c63529d32a64ac152d908b675b794.nq.gz
│   ├── dc6cbd2a7161406265243e8d8c5ed0da5a166192.nq.gz
│   ├── dd0e65a0fa73f6277e695d16ff7e16ed48d31ef7.nq.gz
│   ├── de93377412cd383d8037591b474406758ef7f755.nq.gz
│   ├── e1463f55c89cb3861f41230391611d97beceee76.nq.gz
│   ├── e1b371a0701769266ecd85b837c8252fc63e7ff3.nq.gz
│   ├── e230387b06f427a744e65453a74cf31aae4dc465.nq.gz
│   ├── e3851679595018d13d4e30afe95b184b38c672f3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7530a56bc22426757ad17919b6c393d2df3adb6.nq.gz
│   ├── e948913033e22f6fdeeb1ca8ad673f6e70288cc4.nq.gz
│   ├── e95093f31f49f307494e40da87190c98e45b0893.nq.gz
│   ├── e9d3f7765d7cb846d0c40fa0d6e2da824b7efa06.nq.gz
│   ├── e9e638479dfd3c1bf99786b32ea2457b5c044330.nq.gz
│   ├── ea90bdcf5f75b28e8611cc83f790b1ace1d6cca5.nq.gz
│   ├── ebd2d3d5bb0a5cff31ef182bce1e9d619500a934.nq.gz
│   ├── f24b61e23fe8615c14b702cc096a357195617228.nq.gz
│   ├── f43a11f6409ec33436142d925d69576e266700e2.nq.gz
│   ├── f5a5f50e6b718e3bca16e9e0c6d1d092f4dc2566.nq.gz
│   ├── fc7a43cb32a87c4affcbd5802306c9e8627c7977.nq.gz
│   └── ff7367d21e5c5ef165afbc94ffe33ba8228847df.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── dd03c2bbaab6847166e773c76dc25ee5d7483761.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 140 files
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

[sphinx-contrib/openapi](https://github.com/sphinx-contrib/openapi)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
