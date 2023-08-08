# My Local Mac

나만의 로컬 환경 설정 리스트

- <i>설정 및 소프트웨어 자유롭게 추천해주세요</i>

<br/>
<img src="https://media.giphy.com/media/12bVDtXPOzYwda/giphy.gif" alt="Coder GIF">



## Mac

- 계정 이름, 비밀번호 바꾸기
- Touch ID 사용 활성화
- Display 핫 코너 설정
- 트랙패드 ‘스크롤방향 자연스럽게’ 비활성화
- Dock
  - Dock 방향 왼쪽 설정
  - Dock 확대 활성화
  - 자동으로 Dock 가리기 활성화
  - Dock에서 최근에 사용한 응용프로그램 보기 비활성화
- 일반
  - 화면모드 ‘다크모드’ 설정
  - 기본 브라우저 Chrome 설정
- 계정
  - 캘린더, 메일 동기화
- 배터리 퍼센트 보기



<br/>

## Software 설치

- InteliJ toolbox, IDEA, Datagrip
  - keymap ‘rename’ to option+R 추가
  - Plugins 설치 (Lombok, …)
  - Theme - High Contrast (고대비) 설정
- Iterm
  - Oh-my-zsh 설치
    - `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
  - Autojump, zsh-autosuggestions, zsh-syntax-highlighting, zsh-completions, oh-my-zsh 설치
    - ```bash
      brew install autojump
      
      git clone https://github.com/zsh-users/zsh-completions ${ZSH_CUSTOM:=~/.oh-my-zsh/custom}/plugins/zsh-completions
      
      git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
      
      git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
      ```

      ```
      // .zshrc
      
      plugins=(
          [Plugins...]

          autojump
          zsh-syntax-highlighting
          zsh-completions
          zsh-autosuggestions
      )
      
      ```
  - ZSH_THEME을 agnoster로 설정 (또는 POWERLEVEL9K 사용)
  - JetbraninsMono Nerd font 또는 D2-coding 글꼴 설치 및 적용
  - Reuse previous session’s directory 설정

- Typora / Sublime Text / Notion
- Chrome
- VSCode
  - Git graph
  - Install ‘code’ command in PATH
- Kakaotalk / Slack / Discord
- Magnet
- Postman
- Zoom
- Amphetamine
- Keka
- FileZilla
- Clipboard tool (App Store)
- Optional
  - Step two (OTP)
  - Bitwarden
  - YT music

<br/>

## CLI Alias/Function 추가

- kubectl (k, kaf, kga, kns)
- `hosts` update function
- java/pod log dump functions


<br/>

## 개발

- [brew](https://brew.sh/index_ko)
- [sdkman](https://sdkman.io/install)
- Java, python, go, node
- Nginx
- Npm, yarn
- docker (only my laptop) or podman, colima
- Redis (+ Medis)
- ngrok
- kubectl, minikube, helm
  - kubens, kubeseal, kubectx


