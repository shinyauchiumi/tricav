# tricav
Computation of the lid-driven cavity problem in triangular domains by FreeFEM

FreeFem++ tri0.edp

で実行します．スクリプトの最初の方には，メッシュの情報や，continuation の初期値があります．60度の二等辺三角形領域に対する初期値2つと，90度のそれ1つで，3セットあります．

bool outputFigData = false;

をtrueに変えると，流れ関数がP1要素関数として出力されます．
