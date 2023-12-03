# dotfiles

## Tools

| Tool                              | Purpose                       | Why?                                                  |
|-----------------------------------|-------------------------------|-------------------------------------------------------|
| `zsh`                             | ZSH Shell                     |                                                       |
| [`nix`](https://nixos.org/)       | Package Manager               | Nix seems better for system level packages (global)   |
| [`asdf`](https://asdf-vm.com/)    | Package Manager               | asdf better at controlling packages at runtime level  |
| `chezmoi`                         | dotfiles manager              | Seems better than `yadm`                              |
| `gh`                              | GitHub CLI                    |                                                       |
| `wslu`                            | WSL Utilities                 | Dependency for `wslview` (URL Forwarding to Windows)  |



### `wslview`
https://manpages.ubuntu.com/manpages/focal/en/man1/wslview.1.html  
Add to `.zshrc`:  
    `export BROWSER="wslview %s"`  





## Things you generally wanna do each time
* SSH Key
* GPG Key
* Deploy dotfiles
