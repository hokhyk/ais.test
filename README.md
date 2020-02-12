# ais.test
應收應付系統API測試碼

## 資料夾結構
./resource 上傳相關檔案

./env.csv.swp JMeter 設定檔

## 對照API
[https://github.com/teed7334-restore/ais](https://github.com/teed7334-restore/ais)

## 使用說明
1. 安裝 JMeter
2. 將 .env.csv.swp 置換成 .env.csv
3. 修改 .env.csv 內容
4. 確認所需服務皆運行中，包含 AIS API 與 HRM
5. 測試碼命名方式為 [package].[func].jmx