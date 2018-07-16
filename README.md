# 2018.Software.Developer-VII

請依照下面虛擬情境的描述及題目所要求之技術，建置解決該問題之應用系統

**工業4.0是製造業轉型重要一環，工業4.0最重要第一步就是蒐集設備端的資料，需要從設備端資料蒐集資料，並在Web呈現其監控數據**，請依照上述需求，建立一個*模擬設備監控*軟體，可以做到每秒寫入1筆監控資料到檔案中，另一端，設計*收集資料*軟體，每秒要能讀取模擬軟體寫入的資料，並送入DB儲存，同時，建立Web監控即時系統，即時呈現監控數據

##### 原始需求
1. 監控欄位
   - Date
   - Time
   - Product Tracking Package Dropped Alarm State
   - Product Tracking Total Boards Current Count
   - Product Tracking This Recipe Current Count
   - Conveyor Speed 
2. 請建立Web即時監控**Conveyor Speed**、**Product Tracking Total Boards Current Count**數據變化，要能監控到每秒數據變化
3. 蒐集資料軟體要即時資料抓取資料

# Skill Requirement
> 環境
- 請將開發系統，佈署至Micrsoft Azure (可免費使用30天)
- 請將程式碼透過Visual Studio Team Service進行版控 (可免費使用)，使用Git
- 資料蒐集與模擬軟體，Demo時，可以在本機端執行
> 技術
- Web : 請使用ASP.Net Core 2.0進行開發，前端不限
- Client : 請使用.NET Core開發
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

> 第二次面試時，請說出你如何看到`DevOps`對於開發上的改變


