# Repolex Knowledge Graph of block/stoic

RDF knowledge graph data for [block/stoic](https://github.com/block/stoic), parsed by [repolex](https://repolex.ai).

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
rlex download block/stoic
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9e14ad16dc52456d18f1c898d5c293a66d330d5e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 9e14ad16dc52456d18f1c898d5c293a66d330d5e.nq.gz
│   └── repolex
│       └── 9e14ad16dc52456d18f1c898d5c293a66d330d5e
│           └── chunk-001.nq.gz
└── blob
    ├── 00e43e70cebef40fe31220cac5d08395a4d6f2e1.nq.gz
    ├── 03ed7ae6883d7aee2ac5b7a2537955382dd2ff4e.nq.gz
    ├── 03ee357d9c65331f84e0a77de2c1045d787d9cef.nq.gz
    ├── 053879bebe96e4dfc74ebd016a73e2f886d34b2d.nq.gz
    ├── 0544946902ec4b7725d492023e43c78deb3c4975.nq.gz
    ├── 056901f32f1913470ec7d94f0ba185b6c67c0211.nq.gz
    ├── 05d339bb60e1b1b4942b969ec80ca3f2eac3b84d.nq.gz
    ├── 0700849afe7a2be0ff3ff924f97b98800560eda1.nq.gz
    ├── 079cc6a2ea07dc442d5e65045c27531cf14ef717.nq.gz
    ├── 0992e429cc66513b58d30dab16c201ad0a3ebc43.nq.gz
    ├── 0d3d15bd8bad933eedfc24a41181f17418dd1fda.nq.gz
    ├── 0eac715fe29b5a2bdb093c82fe814ce9cde89480.nq.gz
    ├── 100829200b1f584b1c0ed489dc7dc16df12df4f7.nq.gz
    ├── 116effe8cf8777d8ff5fc1208c6bcda3c0977651.nq.gz
    ├── 12ead5a11c35f23faa866b8dfa2a1064ffe65201.nq.gz
    ├── 12f777cf3c741de855096c4f9fddfdd5e6ac90d7.nq.gz
    ├── 15efd57ee3b40c78d30bfd6a92de78c3de3bbbfc.nq.gz
    ├── 1aa94a4269074199e6ed2c37e8db3e0826030965.nq.gz
    ├── 1b9a6956b3acdc11f40ce2bb3f6efbd845cc243f.nq.gz
    ├── 1be0a9a697594e4adb26fab4d39f30521d625b84.nq.gz
    ├── 1c4050ed233175bf3b8a171bef70271bf9624923.nq.gz
    ├── 211680897ecb5eed40e38b20e374b8e9b09b4cf2.nq.gz
    ├── 21ff9628fc8fa8d87ba8cf3f2b17768d50bfc141.nq.gz
    ├── 22050e4a7193223dfba03005e68b149287903577.nq.gz
    ├── 227235c881e12b1c0a559ffbed7bc77ab44ebcb6.nq.gz
    ├── 23b7e48f7657fc3cab4ca019295c5119440cb9e3.nq.gz
    ├── 23d59fa8999c5197dbdac05fed7a893fa8a3cc30.nq.gz
    ├── 25517b5d72e4057e1e5e3c1ce6eaceaca3af4dd3.nq.gz
    ├── 2598173389dcf131b60fc28200588ab3ecba4542.nq.gz
    ├── 25de0fc7c0c82c142ca73910c62674cfd9a4550e.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 26cd6e30ac3996d87b29f085f34e2374c79a9da8.nq.gz
    ├── 280004ca4ab8bdde8b6fd4c6671ffe6a61aa6184.nq.gz
    ├── 28d4b77f9f036a47549d47db79c16788749dca10.nq.gz
    ├── 294e82b355764d6b46f9d9e2c70fc5f5f0e3a8b7.nq.gz
    ├── 29744ec1bcdec541fbe5ca54472df80164e2e188.nq.gz
    ├── 2f3588d6348a3c9c9e5c5522d467475c48697830.nq.gz
    ├── 31bc2e89a44014e19897e348151ab4bcfe569710.nq.gz
    ├── 31c94dbf38fa204ccd8db950c6f48c6a18a51460.nq.gz
    ├── 32ae8850c1226543af264e4f1a199d1822e6a1e0.nq.gz
    ├── 3313494fd95884b846ef236c16facdea8af7166e.nq.gz
    ├── 33f489970dd35dae985d898265564bae40d354ae.nq.gz
    ├── 36e0505e14e90488b2b5447ef8de950e8262c0d1.nq.gz
    ├── 3789a57d47ade970688eeb7f7049ae41d757f14e.nq.gz
    ├── 37f853b1c84d2e2dd1c88441fcc755d7f6643668.nq.gz
    ├── 3910f6792e1d0ee79eecddb8ab459d07b2bf1720.nq.gz
    ├── 399a2b3c8cb5f234e6ba6d409edaba109fac67cd.nq.gz
    ├── 39d5cf8cd54b9ca2b9c10ac9884e7e950ea45362.nq.gz
    ├── 3a852d9805fbceec2e955c1a694ae42a33be818b.nq.gz
    ├── 3a94d4c40fed0850a775ec686a754868e1f921a1.nq.gz
    ├── 3c448aed34af6c7821ace5ae4ae1accacfbe1d44.nq.gz
    ├── 3dd1bbaa301bed6bfcddd26e6c8f5fa2d8cef51a.nq.gz
    ├── 3e022222bc5b856f0318e470c87e898a3fb17832.nq.gz
    ├── 3fe3e70617f2103031869e49e2f8f2c1d8f58c71.nq.gz
    ├── 3ffd8c8372ebeebc76e97d56ddddae35cdfee417.nq.gz
    ├── 41d848d49bd602f96e47ec52516a4c9aaf306b94.nq.gz
    ├── 41d93dbb94c46f8618fedd01b2d89b8a2a03963d.nq.gz
    ├── 42afabfd2abebf31384ca7797186a27a4b7dbee8.nq.gz
    ├── 432d45bb05c8b0a1834e52fe03d41e8abd3e743a.nq.gz
    ├── 434e764aefb2d83ccbcf138caa3f7ff5666c8642.nq.gz
    ├── 43d25aad1bd63c7e4ef49e5553e6044abdc1f116.nq.gz
    ├── 4530313e1680887a5d3bcd24215661f856f73ae2.nq.gz
    ├── 481bb434814107eb79d7a30b676d344b0df2f8ce.nq.gz
    ├── 494939540a3dccd50afaaab1585169617b7855bf.nq.gz
    ├── 4f0f1d64e58ba64d180ce43ee13bf9a17835fbca.nq.gz
    ├── 4f6859862610130bfc9fd04b2c70f8b72c71ba4f.nq.gz
    ├── 511e9a1e99562b9e1adadfb5fe6ed988039cdd3a.nq.gz
    ├── 5244fa7a4f87372763f81e761174e6cc223369a3.nq.gz
    ├── 526b7baf9acf0f48a4d974dba82a286ed7f66f50.nq.gz
    ├── 53ce7ff1c1f36eb71976f405088e359518294cbf.nq.gz
    ├── 53d1254ed05c1477f6fa83df64b5d2bfa3ed5de3.nq.gz
    ├── 53df4dc6855057a0c2be534251834dbc9715c18f.nq.gz
    ├── 5465d8b6400334f1dade0095a7af219e977538d2.nq.gz
    ├── 54e569d906ec5ecc4a964b653c4c531c8cb6cbbf.nq.gz
    ├── 56089cb2cae4dac5052045ee0cdaa3909830551a.nq.gz
    ├── 5939ca8cfd097c2009af98c3a8185eef529bf443.nq.gz
    ├── 59b9d934953f40e74cd37f1d5807e7c2d4b4f17c.nq.gz
    ├── 5a1d4c0e47504cb9dbf325847ca6286ec42b1169.nq.gz
    ├── 5ad9ce1576fc52f28229404edcbef39381bc57bc.nq.gz
    ├── 5c939f01b9795831e0ad1d8293ef79a57f980812.nq.gz
    ├── 5cf7c4df72f2609fba45f0e6c73930d5606d6e3e.nq.gz
    ├── 5da2b316bb5530549278b3e9bb3c7cf401128fb0.nq.gz
    ├── 5e78a6a8da3d2035cefdbb2c12e3cd03ba4d52f7.nq.gz
    ├── 604ab756afcf8b0eed493cdba3275786df646c40.nq.gz
    ├── 6099ce610c7b2436d16edfa28a94f5d16453d36a.nq.gz
    ├── 60c77ad4b44842a4a0d971b905e64798098bf6d1.nq.gz
    ├── 62b611da081676d42f6c3f78a2c91e7bcedddedb.nq.gz
    ├── 6350e13300d7a1bab10c0f87f89a3d5ed0f625e6.nq.gz
    ├── 6410824640a8ddb9edb009f1c3a022b79000faae.nq.gz
    ├── 643c0f77909d44fb9541a3d0fea137a355f2b73c.nq.gz
    ├── 65375e71f7e9cb26155a8c633a2550a5d1e705cf.nq.gz
    ├── 66892c0139dae43317f6852262980b2bd57ff002.nq.gz
    ├── 67e2706531eaf1e95717c127276e05b464b6b5bc.nq.gz
    ├── 6830d82c3cc16cd32069d512a6ca8b9830b731d8.nq.gz
    ├── 6875ab74694af0f898c19b72e0fad0d83b338e01.nq.gz
    ├── 6b4a3de53d733c4782e2461c45b61d65ff8ebed5.nq.gz
    ├── 6c95c68bfcdcf632a9576f4049d60c24d63726de.nq.gz
    ├── 6ca7224bfc45ea4b2fce093b173a9885e8a762c5.nq.gz
    ├── 6f6cf12a2a2f0d0885a2b16f4d214d41a35efde1.nq.gz
    ├── 7101f8e4676fcad8adc961e929ea3bcb37b5262f.nq.gz
    ├── 712e239550867c57c04ca6e6967c74035e2e6f80.nq.gz
    ├── 71ca2d1d34f4720638b049686ce06d1e0fc34c7a.nq.gz
    ├── 7413088a0076502fef583bc2ed69d20c223fc0f5.nq.gz
    ├── 749d356fba47b513f2f5701d70ad90f7f746397b.nq.gz
    ├── 76365db3fb7e4d048755abdebe0e2d7ece54992f.nq.gz
    ├── 772ca2f94c719b15a2dd48bd3336ea32f823e239.nq.gz
    ├── 77383650509eb8a10ce8f5fe5a98b8217237954f.nq.gz
    ├── 77b8c062d3c13ca374f21902de1f51a25c8ba1a5.nq.gz
    ├── 78ee52fb654f62c3ed792512223f597aa89b4f09.nq.gz
    ├── 7a3e4eb3caf2456bf55c7d5632265d33292d4219.nq.gz
    ├── 7ae989dcaa4ab93df4939742c36fe9b63670a61b.nq.gz
    ├── 7b03b3c37dfc103725c96120663f45925d9b54ce.nq.gz
    ├── 7bb69a6a041d1068ef3102db5fc689d753415dba.nq.gz
    ├── 7bcbcc8ff0998a07d30619334387db79a9ed5e24.nq.gz
    ├── 7bd86f2e0b872f06816d370f7375eb7f4e306d72.nq.gz
    ├── 7bff8edf86fbd527b1293e763ca2f8e0f9ba9515.nq.gz
    ├── 7f7e5437764ceb21c49fc41a94d7e5959bcaca2d.nq.gz
    ├── 88d0e81024e662a7d18ae414873cda6f4088b90d.nq.gz
    ├── 8d4601609ed484d023e89fefb78ccf72854cebb9.nq.gz
    ├── 8e4d2b56a9607f7f4265829bb084ccbfb7d906b8.nq.gz
    ├── 8f4793500d84545a25d4d7760752e444e540d00f.nq.gz
    ├── 8ffa8d69e22bc07605188ba3902e4407805d5171.nq.gz
    ├── 90467b3e0b439da1ddea5cfcec78621237ce44b6.nq.gz
    ├── 9126ae37cbc3587421d6889eadd1d91fbf1994d4.nq.gz
    ├── 9287f5083623b375139afb391af71cc533a7dd37.nq.gz
    ├── 948a3070fe34c611c42c0d3ad3013a0dce358be0.nq.gz
    ├── 98d9bcb75a685dfbfd60f611c309410152935b3d.nq.gz
    ├── 993b8c10557e711b063eab392c5369cb48a5e444.nq.gz
    ├── 99d03bffdfdd1d69c735d50a0fec8639f3536d0b.nq.gz
    ├── 9b12f19e5d6aa00c510301cb6850b8457e9d18b7.nq.gz
    ├── 9b42019c7915b971238526075306ffba3b666dd5.nq.gz
    ├── 9bbc975c742b298b441bfb90dbc124400a3751b9.nq.gz
    ├── 9cebaa3590a4c1cd850791d54fb18003e488ad5a.nq.gz
    ├── 9f818fc64ff86125682a4df2bf87982b46da6aa0.nq.gz
    ├── a283cb2df5221d024260f5977d40c3a4ff349158.nq.gz
    ├── a3137b025c9b038c25092abbaccbef11c09c52a0.nq.gz
    ├── a46f4929c1b340e126f5d3860e2aebeca1746576.nq.gz
    ├── a9ef9c86d48b2bbc9c5d9a65bcc0de08013d4ecf.nq.gz
    ├── aa7d6427e6fa1074b79ccd52ef67ac15c5637e85.nq.gz
    ├── ac3255c959488e5a442ac09d36f7add0a3505ab4.nq.gz
    ├── ac5cf2d17eebadffaaf20f0beecd684ba6ac1a5e.nq.gz
    ├── ad59c14d11e95dc908fb8273883ef89f0cbba3fb.nq.gz
    ├── ad8f73730a76a854be2476e5fa057254cdf3e810.nq.gz
    ├── b1ccf40345f8dad940a004f7a008938d59ba5270.nq.gz
    ├── b2dfe3d1ba5cf3ee31b3ecc1ced89044a1f3b7a9.nq.gz
    ├── b32c0d2ef505de523641da8e33ff736eff08cd41.nq.gz
    ├── b3422c667e2dad885199bf6c69d0687a8afb90f9.nq.gz
    ├── b5cf898ae853f1de467017f359f5e928142a4c56.nq.gz
    ├── b5db6101c7be11ce8cd20f84201d0b2a4653a3a3.nq.gz
    ├── b6ab01ba6ab1e033fd565b9cde1916950a65059b.nq.gz
    ├── b6e037013a74ef9a5e060af30020ee461b29437e.nq.gz
    ├── b73d6c1630c75004e96cadbdb7dea0f59aaf475e.nq.gz
    ├── b89ddbddc5349bd068707484729a442bf80c51aa.nq.gz
    ├── ba0213c983f9994caff25c6436b04bd0b9ddbb32.nq.gz
    ├── ba286ab449d14ffc221365e00e7cff341e6a2ce3.nq.gz
    ├── bb08962122419942e6476c348d642dbf88719f3c.nq.gz
    ├── bc7306ff308875d9b05ac8d59f8dae36300825f3.nq.gz
    ├── bcd60892e13af1a385bc7c29c9dffd58b54df49b.nq.gz
    ├── bd59de4d367da5db7743feb442076403d45b08a4.nq.gz
    ├── bec78a5df02493fd829733e281100a74d12a40ab.nq.gz
    ├── c1d5e0185987c556421e0c62058c16ab636e7940.nq.gz
    ├── c209e78ecd372343283f4157dcfd918ec5165bb3.nq.gz
    ├── c3309a910b48cd12fd75b9e732bfb2d506295658.nq.gz
    ├── c60a2f028574c361f818366e45db14def0c97a04.nq.gz
    ├── c75b45474b15f43565405f1e0d390159c8185099.nq.gz
    ├── c7919c94f8a819592040c3f14ed4427068025921.nq.gz
    ├── c7d8e78b01fdfa21315e5ff25e74b36a4f2e4309.nq.gz
    ├── c7e9cfba451590bf9981f2dfd418641b78f2aa0d.nq.gz
    ├── cac793a448681d35e4f39dd148f9500b8f18e2ff.nq.gz
    ├── cbb98c8e8340d77c1fcaf6c4a241d3137925e275.nq.gz
    ├── cc67958640566bd9b1b4705d50ed2d6ad0070547.nq.gz
    ├── d08a67fa2b3812c9c6a73a538f0c71850d3a7580.nq.gz
    ├── d0c3949babdcfd4255f62c019fc9ea85a803fe3c.nq.gz
    ├── d0dcbbb7d71bdc9c01aebf10ba796517a2ff7352.nq.gz
    ├── d21bb206a726bce7715bfb4d5c1b500be0f4d4c2.nq.gz
    ├── d2d4a9563288a9819486d6f53a74989d35b2b799.nq.gz
    ├── d66ab14ab6f90bab6d0061a89acc718288b9252b.nq.gz
    ├── d82815376835b2c8a7147cb8661a0272f45e5487.nq.gz
    ├── d837f366536d709d5b1d25718bfa7b070355b956.nq.gz
    ├── db3ddeffb84960e3fad26691018fedc5167e93df.nq.gz
    ├── df570a80d80d4660646a04e0aea8d416e81d0e0c.nq.gz
    ├── e0e2f9222dbf660682614c128adaaeb762fb0353.nq.gz
    ├── e405c4f88e00c8af3eececa1df34d42045ce3c1b.nq.gz
    ├── e5c811faa3b9029d5aab72d31dc02266df846a5a.nq.gz
    ├── e6441136f3d4ba8a0da8d277868979cfbc8ad796.nq.gz
    ├── e64c5d6d97821aaa78686776eb20f588e2c2ef8e.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e7ee74e3bd78c6b7967ea091f760aca565965e03.nq.gz
    ├── e90e95e13151d97c83d939b884ddc1e0513f638a.nq.gz
    ├── ebf4d3f8bef2e0c9ee468baeb6a054883953ee28.nq.gz
    ├── ee537c9e57e641a8657eec4cd3a88443e57c5553.nq.gz
    ├── ef2c48cdce11d5d4727d1fdde82ab9c4f7d6657c.nq.gz
    ├── ef9e7dc7b08909023feb1e76b360d36e441f76f3.nq.gz
    ├── f0f88c746166f6211b6d8138ffedbbf4a4e0867c.nq.gz
    ├── f222931e0c5fa1af0627cafe2f91f0d5b3bb1f32.nq.gz
    ├── f3c8b010148d4422250a1d5b5c695e7d698fe4ec.nq.gz
    └── f589c4128297b0483d18b0444a6a0bb1c63d5fcf.nq.gz

8 directories, 200 files
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

[block/stoic](https://github.com/block/stoic)

---
*Parsed on 2026-10-02 by [repolex](https://repolex.ai)*
