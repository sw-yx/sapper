# @ssgjs/sapper

This is a community fork of [Sapper](https://sapper.svelte.dev) focused on static export needs.

It includes:

- entry-only optional param for export https://github.com/sveltejs/sapper/pull/856
- Handle i/o backpressure with sapper export https://github.com/sveltejs/sapper/pull/869
- (partially merged) Export filter urls by regex https://github.com/sveltejs/sapper/pull/859
- fallback rollup.config.js https://github.com/sw-yx/sapper/pull/2 and https://github.com/sw-yx/sapper/pull/1
  - `svelte-preprocess` in the fallback rollup https://github.com/sw-yx/sapper/pull/10/
- fallback client/server/template https://github.com/sw-yx/sapper/pull/3
- this fix for the JSON race condition issue https://github.com/nealalpert/sapper/commit/3247d504cb4c7cf3f71e57614697e2b559b40138
- a `this.ssgData` wrapper over `this.fetch` in the preload context https://github.com/sw-yx/sapper/pull/9

We maintain this fork because we feel pain points around sapper static export, and still have hope it is merged upstream one day.
