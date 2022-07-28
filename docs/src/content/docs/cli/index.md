---
title: CLI
section: 6
redirect_from:
  - /cli/
  - /cli
---

# CLI

You can get help on tap's command line interface by running `tap -h`.

Any configuration options may be set on the command line, in your
`package.json` file in a `tap` section, or in a YAML-formatted `.taprc` file in
the root of your project.  See [configuring tap](/docs/configuring/) for more
information.

```
internal/modules/cjs/loader.js:905
  throw err;
  ^

Error: Cannot find module 'signal-exit'
Require stack:
- /Users/gsabirovsky/WebstormProjects/node-tap/bin/run.js
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:902:15)
    at Function.Module._load (internal/modules/cjs/loader.js:746:27)
    at Module.require (internal/modules/cjs/loader.js:974:19)
    at require (internal/modules/cjs/helpers.js:101:18)
    at Object.<anonymous> (/Users/gsabirovsky/WebstormProjects/node-tap/bin/run.js:9:20)
    at Module._compile (internal/modules/cjs/loader.js:1085:14)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1114:10)
    at Module.load (internal/modules/cjs/loader.js:950:32)
    at Function.Module._load (internal/modules/cjs/loader.js:790:12)
    at Function.executeUserEntryPoint [as runMain] (internal/modules/run_main.js:75:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [ '/Users/gsabirovsky/WebstormProjects/node-tap/bin/run.js' ]
}

```
