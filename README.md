# Repolex Knowledge Graph of combust/mleap

RDF knowledge graph data for [combust/mleap](https://github.com/combust/mleap), parsed by [repolex](https://repolex.ai).

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
rlex download combust/mleap
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 53697f872274eb9a4603363c51138e76a47dbec2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 53697f872274eb9a4603363c51138e76a47dbec2
│           └── chunk-001.nq.gz
└── blob
    ├── 000f5f76a5c30909b23ab27baa58272453747621.nq.gz
    ├── 00c3eabd026d26d89690a41779f351bd65ba8018.nq.gz
    ├── 01775e3af76429460d4b14ffb366c5d6877c0b1a.nq.gz
    ├── 02be7c6319c15bd41ecd26a99598600559770f0b.nq.gz
    ├── 0363dd40b96f891494206c2db1ce73693e25d04f.nq.gz
    ├── 04650ad228c16d6fe99ae60be19dae66edb391e2.nq.gz
    ├── 05721d4ee32aec8581e6aedfe9e658e25998dd62.nq.gz
    ├── 059d785caa1fe43da31d27ac03e92e9311f99c6e.nq.gz
    ├── 06bf5e3007c60c13565f2d8b3248f3bf2e1d76b5.nq.gz
    ├── 073188d1e159240f2406ee62503d1a3d6a8798b9.nq.gz
    ├── 0738ab9af068b155aed0dfbeb88aa25e6bdb6c9e.nq.gz
    ├── 076c11c7264ae8130dadecea423c7e01fe7abe8c.nq.gz
    ├── 0773609c278af76f85d32af5a0c0cc6eb47e2421.nq.gz
    ├── 078dd23136d1d499c71beb394b2b2e76c3b83a8c.nq.gz
    ├── 0889142950797ecccdcc04b8a2c9f4cbc7c21fb6.nq.gz
    ├── 08bf3ca4c279879cbf8edd48b14c10b6a6602c73.nq.gz
    ├── 0907960d0b0c585feff92e1ce4b93a31e0948813.nq.gz
    ├── 0977f435ade7f940389c1af76a459fa02f362fcd.nq.gz
    ├── 0a2fd26953f7a8cef27058e8b2662640288cd567.nq.gz
    ├── 0a91e3cc7afd8433c7fb958ab82ec43fe16ef9aa.nq.gz
    ├── 0b51449355f9f271aac6830bff13fb743a0db0c1.nq.gz
    ├── 0c0df074068771e240a46b26ecbfdcdcfc4b247c.nq.gz
    ├── 0d8a0b9d336b38bdf9de006775b59519f98bfc10.nq.gz
    ├── 0dc34ba0b4eb99bb69657ed752338e4608659601.nq.gz
    ├── 0dd64553531b6600bdc4b193746f3f715497b9b3.nq.gz
    ├── 0f20e8e94c9e4c48ad76ed71bb812bf0d15b4975.nq.gz
    ├── 0fc38a2a1ba4e2dfda842c9bd962b664d5e97aa3.nq.gz
    ├── 1058661868e8e6cc07e04457c178470657459927.nq.gz
    ├── 10910658bfefd8ec541f84a5777a972d874c41d1.nq.gz
    ├── 116485e85081c358c5bd1daf9fc2f63b027ffbd7.nq.gz
    ├── 1209dbd644b7deb2d8e2a2d0d49c4cfb622dc6cc.nq.gz
    ├── 1287907e7f4c52fb0e1da515db752f29abd705f7.nq.gz
    ├── 13372c379e9c8ee0abdaf93889b4d4acae42de3f.nq.gz
    ├── 137094ccf939df4a180db7b05779c669c8da2a6f.nq.gz
    ├── 1422dd7793551e242032a9fe6689ae520e3a4e43.nq.gz
    ├── 1428a51cc16cddd767eeed9c487b54f80d6ae93f.nq.gz
    ├── 149702132b3aaaa3afb26efa5304c85af8c19c96.nq.gz
    ├── 15d3730ffe1b90c602c8dfe6b50cf03077de83df.nq.gz
    ├── 15df6ea81b580e3738eaea2f50a64d6bdae6696e.nq.gz
    ├── 164abdc340f97a3b66d185ba069a3efbd720cbc5.nq.gz
    ├── 164bb11635bfb50ad212644a6afdeebb255a8391.nq.gz
    ├── 16cdaa3ee22f7ae082ad3d216963b9d8b7f7d6ad.nq.gz
    ├── 1746bcb5bd0d3a045ef75bbf90730dab78b7cf02.nq.gz
    ├── 180f61ac56ac7c7a48f098531b8f31fff82a21cb.nq.gz
    ├── 184a6d28eb0b5f3e7e46a2092545830939c99414.nq.gz
    ├── 18f1cf457da02cc47c44c35f6cc3edcd7e81fb21.nq.gz
    ├── 197859b9b631079326e9986d176affd43735bda7.nq.gz
    ├── 19a2572b6e768166fc86eb2f9f475aeafe5b8392.nq.gz
    ├── 1a901cee0be031765e540a088b7773f1a9623f47.nq.gz
    ├── 1af150e71025ea8b77a48a69565f3681227f6c0c.nq.gz
    ├── 1b0bed036a54a29ee4df1502c132a268c6257629.nq.gz
    ├── 1b2b176f488a7df1bc32590cc921cd04919ce36d.nq.gz
    ├── 1bb16e0d074af6cffffef7a6693ba27232702e78.nq.gz
    ├── 1bc8e2f2e4093f7b942d31dc255f1ecee9db13bb.nq.gz
    ├── 1c2e8efc13a4e59f98c97f5f3d1dfd2583010479.nq.gz
    ├── 1c55b783b6d6d8de44577624af0e86dc30285dec.nq.gz
    ├── 1c73a41a9e04c6cb08b6c05be71d85773d542890.nq.gz
    ├── 1cbad9cfd360cfa2cfbfe082a963424801e118fc.nq.gz
    ├── 1d391822e4da7ffac1313472c1567b9ea32dcdde.nq.gz
    ├── 1e33a8a1dbe995cb00d3f5179767f8ed7a21709b.nq.gz
    ├── 1e6034715b2d80d22a76fadef1b985586cd82491.nq.gz
    ├── 1e858dc4c3906daf1f2262e948d64ee1f5653aeb.nq.gz
    ├── 1e8f7e1f014273482efb349830ed6a3083a73f41.nq.gz
    ├── 1eb6f7f0c6d91819996939a9971a005a3bf04b4f.nq.gz
    ├── 1f3ee216cc197c7a1b6083a0f6ff0eeed5dfe01e.nq.gz
    ├── 1f53c8b37da155d7adcbdb28ebbfd42d5d23f12f.nq.gz
    ├── 206508183781dc355ba4b4664805cb3effbe094f.nq.gz
    ├── 2141e15932776eb78ad54dbd0ef29a935f9ceba4.nq.gz
    ├── 214ef4f9d8114f1ecd36f490467c709dbe67fa89.nq.gz
    ├── 224a77957f5db48dfa25c8bb4a35f535202da203.nq.gz
    ├── 22bec56c020a7a8c758a1233bfe18ceb05e9bf85.nq.gz
    ├── 241546a856fea34a460c7060be37240348a4206b.nq.gz
    ├── 2560bcaa71323bff4c7ee8511752722e1343bac0.nq.gz
    ├── 25cf49238b72c58e97d464c4df4d49c079175ab1.nq.gz
    ├── 270c731ee954cc40d23188af9a9f8ee43ed7f7c8.nq.gz
    ├── 275728a06bf1cce00523baa9e473aa6027a51d16.nq.gz
    ├── 28048d0afaeb2f7ad29ac41d79ffe13b0e556591.nq.gz
    ├── 286cae73b7596bbd52d2b6c2a5c58382472c38f7.nq.gz
    ├── 2956d4b5457480b67061bf5d1182dfcbbde3f369.nq.gz
    ├── 29c0d0ad2e2beb4125972826db3cb2b76664acfd.nq.gz
    ├── 2a43f182e1ab3e5f14daf099dab7978861ea94ff.nq.gz
    ├── 2aeb0f1c8e6c4ae5e2adccb03495be1bbac9b9c8.nq.gz
    ├── 2b2c5a3f364af1c7306c32ff7cccea4b8a9222dd.nq.gz
    ├── 2b50952b094f8ca857e1db30389048f173cb7134.nq.gz
    ├── 2c78243ee06787e72ced131def3116de59f7526c.nq.gz
    ├── 2ddf3ff70c070d0040df3b5a3a371908fb9b24b8.nq.gz
    ├── 2de1e454566c871475057f43c6c14de1140d7572.nq.gz
    ├── 2e518763b3a0706d3f5d155e6d1dc0d7d4df7a2c.nq.gz
    ├── 302864f109ef12ee3626be3066f32bafd163cff2.nq.gz
    ├── 30356fe9186576f283759d49b15d7f0382ee2a6d.nq.gz
    ├── 303f9e81080897a13eb4c83ad21f378c9cce9808.nq.gz
    ├── 31368a121a998a1f93d11163411c74944c50dcac.nq.gz
    ├── 315240ecccdcb2f227c2daedc9f022a09a66e1fd.nq.gz
    ├── 31dc9c53c055d8cad0c242031ace8d069e3cefa8.nq.gz
    ├── 31e69d201ad6223c05e563d92500c78230df2347.nq.gz
    ├── 31fe9cd1d88df219b6a6732f7365072ce5dc5d4c.nq.gz
    ├── 32481e2d54be0a719aba4e0ebedf3bd5e23abca4.nq.gz
    ├── 3282df3179709b4328ff26da43df52db08df6e63.nq.gz
    ├── 3285234bfde382edcd3042b1e2ae695cc20887e8.nq.gz
    ├── 32d1e2cec329c86d3be7c1f8490a9995d3ee58ee.nq.gz
    ├── 3327e9457f2a7258f99c63d82970b7c73753c752.nq.gz
    ├── 33dc2a447dd1c81703f99fccfdee550bab8d5544.nq.gz
    ├── 33e61afb605b674b8195a9a342346e6506704930.nq.gz
    ├── 340dd80026ae77252cde73889ba03aec5abc96a5.nq.gz
    ├── 341a81a341d78731b9ade21560230665c5205b21.nq.gz
    ├── 34a0d7e98f585fa745ae2a44ea6c076e9c708766.nq.gz
    ├── 35c35796460b23378dcb2fdaef305600fd550828.nq.gz
    ├── 36baef32a2178d26fea8938791d96d2bee09bdcb.nq.gz
    ├── 3771c8c8db4f19d2ec36dda61d65c5ebab652deb.nq.gz
    ├── 37d49599b4294ba07e0af6662d8950c339681645.nq.gz
    ├── 380dcce3248ebef68bbd2188edcc5f1d683c717a.nq.gz
    ├── 3927e0725e7996c3b190b38379cdb5be501f6d4b.nq.gz
    ├── 3937a58c9070a6f2623926d277bc834ce93b29fd.nq.gz
    ├── 39ec9c173fdcd267b3d6ef2ddda859c14ec9f88e.nq.gz
    ├── 3a33a4d5f86bbe3acce508f45a1e7cddd1ce511c.nq.gz
    ├── 3abbec8c7a677f61c745c09262cc6ddc9e396b25.nq.gz
    ├── 3ad1f44192bd6310d62f01d7f77f0e5c68f0d959.nq.gz
    ├── 3af96ee323ed53cc4b6481c35950289da7f46540.nq.gz
    ├── 3c815b34fe495cec25747f3df530e859ef9f31ad.nq.gz
    ├── 3cac97dc824584851ec805bf75a8238475cdd9eb.nq.gz
    ├── 3daf53fce53d839f9b7f1097f0dfb0c6f0b95d46.nq.gz
    ├── 3dc048b271f84069a9665dd46ccdbbf60b981fd8.nq.gz
    ├── 3dd0d3ea73241967a6a17be628c2663906a1643b.nq.gz
    ├── 3deeb4e4606330e70209e7ebb1b9f1efb13e543a.nq.gz
    ├── 3e122c0124c4a88640f2d7516347c028fdddeb4a.nq.gz
    ├── 3e3fa5fddf151066298a76c6577d9323ead724c9.nq.gz
    ├── 3e96268d1bb2211411480ba9c863a8392f1c6366.nq.gz
    ├── 3ee4a075b697b8d3215464609b66b627ad9dbcaa.nq.gz
    ├── 3eed2ac112bca18ca81b9f20582db11e51745f78.nq.gz
    ├── 3ef200d7a22216e39393aa46491720b51ab5369b.nq.gz
    ├── 3f2b477429dfa6f9ae3a392f8e05c888da76c845.nq.gz
    ├── 3f7f7f64ae6256b7431b3f3d51f42413dbedcd78.nq.gz
    ├── 3f8187a3a4e4818694a9f2bfc7a5131485b552e7.nq.gz
    ├── 40538781f2a9df0592f88e9e0bd95f9dd9eb3ecc.nq.gz
    ├── 40bc8fa00e085af33fe1eb65829e41d8bbaa391c.nq.gz
    ├── 40c55691141ab4ce4c23064bdeff74611fda3bb0.nq.gz
    ├── 40d4723af7405587958c60ce4857923a6ba20d77.nq.gz
    ├── 4100e1a257d9f4c09f821e5ba731a955db39af9f.nq.gz
    ├── 41652fdd6d4bc81787b9024b702f367a79e50c6f.nq.gz
    ├── 4191d4e3edeef35c7a906ade922e0e7e5cb04e4e.nq.gz
    ├── 42065db6ffd0f5fb91b90549f0a757c9647d55b2.nq.gz
    ├── 4251bf9b06080d1237cfc39d57022fb1d2760c50.nq.gz
    ├── 426a6b6bd2b4e9d36d810f4030920a88c0205ac8.nq.gz
    ├── 42ce7df4d3a3b573c2a6015d13c85e18b7c1a9da.nq.gz
    ├── 42ef227c29ba7d330e1d81b912840b979b5d33fa.nq.gz
    ├── 4319aed4e407d2bfcda1471eb5cc5274777db661.nq.gz
    ├── 438915e86cd98bbd6cc8abdb9784fb032482b296.nq.gz
    ├── 441c1e074e61cb1456e2816eac5262237c843159.nq.gz
    ├── 4453748482984297daef36e73afc614b86892cc5.nq.gz
    ├── 4493c1ea28ed0eadcb4667990f19d23065c96d2c.nq.gz
    ├── 4514302ade5758b7f89297b30cd1250ebe6cd3a8.nq.gz
    ├── 4550e4a8d4697dcc94d8ca88262649adbd39c11e.nq.gz
    ├── 463b8c79546358d277104f38baebeeb437bd92f6.nq.gz
    ├── 46a1e818c4329525c8dc2a4df1c051f3b919abb6.nq.gz
    ├── 470152e47d724f5384d6c4eea414bbf52c80c003.nq.gz
    ├── 477783394d227c5c19d23efcb33a851aea274fe0.nq.gz
    ├── 47a1577a7db2dc096ab392947ca795e1e6578463.nq.gz
    ├── 47a23dcb6236bbc74851194445b353ee36a37bf1.nq.gz
    ├── 4913f6d4ea890b2da062c15d47a7b2aa93ada382.nq.gz
    ├── 4919ae39d47f1d011188b490c2a5ec974787df7d.nq.gz
    ├── 4940aa526db6964b7cf68997b381d2948b9539e6.nq.gz
    ├── 496fdcbb2f250ed966ef7376db08332d1584d20c.nq.gz
    ├── 49a4e9e7c00b9aae77c6dfad5a872e6f5c14a025.nq.gz
    ├── 4a37d1e2e202f8a9a00cf2fedf72b25392cbe844.nq.gz
    ├── 4a627bbed2ced3487f4e3768fec90ecdf89846b2.nq.gz
    ├── 4a876c1d4b8a21dbba521283e489fefb3bc58926.nq.gz
    ├── 4b7878ac295c270279178a533bd6a8b3b1e01cae.nq.gz
    ├── 4d254bd9345f4fbd58ab37db7aa3a7ad8f1f6061.nq.gz
    ├── 4e97797f17a9883ac2ed28fe123d6be5f32133cd.nq.gz
    ├── 4edd6c0a466b24bf60cf9e2dcc639a710cea1da0.nq.gz
    ├── 4f3b3f372600718e9ec974fd7ce8d913f569a97d.nq.gz
    ├── 4f599a13eda60d0731cd22f09e6f39c6af71d650.nq.gz
    ├── 5033951472f02cb59ea800eb3efb5033275f33b0.nq.gz
    ├── 508ee95d7ade5e80a3ccb0bd8081f81238bb4814.nq.gz
    ├── 50cfc239cce00770b1d04a64e13dde91eac43de5.nq.gz
    ├── 511e74b7f80d632638b86bf873a4f329bae5f2a8.nq.gz
    ├── 51383ad36a00235cb7efda737d9a7aef6c1e4fed.nq.gz
    ├── 5265f8bb10aa848bd32199393f4fadcea209d8fd.nq.gz
    ├── 528ecdcd802a69952cd53dcd198484ebb052a0c9.nq.gz
    ├── 52a44a992cd27a694e1b7ed31de7570c2835bb6c.nq.gz
    ├── 53813a8a0b1aad596349ee379157faccddf408d8.nq.gz
    ├── 543afa29bfb3730ba703f5230dfa6f5e0ab0696f.nq.gz
    ├── 55186697fc69dd901f298a184b2b44c95ad90c71.nq.gz
    ├── 55866e8d0b79a235ec625ba4f18b99f0fde24eba.nq.gz
    ├── 558d1e8aee40e30463fd8e66b44f9d17f4f94588.nq.gz
    ├── 55c2648752511a3e92e2830a2dae419f38ec188e.nq.gz
    ├── 568345efcf70a48d1acf375e0da9318e03fa6fb6.nq.gz
    ├── 56de9d95f189d35977161dcde463e7b94ba146c2.nq.gz
    ├── 577beb165f3b0d07da7efb07643ad490cc39be28.nq.gz
    ├── 5798cdd367b7baee04b476adbd90ec3a19efe823.nq.gz
    ├── 57e49c972d283af8d069b813f7112b3a9290c5db.nq.gz
    ├── 583eeb00693f52ad6c15029b80f4db038a1f77af.nq.gz
    ├── 58a99c706aff813558094e5358f4d1665b5ec7a2.nq.gz
    ├── 58ecf4fd6923418d350fea865c07ab69d9b77886.nq.gz
    ├── 58f4d3006ee1288b62890b3f426f8e2ca5ff8a7f.nq.gz
    ├── 590c5846e55db2c8612d5e7f227fa27084bf7e80.nq.gz
    ├── 59161e07abc347dad48291477f6d2d387af12ca1.nq.gz
    └── 59cd06e77a1816258db68c9d258f06cf06459d40.nq.gz

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

[combust/mleap](https://github.com/combust/mleap)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
