python_visual_recognition_tutorials
===================================

DERiVEメルマガのシリーズ「scikit-learnとscikit-imageで作る○○」のipython notebook集です。メルマガでは、pythonを用いた画像認識(visual recognition)の作り方をシリーズを組んで解説記事を書いており、このレポジトリではそこで紹介したipython notebookを共有しています。

スクリプトの解説はメルマガにのみ書いていますので、読者の方はその解説を読んだ上で、実際に動くipython notebookのスクリプトにより、実践的な画像認識プログラムの作り方を学んで頂けます。

### python科学計算環境のインストール

pythonの実行環境の準備についてです。Windows環境の方は、[ブログの記事](http://derivecv.tumblr.com/post/31977310381)でも紹介したことがある [python(x,y)](https://code.google.com/p/pythonxy/)をインストールして頂くと、実行に必要なライブラリ(ipython,numpy,matplotlib,scikit-learn,scikit-image)が一括でインストールされるので楽です。また、私がMac OSXにて普段使用している [Anaconda] (https://store.continuum.io/cshop/anaconda/) をインストールして頂くのもオススメです。


### 「scikit-learnとscikit-imageで作る人検出」
vol.11からスタートした「scikit-learnとscikit-imageで作る人検出」の、各回のipython notebook集です。vol.13以降、記事と連動したipython notebookを一つ新たに追加しています。

notebook一覧:

- [01_train_from_normalized_images.ipynb](http://nbviewer.ipython.org/github/payashim/python_visual_recognition_tutorials/blob/master/01_pedestrian_detector/notebooks/01_train_from_normalized_images.ipynb) ：　vol.13「その3. 学習フェーズのスクリプトtrain.pyの作成 前編」
- [02_visalize_pos_neg_HOG.ipynb](http://nbviewer.ipython.org/github/payashim/python_visual_recognition_tutorials/blob/master/01_pedestrian_detector/notebooks/02_visalize_pos_neg_HOG.ipynb) ：　vol.14「その4. 学習フェーズのスクリプトtrain.pyの作成 後編」
- [03_train.py.ipynb](http://nbviewer.ipython.org/github/payashim/python_visual_recognition_tutorials/blob/master/01_pedestrian_detector/notebooks/03_train.py.ipynb) ：　vol.14「その4. 学習フェーズのスクリプトtrain.pyの作成 後編」

- [04_likelihood_map_with_sliding_window.ipynb](http://nbviewer.ipython.org/github/payashim/python_visual_recognition_tutorials/blob/master/01_pedestrian_detector/notebooks/04_likelihood_map_with_sliding_window.ipynb) ：　vol.15「その5. テストフェーズのスクリプトtest.pyの作成 前編」