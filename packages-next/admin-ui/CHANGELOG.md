# @keystone-next/admin-ui

## 3.1.2

### Patch Changes

- [`d36e580cc`](https://github.com/keystonejs/keystone/commit/d36e580cc21e4b77a1bd0615c96c0793b9c5dac5) [#4426](https://github.com/keystonejs/keystone/pull/4426) Thanks [@timleslie](https://github.com/timleslie)! - Used the `KeystoneContext` type rather than `any` where appropriate.

- Updated dependencies [[`b6498d9f1`](https://github.com/keystonejs/keystone/commit/b6498d9f1341648742f2db78fec53b851b36dddd), [`d36e580cc`](https://github.com/keystonejs/keystone/commit/d36e580cc21e4b77a1bd0615c96c0793b9c5dac5), [`803626e88`](https://github.com/keystonejs/keystone/commit/803626e8854f9b7d293bd1829398d25a6692154a)]:
  - @keystone-next/keystone@5.0.0
  - @keystone-next/types@5.0.0
  - @keystone-next/admin-ui-utils@2.0.1

## 3.1.1

### Patch Changes

- [`c9159c956`](https://github.com/keystonejs/keystone/commit/c9159c9560efa7f7ae6ef802302c97b7a23f987b) [#4387](https://github.com/keystonejs/keystone/pull/4387) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Updated usage of `Fields` component

* [`eddd7e795`](https://github.com/keystonejs/keystone/commit/eddd7e79599e20f5bef61f240d874b37d0a084c4) [#4376](https://github.com/keystonejs/keystone/pull/4376) Thanks [@jossmac](https://github.com/jossmac)! - tidy the document field; primarily the toolbar

- [`139c74a4a`](https://github.com/keystonejs/keystone/commit/139c74a4aacfd5230fc86471b9cbd2a3c90bac9a) [#4378](https://github.com/keystonejs/keystone/pull/4378) Thanks [@timleslie](https://github.com/timleslie)! - Updated code to consistently use `context` rather than `ctx` for graphQL context variables.

- Updated dependencies [[`8b12f795d`](https://github.com/keystonejs/keystone/commit/8b12f795d64dc085ca663921aa6826350d234cd0), [`55a04a100`](https://github.com/keystonejs/keystone/commit/55a04a1004b7f15fcd41b4935d74fd1847c9deeb), [`f4a855c71`](https://github.com/keystonejs/keystone/commit/f4a855c71e966ef3ebc894a3b0f1af51e5182394), [`c9159c956`](https://github.com/keystonejs/keystone/commit/c9159c9560efa7f7ae6ef802302c97b7a23f987b), [`6cd469e29`](https://github.com/keystonejs/keystone/commit/6cd469e29682ff41a515ed76919efc2bfe0c7567), [`fa12a18b0`](https://github.com/keystonejs/keystone/commit/fa12a18b077367563b1b69db55274e47a1bd5027), [`eddd7e795`](https://github.com/keystonejs/keystone/commit/eddd7e79599e20f5bef61f240d874b37d0a084c4), [`139c74a4a`](https://github.com/keystonejs/keystone/commit/139c74a4aacfd5230fc86471b9cbd2a3c90bac9a), [`c9159c956`](https://github.com/keystonejs/keystone/commit/c9159c9560efa7f7ae6ef802302c97b7a23f987b)]:
  - @keystone-ui/popover@1.1.0
  - @keystone-ui/core@1.0.3
  - @keystone-next/admin-ui-utils@2.0.0
  - @keystone-next/keystone@4.1.1
  - @keystone-next/types@4.1.1
  - @keystone-ui/tooltip@1.0.3

## 3.1.0

### Minor Changes

- [`2d5f78207`](https://github.com/keystonejs/keystone/commit/2d5f78207103caaf8f86a4dd05b7e4b0a4795213) [#4302](https://github.com/keystonejs/keystone/pull/4302) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Add optional `allowedExportsOnCustomViews` export to field views

### Patch Changes

- Updated dependencies [[`ad10994d2`](https://github.com/keystonejs/keystone/commit/ad10994d271cff6f95e9e412a7e6830742a6d949), [`80c980452`](https://github.com/keystonejs/keystone/commit/80c9804522d493106321e1832ca07be07437720a), [`d2ebd1c39`](https://github.com/keystonejs/keystone/commit/d2ebd1c3922f1090bcc8e89c9c70ae880f6a24d9), [`add3f67e3`](https://github.com/keystonejs/keystone/commit/add3f67e379caebbcf0880b4ce82cf6a1e89020b), [`2d5f78207`](https://github.com/keystonejs/keystone/commit/2d5f78207103caaf8f86a4dd05b7e4b0a4795213)]:
  - @keystone-next/keystone@4.1.0
  - @keystone-ui/fields@1.0.2
  - @keystone-next/types@4.1.0

## 3.0.0

### Major Changes

- [`cc987d078`](https://github.com/keystonejs/keystone/commit/cc987d078653fd9e686069f9f885f1269b64a882) [#4269](https://github.com/keystonejs/keystone/pull/4269) Thanks [@timleslie](https://github.com/timleslie)! - Renamed `keystone` argument of `writeAdminFiles()` to `system`.

### Patch Changes

- [`11777cddb`](https://github.com/keystonejs/keystone/commit/11777cddba45b28a9e17a3149b792db121322b46) [#4263](https://github.com/keystonejs/keystone/pull/4263) Thanks [@timleslie](https://github.com/timleslie)! - Renamed the type `Keystone` to `KeystoneSystem` to avoid confusion with the core `Keystone` class.

* [`cbf11a69b`](https://github.com/keystonejs/keystone/commit/cbf11a69b8f2c428e2c0a08dd568b3bc0e0d80f4) [#4291](https://github.com/keystonejs/keystone/pull/4291) Thanks [@JedWatson](https://github.com/JedWatson)! - Fixed hard errors on the item screen when you can't load the item

- [`60e061246`](https://github.com/keystonejs/keystone/commit/60e061246bc35b76031f43ff6c07446fe6ad3c6b) [#4260](https://github.com/keystonejs/keystone/pull/4260) Thanks [@JedWatson](https://github.com/JedWatson)! - Updating Create Item placement and style

- Updated dependencies [[`96a1d5226`](https://github.com/keystonejs/keystone/commit/96a1d52263db625cd117ab85cb6a4a5c3888fdca), [`11777cddb`](https://github.com/keystonejs/keystone/commit/11777cddba45b28a9e17a3149b792db121322b46), [`5866cb81f`](https://github.com/keystonejs/keystone/commit/5866cb81fd462b86851deb0a88e5034f1934ac84), [`c858a05fe`](https://github.com/keystonejs/keystone/commit/c858a05fee6dc3ed3d80db9fdf50944217bee072), [`d1ea5e667`](https://github.com/keystonejs/keystone/commit/d1ea5e66750175e907f41a58c15fce86a4b4ea77), [`c60b229ec`](https://github.com/keystonejs/keystone/commit/c60b229ec38b4845ac606ee83b9787a97834baf3), [`b2de22941`](https://github.com/keystonejs/keystone/commit/b2de229419cc93b69ee4027c387cab9c8d701488), [`cc987d078`](https://github.com/keystonejs/keystone/commit/cc987d078653fd9e686069f9f885f1269b64a882), [`9fddeee41`](https://github.com/keystonejs/keystone/commit/9fddeee41b7e0dbb3854e5ce6abea4cdeeaa81d0), [`cc987d078`](https://github.com/keystonejs/keystone/commit/cc987d078653fd9e686069f9f885f1269b64a882)]:
  - @keystone-next/keystone@4.0.0
  - @keystone-next/types@4.0.0
  - @keystone-next/admin-ui-utils@1.0.2

## 2.0.2

### Patch Changes

- [`c103cde7d`](https://github.com/keystonejs/keystone/commit/c103cde7da198cd7e9adefa763c51e433680e800) [#4226](https://github.com/keystonejs/keystone/pull/4226) Thanks [@jossmac](https://github.com/jossmac)! - General admin tidy

* [`302afe226`](https://github.com/keystonejs/keystone/commit/302afe226162452c91d9e2f11f5c29552df70c6a) [#4195](https://github.com/keystonejs/keystone/pull/4195) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Fixed create item modals staying open after creating when on the item page

- [`7afde2fb5`](https://github.com/keystonejs/keystone/commit/7afde2fb516e1d3824d73a96308abb4a6b022400) [#4253](https://github.com/keystonejs/keystone/pull/4253) Thanks [@jossmac](https://github.com/jossmac)! - Admin UI layout experiments and general tidy, esp. fields

* [`8291187de`](https://github.com/keystonejs/keystone/commit/8291187de347784f21e4d856ed1eefbc5b8a103b) [#4207](https://github.com/keystonejs/keystone/pull/4207) Thanks [@JedWatson](https://github.com/JedWatson)! - Improve field cell components

- [`36cf9b0a9`](https://github.com/keystonejs/keystone/commit/36cf9b0a9f6c9c2cd3c823146135f86d4152718b) [#4182](https://github.com/keystonejs/keystone/pull/4182) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Fixed item form not being updated with new values when no errors are returned

* [`6eb4def9a`](https://github.com/keystonejs/keystone/commit/6eb4def9a1be293872e59bcf6472866c0981b45f) [#4181](https://github.com/keystonejs/keystone/pull/4181) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Fixed fields with read access statically false breaking the item page

- [`28e2b43d4`](https://github.com/keystonejs/keystone/commit/28e2b43d4a5a4624b3ad6683e5f4f0116a5971f4) [#4224](https://github.com/keystonejs/keystone/pull/4224) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Fixed lazy admin meta staying in the loading state even though the request completed in Safari after restarting the dev server but not reloading the page

* [`cfa0d8275`](https://github.com/keystonejs/keystone/commit/cfa0d8275c89f09b89643c801b208161348b4f65) [#4198](https://github.com/keystonejs/keystone/pull/4198) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Fixed fields on item page flicking between new value and old value when saving

- [`0e65409c7`](https://github.com/keystonejs/keystone/commit/0e65409c7416d285fdc4f9da4a7dfb0f652c6cb2) [#4216](https://github.com/keystonejs/keystone/pull/4216) Thanks [@jossmac](https://github.com/jossmac)! - Admin UI tidy: mostly alignment and spacing consolidation.

- Updated dependencies [[`fd4b0d04c`](https://github.com/keystonejs/keystone/commit/fd4b0d04cd9ab8ba12653f1e64fdf08d8cb0c4db), [`d2cfd6106`](https://github.com/keystonejs/keystone/commit/d2cfd6106b44b13254ff1e18601ef943c4211faf), [`c103cde7d`](https://github.com/keystonejs/keystone/commit/c103cde7da198cd7e9adefa763c51e433680e800), [`3d66ebc87`](https://github.com/keystonejs/keystone/commit/3d66ebc87c4dea7fa70df1209c8d85f539ceccb8), [`98e8fd4bc`](https://github.com/keystonejs/keystone/commit/98e8fd4bc586c732d629328ef643014ce42442ed), [`d02957453`](https://github.com/keystonejs/keystone/commit/d029574533c179fa53f65c0e0ba3812dab2ba4ad), [`98dd7dcff`](https://github.com/keystonejs/keystone/commit/98dd7dcffa797eb40eb1713ba1ac2697dfef95e3), [`bc198775e`](https://github.com/keystonejs/keystone/commit/bc198775ed27d356017b4a0c6aadeba47e37ce2e), [`7afde2fb5`](https://github.com/keystonejs/keystone/commit/7afde2fb516e1d3824d73a96308abb4a6b022400), [`5216e9dc6`](https://github.com/keystonejs/keystone/commit/5216e9dc6894c1a6e81765c0278dc6f7c4cc617b), [`fab97f6b4`](https://github.com/keystonejs/keystone/commit/fab97f6b416d7040cdd159be379e226142fc189c), [`8f4ebd5f7`](https://github.com/keystonejs/keystone/commit/8f4ebd5f70251ccdfb6b5ce14efb9fb59f5d2b3d), [`2a2a7c00b`](https://github.com/keystonejs/keystone/commit/2a2a7c00b74028b758006219781cbbd22909be85), [`68f1c8fdc`](https://github.com/keystonejs/keystone/commit/68f1c8fdc83f683d13de55b2f3a81eff7639ebf6), [`b9e93cb66`](https://github.com/keystonejs/keystone/commit/b9e93cb66e8559858ecfbfee3244a761f821b9ec), [`b89377c9c`](https://github.com/keystonejs/keystone/commit/b89377c9c668c6a4b1be742a177cfb50568d48bf), [`9928da13e`](https://github.com/keystonejs/keystone/commit/9928da13ecca03fed560a42e1071afc59c0feb3b), [`fab97f6b4`](https://github.com/keystonejs/keystone/commit/fab97f6b416d7040cdd159be379e226142fc189c), [`d2927f78c`](https://github.com/keystonejs/keystone/commit/d2927f78c40bdb21190d06991466566f49a9f08b), [`dce39ca1b`](https://github.com/keystonejs/keystone/commit/dce39ca1be682647b05a2b59710f05e421b140a1), [`0e65409c7`](https://github.com/keystonejs/keystone/commit/0e65409c7416d285fdc4f9da4a7dfb0f652c6cb2)]:
  - @keystone-ui/core@1.0.2
  - @keystone-ui/fields@1.0.1
  - @keystone-next/keystone@3.0.0
  - @keystone-ui/pill@1.0.2
  - @keystone-ui/tooltip@1.0.2
  - @keystone-next/types@3.0.0
  - @keystone-next/admin-ui-utils@1.0.1
  - @keystone-ui/modals@1.0.2
  - @keystone-ui/toast@1.0.1
  - @keystone-ui/button@2.0.1

## 2.0.1

### Patch Changes

- [`39a5890de`](https://github.com/keystonejs/keystone/commit/39a5890de2021b9e32569ce4011c3e2948d4ede6) [#4160](https://github.com/keystonejs/keystone/pull/4160) Thanks [@JedWatson](https://github.com/JedWatson)! - Show a neutral button on the Item form when there are no changes to save

- Updated dependencies [[`344157577`](https://github.com/keystonejs/keystone/commit/344157577aa285b22cd621809a72a540830f47ab), [`ce6b8ebee`](https://github.com/keystonejs/keystone/commit/ce6b8ebeef39f2d22bfc62500a408739a7f1f419), [`6c3b566a1`](https://github.com/keystonejs/keystone/commit/6c3b566a130fa4eb5ae57e638b4cff7a16299998), [`c3e4c1e3f`](https://github.com/keystonejs/keystone/commit/c3e4c1e3fdf8ffdbfd785860c26d15e665c5e25e)]:
  - @keystone-ui/pill@1.0.1
  - @keystone-ui/tooltip@1.0.1
  - @keystone-ui/button@2.0.0
  - @keystone-ui/notice@1.0.1
  - @keystone-ui/core@1.0.1
  - @keystone-ui/modals@1.0.1

## 2.0.0

### Major Changes

- [`ae0fc4d78`](https://github.com/keystonejs/keystone/commit/ae0fc4d787ba47eb9e5258a20a57f76124aee797) [#4132](https://github.com/keystonejs/keystone/pull/4132) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Remove entrypoint at `@keystone-next/admin-ui` and replace with `@keystone-next/admin-ui/context` and `@keystone-next/pages/*`

### Minor Changes

- [`166acb9bf`](https://github.com/keystonejs/keystone/commit/166acb9bf211e0ee8a90d4740f6ebc54ffe72dec) [#4138](https://github.com/keystonejs/keystone/pull/4138) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Support uploading files with apollo-upload-client

### Patch Changes

- [`71b74161d`](https://github.com/keystonejs/keystone/commit/71b74161dfc9d7f0b918a3451cf545935afce94d) [#4146](https://github.com/keystonejs/keystone/pull/4146) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Disable create buttons while create item modal is open

- Updated dependencies [[`ae0fc4d78`](https://github.com/keystonejs/keystone/commit/ae0fc4d787ba47eb9e5258a20a57f76124aee797), [`166acb9bf`](https://github.com/keystonejs/keystone/commit/166acb9bf211e0ee8a90d4740f6ebc54ffe72dec), [`ae0fc4d78`](https://github.com/keystonejs/keystone/commit/ae0fc4d787ba47eb9e5258a20a57f76124aee797), [`166acb9bf`](https://github.com/keystonejs/keystone/commit/166acb9bf211e0ee8a90d4740f6ebc54ffe72dec)]:
  - @keystone-next/admin-ui-utils@1.0.0
  - @keystone-next/types@2.0.0
  - @keystone-next/keystone@2.0.0

## 1.0.0

### Major Changes

- [`9d360a67b`](https://github.com/keystonejs/keystone/commit/9d360a67b69ec38e3018fe132b1e34f24956f86c) [#4106](https://github.com/keystonejs/keystone/pull/4106) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Initial release

### Patch Changes

- Updated dependencies [[`9d360a67b`](https://github.com/keystonejs/keystone/commit/9d360a67b69ec38e3018fe132b1e34f24956f86c)]:
  - @keystone-ui/button@1.0.0
  - @keystone-ui/core@1.0.0
  - @keystone-ui/fields@1.0.0
  - @keystone-ui/icons@1.0.0
  - @keystone-ui/loading@1.0.0
  - @keystone-ui/modals@1.0.0
  - @keystone-ui/notice@1.0.0
  - @keystone-ui/options@1.0.0
  - @keystone-ui/pill@1.0.0
  - @keystone-ui/popover@1.0.0
  - @keystone-ui/toast@1.0.0
  - @keystone-ui/tooltip@1.0.0
  - @keystone-next/keystone@1.0.0
  - @keystone-next/types@1.0.0
