# pyctrl2
『Pythonによる制御工学入門（改訂２版）』のサポート

Binderの仮想環境でサンプルコードを実行できます（ただし，slycotをimportする関数は使えません）

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/373yuki/pyctrl2/main)

## Pythonコード
書籍の中に記載したPythonコードや補足のPythonコードです．
各章ごとにファイルを分けています．

Jupyter Notebook 形式（ipynb形式）となっていますので，ダウンロード後，JupyterNotebook上にアップロードして利用してください．

## Pythonコード実行に必要なもの
- Python 3.6 以降
- Matplotlib
- NumPy
- SciPy
- SymPy
- JupyterNotebook (JupyterLab)
- Slycot
- Control

## Juliaコード
書籍の中に記載したPythonコードをJulia用に書き換えました．ただし，数式処理やロバスト制御の部分など一部は未実装です．

## Juliaコード実行に必要なもの
- Julia 1.10 
- IJuia
- ControlSystems ()
- Plots
- LinearAlgebra
- DifferentialEquations
- Symbolics

## MATLABコード
書籍の中に記載したPythonコードをMATLAB用に書き換えました．PythonとMATLABの親和性の高さがわかります．
ライブスクリプト形式（mlx形式）となっています．plot_setとbodeplot_setも同じフォルダに入れてください．

## 書籍のサポートページ
https://y373.sakura.ne.jp/minami/pyctrl
