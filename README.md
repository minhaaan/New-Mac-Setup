# README.md

## Install homebrew

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

## brew download

```bash
brew install \
    nvm \
    git \
    wget \
    curl \
    tree \
    zsh \
    git-lfs \
    zsh-autosuggestions \
    zsh-syntax-highlighting \
    powerlevel10k \
    swift-format \
    swiftlint \
    mise \
    rbenv
```

## cask download

```bash
brew install --cask \
    iterm2 \
    github \
    cursor \
    visual-studio-code \
    obsidian \
    notion \
    discord \
    appcleaner \
    rectangle \
    karabiner-elements \
    stats \
    raycast \
    fork \
    font-jetbrains-mono \
    font-google-sans-code \
    font-d2coding \
    slack \
    proxyman

```

## Manual Download

- [Xcodes](https://github.com/XcodesOrg/XcodesApp)
- [ScreenFloat](https://apps.apple.com/kr/app/screenfloat-pro-screen-capture/id414528154?mt=12ScreenFloat—Pro)
- [Amphetamine](https://apps.apple.com/kr/app/amphetamine/id937984704?mt=12)
- [`Amazon` Q](https://docs.aws.amazon.com/ko_kr/amazonq/latest/qdeveloper-ug/command-line-installing.html)
- [KakaoTalk](https://apps.apple.com/kr/app/kakaotalk/id869223134?mt=12KakaoTalk)
- Tuist: `mise install tuist`, `mise use tuist@x.y.z`


## Node.js & NVM 설정
```bash
# NVM을 사용한 Node.js 설치
nvm install node
nvm install --lts
nvm use --lts

# 전역 패키지 설치
npm install -g yarn pnpm typescript @types/node @anthropic-ai/claude-code @google/gemini-cli
```

## Ruby

```bash
# list latest stable versions:
rbenv install -l
# install a Ruby version:
rbenv install 3.1.2
# set the default Ruby version for this machine
rbenv global 3.1.2
```

## zsh

```bash
$ source $(brew --prefix)/share/zsh-autosuggestions/zsh-autosuggestions.zsh
$ echo "source $(brew --prefix)/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc

plugins=( 
    zsh-autosuggestions
)

alias
TODO
```


## Git Settings

```bash
git config --global user.name "minhaaan"
git config --global user.email "chmh0411@gmail.com"
```

---

*마지막 업데이트: $(date)*