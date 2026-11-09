# Repolex Knowledge Graph of GhostenEditor/Ghosten-Player

RDF knowledge graph data for [GhostenEditor/Ghosten-Player](https://github.com/GhostenEditor/Ghosten-Player), parsed by [repolex](https://repolex.ai).

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
rlex download GhostenEditor/Ghosten-Player
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8c4fc325c2f816470cb60c1123fd7d7cdb884941
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8c4fc325c2f816470cb60c1123fd7d7cdb884941
│           └── chunk-001.nq.gz
└── blob
    ├── 005741d05b94d50ab7e396fe29f8f6af564b96ce.nq.gz
    ├── 01270d7473e2db1e95894532a85e399f9efe3660.nq.gz
    ├── 0244be3b5795e8c381a85d3e7892c666fc21a5ee.nq.gz
    ├── 042e020dbe000606055bb672b0038bcc0ffbd5d7.nq.gz
    ├── 04d56df5eb7e248d211235440b692f1b8c834c8b.nq.gz
    ├── 08a47a3ece7764ad0f24a70301c069d55bf7d2cd.nq.gz
    ├── 0a497e906c529cc30f455de5000540e3cd2afe58.nq.gz
    ├── 0ad25db4bd1d86c452db3f9602ccdbe172438f52.nq.gz
    ├── 0ae64941fe06606652ea560a9a94d3bbe9e7afbc.nq.gz
    ├── 0b229742a05a1ee60c042dda84902d8f93252abb.nq.gz
    ├── 0b878e926feeb1f3f47e9f36197d00d2e1962a95.nq.gz
    ├── 0cdb06eabb9dbf69d49e6e3f19be2944c16bb086.nq.gz
    ├── 0d60fef762911e1e4a1bbbe1f7d030f513011d9b.nq.gz
    ├── 0d6672e01e5fa5f1a813045476659e91c7d8e6e7.nq.gz
    ├── 0dcc2c6bf280f14d3593ad317caefdedcdf1e707.nq.gz
    ├── 0f39ba175ef1f3b99b99bcc56cbe7d2c8a82bb52.nq.gz
    ├── 10d8e4c26eac4e7de60eadcf54380578a8e3aa46.nq.gz
    ├── 11722a749e83fd3a0ede4ddbc6ffe31f9db9d401.nq.gz
    ├── 13395bfac674eaf03c6c280989dcbc776114814d.nq.gz
    ├── 13a0e5c51757982d0926464b4ae8c1d135f54aae.nq.gz
    ├── 14a85946b676ea3dab1e294a95d291a5af4eb4dc.nq.gz
    ├── 1751932e8d5e7866f10ae7edc65fc7fb46177950.nq.gz
    ├── 19252cb0e946c74624bdcccbbc74d4bd2da38737.nq.gz
    ├── 19bbec864324969390f87df300ce4efa8f79ba85.nq.gz
    ├── 1a271242553eb01ed43d1ead6ce0e95bf95f6708.nq.gz
    ├── 1a5fd237c4173a592f24fce499ebb8ec06b3b272.nq.gz
    ├── 1aaf4d9efbea8c74e9c7955e9eddd4e6c392da12.nq.gz
    ├── 1b6915c59a568914c205009d6d6febc5b89490ae.nq.gz
    ├── 1bddde7199f159a2522698e427655fc9fee5f8f2.nq.gz
    ├── 1d12bc13ad3b2965c72e28bdf0d11f05d52c1300.nq.gz
    ├── 1d6aea3f45f7ccce8abde6e4d6ecda32ad329367.nq.gz
    ├── 1e29e9c4804f0f9fc73e65fbbc00f119c6818b78.nq.gz
    ├── 2033e678f43c3e69dd9f76e5d227e93b263ee403.nq.gz
    ├── 2136d27e7c78347ba142f298d10ee14eab386612.nq.gz
    ├── 23f5807bbdde39a29d1230472dfb0952495a5391.nq.gz
    ├── 24be98ab77e42d65f7d160ff3c7a3fe2e12742bb.nq.gz
    ├── 2589594645f06b6b2631d82a3e18bb208856b102.nq.gz
    ├── 26d9063b8e2719ab46247af1eb98206a6dad3dde.nq.gz
    ├── 2759a15c33ea25415797b42ce2361fb8c069b8bc.nq.gz
    ├── 2858e535f4ba63e1c92b3388308a6a814a728849.nq.gz
    ├── 28772fbeff748478d0ff23588521ab50ce77ba51.nq.gz
    ├── 28aceb127afe77e4e371a8528bf9d787eb195e05.nq.gz
    ├── 28b6ffc1a3c89f310238d99106b66a4598c78fc9.nq.gz
    ├── 2dce4d87b3b89df61b7d4cbb404d1412c581362a.nq.gz
    ├── 2e166a6750389484e7a7375bb25e8bcff044bd33.nq.gz
    ├── 2f5cc03634374b684285c0a3cb654417b2a504ec.nq.gz
    ├── 3015efb53a6dc74cb4de5a03dc774ea743110676.nq.gz
    ├── 316496538a55eebb9ca4d742820f0c387753993b.nq.gz
    ├── 32f76405c7ea78da0e2460499b5b4d8812ecf04b.nq.gz
    ├── 345c32b5a85a7ff978e991aeeb0be1ca444eb007.nq.gz
    ├── 351094f7dfc5853ae14f3b024d93bfab5c07bbc3.nq.gz
    ├── 355f68343b99744204d5b9c10d15aad989da7b51.nq.gz
    ├── 35d096a52aa622dffda9ad91177a5b681cf24ccd.nq.gz
    ├── 35edabf8e6b11d198d1494fbe8e194c21b914302.nq.gz
    ├── 39fdb6b4492a1025b909feb94442b575a113a63d.nq.gz
    ├── 3a00459a724b4151806151e9dd807b0e8cccd7ad.nq.gz
    ├── 3f30e86c9402884015339935cbd96e1c60f83bd8.nq.gz
    ├── 3fcf1e69ed4e8906fb8f09966dda6d0f4c1a03ed.nq.gz
    ├── 401403793d16ada0ad64031b7bd3630c191d24dd.nq.gz
    ├── 40d4384fa3cbff5010534cc7f9f1e63accec609e.nq.gz
    ├── 41194364c36747c9596764ba837ff25c5f3d5e79.nq.gz
    ├── 42ac83bccfbc3fc4c3f2415c9b8d0c6bf459b062.nq.gz
    ├── 432e7a8b13739290b77ebb006d4b4343003305de.nq.gz
    ├── 46b3443f8f38a43947e80b6480bcb879a51483f1.nq.gz
    ├── 47308297489a615cfab997fa9fcaefeba58ebc88.nq.gz
    ├── 4b6cdc5fed9aa79b6fd19c8291edf60ac0447a4f.nq.gz
    ├── 4c1deb2660e10968468f9c893db284c499cff9d9.nq.gz
    ├── 4c8f8ac15a72d9b8f40f2e4d970f1f9156bad65c.nq.gz
    ├── 4dbfbc1c08dceeec0608814ed9b51cb07476b511.nq.gz
    ├── 4e03214ddfe30360aff8d5ff02a206d39681aef4.nq.gz
    ├── 4e6692e551617c40eb85069b2d9104b94daded6f.nq.gz
    ├── 4f30f4c6f4b8c01a988fe157eeb102961839a62e.nq.gz
    ├── 4f92ec5d5b17540f2d45a1a6d5c3d7c49c5d1671.nq.gz
    ├── 50f2e88ae2df899b84f293f673b6f27cc84d826a.nq.gz
    ├── 52c62423b6ae11c115889eda34eec7aad3fdc132.nq.gz
    ├── 560a42e8e0fcd62d70363e3549785379d61901b6.nq.gz
    ├── 5aa1d964defe2085fad5ce1e2d0f08141faf61b3.nq.gz
    ├── 5b4a80e59f3f4d22710897fffcccb71a033be605.nq.gz
    ├── 5cf49b65c223107d22f6b49a67ebd16329bf973d.nq.gz
    ├── 5e498e49e9caa270689b508f64dbbb2fdb75e565.nq.gz
    ├── 5fd3f777eadb28109648bcf436005ba5bb429a04.nq.gz
    ├── 609ee4803572911840c5d67291d75d6f9f3f8c13.nq.gz
    ├── 6253f012185b3429a1a8c485abd9493e54be1d02.nq.gz
    ├── 62d4417e8b51982a22358fe90ce9aa0b12e57bf4.nq.gz
    ├── 62e1b3ef0cdd3ec2176879819b9512e5dc5ed669.nq.gz
    ├── 67decf548775d8d4276e35b0efb5386165405033.nq.gz
    ├── 68da5706af457c880ffcd85a7a3cefc8c7cc9f78.nq.gz
    ├── 68eed230240cea722701639a79a8cc3774efcee7.nq.gz
    ├── 6b1bbe5fb1f53798f0d9cf501f8c6a68da51b6aa.nq.gz
    ├── 6b8b9dd492115d9cd98dc57fd96627ca63d3ec1e.nq.gz
    ├── 6ba5862e97182e66c244365f82303b365c7af3aa.nq.gz
    ├── 6d26422a83ad0fc94f5e2322f9a2c609142d94b4.nq.gz
    ├── 6d61fb105040ee703e6cc03d620df1c97ad0b410.nq.gz
    ├── 6d8c4ff01d0993da6912bc1240a8c1fd47f3b817.nq.gz
    ├── 6dc3552f7ad40d4849179315de79cc454d4cb736.nq.gz
    ├── 6e42a934ba4fae7ed058123f811bfb69fd8cf576.nq.gz
    ├── 6e44e6200f6461c1103dcd416d4e095965dc6e23.nq.gz
    ├── 6e5c85f8b72bf71b08d7c378881358ce7f0b6c8f.nq.gz
    ├── 6eeefb38ee6eefee228e98eeb4e3dfd79abf0c0a.nq.gz
    ├── 6f3368077389301dec0e76a7a3a14219ef39e6d2.nq.gz
    ├── 6f5aa4a338592c03abd7a8d1e5c33f7e801667e8.nq.gz
    ├── 6f98e16156c76a047e40ebee12a16198113352c0.nq.gz
    ├── 701a0cd8ba5dec1ad180cb272c050245a2edd1c5.nq.gz
    ├── 70a88d8dfa8271176e262d5a44a099e136b1545f.nq.gz
    ├── 70da3fdac1d320335455a512479fa51230a5223e.nq.gz
    ├── 72639e547cb6c61ce3f2ddb9db279a20946f6b25.nq.gz
    ├── 72aac562f242e327cf67ab9c3bfd5f30cfa7068e.nq.gz
    ├── 72c0033a72dfb3b7a74c7fa96465fa1016b72ff8.nq.gz
    ├── 72eb3b508e5be9889a1fa5f86cd8875a82dc8704.nq.gz
    ├── 731a51f74e2a4d9fd7dff5653e59668ed9557a45.nq.gz
    ├── 731cc874e8fbde32ceaf38aeb8493fcdb8e25d1f.nq.gz
    ├── 73c1dfe6c47fc7062bdb0c72ae0e638abfdf2df9.nq.gz
    ├── 747e58937f55ee5a594f9e4e9d325cff50d5d4bb.nq.gz
    ├── 74f029c7c4600fe7a89a7d9d70916d50520fd01a.nq.gz
    ├── 768a0cd414ab18fe10fbed550c8191bbed7ee5f7.nq.gz
    ├── 772f7db5cdec0fc66fb658f84053fbe55f804f84.nq.gz
    ├── 7820b585c9bb6705187cd284232566566d5ad378.nq.gz
    ├── 790cee5e8a76bd10795970a37e1c73c60eae1ff8.nq.gz
    ├── 79c113f9b50178eefaedb999950fa206eaf6d645.nq.gz
    ├── 7b0fd09bb67bc95df292e0af4f85d15437010fa5.nq.gz
    ├── 7bbbb8927d15a40d029eab2cf927ac6272bf9342.nq.gz
    ├── 7be277c9356b0442d46f47374be21ffd7e04fe26.nq.gz
    ├── 7e8c7d4042a2f6e74c15c9c2b0f62a35d0b77ca6.nq.gz
    ├── 831ce054bcc84927ad010634fdb796ab470db6f1.nq.gz
    ├── 839a736a3f2fd449979bbf25bdf575423a9a8698.nq.gz
    ├── 83bdaf53821d8bd24200ffae4ba96a4cdedfde97.nq.gz
    ├── 84d9bc7d672f4f1ea7916845d593bb1164a872ce.nq.gz
    ├── 8733d257eadaa837f83f7ce5d24778a60bcb67ac.nq.gz
    ├── 87640b84b88e34af81fd92e65df30ef179c1ef37.nq.gz
    ├── 895a24ddd0a1f9ec9a243718b1e3be146ed0df1e.nq.gz
    ├── 8a196678837d45372cdb2da22e508db84ed18e6d.nq.gz
    ├── 8aaab774e12c6c035cd06efccc2e8882c40d5ad9.nq.gz
    ├── 8abf957de505f86a1bae2fc48097bdf58154dfc9.nq.gz
    ├── 8bd190eff0e7f95d4836254a09f66726d807a8d8.nq.gz
    ├── 8c9cd650486a4e0604e10949cbaaa50c19747702.nq.gz
    ├── 8dec97e4d043c91f7ee8d3072a8c5ff925931a82.nq.gz
    ├── 8e6a71f4c0b4c11eee5e25f45910198154e32db5.nq.gz
    ├── 8f2b9333aee1d5704bc0a89b19adc92c8b1b0b0a.nq.gz
    ├── 90af778826a737e2231adafb4bca658c8d32fb1c.nq.gz
    ├── 90f84b0b3b85ec5ca127c8310430031f6f910770.nq.gz
    ├── 91b4d0cd8bd586261c6cd8db92e60fc16c781b78.nq.gz
    ├── 92b28448449086d155879015422f74d1a095e757.nq.gz
    ├── 92d027353c7de8dbee088fc6fdf4d2dd6844fe42.nq.gz
    ├── 94b366749a3350e53956e0a758a581cd65b02a7b.nq.gz
    ├── 95656c1730746fa428e145d202db819d1da7fbb1.nq.gz
    ├── 95bc872452f8ec1cf32cd0c289573371479a6ac8.nq.gz
    ├── 97e5b5b69a75f1b156d6716287f921b91f7989a0.nq.gz
    ├── 98261fe6931dc225897645c900694b634906f7aa.nq.gz
    ├── 98d32188ef367a0d1a83c2b7e4e49fbff30ea1ae.nq.gz
    ├── 98d8d48195dc67e34382f733560496a5dccc6692.nq.gz
    ├── 9a5fb9cd806e582c6f9909bc98b5f9ee3b34e1cc.nq.gz
    ├── 9a6367ee5e09b37245299f995f085c8298c44d39.nq.gz
    ├── 9b4471095dfb0e87744d295c3b2b004032ba6886.nq.gz
    ├── 9c746841b5ead247aa7e82f24e31f76b129159a2.nq.gz
    ├── 9dea2f741a81691f9e08abb74eb673465725e0d2.nq.gz
    ├── 9e03779c6d047b22459ec140d1917a2a827748b3.nq.gz
    ├── 9e444e7d9928da4f303119e32ac684f424eae588.nq.gz
    ├── a0e66df59dd9b48b7f369526b1aa9d1220747710.nq.gz
    ├── a27c5cf678c210c359429445f75811fdda82cb23.nq.gz
    ├── a35fb552ca9a7c775cbf91a9219122e1a96c46a3.nq.gz
    ├── a3f94c626739da2f72fb4839c5b4f93b7af81814.nq.gz
    ├── a484a04176800ce39d4ea70ffa7e48c7ce9652b7.nq.gz
    ├── a5ebe469e330eaf1435076dc3c984444e7c7c301.nq.gz
    ├── a6ab2d87d55eac86a9ac5df3d0c82d801df99011.nq.gz
    ├── a6c8ef23c13bbc9d404a1bed31b1f823819948c5.nq.gz
    ├── a7063dd57cdaefe7467ea47b033675fad4bb86a8.nq.gz
    ├── a7a5c276f0f6a712f4b56bf012b7378ea8517052.nq.gz
    ├── a7e7fe46cefb1915617e2a8a49e434486f669809.nq.gz
    ├── aa0c3dcb3124243f69fad657923abe257e049237.nq.gz
    ├── ab40420733e82541ef1c70e81f17932209f1ad4d.nq.gz
    ├── ac3b47926ee56b0efc39cbff3c532918abbf953f.nq.gz
    ├── acd9c386835a6b607c5454579b4ec2266f9dfe1d.nq.gz
    ├── af638c9e35306d585be1aee884c1f61df9d7a753.nq.gz
    ├── b49806ac4df3b5637997db7a702b7145bdf81ef7.nq.gz
    ├── b4bf0e9715db762a5f125ffccdf4ec347642736b.nq.gz
    ├── b4df17514fdcfd958e5d0425228a62f57d3389c9.nq.gz
    ├── b4e92f0ab09a5e95f0a65eafc2ed4e5cd234687a.nq.gz
    ├── b59fb6186343b95f4ec2391cf2f17c15738c6f3c.nq.gz
    ├── b60564aecdc653da7e4995a5b6e2f547e740fa80.nq.gz
    ├── b756d6b10cfdc4974b75e0c2685cb6f211ecfeb9.nq.gz
    ├── b85e95dfddd484af09ef404654afe9fa51640ec3.nq.gz
    ├── b9f06ef97ac6c9896a97644e3f0742c408b158f0.nq.gz
    ├── bbd7ee77760dad3964ef473a1cd012740c6975ec.nq.gz
    ├── be79314a4dc134c8a6ea172669f2f5411b1eaae8.nq.gz
    ├── c2775a0c95bd6f6c7c702e5347c86370c7114930.nq.gz
    ├── c3297ddc83bcb05a63fba6dafb2867fa7392adc7.nq.gz
    ├── c3362cb9e57162cad10707a8f92d76d3da780dc1.nq.gz
    ├── c35b0669fc5ec7b758bef0c89a02517d2e194fc2.nq.gz
    ├── c5fac415886ee7fc384adde97359e9ff119328e2.nq.gz
    ├── c69a11ebed2755aba6994ac71edfa4c25124019c.nq.gz
    ├── c97dfb083002c27456de407cf1638c11b41a9007.nq.gz
    ├── c97f3fdd3e91908e3b9226d5a8b4ac241df27971.nq.gz
    ├── cac218898dffd9b51b0188a589695b4d01296e43.nq.gz
    ├── cb7d7dd0089eb93618954a52bf955ceafb88f97f.nq.gz
    ├── cdfd97308f2fda35e75140a920d125b2652f8a28.nq.gz
    ├── cf60eb0bb516bef406bb2766cda218a7005acb54.nq.gz
    ├── d0b719b27dc6ac8c39766b52318e21361a885be2.nq.gz
    └── d17597bf22747dd9b44958e7c5bcaa5ede40e23f.nq.gz

7 directories, 200 files
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

[GhostenEditor/Ghosten-Player](https://github.com/GhostenEditor/Ghosten-Player)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
