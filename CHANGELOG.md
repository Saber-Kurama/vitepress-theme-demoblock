## [0.0.1](https://github.com/Saber-Kurama/vitepress-theme-demoblock/compare/70985030a7fc5bcf5ecf87b5ed0cbc5dfa225cf0...v0.0.1) (2023-07-12)


### Bug Fixes

* 临时解决setup 语法报错，锁定 vue 版本为 3.2.44。 ([0e0b6e3](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/0e0b6e3a1dbfcbe70e6cc63e08cb360cf2ddab10))
* 删除字体图标替换成css生成三角形 ([92d7cb7](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/92d7cb7506041c7abb499cc47479355d94fd94fe))
* controlText does not disappear when a block of code is retracted on the mobile client ([3cb1040](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/3cb1040307c1ef7e108994da253dc8719efa71a5))
* demo style bug ([3f69bb9](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/3f69bb9d7c3f122fca5bacb53b760c2dc4e6973b))
* **Demo:** 修复窗口缩放时，底部 demo-block-control 的宽度和位置不准确问题 ([d039003](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/d0390031e88cc5d418ba10bcebc5bd6e71567b98))
* **Demo:** 已经有一个展开操作区固定在下方的情况下，再展开一个会出现重叠的现象 ([dd9f061](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/dd9f0612310700942ed369853432f8d08f4a4f0a)), closes [#10](https://github.com/Saber-Kurama/vitepress-theme-demoblock/issues/10)
* **Demo:** 已经有一个展开操作区固定在下方的情况下，再展开一个会出现重叠的现象 ([5dd9608](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/5dd9608a6c60e468fae841a18fc041e348f9a5ae)), closes [#10](https://github.com/Saber-Kurama/vitepress-theme-demoblock/issues/10)
* **Demo:** demo-block-control样式问题；代码展开/收起的操作区未遮挡语言的问题 ([a6f0e55](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/a6f0e554aeba95e01cd02ea4d35db1f5d8319129)), closes [#8](https://github.com/Saber-Kurama/vitepress-theme-demoblock/issues/8) [#9](https://github.com/Saber-Kurama/vitepress-theme-demoblock/issues/9)
* folded width of the demoblock ([83774d1](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/83774d115d8310bdd0360ea5a23bb7cc717cbf14))
* scriptImports为空时报错 ([99235b8](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/99235b8dd5f29f130811b9e299be30ba0f1fab8a))
* when demoblock i18n is empty, the component reports an error ([db90f4e](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/db90f4ed88cd1252886d9b96dc0e125da0c233e8))
* when demoblock i18n is empty, the component reports an error ([f84a2e1](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/f84a2e14957846983f27d1652655a62a6f4d8425))


### Features

* 1.UI改版； ([78bf883](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/78bf8837d519044853c629a9da004d32a243c204))
* 复制代码后 toast 展示成功 ([d05b64e](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/d05b64e20b3c3518396c860b99373c18b5ea5f63))
* 适配vitepress@1.0.0-alpha.28 ([a5de5b5](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/a5de5b5eb1b31a49047eed769dc6497fe930ca4c))
* 适配vitepress@1.0.0-alpha.28, 支持多script ([e144fd3](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/e144fd33b1e54f4ca5826531ef9da13d7967e659))
* 新增了复制成功文案 ([e3ff5b7](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/e3ff5b7e5d76535ce3af0c4ebf06bd007c4613dd))
* 新增了复制成功文案以及为demo展示增加溢出隐藏 ([2b23d2b](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/2b23d2b028e3c08364476926c59f8891733992fe))
* add support for Markdown File Inclusion ([004965f](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/004965fe73a13892a83ab4055326dba5707a4909))
* clipboard-copy ([eebb743](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/eebb743d36634e6d0994a5d7d334424352d8722e))
* code demo copy success text, update README.md ([9359f92](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/9359f924ee95c849e8e97bf2932c01a4ad668842))
* demo block control style ([3106b13](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/3106b1384406a060a634f753f4a387a9cb814bef))
* export utils ([75ee117](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/75ee1179071423397480324c4b53de20613c1f82))
* message toast style ([f3a751b](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/f3a751b75d8160d58906ba8716c2438a2206f5eb))
* remove lodash-es, Optimize package volume, reduce first load time ([c7956d9](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/c7956d9c5a2852c2d277e9cd081b0648ef4b9f9e))
* rename demo-block to demoblock ([7f674b5](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/7f674b5f488c8aa6fce92dbd1c3431c4ecbab3cd))
* split style files ([3780f30](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/3780f3099b16073fd0aa31baed44ce0ebe9ffcf5))
* support css preprocessors ([c8a335e](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/c8a335e9ef00313695c0fa45fbd81e532d74132d))
* support custom scriptImports and custom lang ([68b2f38](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/68b2f38f97bc3123f7171ecb92fe34041431301b))
* support custom scriptImports and custom scriptReplaces, see readme.md for details ([8434eba](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/8434eba35e9537338fe60898f4fadb1afe84c6a4))
* support i18n ([af7cc96](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/af7cc969e3dde91e6286a265353aa2c9bda270cc))
* support styleReplaces ([a99cca3](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/a99cca324c9803c01e5098baefb360acf99083da))
* support vue script setup syntax ([43083a2](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/43083a21a1863a05523b84681cb973c816d602c1))
* theme index.css ([b9ec799](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/b9ec7998c12f4129d1a68ef8dde66ad221e310b7))
* v2.0 开发中，使用TypeScript重写，支持vitepress新版 ([048dcaa](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/048dcaac1f1fa69e2ad9c731540fb5aae6cbf57b))
* v2.0 开发中，使用TypeScript重写，支持vitepress新版 ([3245fc4](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/3245fc490077fb0de4008b3e777c7d11f7489373))
* vitepress-theme-demoblock@1.0 ([db9a46c](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/db9a46c1bebb087890e388f9fda2f6eee872fd3e))
* vitepress-theme-demoblock@1.0 ([7098503](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/70985030a7fc5bcf5ecf87b5ed0cbc5dfa225cf0))
* vitepress-theme-demoblock@1.1 ([6316809](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/63168096908189b46a4eb4780bf891d082825e5e))
* vitepress-theme-demoblock@1.1.0, support script setup and typescript ([09cfd3a](https://github.com/Saber-Kurama/vitepress-theme-demoblock/commit/09cfd3a04d7074cea0fd43839f6173a94b6e1a63))



