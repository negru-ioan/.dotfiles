https://ohmyposh.dev/

run: Get-PoshThemes

then choose a theme:
oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH/(**THEME_NAME**).omp.json" | Invoke-Expression

in $PROFILE:
oh-my-posh init pwsh --config 'C:\Users\dev\AppData\Local\Programs\oh-my-posh\themes\kali.omp.json' | Invoke-Expression


[**docs**](https://ohmyposh.dev/docs/installation/customize)