# ddev-opencode <!-- omit in toc -->

## Opencode

[Opencode](https://opencode.ai/) is installed inside the DDEV container and is accesible using
`ddev opencode`. When you first run, you will be prompted to do this
interactively. Your configuration will be stored in `.ddev/opencode.jsonc`
and `.ddev/.opencode/`, and will be persisted across restarts.

You can copy in an existing `.ddev/opencode.jsonc`, for example if you want to
use an existing key, or allowed functions etc.

## Acknowledgement

> This is a fork from [https://github.com/FreelyGive/ddev-claude-code](ddev-claude-code). Thanks to [@FreelyGive](https://github.com/FreelyGive) for providing this project repo as a template for integrating CLI coding agents into ddev.
