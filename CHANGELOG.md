# Changelog

## 1.1.1 - 2016-09-17

- Fix localhosts passed through. Backport https://github.com/assaf/node-replay/commit/257d449f3f43fc01347efbd764b0caec03a5db79.

## 1.1.0 - 2016-08-05

- Normalize request path during comparison.
- `NODE_RETELL_MODE` env variable was not taken into account.
- Finish re-branding to **node-retell**.

## 1.0.0 - 2016-07-28

Fork [node-replay](https://www.npmjs.com/package/replay) to node-retell.
See https://github.com/assaf/node-replay/blob/master/CHANGELOG.md for original list of changes.

### Changed

- Rename to node-retell.
- Drop support of Node.js<4.
- Update to babel 6.x.

### Added

- Record unzipped reply.
- Support for passing-through client cert and key.

## 
