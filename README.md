# 0114

1.(1)von Neumann architecture
      馮紐曼架構主要分為:
      算術邏輯單元（Arithmetic Logic Unit,ALU）處理算術與邏輯運算
      記憶單元（Memory Unit,MU）：儲存資料與程式、指令，並提供 ALU 運算的資料。
      輸入（Input Unit,IU）：讀取外界之命令、資料及訊號。
      輸出（Output Unit,OU）將資料輸出。
      控制單元（Control Unit,CU）指揮整部電腦、指令解碼、協調各單元運作與資料傳送。
(2)虛擬記憶體
      將輔助記憶體模擬成主記憶體使用，可增加記憶體空間
(3)POST全名Power-On Self-Test啟動自我檢測
      在啟動時會執行，針對計算機硬體如CPU、主機板、記憶體等進行檢測
(4)machine cycle(instruction cycle) 機器循環週期
      包含四個步驟
      取得指令
      解碼指令
      執行指令
      儲存結果
2.(1)作業系統的功能
      提供操作電腦的介面,讓人們跟電腦溝通
      執行應用軟體提供應用軟體執行的環境將應用軟體的程式載入到記憶體中，以執行程式。
      提供檔案管理系統管理磁碟中檔案的位置只要知道檔案的名稱，就可以進行存取、刪除檔案
      監控和維護電腦運作系統發生錯誤時，作業系統會終止有問題的程式，以確保系統不受到傷害
      分配系統資源讓資源獲得最有效的利用當使用者進行多項工作時，作業系統會妥善分配資源給每一個部份使用

(2)Memory hierarchy

3.(10011001.101)2=(231.4)8=(99.A)16=(153.625)10

4.(153.625)10=(10011001.101)2

5.(A)signed-magnitude
  (39)10=(100111)2
   10100111 
  (B)1’s complement
  00100111
  11011000
  (C)2’s complement
  00100111
  11011000
  11011001
6.(A) signed-magnitude
  10010010
  1 (-)0010010(18)
  -18
  (B) 1’s complement
  1(-)
  0010010
  1101101
  109
  -109
  (C) 2’s complement
  10010010
  1(-)
  0010010-1
  0010001
  17
  -17
