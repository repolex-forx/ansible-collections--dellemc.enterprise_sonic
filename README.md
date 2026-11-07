# Repolex Knowledge Graph of ansible-collections/dellemc.enterprise_sonic

RDF knowledge graph data for [ansible-collections/dellemc.enterprise_sonic](https://github.com/ansible-collections/dellemc.enterprise_sonic), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/dellemc.enterprise_sonic
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 46eba3b9b53e0779f214412f84f4dd3acd929788
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 46eba3b9b53e0779f214412f84f4dd3acd929788
│           └── chunk-001.nq.gz
└── blob
    ├── 000b5ec541021f339c6e180dc6dafa1b81c915d7.nq.gz
    ├── 018f5873c4d02ac61a82d1caff0c28cd481ee68d.nq.gz
    ├── 0191b619528f3e815e087c2377e92dec9e67f549.nq.gz
    ├── 021507f5c3b16bf4f6529648962793a8707bf997.nq.gz
    ├── 031546093ebced2098bd820c93fd9f780f82d964.nq.gz
    ├── 037c834c6ac7353366f1b317f9b4a9c6daa99847.nq.gz
    ├── 03baed8c4faee6d6f925ed44090f621f3954530d.nq.gz
    ├── 0447e1a90b1d9f895d24c1b87dd2335c762e9348.nq.gz
    ├── 0473ac7586608ed19b3690c915f5deab99a4554e.nq.gz
    ├── 04b09288c82585918b9e741ad317baed03efb860.nq.gz
    ├── 04ebc993629efdf7bc4bb5e15ab917e8f3904628.nq.gz
    ├── 05403f47efb8b5d888c948fbe5176e5dbbe5f750.nq.gz
    ├── 0617d6a3185e21ce9b618d60a169ddaea3e2ce42.nq.gz
    ├── 0682a54f1bcd9850aaf0b6c7abc8137b67c63287.nq.gz
    ├── 076d1c6cdfbda48dee1ac5c6d404c14533587168.nq.gz
    ├── 07b5bd5d8a4b9281805a4a09daeedafc68a7e99b.nq.gz
    ├── 090defcd051e76ff696dbe4d5684754a7e0b3300.nq.gz
    ├── 0aee8310564a9145595dd826d080a152f893eac2.nq.gz
    ├── 0b0a4c76f626987aa9dd6f8a6d80db658bc76f15.nq.gz
    ├── 0bddd68012495cd99e326d324b05720c315e78af.nq.gz
    ├── 0c4cc4daf2e26154e977f2e9e150dbc0fdb02efb.nq.gz
    ├── 0c528daa7cf1b04215da0de02dafc8560d7dd45c.nq.gz
    ├── 0ca834487fa60920118ac6e3ecae18843c2f607b.nq.gz
    ├── 0ceb719454633d690f66eb83eac042c97ca82ef5.nq.gz
    ├── 0d357cc2e01a5efd753173ef810de3da0ec90984.nq.gz
    ├── 0d507323009b73575bf12f23c57df1079cf8feec.nq.gz
    ├── 0f295c9477270782717cf4c42860c52f0b09e814.nq.gz
    ├── 0f2e8201ff3a4d189df56e25631a7e1def66c3d3.nq.gz
    ├── 0f402ebb0768970b7ff2e8a3cb8b583d0ac0d810.nq.gz
    ├── 0f53868198262ff7a73b11727904a476351f9189.nq.gz
    ├── 0fcf175adf4fd2f022b9b0862433e97f919a262c.nq.gz
    ├── 1017810d347d8a55c10c773cff14a7b8dfc1d016.nq.gz
    ├── 1089b8be9de6b9913105fdf77bae5c7b6e24d662.nq.gz
    ├── 1098075cc246f8ada238b2ea47a8bf5b1f46c140.nq.gz
    ├── 10fcf63105f915b2bdf2497c6e5584b8bf31c1fe.nq.gz
    ├── 124bd4b7ae62401512fec26dea0188ebb35f1fd5.nq.gz
    ├── 14ae0377eefa33c46688dfe20c1319ecae4ed567.nq.gz
    ├── 14ef8484bb44568b2cec16a89e0cae29ff13bb58.nq.gz
    ├── 15ba7a45fc0b5cf411cd83a16257f89383048ab0.nq.gz
    ├── 164bd8fbcb7de9bd5c7b173d8e2ae099b0b3ed76.nq.gz
    ├── 16b12768d9d78128432fd008eea08a451ae47ae1.nq.gz
    ├── 16e164cbd70cca4f63ff3a03b57df507ac7694f1.nq.gz
    ├── 177ea6ef57f469f2dfb84ce3abf89a80180fd838.nq.gz
    ├── 17de2eeaecad6291dbbeccb456c169e7e33d8d8e.nq.gz
    ├── 18096164e31bbaa9f84ec7f092cc841fe69744c0.nq.gz
    ├── 18837c3cb7e1e27d6b49df10f5836ea192e923ca.nq.gz
    ├── 197a4b81382967a3e22482f819d5fae736a16bc3.nq.gz
    ├── 1a0dee0a1a824b0e9ff580d47f544343b6a8bec5.nq.gz
    ├── 1b7fef0c554c91b93bcf4d1b7c7467ff9eae8833.nq.gz
    ├── 1bdd544cd694fb193bf0b2b6c9ddea9ff3362297.nq.gz
    ├── 1c91dfd30614f3e52a95a7d063b61a0caddd0c46.nq.gz
    ├── 1d27a34b5c476d90877ce8bd4010b01aaf6f827c.nq.gz
    ├── 1e21b86abab23e296b4722a8d81a4a72fcadda0e.nq.gz
    ├── 1f49fa4a02303228c0a8e6fac886bfb606aadd59.nq.gz
    ├── 1fea0ce3d5ec0a1c966b52dfdecc7a60d920834f.nq.gz
    ├── 2066573655ba06b41492770909ae5e4b0585884d.nq.gz
    ├── 20f79fdc8ee0089bdff2d3e4f5f140e44fa646b9.nq.gz
    ├── 21252dbb9620901196267e4c2985b8686f635af6.nq.gz
    ├── 2171d48b284d2965c7cd2019e9d34ceca6a456fc.nq.gz
    ├── 21da1c3168a9a1bf5401137ebbc4a356cfd345bf.nq.gz
    ├── 2528e191450922f4f83e90cde14c87eb662dea6f.nq.gz
    ├── 262dd3ec0745fb11ba610b1d4d5643f1d4cf5342.nq.gz
    ├── 26364dd843f90087fe8282e48bbcd6c80879f9d6.nq.gz
    ├── 266f63f0b81712312bb51005fd416ab72ae21f91.nq.gz
    ├── 26f77bad736bab91182e5987dade4e3f45ca71d0.nq.gz
    ├── 273682ccb4fa2fa8015c56502d7110ee11fd283c.nq.gz
    ├── 298e92cd10b93601f9dc2e0bc3ed4164b6f3aaa1.nq.gz
    ├── 29cbe72970449460bd2d3ca19f0c2e72dda19c32.nq.gz
    ├── 2a517211824c7729110ac5bf9836c69447304759.nq.gz
    ├── 2a5f04a4562c6167d0ff5478e74da12178d0d4ec.nq.gz
    ├── 2a67f8386fc6a7d933b8469e2b8b4b46222a3733.nq.gz
    ├── 2b20056caaa890be7f4138ba3e780611c11279fa.nq.gz
    ├── 2bcb16a50c74deeda6422a8ddc6b69f61bb07dbb.nq.gz
    ├── 2bedce46f69b224a48e3ded06357523c7f9f6c34.nq.gz
    ├── 2f4665e1e0e7c3f4367942b3ec8b1628defa57a2.nq.gz
    ├── 2f74a29e2ac38feb45c60cefe1398d4326b8f11f.nq.gz
    ├── 2fd21a47c1f31e391a10906f984905edc08f65d4.nq.gz
    ├── 2fed00f0cbd1acfb03bdc16181b9214b1d24cfc0.nq.gz
    ├── 3109bbcbc82e1a7468e23c128f66ed8f2750fbb4.nq.gz
    ├── 31cada350b9770da7306db3663ff1ab2596c1e96.nq.gz
    ├── 334a657be2888aee5443526d594d6ca3822509e4.nq.gz
    ├── 3360bc5c63d9d1dfe8aaf6babf18b000876d8082.nq.gz
    ├── 33ce85d80795cd380e5209ea574189b3f4f4c0ce.nq.gz
    ├── 33ef079e27362df5728a2df19698e1ed55ab3dc7.nq.gz
    ├── 345920aaa6f5409bde0f53f027962679fbbc57bf.nq.gz
    ├── 347fd2c56387664829724957ae517c56c011207d.nq.gz
    ├── 34a97fa2c095b31f4a1616f5cc2a95bfb8326e48.nq.gz
    ├── 3630e01c4ebbe42750b88df4113a8bf0dd3dc181.nq.gz
    ├── 367d3510a1de076bc9ac7818f99f55b1e2295e5a.nq.gz
    ├── 36f47805b552663b13a822a7195a35dab8d5324c.nq.gz
    ├── 370a5816d6c62dd92f4333313279eb801576c6d0.nq.gz
    ├── 380faba441cb631c0e7ef43325c83cd213a257a4.nq.gz
    ├── 3833030b2ca41ede56f2a7be26a98eb78644202a.nq.gz
    ├── 38a1b19ad249938b9cf9535a745e916b07ed8b41.nq.gz
    ├── 392ebeb87a367569864f4146f185215659c12f33.nq.gz
    ├── 396c392ebcdbb12032df1bfe3e8a2a11dc7ae0bb.nq.gz
    ├── 39711b246c9f86bb33f037effd52c380cdd97d24.nq.gz
    ├── 3a129c2410901f53ba696bcbd885aa16380fd49c.nq.gz
    ├── 3ad1150c0c54b42219c91ea90e46e7adff864e37.nq.gz
    ├── 3b5949d151032f10263ba5a8657156d0df694a63.nq.gz
    ├── 3b7ad2c61b7f895276fd4cee09b523ba812386e1.nq.gz
    ├── 3bd0b516b7a5e7d6fba3334f0a96c7ffd6420124.nq.gz
    ├── 3bd9607612ddc5c06e5852cff0aa78eefb342cf1.nq.gz
    ├── 3c21849833ca8b4002d164e462377439ecc1a63f.nq.gz
    ├── 3c49eda792b58587ed0e620fbf972583f178f491.nq.gz
    ├── 3c806bebf0e1ef853d895c33165583869ab4f285.nq.gz
    ├── 3dbdaa17849ba50267ae483a8c0f7459ed303178.nq.gz
    ├── 3de7cb9e6bd6a9d2469cb7cb8f79a8440c52efae.nq.gz
    ├── 3dedc6c8326dd45d2b7f99bd4ccf404cb1313b01.nq.gz
    ├── 3df1c6a532dd01c2452bb46c148c8c54ea07e16d.nq.gz
    ├── 3e1c44031a44d1c0c137abb3aed54167784811ed.nq.gz
    ├── 3e4df1809a5e3652bb8636190349eec9d77a66af.nq.gz
    ├── 3e5e26434edb41d191995bd85d918633967b83fd.nq.gz
    ├── 3e65de00f6f64066126fe3a7354c6e7cd03d0e87.nq.gz
    ├── 3f5c7d7257f865dbf532366a84cc8065d1b5fb50.nq.gz
    ├── 40982c232a199dd33457d72517c9dbf2fd47b0ba.nq.gz
    ├── 413ea1be6c564d7f62dba8989f355b9561a42c68.nq.gz
    ├── 4175f381e7e928e8bb80349714eda9cce1c711a0.nq.gz
    ├── 41a3185593727611417119677b7c6e439dc559dd.nq.gz
    ├── 41cc5e9d44c4272c93430d2faacd696bdb26d046.nq.gz
    ├── 42322b31679e85233b59081778b2adc61fd79070.nq.gz
    ├── 4259dabb3f08cd780a7d513b827bd4a771b0c9d8.nq.gz
    ├── 42980f215043850c6f3de4b4de4619ec2b289910.nq.gz
    ├── 43b99fe1125137a99af16d23e9aa57df57ee5e52.nq.gz
    ├── 441721a933a239b6730fd5550816cd7647977832.nq.gz
    ├── 4434efce166494fc3371a17ec6bf159b7886a28a.nq.gz
    ├── 45f7bf480fa5f7893970e7e1d5f52249590a7772.nq.gz
    ├── 460aa80e4c9e8d190791b5b638c470c84f623031.nq.gz
    ├── 4686a838a2d5c284cd1b0bcaf102f093b2d5c0b3.nq.gz
    ├── 47249d8b42600f85d37d75099d9cfe0972ce7f53.nq.gz
    ├── 4749ae6888e03ed8e7cb299f2443fdcaeb49e923.nq.gz
    ├── 47c14787cd3683a54ef3b3243e09738095c8475b.nq.gz
    ├── 4ad92f10512eea09f030fae5bd10e9e88a9571f5.nq.gz
    ├── 4b117d25dd138965f765e354dc421b0094d299fb.nq.gz
    ├── 4be428c068e2c6e4732a9f084a4ed62e52eca6eb.nq.gz
    ├── 4be5c64a7a141fb6624bf47dacffc810e6cdf0a6.nq.gz
    ├── 4c4fc8464b833b35ee0943c70e7e3d9a09815fb9.nq.gz
    ├── 4c71d551965baa262c2472ff959d479091f3b361.nq.gz
    ├── 4cee6182bc3443cef8b1c77e2295127f3df64ae9.nq.gz
    ├── 4df4761c438f7aeb4271e723e69a655e9e77d7de.nq.gz
    ├── 4e425ff1a900f99c148d9897f8aa21a69418ed5a.nq.gz
    ├── 4e8b3a71a93436e63bd99dc6131f01539bfe0ece.nq.gz
    ├── 4ffac4a6a013c72559e7f4e82d1485cf0f35826f.nq.gz
    ├── 501ed0c4ef5a70c5849411b6742ce9aa56e36b5b.nq.gz
    ├── 51046f0a9b9ff3e62fc5cb8029be4350befd88b6.nq.gz
    ├── 5241da8408ee7d42eaf4a58ce1a7c60eb9a90068.nq.gz
    ├── 533e70a84e9e6249c87026a9a2ef52ecde888ebd.nq.gz
    ├── 53c9a0836051ecbce4acacc8f93c6d32c718e942.nq.gz
    ├── 53f37860851bcab8cc37172c2c52d15818b13982.nq.gz
    ├── 546d52b887a5e6bd5b3ef9cbac20a0f6765c0ad8.nq.gz
    ├── 5677fc5297bc5ddfc1228c0fc37490d7b95d2a99.nq.gz
    ├── 56e2afe2774cfc2e1c6f59f125e50f97095ace97.nq.gz
    ├── 5749d079d366725059e56a77602a65d8cd23e880.nq.gz
    ├── 57bf9f1f8bc6816e65d71081458ed0e9da079fbb.nq.gz
    ├── 5857eb8d2cd9d4f97a99fb5fcc731813917ee635.nq.gz
    ├── 5abe70b972737e3f2466018e5a682e53fbe60a64.nq.gz
    ├── 5ae9e3d1d9251ad861087734d8a1d5759df22ed9.nq.gz
    ├── 5af570fb2b472ff480dc0ac71c5ef55ab7bdaf12.nq.gz
    ├── 5b770a7ea2a48e2260b440a45f342d9d519195a5.nq.gz
    ├── 5bcc5ca26e75c2f04eec34a6224012c306e04998.nq.gz
    ├── 5bfc0fab67c47e6aae928d8bf198c4d3b61e8b01.nq.gz
    ├── 5c24aa1bf468deae159bb6a6477d3e5739707397.nq.gz
    ├── 5cb97f8972d61a671fd345e4a0bf7b6ec13f3585.nq.gz
    ├── 5d18d9a28cba41e95e5eeaa7b9086aaab0275a35.nq.gz
    ├── 5d7c0318fb2a299351c961f008330823d3ce76ed.nq.gz
    ├── 5d97a4f6e42e92573456ef182a11d905998c313b.nq.gz
    ├── 5db3c0c56ddf0b40ba4a9e8555f87f6b97e75b2d.nq.gz
    ├── 5dd0e5db474137f0dd236d78d654d43f4b9f1b41.nq.gz
    ├── 5dd482e12d85c3a237f1dfe02c45a1c181297fb9.nq.gz
    ├── 5e3293b8a7d181f0b2b6580c28eaf0fd98291c51.nq.gz
    ├── 5f7ac3a821f0360eae9118f3007e1bc3480d253f.nq.gz
    ├── 5fd2299b692fd6b5b182d3d6403070d5431101fc.nq.gz
    ├── 60678c39f1d7d330ef037e09e479ef431b33fce6.nq.gz
    ├── 60fc17f6ff6a19c57080e7fc83166b9cb3d88f7c.nq.gz
    ├── 62683d50ef81c67cc03dc688d0b635cedab6f395.nq.gz
    ├── 62eae56ee22b005bb107f38210c18d1cd7735054.nq.gz
    ├── 6371328cf160754f0f77153949856e095c54b517.nq.gz
    ├── 638a209a9fcaad5a182c369bbeb25645313721d3.nq.gz
    ├── 638dbcefcab4dabad52ed5a2850cfd95920a331e.nq.gz
    ├── 64451a890fb76a2ddb3d7a159b0c7f1b8a17dee4.nq.gz
    ├── 647a2aa13e4143b70df0fc782559284e323fa3c2.nq.gz
    ├── 6544aeb6eff4ece382e6fe20136b7fdd83ea45be.nq.gz
    ├── 65f384a1ecb32a4607dc7fabe5c954e7fa2f1a2a.nq.gz
    ├── 66323d75511a5cfd6da86ae314f805b34abf020d.nq.gz
    ├── 6645e936aacf7d82cfa3c377b574300fb271865e.nq.gz
    ├── 66b7e14547bf7c64f78589edea1f73c661bb4307.nq.gz
    ├── 67bf307e91ba54c312af905b2c49b3483f9f8d14.nq.gz
    ├── 6974d58bbad0f4e8b9ab18a45c6d9659113c2aee.nq.gz
    ├── 69d67ff9def32368cad0054c592934b66d116b4a.nq.gz
    ├── 6a0feb488bd720f434b523ac4224c81f946594cf.nq.gz
    ├── 6acbafbe6f247d705b62a61ad360d22d21822005.nq.gz
    ├── 6bf8622a4b9d2862c6d965f91a82b0487129c9f1.nq.gz
    ├── 6c17a4ce819d17316dfa7e05d748044f4152d0d9.nq.gz
    ├── 6c71b4dae502529acc4774b7a1388b9111674f0f.nq.gz
    ├── 6d23d2c1e1f34fd1cb1bdf134c69b367f7083a6f.nq.gz
    ├── 6d6237a283358cda504d189209e89e13bf588fca.nq.gz
    ├── 6d8ddba7ba69326159361518fe47093950228151.nq.gz
    └── 6dc4c6d436d49cc2366da781031229cdb3549dad.nq.gz

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

[ansible-collections/dellemc.enterprise_sonic](https://github.com/ansible-collections/dellemc.enterprise_sonic)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
