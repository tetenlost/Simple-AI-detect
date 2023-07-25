# Simple-AI-detect

這裡存放一些網路上AI影像偵測的相關程式碼，可以使用colab或是jupyter執行

 ## 程式分類
 ### 物件分類器應用
 [resnet18訓練](https://github.com/tetenlost/Simple-AI-detect/blob/main/resnet18_%E8%A8%93%E7%B7%B4.ipynb)  
[resnet18訓練（不平衡資料集）](https://github.com/tetenlost/Simple-AI-detect/blob/main/resnet18_%E8%A8%93%E7%B7%B4for%E4%B8%8D%E5%B9%B3%E8%A1%A1%E8%A8%93%E7%B7%B4%E8%B3%87%E6%96%99%E9%9B%86.ipynb)  
[grabcam可視化](https://github.com/tetenlost/Simple-AI-detect/blob/main/gradcam%E5%81%B5%E6%B8%AC%E7%B5%90%E6%9E%9C%E5%8F%AF%E8%A6%96%E5%8C%96.ipynb)  
### AE自編解碼器應用
[去噪](https://github.com/tetenlost/Simple-AI-detect/blob/main/AutoEncoder_%E5%8E%BB%E5%99%AA.ipynb)  
[壓縮](https://github.com/tetenlost/Simple-AI-detect/blob/main/AutoEncoder_%E5%A3%93%E7%B8%AE.ipynb)  
[異常檢測](https://github.com/tetenlost/Simple-AI-detect/blob/main/AutoEncoder_%E7%95%B0%E5%B8%B8%E6%AA%A2%E6%B8%AC.ipynb)  
### 異常檢測（使用電晶體影像）  
[AE自編解碼器](https://github.com/tetenlost/Simple-AI-detect/blob/main/AutoEncoder%E7%95%B0%E5%B8%B8%E6%AA%A2%E6%B8%AC%EF%BC%88%E9%9B%BB%E6%99%B6%E9%AB%94%E5%BD%B1%E5%83%8F%EF%BC%89.ipynb)  
[PADIM](https://github.com/tetenlost/Simple-AI-detect/blob/main/PADIM%E7%95%B0%E5%B8%B8%E6%AA%A2%E6%B8%AC_%EF%BC%88%E4%BD%BF%E7%94%A8%E9%9B%BB%E6%99%B6%E9%AB%94%E5%BD%B1%E5%83%8F%EF%BC%89.ipynb)  
[FastFlow](https://github.com/tetenlost/Simple-AI-detect/blob/main/fastflow%E7%95%B0%E5%B8%B8%E6%AA%A2%E6%B8%AC%EF%BC%88%E4%BD%BF%E7%94%A8%E9%9B%BB%E6%99%B6%E9%AB%94%E5%BD%B1%E5%83%8F%EF%BC%89.ipynb)  
##  colab 使用方法

colab網站:https://colab.research.google.com/

進入colab後，點選"github"，在網址上輸入"https://github.com/tetenlost/Simple-AI-detect/"
![image](https://user-images.githubusercontent.com/38835841/215302651-df0edfde-71c0-4538-ab3f-4b2116195c0c.png)
選擇相關".ipynb"檔點選並打開，點擊播放鍵可執行該段落之程式
![image](https://user-images.githubusercontent.com/38835841/215302738-a8bed53b-42d7-41bf-81e1-9c3b52219f12.png)
## colab 切換GPU方法
點擊"編輯"->"筆記本設定"

![image](https://user-images.githubusercontent.com/38835841/215302785-d332a0b1-8b41-48b7-a922-fbc66982da55.png)

點擊 "GPU"->儲存 (有時GOOGLE GPU 資源吃緊，可能無法使用，這時就選擇"NONE"，或是跳過此步驟即可)

![image](https://user-images.githubusercontent.com/38835841/215302823-8331a834-0b5e-49b2-b60a-149b9d6d8342.png)
