=======================================================================
応用計算
=======================================================================

相互作用エネルギー
=======================================================================

エネルギー微分
=======================================================================

エネルギーの微分から様々な物理量が得られます [#energy_gradient]_ 。

.. csv-table::
   
   :math:`\frac{\partial E}{\partial R_{A}}`, 原子核に働く力、構造最適化
   :math:`\frac{\partial^2 E}{\partial R_{A}\partial R_{B}}`, 基準振動解析、力の定数行列(Hessian行列)
   :math:`\frac{\partial E}{\partial F_{i}}`, 電気双極子モーメント
   :math:`\frac{\partial^2 E}{\partial F_{i}\partial F_{j}}`, 分極率
   :math:`\frac{\partial^2 E}{\partial R_{A}\partial F_{i}}`, IR吸収強度
   :math:`\frac{\partial^3 E}{\partial R_{A}\partial F_{i}\partial F_{j}}`, Raman強度
   :math:`\frac{\partial E}{\partial B_{a}}`, 磁気双極子モーメント
   :math:`\frac{\partial^2 E}{\partial B_{a}\partial B_{b}}`, 磁化率
   :math:`\frac{\partial^2 E}{\partial B_{a}\partial \mu_{b}}`, NMR化学シフト

ここで記号の意味は次の通り。

- :math:`R`: 核座標
- :math:`F`: 電場
- :math:`B`: 磁束密度
- :math:`\mu`: 核磁気モーメント


Gaussianでの計算
-----------------------------------------------------------------------

詳しくはGaussianキーワードリスト(http://gaussian.com/keywords/)を御覧ください。


.. csv-table::
   :header: キーワード, 用途

   opt, 構造最適化
   freq, IR
   freq(raman), Raman
   freq(vcd), 振動円偏光二色性スペクトル
   nmr, NMR


.. [#energy_gradient] 日本化学会 編, 実験化学講座12, p. 88(2004), 丸善
