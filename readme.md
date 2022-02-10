### 村上諒
- 電気通信大学大学院 情報理工学研究科 情報学専攻 博士課程
- JST次世代研究者挑戦的研究プログラム研究員
- 株式会社オープンストリーム 技術創発推進室

## 目次
- [職務要約](#職務要約)
- [スキルセット](#スキルセット)
  - [情報科学のスキル](#情報科学のスキル)
  - [材料開発のスキル](#材料開発のスキル)
- [研究経歴](#研究経歴)
  - [光電子分光スペクトルにおける自動解析手法の開発](#光電子分光スペクトルにおける自動解析手法の開発)
  - [視覚認知に基づく画像統計量を用いた磁区形成パラメータの逆推定](#視覚認知に基づく画像統計量を用いた磁区形成パラメータの逆推定)
  - [その他の研究課題](#その他の研究課題)
- [業務経歴](#業務経歴)
  - [非線形時系列予測による異常検知システム開発](#非線形時系列予測による異常検知システム開発)
  - [敵対的生成学習を用いた深層学習モデルの分散表現可視化](#敵対的生成学習を用いた深層学習モデルの分散表現可視化)
  - [アパレルECサイトにおけるクローリングシステムの開発](#アパレルecサイトにおけるクローリングシステムの開発)
- [研究活動に関する業績](#研究活動に関する業績)
  - [査読あり筆頭著者論文](#査読あり筆頭著者論文)
  - [査読あり共著著者論文](#査読あり共著著者論文)
  - [査読あり国際学会](#査読あり国際学会)
  - [査読あり国内筆頭発表](#査読あり国内筆頭発表)
  - [査読なし国内筆頭発表](#査読なし国内筆頭発表)
  - [受賞歴](#受賞歴)
  - [その他](#その他)
- [学業経歴](#学業経歴)
- [職務経歴](#職務経歴)
- [資格および免許](#資格および免許)

## 職務要約
物質・材料の計測データ解析において，情報科学技術を取り入れた新たな解析手法の研究開発を行ってきました．これらの研究開発は，物質・材料研究機構(NIMS)やSpring-8などの研究機関と共同で行い，開発した手法を実解析現場のユーザに利用していただく部分まで活動を行なっております．

## スキルセット
### 情報科学のスキル
- 勾配法や進化計算による最適解探索の独自実装
- ベイズ推定に向けた温度交換モンテカルロ法の実装
- 深層学習による画像処理（CNN, Style Transfer, GANなど）
- 材料画像におけるパターン構造解析の独自開発
- IoTセンサの時系列信号における異常検知手法の開発

### 材料開発のスキル
- 物理シミュレータ（イジングモデル＋拡散方程式）の利活用
- 走査型電子顕微鏡(SEM)や量子ビーム計測などの利用経験
- 光電子分光計測におけるイオンビームエッチングの利用経験

## 研究経歴
これまで従事した主担当の研究課題を示す．
### 光電子分光スペクトルにおける自動解析手法の開発
X線光電子分光(XPS)スペクトルの生成過程をモデリングし，電子状態に由来したピーク構造を逆推定する手法を開発した．これは，熟練した研究者が手動で行う解析手順を数理最適化問題に置き換え，解析手法を実現した．さらに，この手法はスパースモデリング技術を利用することにより，化合物種の自動同定も同時に行うことができる．これにより，化合物種と紐づけられたピーク構造を介した電子状態の自動的な直接推定が可能となり，解析のばらつきを70%軽減させることに成功した．開発した手法は，物質材料研究機構で運用する予定である（現在，試験運用中）．この手法は，C++を用いて実装した．

研究期間：2017年4月〜現在進行中

### 視覚認知に基づく画像統計量を用いた磁区形成パラメータの逆推定
本研究は，計測した磁区のダイナミクスパターンと類似したシミュレーション結果が得られる磁区形成パラメータを逆推定する手法の開発を目的とした．提案手法では，効率的なパラメータ探索を行うために，ガウス過程回帰に基づく実験計画法を採用した．また，磁区の時間発展パターンの類似度として，パターン構造を記述する画像統計量に注目した．本研究では，複数の磁区形成パラメータを同時かつ高精度に逆推定できることを示した．特に，提案手法は従来手法と比べて計算コストを90%軽減させることに成功した．

研究期間：2020年4月〜2022年2月

### その他の研究課題
- X線回折スペクトルにおける自動解析手法の開発｜NIMSとの共同研究，研究期間：2021年4月〜現在進行中
- ラウンドロビン・テストの計測データにおける定量分析｜SASJ XPS-WGとの共同研究，研究期間：2022年1月〜現在進行中

## 業務経歴
### 非線形時系列予測による異常検知システム開発
機械学習を用いた非線形時系列予測に基づく異常検知システム開発に主担当者として従事した．私は論文調査，解析手法の確立からソフトウェアを運用環境への配置する部分まで業務を行なった．この業務経験により，以下の知見や経験を得ることできた．
- 時系列データ解析や異常検知の知見・独自実装
- Docker・Kubernetesやクラウドサービスの利用経験
- GitHubを利用した共同プログラム開発
- Cassandraデータベースの利用経験
- マルチプロセスプログラムの実装

研究期間：2021年4月〜現在進行中

### 敵対的生成学習を用いた深層学習モデルの分散表現可視化
画像認識や画像生成などで著しい発展を遂げている深層学習のホワイトボックス化を目的とした．先行研究として，画像再構成の学習に敵対的生成ネットワーク(GAN)を用いた手法が提案されている．本研究では，先行研究の手法にStyle-Transferの知見を導入し，畳み込みニューラルネットワーク(CNN)の特徴抽出に関する特性と一貫するような再構成画像を得るようにアーキテクチャの改良を行った．この研究は，NTT研究所との共同研究である．この研究成果は，画像電子学会において受賞された．

研究期間：2020年6月〜2020年12月

### アパレルECサイトにおけるクローリングシステムの開発
クラウドソーシングサイトから業務委託の形式で依頼を受け，クローリングシステムの開発業務に従事した．このシステムは，アパレルECサイトの商品在庫や価格を監視し，データベースへの蓄積を行う．実装には，以下のツールを活用した．
- 開発言語　　　：Python
- スクレイピング：Selenium, BeautifulSoup
- データベース　：SQL(RDBMS)
- 定期実行　　　：Cron
- 環境構築　　　：Docker

## 研究活動に関する業績
### 査読あり筆頭著者論文
- R. Murakami et al., “Inverse estimation of parameters for the magnetic domain via dynamics matching using visual perceptive similarity”: *STAM-methods*, under peer review.
- R. Murakami et al., “Automatic estimation of unknown chemical components in a mixed material by XPS analysis using a genetic algorithm”: *STAM-methods*, under peer review.
- R. Murakami et al., “[Determination of common peak structure from multiple X-ray photo-electron spectroscopy data sets](https://www.tandfonline.com/doi/full/10.1080/27660400.2021.1957304)”: *STAM-methods* **1** (2021) 182−191.
- R. Murakami et al., “[Texture Analysis of Magnetic Domain Images Using Statistics Based on Human Visual Perception](https://journals.jps.jp/doi/full/10.7566/JPSJ.90.044705)”: *J. Phys. Soc. Jpn.* **90** (2021) 044705.
- R. Murakami et al., “[Development of multiple core-level XPS spectra decomposition method based on the Bayesian information criterion](https://doi.org/10.1016/j.elspec.2020.147003)”: *J. Electron Spectrosc. Relat. Phenom.* **245** (2020) 147003.
- R. Murakami et al., “[Efficient Removal of Noise-derived Components for Automatic XPS Spectral Decomposition Using Hierarchical Clustering](https://doi.org/10.1380/ejssnt.2020.201)”: *e-JSSNT*. **18** (2020) 201–207.
- R. Murakami et al., “[Background Estimation in X-ray Photoelectron Spectroscopy Data Using an Active Shirley Method with Automated Selection of the Analytical Range](https://doi.org/10.1380/ejssnt.2019.61)”: *e-JSSNT*. **17** (2019) 61–68.

### 査読あり共著著者論文
- S. Tsuji, R. Murakami et al., “Magnetic Domain Pattern Analysis for Anisotropy Using Wavelet Based Joint Texture Image Statistics”: *J. Phys. Soc. Jpn.*, under peer review.
- A. Machida, R. Murakami et al., “[Bayesian estimation for XPS spectral analysis at multiple core levels](https://www.tandfonline.com/doi/full/10.1080/27660400.2021.1943172)”: *STAM-methods* **1** (2021) 123–133.
- H. Shinotsuka, R. Murakami et al., “[Automated information compression of XPS spectrum using information criteria](https://doi.org/10.1016/j.elspec.2019.146903)”: *J. Electron Spectrosc. Relat. Phenom.* **239** (2020) 146903.
- R. Matsumoto, R. Murakami et al., “[Pressure-induced insulator to metal transition of mixed valence compound Ce(O,F)SbS2](https://doi.org/10.1063/1.5079765)”: *Journal of Applied Physics*, **125** (2019) 075102.   ※ Chosen as an Editor's Pick
- R. Matsumoto, R. Murakami Y. Takano et al., “[Data-driven exploration of new pressure induced superconductivity in PbBi2Te4](https://doi.org/10.1080/14686996.2018.1548885)”: *Sci. Tech. Adv. Mater.* **19** (2018) 909–916.  ※ Editor's choice 2018.

### 査読あり国際学会
- R. Murakami, K. Nagata, H. Yoshikawa et. al., "Magnetic Domain Pattern Analysis Using Wavelet-Based Joint Texture Statistics": *Material Research Meeting* (2021).
- R. Murakami, M. Mizumaki, I. Akai, et. al., "Automatic Estimation of XPS Reference Spectra for TiO2 Semiconductor Free from Equipment-derived Arbitrariness": *Material Research Meeting* (2021).

### 査読あり国内筆頭発表
- 村上諒, 仲村和貴, 陰山弘典, “ワンクリック！！膨大なスペクトルの一括解析 ～ビックデータ活用を見据えて～”: 文部科学省主催 サイエンス・インカレ (2018) 39.
- 村上諒, 仲村和貴, 田中祥太, “完全自動な材料開発を見据えた参照データの照合によるXPSスペクトル分解”: 文部科学省主催 サイエンス・インカレ (2020) 99. 	　　　  他２件

### 査読なし国内筆頭発表
応用物理学会, 表面真空学会，放射光学会や計測インフォマティクス研究会など20件の発表

### 受賞歴
- Practical Surface Analysis 2018: Powell Prize 3rd place
- 2017年度 応用物理学会中国四国支部: 奨励賞
- 文部科学省主催 サイエンス・インカレ2018: 審査員特別賞
- 文部科学省主催 サイエンス・インカレ2019: コンソーシアム奨励賞
- NIMS Internship Award 2016
- NIMS Internship Award 2019 
- 2020年度 画像電子学会：インターンシップセッション優秀賞
- 2018年度 米子高専電気情報工学科卒業研究発表：優秀賞

### その他
- International Seminar on Technology for Sustainability 2018　※選考あり
- NIMS Internship, 受入先：DPFC 材料データ解析グループ　※選考あり
- NTT R&Dメディアインテリジェンス研究所 インターンシップ ※給与あり
- 電気通信大学ニュースリリース：[視覚認知に基づいた統計量による磁区パターン画像から物理の解析](https://www.uec.ac.jp/news/announcement/2021/20210701_3495.html)

## 学業経歴
- 2023年3月　電気通信大学大学院 情報理工学研究科 情報学専攻 博士後期課程 修了見込
- 2022年4月　電気通信大学大学院 情報理工学研究科 情報学専攻 博士後期課程 入学
- 2022年3月　電気通信大学大学院 情報理工学研究科 情報学専攻 博士前期課程 修了
- 2020年4月　電気通信大学大学院 情報理工学研究科 情報学専攻 博士前期課程 入学
- 2020年3月　米子工業高等専門学校専攻科 生産システム専攻 卒業
- 2018年4月　米子工業高等専門学校専攻科 生産システム専攻 入学
- 2018年3月　米子工業高等専門学校 電気情報工学科 卒業
- 2013年4月　米子工業高等専門学校 電気情報工学科 入学

## 職務経歴
- 2021年4月　株式会社オープンストリーム 技術創発推進室, 東京都新宿区西新宿2-7-1

## 資格および免許
- 2018年7月　普通車運転免許証取得
