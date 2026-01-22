# helix-config
## Helix编辑器相关配置

1. 将config.toml和language.toml放到`~/.config/helix`中
2. clang-format放置到`~/.clang-format`
## 常用LSP支持
1. cargo安装部分
```bash
cargo install neocmakelsp asm-lsp
rustup component add rust-analyzer
```
2. pipx安装部分
```bash
pipx install ruff jedi-language-server python-lsp-server 
```
3. npm安装部分
```bash
sudo npm install -g vscode-langservers-extracted yaml-language-server typescript-language-server bash-language-server @imc-trading/svlangserver
```
4. 手动安装部分
- superhtml: https://github.com/kristoff-it/superhtml/releases/tag/v0.6.2
- lua-language-server: https://github.com/LuaLS/lua-language-server/releases/tag/3.17.1
- taplo: https://github.com/tamasfe/taplo/releases/tag/0.10.0
- tombi: github.com/tombi-toml/tombi/releases/tag/v0.7.22
- marksman：https://github.com/artempyanykh/marksman/releases/tag/2025-12-13
- markdown-oxide：https://github.com/Feel-ix-343/markdown-oxide/releases/tag/v0.25.10
