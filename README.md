# Terminal [ohmyposh](https://ohmyposh.dev/docs/)
### 1. install [nerd font](https://www.nerdfonts.com/font-downloads) *or*  [meslo LGM NF (recommend)](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/Meslo.zip)

### 2. install ohmyposh themes
```
 winget install JanDeDobbeleer.OhMyPosh -s winget
```
### 3. run the following command to open VS code
```
code $profile
```
### 4. past the script
```
 oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH\jandedobbeleer.omp.json"
```
### 5. run the following command 
```
 Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
```
*or*
```
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Bypass -Force
```
### 6. add vs code setting
```  
"terminal.integrated.fontFamily": "MesloLGS NF"
```
</br>
</br>

# Flutter [ohmyposh](https://flutter.dev/)



