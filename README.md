# Repolex Knowledge Graph of SmileyChris/django-countries

RDF knowledge graph data for [SmileyChris/django-countries](https://github.com/SmileyChris/django-countries), parsed by [repolex](https://repolex.ai).

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
rlex download SmileyChris/django-countries
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a6462d30fa70992aa38a6c9af9a4ad9c88c41ae2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a6462d30fa70992aa38a6c9af9a4ad9c88c41ae2
│           └── chunk-001.nq.gz
└── blob
    ├── 0015642f166c56815597ecea8c9a8af9c643b695.nq.gz
    ├── 003c996375f83726df2dc1f27054d142cb692c5a.nq.gz
    ├── 0111bb5dca8197a067646690b683d26e99c73ee2.nq.gz
    ├── 031238a4f26e7104974ebb1472e623aa3f848cc3.nq.gz
    ├── 03ce123673121613044f8d8db42d2e138c4bc510.nq.gz
    ├── 03d8964bb7aa7bbf9d57d2ff509c46ef7c7887ad.nq.gz
    ├── 04509033e8fbe3c305dd7933f55299fe7fb7eb82.nq.gz
    ├── 046c1dcf7da3142836eab43e4163b08805b8bd31.nq.gz
    ├── 066410d7241ef1038afb9042c50447b31401cc69.nq.gz
    ├── 06718ac97ce7c040a0366ae852cafa0bdc69ba2b.nq.gz
    ├── 0765a0abfb08a2f911e7f70883695a17daa4bc6f.nq.gz
    ├── 07fce6f966de47238f9826a8be4c532bd3c103fb.nq.gz
    ├── 08945485bf4cff7b844e3c99098d9f47c873e7a4.nq.gz
    ├── 089c0748d50be6a624e5d54137fbdfec9cf13ae3.nq.gz
    ├── 0929974aa8d05070a4642d66de30f7a5c80b4a82.nq.gz
    ├── 09e71003f3a0b827735e469831e0b486553bab5f.nq.gz
    ├── 0af32f044d8ffeb1f9aa14f1089b159e2b0d8f8a.nq.gz
    ├── 0bef34cab321c1b494d266296ef27fc45ee3fd72.nq.gz
    ├── 0c21d69ab5528ba0c107445c4afeff3c61f7e447.nq.gz
    ├── 0c645609301cccc88275f99678981e02615e6021.nq.gz
    ├── 0d555ce2057fc67b1d3a6ded0153e6d797bc4c34.nq.gz
    ├── 0d8c19eaf8e9ce3f09966862237e2064235fd805.nq.gz
    ├── 0d9e3f5c96092ff8b83e1c4bbec1571dad1b8f05.nq.gz
    ├── 0dfb639377b2af245b4f073317503e68389a4b2b.nq.gz
    ├── 0ede3c2a1c26d5639ce35eb4913e487704aafec4.nq.gz
    ├── 0fbfdce7b303c2c5f41f0b60b936c772f8ba8df9.nq.gz
    ├── 10542cd69d78384c67429661cfce3fb174908bd6.nq.gz
    ├── 1058f29def71b0e741f32ace1922e96cbf40cec7.nq.gz
    ├── 126209b6ca438a077d2ef8feb4914e6822569e1a.nq.gz
    ├── 129c631f8b940278bf24a95d5bd6ef2e9335ebce.nq.gz
    ├── 133cffd39c7593d3915fa91999cca0a1d5c61c84.nq.gz
    ├── 14806e3cfab599fbd9ac8eada463079fb447e9c3.nq.gz
    ├── 14e1b0c8fe7c1435667f72a0e247628dee0144f9.nq.gz
    ├── 1525937132f0a109a879a95d1bf6e208ea3371b7.nq.gz
    ├── 1681b9fb664038a6b1a8bbf0c3b91822e5309db3.nq.gz
    ├── 19328ddc95da758c8a2596099f54c42c01ddd0c1.nq.gz
    ├── 199dca2437b240152912f73a0013ce3662595653.nq.gz
    ├── 19c221a88a3c3a0fd4da41224ee2200f4e71e879.nq.gz
    ├── 1b7f551d95106af9891f335916faaa5045c9cbec.nq.gz
    ├── 1bc86250c91a17c554e3c8e990a4b916865fa164.nq.gz
    ├── 1c455f59a94814ca18b74579b4489a74cfdb11cb.nq.gz
    ├── 1c62fe794b9ab2a52a4a92fe8d9a6c2b4469d0c8.nq.gz
    ├── 1c94d77086af576991fc6b185b75b309d9aec171.nq.gz
    ├── 1d6234bcc17f05343ba77a73d7afd33d5f04d4fa.nq.gz
    ├── 1d6a968fb253b548d5d7f638d6bbce271827f03c.nq.gz
    ├── 1f0c15b1ba40ead4926068fa9cb270e0709621dc.nq.gz
    ├── 1f523d1162b89097f4e3f609ba1d45721ef59f82.nq.gz
    ├── 1f9040b3e1d2e0a835310a840ebd79a9ce4cb476.nq.gz
    ├── 204c87e5fa3ce3bbd19312a9fa8e4a8236e79c32.nq.gz
    ├── 206e7aadd5ceb63189b10171c521409251d3b9ff.nq.gz
    ├── 20c8ab8bd4f332679c83410037e4708eb9a36eb5.nq.gz
    ├── 20de860ebad9f850a997ffa8646091003fe2a1fd.nq.gz
    ├── 215ebb67bcc9bea8060cc24db3271b5ecef33813.nq.gz
    ├── 235587ec3b5e6b385f3f2e05c327017c401b2675.nq.gz
    ├── 249d624aa714ff8586ffbfab97ec0b465bf7ae28.nq.gz
    ├── 266097f15730bb5b1b557c73d855c6195b17dde2.nq.gz
    ├── 26cc71bf409cf7a577140ffa35546011bd722f80.nq.gz
    ├── 2791ec633413880735424cf20ce982e726cc2dc2.nq.gz
    ├── 27aaaa49d41042d307a9b34c8b76fd2eaf1ae310.nq.gz
    ├── 2800bd4b1155a650fddb2c9e385f72e844b7cb96.nq.gz
    ├── 280236392e8d8f08c8c25485478244a3cbe87a70.nq.gz
    ├── 288f7917358cc23c6c4ee51c97ebb9a3e0bf4268.nq.gz
    ├── 2898de2e06f5e77a5d58ee0e88462ef347d0ba09.nq.gz
    ├── 28e1dfc4f88140b733ffa3ce8e1bad1bbffbee19.nq.gz
    ├── 2a3e6ae3e374a4c50aeb570b5a70bad5e0814a58.nq.gz
    ├── 2a4e71ad4243e78bdf11d5995a211e29cee052ec.nq.gz
    ├── 2a602aa02a2287c1cad6a17a84ed55dfc15c937f.nq.gz
    ├── 2cac52e1fc685f7beb8210bc43e0d404d2a4dccb.nq.gz
    ├── 2d167171367b099c3933edb81fa9a6cc3fa11a7e.nq.gz
    ├── 2d6dcba673992694162f1fc291549aa707d891c1.nq.gz
    ├── 2d7f21b8cbc06ab8bf0538bd19e0c22e3e21c31d.nq.gz
    ├── 2d8693d8d252dc0dda15c9cd6acf0629ac829114.nq.gz
    ├── 2e82b360644af00c188c704f8340dad5fa06d214.nq.gz
    ├── 2ef117132aa631707eb41e7ddcc481993334e6e6.nq.gz
    ├── 2f73b350d0545c6569848aa8ca1f431366b1707c.nq.gz
    ├── 313c2604aa1983bd948d6d9c6e9077732356ad1e.nq.gz
    ├── 323d3b716eb30a3acff632515361dcf4b0be9081.nq.gz
    ├── 32917747a3dedc6913bde4bf4dc4ecff615e5996.nq.gz
    ├── 33873363b4ae833ce0701dd08eb77975196d1141.nq.gz
    ├── 34554f3bc3878ef75deebe0f614be333271dcf81.nq.gz
    ├── 35bf320298787b1033280e6a9eecfef470065b31.nq.gz
    ├── 3717005f0adbd4947995f726b9a026bca5c05505.nq.gz
    ├── 3720fc4a262b3a3997ab29b63d367a528449865d.nq.gz
    ├── 37711fd9a4ef7083c50e1e1483f876b5b84fc7a8.nq.gz
    ├── 37beadfbc6323f2b5e2ac5d103359499cb1d6fd9.nq.gz
    ├── 37bfbeda2a951b2a4eeb9768f5cd21239b8f342c.nq.gz
    ├── 37c8c3d334a0482e51c91476e38d50adcf3e212b.nq.gz
    ├── 37cd35f8a4edb8e0a3770db1493b07cb58cba890.nq.gz
    ├── 39c87825320011aa0dd66a4b50705550cca180e0.nq.gz
    ├── 3ad13827a096c67cf44085350d7ebf3795eadc93.nq.gz
    ├── 3af6339f6cdd6b6de5c48596ea6ed0e69c3fe95e.nq.gz
    ├── 3cddeecf7aa8ea995e0f34d80f701fd70c60d6d6.nq.gz
    ├── 3d3b13786fce79c3275c5a964f24db2341625ac2.nq.gz
    ├── 3dd57939357d74740035a91f51644f0e6e73f78d.nq.gz
    ├── 40146454caaa4f72f95bd98a155830b61e2308c7.nq.gz
    ├── 4058bd5822d4aaa0539ae022b09d3f56e47f1588.nq.gz
    ├── 40d1b06489c8da27c721fd454d76fd1d2982c5f3.nq.gz
    ├── 416379d368248bd980e2146f6e039456e09792ac.nq.gz
    ├── 41fcc2d37c871893ef903419d7ad4e57877bf3c1.nq.gz
    ├── 433b1314c48db8fc462a5b2b361788e47c013753.nq.gz
    ├── 448e65cb8fe562335e0b96424f7868615b952ba8.nq.gz
    ├── 450fd74b3e54f3cd15deb1eef25914b3b45cea3d.nq.gz
    ├── 4787f84bfec7db54cfa9ad0984ba72760981856e.nq.gz
    ├── 481ffd69a8cd9a7c92163dc9a721ddda48192014.nq.gz
    ├── 49e72c0552c5a426e6dae95391de24199cdb8df5.nq.gz
    ├── 4a49238edd7a86e9bf85661b159394bccfeaf78c.nq.gz
    ├── 4ada27cc58d88d9fdba00d4bbc68ffdec3195458.nq.gz
    ├── 4c61496dbdc20c2f31a5a6107876429eaaf20a85.nq.gz
    ├── 4c77d67cf4a7e3aa7dc93e91b4395d32d9108a04.nq.gz
    ├── 4dc735a1739e2880e1ee00af58e66234337569ab.nq.gz
    ├── 4f0937cbaf9c8f618761a72d33f9a4744b8b28df.nq.gz
    ├── 4f1c271d423042158effcdc60c196a535b6835ed.nq.gz
    ├── 4f1dadcc173b1c6f15201a868ea5af0f2617b5a6.nq.gz
    ├── 4f7224154b5e294e607403e236b052f271ea75dc.nq.gz
    ├── 4fa1f6384b0ab859901a9ee97f483cbc1565819b.nq.gz
    ├── 513de42fbcf3012ac50098ad55a952f462746ca4.nq.gz
    ├── 523cab12f1b09b08d34c973a6c1087282c00abb1.nq.gz
    ├── 52e33496a0c027130cc5dd5979a08c17d15ca891.nq.gz
    ├── 530bddbfe3c9a5d1bef0f1a0d3c8ee4f51819323.nq.gz
    ├── 531cdb97ec6df2ea0d9d45b5cb5c2436e4051c0e.nq.gz
    ├── 534387a5691252b7630dba33913d87e3faecf2b9.nq.gz
    ├── 53cdf7ad4e1ee04254dad17fb619a9f7f791060a.nq.gz
    ├── 54259c07bc573478b671e99863d64de776c8ce8a.nq.gz
    ├── 55510d6db74ae28909b9870e19e65a8a5403fd75.nq.gz
    ├── 55b910dfe9f4df504fefa7694a9e973b81f80166.nq.gz
    ├── 561675f89b6489b4ba9e9fc25886fef9b6889afd.nq.gz
    ├── 56918bfc0181e8097ab0095ba5c37d83ed8b9f32.nq.gz
    ├── 5714b4535b25964a6b2c949b3168560e6df56825.nq.gz
    ├── 5785c13371746313e2f7ee2e5a3b6daf9ea3e85a.nq.gz
    ├── 57dc21c6135b3a17e57f7694f223f46f2654944f.nq.gz
    ├── 580c8d52097478a40bbf0dda6748a52152808e11.nq.gz
    ├── 592ae1a0ef0c718f74d1fb4a8ac024e52726faea.nq.gz
    ├── 596178868e9aa143fb5bd4632c1561af99713be4.nq.gz
    ├── 5c7f795a75ca97de40741bf9e41544803304fe34.nq.gz
    ├── 5e299d16a227b1d27454fd4576f98460eb8f480c.nq.gz
    ├── 5e69416936db35977d3ecde15f25336c8005bb96.nq.gz
    ├── 5ea2da44f9ac3e1c22c065f2bacf004701dce663.nq.gz
    ├── 5f28909c29b8681f21a7aef86ecb48480d455f18.nq.gz
    ├── 5f3d8ac57e702c70c4b1804c85e134484d453d2e.nq.gz
    ├── 6144583ad2faa1f43958baea6a5dc9af1a4bd855.nq.gz
    ├── 62588a82daffc1d350b17d1e08ace79fa16f9cc7.nq.gz
    ├── 629f259f5d07bcaf93f5677773e693823572f3b1.nq.gz
    ├── 632a5fd8dd7dca7a4fe01aaea2291bd55e25ce65.nq.gz
    ├── 64348244a4427a148fc5e7ca97f631810ce8fe69.nq.gz
    ├── 6441802344850bf6c8a83e958ebaed5aa7766b83.nq.gz
    ├── 65f5d9e39bffff931106e6d0cd1026a400558683.nq.gz
    ├── 681e50aeb817907d7b3de512969317ff38031f38.nq.gz
    ├── 68855424b6f515813d2659086b43ffb4649da5e3.nq.gz
    ├── 689aab79ecfc2180d72ab1ec82e728b3a53f5fe1.nq.gz
    ├── 68dcdd5af7d1a237f19a9b8ecc4b8ffc148f01e9.nq.gz
    ├── 69cd34a2ff577f4722b862cdfc2b736f24ba0ae9.nq.gz
    ├── 6a8a6f75a7f14ab1830df0bd1009b51f63bf68f6.nq.gz
    ├── 6b7d8394f5ab769212b12f937b187aefeeff026f.nq.gz
    ├── 6baeec2fb5a5e92cad095b8417761f855e2f343f.nq.gz
    ├── 6bbd1d3c78d68eb272a2e825daec5158990efd0b.nq.gz
    ├── 6c6d1064a8a0b7a2d17b7cdf10cabe2243dfd8a7.nq.gz
    ├── 6d3fe8b0fc77e990a6ad2c713b252ea985106a59.nq.gz
    ├── 6d4efcb157ee7f66c5906c029ff1f74ab72d28e3.nq.gz
    ├── 6d7223a4feb8ca00609e1ad167ddbe95937fe276.nq.gz
    ├── 6d840f8bf069547086e971e7a7ed106d8b415b3a.nq.gz
    ├── 6dbba6a32ea84d2b73fed9a9fa879f5c1b8c5a2d.nq.gz
    ├── 6eadd88db87f50d76e47d23a51b759ff28fa69d9.nq.gz
    ├── 6eb0c41343fcc10690cf5a2ff61d3cbf464301d5.nq.gz
    ├── 6eed5075c092336ef23fcc53451fe8c85b1bd4ff.nq.gz
    ├── 6ef0db344d18474cfeae476ae102ac5dfda00c8c.nq.gz
    ├── 6f9a26ef95536bff5c1ab16ea874481613f77968.nq.gz
    ├── 7029201fb940ae8e21893bfc1882272532dbb71d.nq.gz
    ├── 702e500859c1395d7620a7f07055e218808c51b3.nq.gz
    ├── 708cbf1df77d1e8e9ef8cf5cc1d3728bc1d51751.nq.gz
    ├── 70bfe34af9d6907dde6fcd025989ce9825182086.nq.gz
    ├── 71933a96c91d0b6ec4c2804119f0254a5d9521a7.nq.gz
    ├── 73039627eb0675ec67584a164be6ddaad4e90ae6.nq.gz
    ├── 7369b9e4cc4969890b0d9b1cdcf6c6119a3e4670.nq.gz
    ├── 73feb36a9469da9f1a5ecda48cebecc4d8efb2dc.nq.gz
    ├── 73fed1f99a3ecc66d71433bb98756eb4712ab753.nq.gz
    ├── 7421ecc6d525740476e6438b64a85d27a65c6106.nq.gz
    ├── 745a71d62a4eafc8400a989aeba66991ba564d74.nq.gz
    ├── 74df50834234bbc0b2177deb37dfdca73b67812a.nq.gz
    ├── 74f39fd9a88eb3ffa154cab92b0d7754ae07b5da.nq.gz
    ├── 7525731e397b4de5fa1a84379cf9f9d2477510bb.nq.gz
    ├── 7533e5cd76b4da3ae84c2abe8da76cb669e7e388.nq.gz
    ├── 7557345e4b4e2f1aaee6dd1865a6a8cd766e53f5.nq.gz
    ├── 757c1e68500ea22a733073b8749b0e9b14a260eb.nq.gz
    ├── 75c8f4ea908377fa78882a1af4f38e2c8c6e5731.nq.gz
    ├── 7653ccac01d5c9e89be26af6c61c7f0010fdec47.nq.gz
    ├── 767deb67a3cce1a2d40465899ae3d700713304c8.nq.gz
    ├── 779400400627d3a86e7c41578b7245cd28d5d24b.nq.gz
    ├── 77cafc7061fa7893b49ec480d2b514225346fbb4.nq.gz
    ├── 7932243243aa06f05e0650ad177d5785fd041514.nq.gz
    ├── 79acb27f3f32306ea2f33580ba907764af7002f4.nq.gz
    ├── 7a4dd43c42cb7db68c88005690bcf9114e18a4cf.nq.gz
    ├── 7a629a39e612bdd2a092c13802b17c90de058aa5.nq.gz
    ├── 7b3fd388abacf217483f64316e207ebf481caf77.nq.gz
    ├── 7c468371600315e68990920c5b8e8b113e22ff4d.nq.gz
    ├── 7c64caf5941721a03971f3657d0118404401a209.nq.gz
    ├── 7cbfe6bac5c71853782b3165fc0213eb4eade795.nq.gz
    ├── 7d2b276cc5385d1aee7d00f8e0ac4ed4bec350bb.nq.gz
    └── 7e813b4d72a9967d4add82678ea1243411591737.nq.gz

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

[SmileyChris/django-countries](https://github.com/SmileyChris/django-countries)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
