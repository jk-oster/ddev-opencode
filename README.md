# ddev-opencode <!-- omit in toc -->

## Opencode

[Opencode](https://opencode.ai/) is installed inside the DDEV container and is accesible using
`ddev opencode`. Your configuration will be stored in `.ddev/.opencode` (symlinked to `~/.config/opencode` in the web container), and will be persisted across restarts.

You can copy in an existing `opencode.jsonc`, for example if you want to use an existing configuration, mcps, permissions,...

## Installation
```sh
ddev add-on get jk-oster/ddev-opencode
```

## Usage

### Laravel Boost

Enable the pre-configured Laravel Boost MCP server in `.ddev/.opencode/opencode.jsonc`

## Acknowledgement

> This is a fork from [ddev-claude-code](https://github.com/FreelyGive/ddev-claude-code). Thanks to [@FreelyGive](https://github.com/FreelyGive) for providing this project repo as a template for integrating CLI coding agents as [addon](https://addons.ddev.com/) into [ddev](https://ddev.com/).
