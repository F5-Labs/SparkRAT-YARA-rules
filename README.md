# Overview

YARA rule to detect SparkRAT (open-source offensive malware written in Go).

# Usage

```bash
yara -r MAL_APT_CRIME_RAT_GO_Unpacked_SparkRAT_Jul25.rule <PATH_TO_SCAN>
```

# Malware Bazaar matches

Based on samples from 2020-02 through 2024-04, the following samples matched. Note that no false positives were encountered. Note also that unique file hashes do not imply unique variants. This is because the binary embeds client configuration so a change in client configuration results in a change in hash.

| KASPERSKY ID | SHA1 | FIRST SEEN |
| --- | --- | --- |
| [Backdoor.Win64.GoRat.a](https://bazaar.abuse.ch/sample/99d32bfd135a2a1575b0f83a31a0ab817a6a4fe329f3e05bebdb73c26f988658) | b88126691e8fad868edd5e530f4d638d959b1b97 | 2022-06-03 |
| [Backdoor.Win64.GoRat.z](https://bazaar.abuse.ch/sample/442c2b7b8e7ec13306bfb6c1332bd87e4d9cac242fd86555df355a606b895c46) | bee6460d9a9b678b15f719dab2fd5bd5d1ee8c48 | 2022-10-21 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/decc5c6c0b83388a4faf541a22bc8faaf4c969903920d61b94e7c86d4c0be692) | 73e481dd39eeb77086b2def50f380a972b50aaa7 | 2023-02-05 |
| [Trojan-PSW.Win64.BroPass.bxn](https://bazaar.abuse.ch/sample/f252274a873b52ec33625b8f8ddb77dcdf9dfc8781585d22461f11c9d337b39d) | 9e2364263c617c19930a1b374d0c87cf8ab4f6c8 | 2023-05-08 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/07667fb2483b4727216ad7f7ce6413f32bea9530ad405fc7a415812ef6f3449a) | d972853ff110149b6a702b278ec168e4ba3e9daa | 2023-10-12 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/0b687729eb0cf87dafd6a27b4338f1aac5750eeaad3779bcea32c74602b50bb3) | 3da227a5eda5ecfa73cfb2643a83be7b35c1aa5e | 2023-10-12 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/2a6693166d2db53f60f7b18d49329204dc685a0c12c5cb8be1b62ced46980041) | 9dded41494e93d5378e4a85d5be5e6b1fc29ed52 | 2023-10-12 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/33d0fad1937c17ef1a7ef241497224ab603af12bc6fd56b320c9d7ab80294204) | 97bb9cdda02fc22d737ea20ed99d77d00b92cc5c | 2023-10-12 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/35da1fcf3156cf1d4c200ddebe7047a4830965522daaa4972be445ba36eddc62) | ea3784a979ab3bf8fa634477f89ca867bf2cabf9 | 2023-10-12 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/36b8623b6b1120313cd6a82751d5eb175d274d2952a8b3d3d6f69874fb4e88b9) | 9c6f15d8309bc785ed1267bd4cc3ac3da2dc5e72 | 2023-10-12 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/60c163c0f00a2aeeae8648898d75314b1c5e749777f227ac6c3c84656a68516e) | 287742b94cd4e9581c4f3aa1ca981ec67fd23b8a | 2023-10-12 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/6c4cb9d518f725b5c92f68699992f5525592328a47517d5897d971aac0ab6539) | 766deeee14dece814544852253d5bbb1823c1e60 | 2023-10-12 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/739ae6a61c12e14cca5f0c9cad3264f9cb7db70577efc9be354719455426443f) | 199bbaf99f00f79ef6f7c068927dd9b6bcb57c37 | 2023-10-12 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/78780bbc3be24085b453f77b1aee712a4b3fc41126a473a360768d3cc85a1f55) | 476f1f32ca9bfaa2af3d6aa83ec049c808cf514b | 2023-10-12 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/8ae2e582e6886753843e2f31001fe373bacc1cc0231bec8a6ba64d39394fe48c) | 1e272d5a39375d5625c02824f17fc6aa0d04d304 | 2023-10-12 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/9c672b05b987575f132c5f798a162abfa487ac60dcf19a19220b4451b10d79a2) | 154754016f21de234c9298942b994384709e673a | 2023-10-12 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/b724da89a80fc6aa20d1214c42f002ac850c5b11c37873a0a06f91e3168a8031) | d8097e47bf60b4e204acd48d206c586b6f00839c | 2023-10-12 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/c24630ac0393879f0a49b298e23fd8bdb5caf2fc7d544735d5dc1e3d8bd31100) | 72e03c4785952ae77ac7f16a19fa9edb59dc380c | 2023-10-12 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/d2c72e0d3a6a14fc83ae9f0ee58da6674ec7096fd7ddf61a7fabb6737c08fffb) | 4852809c59e185c716ed3c972e69e8fbfb48f28f | 2023-10-12 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/d3e19d396ade2fca0f69b766d9683068486009103d1a0aa57b3b6228b30bded2) | cfe7036aa46dff9b7b12b47556c5b5eeb6908d93 | 2023-10-12 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/db1b6d7e289c8c15bf9531dcc7f965a9c5a133b4f0438a95cde2ab2482080fd0) | 091f022ca05db3822e95b7141a3a13882b71f226 | 2023-10-12 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/efd8049d67d1bcdb6c0aba4da7ca6d4feacc65eb874447cc2c69d12dd4a83675) | 2d9d5ef1cb164244d9a0108ce130ebf47155b97e | 2023-10-12 |
| [Backdoor.Win64.GoRat.al](https://bazaar.abuse.ch/sample/fbe68d517f32b3a3507c6dfe6af41334a4c023d42a5a89725ea6e3fe28df4392) | 2c22681dcace627d7005bb8271ec8d4ce21d297a | 2023-10-12 |
| [HEUR-Backdoor.Multi.Spark.a](https://bazaar.abuse.ch/sample/bc140d13eb3190d51c46ad5855f32f908b7617ab5b40d38b4e64914733beff85) | fbc83079fd566ec722785a2d9865f95dddadb0b2 | 2023-10-12 |
| [HEUR-Backdoor.Multi.Spark.a](https://bazaar.abuse.ch/sample/d5f2cefc53e8355fe26e8c87f6212abf3a345cd1b82af97ac0bc540fd9dd1ed7) | 7647d36b7aef59782c2393828127ee1c39405e51 | 2023-10-12 |
| [HEUR-Backdoor.Multi.Spark.a](https://bazaar.abuse.ch/sample/e0b0fe364fe6118e0246d65eeb32a4b3d37c44737dd2aa8d2291af1482cbc99b) | 25035cf0c7791664bc8ae2d07a4a5cc5fd7183a4 | 2023-10-12 |
| [HEUR-Backdoor.Multi.Spark.a](https://bazaar.abuse.ch/sample/4d3c70c56adac4b118be2c42cab1cd3fb775f5c57ce85041f012d67ba2b73639) | 14ecccbc63f556939817d8c8990f455955b10017 | 2023-11-20 |
| [HEUR-Backdoor.Linux.Agent.gen](https://bazaar.abuse.ch/sample/103c3465516b5b5edd7a493b0cb4eab1a31ca282d693f59e7d6f8fd97e3c436a) | 39d7334f8eccbc9b0585680a3e2acf5269c3d259 | 2024-04-21 |
