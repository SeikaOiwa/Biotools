# Biotools
遺伝子解析ツール🧰

# 1. 概要

標準的な遺伝子解析ツールをstreamlitを用いてwebアプリ化

![概要](./File/main.png)

# 2. コンテンツ

(1) Local_blast

    blast検索実行ツール

(2) GeneExtract

    ゲノムデータから、遺伝子番号や染色体位置情報に該当する配列を抽出するツール

# 3. 環境構築

(1) モジュールインストール

`conda create -n biotools python`

`conda activate biotools`

`conda install biopython`

`conda install -c bioconda blast`

`pip install openpyxl`

`pip install streamlit`

(2) gitから解析フォルダダウンロード

`git clone https://github.com/SeikaOiwa/Biotools.git`

# 4. 起動方法

(1) git cloneでダウンロードした`Biotools`(フォルダ)に移動

`cd /**/**/Biotools`

(2) conda環境に入り、streamlitを動かす

`conda activate biotools`

`streamlit run st_analysis_tool.py`

(3) ローカルホスト上に下図のwebアプリが表示される。

![初期画面](./File/monitor.png)