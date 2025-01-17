# Changelog

The format is based on [Keep a Changelog].

[Keep a Changelog]: http://keepachangelog.com/en/1.0.0/

## [0.1.4] - 2023-01-28
- Fixed unnecessary decoding and allocations for bounded types, when the decoded length is greater than the allowed bound.
- Add `Hash` derivation (when `feature = "std"`) for bounded types.

## [0.1.3] - 2023-01-27
- Removed non-existent `bounded` mod reference. [#715](https://github.com/paritytech/parity-common/pull/715)

## [0.1.2] - 2023-01-27
- Ensured `bounded-collections` crate compiles under `no_std`. [#712](https://github.com/paritytech/parity-common/pull/712)

## [0.1.1] - 2023-01-26
- Made `alloc` public. [#711](https://github.com/paritytech/parity-common/pull/711)
- Removed a reference to `sp_core` in the comments. [#710](https://github.com/paritytech/parity-common/pull/710)

## [0.1.0] - 2023-01-26
- Wrote better description for `bounded-collections`. [#709](https://github.com/paritytech/parity-common/pull/709)
- Added `bounded-collections` crate. [#708](https://github.com/paritytech/parity-common/pull/708)
