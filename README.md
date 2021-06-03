# 実験について







## 実験結果の公表

この実験で得られた結果は，個人が特定されない状態にした上で，
[FIT 2021](https://www.ipsj.or.jp/event/fit/fit2021/) にて発表予定です．
また，追加実験を行い，他の会議に投稿するかもしれません．
いずれにせよ，個人が特定されることがないようにした上で発表します．

## 実験の目的

## 実験の手順

1. kaniのインストール．
2. [事前アンケート](https://forms.gle/43zfr7C7ZDuZyqBF9)への回答．
3. [練習問題](https://github.com/tamadalab/2021fit_masuda_experiment_example)の実施．
    * リポジトリの作成
    * kaniの有効化
    * 問題に取り組む
4. [課題1](https://github.com/tamadalab/2021fit_masuda_experiment1)の実施．
    * リポジトリの作成
    * kaniの有効化
    * 問題に取り組む
5. [課題2](https://github.com/tamadalab/2021fit_masuda_experiment2)の実施．
    * リポジトリの作成
    * kaniの有効化
    * 問題に取り組む
6. 必要ファイルの送付．
7. [事後アンケート](https://forms.gle/DiVQ9tRPCk1yDeiN8)への回答．
8. kaniのアンインストール．

### 1. kaniのインストール．

Git/GitHub 操作支援ツール kani をインストールします．
kaniは [github.com/tamadalab/kani](https://github.com/tamadalab/kani)にて開発されています．

#### brew によるインストール

以下の手順でインストールしてください．

```sh
brew tap tamadalab/brew
brew install kani
```

すでにインストール済みの場合は，`brew upgrade kani` でアップグレードしてください．

#### 初期設定

`echo $SHELL` を実行し，結果を確認してください．
`/bin/bash` の場合と `/bin/zsh`で行うべき処理が異なります．

* `/bin/bash`の場合
    * `echo 'eval "$(git kani init -)"' >> ~/.bashrc`
    * その後，`. ~/.bashrc` を実行し，設定を反映させましょう．
* `/bin/zsh`の場合
    * `echo 'eval "$(git kani init -)"' >> ~/.zshrc`
    * その後，`. ~/.zshrc` を実行し，設定を反映させましょう．


### 2. 事前アンケートへの回答．

[事前アンケート](https://forms.gle/43zfr7C7ZDuZyqBF9)に回答願います．
回答時間の目安は約5分です．

### 3. 練習問題の実施．

#### リポジトリの作成

[pre_experiment](https://classroom.github.com/a/HbeHGRpJ)にアクセスし，「Accept this assignment」をクリックしてください．
クリックすると初期設定中の画面に移ります．
しばらくしてから，ページを再読み込みすると，準備完了のページが表示されます．

![初期設定中](https://github.com/tamadalab/2021fit_masuda_experiments/raw/main/resources/pre_experiment/accepting.png)
![準備完了](https://github.com/tamadalab/2021fit_masuda_experiments/raw/main/resources/pre_experiment/ready_to_go.png)

準備完了画面に，作成されたリポジトリのURLが表示されています．
そのURLをクリックして作成されたリポジトリのページを表示してください．

#### kani の有効化

リポジトリを clone 後，
リポジトリのトップディレクトリに移動して，以下のコマンドを入力し kani を有効化してください．

```sh
# ローカル環境にリポジトリを clone しましょう．最後の ??? は実行した人のアカウントに読み替えてください．
git clone git@github.com/tmdlab2020TestTeam/pre_experiment-????.git 
# clone したリポジトリに移動します．最後の ??? は実行した人のアカウントに読み替えてください．
cd pre_experiment-???
# kani を有効化します．
kani init 
```

#### 問題に取り組む

作成されたリポジトリのページをみると，どのように問題に取り組めば良いかが示されています．
指示に従い，問題に取り組んでください．
作成されたリポジトリに push できて初めてそのステップが完了したことになる点に注意してください．

### 4. 課題1の実施．

#### リポジトリの作成

練習問題の時と同様に次の手順でリポジトリを作成し，リポジトリのページにアクセスしてください．

1. [experiment1](https://classroom.github.com/a/baAaupRY)にアクセスする．
2. 「Accept this assignment」をクリックする．
3. 準備完了ページを表示する（初期設定中の画面で再読み込みする）．
4. 作成されたリポジトリのURLをクリックする．

#### kani の有効化

リポジトリを clone 後，
リポジトリのトップディレクトリに移動して，以下のコマンドを入力し kani を有効化してください．

```sh
git clone git@github.com/tmdlab2020TestTeam/experiment1-????.git 
cd experiment1-???
kani init 
```

#### 問題に取り組む

作成されたリポジトリのページをみると，どのように問題に取り組めば良いかが示されています．
指示に従い，問題に取り組んでください．
作成されたリポジトリに push できて初めてそのステップが完了したことになる点に注意してください．


### 5. 課題2の実施．

#### リポジトリの作成

練習問題の時と同様に次の手順でリポジトリを作成し，リポジトリのページにアクセスしてください．

1. [experiment2](https://classroom.github.com/a/fJCx98MN)にアクセスする．
2. 「Accept this assignment」をクリックする．
3. 準備完了ページを表示する（初期設定中の画面で再読み込みする）．
4. 作成されたリポジトリのURLをクリックする．

#### kani の有効化

リポジトリを clone 後，
リポジトリのトップディレクトリに移動して，以下のコマンドを入力し kani を有効化してください．

```sh
git clone git@github.com/tmdlab2020TestTeam/experiment2-????.git 
cd experiment2-???
kani init 
```

#### 問題に取り組む

作成されたリポジトリのページをみると，どのように問題に取り組めば良いかが示されています．
指示に従い，問題に取り組んでください．
作成されたリポジトリに push できて初めてそのステップが完了したことになる点に注意してください．

### 6. 必要ファイルの送付

各プロジェクトの `.kani/kani.sqlite` を[Google Drive](https://drive.google.com/drive/folders/1WUKMcC6sM6QQz-wb9NJmugFvpW3mvAHu?usp=sharing)の自分の名前のフォルダに3つの `kani.sqlite`を置いてください．
その際，それぞれを `example.sqlite`，`experiment1.sqlite`，`experiment2.sqlite`に名前を変更してください．

### 7. 事後アンケートへの回答．

[事後アンケート](https://forms.gle/DiVQ9tRPCk1yDeiN8)に回答願います．
回答時間の目安は約5分です．

### 8. kani のアンインストール

今後，`kani`が不要であれば，以下のコマンドでアンインストールしてください．

```sh
brew uninstall kani
```

以上で実験は終了です．
ご協力ありがとうございました．
