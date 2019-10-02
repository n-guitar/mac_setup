# mac_setup

##  動作確認済み
```bash
$ sw_vers
ProductName:	Mac OS X
ProductVersion:	10.14.5
BuildVersion:	18F132
```

## 前提条件

### Homebrewインストール
※homebrew：https://brew.sh/index_ja<br>
※enter kye/passwordが求められる
```bash
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

$ brew -v
Homebrew 2.1.11
Homebrew/homebrew-core (git revision 54e9; last commit 2019-10-02)

```

### ansible、gitインストール
```bash
$ brew install ansible
$ brew install git

$ ansible --version
ansible 2.8.5

$  git --version
git version 2.23.0
```

### gitリポジトリクローン
※注意：Private Repository
```bash
$ mkdir ~/github
$ cd ~/github
$ git clone https://github.com/n-guitar/mac_setup.git
```