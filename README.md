# How to use
[ohmyposh.dev/docs](https://ohmyposh.dev/docs)
[oh-my-posh github repo](https://github.com/jandedobbeleer/oh-my-posh)

## Bash/wsl
1. Install Oh-my-posh: [Install on Linux](https://ohmyposh.dev/docs/installation/linux)
2. Get the theme and put it in .config/oh-my-posh/
3. Add the following line to .bashrc: 

`eval $(oh-my-posh init bash --config '~/.config/oh-my-posh/onehalf.minimal.omp.json')`

## Powershell
1. Install Oh-my-posh on windows: [Install on windows](https://ohmyposh.dev/docs/installation/windows)
2. Get the theme and put it somewhere reasonable. For example `C:\Users\USERNAME\config\oh-my-posh`
3. Add the following line to `$PROFILE`

`oh-my-posh init pwsh --config 'path\to\omp.json' | Invoke-Expression`

$PROFILE points to the pshell setup file, something like: `C:\Users\USERNAME\Documents\WindowsPowerShell\Microsoft.PowerShell_profile.ps1`
