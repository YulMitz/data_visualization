# 資料視覺化
### 資料使用說明
---
* 資料來源：台灣社會變遷調查資料庫
* 資料下載：[連結](https://www2.ios.sinica.edu.tw/sc/cht/scDownload3a.php)

 
* 使用資料： 
    * 第八期（2020~2024）
    * 社會階層資料（tscs221.sav） 

### Python 環境初始化
---
```Python
# 如果沒裝 uv 先裝 uv

# 初始化虛擬環境
uv venv --python 3.12

# 同步必須套件
uv sync
```
### 資料範例
---
請看 `example.ipynb`
包含：
* 資料讀入
* 印出變項說明
* 印出變項的值 - 標籤
* Matplot 範例

變項說明圖片示例：
![Print Column Labels](./asset/column%20label.png)

變項的值-標籤圖片示例：
![Print Variable Value Labels](./asset/variable%20value%20label.png)