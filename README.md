# Repolex Knowledge Graph of huggingface/dataset-viewer

RDF knowledge graph data for [huggingface/dataset-viewer](https://github.com/huggingface/dataset-viewer), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/dataset-viewer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fb279f652181b3932dd021585e106728cc030c66
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fb279f652181b3932dd021585e106728cc030c66
│           └── chunk-001.nq.gz
└── blob
    ├── 001290941e3c8a3dc7522154e22060c09279c5e5.nq.gz
    ├── 00540910fd4cb129412c5a5427d0e56149c8cd0e.nq.gz
    ├── 006afb1fca1c0a6b2e19d9f4cc8edb7baca5eeb6.nq.gz
    ├── 00a86ec6600adbd15fa9850b7252a001ecb98ca7.nq.gz
    ├── 01077c7a42daaa7a8681a57ee9e1bc8675bf344b.nq.gz
    ├── 01c34a39e83c981e9fbdf43cd975abc3778e223c.nq.gz
    ├── 024b921586edf971dcb255567ca3f4f218033473.nq.gz
    ├── 02e03abc639bb5fde3665172482186a2dd63afc6.nq.gz
    ├── 0341ee561316e758fe4b4063736de535baff54a9.nq.gz
    ├── 035e724aca91075813ccad0ca7b7486e6f000d97.nq.gz
    ├── 03c8dad00bb8ab1d3e2436b7f55cf273ee5037e5.nq.gz
    ├── 0440a58d2c2e90eba6d32852bfed46d9f5696a66.nq.gz
    ├── 04469681076a6248f8a01b668aa04d9d396a0cb9.nq.gz
    ├── 056cae0b3ff00f578d1d7685621e476084d35823.nq.gz
    ├── 05bdf28db93380e5c1e6ea2cf9c499bf6e72d3eb.nq.gz
    ├── 061ee3f2e6cf0be1cb7c15a8d5b9373e4df641a9.nq.gz
    ├── 06800d7dffa36ecdfc3c894f71ea0352edc3189e.nq.gz
    ├── 07b6f260d6ca723f6bc4210559efa213c3fc2c5e.nq.gz
    ├── 08667fec188459fc8079189782a3e22678b4464f.nq.gz
    ├── 0932b892c9317e67ea0964536226778790bbc4c0.nq.gz
    ├── 09333d6227c90bfa04bb2deef3e9b284a1f6bee0.nq.gz
    ├── 09385b274a29d3491a077a1a9d32386eb875dd77.nq.gz
    ├── 09b36318978484f0c461d9c794cded7f762ff0ca.nq.gz
    ├── 0b529b2f3199f76c277ab0f8f9b0c336ed5a761f.nq.gz
    ├── 0b75056c8fcbfe7ec137fdc674e590ec6da8e5b0.nq.gz
    ├── 0b98c075ca89fb14abb1f8ded527bff00e2fc983.nq.gz
    ├── 0bf9a629c586a56ee5ceeb740ced4798803e3bd6.nq.gz
    ├── 0c06ed1215c78c894b20333391d9283a94740754.nq.gz
    ├── 0c5a1da3c036b8bd76cb6712a92e6f7cb6fcd606.nq.gz
    ├── 0d1994ed4cd95c4baf45030cf6c0308416b546cd.nq.gz
    ├── 0e0ad1bde9ef2225a5b7f398108fb1f47bc71258.nq.gz
    ├── 0e47acd0b3b56705a860f89a8c71b1449d87133d.nq.gz
    ├── 0e88eed96595cb2a38b7b9f1473b481c8ce51021.nq.gz
    ├── 0f569ecf102e4c0e9d35a854fac11dce42f16756.nq.gz
    ├── 0fc120a87a65b9cbc9b12bd623dff63fea6e5bb4.nq.gz
    ├── 10859a686e0971c027e987bacda690ba4d4ea31a.nq.gz
    ├── 11365946f80facedb2378d2c393baa3ee3ee31e2.nq.gz
    ├── 1199db64c40bc5864cb6f608dbe7d41d49cc0189.nq.gz
    ├── 13934b9a875d98501d72254145af61e18399d744.nq.gz
    ├── 13beceabd0de6405a86ed71af03e8a74566cab98.nq.gz
    ├── 140c438743af5caba6cdff4d9aed139f59e2155c.nq.gz
    ├── 1449fd65f5213f01bf59f5e72cb0d222503dfab9.nq.gz
    ├── 14f829644c5f7e324d2b8a15c3edf92aeb21e6b9.nq.gz
    ├── 152710bfe3e325bbcbde350ca45219220fe80af3.nq.gz
    ├── 15cc2413f609270ba55189c3418c5a462cdcadc2.nq.gz
    ├── 1674329b97d3124161e7a3f1ea17bad6eceb81cc.nq.gz
    ├── 16ad8dd65e15799385ed60b9f46098a04258d804.nq.gz
    ├── 16cecee3cd45f71bfeaa66d6dd07c617992baca3.nq.gz
    ├── 17a20486abfba81751088e682ecb67edd7130688.nq.gz
    ├── 196005f901a543c1b9f1a2ca120eb1b023153f2d.nq.gz
    ├── 19b0f8d8b906f5d002a62a5e9e1e3dd3589dbbcf.nq.gz
    ├── 19de3ad303dcaaebbf827150bfc15e7e06f22dd4.nq.gz
    ├── 1cce1631c9346ca463fca63c3dadb5ca496f3dd1.nq.gz
    ├── 1cdb59ec1e727e890e70b6a20738940a683baa7e.nq.gz
    ├── 1d2e17db85be93a488892fffa0851d3acc552b7e.nq.gz
    ├── 1d7f29dc4a1a7b128347caed77d79e01bd4a54a4.nq.gz
    ├── 1db4f279ebc9535610dcc2d00a376fd2e59098a8.nq.gz
    ├── 1dea5ce6adaaca7b52af35cd6e6a13f45c311bf0.nq.gz
    ├── 1e1fd9e577c390f8419a509d105f3edf3063ecf6.nq.gz
    ├── 1e73afd7b6086264f909b65dcda0b8e979178d35.nq.gz
    ├── 1e9d0c5a99295800886d2dd1d200273f83f24960.nq.gz
    ├── 1f408cea46562d3ccb1781d872b2825e5c3b655f.nq.gz
    ├── 1f454baa19a88985d63dedd96a2c68557d36944c.nq.gz
    ├── 1f74425c4cb251e09c0e42465cdeb716e125db18.nq.gz
    ├── 213f09f7dcc2ab8d3cfeff3b82553fc6e5cd340d.nq.gz
    ├── 21c64d80aba1ae62ec21668557ddeb5f6de96979.nq.gz
    ├── 21d0c4433d8fccc64230def27eae63ab0b2ba0f7.nq.gz
    ├── 22c9dbfc8cda8a1ae54c306b1b1040a33f2df755.nq.gz
    ├── 23a00571d204857440b4fa443aef72d07dbdd028.nq.gz
    ├── 244eef9240d4e80bca793e2bc35f61e87af0270a.nq.gz
    ├── 246f554602800f7fb0530070d7b941ccda11d7f4.nq.gz
    ├── 247f9f61ab223650073a114e749191dfe29d8d25.nq.gz
    ├── 24916585df30238f9d03e9c8a770677bcf496a71.nq.gz
    ├── 25a709673e02038b478de61beb96230b1de5a1b9.nq.gz
    ├── 25daa5a42a51d13a034f7662144e638acd202293.nq.gz
    ├── 25eb2ff012b4b5c48f39bebe1b45977d116f7cbc.nq.gz
    ├── 25ecc26858dc4ee63071e01a865f8553100f2b49.nq.gz
    ├── 2648020ca08a00730ca6d2a6864cb37fc73f6df4.nq.gz
    ├── 28037a741e3b952f6bdeae7b90af93a7ac5b985c.nq.gz
    ├── 282be592c3a2fb29bee281a627649110bf223fcb.nq.gz
    ├── 28def059550a032d33e276cc629e760f082bdcfd.nq.gz
    ├── 28f609ea577669a60851024f0bf0b4635867a98a.nq.gz
    ├── 290a7fe3617cbda8c0514b3e36a41cb8910eb799.nq.gz
    ├── 29133ae48171c45013c38bfd7422e603402cdf53.nq.gz
    ├── 2968687cc1c9c1d5c7d588904f10071248687f09.nq.gz
    ├── 29759c3bed7677874345111d9caba1331e60123f.nq.gz
    ├── 29afbde742080a50b8e3ee01df2217bd5978c3cc.nq.gz
    ├── 2a10e3d7a371483d1378efa87046d9f814a816de.nq.gz
    ├── 2baa234750e857256f57da203d5ff2626b4a92a8.nq.gz
    ├── 2bca11dde42c60aaf16419ad328b30dafff801b3.nq.gz
    ├── 2c88a975856869b30cf1c362662b4d8f71b23e3e.nq.gz
    ├── 2d358fe6620d635253bf8dbc220605c8519aeab4.nq.gz
    ├── 2e58eed765a410b60d415b5cd20af96dbba44009.nq.gz
    ├── 2f6cdb1abf1b7b8f3b5979536218cb706e4979c5.nq.gz
    ├── 300def3d429dda8172d24079928b354659f12c32.nq.gz
    ├── 307da61041e58c636d5a4af8780108d76ffe9849.nq.gz
    ├── 31767937f4a53d387e6076557e334c13456910dc.nq.gz
    ├── 317c52355d40a5e980c74981ca17e66fbe8150ba.nq.gz
    ├── 31a3f3622988d793e5786336b115bd02e72e6dfb.nq.gz
    ├── 32739951dc006a04db338503f3b641b8f14307d7.nq.gz
    ├── 32e9e0624902069487860c45964943cb6a0016c1.nq.gz
    ├── 345f8d1bdc80d6ba3ded0f48cb6bb0a7d9204c82.nq.gz
    ├── 35d813d39fc929ca3f67dd23b82107f227f3b27a.nq.gz
    ├── 35fba1910e64f75014424848c9697fe1ce3d9ac3.nq.gz
    ├── 3620b33cc01b71e1beef9a15dedfa69dd3809be6.nq.gz
    ├── 36a538d2b5c61fed1b5557ec78ff456c02ac20d4.nq.gz
    ├── 36aababdfb2f8044b464786b3ddf0ffaebb501c3.nq.gz
    ├── 371c81d7ad2cf465ebfd010d56419d90ccf546d6.nq.gz
    ├── 378b970b95aae54c582f11d348c1c18399cf1e40.nq.gz
    ├── 3817a8d4a5ab50eeb0adf33edc735479f5919445.nq.gz
    ├── 386a954ccf6870c7683ab658f19adc0924a6d00b.nq.gz
    ├── 3975cefe656c9a18e7a61ad3952c785495d771e9.nq.gz
    ├── 39ab21dfd60c780d29d21aa47cd5d5b4dc260d19.nq.gz
    ├── 39d02ca55c5bd00d905430c4fd833e6b69273363.nq.gz
    ├── 3a4c729f2848c1c211bf7693b36904486462cc6a.nq.gz
    ├── 3abf2ee0745923a5bbb160330afe2f4f8575b7fc.nq.gz
    ├── 3b25e68b5670e9dca3d8ceb30a3c4f4e58829426.nq.gz
    ├── 3bd88c544bbd06dde0514d74c1c26a133953e577.nq.gz
    ├── 3cb131528def4e51fcf49c431d24be672bc6186b.nq.gz
    ├── 3dd94b362fa8c3a362766879b708937fdad668bf.nq.gz
    ├── 3deaa26289281f80433950f5b263ff6e91066e54.nq.gz
    ├── 3eaa9266d86fa5caaaa208ae0a3df54aa5ac48ad.nq.gz
    ├── 3efaef680cdbbcb33ded77da6e0c4ef3ed10afed.nq.gz
    ├── 3f57ac7d86a1214e1698e13aeb24a5cc88974bf9.nq.gz
    ├── 3fd5d98bce0fcf15bfb18701e6c1130bdc2a23ab.nq.gz
    ├── 40e6df5557f396e75dcee729da90dc7a867ab7cc.nq.gz
    ├── 4100b0f11f6b1a3ac313a5f686be3489820647b3.nq.gz
    ├── 4190a41b4fe807dede28d28c438248e6718b86e6.nq.gz
    ├── 41a91949d203ecda785e01cd9374989d67516e73.nq.gz
    ├── 41d3b058a1e0a8db6e5dd464887da548cbb985b5.nq.gz
    ├── 4235ac479d1e5b58d876c39a0624f523958e8462.nq.gz
    ├── 427b36e3ac658328c7254a7c7371f2c8c44bdbe8.nq.gz
    ├── 42b9db3227f95e7085853b48574554bf95ccc954.nq.gz
    ├── 437a463399426746bdfab2931a9ef8b3acd33894.nq.gz
    ├── 4391d40f5e91b5346543f6e509eacc6e1403a606.nq.gz
    ├── 43b397e974fa10e66294305079408b0a517437c1.nq.gz
    ├── 43b666072080042de63c0c563dda5476824d45e7.nq.gz
    ├── 44291b2aaa1fac71aecc9a88a7ef4c6b420ed316.nq.gz
    ├── 448db2c8783efd3c8f86de94dd4cd23c0d0e79fd.nq.gz
    ├── 449e3e84cf4adf1eafb2d507f5e574a056f85b9d.nq.gz
    ├── 44d6fb620987cbea26c3e254d77af008c3256992.nq.gz
    ├── 450a63cc303b2eceb983656a6201e7702b8a56d0.nq.gz
    ├── 4566eeba40f6309a2d8cec0e7f449bc75536d01c.nq.gz
    ├── 4617181213df0e96719876767084f71fef4f06df.nq.gz
    ├── 462b689bbc79f215e4215c748f8c91b9a8b0cec1.nq.gz
    ├── 46a08152970ee81f064ce3e6cd1d773000f5d00e.nq.gz
    ├── 472ed1a65e90682ed2713eb13754d6a10a8910e5.nq.gz
    ├── 47e086f98dde5c348a9e74dfaf18540c96224b7f.nq.gz
    ├── 480c60756a022929f26c403e035fa43c02e3ca16.nq.gz
    ├── 48458c88605f5b442715bf242f227629934185d7.nq.gz
    ├── 4883a86607a2cdcb32fb5310f6da7dac189c77fd.nq.gz
    ├── 493cb70ca848dab51fec0739aed90a70fde87c9e.nq.gz
    ├── 49a841f952e8f5f4fa25fb6a7d71e0f387407362.nq.gz
    ├── 4a88677bc1439e60159e4647a7d454a283ee400f.nq.gz
    ├── 4b0890e4c067ad67a07ddf604077124d4285e693.nq.gz
    ├── 4bb623f3deec994fa8c1a2e8c5134d445fe82317.nq.gz
    ├── 4c41a32fef4dd479f77d421da6b7cd3853d58af0.nq.gz
    ├── 4c6d7f5c7bf7a8ee9971576236f3bb29cf8fdc0c.nq.gz
    ├── 4cf441b5ccd5bebb5c254ede8d65ba27660d35f1.nq.gz
    ├── 4de1d50529521a9f474a3cf0037c7e89cc5fdad2.nq.gz
    ├── 4de3c2adcd7f3e02f344f0ef4d4634fdab05f4f6.nq.gz
    ├── 4e22585ea3572a2055713a82a696b4cb704ca204.nq.gz
    ├── 4e549ffd7635694a663caf7e730711b455a67304.nq.gz
    ├── 4ec81de8e4566dcb54d6b177cdc27d27b2abd812.nq.gz
    ├── 4f52abb43034a261fba7fd1b48d8f7d7ce9eda04.nq.gz
    ├── 520dd44ed6eff4071dfcaa637449f0384fd3f0e6.nq.gz
    ├── 524c8133927c794bf5bbbec778b8a6225561fb9c.nq.gz
    ├── 5286ddc0ee3548d90247c104b7ac4467d54e0b1f.nq.gz
    ├── 528feaf6e0e0cee5c948434e59e6d091a25f4dba.nq.gz
    ├── 530e03d66464b8d4bd36bd53a38fb652406da198.nq.gz
    ├── 53338d55674e478fdb0e4d9079f4b34d849bd446.nq.gz
    ├── 5393698044b8bbdecaac6cd6f7b2ed35c28d963f.nq.gz
    ├── 53c4dfbc9e72da2debfe56ef01cbbe824ab5a919.nq.gz
    ├── 53e2d2758477e1c62dd5a860b89e54812a5f9f99.nq.gz
    ├── 541b0ea3e9cab55945d9bd67cf547c491821b2b7.nq.gz
    ├── 5472414b6daf51142893e275f190924acac969f9.nq.gz
    ├── 5487dc6d3c239cd683762284da32b8747142cff7.nq.gz
    ├── 563a58b1211e4e2867667a1382ace4c6d49684b2.nq.gz
    ├── 564df0fccba5f146d8a685126115e0a573b214bd.nq.gz
    ├── 5656f8d482f045e054fbc4eede99f0eb1748d56d.nq.gz
    ├── 5706504cdf99dcb1620671e535a70406ec5e3466.nq.gz
    ├── 5723724f1c7ac0f7967249128e4a3a941a12754b.nq.gz
    ├── 57b88ed1d0bdf0509266b8676f5a4fad01d0dd43.nq.gz
    ├── 57f6a863b0072b5baeadf0bb8e1bfd22662b2ab6.nq.gz
    ├── 582425a2071a3a4de877259c53c33fd0712c71e0.nq.gz
    ├── 583769861481ab649afa451f148f65ca09c7a93e.nq.gz
    ├── 58aa83af38620339411f940f1fee910e9de53a6d.nq.gz
    ├── 58e6975049aaa4503d1173c5043f3c45455eed4d.nq.gz
    ├── 590d90227664bffef7102b3153f0403946269162.nq.gz
    ├── 5981f34c66520395851eec6211978fa1de8c2e7a.nq.gz
    ├── 59c18f7461cac0e226ddc251c75114b80f5d7f95.nq.gz
    ├── 5a79f6131bda2ec97d8fd363101b70858dcb8a2d.nq.gz
    ├── 5a846d14c42020e2fa35b8aadb7e649b4ae786d2.nq.gz
    ├── 5ab5c3d4e2ebb8d5f2ab2fa3671b5851465bb100.nq.gz
    ├── 5b4c2d151a44485ed95d21725c496fb494375105.nq.gz
    ├── 5bba1032489da0a24129996f6627b8bde5498fee.nq.gz
    ├── 5c4a309bcfdac16c4bcac4ec304d67846de27440.nq.gz
    └── 5c563aad08ad4b2a40bd9fb2fe66661bc5069cc8.nq.gz

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

[huggingface/dataset-viewer](https://github.com/huggingface/dataset-viewer)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
