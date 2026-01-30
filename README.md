# tricav
Computation of the lid-driven cavity problem in triangular domains by FreeFEM

`FreeFem++ tri0.edp`

で実行します．スクリプトの最初の方には，メッシュの情報や，continuation の初期値があります．最初の commit では60度の二等辺三角形領域に対する初期値2つと，90度のそれ1つで，3セットあります．
2026/1/30の commit で，データを追加しました．doc/takaokaUchiumi251228.pdf にある図式の一部に対応しています．

`bool outputFigData = false;`

をtrueに変えると，resdirに多数のファイルが出力されます．特に，流れ関数がP1要素関数として出力されます．tri0.edp の最初の方で meshfilename で指定したメッシュに対応する有限要素関数です．頂角が同じでも違うメッシュを使っている場合がありますのでご注意ください．
