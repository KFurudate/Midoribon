# Midoribon

<a target="_blank" href="https://www.amazon.co.jp/gp/product/400006973X/ref=as_li_tl?ie=UTF8&camp=247&creative=1211&creativeASIN=400006973X&linkCode=as2&tag=reaesjapan05-22&linkId=193d5bb35db89dc42f382607f2b59a4c">データ解析のための統計モデリング入門 一般化線形モデル・階層ベイズモデル・MCMC (確率と情報の科学)</a><img src="//ir-jp.amazon-adsystem.com/e/ir?t=reaesjapan05-22&l=am2&o=9&a=400006973X" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />

<img width="157" alt="Screen Shot 2020-10-02 at 23 49 26" src="https://user-images.githubusercontent.com/50528980/94983619-298f4880-050a-11eb-8359-4144bed5b4cd.png">

久保拓弥先生(著者)のページ

https://kuboweb.github.io/-kubo/ce/IwanamiBook.html

## 目次
- 第1章   データを理解するために統計モデルを作る
- [第2章   確率分布と統計モデルの最尤推定](/chap2.ipynb)
- [第3章   一般線形モデル(GLM) -ポアソン回帰-](/chap3.ipynb)
- 第4章   GLMのモデル選択 -AICとモデルの予測の良さ-
- 第5章   GLMの尤度比検定と検定の非対称性
- 第6章   GLMの応用範囲をひろげる  -ロジスティック回帰など-
- 第7章   一般線形混合モデル(GLMM) -個体差のモデリング-
- 第8章   マルコフ連鎖モンテカルロ(MCMC)法とベイズ統計モデル
- 第9章   GLMのベイズモデル化と事後分布の推定
- 第10章  階層ベイズモデル - GLMMのベイズモデル化ー
- 第11章  空間構造のある階層ベイズモデル

## 第1章 データを理解するために統計モデルを作る

- 統計モデルとは、

  観測されたデータの解析に伴う情報の損失を抑えながら、現象を要約・整理し、未観測の挙動を予測するために作り上げられる数式。
 
-　説明変数と応答変数とは、

  説明変数（独立変数）は、「何かの原因となっている変数」。
  
  応答変数（目的変数）は、「その原因を受けて発生した結果の変数」。

## 第2章 確率分布と統計モデルの最尤推定

- 確率分布とは、

  確率変数（random variable)の値とそれが出現する確率を対応させ、データに見られるばらつきを表現するもの。確率分布は、パラメーターの値に依存して分布のカタチが変わる。

- 最尤推定とは、

  得られたデータに対するあてはまりの良さ（尤度）を最大にするようなパラメーターの値を探そうとするパラメーター推定方法。対数尤度を用いる。

- ポアソン分布とは、
  
  起こる確率が常に一定である出来事が、一定期間内に、何回発生するかをあらわす離散型確率分布（平均=分散=λ）。

## 第3章   一般線形モデル(GLM) -ポアソン回帰-

- 一般線形モデル(Generalized linear model:GLM)とは、

  誤差の推定量をある分布と仮定すると、足し算の数式であらわされるモデル（線形モデル）。
