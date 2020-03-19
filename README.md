binder, Turn a Git repository into a collection of interactive notebooks
================

　本リポジトリは [binder example](https://github.com/binder-examples/r)
からフォークしたものです。フォークしたファイルのライセンスはフォーク元のライセンスにしたがいます。本リポジトリで追加したファイルのライセンスは
CC 4.0 BY-NC-SA となります。

　

# binder

　[binder <i class="fa fa-external-link"></i>](https://mybinder.org/) は
GitHub のリポジトリから Jupyter Notebook や RStudio Server
などのコード実行環境を構築できるクラウドサービスです。  
　binder を利用することで環境構築の手間が省けるだけでなく環境の再現性が確保できるのが大きなメリットです。ただし、構築される環境は
**ワンタイム** な環境ですので永続的に利用することはできません。

　

## Try binder

　まずは試してみましょう！

[![binder](https://mybinder.org/badge_logo.svg) Try to lunch
Jupyter](https://mybinder.org/v2/gh/k-metrics/rocker/master?filepath=index.ipynb)

[![binder](https://mybinder.org/badge_logo.svg) Try to lunch RStudio
Server](https://mybinder.org/v2/gh/k-metrics/rocker/master?urlpath=rstudio)

　

## R/RStduio環境

　本リポジトリでは日本語フォントとロケールが設定された Docker イメージベースで binder
環境を構築しますので、プロット（図）で日本語が文字化けすることはありません。

　

-----

Enjoy\!
