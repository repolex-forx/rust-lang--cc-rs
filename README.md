# Repolex Knowledge Graph of rust-lang/cc-rs

RDF knowledge graph data for [rust-lang/cc-rs](https://github.com/rust-lang/cc-rs), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download rust-lang/cc-rs
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0767349e1d1253e6849b4c2af2059db661f54343
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 0767349e1d1253e6849b4c2af2059db661f54343.nq.gz
│   └── repolex
│       └── 0767349e1d1253e6849b4c2af2059db661f54343
│           └── chunk-001.nq.gz
├── blob
│   ├── 0546bc9bfb4ff1e18feacf3cfc59e9cb1712dc34.nq.gz
│   ├── 06bdb7375d89297ad3aabc83c14d7f363ea974be.nq.gz
│   ├── 07d0f647633e8da546da7f6b9f2ef68a51e34d85.nq.gz
│   ├── 0834c694ba5dfb0c7bdc49ae0a59a69d2809ffbc.nq.gz
│   ├── 0896aa09f57c679d9cfcd3fd2498cd4495458e86.nq.gz
│   ├── 09dfe125afbfc2fbea67ca2a7f80b7180aa40712.nq.gz
│   ├── 0edb14bee59cea3347055aed9e97d1a0e59779f6.nq.gz
│   ├── 12684671e3a99edf3c5f959a29e92af99e9ac9ff.nq.gz
│   ├── 12b39bad3066d0658b4cc81159c9c62ca376e21e.nq.gz
│   ├── 14692a16b385bd3f20a9cd9ac2d5a3d5ca9f9194.nq.gz
│   ├── 15baff946dd806b701883c9ffdcdfa268a97e474.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 1c031015d2316d5eecf977434ab97824a65dec4b.nq.gz
│   ├── 1d9062d71170cd79e91e1684a5c777ea7d7cca72.nq.gz
│   ├── 1ea1830d5123c7ebc6e18996c14c6461a2dd93c0.nq.gz
│   ├── 22815ab8f020878e8ff95f7ce9275871a5a95d0e.nq.gz
│   ├── 23089c77e9042ad5431a12d373ee4283da28f157.nq.gz
│   ├── 26f17a7409c9fe4d910022e1dcc3cfc302488226.nq.gz
│   ├── 27dcec91409cefa0795291d85e2cee48d2909c66.nq.gz
│   ├── 2b492a2d5187ce52619b615f92f571026592b1f5.nq.gz
│   ├── 2c51abecbd7d05dca862e0c87f7edd4f5d7089b3.nq.gz
│   ├── 2cf3fc4b249eb661124a4b424d84edce9beaa342.nq.gz
│   ├── 2d4b959e8479a5c07a45182d785227b3b6d1b8ae.nq.gz
│   ├── 2d6f2e8a7215ac8ae1c701f18800071200351dc8.nq.gz
│   ├── 310c91b0a07b94c5a6a8d8089fbee0f1d3e46414.nq.gz
│   ├── 39e0ed6602151f235148e6c08413aa7eda5b9038.nq.gz
│   ├── 39e6cc64d88cb95cb7dd58de57b101f7576dccd3.nq.gz
│   ├── 3c6afdce4e0e5b396ddebb87a8f554ff7757fbf3.nq.gz
│   ├── 3ec1c8eef003855e2ab63e241217257ccdea027b.nq.gz
│   ├── 3ed9e866f3967edb95fa1ca1bda5cc2f9ad5a5d8.nq.gz
│   ├── 47b306954585fe1050c667b7461df68887a947c8.nq.gz
│   ├── 4e61b2e985dfce80fc3f2212b56206e9486b5107.nq.gz
│   ├── 52790a5852bf66c6311964600c19a6bc329f4333.nq.gz
│   ├── 535ae3419244f9df141af1b3392691e1cbde104a.nq.gz
│   ├── 541e62c4f02f69a39560be0ddb3c7c964b1ac43b.nq.gz
│   ├── 55b4cac3858b4b92fceab8a23c70ae0a35d3d4a0.nq.gz
│   ├── 571a3f77440fb611da560478a068c18ccccbe551.nq.gz
│   ├── 5c0f7c776827241e80f41115784f581bd6d0a82a.nq.gz
│   ├── 5f090b32e32b6b7bfba0248b7348f2423c75330b.nq.gz
│   ├── 601cee6c4878cc9d83010982ef7cd08f3f0defa5.nq.gz
│   ├── 605be33413a645d4a15ee8dac5bf315806dbb607.nq.gz
│   ├── 6261353b4a4f16e5161bd222279a1a156cd247bf.nq.gz
│   ├── 6bf9676bfd808b208803d98f38528c7ccd0a81f7.nq.gz
│   ├── 704d78630fd4d6bbac2301396acb3e34806827e0.nq.gz
│   ├── 76219eb72e8524f15c21ec93b9b2592da49b5460.nq.gz
│   ├── 786d407ec4f0ae8095fc4c662f926ee0f0845f40.nq.gz
│   ├── 7a8a94933695426d4c0c97332c47a9d58c50632e.nq.gz
│   ├── 7b6d2423a05af5ca84d5ce4663c7034c05357f0f.nq.gz
│   ├── 7d843e5246ff9e493b48e5cf2da318bedb142f9e.nq.gz
│   ├── 7ec2f2f696cd01e213f35352128e07588c6baa66.nq.gz
│   ├── 84bcd75d10730b1228fbf461f2227844148b93fa.nq.gz
│   ├── 8533fec9ab2accdbeebda927daa7507149c6ff33.nq.gz
│   ├── 89a08efb3f6400d4d665d8a490dca55718b4c468.nq.gz
│   ├── 9393a98ff1a04e400c32539c40f5726afb03201d.nq.gz
│   ├── 965b606f331b51d566b46025f9ff311a7aad0c12.nq.gz
│   ├── 971ade678614a0bc09efd04f9ee326f4fe632737.nq.gz
│   ├── 99c04897bedd5e1e07d5f2618f9c525d4c1f6d5d.nq.gz
│   ├── 9be4291183615e35056cfcb480bbda4749331a67.nq.gz
│   ├── 9bfe61dc56305cdc9f2ba659d2ce6b7be44f721f.nq.gz
│   ├── 9ebd1ad56205960e302c2a076bacc21826da1874.nq.gz
│   ├── a657e1ea4b158dc0cb3ce639acfe9827620b85e7.nq.gz
│   ├── a74af8cce42484e8268608f23ce9ef7f1f2538d0.nq.gz
│   ├── a7f7c64e9f80a1573cb41ce11d25f9a1821acc32.nq.gz
│   ├── a928d0bed20fb24ab8767d25f58b640b349fc494.nq.gz
│   ├── afc34cceaa924ad336cffe1ec571b56add1a9303.nq.gz
│   ├── b003c0c53f036bc69d638cc7a9e65fe64d8ac213.nq.gz
│   ├── b42ebf7920d6e758ffbdd9a8c3d087eb0edfbe02.nq.gz
│   ├── b539dbf9ff745e62b5a4f09380648a9f8325d6b4.nq.gz
│   ├── b7f8dad5f5db4edfe74749c678b40bb0912d9e9b.nq.gz
│   ├── bc42479dd4be37ff0ddc4711a93d1cb773a46e19.nq.gz
│   ├── c524c7da4e9f086c570942fbc651facb8de8b944.nq.gz
│   ├── c5c60c8ffedb9fd1125be698b7ef2105eb47d36a.nq.gz
│   ├── c66935249e91c21067eadbb7a0944437259b5ed8.nq.gz
│   ├── c7d6fff620a7a17a1f129873f1db6ceb3f85df8d.nq.gz
│   ├── c80f50617553b6deb11f9c4913e10c3dac89c8f8.nq.gz
│   ├── c928b8d97cdc8a12508c085983c86301cd4432fa.nq.gz
│   ├── cc7747eb6068b7a0b11dbfe970bfafef4443e023.nq.gz
│   ├── ceb74c847de1221e27165c0532b5ce659ea47e4c.nq.gz
│   ├── cff09959677071e31f0b0764c4baf461d23e5b8c.nq.gz
│   ├── d08affe0041700c97310e0053ebb2ac37bc5d81b.nq.gz
│   ├── d50828306ac53aa768d2cd0242d31a6e4eade029.nq.gz
│   ├── dbbc4945a4b1c13ea42824ebe3e03492de8a6193.nq.gz
│   ├── e0e17b04975da1b89cea12f69020b347fdcdd42b.nq.gz
│   ├── e211b18880ed09a49eba1b7946709c0674f69fb8.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea4420a6b4cbcb8c536702ff2fc3fdeea0ee05be.nq.gz
│   ├── ed432df5893792027537aeee9f75c2cd51dbed6a.nq.gz
│   ├── f1d11190bf9738b78b6389feabf6ffff970b87f0.nq.gz
│   ├── f3830212f09ca342ae2ff538ef84116c34388644.nq.gz
│   ├── f49a24b28c45047ef3f66022eba99c2f4a610108.nq.gz
│   ├── f94f81adb08e9c1bcd57c7214d52518c4b9db5ec.nq.gz
│   ├── f9bf28f4eb8601dc82cd16f8eda74960f42566be.nq.gz
│   └── fe2c0309638bcd87e21a96494331715bcbfc2e5a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 0767349e1d1253e6849b4c2af2059db661f54343.nq.gz
├── filetree
│   └── 0767349e1d1253e6849b4c2af2059db661f54343.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 103 files
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

## Source repository

[rust-lang/cc-rs](https://github.com/rust-lang/cc-rs)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
