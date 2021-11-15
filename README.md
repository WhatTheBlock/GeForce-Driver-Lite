# NVIDIA Driver Lite

![demo](/demo.png)

---

### 使用說明：
1. 依照支援的顯卡型號下載驅動
2. 使用DDU完整移除現有的NVIDIA顯卡驅動
3. 解壓縮精簡版驅動程式 (建議使用最新版 7-Zip)
4. 執行`setup.exe`安裝

---

### 精簡列表：

#### Notebook-Standard
- 移除GeForce Experience相關組件
- 移除HDMI音效驅動
- 移除VC 2017 Runtimes
- 移除Ansel
- 移除USB Type-C驅動 (for RTX 20XX)
- 移除FrameView SDK (用於監控顯卡狀態)
- 移除WMI Provider (for Quadro or NVS)
- 移除Quadro View (for Quadro or NVS)
- 移除Shield Wireless驅動
- 移除安裝過程的廣告

#### Notebook-DCH
- 移除GeForce Experience相關組件
- 移除HDMI音效驅動
- 移除VC 2017 Runtimes
- 移除USB Type-C驅動 (for RTX 20XX)
- 移除FrameView SDK (用於監控顯卡狀態)
- 移除Quadro View (for Quadro or NVS)
- 移除Shield Wireless驅動
- 移除安裝過程的廣告

#### Desktop-Standard
- 移除GeForce Experience相關組件
- 移除HDMI音效驅動
- 移除VC 2017 Runtimes
- 移除Ansel
- 移除Optimus
- 移除WMI Provider (for Quadro or NVS)
- 移除Quadro View (for Quadro or NVS)
- 移除Shield Wireless驅動
- 移除安裝過程的廣告

#### Desktop-DCH
- 移除GeForce Experience相關組件
- 移除HDMI音效驅動
- 移除VC 2017 Runtimes
- 移除Optimus
- 移除Quadro View (for Quadro or NVS)
- 移除Shield Wireless驅動
- 移除安裝過程的廣告

---

### 常見問題：
Q：Standard和DCH都有支援我的顯卡，我該選擇哪種？  
A：如果系統有Windows Store就選擇DCH  

Q：只有DCH支援我的顯卡，但系統沒有Windows Store怎麼辦？(e.g., LTSC)  
A：一樣可以安裝DCH，但Control Panel會無法使用，建議先在LTSC手動安裝Store  
