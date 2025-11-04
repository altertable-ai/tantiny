# Changelog

## [0.4.2](https://github.com/altertable-ai/tantiny/compare/tantiny/v0.4.1...tantiny/v0.4.2) (2025-11-04)


### Bug Fixes

* **highlighting:** only highlight the matching prefix ([#9](https://github.com/altertable-ai/tantiny/issues/9)) ([8ce9bbe](https://github.com/altertable-ai/tantiny/commit/8ce9bbe56392ed055b56ee7118427e41c1140222))

## [0.4.1](https://github.com/altertable-ai/tantiny/compare/tantiny/v0.4.0...tantiny/v0.4.1) (2025-11-03)


### Bug Fixes

* **highlighting:** ensure the same tokenizer is used for text & query + handle last term as prefix ([#7](https://github.com/altertable-ai/tantiny/issues/7)) ([e713de3](https://github.com/altertable-ai/tantiny/commit/e713de385fea5a8060e615c173e9097871e052fc))

## [0.4.0](https://github.com/altertable-ai/tantiny/compare/tantiny-v0.3.3...tantiny/v0.4.0) (2025-11-01)

[Resume development & transfer ownership](https://github.com/altertable-ai/tantiny/pull/1) following https://github.com/baygeldin/tantiny/pull/24

### Features

* Add simple highlighting feature ([7d4273e](https://github.com/altertable-ai/tantiny/commit/7d4273e657b658a670fc882714bb319d0b3b374c))
* Add in-memory indexing capabilities ([7d4273e](https://github.com/altertable-ai/tantiny/commit/7d4273e657b658a670fc882714bb319d0b3b374c))

### Bug Fixes

* Support Ruby 3.4 moving from Rutie to Magnus ([7d4273e](https://github.com/altertable-ai/tantiny/commit/7d4273e657b658a670fc882714bb319d0b3b374c))

### [0.3.3](https://github.com/baygeldin/tantiny/compare/v0.3.2...v0.3.3) (2022-04-29)


### Bug Fixes

* Require native extension through Thermite::Fiddle ([da4cb44](https://github.com/baygeldin/tantiny/commit/da4cb44438f9bdeb604fbe57ff595f552fdf1c8c))

### [0.3.2](https://github.com/baygeldin/tantiny/compare/v0.3.1...v0.3.2) (2022-04-21)


### Bug Fixes

* Fix the native extension for OSX ([4026e8f](https://github.com/baygeldin/tantiny/commit/4026e8fad4179b100abc89d7f6aa2203232c9322))

### [0.3.1](https://github.com/baygeldin/tantiny/compare/v0.3.0...v0.3.1) (2022-03-17)


### Bug Fixes

* Fix native extensions build on Ruby <= 3.1 ([f801ef3](https://github.com/baygeldin/tantiny/commit/f801ef38db4ec164c28c27a309b215ad67e63b5c))

## [0.3.0](https://github.com/baygeldin/tantiny/compare/v0.2.2...v0.3.0) (2022-03-17)


### ⚠ BREAKING CHANGES

* `commit` method is no longer public

### Features

* Support multithreaded and multiprocess environments ([053b4a0](https://github.com/baygeldin/tantiny/commit/053b4a0a026ae8fd689d95a8d4f3b1a7b6d6779f))


### Bug Fixes

* Create the folder at index path when it doesn't exist ([c9446b7](https://github.com/baygeldin/tantiny/commit/c9446b7e949aad40de9ce179707a88915682055c))

### [0.2.2](https://github.com/baygeldin/tantiny/compare/v0.2.1...v0.2.2) (2022-03-07)


### Bug Fixes

* Fix native extension initialization ([78c7495](https://github.com/baygeldin/tantiny/commit/78c74951a4ade684395f756467aa583aad1f90a8))
* Include transpiled files in the gem build ([5dba8f6](https://github.com/baygeldin/tantiny/commit/5dba8f6a75f36eb27756c9e8d8f7f3872d73bf97))

### [0.2.1](https://github.com/baygeldin/tantiny/compare/v0.2.0...v0.2.1) (2022-03-07)


### Features

* Initial release ([f10ed87](https://github.com/baygeldin/tantiny/commit/f10ed878e0b781580d5a04d854c44e6b868621b1))
