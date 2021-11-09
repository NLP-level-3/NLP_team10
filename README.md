# 제공받은 서버에 zsh 설치하는 방법

## 0. 파일을 서버에 업로드
`zshrc.back`과 `zsh_install.sh`파일을 `/opt/ml`에 업로드

<br>

## 1. 폰트설정!

### [vscode](https://velog.io/@kangko05/Vscode-powerlevel10k)

`setting -> terminal.integrated.fontFamily -> MesloLGS NF`

### pycharm

`shift*2 -> 글꼴 -> MesloLGS NF`

### jupyter lab

`setting -> Advanced Setings Editor -> Terminal -> User Preferences -> "fontFamily": "MesloLGS NF" 추가`

<br>

## 2. install

zsh-autosuggestions 과 zsh-syntax-highlighting이 적용됩니다.

```bash
$ bash zsh_install.sh
```



# 😀 p10k 스타일 재설정

```bash
$ p10k configure
```
