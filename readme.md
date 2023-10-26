卒論 with tex
===

# Usage.

## 自分の作業ブランチを作る

```
# その年のテンプレートがあるブランチへ
git checkout template/12fi

# 自分ブランチを切る
git checkout -b 12fi/hiro

# テンプレートファイルコピー
cp template.tex hiro_thesis.tex
```

## 今年のテンプレートを作る

```
# テンプレートブランチへ
git checkout templates

# 今年向けに編集してコミット
git commit

# ブランチ作成
git checkout -b template/12fi

2023/10/26
GitHubのテンプレートにしたため、上記の作業は不要？
梗概用テンプレート2022年のページ↓
https://www.mlab.im.dendai.ac.jp/~assist/thesis/2022/


2023/01/04
空白のテンプレート作成しました
変だったらすみません
appendix:付録用フォルダ
images:画像用フォルダ

コンパイラーをLatexに変更、main_thesis.texをmain　documentに設定

# Graduation-thesis-template2023
