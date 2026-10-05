<!-- tyhp-readme:start -->
# tyhpdef/illuminate-session

Tyhp type definitions for `illuminate/session` `13.32.0`.

```bash
composer require --dev tyhpdef/illuminate-session:13.32.0
```

This is a metapackage. Composer also installs `tyhpdef/illuminate-session-impl` (type files).
Require **this** name, not `tyhpdef/illuminate-session-impl`.

See https://tyhplang.com.

## Maintain `illuminate/session`? Ship the types yourself

If you are a Packagist maintainer of `illuminate/session`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/illuminate-session-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `illuminate/session` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/illuminate-session": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `illuminate/session` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `illuminate/session` with a real constraint,
   `"replace": { "tyhpdef/illuminate-session": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `illuminate/session` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/illuminate-session` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
