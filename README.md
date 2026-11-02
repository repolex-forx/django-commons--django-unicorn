# Repolex Knowledge Graph of django-commons/django-unicorn

RDF knowledge graph data for [django-commons/django-unicorn](https://github.com/django-commons/django-unicorn), parsed by [repolex](https://repolex.ai).

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
rlex download django-commons/django-unicorn
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 63043f40424455e189bd4d094beeeb1f3f2008bd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 63043f40424455e189bd4d094beeeb1f3f2008bd
│           └── chunk-001.nq.gz
└── blob
    ├── 010d7148115e7104b4902840b0d52e11e0848fae.nq.gz
    ├── 02922fde39f4866e255bbda37ce194710547c639.nq.gz
    ├── 02c2f996b89b87bbb079554a265626005f999a2b.nq.gz
    ├── 0385ec9d4c6cb2cef31baa631f764d4d69cd23ea.nq.gz
    ├── 03e932e3ccafaeeead80f8bd523b334cb71865f6.nq.gz
    ├── 0439ddd963e85d3b4ae8eca9bc52b8225d0e0782.nq.gz
    ├── 05461434cdbd1e1c9c5b98095c23695f280cf71f.nq.gz
    ├── 088b38d88d7aa02365b49d74382767c87c04455d.nq.gz
    ├── 08d98a402ddcb110c437510ec7ac3b59b1e52b8e.nq.gz
    ├── 09cf3b147b4f504cc9a4ba6a212df8b8fb6708d4.nq.gz
    ├── 0aaf199824c3442b99eac1e53a30e61d7faadc6c.nq.gz
    ├── 0c332bedb5b5503797ac51e289196166a601b46d.nq.gz
    ├── 0cc8dc0aa54853e655db414d085fefd9cfbec47f.nq.gz
    ├── 0cf920e66cb4733f42998c4c84b2eaff4bdfef0d.nq.gz
    ├── 0e4d8f3f1033cf40b4f0522a2b5f1b3ab487c6a1.nq.gz
    ├── 0e8e2a98dd884240bb8fbc8bc58d924967b0d4e7.nq.gz
    ├── 12a3cc9a4b7f13a3fac757d5c1758f0b5f4a9349.nq.gz
    ├── 12e83cb826952bac03f11a11dbb8334e2d1cec22.nq.gz
    ├── 1321c7e65b6ff5d592bc31391e90322470d14172.nq.gz
    ├── 146710111c2adf5c0848c7c2126efaf2c4e02149.nq.gz
    ├── 15c3edf72aee587ec586b0ad5d1fe62bcf288e0c.nq.gz
    ├── 17f279d40154963d1a046292f08466ee124e27eb.nq.gz
    ├── 1a0f418e0e2e6336c6e2d254c529c2208d198b1e.nq.gz
    ├── 1a24893ea0fbeed5b53c36c79154eb416770bd76.nq.gz
    ├── 1aa7c45bd48a4915ed120a44716d12777eab4c80.nq.gz
    ├── 1bba7f696aa5d6dbf27e344dbec5b60d905671a3.nq.gz
    ├── 1d7c603ad14da5deb44c1ba2e0b8c0b517683796.nq.gz
    ├── 1e371dae4839803bb65277c8f698f732d237380d.nq.gz
    ├── 1e807322626d79f6a0906af36fc11b1f940416d8.nq.gz
    ├── 204551b15efb68ace56cd3d87f8c0709576706bb.nq.gz
    ├── 20a34bb076322a66237d201f27334c0ede7d0d3f.nq.gz
    ├── 21a4ffdbaf07eda242beba5c096b867441e17fbe.nq.gz
    ├── 21f28669bd85bfdfd860862fecdb568f959441ed.nq.gz
    ├── 225e4afb0d2116dbfca0da17b54838f9edfe92d6.nq.gz
    ├── 231e2dc2065bdd5417c2c5cf4069dde14c7f16ef.nq.gz
    ├── 24e9d792f85f4f9f8dee67da8c4f762f01c20c66.nq.gz
    ├── 2543d4ea92400190b1b52d66c42db0e09c5cacb3.nq.gz
    ├── 27594f2cf1b3f7b61ca8dd1731fa77ce94fc002e.nq.gz
    ├── 2b870c42ce580d744ccd8b8ffc42bf55838f9aca.nq.gz
    ├── 2c1d675ce890bddeac817f4441693d52bb0820b1.nq.gz
    ├── 2d19fc766d98a08d9d1437896bfb008a7b15f340.nq.gz
    ├── 2e7f1bbfe861f1fa47728b6aead410458688cac5.nq.gz
    ├── 304d00153afc11b012e7c0418a8fdff507ce5d58.nq.gz
    ├── 31176215a33c7888af8a282177eb528223319d93.nq.gz
    ├── 32041403df4d0e244feac08d74cb1ef5fd438986.nq.gz
    ├── 321cfaa3259e38a2225d117d1a4320b99beb9f8f.nq.gz
    ├── 33efddab9d090df393310017df20888fe9953c7d.nq.gz
    ├── 34cdb9ec5b8cf189f8bcb882032e62733586fa3d.nq.gz
    ├── 35cee048a2140e6c2c54358c046db99c39817ec8.nq.gz
    ├── 35d68167ab9b1c6e62bbcf27aaac85795ffb210d.nq.gz
    ├── 35fad4d474162e21980be095773a2cf52ffd7dfc.nq.gz
    ├── 3740dc93304e61347963ccdc0ef17409269289db.nq.gz
    ├── 3846568fef2ea52cc0de2c2c7285539de7e91366.nq.gz
    ├── 39ad6c37258f70949cef6647dd5d434b54ea18ad.nq.gz
    ├── 39b1ff1369b2fb635a25c2ce304e669eea5c7654.nq.gz
    ├── 3a7afe8460fefce57d705659302eaa6e2f24e442.nq.gz
    ├── 3a81bf97ce2de31338bf0505f310d3130972e8fc.nq.gz
    ├── 3ae6b8a73f6696a06e54b24a8b5e3f95569ff642.nq.gz
    ├── 3d722a8cfb41e6c7a341589ea26a381e57100e59.nq.gz
    ├── 3fafbb453ff6f76539c8f49e3b82d4ceaf72f264.nq.gz
    ├── 402045876b921e49c2b3bcec8a6e0c194b9293c4.nq.gz
    ├── 407965b65478f4b24812366f2f0d032614320a9e.nq.gz
    ├── 409204de4a5b1d27179d9aa80f42093eeaaaad2b.nq.gz
    ├── 4102794c15bee79ef6ec1e77ddb96e86180fcf91.nq.gz
    ├── 414cc027f61322234133fd6f7341d197b4d1e9a8.nq.gz
    ├── 41c0ee61c33585ad61b9f52ea3297853f926b7b6.nq.gz
    ├── 4279b22a360c57489a8d80332e2f11217975b745.nq.gz
    ├── 42c340e42ac56c17061fb455da15a8bf755b43c5.nq.gz
    ├── 42c8a279835460e013ebb7e1c4d459f650f982f5.nq.gz
    ├── 435c7940d9740cbaa78534a7575a87effb055809.nq.gz
    ├── 43767656345776637f9a1006811a0b84fcd1a6e7.nq.gz
    ├── 43800181a2619bce49a7e824b4eb7ef3699ddb5e.nq.gz
    ├── 447085f88a2c21e0f3169c1a118504203506a82c.nq.gz
    ├── 44eac56af87fad85ddffd189b3e213dd003e3bd1.nq.gz
    ├── 468b92bd6b7139671f69114e551d74381579f514.nq.gz
    ├── 469573e2f9afc15a0a1da58135affca6e7c3633f.nq.gz
    ├── 46f9d48ff5a1fbba2bbcc0440718509928c91c64.nq.gz
    ├── 49400a8f1b7182436373eadc3cfc679592854a2e.nq.gz
    ├── 4a225e5e6aac4f15979c43e50b7392b8d8dbc18d.nq.gz
    ├── 4d0d3ec7848e47a2bc84b5e562d72b0f9c73999c.nq.gz
    ├── 4f305fb34dc36d51b92d0d68f64e51eccc350d84.nq.gz
    ├── 4ffcbd07c11af66971d3ba48b878279e30edaad1.nq.gz
    ├── 514d13b824e551526c1f2eba26cf2607a60ce7b2.nq.gz
    ├── 53deaae50fc1bcc651345f9478e638d631e9916d.nq.gz
    ├── 54f2a86874fcb1f628f9731c9ded497d9ef92111.nq.gz
    ├── 55cd27af36b050e8631070ec194584462f61258c.nq.gz
    ├── 5655a7d934464efb439d818bab5cdd3b2c6a3e0e.nq.gz
    ├── 56d62f6c92069d647ac8d64a8e792602ad248e5f.nq.gz
    ├── 579885d8cf683a70e4839903242dd206f3010bba.nq.gz
    ├── 58021315648aa8f0e1c493b042ef351aa2d70899.nq.gz
    ├── 58b49ab4d3b377a5bbd37898f397c8aa786f95ae.nq.gz
    ├── 593735b772bc97a7b97adcc0e51a4a1bd07d10d4.nq.gz
    ├── 5947fd39c33a9366c139df1c374d01047d62f471.nq.gz
    ├── 5ae1afb9f2e6bf4e64342777ce453028de16ad8d.nq.gz
    ├── 5b056387ee30976d1b06e2f3122377e5128793af.nq.gz
    ├── 5b10ba7bb784ee04277f784bd5e4da2636e04633.nq.gz
    ├── 5f02d4f5cf2abf5f64e3a4635babb629c48b5969.nq.gz
    ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
    ├── 64c70ad8290b062ab6cff2afa31b9237d8a71c44.nq.gz
    ├── 64d9c0c632c4e88901a34d3ae878c2adac0e8c07.nq.gz
    ├── 663e21d3e9d8d1a96b85f8c66231f0d0f263241d.nq.gz
    ├── 687fa72f4d3037c9285022237b19b36b73028473.nq.gz
    ├── 6911cae27f2193ee14427a48a0fe3825a97240ea.nq.gz
    ├── 69472ac0b2cd2e17116a5db5d26a4a6524f22158.nq.gz
    ├── 6b9dac265648389154f221f86f995dd5d51ba591.nq.gz
    ├── 6bf2084d8233284f68489b7c7394dbb7939f6de1.nq.gz
    ├── 6bfb3f8aba4d3254143d50f7edfc696b2d0b02c6.nq.gz
    ├── 6c8988582025f27294fc7aa2fcd7e53ed79675c3.nq.gz
    ├── 6d25af81ea7079dcc12922dc6ee1d77301e37d0d.nq.gz
    ├── 6d5de55064b213d850498703763866b5ca857e83.nq.gz
    ├── 6d65a7e32a10b45aaefd6e9f6fbead0aba82d54b.nq.gz
    ├── 6fc4431a76865424c5e530e103fdecaef990646a.nq.gz
    ├── 71147bbed9362d1bbc1c7a5cb1571ae216ac3ac7.nq.gz
    ├── 711743ee3c409622f8d5d11353d717ff65d78d41.nq.gz
    ├── 727f236921a1c749e51a4377fffa2142d5f88549.nq.gz
    ├── 7379f0e46d18e4d2da1621a071a04f8322dac483.nq.gz
    ├── 75562f6cda42a905ae2cc4430628d514c4f31028.nq.gz
    ├── 76530908b98b1b69b1898b6a78a9fb46ca5e39c6.nq.gz
    ├── 788543917d55ce445798c818a2c0bc26138fdc24.nq.gz
    ├── 7a37f0c94766acaf87aa3dc011340895d0d31016.nq.gz
    ├── 7a4de606876e3e2b540506c0b06f8681c653362d.nq.gz
    ├── 7a52991e5cb07ecdc657ece387b75731c2c3e766.nq.gz
    ├── 7a8402c76aa3a641a0d17258abd4d4d3c84196c9.nq.gz
    ├── 7beb628ded5b846da0a2a0cc7d3733e97528d6d3.nq.gz
    ├── 7c97f6cac2b46751937f025a55fbe9493451eed9.nq.gz
    ├── 7e14ece36c22b4a8c6881a12a9a6eb13a285e6d1.nq.gz
    ├── 7f4c2ea132cd4cf609811dc321eae3edfcd2bb63.nq.gz
    ├── 7ffe07d483526b56974766f0799d0071cf55c479.nq.gz
    ├── 804d55c2c421b3822e4c2b781904cb8cfe720390.nq.gz
    ├── 815b2b377879b0fff30cc0ec74f0f5533f43e454.nq.gz
    ├── 819a291ffd4027dfd04c6f1e4b7f711a9691d8a6.nq.gz
    ├── 8216244296ee75fd92db0ad4e125bb5bdcf8cddd.nq.gz
    ├── 824280a7278720938328d650e3b5a51f52fcc886.nq.gz
    ├── 84bf96f44fbd1c5c1d7165aa1f76b1a295cf9cdb.nq.gz
    ├── 85f3561f9092f637393769c88eb7c13e8d528c45.nq.gz
    ├── 865595e5c50b1866ba3edc0feab112c7266381eb.nq.gz
    ├── 8835724b1957cf024b37fe14e21abc985c7632fc.nq.gz
    ├── 8a287d190f340a718cba5b5b8ba2dd5bd673a5c6.nq.gz
    ├── 8af4c4e007d6521b54ba02b17fc8166053f3db8a.nq.gz
    ├── 8af7a5557b66b96da9fe12050da40e0d84131eb1.nq.gz
    ├── 8b77d84513edf6ca0f78e54ba008a0a68d0c7d45.nq.gz
    ├── 8c0317a6decdabd9b75dd7c0eee1fc7f88ce7db2.nq.gz
    ├── 8cac3f2cb6367cd775570c5249dcef2cbeeaeaab.nq.gz
    ├── 8dab51527f39d23b4502d3ad1ab9039faca396e9.nq.gz
    ├── 8ea1b17edd0137f15217ca781dcbfd3327ad154d.nq.gz
    ├── 8eca1cfd3548a7b6e7c9441e2c1ad4f91a56660b.nq.gz
    ├── 8ee17b5cec74cbea15b99ee3ade06507fad5f470.nq.gz
    ├── 8fcf6558e936d125e2b74783b964ecfa62eb553a.nq.gz
    ├── 91541d3bd5eeb380b7eed35313815102b5763586.nq.gz
    ├── 925c7b74c987761ee4dbc76877fffcacc46b819c.nq.gz
    ├── 934e9e0a9965ac356bc0fd7d7e7ac1015fc3e064.nq.gz
    ├── 94618dbea80bd3ad1dca86e3e4c6f0c8fe951f49.nq.gz
    ├── 94f02db61c6e1cf196ea33ed6fc925f4bc5e06a8.nq.gz
    ├── 979e2f46bae3cc105fb68535c36937fb4b7d97b6.nq.gz
    ├── 9814253e918035cc5babc4e2ed041c7a31dbbc28.nq.gz
    ├── 9a0bea6bedaa78a5a5a97ac04907e5b2fca243cf.nq.gz
    ├── 9adf61af11afc75aeecd3ace02895177054e20d3.nq.gz
    ├── 9b24b7f902c9c4bdfdaede6a1f17dda91780f1ba.nq.gz
    ├── 9ba6a7cf49f8f522cb31e6c67186cc46bf21279c.nq.gz
    ├── 9c14392508e161e7b5b2e740fab166c9c9d3828c.nq.gz
    ├── 9c639b638020f68fd2280959a0017e8bfadb61d1.nq.gz
    ├── 9ce87df08342fbef050ee03ae0af8dbe6fe683ef.nq.gz
    ├── 9dc9322ef99383d32f7811ee96aa7341c805508a.nq.gz
    ├── 9f535364b6e23f242203c329af39be37247d0c37.nq.gz
    ├── a0446d61708ef474649f679e35144d564e53ad29.nq.gz
    ├── a0d1e5d63c4c650662a249b66858128cee3ec64f.nq.gz
    ├── a2b79b96b898f49fb727ced2aeb48614ac1bebd5.nq.gz
    ├── a35c89b7fd7b113fff965efbf6307f87c05d5442.nq.gz
    ├── a4bc08c2542f96f9175cd45419d3d393cf3b43cf.nq.gz
    ├── a7203db235a337b318622af3f17c24cd546dec21.nq.gz
    ├── a8fdcca6e019b7279238e3967c8b7b9b4c4bb713.nq.gz
    ├── a97766603e66cfebc240fb12fcfbf8391aca8af5.nq.gz
    ├── aa908baad8c5fc9cc0b281e60463e0f85d6bbecc.nq.gz
    ├── aafbaa786515763e391d010c80b9ed9c3f86ff9f.nq.gz
    ├── ac9221a4701f029f370a25c29ba1b205cf46c477.nq.gz
    ├── ade34aa318effe53de7e27ef267549fc9d10f438.nq.gz
    ├── afc3b7a2a59c195645650d9a828b6b3b11c69e49.nq.gz
    ├── b0082205f65f11b635b3652a8c8909c5127040fe.nq.gz
    ├── b027dc201f46f59d8a155d8c7a0df663edb05aa7.nq.gz
    ├── b07f68c32fb6252eb50361b127293c635336dd6d.nq.gz
    ├── b1252f914038756672d60e542fd0983b26c72666.nq.gz
    ├── b154f1f8e0d0228d62eb51e45d3686a425aa25c9.nq.gz
    ├── b2d398417af8226cb64ce84f550e429da93c2802.nq.gz
    ├── b365427f6c52510a4b21f6ac3b4a665efbed9e5d.nq.gz
    ├── b36c1c955675d39536dc36c6819bbfe96d262e1e.nq.gz
    ├── b3d26f39129124954f900742eaa707c9b79dbd90.nq.gz
    ├── b4165f461116a13c5e688d340e430318edf6ec3d.nq.gz
    ├── b6788257686ecb1d8dc80dfd11698e654e829ac9.nq.gz
    ├── ba11dfe646088aa328c169ed10de9e10fd430572.nq.gz
    ├── ba5149549bcae8f4127173349536c87d08f7efa5.nq.gz
    ├── bb587f68c489150f3c1d169ed594ce3c9f22c17d.nq.gz
    ├── bb6c42d1211f8eb482a9ba070253921dbab47f29.nq.gz
    ├── bc1a64577e18709854547dba85fdee91831ae69a.nq.gz
    ├── bd08251ac4a0ef278807e5026adcdc23b2884e8b.nq.gz
    ├── bd96b8888879ad1b69d4ac7e23c922ed6ad7bd68.nq.gz
    ├── bda0d3f90916a7a01dc24b04ca845ba1230230d2.nq.gz
    ├── bdcd5489db5665bda6358d65ed8ef9272303e8e5.nq.gz
    └── bf09fc75f933f2a0693ffc7a7e99ad3964b5df0c.nq.gz

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

[django-commons/django-unicorn](https://github.com/django-commons/django-unicorn)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
