# Repolex Knowledge Graph of tiangolo/agentskills

RDF knowledge graph data for [tiangolo/agentskills](https://github.com/tiangolo/agentskills), parsed by [repolex](https://repolex.ai).

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
rlex download tiangolo/agentskills
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 752b29a0a1a128b7baa6aad23203f6433cc0b24b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 752b29a0a1a128b7baa6aad23203f6433cc0b24b
│           └── chunk-001.nq.gz
├── blob
│   ├── 017c658e43efa15e787d18b7db5fe0240b2cfbff.nq.gz
│   ├── 06e2a1f0f631f56a64b9a3834448da6fd2cd133c.nq.gz
│   ├── 07e49df0bd4e20590f0e1911255ab01a7a9970a1.nq.gz
│   ├── 08bdef69c64270bb72446d01180dbd3285d480cc.nq.gz
│   ├── 0a01db8574948e637d8bde159d5daab7c8f12cb2.nq.gz
│   ├── 0da6f50261a7afaf32e94f93883cceab225a5c63.nq.gz
│   ├── 0dc0c2cb74a86ecc61d4c6364189287b98390d04.nq.gz
│   ├── 0f92952d8324dcef2521a226099d8f58cc3d39b6.nq.gz
│   ├── 13b4d0fa9c2c81b69762deb71053292f5bf8f5ed.nq.gz
│   ├── 15b6f7d27268c17c4dd4210c47fde758156b5e6d.nq.gz
│   ├── 1a5b1dd474091369be6febf4846a2abd2072aaf6.nq.gz
│   ├── 1ca6834ab61491cff981e3d01e66e985ab8ee64b.nq.gz
│   ├── 1ced12cccb63443b015bc10561106b6cf8ca16c8.nq.gz
│   ├── 210d73c5e35dac01c18e32efb31512d72db376c9.nq.gz
│   ├── 22cf6f8ae5f905d780cb097c0938711cc37016a9.nq.gz
│   ├── 26c02750f3b964b4c6a06de41b7ed40a63847c01.nq.gz
│   ├── 26f0bd339ff79a1f51a9dbeb10c424fd9c09cb73.nq.gz
│   ├── 3173c5e7b31e129653c7c82fbb9f4be8a5ffde4f.nq.gz
│   ├── 323bf30d9462e725aa7455111962acad2d219126.nq.gz
│   ├── 33f25b0f348deb3bb2ea97f6ec63eb6f72dd14a3.nq.gz
│   ├── 35d4cf1dee84ab826fa7776d2a516deba679c95a.nq.gz
│   ├── 382cbe6eec050ae9e26fc126cb65693d463b177e.nq.gz
│   ├── 385abda838b3de6620ef6f36a7b319be48a4ae88.nq.gz
│   ├── 3879c9f274b79152c3a4ad501ed1f0da010ea560.nq.gz
│   ├── 3a7d714bf60745a04e025764e724e9043791b6e9.nq.gz
│   ├── 3b5e89da7af4b5db2eb8aa74d35a5f7e2e3893c7.nq.gz
│   ├── 3bf6bab95d718d80535afaecf0007c0a2768e9ad.nq.gz
│   ├── 412c195605955525c4ec83dd9f67e4d9d1557321.nq.gz
│   ├── 43776daaf113e072d0e3cd7bed8d898ba4e12939.nq.gz
│   ├── 458b7de9771b3aad2fb3707c5fed2ab31c8cb2f1.nq.gz
│   ├── 4611272ec41f38dd5918e09f83944e5f12c3639d.nq.gz
│   ├── 484705d483fd9ac4e4a3ce84f4d30f7aa3547bf1.nq.gz
│   ├── 4bfd6f455ebe71a31a7feeff16ec3007b4adba5b.nq.gz
│   ├── 4ea99c213c5c0c005ae4e80df8e52169d06896ec.nq.gz
│   ├── 552298435b7ccddf11a1ca1b67532a7e3e8777c5.nq.gz
│   ├── 5b67a675dc19da3cd6acd49f69843f099c0911dd.nq.gz
│   ├── 5e648776996e267cb25650210b13a4c1b8e09d82.nq.gz
│   ├── 690c14e27b61405e3b1346dc22c8678cd3e79b35.nq.gz
│   ├── 7210de15ded28aba531c4e814542db64b4078855.nq.gz
│   ├── 747fa032b08b110b164d54d82d247bba2a38c9fd.nq.gz
│   ├── 77fa89ed2ccce99b10068fccd2ca26a2db24b1b1.nq.gz
│   ├── 7a134f46920401f2e15a3da6ac9767fdd6e18a72.nq.gz
│   ├── 7a25d59c6ef5dfe63703026e296e58c666381cba.nq.gz
│   ├── 7a4a3ea2424c09fbe48d455aed1eaa94d9124835.nq.gz
│   ├── 7ac6e6224f5dd7d1a11fc9be5f512fade5037496.nq.gz
│   ├── 7df2b359bd4e608a1d59b195d68a9f303350c0b8.nq.gz
│   ├── 7e23de463eecad5246b3b97cdedf38cf58f66f1c.nq.gz
│   ├── 7e32aa401085c5a25185befb0f93126b9db75ee2.nq.gz
│   ├── 7ebd2379b78dc68017ddd0329e93853998392c11.nq.gz
│   ├── 821d4f35016f3ce25ac188f01cfe8757594efc20.nq.gz
│   ├── 8edf738be8f719b21ad61b69192d8c1b80fe8209.nq.gz
│   ├── 8f48234ef25cdc1d6bd251295665dffe92ace26c.nq.gz
│   ├── 8fe6577a9435c17a6b6dceaa559a29285eecff3e.nq.gz
│   ├── 92b6d8e4dc8f1159cee5281885f70b44a56a739d.nq.gz
│   ├── 987d3931de9b9b7095fc827b6939e6c1b8a8227a.nq.gz
│   ├── 9af9fc3068a6420d8d0715616b11d2628e10a86a.nq.gz
│   ├── 9ba700189a98da8fb4433af067aa1ea5a6dbdc33.nq.gz
│   ├── 9fb120eb4e854b8313290aab5e0248cc82995ad0.nq.gz
│   ├── a20f4476df158a57a68409015ea607c738856f57.nq.gz
│   ├── a3ced1bdbd7f256082f30c4c63f66d28ff5d4ef3.nq.gz
│   ├── a6215d606ff75da164a90d22cd21410b48915210.nq.gz
│   ├── ab1ca2a21ba514748f993c6f72dffdf76ba615bc.nq.gz
│   ├── b10659c84a8352917509919d9b517ecf99ad1dd5.nq.gz
│   ├── b4612aaab9276d86905cb383bb299217d6b15db5.nq.gz
│   ├── b5c1646b29fba7a733482c2949aa1fb53036cc4d.nq.gz
│   ├── b86ccc745651c522be95ba638cdeda33ebbe658a.nq.gz
│   ├── b8b6cef6555d57176bda4bc96d74ff7cba11c2a5.nq.gz
│   ├── b9b161e9d076128fd14668bdf402468adb85ac5e.nq.gz
│   ├── bc76b93d6e19a383520ba95ef7e08deb4ef4bf5a.nq.gz
│   ├── bde735cd9e2f729b6418fff75078f8fdc95e3219.nq.gz
│   ├── c1b9c4a1c7c14f55cffcdccfa5028eefb5f9ffd3.nq.gz
│   ├── c31296c141358bcb304937b3e5333e400903ec29.nq.gz
│   ├── c348e4bfd5f4695df9cb39d7a8ee554525e29f9b.nq.gz
│   ├── c52b73c00475c302b5cdedd04547a4febf4c679d.nq.gz
│   ├── c6461960640e91c8ad58d05b2a335186abb43a2a.nq.gz
│   ├── cde9068491464542e8b527b2c7ff3ebb58e493e2.nq.gz
│   ├── d0a7ff2628e92a5d6b5d2b943996b6edd82eb906.nq.gz
│   ├── d89abdb5861b3b1ec3ead567272d7d5463fa3a4f.nq.gz
│   ├── e33067fe47fd1bc61c34344e24be742f12d992da.nq.gz
│   ├── e3e952ae586d6fe4cbb848f7125c0218bf17afc9.nq.gz
│   ├── e9b49b50a02f27a08df2d9561c7d1973974ab17f.nq.gz
│   ├── ea5047006c3ff3b54e2775e4b911458721097ca8.nq.gz
│   ├── ed14b63805790cd1931f34f7dcef8ccbc10d762d.nq.gz
│   ├── eda539d2ab4908e84692894111808eed2cb271d1.nq.gz
│   ├── efea6391dad1adeb22bac9588e8f78eed9f00d21.nq.gz
│   ├── f095132bff6eb86d796893220cfbb1d0f2461596.nq.gz
│   ├── f0ce9cfbae892529005351cc0f5a3b8fdfdfadac.nq.gz
│   ├── f5b90cd00ca6b8ccaa562c9ca7777a5b8a2f3afd.nq.gz
│   ├── f5c6e139d60f63acd620dc9f1aeb6776c11057e9.nq.gz
│   ├── f75f0fe2b6550dca006410764701eaa92e423854.nq.gz
│   ├── fa6c97ecc008bd81108b3aca5f6ec2534b7a01d5.nq.gz
│   ├── fce673752abbb60a0c2edbb41038f9d820b84b12.nq.gz
│   └── fdf9a0664376c785d4198654d511bdec3c3166e4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 752b29a0a1a128b7baa6aad23203f6433cc0b24b.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 99 files
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

[tiangolo/agentskills](https://github.com/tiangolo/agentskills)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
