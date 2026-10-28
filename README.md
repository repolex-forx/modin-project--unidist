# Repolex Knowledge Graph of modin-project/unidist

RDF knowledge graph data for [modin-project/unidist](https://github.com/modin-project/unidist), parsed by [repolex](https://repolex.ai).

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
rlex download modin-project/unidist
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 84dd28ba26c667523519c2372c6fec01881e7c39
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 84dd28ba26c667523519c2372c6fec01881e7c39
│           └── chunk-001.nq.gz
├── blob
│   ├── 0144ca6742e2182f4e125010162c734e2ff6f6ff.nq.gz
│   ├── 03a9ebbd2129884b8ddd5614c810f2d363df41cb.nq.gz
│   ├── 058ae37995652c8f60dc5f2e5119a6417ee4477c.nq.gz
│   ├── 0685fa279c995959e031d22ba57b9f2a56d188d1.nq.gz
│   ├── 07037af4a2260294433b1bd3db52433916726be4.nq.gz
│   ├── 0772844dac19062d29b625b9c3d900a445ba4e82.nq.gz
│   ├── 0a09447c9a3d76c716618b8ef97d78a2e6971ad1.nq.gz
│   ├── 0a3c9c17e5dd030761113a634bd87d737c2ec723.nq.gz
│   ├── 0b5f7dedff03cb5ac4f2655cea327cc20c8d50d6.nq.gz
│   ├── 0d786cb9cf22bc1ab8825c41e0dcd2c31955fc52.nq.gz
│   ├── 0e179e7333562f1d52ba55ec23be9b2678924cba.nq.gz
│   ├── 0e66311ce3d67d6dae18c75d0c82743b0deffef7.nq.gz
│   ├── 0f326c00a2bbdf44bb54f31d87e6fadbc4b5a4e4.nq.gz
│   ├── 114b9e9b3626661fbb213fa51b9c21a1b6a03595.nq.gz
│   ├── 17d0063ae322a3fe371c0ba31ce9e7871b98783f.nq.gz
│   ├── 18a658831205f427e386c3739c202a040421f3a9.nq.gz
│   ├── 18c120cd559632e7e274da51d65a3aff51324197.nq.gz
│   ├── 1acbfab6e1de10d7aa1410efae4ae7b5989883ef.nq.gz
│   ├── 1cb08c59db23029aab7bca43d02cbb28b0fcb2be.nq.gz
│   ├── 1cb346d85c2d5a4085bf45ad56f920cee5fc7498.nq.gz
│   ├── 1de74426b0d873b1fb4ff8778b279d109b0d76fe.nq.gz
│   ├── 1f6a44b558b3629d4228b115d6b126e4ed4d0bdd.nq.gz
│   ├── 235239202c4a428befcfc9ea3f5e99524712d7c0.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 271a3445f7370348b0938cae08ed090fe00de8d6.nq.gz
│   ├── 27f1d24d0a71b22648c7f94df543591405416461.nq.gz
│   ├── 282100bd00642d13da19b34b3b309f433bc4d67b.nq.gz
│   ├── 2a71738bd646493915e08e985a89be8df0234cec.nq.gz
│   ├── 2d5bc3e9ea652997a51f942cdaa83e8ad8e341aa.nq.gz
│   ├── 2fbaf40496e5760e4cae427512f09eeb5be54a35.nq.gz
│   ├── 36e8b77f83a1f27132745a5b4fa07e2efbfc170f.nq.gz
│   ├── 3c90b040781bef8b10b142c9aaa3be731c0751fa.nq.gz
│   ├── 3cf11ac183ac3aa39c307a628c11b0a3f6860bf2.nq.gz
│   ├── 3f5ca3dca07ed786098f109f560b447c85a2d112.nq.gz
│   ├── 4007e67a9c6613a51ebeaab2fff7374dec20b951.nq.gz
│   ├── 417cfa7e211508b93406141bc3597dc21605ccc9.nq.gz
│   ├── 443344c9b5ae8b5237cef1885784d04b70341726.nq.gz
│   ├── 46800ae8a1439dc720449cc5755514e515673017.nq.gz
│   ├── 46d740bb7d83a0bbb9c8cd16255ee451cfd6aac8.nq.gz
│   ├── 49874874b83f4c988952763e3edd0dc380b7f8fb.nq.gz
│   ├── 4a18e1346229c64a4d95747efa694cbcea594b20.nq.gz
│   ├── 4aff7c4e4f0eb7f6d79d9da699277f2c5cb06b03.nq.gz
│   ├── 4c9e0f8e9e3ddd2508878b0e55d0c3b3590662d8.nq.gz
│   ├── 4d9d93047583e6d1a4a0245309270afc278fe40f.nq.gz
│   ├── 4e1b3820b6099a2e86f623b2511123210da04f72.nq.gz
│   ├── 504c11fe5d16d3059c98e8b79e3e8213887e51da.nq.gz
│   ├── 50a28534f7251fbea56f8322ff152bf6ab52cfac.nq.gz
│   ├── 50edd07fb5d5df1777082fa5d51d3a89f5fcf13d.nq.gz
│   ├── 50f8e6301bda2976e555615174ce043de73b0943.nq.gz
│   ├── 51c08eb4b03e725019727a75f6ad326b8f815ca6.nq.gz
│   ├── 5286b937cf2935bfc885b9722d5272aff8ca179d.nq.gz
│   ├── 53d585398f55a72217477a9deef5d35978cffbbd.nq.gz
│   ├── 54930b1493beda3e356aad1b030d2c3ec0b6c6ec.nq.gz
│   ├── 5515ff564f2f9afc6aae6b79b46ebfba1b43346d.nq.gz
│   ├── 5538cc4457813759fce8f82b1cd08b980db644d3.nq.gz
│   ├── 57457198b7633012f0e178256bd757e4dd87c77a.nq.gz
│   ├── 57c246b9f6d1fcad137e332f0cf320e674b7023b.nq.gz
│   ├── 585f00a770d75ac9aafef554f5332e74fee7bec2.nq.gz
│   ├── 58ade908f62a11c1f24a4dec643a07294937e16c.nq.gz
│   ├── 58b015b88925bca1ba4e0091f3dbfc53eee101d7.nq.gz
│   ├── 5900a4227e3f50d9669846f0be1e49e8e91885f3.nq.gz
│   ├── 5992e73ffbc5ec823e87beba9a59fd2483ac0aed.nq.gz
│   ├── 5b9f845bbf7c97eef1f3082ed4cf960f3a268ded.nq.gz
│   ├── 5eba54397c32da0a7af757ff8cb810df93653277.nq.gz
│   ├── 5f74b6dafc0ae6a6784c89a7600cef51595cada8.nq.gz
│   ├── 5fd1c9dac7a6a2d4aba36917e0ffa650eff90c96.nq.gz
│   ├── 5ffbbb9dc2a98830a010ff1f5090c6feb7d9c025.nq.gz
│   ├── 61e86c251e6a2b7d0a70775d9e905fec6512add2.nq.gz
│   ├── 6213baf6f6630e0a03eec496fd88cf7ca4c96890.nq.gz
│   ├── 62942a7e6e78e1fb4543109b4a4fdb322ed1f6cb.nq.gz
│   ├── 6575634af1ea45813b51c16176742d684b467c39.nq.gz
│   ├── 658ca7e357eb58f5f4bc10b02a1471e5222b4da6.nq.gz
│   ├── 686fbacfb54de302e1178a8088bee3c84fe6586f.nq.gz
│   ├── 6955d6810c9f7336f5614c4fedc6d33a7cbd2311.nq.gz
│   ├── 6b366ec2afaacac917193f51b3d937d6df0e192d.nq.gz
│   ├── 6be3ed9368ff17979856be73f4ac72607e52f18c.nq.gz
│   ├── 6bf6c87af0756f7a17738a77c974cbaad4a9822a.nq.gz
│   ├── 6d6f36896d47789382de9a1a2e9030764e385b56.nq.gz
│   ├── 714f50d0d3d650952695c875994cb6932f2e916b.nq.gz
│   ├── 7187ad6c7adf4c838da34cc009ac15a0fe11f912.nq.gz
│   ├── 7371daa2096e466eb9cb3a256a12674ca1503fc6.nq.gz
│   ├── 73a4ed69fcf6dc79b0f85213625e69942caf22c0.nq.gz
│   ├── 73d87c7021ceb521fde29719f8b7f8c58e736db1.nq.gz
│   ├── 7697352ccf4d9ec32008f47c16f9ba22dd8c8e55.nq.gz
│   ├── 77635469c298b6c321e44525ec9bc0f3e60dff27.nq.gz
│   ├── 7787133b51832af30650f55c3a086c20c8c85c52.nq.gz
│   ├── 7a2f3143680c5274cd097a22d5b4619149821196.nq.gz
│   ├── 8102948d983b728e5b7421eab24bf15c9ace390f.nq.gz
│   ├── 81c7aa37a8b665662ebc7f9f2297136b6efe589b.nq.gz
│   ├── 84dcfbbcf1ea4527039fe839932bf326643dc36a.nq.gz
│   ├── 88eee31fa91dc207d5d10ef04963eb9870977af8.nq.gz
│   ├── 89703cf702adeb94935ac828a06e6c72f57fe8ee.nq.gz
│   ├── 89ae3c2ed40aa37ddefe919531aa608c771057e8.nq.gz
│   ├── 8a5b75e6a5aa0b0c131450581b116ce0478bb011.nq.gz
│   ├── 8af83c84418f274a5d9011d0ee772bed34a3708d.nq.gz
│   ├── 8b709046cc6df7b79ca36dfb984a712e72a67dc8.nq.gz
│   ├── 8dacdb9b33b076e646f8c4e180c9a088ff2029c0.nq.gz
│   ├── 8dccb5e734038c835aab6eaffe5dd2c1f276c985.nq.gz
│   ├── 8e61ab7057e3dedf86f36b695240a752b33c4348.nq.gz
│   ├── 90f725b2ed0db0b885f278d59e7403518a6f2d82.nq.gz
│   ├── 983f4394797a440d425ec2844969bb7b03d71043.nq.gz
│   ├── 9977911bee5e4cbcbebb34fa58c29198a1e7982c.nq.gz
│   ├── 99997ee400736f25c4ff7c27c77a39351d4bf06e.nq.gz
│   ├── 9cc6f21e7d8c2de201adb4da516b0599a26fe9e0.nq.gz
│   ├── 9d460fbdedc7d4abf61c73da1152510e4e5b8f40.nq.gz
│   ├── 9d5b27100134cd20b3bca4f3a1bc44d2ba7e2d4f.nq.gz
│   ├── 9f7fb2dff160eb04446ccc1299ef3ad0b1ae7c40.nq.gz
│   ├── a0b7c30a57b471c1c869b933f3688cfc9c68e18b.nq.gz
│   ├── a0bb2a4880f7e177fcfa5053aa8fb8b2c3d6e61f.nq.gz
│   ├── a37de607eebe786e66b09706fe0de83f48393b5e.nq.gz
│   ├── a44d342f2eb92c6cc86a0c820d08bacb893e0412.nq.gz
│   ├── a5a9b37a057917cf6a10bc6d99a2070b8b757e9e.nq.gz
│   ├── a8488d16926f805d1f74c43a33c694c44deda889.nq.gz
│   ├── a864e66718e7c1b19e96f16e0a0d17309a565918.nq.gz
│   ├── ab17aac7c6025cc7bca545a647eeefec6c3c990c.nq.gz
│   ├── ae055ae3c432a927b14cf395933019d7e3ea787d.nq.gz
│   ├── aea351775754f7cf4805c82bcf1233233b2058cc.nq.gz
│   ├── af43c07c9baa10895eb0c9624c787ae5500d28a6.nq.gz
│   ├── b06c8b33a6efb8073d336f79d35bf5b75a431167.nq.gz
│   ├── b08e5a4452d1e4cfd22eafccfe8cfcc99a20f6d5.nq.gz
│   ├── b2206939d980d585b076a1f775fa9516d9444e98.nq.gz
│   ├── b4774deec5d8fa62306f30a0545ee25d6a40da94.nq.gz
│   ├── b4a1acf484da9757fe29333d361fcfef1599978f.nq.gz
│   ├── b67d25bdebe7ed4a50c9dfaf2604a5ec87de65e7.nq.gz
│   ├── b8208c613142308da05e2c5296e2fa08d82cf918.nq.gz
│   ├── c01b70713c18806848580b593d2f243722fa301a.nq.gz
│   ├── c3a985f3b67dfcf8a67ff448b2259e9c7a88c797.nq.gz
│   ├── ca1468ed559ec918e8c1bf617b16e9a3dd884baf.nq.gz
│   ├── cb6d4d2400588e758bbc8d8f21d8221d27546df5.nq.gz
│   ├── cb994e6b43b507e3373b2fd6657f6bccd9c5a84b.nq.gz
│   ├── cbdbb98eaa680ec6669140f377ebb207074e7070.nq.gz
│   ├── cc57477a17c1d7044c7816776348adb6c0eeb19b.nq.gz
│   ├── ccdd7ae3187c930c6960a8671dab9578721c8155.nq.gz
│   ├── cecb523f75b610492c4ac7704e4b8ac90fe6eaf1.nq.gz
│   ├── d21d827e71e7481ca0f467f86a2b7742f1c73a4f.nq.gz
│   ├── d22cb62afc4bb23e7f2fc7872bf8e329e55c41ae.nq.gz
│   ├── d43ad528cacd67e1cef5f206cf9521588a2e6bde.nq.gz
│   ├── d4998f3ce7ad1276bfee9de1830fee586f049a86.nq.gz
│   ├── d4f404ae5b9311f5fa12fbbf4ab34858572c9424.nq.gz
│   ├── d71b55d6da2c6f4055b6ffd63bc6c7bca5a7b630.nq.gz
│   ├── db67c3733abc7b3dd6333def4573256903e96c56.nq.gz
│   ├── dd0ca16c3d15535aac873bbf4c9aa62b2df1fa7c.nq.gz
│   ├── de97d9042ce12adc2594b401834611427d3fb1aa.nq.gz
│   ├── def79577fce8cb033fce76b45a9a19730083b4b8.nq.gz
│   ├── dfe7607aa1208a49df7cc3e54699a97aa93861c7.nq.gz
│   ├── e038fb296350459db18ecf5dfc6b9114c0f74e1f.nq.gz
│   ├── e04aa649b860bc8176226377ece2ba96de687b9d.nq.gz
│   ├── e2e04b390165d457324828a8f33fcc59e4f6286b.nq.gz
│   ├── e416c817dd21da73a2721558a10134a7fa66830d.nq.gz
│   ├── e8a67db0c3fd91e53e44d04bc1f7cd34ecbb434a.nq.gz
│   ├── e940a8ee873325c5c3277fbea3c1a17d6cfcd3da.nq.gz
│   ├── eab9c876e1fee4ca82433a967b937d64b25e904a.nq.gz
│   ├── eb877486d59763b2cf37283e874d303d5e8e74db.nq.gz
│   ├── ec12799a1b1e964a495849dcdac5a84b0d6c64ba.nq.gz
│   ├── ee66311c281bcd1785bdcc3e1e6c647b7838b770.nq.gz
│   ├── efb5b84577a7987dbf9ce8e2472e6d270abf8f14.nq.gz
│   ├── f033434111c27616f9a84f3f910bcd3e29eb71d4.nq.gz
│   ├── f105c0b9fb756ac126e51f006703b88463b77955.nq.gz
│   ├── f3aabab8760959ab6f66097d4e10d1f489dc272d.nq.gz
│   ├── f4944a2c5f7efb7b368c6a9a24e404e68efa15a5.nq.gz
│   ├── f4a92ab9fcab3368b4077acaa750c6a987db967d.nq.gz
│   ├── f884ed9d61d49fad80df20072bf46e5ce6271a43.nq.gz
│   ├── f9be5c505dcfe19dd37db442e1ee47dc57d3184c.nq.gz
│   ├── fb269d17c11271c93793d6c0323bf041dd10119a.nq.gz
│   ├── fbc72b9c8237d35bfe12da84a954158eeb0e5b2c.nq.gz
│   └── fec7aacd02a0b3a83142e7256022b671976b00d0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 84dd28ba26c667523519c2372c6fec01881e7c39.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 174 files
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

[modin-project/unidist](https://github.com/modin-project/unidist)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
