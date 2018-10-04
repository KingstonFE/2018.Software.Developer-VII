# 2018.Software.Developer-VII

請依照下面虛擬情境的描述及題目所要求之技術，建置解決該問題之應用系統

**工業4.0是製造業轉型重要一環，工業4.0最重要第一步就是蒐集設備端的資料，需要從設備端資料蒐集資料，並在Web呈現其監控數據**，請依照上述需求，建立一個模擬*監控設備健康狀況*系統，設備端會每秒寫入1筆資料到設備資料庫中，因此，需要設計*收集資料*軟體，每秒要能讀取設備資料庫內的資料，要能存入系統DB，同時，建立Web監控即時系統，即時呈現監控數據變化

##### 原始需求
1. 監控欄位
   - Date
   - Time
   - Product Tracking Package Dropped Alarm State
   - Product Tracking Total Boards Current Count
   - Product Tracking This Recipe Current Count
   - Conveyor Speed 
2. 請建立Web即時監控**Conveyor Speed**、**Product Tracking Total Boards Current Count**數據變化，要能監控到每秒數據變化
3. 收集資料要即時抓取設備資料庫資料
4. 請自行建立設備模擬軟體，模擬每秒寫入設備資料庫，並且模擬三台設備同時運作. 
5. Web端要能呈現搜取的資料，並繪製下方兩種圖表
   - 趨勢圖: X 軸是時間、Y軸是Conveyor Speed，同時顯示三台設備
   - 長條圖: X軸是Product Tracking Total Boards Current Count，Y軸是量


# Skill Requirement
> 環境
- 請將開發系統，佈署至Micrsoft Azure (可免費使用30天)
- 請將程式碼透過Visual Studio Team Service進行版控 (可免費使用)，使用Git
- 資料蒐集與模擬軟體，Demo時，可以在本機端執行
> 技術
所有軟體開發請使用C#且是.NET Core Framework開發
- Web : 請使用ASP.Net Core 2.1進行開發，前端不限
- Client : 請使用.NET Core開發
- 圖表 : 請使用D3.js套件繪製
- DataBase : 依照需求自行決定

# Acceptance Criteria
> 時間
- 依照HR指定時間完成，並再跟HR約第二次面談時間

> 成果展示
- 於第二次面試時間的前一週，把自己的Code從VSTS搬移到Github的`Repository`並邀請此帳號加入
- 提供Azure Web Site Url，以供瀏覽成果

> 第二次面試時，請現場Demo作品及說明系統架構
- Demo時，請直接使用Azure Web Site成品說明
- 當天顯示Visual Studio Team Server版控歷史紀錄

> 請依照`Description`，設計解決方案

> 第二次面試時，請說出你如何扮演好`DevOps`團隊一員


