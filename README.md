# 201807_104_hr_bank

【2018年104資訊科技Hackathon】為資料來源
* 公司營業地址是政府營業登記資料(營業+歇業)，其中有1/3資料無法對回，估計是104資料問題。

## Finished:

* 資料筆數約1.2億筆，已完成基本資料清理。
* 利用HDF5處理資料，並獲得時間為基礎的統計資料（某工作最新一筆交易，與其點擊、儲存、應徵累計）
* 使用RFM理論處理資料，並利用rank(pct=True)的方式來當評分方法。
* word count and wordcloud
* 某程度上證明基本統計資料已經可以達成一定程度的實用性。


## To be better list:

* SVD矩陣分解實作
* 將資料利用回歸方式訓練
* 應用TF-IDF 方式改進排序 
* 了解learning to rank
* 利用深度學習

<img src="https://github.com/kuonumber/201807_104_hr_bank/blob/master/keyword.png?raw=true" width="700" height="500">

