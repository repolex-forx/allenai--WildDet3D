# Repolex Knowledge Graph of allenai/WildDet3D

RDF knowledge graph data for [allenai/WildDet3D](https://github.com/allenai/WildDet3D), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/WildDet3D
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1b8aa52b6ff3f00d0ebfa07175efc0c0c440964a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1b8aa52b6ff3f00d0ebfa07175efc0c0c440964a
│           └── chunk-001.nq.gz
├── blob
│   ├── 00030caa37d1d1714b2eb0d7f55c50c5805ed4ce.nq.gz
│   ├── 003c95a3c90fe2349168c5a640905c25996b6a7e.nq.gz
│   ├── 0090ead850330426c45d79494176e5df9133eb5b.nq.gz
│   ├── 0271542144c6a33f59e9643db8dfb7da206fc008.nq.gz
│   ├── 04ba8b529deb3cbc7e5ca165eeef64fb63c6f50c.nq.gz
│   ├── 06a9258a7c55d7d5c2a80c0ecebef49267b4529d.nq.gz
│   ├── 07e5c0ab40242a8e0550799a41de8c1f1cead87a.nq.gz
│   ├── 0cca3d1d0f78ded03c1eb72cce1fe89d6e0d7740.nq.gz
│   ├── 0ef2b4aac045f5bf11bb19f6ea9dedeb5a7a50fb.nq.gz
│   ├── 0f01a93fdbcedfab1396af9ec44f4c6cabb75751.nq.gz
│   ├── 11b2218250b13677bc3797720e792f8bfd7dbd9b.nq.gz
│   ├── 12a96845a4c5cead3778e4088f5e30cacbc17f8b.nq.gz
│   ├── 13aa64d94ea7d4ff5dd15d8e0ca7bed7070d0fa1.nq.gz
│   ├── 1716cb1b5738f9ba284fa27fd28e6af04bd8cb94.nq.gz
│   ├── 18c0849a46228f3e062f81cc8f7ab818a8fea410.nq.gz
│   ├── 18e5f306ee55d01522a5ae222eaaee597d489fb0.nq.gz
│   ├── 1a7dd5fa2e3b9fff89c01fac62b90845849b9eef.nq.gz
│   ├── 1d61644b152c5719e94ebbe69eeb0c9e99f56c47.nq.gz
│   ├── 1e598fcc706ae298cf96849188ce6996514d1039.nq.gz
│   ├── 1f5a74e2349171bd703823d0095dbde19cde7923.nq.gz
│   ├── 2366978a57b886d3bfd9ec7fe6c71db5eca4aa81.nq.gz
│   ├── 2426e26e9c0fdeaeffd977c4709707c005fcc86f.nq.gz
│   ├── 24c2f9eb4dd4d16fae8ba87c6ee074d7f1cdc700.nq.gz
│   ├── 274579c850e7555f44197c05554d05fe1e564cee.nq.gz
│   ├── 2add5340260e8b7fad56ac6fbd20fa086ef27de7.nq.gz
│   ├── 2b2066530c43229d9423d632e0c6a6fe3c90d9be.nq.gz
│   ├── 2b4b7b550330339668cbd49eaa374e621877dc2e.nq.gz
│   ├── 2b54115086a6b813ba8d2c2e9462adc3a19c9787.nq.gz
│   ├── 31132e80e180e2030798750f45bbc959698e9596.nq.gz
│   ├── 312b5515b311bf93a14baa64fdadaa323c70462e.nq.gz
│   ├── 314064cf67f1727c700264e23e92b30bd89a8863.nq.gz
│   ├── 33894967eba341b5526e535167f5aa64d4ff3210.nq.gz
│   ├── 3487cc477bced2c1fa5f9d48e987263ef542c770.nq.gz
│   ├── 36bbb243d68c3c4ab8e054defd1c13cd8a379c8a.nq.gz
│   ├── 372811864ede94f09f8a718e63f6dba54a420f7a.nq.gz
│   ├── 392042f84e7153768515d52bc53aafe35ff49db8.nq.gz
│   ├── 3a7a8c07191d352827c9fccdcd907ed3a494ce1c.nq.gz
│   ├── 3c0de2efa2518eff98a00365b284e943bb5570e6.nq.gz
│   ├── 3c35ab87bfdae026bb9e9fa9dc42cb64901d931d.nq.gz
│   ├── 3cc32a1d0233ca25bd34426a56cf3a7d17ba7d5a.nq.gz
│   ├── 3d0cf0c60f2c8e9d39ee404b72a032eb04e68603.nq.gz
│   ├── 3f3ebbbf49e1a17c1bdaad1ec97a5d80ee85c3ff.nq.gz
│   ├── 3fae551432aba5cfd9f28f0126b1f5fb2b06fdf1.nq.gz
│   ├── 4811fcb216cfa6f4d7e7fcb84e0e2800508bb63f.nq.gz
│   ├── 495a0b8a72e2568d47604ea2d9eb20ca14f1afa0.nq.gz
│   ├── 4a5f75473d1dca854e68f1361b3c14b509f16e0a.nq.gz
│   ├── 4afe706ce0a2bccd2521b6a40fea23395499cee8.nq.gz
│   ├── 4e41d1c65ee0b5317b72648f8bd50353ccd2919c.nq.gz
│   ├── 4f5784257bf1da0341b0027ae9806cb14518b6ad.nq.gz
│   ├── 4ffb2fa5a54a8a5ce4f1b7634db16d25fb0cd51e.nq.gz
│   ├── 5032fc27faed0de4d2b531e6c9826e106c99400b.nq.gz
│   ├── 528d2397cc6edb4fb688baa2948de5be4b423c85.nq.gz
│   ├── 52d93a3fbf43352085a4089047aeb600929fd583.nq.gz
│   ├── 536278189841bd67aa0c5431e79a2bc15e99e2be.nq.gz
│   ├── 54f60503baae6b4e4b76a219026d1500004983e0.nq.gz
│   ├── 567d5abc517aafdaf44c9738cf2ce4e62bf1de36.nq.gz
│   ├── 576ce8af457539b99fecb449c3b7e280a83aa75b.nq.gz
│   ├── 587d0bec0dae7eac79eea08cfb26732c3ba6cc21.nq.gz
│   ├── 60ee8cea981c806c37f5343744a1a914703041d5.nq.gz
│   ├── 60fccac979f640c7eb28a68846dd7d86359f2b1c.nq.gz
│   ├── 621c9834abc94c41726be625ba44146d016c8522.nq.gz
│   ├── 65cce5d89928862760bbff9db42d5e16a6002e98.nq.gz
│   ├── 669ee5707bd24f1fdd1f926bb93ca7e02ccfdee3.nq.gz
│   ├── 682ba037b68f31d0b551744e93194426cbb1e538.nq.gz
│   ├── 686ee6d79c1fa2abafdd3565007ef012e1fa4a38.nq.gz
│   ├── 68ffbd63f41daecbc90a48541f408e03349431e3.nq.gz
│   ├── 6b0613fca6abf0443fec6b38fd9e2c43dcc56cb9.nq.gz
│   ├── 6fa8a241836caba6e3fcc4c2568fcf5b824eaf3f.nq.gz
│   ├── 702b0f05f80677ba7fd998dc40c386091d686020.nq.gz
│   ├── 730dffa3826c2decc48b0409ec6c10bc4e3b79eb.nq.gz
│   ├── 737a2e05f9740cdb973c7cf22aacbe7cb6a09c01.nq.gz
│   ├── 739d0b36e24847c9839a6bb967a1d984b8d40948.nq.gz
│   ├── 73e79586971ff5ea47ea158d4066fda579f5b608.nq.gz
│   ├── 7608a3c02da443ce797ce276e500133f3f093024.nq.gz
│   ├── 76dc5648182c920e539b05bea1f1aca0854b18c0.nq.gz
│   ├── 77fc2805c8faeb02dc7ced5cd636f461a7062358.nq.gz
│   ├── 7b6751b450ac3c2c61b16c14e8932bf5403976da.nq.gz
│   ├── 7bc7af6159d07a08e1ad770bd365bdc007a8c542.nq.gz
│   ├── 7c12226350ccd2e428d5a1be86ed2b742671d684.nq.gz
│   ├── 7e56aa6f6a6c0db969621e03f475a60bec0e10fa.nq.gz
│   ├── 7f31438a6b22fa81876aa58f4652877786fa9246.nq.gz
│   ├── 7f3e1c8196b7fe546bd2cfae2a964a5dd6facd84.nq.gz
│   ├── 7f538917ecc09079216920e6f1c4feeea275d6f5.nq.gz
│   ├── 81b11c43c5e3599fcdcdd76865ff02a51b0e1834.nq.gz
│   ├── 8202d5feeccd1ca69619df63f5196c13c415eb9d.nq.gz
│   ├── 8260f8415144d7d37d3f33a41abeb84bf91170e9.nq.gz
│   ├── 8333817e9ca277d3a0c5af206ee37927745fbe9c.nq.gz
│   ├── 84a1e84d949518a7960ddf8a2ca9928cfd64a37e.nq.gz
│   ├── 85c3d00ab58b4af33dbb8f81711b1b7abccb75ad.nq.gz
│   ├── 85e036efd34d272b11398d7320f5505611913003.nq.gz
│   ├── 86896951fcdb23d57712c44e9899c68d7faa5515.nq.gz
│   ├── 870040840640e0ee394046589a52439b1664f433.nq.gz
│   ├── 882b8ab1042b14d22e75f36199989d04c95a6b32.nq.gz
│   ├── 88894c4205d5d4743b426cfa59c63b10de52ffe2.nq.gz
│   ├── 88b2026615ea1848aa7c6d4b3ad983df38fda0b6.nq.gz
│   ├── 892840befc121fbf51ddeea16cc1b25b31fc5c12.nq.gz
│   ├── 8c0c34dce5ffb656b98b4526d809200d010bd388.nq.gz
│   ├── 8ccd6ef1b695a04717c8f6254a2f18df091fcc9a.nq.gz
│   ├── 8d45dc7873b2f66e6ec24c2b755f457417677945.nq.gz
│   ├── 8de438b0624d2c203df5886f8ffeb3d8ebf4ce5c.nq.gz
│   ├── 8f9cf007b3753b45c3c13290ba94324502828f7a.nq.gz
│   ├── 905c7f5b8037936014c21727c689910f7db70199.nq.gz
│   ├── 9116eb6a48f6babcd93a6ab0dcbdc6e7c5fa0c34.nq.gz
│   ├── 92c210b4b06aa616bd6bacc4fc588399568110cc.nq.gz
│   ├── 92f066ab56189fabca293cfa15c3de216f936ad3.nq.gz
│   ├── 95c3f745d697f716979112e30ff50d0af6aca624.nq.gz
│   ├── 95fe54423d065de598cc22bf97b8f25e2b9018aa.nq.gz
│   ├── 9624f90d81f2013cce07529c47f529b4ecb873d9.nq.gz
│   ├── 96ec75eb0e6f0887f33de3fd9cf077a9948cfc7c.nq.gz
│   ├── 980bd1bb5abaceff1711d4f6bfe0596abce0e28a.nq.gz
│   ├── 9a2fd9f1756bd6fe04db2a8ebf0a01d5e3f92442.nq.gz
│   ├── 9b0e34605646838fe4b3f60ab2a9b0b1d9b14226.nq.gz
│   ├── a0459b01730c973841195726e1a7250747bce2e2.nq.gz
│   ├── a04858cf7b801b5c6febfd85e91db26dbcc4ed9a.nq.gz
│   ├── a31b43c0193ce5386145063f9fe0857ac27c23f1.nq.gz
│   ├── a4476dbc617fb6fc3e5af43a4403fd8a6d8d6834.nq.gz
│   ├── a4d4f1eb0e355ef7920bd8b38a2ca6b51111c4fb.nq.gz
│   ├── a4f5e51404fbd13ab7018e14f34574e763055c82.nq.gz
│   ├── a6cf0e13d95a13deec34634fc92236725817eb94.nq.gz
│   ├── a9c0412e62ea0b872321704ee87f78c02d56ca38.nq.gz
│   ├── aa2b6fa2df479f932b5c14731e52ae808027fae4.nq.gz
│   ├── ac21532950926380526e04720f5656fa477f6070.nq.gz
│   ├── adf3a1932712c991775422dd6707a99bfe2775e3.nq.gz
│   ├── afb3a8a106065b967cf4290798801d4eadd70bf7.nq.gz
│   ├── affc780130d82463684e4d451638a391ed439f73.nq.gz
│   ├── b1cdb12ad534780d2b33bac40f3159c78322e68b.nq.gz
│   ├── b349df1b1320f95115176401eab6bcd16df9bb4e.nq.gz
│   ├── b55af08bb6aa7ede458b52a0ff44078c7f3f14cb.nq.gz
│   ├── b743cd50f2fddd2fa504f1d9d1ee9fd7fef3e47e.nq.gz
│   ├── b86f01a73ef557434fa4a35bf909e82ccf689d85.nq.gz
│   ├── b911c4caad26a9250d7f17375b420c54c5822c11.nq.gz
│   ├── bc59dd319ef1af28753e870e0449986fd55bc8e0.nq.gz
│   ├── bc9d1a706d76b55ec501d73af7bfc20d2ccef8b2.nq.gz
│   ├── c21026e824f977bf2fea9b97955ac39907c9f7ac.nq.gz
│   ├── c303aa1c9b692a45d5d3f48c231aeebd68fd9a14.nq.gz
│   ├── c3bc38cc72158d85e1e8f8795528df74d0ecf313.nq.gz
│   ├── c6d9676d666f825ad5d1baf80851061b934aa3f1.nq.gz
│   ├── c7b2e0d03ed20a28e8f295b4a9994e26e79904c2.nq.gz
│   ├── c856ce6ff1fb60e03b33c447dd24c071cfad4daf.nq.gz
│   ├── c92b582387d381e26832b8c4efaf97f49373a0c5.nq.gz
│   ├── c93680d9616b2876b92ffc779da6d58ca0042720.nq.gz
│   ├── cbbf4591454016c81de77b048b5d263529604bf7.nq.gz
│   ├── cc52bc04633694e2ea8cd74bfdae9be173d16858.nq.gz
│   ├── ccfdadbc47c8471f7fde9bdd7a7c24cc6987b506.nq.gz
│   ├── cd0fbf59e624249155283761f52845f8ba26018c.nq.gz
│   ├── ce9df2bcb3e874e437b8b77db9678ec9015ab47f.nq.gz
│   ├── cf74142eb29f1df700d59a3670dc12a9a553019c.nq.gz
│   ├── d1ab0727e237085ba7b315948d2ee9ec4b728b46.nq.gz
│   ├── d1cc1341913b130cff92343f85ce5728f44ccba1.nq.gz
│   ├── d2067700d2b73e4d84717034d83285846d047e4d.nq.gz
│   ├── d2afcc80796d496be319e700ec04a53d2fee407c.nq.gz
│   ├── d2f92c4b6244dea653d83d9a1f4396519f679b27.nq.gz
│   ├── d330a6a34a5392ee241a017049533ca4eec0528c.nq.gz
│   ├── d3c2a09109ae00395909e5474b004e5d26c74e92.nq.gz
│   ├── d446344cf4bb47f9a99584ed37a02a3e4af05788.nq.gz
│   ├── d640f9cb91ccb99364ab275362efcf81981f8c02.nq.gz
│   ├── d8003f6e8f9f25d091f7ea3ba07a4eb78664f203.nq.gz
│   ├── d8d279668a5bb93c47e10617ab63aa591cd3eaa8.nq.gz
│   ├── d9dceb74ea84bd9fd1ebe91388990ae6134fc291.nq.gz
│   ├── dab30c5aa5dd2644714a158106e0d832f55e6684.nq.gz
│   ├── db8b039e3fac6aa86c978c2ab2c13910f4f39a11.nq.gz
│   ├── dd602e9f048467ec1ea5fd3551a7bcb53aabf78e.nq.gz
│   ├── de46146513fda9269994dffe007a4d4aa1bd6fbd.nq.gz
│   ├── e0cd53ec57f9b272d3730e677ad6ee338db892a0.nq.gz
│   ├── e26f3f3393ce1c994dc79c3f842254401254d3c3.nq.gz
│   ├── e2ac6a35408768097459caf082b2f75b5ff40f8f.nq.gz
│   ├── e52d42ccbd862883d6b844f47a256d973e08d499.nq.gz
│   ├── e63c586a191439e227a0bafa215c7ba57e17a043.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e74da9b8ac2d4bcb0bac07a2aff0dce4f8b0dc66.nq.gz
│   ├── e7adffc042a79ed0918ab0c4c616b7ade6a9a487.nq.gz
│   ├── e8380801b36c3bdedca8125359180f280f1a2179.nq.gz
│   ├── e8bc3f4d26a485d3ec9a6bab98d6d24ee812f0ab.nq.gz
│   ├── ea034b79986782562e0822d7aaba9b6a5d8ade7d.nq.gz
│   ├── ea295df86f8286116a39942ba0751787415c41cc.nq.gz
│   ├── eac95a5e29181d898bf3342630481658689ef7bf.nq.gz
│   ├── eb48591771bec42ddac8fae5285174ce39fbb38e.nq.gz
│   ├── ebdaa8365c5741c74cff9e22b378fa65a4ff2b40.nq.gz
│   ├── ec2459e39c7bbe766f06298b8388f4d07215fd5b.nq.gz
│   ├── ec435b5d22119a194c476634221d81a0b3bcac6e.nq.gz
│   ├── ee88e204bf1a27e120ee23dcbbed76f221907f1b.nq.gz
│   ├── f1340c52ad1bbd246ddd37ca40153d6da79a5ce3.nq.gz
│   ├── f173db6b4ea0691fb71340d1a8b870c841873c00.nq.gz
│   ├── f1a46f2f13b63539c670bb1ed10ff1672a867840.nq.gz
│   ├── f21357c05b848ae27d4ba904194c176e899dbd36.nq.gz
│   ├── f218bff9205ddaf87801c98c6a68005f66c7d364.nq.gz
│   ├── f304621678ebbec1b3feefc25720d0e4a9865e42.nq.gz
│   ├── f43b8f2189da9b7d3906ec11138e0eb7a3ac920c.nq.gz
│   ├── f5462649db3e16de36715c23265e7df14b3b8247.nq.gz
│   ├── f5c8863b9706e3dfafb6f584f1e74090c2a6fed9.nq.gz
│   ├── f5d93c7efa7ff98cb6facb4b83076d79e7b7e4ae.nq.gz
│   ├── f82226f1c2ecf6806e13c6e4344807b2eb45a292.nq.gz
│   ├── fa15246f3ae966757898cd15951d527d6ac59eaa.nq.gz
│   ├── faf20e1bca562e402a2786c635b59d80892f610e.nq.gz
│   ├── fc108fa9f5782970c06671ecc1c36287e476444a.nq.gz
│   └── fc8a03a868208c18485bf702859149febf015495.nq.gz
├── branch
│   └── branch.nq.gz
└── commit
    └── commit.nq.gz

9 directories, 200 files
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

[allenai/WildDet3D](https://github.com/allenai/WildDet3D)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
