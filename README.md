# Repolex Knowledge Graph of celery/kombu

RDF knowledge graph data for [celery/kombu](https://github.com/celery/kombu), parsed by [repolex](https://repolex.ai).

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
rlex download celery/kombu
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4a8f695e4627842af8744a477f30b707e5988d20
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4a8f695e4627842af8744a477f30b707e5988d20
│           └── chunk-001.nq.gz
└── blob
    ├── 0023c6d0bfeb71076d4d6eaf387c1eb49dddf324.nq.gz
    ├── 004268cb379efa852f403eb7057e5667d66530c9.nq.gz
    ├── 00c27f227833e6b6f6f53dd6b74f380935daae91.nq.gz
    ├── 02edda074be43a151104b65a1cebd61aeafb7f4c.nq.gz
    ├── 054e7ba42b51e5fea7138c8a0d4286c34b5f199f.nq.gz
    ├── 05e3ef83217d3d2b4804d1d865302f1020c11816.nq.gz
    ├── 069a81c90c3d74e5803789602cc69295a4919363.nq.gz
    ├── 07b47581d7b30f5fcc7f1020f3206cccf750a81d.nq.gz
    ├── 07ca9bfbb8fe465827c0de70d5d1a96bac50af0c.nq.gz
    ├── 08794ddb071295eb75ff6d21a89e70cc6083d34b.nq.gz
    ├── 08e524c279d27ef8246b40e93e372c94c06a5613.nq.gz
    ├── 08f9508368af0a412f0a27ba6eee95ec5885bbd5.nq.gz
    ├── 0955368e77076010a8a2e556d453d4b557189a50.nq.gz
    ├── 0c219f0ec74e8b5f774664937014280942d7f0f7.nq.gz
    ├── 0d63e241801efe055ecf738e08090e3a60c5c59f.nq.gz
    ├── 0d7b97c51abb3e3278d1872a213dd2ad5133acd6.nq.gz
    ├── 0dc15521c59d6984870373c06e0e61d9046a6419.nq.gz
    ├── 0fb723c519a480f8c2b2445c437439319bc7366d.nq.gz
    ├── 1058c1bd7215e58148971db6bc1cd9b269649c2d.nq.gz
    ├── 10ac1022ef52493bcf5d2e3fe0f12258a957c04b.nq.gz
    ├── 11039e4054f20d654d6cbcb579901f16742f807b.nq.gz
    ├── 114f2a92afbeb0b07269e66ad8a561ca122f00f0.nq.gz
    ├── 121ae07d2e7ea3a3d87054cff30629df84c6a494.nq.gz
    ├── 12d2b98320940cef0bbf36ec5b1f5c7f65acd85e.nq.gz
    ├── 14c1c1b9fd8703ef42f60c826d7db4eef0093699.nq.gz
    ├── 1512dcd2fb0e76464932a174689b69c773e20e58.nq.gz
    ├── 15e31366653b8c02c121de4f146d0ecbe4d75cc8.nq.gz
    ├── 171172dff468d7f5a6ae6e043b4615e5787a918f.nq.gz
    ├── 1822c22e99c6bb02fa70f26f81c3a9258968d23b.nq.gz
    ├── 1935a1c602647bdec1c87ecaf9fed9021e26a6a8.nq.gz
    ├── 194fb81041ec7bb3937cda301e4f794b20863592.nq.gz
    ├── 19ca97b0d46eff0f40dcdb3cf1262ef1529ae38e.nq.gz
    ├── 1a0a6d0d11b2c582cf3c11ff6043628046d55303.nq.gz
    ├── 1c461d4ae92f090632020e779b002eaf3e2b72d3.nq.gz
    ├── 1c967165d4e999c62c7ec1964bbe473af849a113.nq.gz
    ├── 1d00f34aa68c5f57dbd6e97b405125b22b40ce4f.nq.gz
    ├── 1ec5c3e3a1ed58c4965b4ea38b317c679f6232d7.nq.gz
    ├── 1f1fb5e2689bb04294f1f50edcacc4d273a6cc56.nq.gz
    ├── 1ff3d9c6de49c1f97404d47c911edb5af07a830c.nq.gz
    ├── 2135ce6687c5723eb581066d1744e5fd3970f984.nq.gz
    ├── 220cd700dad62b5a83d8500bfbae7f562e4c3680.nq.gz
    ├── 22fb1f902a9f8dced0c3180ed0187471396cbf8b.nq.gz
    ├── 22fb935542131caf045213e44a7b228f95e80394.nq.gz
    ├── 2303d8878fd65759f5afc37396487abd0d8cc201.nq.gz
    ├── 23b4172891d07d176532e62a894b368ab3659701.nq.gz
    ├── 23c508732117b674c8e819ad889425be04f2a425.nq.gz
    ├── 248cfc7476edf9f6e7b20283adeaeadb12ddace0.nq.gz
    ├── 24dc359fe6ca4cdc8259df82a3e4ef6a59d033af.nq.gz
    ├── 27b761afa5abddfa735ad36376aadb8568b877a2.nq.gz
    ├── 28ed863bf47ff3b9224cae5f928b8a461eb5fe8d.nq.gz
    ├── 2936459e64a59e08d804e449605477b95ff20743.nq.gz
    ├── 29eadf7bac3a67a6c58e54c6cd1dbe6cfd0fd448.nq.gz
    ├── 2b6d2351e6d32be6c9cafceb7d0d29a03c39af95.nq.gz
    ├── 2bb692269f868912c16329d395bb4f7e3b48fd46.nq.gz
    ├── 2c03b217724f907945ac32ca6ccda1d06adb6af7.nq.gz
    ├── 2c9c9860e8454b7575f3a68e271aef953aef0d34.nq.gz
    ├── 2d597f185e3a81625680d6374b6893c7a2913fdd.nq.gz
    ├── 2dd280002aacdfa1891bc9749a195826567bb219.nq.gz
    ├── 2e38b09c8568a672a53ddb950543c4b8ced321d5.nq.gz
    ├── 2f06ed20eddbedec53e644f240af7a1b9862ab8b.nq.gz
    ├── 2f377bda8b645a076e9f6bf9553442b22c1cfd4e.nq.gz
    ├── 321b6d1aa384ccd4cc64ad96819821ba99937be5.nq.gz
    ├── 328e13a8b3e1979d9e704415f1aab43404f9da67.nq.gz
    ├── 33430541fddd39de42a88598771443286804b381.nq.gz
    ├── 339bf99a6b9827e7f4ff1fba7e8a0461e7f75982.nq.gz
    ├── 352a477e7f2ed0ed947d8802e7af306892a1cea9.nq.gz
    ├── 3541f46879a444d8d27260c0a522428e2ac8a2c4.nq.gz
    ├── 35bd07876fd064e36d6ea9ed5a0115c43e9ba4db.nq.gz
    ├── 36fdafe1d5fc9e13dbc079ef799c63ff97755591.nq.gz
    ├── 370a430278d05836bc31078096dc8cb435e510d0.nq.gz
    ├── 37ae5207a22dd0ef21b6691800d93bac9c02f201.nq.gz
    ├── 38b2b61d10c8083a93aaf344bdabae1671792cfa.nq.gz
    ├── 39ce5548422693aa88bb58e0d754e6a69e52ae6f.nq.gz
    ├── 3b171a288b647bd2b39fbd5a975c825eb98aa58a.nq.gz
    ├── 3b7059fa9483a00b3e2bc4c9332108da4d4a0c93.nq.gz
    ├── 3bb0210882a10087f350d98677ae7dc8df6abd49.nq.gz
    ├── 3c9d07ae67ea1130ca32d64e6bf141e6d2dc4b4c.nq.gz
    ├── 3cee17c5e96b1a6e68349f6100d64a67f382fa5f.nq.gz
    ├── 3df65f56a8ea1bf457d00dfbdb45332e5d51ac91.nq.gz
    ├── 3e719b5367411f0c0a7cbf3593049dad1f1abef8.nq.gz
    ├── 3ee0ef6d963909ec34e59fa9b570c4c1a4195ac3.nq.gz
    ├── 3ef4b9584a80c387f52ee10a6468bd5c0e261b11.nq.gz
    ├── 3f411ae7e3b532c2d687dc3e03aee38de255998b.nq.gz
    ├── 40f7311f5d0f92cf60538a95ca57aa555388e84b.nq.gz
    ├── 41adb3feab1665a8eca8134abd3e6a3c8197d976.nq.gz
    ├── 42bf2ce9f8f7bb7b296890c2b7740ccef58b8311.nq.gz
    ├── 4336879d96a0755eb83a925487b0b57da911ecee.nq.gz
    ├── 436bc535ac0cd1e15f90d667c00195a144d8be42.nq.gz
    ├── 46326c109882e3f15b58318d66a56ebd3929ef01.nq.gz
    ├── 46fa8a8788be1b0f312d90bd9544f6fe6b728781.nq.gz
    ├── 4757936b76ded385824ef2bbe896154a883e99d5.nq.gz
    ├── 47a31bc9d657ef5ba89d1889963b30ab32f1ebd5.nq.gz
    ├── 488d782fa5708d2f6614220e095aa5206bed8d71.nq.gz
    ├── 48903cd23fbe38ab35afd316d892632378f9428f.nq.gz
    ├── 48c351411c0de87c82a0e6ed93d85b899f68ad45.nq.gz
    ├── 4ba59042aa7e03911b6fa222ef6d44d91890b916.nq.gz
    ├── 4c53cac2cf5e8dffca23773531e473a0a338595b.nq.gz
    ├── 4c99f0102339905b49cde1cb842963524b748c8f.nq.gz
    ├── 4d16e309a2840794fca91c1b6efb487773ff6039.nq.gz
    ├── 4d450b1c28da62e316d913259886819d42d911f8.nq.gz
    ├── 4ffcd03bb5d5183f2e25a1271f610cb0ff78e3cd.nq.gz
    ├── 507e6043fbf4a69ff507c2181c3ad014785af416.nq.gz
    ├── 50efca72c89cf077efcc58e78d8cf8f7090c702e.nq.gz
    ├── 52727bb74db05e041760b78710b978a9ff24cbf2.nq.gz
    ├── 5306075354e5905ffeb21067d65e708f40bdcef7.nq.gz
    ├── 5380de17929eac39815ce0c8bb5829b90e025c2e.nq.gz
    ├── 53c7978463ac544c280052933bd51f75a0f4927c.nq.gz
    ├── 54e846654d9abfb938fb18c089b8ed753b14dd8c.nq.gz
    ├── 55175ca206efca9ad66a1c17a83d94975ccd4b17.nq.gz
    ├── 55682445c1ca8c6335b490a409003a320b2c77f5.nq.gz
    ├── 55b50444da985101744c52c4d801e55a3be5d4ec.nq.gz
    ├── 568639c2efb096dff6be35987823f84fb134f984.nq.gz
    ├── 575c551db228742ab46e2df16171bbe5e7ec3e5a.nq.gz
    ├── 57bbb3d855c3a1af5f900b7b884d3c3f15aab190.nq.gz
    ├── 591b14b09451bdabd6330a4240179b5931d41df1.nq.gz
    ├── 59493f6f1a7fd517d23713f9ed7b324dfdfa1e14.nq.gz
    ├── 598365b3e7be369069c772947844ab2ca1570ce5.nq.gz
    ├── 5af7ff6b095cb50641af95fc5ef7b7d92d0b0eb2.nq.gz
    ├── 5b8539ce95d0ad4ab3dcfe71b93e89c72c2fc1b8.nq.gz
    ├── 5c41a6d8626f4941e06a57ea187eaec3010d2449.nq.gz
    ├── 5c46dbde61bb3ec3300a922ac53c91eef2230913.nq.gz
    ├── 5cee2bf5996029ea056a063035c11d0c4fa0fbb5.nq.gz
    ├── 5fff33cf3b956f3bfebe14362aac8d5d6eeb6f68.nq.gz
    ├── 60ff2dcec5a8d77cdb3bfb1f91cd17dc66255d0f.nq.gz
    ├── 62e4d06e7da8d5c4f9b85a05327ac66228c193de.nq.gz
    ├── 6639e1a5693a94bbd4d53111a850f73248cf497f.nq.gz
    ├── 6699308e14a8c874abc17265a1d0808c775bf879.nq.gz
    ├── 67223e4119b16ac0d4531afdeae197c9e2a0e26c.nq.gz
    ├── 67e5189e6910e90a643448a185bee7b49b69303c.nq.gz
    ├── 683d4918ea36e14a4a02d59aa7a2b75d183b282e.nq.gz
    ├── 69065aab7795b300e733462ca6fa78cdb1ec080d.nq.gz
    ├── 696fce18e0c47719c8e57b13d8d9438e883e7cc5.nq.gz
    ├── 6a689fe94a3eb77361b87ed738cd714a37fa9aa1.nq.gz
    ├── 6b39c6e37efc7ddec6c500a73f1562074abe1079.nq.gz
    ├── 6b9d9ea49db3d6323b7d8ae07999c3b5f1cecbc1.nq.gz
    ├── 6d49f58433793b3167f66497d56911c4e325db8b.nq.gz
    ├── 6d74e0256a072b0925c9389b21008308ceed35d3.nq.gz
    ├── 6fb07d8eb3cb6571fbe779892b6b5a15ce103e4e.nq.gz
    ├── 703203ad1f435facb64c7690bc0d97a51adc82c0.nq.gz
    ├── 72268b5dbae7b73b1751d5fd6dc254d9f375817a.nq.gz
    ├── 723bd09bbc15332733153c029e237df15eec949e.nq.gz
    ├── 726dc1c0352a2ce5d0bd99678198cfa8ae074074.nq.gz
    ├── 72d440fdd47258f431df02c8ed340a02b673ed4b.nq.gz
    ├── 736fdf8ae9854487979238b26628cc6ec8e6d18a.nq.gz
    ├── 75362a671b489b531536abf3dce7d23f954882a2.nq.gz
    ├── 762a8524a065a36b2ee47d1922da3a990db4046e.nq.gz
    ├── 7649a7330c9a66020d48e19ef52fd7ba8201d518.nq.gz
    ├── 7703e12fe92f1a3e60f6086682cf71bbd7816ce0.nq.gz
    ├── 77f75030cb07953946ccbad2979166891ec38b18.nq.gz
    ├── 78053f04a36939c2b994cc78a1807c9982a5fbe9.nq.gz
    ├── 788b1a807cc57449e80f6675de70793833a1450b.nq.gz
    ├── 78dce43d81f0ffb1ffcc38e7d73faf550f9bf3bf.nq.gz
    ├── 7bc76b96c39f5a6eb3fab16c754a7294252df175.nq.gz
    ├── 7c1e45c763c22bd49ad3625bf1f6b1558d4c4467.nq.gz
    ├── 7c2e2223c4def300f6cb6e4953b07fc32990bdae.nq.gz
    ├── 7c58a873fdc2fe2394b35e7722fd747407648bf2.nq.gz
    ├── 7ca78f753e909c633274e8cf42d50121adbac682.nq.gz
    ├── 7d7eaebae2b7f8acf681b84d3e33afe65b83aff5.nq.gz
    ├── 7e67fc6f6bbb2f7909871427a37e62d08395955d.nq.gz
    ├── 7fae374d51b871ed6c49d9954f9556642379c7f5.nq.gz
    ├── 7fc8b4a351ccd5174931f5062c230db30c82f0c2.nq.gz
    ├── 807dd7e7d38493dccdba6aead94c981d5e3eda07.nq.gz
    ├── 816bf89da47faf24ec8824adc1c762d92b8d7bc5.nq.gz
    ├── 81844a1ad3b521796d71ee66c8940beae5235e87.nq.gz
    ├── 8228d2be651155d4edd033af2f5758309d22f2ab.nq.gz
    ├── 823df1eb3ef7069202032da6eb877165972fddd7.nq.gz
    ├── 8275c820f2392cdb02ae1f81e05b0a19a7e2ec72.nq.gz
    ├── 842d39a217405c906839ee4e6b636f86f6aa54fa.nq.gz
    ├── 85612f634b96d9366f4faa9b2f2bdb4687e30404.nq.gz
    ├── 857b663aa53b647b3985bf998cbb5d2dde5f20b6.nq.gz
    ├── 862f914b31258a91f889e28636e2ce4bffe419e6.nq.gz
    ├── 870a708d02dde2c4afd1f672588f5bc2d3e18479.nq.gz
    ├── 87b304e4a1a5fc266a39a9484668f16ac654f495.nq.gz
    ├── 87cb887f82937553cb62f68c56b66a9c807f6034.nq.gz
    ├── 8825377c32ce58c37ebc8689343a757bc115aefc.nq.gz
    ├── 8918d0357171b997e466e2244b1ecf514ca5d7c1.nq.gz
    ├── 8a395c83bfca2bbc98b632f2667e08184fff3611.nq.gz
    ├── 8d6a2fa5c54133beae8ab034fbc45d7c518b8c18.nq.gz
    ├── 8df5f22dd7b8d65ad412d89f5bc8245589add428.nq.gz
    ├── 8e04b2c4b82fa9812ae1d3c1dcff4f09a123bd62.nq.gz
    ├── 8e66cb186fca1a7b773f7cc3cc1a7acee575d186.nq.gz
    ├── 8f26e514d8db3ef472233feb864edd465c24716f.nq.gz
    ├── 8f2d13404244b34b4b73e2488c04b2d801bb07d7.nq.gz
    ├── 8f515bd80b5545e2d51d804ab15391cff8ef1c99.nq.gz
    ├── 9056714cbf6b38c32c85000819d15f6842bd36fd.nq.gz
    ├── 90967e357919291db8b6417b334bddf1b8ea1ef5.nq.gz
    ├── 917eccf322b02f959d352d3ad9d886d6c931de74.nq.gz
    ├── 9258cbeb7b5695593eca5f757d8c2eb7b9cce251.nq.gz
    ├── 9300cb29c217abe8c452b7e12a25c80c107adf42.nq.gz
    ├── 93efd55ea199509ba5ad88d090d07382709ef0a0.nq.gz
    ├── 953ecf3fc3a6e9e1947f71708e12fe602dce6b95.nq.gz
    ├── 95e13772394d784ccd2af9a21ab95fd0bface973.nq.gz
    ├── 966398ec6cd4b62aeebee08ab770280ddda86f27.nq.gz
    ├── 978b137f87f80eb8285f0a5c79e8995e543ff32b.nq.gz
    ├── 97967bf1095fe365a391f41ff69b429118d1e3c2.nq.gz
    ├── 98b2207eb5bb9020b855d2ce0f177b60e24cbe21.nq.gz
    ├── 9a70feaaa1010e88835884e8b72dfdd5df71c67b.nq.gz
    └── 9ac431a51523088c1414d04cea042962e4594aeb.nq.gz

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

[celery/kombu](https://github.com/celery/kombu)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
