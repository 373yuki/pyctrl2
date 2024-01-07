# pyctrl2
『Pythonによる制御工学入門（改訂２版）』のサポート

Binderの仮想環境でサンプルコードを実行できます（ただし，slycotをimportする関数は使えません）

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/373yuki/pyctrl2/main)

## Pythonコード
書籍の中に記載したPythonコードや補足のPythonコードです．
各章ごとにファイルを分けています．

Jupyter Notebook 形式（ipynb形式）となっていますので，ダウンロード後，JupyterNotebook上にアップロードして利用してください．

## Pythonコード実行に必要なものs
- Python 3.6 以降
- Matplotlib
- NumPy
- SciPy
- SymPy
- JupyterNotebook (JupyterLab)
- Slycot
- Control

## Juliaコード
書籍の中に記載したPythonコードをJulia用に書き換えました．ただし，数式処理や最適制御（モデル予測制御）の部分は未実装です．

## Juliaコード実行に必要なもの
- Julia 1.10
- IJuia
- ControlSystems
- RobustAndOptimalControl
- Plots
- LinearAlgebra
- DifferentialEquations
- Symbolics

## MATLABコード
書籍の中に記載したPythonコードをMATLAB用に書き換えました．ただし，最適制御（モデル予測制御）の部分は未実装です．
ライブスクリプト形式（mlx形式）となっています．plot_setとbodeplot_setも同じフォルダに入れてください．
MATLAB Drive（5GBまで無料）にファイルをコピーしてから，MATLAB Mobile（無料）を利用すれば，MATLABライセンス不要でコードを実行することができます．

## 書籍のサポートページ
https://y373.sakura.ne.jp/minami/pyctrl
