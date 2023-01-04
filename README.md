# Nvim-Config
This is my personal nvim configuration

<a href="#--------">
<img alt="" src="https://i.imgur.com/oU81eWC.png">
</a>

> **Clone Nvim-Config**
```sh 
git clone https://github.com/AnthonyFl27/Nvim-Config.git
```
> **Copy config**
```sh
cd Nvim-Config/
cp -r nvim* ~/.config/     
```
> **Install vim-plug and coc dependencies**
```sh 
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
       
curl -sL install-node.vercel.app/lts | bash
```
## Details coc extensions
- **Extensions diagnostic** --- [coc-diagnostic](https://github.com/iamcco/coc-diagnostic)
- **Python extension** --- [coc-python](https://github.com/neoclide/coc-python)
- **Html extension** --- [coc-html](https://github.com/neoclide/coc-html)
- **Highlight extension** --- [coc-highlight](https://github.com/neoclide/coc-highlight)
- **tsserver extension** --- [coc-tsserver](https://github.com/neoclide/coc-tsserver)
- **Json extension** --- [coc-json](https://github.com/neoclide/coc-json)

## Keybindings
| Keys                                 | Action                         |
| ------------------------------------ | ------------------------------ |
| <kbd>esc + space + w</kbd>                   | Save the file            |
| <kbd>esc + space + q</kbd>                   | Exit the file              |
| <kbd>esc + space + nt</kbd>           | Launch Nerdtreefinder                |
| <kbd>esc + space + t</kbd>           | New tab in Neovim                |
           
