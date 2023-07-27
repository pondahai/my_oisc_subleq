This is about address bus 16 bit and data bus 16 bit

一開始我設計了八位元的資料寬度
後來發現這樣有一件事無法實現
就是無法透過程式計算獲得新的目標位址
例如一種情況：
要根據不同輸入來查表
就需要動態計算出表格索引值

因此再一次改動架構
將資料寬度擴展為十六位元
而控制單元不需改動

20230727  
我把電路模擬器改成logisim-evolution HC edition
