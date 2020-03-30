# Training Deep Networks with Synthetic Data for Textureless
碩士研究成果，不過目前因其他因素，無法公開全文，也不適合作太詳細的說明，還請見諒
最晚公開時間 2025.01
## 論文連結
https://drive.google.com/open?id=14RATn-h3gV4wIrBbZ2rxjERyxK64EEQM
## 簡述
### 問題定義
　　在這個研究中想要解決在工業應用上因傳統視覺伺服的不足而導入深度學習時，所發生的種種問題。
我們假設視覺系統為一個手眼系統(左圖)，所以能夠以物體為圓心定義出一個球座標系(右圖)

![image](img/eyeonhand.png)

　　根據此座標系，在我們的研究中主要考慮三個變量 : In-plane Rotation 、 Theta 、 Phi

![image](img/ThreePara.gif)

　　同時為了解決訓練資料取得及標定不易的問題，我們撰寫了使用OpenGL並在QT上進行開發的CAD模型模擬器，詳細可以前往我的 CAD-Simulator 專案(https://github.com/Nineko/CAD-Simulator)
  
![image](img/CAD模型界面.png)
