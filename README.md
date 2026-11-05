<h1 align="center">tasq.nvim</h1>

<h1 align="center">
<a href='#'><img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/palette/macchiato.png" width="600px"/></a>
  <br> <br>
  <div>
    <a href="https://github.com/IogaMaster/tasq.nvim/issues">
        <img src="https://img.shields.io/github/issues/IogaMaster/tasq.nvim?color=fab387&labelColor=303446&style=for-the-badge">
    </a>
    <a href="https://github.com/IogaMaster/tasq.nvim/stargazers">
        <img src="https://img.shields.io/github/stars/IogaMaster/tasq.nvim?color=ca9ee6&labelColor=303446&style=for-the-badge">
    </a>
    <a href="https://github.com/IogaMaster/tasq.nvim">
        <img src="https://img.shields.io/github/repo-size/IogaMaster/tasq.nvim?color=ea999c&labelColor=303446&style=for-the-badge">
    </a>
    <a href="https://github.com/IogaMaster/tasq.nvim/blob/main/.github/LICENCE">
        <img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=ca9ee6&colorA=313244&colorB=cba6f7"/>
    </a>
    <br>
    </div>
        <img href="https://builtwithnix.org" src="https://builtwithnix.org/badge.svg"/>
   </h1>
   <br>

`tasq.nvim` is a window wrapper around the [tasq](https://github.com/webstonehq/tasq/) tui application.
This plugin is like [lazygit.nvim](https://github.com/kdheepak/lazygit.nvim), but for tasq.

## 📦 Installation and Usage

Include the repo with your favorite package manager.

After that setup will be automatically called, then you can either call the `:Tasq` command.
Or run `require("tasq").tasq()`.

## Config

```lua
require('tasq').setup {
	create_todo_file = true,
	width_ratio = 0.95,
	height_ratio = 0.80,
}
```


## ❤️ Contributing

Contributions are whole-heartedly welcome! Please feel free to suggest new features,
implement additional builders, helpers, or generally assist if you'd like. We'd be happy to have you.
There's more information in [CONTRIBUTING.md](CONTRIBUTING.md).

## 📜 License

Licensed under the MIT license ([LICENSE](LICENSE) or <https://opensource.org/licenses/MIT>).
Unless you explicitly state otherwise, any contribution intentionally
submitted for inclusion in this project by you, shall be licensed as above, without any additional terms or conditions.

