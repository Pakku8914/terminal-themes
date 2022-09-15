ubuntuにoh-my-poshを適用する方法

## 1
- sudo apt-get install build-essential procps curl file git

## 2
- 公式サイトからコマンドをコピー

## 3
- echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"' >> /home/aiuser/.profile

## 4
- eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"

## 5
- sudo apt-get install build-essential

## 6
- brew install gcc

## 7
- brew --version

## 8
- brew install jandedobbeleer/oh-my-posh/oh-my-posh

## 9
- brew update && brew upgrade oh-my-posh

## 10
- cd $(brew --prefix oh-my-posh)

## 11
- cd themes

## 12
- cp -p 好きなテーマ.omp.json ~/

## 13
- eval "$(oh-my-posh --init --shell bash --config ~/好きなテーマ.omp.json)"
