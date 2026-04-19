# Repolex Knowledge Graph of anthropics/anthropic-sdk-java

RDF knowledge graph data for [anthropics/anthropic-sdk-java](https://github.com/anthropics/anthropic-sdk-java), parsed by [repolex](https://repolex.ai).

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
lexq download anthropics/anthropic-sdk-java
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 3014518df675e46b7fb8f57ff0c8e13a740e7b74
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 52273b435e8779cf5c6dc988cdf6b80126c16aaa
│   │   │   ├── chunk-001.nq.gz
│   │   │   ├── chunk-002.nq.gz
│   │   │   └── chunk-003.nq.gz
│   │   ├── 54cac60b023569ca3c0e56d0f9a741baea071ad0
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 7fd04e1e2170f459a7633cea7afa1e0e3da37c4e
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 819295adf126797f8201fc9b74fc6a1835106ab9
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 87d86d9733f954b557c9fcb9525b32b6a5b32182
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 971efc8f1692d2777898029e48bc7c67b3121a82
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── cb2f6468011f155717ff740eed529020bbf97f00
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── ce725820dcd2a96fa081ea43dc3aa26ec6486796
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   └── e3adc58c74d3dab38697bcd46f5845dcc390a458
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   └── 7fd04e1e2170f459a7633cea7afa1e0e3da37c4e.nq.gz
│   └── repolex
│       └── 7fd04e1e2170f459a7633cea7afa1e0e3da37c4e
│           └── chunk-001.nq.gz
└── blob
    ├── 00239e03d9009dce08c0c9f9dcb00f96c8224f98.nq.gz
    ├── 002bca9ad48021e665b1cf28b9d03b92f59d0d30.nq.gz
    ├── 006458c50790be5fe8b0d79aefc98a2325942e2a.nq.gz
    ├── 006dae9a06b340035a3c982680405a191ab3e08a.nq.gz
    ├── 00954883536807de402c1c90fdc30b46181a09de.nq.gz
    ├── 009b7b8fcc1434004f1d2014479c871a34095e8b.nq.gz
    ├── 00aa185e6d3d39adf3a3484c8aa0ec792e2b6fed.nq.gz
    ├── 00bceccba631fe492e61f5d5cbaab04934203bdb.nq.gz
    ├── 00d0f5f1d708bf3edc710b93e13064b9a37c8145.nq.gz
    ├── 0105831c2ba561108399288736bcea3e5cdf6e85.nq.gz
    ├── 0107f45d770cb7662d9d96711f3cd35177d0cc64.nq.gz
    ├── 010e07efa8876bb4d76d52a4a8009badf3cfd2ff.nq.gz
    ├── 0122986b383011d2965e363fc013239bb3e5c43f.nq.gz
    ├── 012a0d5279aff7601ef9346b6f533dda049acc09.nq.gz
    ├── 013c5439c39f9fc36163d17c01254061fa9d38c0.nq.gz
    ├── 01415da839d5ab5f139d921c0fbee7e3a3616825.nq.gz
    ├── 01df5b8aba25104879c6f5d1762516d9a0fa193e.nq.gz
    ├── 01e49cbc46dff10709679e72a65bd5747f9bdd87.nq.gz
    ├── 0217c2831141d644130a6202e0277248917b8faa.nq.gz
    ├── 022b84144a13532f40383d9c8549d43cad760648.nq.gz
    ├── 02356eab0d58f1bf4419cfac13c9f4c8226eadd1.nq.gz
    ├── 029f8a36c38a4c9c3b0b592e4435d132e3ce180e.nq.gz
    ├── 02e5479073814700927bf79a3e89cc8ea2047ec8.nq.gz
    ├── 02e75bdbf85bba0072426b3ae5a32a8a8cc4a269.nq.gz
    ├── 030d93d84da6d1635e2dc411f3c6b1b739200503.nq.gz
    ├── 03265312c7d953a693906f89c49d60e967b4a44c.nq.gz
    ├── 032b24ac4a8c847f75ae7f0b875079948257077b.nq.gz
    ├── 0332d422cac13ba450a2a35ba423bd9f75ee5881.nq.gz
    ├── 0332daeeafffe871dc4ccf294c5d40e500824b21.nq.gz
    ├── 03764360a5952d41ef58fe4318c73bfae77de753.nq.gz
    ├── 037e2c95326ee366d6f069327f4382582d2dfe60.nq.gz
    ├── 039cb15050d47a6e74a9b34276579f0ef6be60f9.nq.gz
    ├── 03aa22628b4014f8fb5494376dbae743d60cda07.nq.gz
    ├── 03da96315f7d0f36c254c9c43c412d18695f5f5c.nq.gz
    ├── 04065b3e9cd3263ac8d8576ecd23bac594acaaea.nq.gz
    ├── 040ad0936f541d99407d399f681d14ac68350748.nq.gz
    ├── 0428206c62a837a3f761d8a6fb67a03a29271054.nq.gz
    ├── 0463337fede9212193334ecda39707de740bbca4.nq.gz
    ├── 046bae45c5033e2c3cb40ecc9d3cf7af56184c7e.nq.gz
    ├── 047bc1dbbc52804da699e0ea5763ab2f7f3eeea6.nq.gz
    ├── 047d2f93d519887b2062cd5e5947e2d567eaf037.nq.gz
    ├── 048d9f9e0dd44279aeca13705aacb2b59e9526a6.nq.gz
    ├── 04a0c1bf3467b5e9762dbfd88350f9367958c7d9.nq.gz
    ├── 04adacc76e4f21f56f83c9a28b05c2d056982f78.nq.gz
    ├── 04b4ffc098fa2edc1e87240cd125443d9d735e15.nq.gz
    ├── 04b59462b1bde29f9d7c2b827225fc6ce49935c9.nq.gz
    ├── 052191bc4b883b24eb3594ca47ec5024954584a6.nq.gz
    ├── 05243a639d9e223c41ad2fee1fa1c661ac320577.nq.gz
    ├── 05d2fb7f9420f822cfe8997bdc2e6963c190a2f4.nq.gz
    ├── 05da7151829fd46c9e828d8effbfb656f00204d3.nq.gz
    ├── 061648953a49fb05da596204ade5446839a1aaa0.nq.gz
    ├── 061de14999839e56b20a42aab2a1e3c10304c583.nq.gz
    ├── 0659670b89865ebccb701446e2d6f3381c5ff52e.nq.gz
    ├── 066c068345da6eab854cbde72a3984d4fb6cb3eb.nq.gz
    ├── 06b970ce439376631be34c7f1241bcc57b217b77.nq.gz
    ├── 06bf685c29a124b5a322350e9becedded845acc2.nq.gz
    ├── 06ce79dbf7d21991f22195e22761db6422844191.nq.gz
    ├── 06e88bcdfe828edc954a2fede814f7584b78ecf1.nq.gz
    ├── 07091167598233e3b4df156ddd4a7dcae5ca0bfc.nq.gz
    ├── 070d8e901f46d60245003826231e9102409b3405.nq.gz
    ├── 071e9283e953a7219ce8d9ae3d6d9f87f1f65e76.nq.gz
    ├── 073da644d04685e6f3da0e3329d7bae2b44ce737.nq.gz
    ├── 075e2400984409e8afa2b3de36af71b7ecbf3e2c.nq.gz
    ├── 076c14a00122b6ad36c5abb06990eee8969ac979.nq.gz
    ├── 07704af85b2483784a84d84814f630e42fea89f7.nq.gz
    ├── 0777382dff5d6a5c648c6d3e39426540fc5412a3.nq.gz
    ├── 078d57035cec3a143ad6e63f27158557f7b510c0.nq.gz
    ├── 078d927e1915ae5fcc94008926866f80f10eff5c.nq.gz
    ├── 07a21b813e76b71119d9edb911d9b2fbe6da0291.nq.gz
    ├── 07eb49b751dd759b4a7abd7cf46e0291f0b160f8.nq.gz
    ├── 07f8056cccc7b30154eac1a73abac5ac3e7cb92e.nq.gz
    ├── 0806b50af07f471c121e41d09e5a1961690640d9.nq.gz
    ├── 081f3214008d4699baf35cc1f34768433f3c9c6d.nq.gz
    ├── 083758aa19101602d63705d8584f5cbc4da655d0.nq.gz
    ├── 08500dbd7df14a6f026828ce3ef6554adac2eb9c.nq.gz
    ├── 088f8f7fc342fea2acff4aa6237ba24ab4ea200a.nq.gz
    ├── 089de7e7209e80f6f4531f561ae7bed41f36d301.nq.gz
    ├── 08a5c4e2cf6a2a96b449753e320dbaee6ceeb34a.nq.gz
    ├── 08baab0ea3bdb1ecdfe24ba857405e1d70fbdbe3.nq.gz
    ├── 090e85ac65d8706c6cc4a50e75415529d3868c18.nq.gz
    ├── 091e3642c02625a7cfcd53e0e21591ff31b997ba.nq.gz
    ├── 094f9f1e0d64cea35b8e7570cf80a9442cb26ecd.nq.gz
    ├── 09575726be6065d0a059b447372eb1e79fbabd98.nq.gz
    ├── 095cbec1437e7dffd769b9682be4a95d16d79143.nq.gz
    ├── 0972e26e431c61a3fb3c741abcc066879e32bf46.nq.gz
    ├── 099b31466725cc30e0a795cb0f6525d319e44eec.nq.gz
    ├── 09b052bddf11973e825c95fc27dff8c2c9c5aedd.nq.gz
    ├── 09b6db709c83735050222285d9345460daa7d04b.nq.gz
    ├── 09cec8c8e386b9039f0e965f591263357f9e5591.nq.gz
    ├── 09daac036888526145bb1b713403436fe2f883dc.nq.gz
    ├── 0a370fba13156b52403cc6a7241a368fcb32c06b.nq.gz
    ├── 0abed758a8a6c0f0ca22496e341f753c6178052b.nq.gz
    ├── 0ac13c65862500ce7fd351004dbf115de8e6b96e.nq.gz
    ├── 0ae0fcb5c074bf5ab134f72199bca353aeca5da4.nq.gz
    ├── 0aef369876d79e8568bdf8032b545c0f51ca33b2.nq.gz
    ├── 0b09396fc2af0b72a1ee55a867e9153b5613c02a.nq.gz
    ├── 0b2588e09946cf3bad3940eff32a8aa9d2bc19c2.nq.gz
    ├── 0b28f6ea23d4fe145da316641ec85506233c03d4.nq.gz
    ├── 0b29002077cebc3db85dedd9329b220a8566149d.nq.gz
    ├── 0b7b2a135282a78c4a3176a499314dccb08f3bf9.nq.gz
    ├── 0bb5067a2eb0f28893bdbc9093348320d8fda7fb.nq.gz
    ├── 0bb5d6a65086b093f0551de73c9ff1e574a0412a.nq.gz
    ├── 0bd214f19fb2a65a45f05099bfa9932c326d7d5c.nq.gz
    ├── 0bdc0f2217a5f611f30cd74644296e017c67ee78.nq.gz
    ├── 0bde954306e254234e872e362ed862cea0025204.nq.gz
    ├── 0be7054e1dc7aa39bed2a42056776e7b01d75515.nq.gz
    ├── 0bee8a2602584939343d3af0a8ae587383264189.nq.gz
    ├── 0c09641daea23748792dce4d10a0f2b71a002bf6.nq.gz
    ├── 0c307dc3c0e9229f14456482d128e2dfe0fa734d.nq.gz
    ├── 0c3e38095e69e4b158b1507081b04a05855dbfca.nq.gz
    ├── 0c94a4458d92a1555d761406d8ffef5a05de28b6.nq.gz
    ├── 0cf11f911fb9248bb7e787b7956588c5e412caef.nq.gz
    ├── 0d08465c29d48e62133ae1de2fcea03298e4f631.nq.gz
    ├── 0d1a35cd3dab0e01758a45e63e9ec91eccd3584c.nq.gz
    ├── 0d3dce2a7a718478537e6c8b0a9325be7717980b.nq.gz
    ├── 0d7336509c96405861ed5d7e5697e2b83b2bf1ea.nq.gz
    ├── 0db0fea8db37ece335c96c03251483f1616fb185.nq.gz
    ├── 0dbc57bbc5e8dd0a6534e43aed6a32f6dbbb8c39.nq.gz
    ├── 0dd67bd4f51d93614888a5db8967580e638f62d2.nq.gz
    ├── 0deedd632de86a298ba46e3ee218261456a2e71e.nq.gz
    ├── 0e2de1be4bd79cc45a414668c43ec0ce4b193a3c.nq.gz
    ├── 0e2e7ad7d42e9875f70b8b58a72be990236e5bcd.nq.gz
    ├── 0e4fe75176a896d632f526e29357dd4448d1c378.nq.gz
    ├── 0ebecad497d8d58b179ec1803328ce9a5bd165b8.nq.gz
    ├── 0ecf491e8a3c1c3f429223a329a2bb5672519877.nq.gz
    ├── 0ef659e4f9e54bb5320f6c6b48f0f16f80717ffd.nq.gz
    ├── 0f39557dd0873676613b6920822769e566eb786c.nq.gz
    ├── 0f62df4ca085fdbb7b9f3b239656828652560e5e.nq.gz
    ├── 0f6481c7176ecf50f52730aa662c8da2296e11d5.nq.gz
    ├── 0f68b11bdceeacaca45f6215462520cd639a89cc.nq.gz
    ├── 0f9f6c6d9720b22d820507129a2174f4eacb5546.nq.gz
    ├── 0fc4c16e20579136e9ad172d9594455d5575f67d.nq.gz
    ├── 1038c23689054500e91f9342d3027b66e8fb86a6.nq.gz
    ├── 1046a758e9e7a96c50c5062563d7335231436072.nq.gz
    ├── 10a6e568b571126fe2e49e0b66c235d4093118c9.nq.gz
    ├── 10abeffb00b0c8f51753f78989b8791486dddfe3.nq.gz
    ├── 10f3c70557aa3b6dab46a9ce639703d2dc92a46c.nq.gz
    ├── 1157f8808d4d2aed27041dafcea3d74cd95a2d24.nq.gz
    ├── 115f926eb33a922ebb9177afc280fbae8b748a6d.nq.gz
    ├── 1170e4e3ed95c0591d641b7c424a877e48d9f2d9.nq.gz
    ├── 1190b19607d2aec811db143104a3c6f8d94b9033.nq.gz
    ├── 119db93a6df53ef2139d88885e00c03ce2d208c8.nq.gz
    ├── 11a120f30ae08e37a0b1e0ca699d495b96e78609.nq.gz
    ├── 11f59abf52533196c90d0f3f37a25cb534e4875b.nq.gz
    ├── 120ec708daef223086044aec6bce1a9f5f15df17.nq.gz
    ├── 1211e1628a53faef0e40ce5ac87c15b7778ed46b.nq.gz
    ├── 1227adaa47421898f8038667ade1c0563002ac49.nq.gz
    ├── 12377be2c6cdd74ff14bada1084480990213017e.nq.gz
    ├── 124173cce20c35d2b99563605ac93e2766dbaa92.nq.gz
    ├── 12418d49795c9535b85f691697c7e62996ad313b.nq.gz
    ├── 12539cc152b81a531e18d282ae4e746d52630d18.nq.gz
    ├── 126e9d598b9106a5fd99c527ed735930efcaca41.nq.gz
    ├── 1278d956ccb45f094f59f08ee5bbe1f0b4856c86.nq.gz
    ├── 129fd31a5c7ea635518555fecac1e5ebb6a57daa.nq.gz
    ├── 12a6052dbaea5aa6ca1adb5862c33406e9add48e.nq.gz
    ├── 12a7e270d773c91f1167d7d251b2a95584b2e928.nq.gz
    ├── 133e5dc2333037db09a2539e7d39c8d885e72be2.nq.gz
    ├── 134538d7d4d17d1197a0762f83849918ebb48dec.nq.gz
    ├── 134f8b7797fabbca9be9c2171a2c98ccbd6ac4eb.nq.gz
    ├── 139037094872013ac16f80abc2178286f52c4fb2.nq.gz
    ├── 1392615f882bdded3da013ae691641f6f49eed3a.nq.gz
    ├── 13b1a7f9fc2c9b978d4cad92fe9d85560eed9789.nq.gz
    ├── 13bc55f26bb5593cbf2bca158402765d22b0327b.nq.gz
    ├── 13c92fc0e757b7f0d2399efb4224af65ff415183.nq.gz
    ├── 13f94d4aaacc63e015b66fc6c53b247363092c3d.nq.gz
    ├── 141b5ecc7644db7237e5d57ca397ce5d9b787164.nq.gz
    ├── 14252ed5a4e7f822c2564ed5cfcfbee3f503ba5a.nq.gz
    ├── 1426230fbea220c8742da20dfc747709cc41d73e.nq.gz
    ├── 14a7ae3715021501bcf4d49d73f8f5a262070846.nq.gz
    ├── 14efc235e1769aecf25a90842a1a827d2620394c.nq.gz
    ├── 15169952fabd0334af70867286b0b1ed3cd71d52.nq.gz
    ├── 15b3cd98bac03442fa942fb22532e435a318a96a.nq.gz
    ├── 15cb35f7765e81372a322341b2bb1271c5044698.nq.gz
    ├── 15d32b884659f6fbca6b5886bd1c912431f1d62e.nq.gz
    ├── 15e3b55014058b7be08e4ce68310186c8a1324fc.nq.gz
    ├── 1601157ebb7b715ac402e33b40e3743e2050cea8.nq.gz
    └── 160622d6e85dc5182bdd96706a522ccdf7cb2a17.nq.gz

17 directories, 200 files
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

[anthropics/anthropic-sdk-java](https://github.com/anthropics/anthropic-sdk-java)

---
*Parsed on 2026-04-19 by [repolex](https://repolex.ai)*
