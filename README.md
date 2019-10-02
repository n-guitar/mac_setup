# mac_setup

## 前提条件

### Homebrewインストール
※homebrew：https://brew.sh/index_ja<br>
※enter kye/passwordが求められる
```bash
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

$ 
```

### ansible、gitインストール
```bash
$ brew install ansible
$ brew install git
```

### gitリポジトリクローン
※注意：Private Repository
```bash
$ mkdir ~/github
$ cd ~/github
$ git clone https://github.com/n-guitar/mac_setup.git
```