# Repolex Knowledge Graph of kvesteri/sqlalchemy-continuum

RDF knowledge graph data for [kvesteri/sqlalchemy-continuum](https://github.com/kvesteri/sqlalchemy-continuum), parsed by [repolex](https://repolex.ai).

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
rlex download kvesteri/sqlalchemy-continuum
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3d3c86bde8fcca29b7232f196ce7525f827c051d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3d3c86bde8fcca29b7232f196ce7525f827c051d
│           └── chunk-001.nq.gz
├── blob
│   ├── 00339ffbf5cfea19ea43a9421e7c4a416cb8716f.nq.gz
│   ├── 0363ba91c943107327496e73a2e5b46e338bfff1.nq.gz
│   ├── 03f1fc4d8bfe104dc13dcec3c8a90381a5c4c63d.nq.gz
│   ├── 045b29792011bf256ef83ebeb07816f816d59941.nq.gz
│   ├── 04c7bc57343507e0b04c76572c92c12814376a88.nq.gz
│   ├── 06bcf243d4a10d3186eb2fe032df483bdef9a9bd.nq.gz
│   ├── 0800cf98f77037f05af95f1874f4ba239de5b872.nq.gz
│   ├── 0a49cefbf0625e00acd05083b3ce1ef82b49e88e.nq.gz
│   ├── 121ac102220d9c5d673eb0294b24576a23d285c3.nq.gz
│   ├── 14304286f137a162b92996ed10a845c8c06d11b0.nq.gz
│   ├── 168bce2c9ce8199d4312812b03af292f89e36529.nq.gz
│   ├── 170d91bc601e9559a77f275e7de76751b7964c82.nq.gz
│   ├── 174ce9179e92d8b8d776b485601fb9d43f448098.nq.gz
│   ├── 18551c9a4ea7d169cae1d398fa64ee1d1406c2b9.nq.gz
│   ├── 1b12f0e24c5332df66e7c71d19979632d0540877.nq.gz
│   ├── 1b4294cb60f0e116aa41ff443c89c9714d8f5144.nq.gz
│   ├── 1dc23f6986ee2dad1a381b20e5f7d8877bbed09a.nq.gz
│   ├── 1df4fdd34060d9d1b6aec2788d0fdcfba792387e.nq.gz
│   ├── 20596f20d6af99432041c30168ddadabfbd21cd3.nq.gz
│   ├── 2445718de3ac6714002a5400acc36ff7fd5b535c.nq.gz
│   ├── 24aa6489d1aeb1adb166c64278829f0d31393930.nq.gz
│   ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
│   ├── 28c3a66a616472ebf9c58a9c56b0cd9e30526b2e.nq.gz
│   ├── 2a689128798bacedda5d1711be6593fee2b39941.nq.gz
│   ├── 2bf21e2f2d55394076993d1d31704ec3f9aef7c6.nq.gz
│   ├── 2c170d8d29314c4421523ed23fb1d23f65b7dbb6.nq.gz
│   ├── 2e00b84ccbaf661635c55e13899447d68d7a283a.nq.gz
│   ├── 2e0dc0db184abff9139812ffa861f204490f1917.nq.gz
│   ├── 30f004399d66c04f6ebf879c80d0cd97d5c681d0.nq.gz
│   ├── 30fbead34dc4ddb59068d9aa994148f70260b28b.nq.gz
│   ├── 3217d16a573e605858179eedfc301cf1e6505d93.nq.gz
│   ├── 326a3820e2939760316af401a4e35f9fffd947e4.nq.gz
│   ├── 32b66bfaa4116fe3d9288b8be475717790256f24.nq.gz
│   ├── 363bd02a6883d7d206d1d82d04c00dd8c6f1b669.nq.gz
│   ├── 39374c8679cfac66fbc157e2d89a31808ea2e6b8.nq.gz
│   ├── 3b6bfc9c254d6b3a6122e0e33c11600da888967f.nq.gz
│   ├── 3bcd27ff462ce41b2f2bb91f86ee79f44ffc789f.nq.gz
│   ├── 3d510348ed908e02efaa0af14ba6a2b1ffbec5f4.nq.gz
│   ├── 3e2a895208b2109ae0e1d1315678756b888ce547.nq.gz
│   ├── 3e9d7f36af3f7b39ff0ba6babf3d3e3a1c39c9c7.nq.gz
│   ├── 458d2c89f537eb6aa95eeda535cdbcd830c3c9e3.nq.gz
│   ├── 4914776f40effa558cc36342ca2d367621538892.nq.gz
│   ├── 4a7f55bf6c68bf9156e9d1bee557d17f60cf0600.nq.gz
│   ├── 4e2b8d701f678fff4aec55b7af3096a8a3403d5c.nq.gz
│   ├── 50e9295ffbabdc7bc21e97301c8f07e23fd1ca2b.nq.gz
│   ├── 518cf57613474ab59c1149cd45dc866fc9539726.nq.gz
│   ├── 51f73fc68a7a51b9c92664690fdff26de7c1aaa7.nq.gz
│   ├── 5310df5a25d53ae0d694130fabb4a94917933742.nq.gz
│   ├── 5341e2e7444dd914cb0ef1ab3528b44d5b8b588c.nq.gz
│   ├── 55a25670753618e831eea70c88b8ff280c4eff0d.nq.gz
│   ├── 5db469718a746d73c2be10e1569c3ecab4ee47db.nq.gz
│   ├── 5dffc7e651890e7b8a9723b62b8806df2cb59a4e.nq.gz
│   ├── 5ea6a27116e34177139024170a31051f028a434a.nq.gz
│   ├── 60bf8cde2ac16fb5217efca3548150f4e271bb9d.nq.gz
│   ├── 639af917341ba2090780df06499c0648450ac0d7.nq.gz
│   ├── 63e0513f1b4a74c710b3c6c6489130f85faa3417.nq.gz
│   ├── 6491bf116ae3a74f8702840ace7c23bd084bd3e9.nq.gz
│   ├── 65d60edc65ff7aa0d35bd910b8e19e40034ecba8.nq.gz
│   ├── 6b14577a7db1d4f00b47b6179baf50b8d71f7140.nq.gz
│   ├── 6ca1e7b89747000952a75d0b5c388709017e36aa.nq.gz
│   ├── 710cfdcda49541eb30551960496071d3396eba6c.nq.gz
│   ├── 724232b3b3e2912e421f33a1c66b4c68fd882bf9.nq.gz
│   ├── 744d00ee7b8be948b29848067f2955a02470e147.nq.gz
│   ├── 76c261f4487216b30558f90df0b97215c9302adc.nq.gz
│   ├── 77e7086a211984eedce52563dd0e88cbd0fdf125.nq.gz
│   ├── 78c780cd8d4b3f66028f9dff3fe1c7927c3e74b8.nq.gz
│   ├── 79354c3c3966adaa988d3f582bfd3feffdf0a5b8.nq.gz
│   ├── 79e3f60193e56d6163ad2fe5123f2ce30fe9071a.nq.gz
│   ├── 7a45fb2913a723e2487f4df992ddbfe05d998989.nq.gz
│   ├── 7a47abd52ca61a29f30287dbbda41043e1e5153d.nq.gz
│   ├── 7c0749bfb825030b2d1572785b1a1b007476bea7.nq.gz
│   ├── 7c1182dc3067156b6403994d37b5414f6454c2da.nq.gz
│   ├── 81ddb7cab4a732bd2680518f9a7a2d04674f1709.nq.gz
│   ├── 82085f0901370868f01c401093d176f176f0874a.nq.gz
│   ├── 83ccfa61989e0045edc0095dbec95df6b48acd9f.nq.gz
│   ├── 8479d8fcee60a693f1790ccaa9c15addbd47cf4d.nq.gz
│   ├── 897f80a0d749f3b788590acc25721916e75e3b97.nq.gz
│   ├── 8a7e974eaadf947493ce301d903e8d41c975fc03.nq.gz
│   ├── 8d76a98f3753e74f9c3cbb561c13fd0f8f499847.nq.gz
│   ├── 95f3a4b23f3d0e1ac6607c20df1f7ba6bd8aa1ef.nq.gz
│   ├── 9bd568eae938e31a435bab4745d031b937aa15ed.nq.gz
│   ├── 9db06c16218aefb487e1102cf0e8f56b3176d3f3.nq.gz
│   ├── a2c65589713f2616379f4066b76820d91ab7c610.nq.gz
│   ├── a7ecae458f4c9cebf0be9c4cf6ab604a6989feb6.nq.gz
│   ├── a82adde29b04d02b0be1c28f8f26daf320e4f668.nq.gz
│   ├── ac665b055e9a4b1d5df1aa0f85c3b1aea293e44f.nq.gz
│   ├── acda7e7bb3bd90c28f5088c11c81eee2e89d07da.nq.gz
│   ├── adb28c064086d394f7100cc92bf5828898db725d.nq.gz
│   ├── af9fe1a2ba8fe193c21cbb5bd2630e02d89835ed.nq.gz
│   ├── b01d698148259f26671d66013109a20b43555514.nq.gz
│   ├── b1576a427c9ddd636df256f2e05989272d4cd18a.nq.gz
│   ├── b7248161e08ba317f16d327172054624665740ed.nq.gz
│   ├── b7aa4e53841f9c00d96450213e367d5a26967524.nq.gz
│   ├── bcfc3936485df0994a73b02837fa317f0a494258.nq.gz
│   ├── bd22ce1b5aef86a0aea3420eb3aebc53b99ad76c.nq.gz
│   ├── c1e1739fbd8b7f4cadac699d534583afd5d882d6.nq.gz
│   ├── c1fe45e0d43dd228f746c6c7620ca14dde250f5e.nq.gz
│   ├── c66401ecbb95157e52204a1658a01d88c523cde9.nq.gz
│   ├── c8f560b530fab08f42a1d34589546332d7203075.nq.gz
│   ├── c9b8fe051772d11a550631c960c74d3cc1d0759b.nq.gz
│   ├── cccc1d8fb6c9095d2aa68c5694ed42b8de9af4ca.nq.gz
│   ├── cd079497270795dad8429c61cb463c64f3a425ec.nq.gz
│   ├── cef34f3f42edcddf56fdaf2b4b2f8d33fb0c4001.nq.gz
│   ├── cf9b4f231e77f3564318918641d56b3b70409de7.nq.gz
│   ├── d45b75e456e608e31b2294df0eda30bf1e2060e2.nq.gz
│   ├── d683ad2615b59058234435d6543fc890247597ee.nq.gz
│   ├── d8ec01cb4f1e2a75226fe4f4d288fe203f7f9cca.nq.gz
│   ├── dea6c652adff86538431b8e6ea287cc83e05a669.nq.gz
│   ├── decb870b1999fb4a803e1b611698d9657bdb3c67.nq.gz
│   ├── deebf56016c58f3e14abd9baa8610098be89971b.nq.gz
│   ├── e4044c8b21b63b5e5bf65652a7723ae0d69ebf2d.nq.gz
│   ├── e59f6ae1ead2d5293923e2bfc98b92d260dbf8b3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eab727dcb21221dc970f45bddfc3cd3502b82d1a.nq.gz
│   ├── ee720ec38aa0bfa1e9184050e196f88e38727f8b.nq.gz
│   ├── ee91e60add7d68ee2a643b8499164696cbbe67cf.nq.gz
│   ├── eeae0dcc9c947a867f0023a2ebe80d1511e19c79.nq.gz
│   ├── ef41451f8727a651514f559bbac1b7423bb5e5b7.nq.gz
│   ├── f005c50d1bd8cbf6328931ba3b8240174301c8d7.nq.gz
│   ├── f00cab7296d06e42fbe0941c6de48155107200ce.nq.gz
│   ├── f163e3a7fa09c9eb57bc3329c89214bec50c3892.nq.gz
│   ├── f234bd2fb108e9adefde95b6f95d3bd416a3567c.nq.gz
│   ├── f2f76c59afcae987f6b14770646a5d1e4318a139.nq.gz
│   ├── f3b8d4aa3ce0391f1eb5399fd92e91def7f9dfc2.nq.gz
│   ├── f402d3ac91c6c39ec1a61c00be61022f073dd3ca.nq.gz
│   ├── f567d99645d88721a3e30b91ee07bcc8577e01d7.nq.gz
│   ├── f75e19248bb483c39d475905ed990622db28a5c1.nq.gz
│   ├── fac8e7bcf79f01b56e9bf62b8c65a42add29ac93.nq.gz
│   ├── fbb8dcc4b3d7df063e3473de16cf492e6aa97ba2.nq.gz
│   ├── fc0963c91cc23d62da6112bc87d63cfa42779c2f.nq.gz
│   └── fe2719567c009ad4ecb55b7cf9a1024e3d5a7e01.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3d3c86bde8fcca29b7232f196ce7525f827c051d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 139 files
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

[kvesteri/sqlalchemy-continuum](https://github.com/kvesteri/sqlalchemy-continuum)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
