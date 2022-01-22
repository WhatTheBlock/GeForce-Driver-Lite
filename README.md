# NVIDIA GeForce Driver Lite

![demo](/demo.png)

---

### 使用說明：
1. 依照支援的顯卡型號下載驅動
2. 使用[DDU](https://www.guru3d.com/files-details/display-driver-uninstaller-download.html)完整移除現有的NVIDIA顯卡驅動*
3. 解壓縮精簡版驅動程式 (建議使用最新版 7-Zip)
4. 執行`setup.exe`安裝

*非必要，但轉換版本 (Standard to DCH) 則需要先完整移除

---

### 精簡列表：

#### Notebook-Standard
- GeForce Experience相關組件
- HDMI音效驅動
- VC 2017 Runtimes
- Ansel
- USB Type-C驅動 (for RTX 20XX)
- FrameView SDK (用於監控顯卡狀態)
- WMI Provider (for Quadro or NVS)
- Quadro View (for Quadro or NVS)
- Shield Wireless驅動
- 安裝過程的廣告

#### Notebook-DCH
- GeForce Experience相關組件
- HDMI音效驅動
- VC 2017 Runtimes
- Optimus
- USB Type-C驅動 (for RTX 20XX)
- FrameView SDK (用於監控顯卡狀態)
- Quadro View (for Quadro or NVS)
- Shield Wireless驅動
- 安裝過程的廣告

#### Desktop-Standard
- GeForce Experience相關組件
- HDMI音效驅動
- VC 2017 Runtimes
- Ansel
- Optimus
- WMI Provider (for Quadro or NVS)
- Quadro View (for Quadro or NVS)
- Shield Wireless驅動
- 安裝過程的廣告

#### Desktop-DCH
- GeForce Experience相關組件
- HDMI音效驅動
- VC 2017 Runtimes
- Optimus
- Quadro View (for Quadro or NVS)
- Shield Wireless驅動
- 安裝過程的廣告

#### AIO-DCH
- GeForce Experience相關組件
- HDMI音效驅動
- VC 2017 Runtimes
- Quadro View (for Quadro or NVS)
- Shield Wireless驅動
- 安裝過程的廣告

---

### 常見問題：
Q：Standard和DCH都有支援我的顯卡，我該選擇哪種？  
A：如果系統有Windows Store就選擇DCH  

Q：只有DCH支援我的顯卡，但系統沒有Windows Store怎麼辦？(e.g., LTSC)  
A：一樣可以安裝DCH，但Control Panel會無法使用，建議先在LTSC手動安裝Store  
