# Repolex Knowledge Graph of astropy/halotools

RDF knowledge graph data for [astropy/halotools](https://github.com/astropy/halotools), parsed by [repolex](https://repolex.ai).

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
rlex download astropy/halotools
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ff438dfd61208fc796eb4bd2ba6099429a949842
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ff438dfd61208fc796eb4bd2ba6099429a949842
│           └── chunk-001.nq.gz
└── blob
    ├── 008262d602c7dc4e9940db24dd80ac4cf3f1cd99.nq.gz
    ├── 013396523d72abcba4fa859c2720ce24be23b158.nq.gz
    ├── 0157af1d128b92c810e721165e41e9ea78abab58.nq.gz
    ├── 01d00dd39dcdff4d66868ec5f00aec7c91f2b9ce.nq.gz
    ├── 01d9655dd75d76bdf2edc65bc084494e21007efd.nq.gz
    ├── 020498931842458263deffacb260449a0db2e9d8.nq.gz
    ├── 023501d8303ce0e815bcc90f95be851e5a3a4765.nq.gz
    ├── 0310c64693e339c44cafa6bd5482911a5e041567.nq.gz
    ├── 036435bb0539ae6d2bbdf170857c757b1a036510.nq.gz
    ├── 039c247a0be7b679fb6395cd8b721ce31eac500e.nq.gz
    ├── 03f314655e760798d75e609c4a9c60e0d8ccfeda.nq.gz
    ├── 041d1bd2c00be400e02ca5997363822d327985a9.nq.gz
    ├── 049cf7f669dec29fefa2c8976d2484bdfcc4487a.nq.gz
    ├── 04c7d3251f0c3ac9d5db168a202845ddd2738d70.nq.gz
    ├── 050a0a549914a609069b2a28aac90d61b6941bee.nq.gz
    ├── 054f0f0c4242c93ff01445c7c6d79eb7ff2f1e32.nq.gz
    ├── 0594f79de6e6496e45892ef12031d72cfbfb933e.nq.gz
    ├── 0610a54d48a71c1c353c9b0a8149b1ebfe5d6bf8.nq.gz
    ├── 06746e9328b458e9371e3e4f36b75bf97073af9a.nq.gz
    ├── 0677f75d84334eec5e25f454ad735369a39a872e.nq.gz
    ├── 06ed904aa71f16c092ebef9047350ab7b049cac2.nq.gz
    ├── 074a747d9f0f2279658072e019df3ca7d42efece.nq.gz
    ├── 08c9584971dfebc99e5895af178c5b0d1a591fdc.nq.gz
    ├── 09fe48375c88c66680ad4ac9df565e85ff2a582b.nq.gz
    ├── 0a2a0e819b1f13797cd2972ba801d17f7cbba8e4.nq.gz
    ├── 0a38625eb1ec505aceefb18b41a720c94eec3246.nq.gz
    ├── 0a7134c89ec6510f940e4eb8ffa2d41e92bdde42.nq.gz
    ├── 0bace27d7b8e56de120de5f2b3cad5d31536ecdf.nq.gz
    ├── 0c65cae80249bc5117f4ed329bb003a4f8bad0e3.nq.gz
    ├── 0d75ab849001de47a65ddf536c5784a6730ba21e.nq.gz
    ├── 0da9dcf31dbce95d0bc32814010a71380072d71b.nq.gz
    ├── 0f6bf9f229531e88c79b7af50bfebe68b011ce57.nq.gz
    ├── 0f8f8204bc18f940180ed129f2f287168a2db3a0.nq.gz
    ├── 1011a613031509efe6cfcc7047e4a5f31e1d7646.nq.gz
    ├── 10bcf7a2589ab935cdf7a2a51a6bb8e8a5c10939.nq.gz
    ├── 11532bdfc5dc7539d6cffd9157dd588ecb2d232c.nq.gz
    ├── 119d050f8232fb4ac5b06fa3af3a2aed39421341.nq.gz
    ├── 1261ec7324f6150a61a009d0bf7d714cc00776f6.nq.gz
    ├── 1291221aba387c217e64fa24381825f95bdd9486.nq.gz
    ├── 12cc264c163b172910965fdb23887a65a9ca4fb7.nq.gz
    ├── 1314331927864638b4735443f87f7466a950678c.nq.gz
    ├── 144ffba02153f147aaaba62564f9d8f38bdf29b3.nq.gz
    ├── 1494efc9b91bdd8d8e64fc409f2956f9a89999a6.nq.gz
    ├── 15234b17b11a46ff5b4d37382ed5a49f67759634.nq.gz
    ├── 153b5b980c11d284df980bdd80fa5543da329170.nq.gz
    ├── 154b972b7e4fb6b60f552828edf50de5bdcc44e8.nq.gz
    ├── 16ca0d5dfa1da600debab91a1aed4107b60220d2.nq.gz
    ├── 1777e6424ddeac8e480123233c5739daaf59a3e7.nq.gz
    ├── 17960825d2ac9b73ccddbbf4eceaf1f8c4275c2a.nq.gz
    ├── 17b03e13b13841ba3b0c7bc9309ed00e81e7c681.nq.gz
    ├── 17e55f7a7e0817f11f21bdb87e49f70bd14dd240.nq.gz
    ├── 1868fc70dde11b9d530e2d488bc8297b49f11b6c.nq.gz
    ├── 1a278e582c5493037eceeae967072cb632f4237f.nq.gz
    ├── 1aba80903bef86d0933d75037f4f9b10a5b0fa87.nq.gz
    ├── 1ad5677a012b9bbab17159cb2589c0b7e9cc522b.nq.gz
    ├── 1ad5accd26a6adce66b1e6773e52daa624db3ecf.nq.gz
    ├── 1cab463ead26390f91dd572dd2afeac1e4dd809d.nq.gz
    ├── 1d723f17b0fabf1f1d76ecbf40bd6ac80126754e.nq.gz
    ├── 1e2b8f410ac088ff414bc3f7a2a293f863d0021e.nq.gz
    ├── 1eb0bae8fc1ce4c9c1e11614d09f4b3db41ba996.nq.gz
    ├── 1eb677e602651da0914f79f300c4e2cb5efb79a3.nq.gz
    ├── 1f5cd775937849a060bbe65da1a99db5d22105ee.nq.gz
    ├── 2039439f745b2e00e01ce91c27506f080b2512fe.nq.gz
    ├── 21bcbcb8b7a7d75e1bf73dbe9115da361caf2126.nq.gz
    ├── 23f98266357e443086e68b5e1b0550f9fdde30df.nq.gz
    ├── 246e6ac29ee744caf8f498f7ab2aa1baafaf464e.nq.gz
    ├── 24c4569e6f1f2034d4de2243011bea03ffdbbe54.nq.gz
    ├── 24cfa637023cbf279d1bd02f24111771d1295714.nq.gz
    ├── 25de95c335138cf666f3be3e01ae620d977097a8.nq.gz
    ├── 262d3ea993665de881300a37443b40a47b12e9e3.nq.gz
    ├── 26390424fd09b8cbd51049c08c6bf451db04a394.nq.gz
    ├── 263b6f4c0714d3ed2c21fd7fa999b487444c6d02.nq.gz
    ├── 26baffaadab2979b57998cb72c56eb8016b73e7d.nq.gz
    ├── 2721efbf6998312e3022f7945cb8f73b16d04602.nq.gz
    ├── 2763969d74221844cd48454c83c449d14d780c34.nq.gz
    ├── 280eb461b549a935bda0a50c74a35e0f7a20326c.nq.gz
    ├── 281d4c4f31a8e949e9d0062085163d3bb7548991.nq.gz
    ├── 2a74b0b8142fb6bcbb32fe26abfa24faca817277.nq.gz
    ├── 2a8e27d1905023f0da9eadc71e454c64451432fd.nq.gz
    ├── 2af0bb9ea1092b889eeac1a41df2bb37254a5512.nq.gz
    ├── 2b0a6ebcddd68250970c72d818b0281ebb60fd33.nq.gz
    ├── 2ca84e51dfc0fe68eac5b7f18f443b032b49ebae.nq.gz
    ├── 2cc5e1dd810125a5e2d601aa471c01dc03c5e250.nq.gz
    ├── 2cd5973d706f13c466e7c5ed1aa5ba3edf3e12b4.nq.gz
    ├── 2d8b18f22c3a1c8a0c22a028cd4f7fb4215b8a83.nq.gz
    ├── 2e1bf48ea1a0a680879a5f42ffa0a14140959646.nq.gz
    ├── 2e6892ef0d4c0c762abd1dc5b59096da5c5e1e48.nq.gz
    ├── 2f37a33030af582a306dd47694136f6e145476b3.nq.gz
    ├── 308e3c802b4020f08debf1a029395fbd6443c7b6.nq.gz
    ├── 313bd9773facefcb13b26ef1db137c98d06aa7ba.nq.gz
    ├── 31ed2e657f47e20e4f80a9950adf118ca3dc1221.nq.gz
    ├── 3309009978c1310f989f4c6230de2d816fa91122.nq.gz
    ├── 337df81cac27d46a2bbca00b20cb22cb99f9daaf.nq.gz
    ├── 361b8b9395a07d9562830b7abc62334aec807821.nq.gz
    ├── 38a5f7b5da833a920d01f9d34f04cb7ab5795836.nq.gz
    ├── 3915932fcc83d47c5ba1e0a238a5cf213e53e3f5.nq.gz
    ├── 3927c9f37d936f9e0b127062509c515e7a2f0ec2.nq.gz
    ├── 396d552b5da35ccba1663d99b5ef3900fd114ad0.nq.gz
    ├── 39d14f98480656ade263eaf7c6b4a83369405da9.nq.gz
    ├── 39fc3cc96f2e61db2768e96d940a84f65703843d.nq.gz
    ├── 3a39f980986b7fdeca6ffa4b191dfdea3fa79739.nq.gz
    ├── 3bdcb601e6c1ee1fc52b4efa6ef3309a42b2e246.nq.gz
    ├── 3ce86567c25a0508357f92499597d8aa328be26b.nq.gz
    ├── 3d6d1078354d5a3ce3bdc391fe94d255b21f806f.nq.gz
    ├── 3dc6fde30c110bccc65e34adc2bda71f6e3e67e5.nq.gz
    ├── 3df1b76ad2deb759c8e2c9be76248cfd5627d10e.nq.gz
    ├── 3e2e85091f4576c3e5ec97bf5489ff510dd6b50a.nq.gz
    ├── 3e7ce26f8758084db865e676e1220a721f42285c.nq.gz
    ├── 3e7d6661df4f4a47858b76182801063ef1db9c2c.nq.gz
    ├── 3f2dcc63ec1dc49c3ca273827fb20e282e19abde.nq.gz
    ├── 41df965ab2709773a26755036a33c14272d53a6d.nq.gz
    ├── 4276387fe675bd56d1f642ff5311a6d6f5e1b973.nq.gz
    ├── 4299910ae8400f3411abe69cd2604c1971b510e7.nq.gz
    ├── 43174b0cc37e4687628fd8ee0985fae7528c1be9.nq.gz
    ├── 431cfde6644bec6c9a48c89e74ea4470ab4f0af2.nq.gz
    ├── 43255eb28dd204e3bed2168131bb4b434223d30e.nq.gz
    ├── 43ddc10a95fe89eabd222d00f4d68eef593efc62.nq.gz
    ├── 4411c6c9d938a96d093dfdd67635ce8f1771f2c3.nq.gz
    ├── 44155151d3f7d719ce54bc1fb58e8d396488d5d2.nq.gz
    ├── 4570df4bb23907bbea7fad1d2e342544e2822ea5.nq.gz
    ├── 46193cb87d9983e75d21a77b506b43e620e854be.nq.gz
    ├── 464c3ea8357f3b54f68fdcf7abcec285232b6dd5.nq.gz
    ├── 4798625d127764d39507030b0fa8563319aea892.nq.gz
    ├── 480034301021785af178965f64705d982db3cbed.nq.gz
    ├── 48c9db0757500388f4fc691683ccfed8c1eedcca.nq.gz
    ├── 48db97341e5ea4fae05ffff43d3a3a137618e7d9.nq.gz
    ├── 48e5ba5c6d747fe0770f8a2954f9c82f267d994d.nq.gz
    ├── 48f47cf4a91c4b75e0adce086eb1d496ad99755a.nq.gz
    ├── 4ab53cdaba35904336192b1245df7ba8d519866f.nq.gz
    ├── 4ac478638285654ac9520e71281a3b55693cdbdf.nq.gz
    ├── 4afca1f8087c9c7ee6858e247da8ded5f81e5f8b.nq.gz
    ├── 4b606ec9b344515ebf8657e3eb0a60ba328304ab.nq.gz
    ├── 4b698aea02141662ac352a4a11c099143a7373b7.nq.gz
    ├── 4ba19b006e80b0d03b37bcfcd2b11819519224e4.nq.gz
    ├── 4bf95c2365dc96b5574362efd65d4f266a04b3ab.nq.gz
    ├── 4cb0d61bf32d9d81e496c7a659bf599b48c30d19.nq.gz
    ├── 4ccbed8142e3d21d23448008f1a5ea69d8f5d431.nq.gz
    ├── 4ccc6521399209b87594d7b441bb5a1e897584da.nq.gz
    ├── 4d11028136be8c44bb0fc245e567bf747937df50.nq.gz
    ├── 4ee2fdc7a6da0c12f648771d5ea46f9c925df290.nq.gz
    ├── 4f2a83df667a0bd29abd2e1074b3f97210d8d5a2.nq.gz
    ├── 5010830614db390f47a0c0bafbba7bb18c1a116f.nq.gz
    ├── 504db3a5c5c5fc29a1e608a0996f8868caa1697f.nq.gz
    ├── 508b164bf41a947a43870c1c6525aeb6c8910af2.nq.gz
    ├── 50fbc935430bf02f73d3547eb513517cd78606f4.nq.gz
    ├── 51274f7049e667ef4a742c1696f35e48fb69d33e.nq.gz
    ├── 513852ede4a7fd35ae2f6934c3fcd8edec6ad8b8.nq.gz
    ├── 517711f3112d151563b5154806a2407fb0438aa0.nq.gz
    ├── 528ea4e0c811d1d03893fab7b85a4825d2eb8637.nq.gz
    ├── 52af25ca14485943e8202d728ffe2492d17ef501.nq.gz
    ├── 530fc5bf09fb6221e4d5f324c6615738a3a08bdf.nq.gz
    ├── 53619da7913bc3af35dbb098f4b66aa1e29a6036.nq.gz
    ├── 539c2e6f5e0ad4890e540288f5eb57b86a4cd8f9.nq.gz
    ├── 5411669f03fec82f9846bbf323506f070ce40869.nq.gz
    ├── 554faf1fac72e652a7b81cf49b9f53a1ae4460fa.nq.gz
    ├── 557ca27099a275d88501a791f500074d94bdd961.nq.gz
    ├── 569c7ccbf914a40d77d4c2f7007f3e0119631a56.nq.gz
    ├── 56e7e242204f8266c57d5a58886e444e681fe63e.nq.gz
    ├── 5720e9caac0fe908c407696f520bc051b4d0c757.nq.gz
    ├── 57fbe2f648f3d2557433a641ede5f758a38b3c1e.nq.gz
    ├── 58b07c84b7afd6f22d49ca9f45879e85b23bea53.nq.gz
    ├── 590b4fe853ab9448c54d7f69c068073a17860a4b.nq.gz
    ├── 599377f3dd30abf100b610f7155f2546b2b6e3ef.nq.gz
    ├── 5bb5c7d1a6bdb40d6bc51e3b681eb4b97ddbac3c.nq.gz
    ├── 5bb9bc82c9543aa3016bdb12a6ad3c0c6c246e0c.nq.gz
    ├── 5c403388b0364462315da2f2a8df4382d56f9145.nq.gz
    ├── 5eef00d7a37855d150297c195332827d3993f13c.nq.gz
    ├── 5fc8b09d79917f939ddc5d0faddcc4d60d2c2e18.nq.gz
    ├── 60334b5b99ee918a5859c832e5ed5c2957a51603.nq.gz
    ├── 6061da9ddc53ec539fedfaa3082a17fa540b5236.nq.gz
    ├── 606776e1b76ba73ba9260336d1e9380e1dcd4c21.nq.gz
    ├── 607403d6c07554432a6508fd5cdade5d454e5344.nq.gz
    ├── 611b39a42c9afd0f056cddf142d946c99e74a0ab.nq.gz
    ├── 62082254929e13d941f88aff9bfcb86af42afcb5.nq.gz
    ├── 6417499bcc0d13b6491be7a109470afd6984661f.nq.gz
    ├── 66a26e665a5d8b4f52acd6bfaa15c1283798d514.nq.gz
    ├── 67d40e09ee309f410b1368b4a5fd1c661f09cbdb.nq.gz
    ├── 682a4cd49e5abb3b3720aea2aa618b4ac44dfb05.nq.gz
    ├── 683bbde1dbf5e79ecf07925e436f4e223b70c608.nq.gz
    ├── 68e2c1adcfb53d9a31899053a8b437d6e4434db8.nq.gz
    ├── 6ad0e20c684c0ad38a18db6f0dba221513c52284.nq.gz
    ├── 6af36c44ca7aafb831006e7cf02d44a7ff3a7ef8.nq.gz
    ├── 6b0c235992bd42858029a97cf48d4950a1438b9a.nq.gz
    ├── 6b214a5c09d3a2ed5399a65ba6100bdfd0b070ca.nq.gz
    ├── 6b7e682185fb7d4126b5c87af76543fb62b5e703.nq.gz
    ├── 6bef3ed5cb21b14c1a9da8c40b9889ea7a57b1af.nq.gz
    ├── 6c252bd24716f320b610592b1ce22100e0b4704a.nq.gz
    ├── 6c50a9fe2b4145265c81807f296f3c102689408d.nq.gz
    ├── 6c6daae78ddf5c621158d7f4df55be6fb81524f2.nq.gz
    ├── 6d3adc6568e8299a13a802c726de45f20a3063ee.nq.gz
    ├── 6e4d332314e86fc794678fb08ae607f583127e9e.nq.gz
    ├── 6e9b49ab4b4530c978fc86fcdf798f2a146b3c25.nq.gz
    ├── 6f02a56477c44f7b131b3b43bed0669c29b80f41.nq.gz
    ├── 6f0c362ba9149058a59b76ce55c1a8dc6a5c5fff.nq.gz
    ├── 6f41fdcef4d7cb761957efdf6ae596c990b428a8.nq.gz
    ├── 6fdccc6759116cc312f6634d3c3223d5b4fc9d4a.nq.gz
    ├── 70a535547cf3087e26c584f89ff860bf9897ab08.nq.gz
    └── 70d90561db74eb4560045936fca11e3266240c10.nq.gz

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

[astropy/halotools](https://github.com/astropy/halotools)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
