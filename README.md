# fastrhino-r66s-rom2026
***電犀牛 FastRhino R66S (2GB) OpenWrt 自定義固件編譯指南***

本指南將帶領你透過 GitHub Actions 雲端編譯專為 FastRhino R66S（基於 Rockchip RK3568 晶片）量身打造的 OpenWrt 固件。針對你提到的自動關機與過熱問題，我們將在配置中加入溫控優化、CPU 頻率調校以及適當的散熱策略。

一、 固件預設目標與優化特點

1. 硬體目標：FastRhino R66S (RK3568, 2GB RAM)

2. 網路設定：

 - 預設 IP: 192.168.1.1
 - 預設帳號: root
 - 預設密碼: password

3. 介面與語言：

 - 主題：luci-theme-istore (iStoreOS 風格主題)
 - 語言包：繁體中文 (zh-tw)、英文 (en)

4. 過熱與自動關機防護優化：

 - 設定 CPU 效能調節器（Governor）為 schedutil 或 conservative，避免長時間全速運行導致過熱。
 - 確保核心內建的 Thermal Management（熱功耗管理）及溫控降頻（Thermal Throttling）正常啟用。
 - 建議在放置時保持周圍通風，避免金屬外殼過度積熱。
