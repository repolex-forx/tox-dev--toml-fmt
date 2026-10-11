# Repolex Knowledge Graph of tox-dev/toml-fmt

RDF knowledge graph data for [tox-dev/toml-fmt](https://github.com/tox-dev/toml-fmt), parsed by [repolex](https://repolex.ai).

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
rlex download tox-dev/toml-fmt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 58709e88fc6ecd2df2a1d4c1ad29738e72dfbf2c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 58709e88fc6ecd2df2a1d4c1ad29738e72dfbf2c
│           └── chunk-001.nq.gz
└── blob
    ├── 017957849880c79aa8eb79f3d8cc146690584dac.nq.gz
    ├── 01e5177cbe563c6b39474a4fa403c40624b319ba.nq.gz
    ├── 0229810dbfadd641b40ab11b8e4828e5607e9572.nq.gz
    ├── 02d9f8742ea931c4caf9db24a34dc158257329a9.nq.gz
    ├── 039c9820c6e84300fe1deeb98621bb4d78b4cefb.nq.gz
    ├── 0403f91d2fff1f5a01f83e0ea98a8f550aafe666.nq.gz
    ├── 07665b51d713a174a262c19949de4c267d855583.nq.gz
    ├── 095c2f25e36937a412cd54069cda77f1a6cbd95b.nq.gz
    ├── 0a4ff87192ffc4e8c9e6b80e09cc5e0e2fd847ba.nq.gz
    ├── 0b6cb55e38a0a162b0004289d275c4fd31c40860.nq.gz
    ├── 0d0dabfbf65041d2806d594192dfe99e115a23a0.nq.gz
    ├── 0f04467d3fa805791a11bb8499eea938f8b2574a.nq.gz
    ├── 108f1a084302666a5b8f43a32073f2db96211d7f.nq.gz
    ├── 11d1e70926c83db4f107b3a031cccfe8f7258e00.nq.gz
    ├── 1280202576ed5ae92fc362e19021632a5cfacfa9.nq.gz
    ├── 14c4abb7b5ddc8d27b6b3104c414aba85d68698c.nq.gz
    ├── 1641e9762a8b16b05e2d6d2545b1ddda0af27a67.nq.gz
    ├── 165adca4c81b6951de702b844efaab25150aa29d.nq.gz
    ├── 167aad37f6756ffec2e3c72b8e7e53d7914929f3.nq.gz
    ├── 1728fad8bad3f0559c3eabc3b0e4022f5457b904.nq.gz
    ├── 175268cc34bfe80dca3cc03b041a0f994b68e612.nq.gz
    ├── 18ff969cc7ab5703f298ecb93702eb312650de41.nq.gz
    ├── 1b3a7d0722f0d7ea425287987aa1f636f683e7b6.nq.gz
    ├── 1c0c7056616085e8885775813a2f84bdf4bf1d3e.nq.gz
    ├── 1c89318f06565ea4c5ba76625b7c739cb5802e73.nq.gz
    ├── 1ec17777aa48dd982412f065c9291ec8d21e0af0.nq.gz
    ├── 1f9658aa7315072e0db01e912fe0576a43bd239e.nq.gz
    ├── 21fbc9e306cfdc7bc5e6a25001b51f9a09967c9f.nq.gz
    ├── 220f93d375a19bb70914391ab389759183167d01.nq.gz
    ├── 23569d8b21a78f2052cbd74dad44c1ac744d82e9.nq.gz
    ├── 2543da3bc58c9c2e349781aafdb48b38e3ec4b70.nq.gz
    ├── 26c91be4f8f5dc7be5ad7b081df051a0cb2afef4.nq.gz
    ├── 272db04e3bd259de9a0a016abc40cfdbec3ab0a3.nq.gz
    ├── 298bf1750752970010fc98eaaaaf1b7b6682f13b.nq.gz
    ├── 2aa06854c087e950e618ada39bb580f5cf3a6bc0.nq.gz
    ├── 2b0d2ff28db6ffbc59c4d9fdfcd4a23cd014ee10.nq.gz
    ├── 2bea98eb67fb262760240cb8c013e72ea33d9c3c.nq.gz
    ├── 2cd37b242598ad0ca49de68b1e10d4ecb028ac45.nq.gz
    ├── 2edb51b777a910dd57c476811d556bd834135f8b.nq.gz
    ├── 2ee5e9f7120a364d44ea39b9760f39f43c709396.nq.gz
    ├── 2f2bfb629a3605d0897e14582756348c3697d96e.nq.gz
    ├── 31ae49d4b6edbe8d8ad078fe5ca4357932c555d9.nq.gz
    ├── 32b997de83edf0a33aa449a496273c22011ac5b3.nq.gz
    ├── 3439d38cd34aed472ef077cd55d3053c21c60c7c.nq.gz
    ├── 343a809a4a473184a728490b81de58d4b2cf190c.nq.gz
    ├── 348dba43fb6ebe56b8fbc2a861e9f33eb2ae776a.nq.gz
    ├── 349996e27c417bd7f0b3a12611c4ba56ebd78364.nq.gz
    ├── 349f16f2b8dd9fd27260ddba88a520044da1088d.nq.gz
    ├── 364982344fbd94d55705e1f27a9a87abaa255333.nq.gz
    ├── 379ef29bfad2c3c90b0bbc5e6199807a68066254.nq.gz
    ├── 387331aebc729de3292f3a08d57df35ff84b74a8.nq.gz
    ├── 3962d5fe0e3687c0cc6cee869a066954cc7ee742.nq.gz
    ├── 3b3d03a7bd276a04e9a611fb73b6c6b7443bc711.nq.gz
    ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
    ├── 3bfa60b7c8519f311d175836c747c2ce046598fe.nq.gz
    ├── 3cdf3c2b67cc81e126ed293866dfae03b5c8d1fc.nq.gz
    ├── 3d422cc5c587c33a768add2ebf1c033f189add1e.nq.gz
    ├── 3ec84f1c0822b103545c6b009a84c416e22c4bda.nq.gz
    ├── 3f5ba429cc8bf6d97885ca951d86491e785ae3ff.nq.gz
    ├── 414208121e3d06f45f682a63cb73a364d2dfd61c.nq.gz
    ├── 45d09d4cbca871c68ddc3787e9b910b5f41e42ac.nq.gz
    ├── 45ec21f82e505bb7b381e9c7fef4f0123d39c8a6.nq.gz
    ├── 46694162a8f5efd1bd64b9224264438882a52f3f.nq.gz
    ├── 46ba547bd68db9cd4cb4b534c3000804a32bea20.nq.gz
    ├── 4a24e3ceafa8ef818349e32cb57cf8fded7d4a53.nq.gz
    ├── 4abefd202a252e6ab3429d98e1705ac12e406d1a.nq.gz
    ├── 4c2d9a763a057c7595fbdb1d6211798ca5ed66a4.nq.gz
    ├── 4c9b734a711c370ef7bda25de1b55932ccab3c1f.nq.gz
    ├── 4d2d9fd642bba8187cff0ac73916ecd869965892.nq.gz
    ├── 4d5e583a9281003cb4d7e779fdd33ee726ef58f0.nq.gz
    ├── 4f8cfcfea8a75937f8c2b91f02a048dcf4ac9bce.nq.gz
    ├── 505bd3efba7d34ffc324cfa13949e2720670e22f.nq.gz
    ├── 509419d8b02f8909f000b14c41abd3ad320b21e5.nq.gz
    ├── 52a7545693a60bc7626fffabad9b0df3fb2214f6.nq.gz
    ├── 544041a1083f3b6b1a157057aa8ec50309b1c5a6.nq.gz
    ├── 547122a98b7bafa286a5f424d21e338b71cddd7c.nq.gz
    ├── 54a49281b178d0bd1d9ea0752fb25c4ee9e84b31.nq.gz
    ├── 54bac0152495c7b7e645888dc7e35a565881f15d.nq.gz
    ├── 5501ef3dae995d11262d5958ad69e3badce17fd8.nq.gz
    ├── 556cb3b40b7392c8295c336d61142317964ca441.nq.gz
    ├── 55bb6fcf86e8967d893270efacd82cf99f629088.nq.gz
    ├── 576cb6f6e51f755a2ea6a324352dadddcc8f523c.nq.gz
    ├── 577f83a0e6705400d32366861964da464adf23b0.nq.gz
    ├── 59e1b753f43b5f54817f5d8a2aba2e1b060f775e.nq.gz
    ├── 5a5ee01797048527ca4cbba8b85604b8fbd9d4e5.nq.gz
    ├── 5c5a3e3e3bf9563abfc4177fca16269d3046c096.nq.gz
    ├── 5c78a0e743fc06e1ac7c9d76a0b793100e46bcc5.nq.gz
    ├── 5f6e1cb4c127b5ce8854f82fc8478134c1e64073.nq.gz
    ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
    ├── 5fb6b35da0d2702ac9be38a7e847ee549a41476a.nq.gz
    ├── 6009358a66d3413a202961eb616159dc9a605439.nq.gz
    ├── 60359d70f7952718f73c9447d8458f5a092dbcab.nq.gz
    ├── 620f5ba2c2bf069b8c9e9595ea50a1892b985e4e.nq.gz
    ├── 620fbe99d33239cf3794dcf0bf34e9cda5bf8345.nq.gz
    ├── 6365839605a0bb88a65c75d2460076648119aa88.nq.gz
    ├── 65827e4c270efeb7c2ecd27f92c7e29c20077bdd.nq.gz
    ├── 66297dee3c008a5d3cff38e4496ca05dbf3206b2.nq.gz
    ├── 662c405884ac27e61d0b96a9c08a64f77657736f.nq.gz
    ├── 669e7e95e999c06291a7490e8c90fcfc21cc6776.nq.gz
    ├── 6793284af0e67b51b3653215f41142debf0c8cd6.nq.gz
    ├── 6bc6b75c28f2c4f050565c3a814c23861edc01ea.nq.gz
    ├── 6c6dc5a7dba743c0dc593d19a95bfd1484417097.nq.gz
    ├── 6cc2c487838e5091d8a67fa128148cde74c33b3e.nq.gz
    ├── 6df3901d15c463a2e274664238f73d2ec7e530b1.nq.gz
    ├── 6ee272c0e08eaad20973787fcd7284f5f328bc88.nq.gz
    ├── 6f66cb218a99734a6c457801588162f2e36d0d7e.nq.gz
    ├── 70284a5110cf2fe822973a2db44712491a6f3e32.nq.gz
    ├── 70efd2ca5876be129b40fa9b23f4041fc8522ce4.nq.gz
    ├── 718a8b1add79fc5008b1a6b385d2bf342c9506d4.nq.gz
    ├── 7229dbfc8c80dd30982197b2d09973134c8a3800.nq.gz
    ├── 726504e8348e5fcdb71fb73de2b866d781f1e14f.nq.gz
    ├── 7348a07114ae0686c8d279774658710c87533888.nq.gz
    ├── 75306517965a54731b94dca8bace640e856af115.nq.gz
    ├── 753e5beb36f2447f19552848839007d562f10167.nq.gz
    ├── 791a9bafb5c1a516f54e169fa1352aef07a79777.nq.gz
    ├── 798f55d01f491663279dba4c9762a8228a0a9dbc.nq.gz
    ├── 79d20990183b654cb4cfcadfd3db74254a64b6f0.nq.gz
    ├── 79f308405356826244c36f6e59fbe80a4f9923dc.nq.gz
    ├── 7a1f12a69e50e2d03c72ea28c9407110558d97ae.nq.gz
    ├── 7c29e8f9127250bf06499f3fe667a3f32653e724.nq.gz
    ├── 7c4fad9da413ca4a68c01270c0902495cacf90b7.nq.gz
    ├── 7d516a271f891394725b47f8f3513a00008951ba.nq.gz
    ├── 7f6a874198a7f9b74edea671734bf8aa37286fb4.nq.gz
    ├── 817e4a59f1ef7ba6896e40669a4f1ef9bee77955.nq.gz
    ├── 821370a90b65eb1107126060799e7164407f1d27.nq.gz
    ├── 8516760c589997dd23d01357ab8af1f0b14c7c6a.nq.gz
    ├── 85702c69dd8f8cfbe67b2a5a6222dccc1acedd10.nq.gz
    ├── 85d64b9334cbea71fec2107827b13adda0cd84f3.nq.gz
    ├── 893ea0f1a63522c6cce3d70b5bb2cae8570010f0.nq.gz
    ├── 8ac764635eb24463bd83dd70d4bfaa2851d58f4f.nq.gz
    ├── 8b395563efd90c3b5a9aa0573eee00c30645b6ca.nq.gz
    ├── 8bfd5e2246c95cff5d2b171b1f58254c063ef554.nq.gz
    ├── 8dcbab09c8649c1a2d439513f2738861b679e907.nq.gz
    ├── 9078358e322e55440811cf4229fbb4a99bb73f42.nq.gz
    ├── 90b7be409656881d11ece05268997b30e956a2c4.nq.gz
    ├── 91906a03f709db9991cd9884132b79e663d4fc5f.nq.gz
    ├── 94e8af227deb937f0db4cb037c78ed17ef2e79d3.nq.gz
    ├── 962a5743e7c6cd27c4e3fd362243b54d46c0c41e.nq.gz
    ├── 96abdee2956851c11b414dd643cae942dce974b5.nq.gz
    ├── 9865a1b91d166c05b9da29c8e3a71510e01c92c8.nq.gz
    ├── 989306fbfb90f6d72418b7b75aec7553601b01e2.nq.gz
    ├── 989a80504159bf8da3a5e74127b5f2f84ddfddd1.nq.gz
    ├── 995912e237e3e6fee4063629d625a94d632241a1.nq.gz
    ├── 99fc1eb976cf3d432781be7585b89a3b4b794681.nq.gz
    ├── 9b4d727560b67c1593717980124077a8adb6bd4a.nq.gz
    ├── 9bd8a96800f6969bedd66c5546908b6ce466bbea.nq.gz
    ├── 9fa52a53a6fec4887f81a44bd5dadb65afee6fd8.nq.gz
    ├── a31f16eeeb4d9a77bad3048f34f4c3a371dc682d.nq.gz
    ├── a553f51cd55888cf3f5f421e6002037e634f2537.nq.gz
    ├── a8e796e7c73d1b89de9bddb2e720f01af0f513a0.nq.gz
    ├── aaaa80dc14f9da67a9024699bcf4f45692d3e0be.nq.gz
    ├── aaaee6e39ebcae61ccee7ecdba9229796f339607.nq.gz
    ├── ab71a3304f19c480a05fbbe3ae65c9bd2483e82c.nq.gz
    ├── abca5bc9db3a40fe55cad16dc17943bb17a55823.nq.gz
    ├── ac2f7fd01fd203aaa80821e71d690d0f4f244d8b.nq.gz
    ├── add05c97d0e303bd6e0fd34fd5c1a205384ef4a4.nq.gz
    ├── af7c7e9ea54ae9b20960b2234ba01c1c184f73fb.nq.gz
    ├── b0a623b816a4718e1d09e666a43be0dde475d5ba.nq.gz
    ├── b29ea5189693e6097b901c59b6b308023d650931.nq.gz
    ├── b3ee6e8aee5bab71989fd060c915523b6f7b5f85.nq.gz
    ├── b47e5ca29eb7ec55dc1620f35aa8e536865956fb.nq.gz
    ├── b50ad6cfed3b99c88cb77797e248f2f15086b9cf.nq.gz
    ├── b56c3769a2458071acd24c743a415e59a28edfe0.nq.gz
    ├── b73223b5863f5c2795a4b5857892e21393a24432.nq.gz
    ├── b7ad776ab882e2b8ee668e267f584cfad0591fe5.nq.gz
    ├── b7c58cc078c2e91f3b7b7bd55e6b41c84575719e.nq.gz
    ├── b8554d20e9986a298ee222394e4d4a7a2e0cf728.nq.gz
    ├── b9a476ce651f02604179ebe29d372cf139a24714.nq.gz
    ├── b9b6411b6734701313bd09de21f7fa550cfad944.nq.gz
    ├── bb4ac2bf2ab8af3eae6d4de77129a250c2e34752.nq.gz
    ├── bce4a03f0c06af1343175db9e59de2761fbb54fc.nq.gz
    ├── be52597898f85cfb31665c60b39c0af7352aa410.nq.gz
    ├── bfc97a95b84252fcca66d7c01b008f72e1e6482a.nq.gz
    ├── c157d93ebc3ed19c8d5fb498b6e5c9f9eda454f3.nq.gz
    ├── c19b540e5157257edabe1d1f10413420565ed419.nq.gz
    ├── c1aa86f5a411551f4cc1506d4ac8f3c6d4b0cb84.nq.gz
    ├── c2d174575f204f18f28e6549484b11e6b352da84.nq.gz
    ├── c4675147d51350ca410e5ac1e8c719ccc794fc10.nq.gz
    ├── c4a12fb4a34b3cadaf5b343638b6ca8fc506770a.nq.gz
    ├── c7f2fc394a7a9656db0b0a7766542b9a9a6cf8a5.nq.gz
    ├── c870ce738942a512141e47935d063ada19e01c62.nq.gz
    ├── c9afa9d7907bbb30f52e711459beb0bbb07334e6.nq.gz
    ├── cd2a23639f3282cb699adb5b93ac6d02ca30c032.nq.gz
    ├── cdf10c29f0acc1d7eac60d700dfaa6ae1e1fef65.nq.gz
    ├── cf5f7e42033e2a56ad7f5115b0c40d6ebfa66ae5.nq.gz
    ├── d1335f1d69da51aca66d6232c34cef35dbc93907.nq.gz
    ├── d1b01ebc93798cd556b1e45dab81b1d3cf8d8ed0.nq.gz
    ├── d1cc94b8459bf489057ff4e1ac68393201fc43c4.nq.gz
    ├── d34783e26a83052b7f0e5f11f602d3e04b55c393.nq.gz
    ├── d4494e6d6ce4ee9b1c1cc38b7ba70146640171e3.nq.gz
    ├── d4d2615cda1ba1af347bac377af22e03f648e368.nq.gz
    ├── d5509036c8130d8352b013679b30b386a5992dec.nq.gz
    ├── d8d0bf25c325675c9743a4b9dbb29569676d222b.nq.gz
    ├── db5360c754057bad9db32a047a977c6b1981efc5.nq.gz
    ├── dc7bb5f0121a1f03795d278d0647eb1149c5e140.nq.gz
    ├── dde0dcec3523d2d34c22940906d818ae3ed117be.nq.gz
    ├── de7ccbd0f2632d4fdb0d776719591dda362d0e7b.nq.gz
    └── dfed29fdf3c6f094f33d01ec3a2a80b5dd5666be.nq.gz

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

[tox-dev/toml-fmt](https://github.com/tox-dev/toml-fmt)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
