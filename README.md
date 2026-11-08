# Repolex Knowledge Graph of canonical/mysql-router-operators

RDF knowledge graph data for [canonical/mysql-router-operators](https://github.com/canonical/mysql-router-operators), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/mysql-router-operators
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5dd832364a764794de5dde2b5d3916f831f041b7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5dd832364a764794de5dde2b5d3916f831f041b7
│           └── chunk-001.nq.gz
└── blob
    ├── 0060aafa4a6a97f83a703e2128daf0f6438e8b29.nq.gz
    ├── 00f007776f60578e139ee281eaa189a33f78c5d0.nq.gz
    ├── 017437ee149cfb3439315b191f9e2b0d14cdc520.nq.gz
    ├── 02c00804d7ef57601cecf81d83ec459376124bd1.nq.gz
    ├── 0436ecde95649628616015baa58e4fec8146ca76.nq.gz
    ├── 05dc4e23efc7f0fcf066096fb55bf1326742330d.nq.gz
    ├── 0604f86107c6e472a17262abb5ae0e506fac8bb1.nq.gz
    ├── 06114fbf074bb0d2694dc40023437b410c6a338e.nq.gz
    ├── 061ad7f09444da204b97ceaa56ac495863fe4441.nq.gz
    ├── 08de6fb087764b1ac53f23d3d8d73139bac6811d.nq.gz
    ├── 0b676740dd0396dc1e90a15a6d3ebeedb34b3ca4.nq.gz
    ├── 0ccaa70eb226090f9aff11057576c9168099950d.nq.gz
    ├── 0d203921de29002a89628363307c894523b69a03.nq.gz
    ├── 0d69cb45175be46f4859123e3df5346002dd05eb.nq.gz
    ├── 0dba566e9292f68faff912e9ec18719cfc053cb2.nq.gz
    ├── 0f64ba95aab80ec9217947f2cb520d4c3c2e2501.nq.gz
    ├── 0fa286782807f2043cb338dc441102562521be4b.nq.gz
    ├── 14106d50b175e910b364c43e11d3b74d28825a7a.nq.gz
    ├── 1479f18ad5d766650e7b45aa0c7f961383effdaa.nq.gz
    ├── 14bdcae7929489173c28de60f389fc9af57222ff.nq.gz
    ├── 15a4f0b86ae2c6142bf52ca0059400ad97803d1a.nq.gz
    ├── 15a78cc947068237f94cfd374a6ba7cda9d4e798.nq.gz
    ├── 1716ea2b32b86eb272bfbb411577f882423d73b6.nq.gz
    ├── 17c6a11d75ebaa6376f74ec55a844b4e411d0b6c.nq.gz
    ├── 194fc2f92807d4ab4eeb640d3de34fcd997ca571.nq.gz
    ├── 19bf3be7ef686dee3b2f9caa9dbde8eee3065e5b.nq.gz
    ├── 1b182cbd154732fd91f4b544f458d85f3685ff5d.nq.gz
    ├── 1b3fffc91ee1281692c4e17974e00658f54cf698.nq.gz
    ├── 1dbba70aa5f9774fbeefcfdb33ccfb45be9c06ac.nq.gz
    ├── 1e7ff8405a21c5b1f06932492a9e54bc04f8cfaa.nq.gz
    ├── 1f576bf66db04b8e25b934f7cd6c8a57662988ce.nq.gz
    ├── 1f9331a8bc1ee6d7e7abcb2659ad980e77d1d7e2.nq.gz
    ├── 2557f795aebf795ae6fe6adf0b94517c24b9743e.nq.gz
    ├── 2623da4fc938452a23c226acef6ec6bee237c1bc.nq.gz
    ├── 27dc31c6a41bc40bb84b2ca5ba404d7ae1e4abe5.nq.gz
    ├── 28354ba75b436b68f76da1e26143a000ada603c7.nq.gz
    ├── 2978b5eef91a7678ea045833dc6ff9e992ebb682.nq.gz
    ├── 29870819214bc691d0dec9c6c7592654f095aec3.nq.gz
    ├── 298c4e75d4f47689843ec2e820bc45db1603da9a.nq.gz
    ├── 2a5692e3801e5e8b720d79036ca73d616f82bf57.nq.gz
    ├── 2b73cb730a352a6ea764c779df081d9bce853b01.nq.gz
    ├── 309ee12fd2c113853b8b270761c68193c3c8978c.nq.gz
    ├── 33fd0113ca09c775b63de738b102696d21d3cbd6.nq.gz
    ├── 3aea50f0fcd78481f9e038939f53f1d1099c0a47.nq.gz
    ├── 3cbbfad11d9721547afde06012ff3b54390548af.nq.gz
    ├── 3e5ef0cc8f68a877b69642bf5b7bda62b0100a68.nq.gz
    ├── 3f7d6bc866f1f013fabc2cb32a08bfa817f715a0.nq.gz
    ├── 40fdbeadac0091aefb95d73155d5ed8c6c2376f3.nq.gz
    ├── 41d9632b265a8a4196f4239eb5db8789ccee41fc.nq.gz
    ├── 437decd378860ec560a67441682e244b59713a92.nq.gz
    ├── 444bbbc940c5896402e0979942607590ad773b43.nq.gz
    ├── 4450837a7f32004271a627f4c0174ddd9b4806d2.nq.gz
    ├── 445da385d6012194857d363794805e32f249fbf4.nq.gz
    ├── 44965cc1e04e8f24fe45e43a01c22a0098e6f8c8.nq.gz
    ├── 4557e3184d9b68c0c683f747ebc16a513dda583f.nq.gz
    ├── 456797165185b32786c98b88b4a7c42aaeb41e0a.nq.gz
    ├── 45bf089f12f94459152ed5bb3a69de92f64f5fc6.nq.gz
    ├── 471175b5ec5d1094a8b232fe258fd63a04698859.nq.gz
    ├── 4872076233eccf9459ecbc51bf3ba6a68e0e7a0d.nq.gz
    ├── 48daf51b49c1292134809f4890ac51b239e6d27f.nq.gz
    ├── 4a264f38937866a77aeaa2a5d95d73547d280b20.nq.gz
    ├── 4b31a46063343e007ca0fb73e56cf2d40bc8fd1e.nq.gz
    ├── 4b634450cd7d3da9109d7dddc996a6c7e9c1fa44.nq.gz
    ├── 4ca8b67991eb466f965ae8956d9340fc2f979e4a.nq.gz
    ├── 4d1a6ce42c3859ecae6f33c60871a1dc8ed93020.nq.gz
    ├── 4da1608835406234d8329d8e6ca55b17c493dafe.nq.gz
    ├── 4da96b3aad17485cfd438e3af8ed8e125c108a19.nq.gz
    ├── 4fb65aeb32133ee0ff637ace7ccb8ff6aa574edc.nq.gz
    ├── 50cb456347064ca9baf67d5e0223d37b07c4a6b1.nq.gz
    ├── 5343e9a79eaf69faab20b7e6818cc452779159c9.nq.gz
    ├── 5348fc41e1cf483a4822cf410e44cc07a98a2d8a.nq.gz
    ├── 53d18bb4c3956f94a5c6b7ba969dfd51b87f4d37.nq.gz
    ├── 53dd8be08041b83786020243d98e385c8807cd38.nq.gz
    ├── 54461a78ea93637bfe7488a0be12f302641937a9.nq.gz
    ├── 58971c75db8e8725b3ee5b5fdfb3adc90ac546ac.nq.gz
    ├── 598c6ed33c5e78f08e0697775691162bfa847bf3.nq.gz
    ├── 5b9bdd94bbb25802a52ecebb1f960a23e7b54d23.nq.gz
    ├── 5d0df9244377490abb46328812b804832be9d9fe.nq.gz
    ├── 5fa3ddd685a3af4ddee844d38560888d0a04e09c.nq.gz
    ├── 61dc2b63633c8dc911071bd2b0b6621ec3aa4f02.nq.gz
    ├── 620329ab45b55bf2243ceb9ecdbc189e4064f4af.nq.gz
    ├── 67c9230dcdeafe6a48107a05eb1604168bcb91f3.nq.gz
    ├── 6b1ec7731ba7d602bec0f149340724ffe47733e4.nq.gz
    ├── 6ca0272a725be0559a2a6b99af06a521c29c2389.nq.gz
    ├── 6ccd559eabeae93e4d23215fa450130fa9b37ace.nq.gz
    ├── 6d6a0ed7c93ca3ade11ffae4710245eda61207d9.nq.gz
    ├── 6d6caeae4acbd12f01f9c193e77d80732d281ea2.nq.gz
    ├── 6e1276876cdede26593a6b17ec9634b6423527ff.nq.gz
    ├── 6f000bc945a39f2702d41501c024248471b289ee.nq.gz
    ├── 6fe3a57910226e7d9510c7a2315f50de87862973.nq.gz
    ├── 7037e3f30e6fca2716cc87661ddbbd5e1aa1bcda.nq.gz
    ├── 7264f1a576c8b78fe7a8db097e9de913c4fdc7e2.nq.gz
    ├── 733694eaab509fd43bbe686fd4a9785c2de52f74.nq.gz
    ├── 73a23149f2c2e6b95044592277e8b35837ac4242.nq.gz
    ├── 73f58cc425fe8f497b98783ee0ca881ce0abec15.nq.gz
    ├── 746c3b57a885d4d7ba78ce44608e4aefd37191c4.nq.gz
    ├── 74c022fa15034f0e7d8293edcbf47010fb9e21f6.nq.gz
    ├── 750734ef222af22bdcdaf997b718ebe9a5983120.nq.gz
    ├── 758fad1ae61277bf07c7525a3b04c9d45f067b50.nq.gz
    ├── 76da633a52126afc7a486c15e6d875d4958fa6e8.nq.gz
    ├── 772e6247e4520033ab9f5c925bd8493feb500179.nq.gz
    ├── 774687e1a027230b07052a1b477adedac138c065.nq.gz
    ├── 78afea9f8ff909d34534c4bf4c98bed45d1e18a6.nq.gz
    ├── 78ef531c624795180c9692cb89bded0654f69290.nq.gz
    ├── 7a18f50eea6d426383d2161f481d40dcfeb5a41a.nq.gz
    ├── 7ad39f426e2d3648d50a6bed1972e7d43e84373c.nq.gz
    ├── 7bc5336c3bc571c9c77cd7bb90e222e0e46bf76f.nq.gz
    ├── 7df8986f9239bcf70b830a3f9a02f85f00eb2699.nq.gz
    ├── 7e3d110a0a7bf1ce8b82208b5db42445ea8c3760.nq.gz
    ├── 7eeaeb3bbb72675c4fa16d7826681b6647a00cb9.nq.gz
    ├── 7fd3c621c4e99772f13615674b0ac2c870a0dc45.nq.gz
    ├── 7fe626eb306e209f86995378f708b0cca5e4e94d.nq.gz
    ├── 80538c902ee6f765eaac15ec015b9e9566c97362.nq.gz
    ├── 80d5c980d0345fd71028a113ddfae530e5c71d1d.nq.gz
    ├── 81145df203377afd9180203bf6cd5d9caa5e9ddb.nq.gz
    ├── 8147359d6337490c59d8c1ff2cc5d694931fd0ce.nq.gz
    ├── 82873741d8a3305eec459e642a09d34f314f9e9f.nq.gz
    ├── 859fc407023a8e0721ad26a21c6faa5a7daef4bc.nq.gz
    ├── 8736f994b25a29c3f636debe1a30e551a19a8d0e.nq.gz
    ├── 8e89d06c411aeccafdd786e62fe0cf666fed2339.nq.gz
    ├── 8f48835fff3e31b23fedd305efdb3fbb341bc3ce.nq.gz
    ├── 90181d0f676f2d5762a77eee91aee0e04d616529.nq.gz
    ├── 91da75b95aa01ad988984e4b9af04ed41f440f5c.nq.gz
    ├── 93df4441d2343742747069845bfc2308ef72f4c4.nq.gz
    ├── 943ee9497207ae093b2a9356814e54992dc46e2f.nq.gz
    ├── 9717119030cd18696316ff2cf51106755a46d4d8.nq.gz
    ├── 9814455f3d9cb8d20fe18c39492c9f8225ed7fac.nq.gz
    ├── 9886fc2b40dfc111e4cc7eb94e14591d5ee21aab.nq.gz
    ├── 99e35c6ec29cac32cb2fca00a89b42d2d4198622.nq.gz
    ├── 9a2199a8603ec421199f8f82ac37bd09cba0b554.nq.gz
    ├── 9af678836cf11d87e15f8fba9dff0f062162b245.nq.gz
    ├── 9c6a3ba6cc7487a8d34359f7a0aea9574b29942f.nq.gz
    ├── 9ca1c192988ae551c46d68b84ef853c4f794fbc2.nq.gz
    ├── 9e868f9264bd717add92acaa915d16d4db35c973.nq.gz
    ├── 9ef36aca6d2980f250f98016204ad1e4b0f11d84.nq.gz
    ├── 9f9fc4488317edea856ecc138e6ca14ef32f57c8.nq.gz
    ├── a25f5c343985f1e8104b980da696444f97d22aa2.nq.gz
    ├── a34d09dd43790a9652c7a46ab48bcce1e2c694e3.nq.gz
    ├── a3e8c4851cbca266a361290cfd0bb7e18404fe3c.nq.gz
    ├── a520a083b341cc10d60e4ec91173d3b0ffecced1.nq.gz
    ├── a7272b2a805596368b998a7f3640bee3f42185d7.nq.gz
    ├── a9f964e78bbd66a7f8235a9c31fc1cd797e31c52.nq.gz
    ├── aa569d14e8acc51973e59299461005ec051d618b.nq.gz
    ├── abb0c5cfb3a5c71c698f24319dd506b5608a7814.nq.gz
    ├── ac32d60ebd40444e2bf18aea0a6a4b3289b2ffde.nq.gz
    ├── adb7b627012fa45c0ba5faf7f5beb9d11ddc03d2.nq.gz
    ├── ae0b6bf4efb314132220ed26296384ca7d267473.nq.gz
    ├── aec91e9e3654ffb91c0c13a27c914e5e3e410c0f.nq.gz
    ├── af6a36fd967c51a55f056b899e89b5027a54c147.nq.gz
    ├── b37d4ed6179117a5bd1661184fea12a1dcc208d0.nq.gz
    ├── b3811c778086f1c31ac0b54a24e2e13a45ba7039.nq.gz
    ├── b4b01ab653ee073e1f618285d4ede3a2c8e78050.nq.gz
    ├── b70d8d5afc03802bbea66e622a50eb2ef9000a7c.nq.gz
    ├── b7f808a0d7a320fe9cc86c220f3715cd23ca1711.nq.gz
    ├── b95ee9a09544b69ba1aec2bc4c2d458e574d4edb.nq.gz
    ├── b9882094ffcc54d443db2466144fee3b2e8fc53f.nq.gz
    ├── baee38bc1a7811ae23eca332851fea3b3ac5c350.nq.gz
    ├── bb490c9b22707d4e71923cbf4248f182341a7bc8.nq.gz
    ├── bcc65177ebc0ab85540f5ffaea43aca154489857.nq.gz
    ├── c0bd3d1b18d92900c2b5df47f7986cef1bd6946e.nq.gz
    ├── c232362feb12d95303f8c12917bf3229f0df4cdb.nq.gz
    ├── c27d27abb42287e920be28d445a670b86d1ff529.nq.gz
    ├── c5646695ad42d2474386734c984c06665c4f93be.nq.gz
    ├── c632066198ceea5a1e266a09f96a832008b1acc0.nq.gz
    ├── c75452917484a09463d4fd22ebb1b90e7f2c27c3.nq.gz
    ├── c8d2bc2941118a9ce370c8a68da4626191a8bf3a.nq.gz
    ├── cf069ab2e31e0bc00e91379b7b654734cb6bc72e.nq.gz
    ├── d03a63ba4593aee91a2315622b2de634289e25eb.nq.gz
    ├── d04e89f36579968da25075d72a99666cbe13a2c4.nq.gz
    ├── d3944207ccdaae42beb931dcc2c290b202325856.nq.gz
    ├── d5239cb39988966d8939d20a325d50f19fa2de37.nq.gz
    ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
    ├── d65c8efb99ad9c02c4e8624e3d2875f8a213af14.nq.gz
    ├── d84430360f3e10bd5827e6d3e5cae1c65458514b.nq.gz
    ├── d944b0c470ba9e94f3a0445afde59cf8bf09c6a2.nq.gz
    ├── d95622c560c7336eb87b78736636e881e643b9ae.nq.gz
    ├── da674d7d0bfbaae8be12f0c056abd223a6a7a1bd.nq.gz
    ├── db3bfe1a652400bb6963dfc7ede76820781ee928.nq.gz
    ├── dd3ca1f098db64fdbcf2d66a858c482f652afedf.nq.gz
    ├── defb25c09a67a8e990c322b2fe02a9b80e7f2df2.nq.gz
    ├── e06ece86b450f630ac95e50c8c4eca1aff965d55.nq.gz
    ├── e150850a991f1123799794b28dc8ca5b4376708c.nq.gz
    ├── e159888b8551be53f9ff8be05c55401e08ff2c77.nq.gz
    ├── e1eb44742bf4e8acac826470f09424dbc4bb4c89.nq.gz
    ├── e2b7c11042c93692dd75756e79e12a06f19530ef.nq.gz
    ├── e5e9317c1f626fef977b0c39d8f1f4b355478b1d.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e77cfba92e4df1b85c4734b343e5b4a1b9965400.nq.gz
    ├── e815f0712cd0b5a47b4c33d98c2961432ecaa05d.nq.gz
    ├── ec1a1f78dec472cebcf451520e0627a4ac6be6a0.nq.gz
    ├── ee1ad93c8e5c74d7cbd9ea3091ecd78f017fa32e.nq.gz
    ├── ee9ae33b128ee45642868d22392fea5e869ad7a2.nq.gz
    ├── eeccd844a76971c0bd3900bd2e5dfd0bcaf3f6b9.nq.gz
    ├── f14eb2ffc02dab3b3cee4d55d4f9470b0dbeae8b.nq.gz
    ├── f188d1bf530e553c5e7d3f0913cc3eab1a7fbbb2.nq.gz
    ├── f1f6e7b487b2cbdec427b7b1bb21755c2ce12b93.nq.gz
    ├── f221f7bda1004b8fc383998d6cde90491c63f15b.nq.gz
    └── f236f26e25e15973b1808d8efe88436ce811f85a.nq.gz

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

[canonical/mysql-router-operators](https://github.com/canonical/mysql-router-operators)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
