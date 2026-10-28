# Fastrhino-r66s-rom2026
***電犀牛 FastRhino R66S (2GB) OpenWrt 自定義固件編譯指南***

本專案透過 GitHub Actions 與 ImmortalWrt ImageBuilder，為 電犀牛 R66S (2GB RAM) 提供高效、穩定且自動化的雲端韌體編譯與打包方案。

**🌟 韌體特色 (Features)**

  - 硬體適配：專為 Rockchip ARMv8 (RK3566) 晶片設計，對應官方機型代號 lunzn_fastrhino-r66s。
  - 高效構建：採用 ImageBuilder 方案，免除龐大原始碼編譯時間，只需 1~2 分鐘即可完成打包。
    
**介面與語言：**
  - 高顏值主題：內建現代化且支援深色模式的 Argon 主題 (luci-theme-argon)。
  - 在地化支援：完整內建 繁體中文語系 (luci-i18n-base-zh-tw)。
    
**硬體：**
  - FastRhino R66S (RK3568, 2GB RAM)
**網卡驅動：**
  - 內建雙 2.5G 網卡專用穩定驅動 (kmod-r8125)。
  
**網路預設：**
  - 預設 IP: 192.168.1.1
  - 預設帳號: root
  - 預設密碼: password

 **過熱與自動關機防護優化：**
   過熱降溫優化：內建開機自啟動腳本，將 CPU 頻率調節器設定為 schedutil，兼顧效能並有效降低發熱與當機風險。
    
*點擊下載 openwrt-r66s-firmware 壓縮包。
解壓縮後即可取得專屬 .img.gz 韌體，可用於刷入 R66S。*
