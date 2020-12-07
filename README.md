# ShallowSea
The new All-in-One CFW package for the Nintendo Switch with atmosphere(fusee primary version) and sxos. 有中文版本指南 & English version readme

中文版本說明:
# 警告！！！ :
* 如果你是第一次破解switch，強烈建議你弄虛擬系統。

# 更新整合包指南(給初學者):
* 如果您是大氣層用戶：除了（Nintendo，emuiibo，emuMMC，JKSV）文件夾，刪除其餘文件夾。然後將 shallowsea/atmosphere X.XX.X/full（or minimal)/ 裏面所有東西解壓縮放到SD卡中。
* 如果您是sxos用戶：除了（Nintendo，emuiibo，sxos/emunand，Emutendo，JKSV）文件夾，刪除其餘文件夾。然後將 shallowsea/sxos X.X.X/full（or minimal)/ 裏面所有東西解壓縮放到SD卡中。

# 大氣層完整版本整合包包括:
大氣層sigpatch
* exosphere.ini（應用了隱身模式）
* hekate
* hbg shop黑商店（帶有jits.cc，redump shop，quotas shop，eeveesaveproject）（語言已更改為中文）
* awoo installer（遊戲安裝軟件，支援格式xci,xcz,nsp,nsz）
* ftpd (電腦遠端控制sd卡文件)(需要filezilla)
* idn_mitm（lan play）
* sysdvr（輸出遊戲畫面到電腦）
* emuiibo（模擬amiibo）
* aio-switch-updater（更新CFW，sigpatches，FW和金手指）
* hb-appstore（自製軟件下載器）
* edizon 4.0（金手指軟件）
* linkalho（鏈接虛假的任天堂帳戶，不刪除用户遊戲保存）
* DBI
* Deepsea toolbox（可以重新啟動到hekate）
* NXDumptool（轉儲遊戲卡）
* daybreak（離線更新固件，與sxos不兼容）
* Choidujournx (大白兔)（離線更新固件。與大氣和sxos兼容）
* nxmtp（使用USB電纜傳輸文件）
* Nx-shell（switch文件管理器）
* JKSV（功能類似於checkpoint，導出和導入保存）
* sigpatch-updater（在線更新大氣層sigpatch）
* pplay（Nintendo Switch的視頻播放器）
* Playernx
* nx-theme-installer（在switch上安裝螢幕桌布）
* N-Xplorer（另一個交換文件管理器）
* switch-cheat-updater（在線更新金手指）
* reboot to payload

插件 ：
* missioncontrol（使用帶有藍牙的第三方控制器而無需轉換器）（不支持sxos）
* syscon（用於具有USB連接的第三方控制器而無需轉換器）
* tesla菜單（由nx-ovlloader加載的初始覆蓋菜單）
* sysclk（超頻switch軟件）

# 大氣層精簡整合包包括:
* 大氣層sigpatch
* exosphere.ini(應用了隱身模式)
* hekate
* daybreak(離線更新固件)(不適用sxos)
* reboot to payload
* hb-appstore(自製軟件下載器)

Poor English version readme
# warning!!! : 
* If you are first time to hack switch, strongly recommend you make sd file emuMMC.

# Update aio-package guide(for beginners):
* If you are Atmosphere user: Delete all the folders but not (Nintendo,emuiibo,emuMMC,JKSV) folders. Then drape and drop shallowsea/atmosphere X.XX.X/full（or minimal)/ into your sd card.
* If you are sxos user: Delete all the folders but not (Nintendo,emuiibo,sxos/emunand,Emutendo,JKSV) folders. Then drape and drop shallowsea/sxos X.X.X/full（or minimal)/ into your sd card.

## atmosphere full version includes:
* sigpatch for atmosphere
* exosphere.ini (Incognito applied)
* hekate
* hbg shop (with jits.cc,redump shop,quotas shop,eeveesaveproject)(language has changed to chinese)
* awoo installer (multi games format installer)
* ftpd (required filezilla)
* idn_mitm (lan play)
* sysdvr (stream switch games to pc)
* emuiibo (amiibo emulated)
* aio-switch-updater (update CFWs, sigpatches, FWs and cheat codes)
* hb-appstore (homebrew app downloader)
* edizon 4.0 (cheat app)
* linkalho (link fake Nintendo account without delete saves)
* DBI
* Deepsea toolbox (u can choose to reboot to hekate)
* NXDumptool (dump gamecard)
* daybreak (offline update firmware，not compatible with sxos)
* Choidujournx (offline update firmware. compatible with both atmosphere and sxos)
* nxmtp (transfer file with usb cable)
* Nx-shell (switch file manager)
* JKSV (function as like as checkpoint，eject or inject save)
* sigpatch-updater (update sigpatch online)
* pplay (a video player for the Nintendo Switch)
* playernx
* nx-theme-installer (install themes on switch)
* N-Xplorer (another switch file manager)
* switch cheat updater (update cheat online)
* reboot to payload

plugin : 
* missioncontrol (sysmodule for third-party controller support with bluetooth)(not support sxos)
* syscon (sysmodule for third-party controller support with usb connection)
* tesla menu (initial overlay menu to be loaded by nx-ovlloader)
* sysclk (overclocked switch)

## atmosphere minimal version includes:
* sigpatch for atmosphere
* exosphere.ini(Incognito applied)
* hekate
* daybreak
* reboot to payload
* hb-appstore

## sxos full version includes:
* hekate
* hbg shop (language has changed to chinese)
* awoo installer (multi games format installer)
* ftpd (required filezilla)
* idn_mitm (lan play)
* sysdvr (stream switch games to pc)
* emuiibo (amiibo emulated)
* aio-switch-updater (update CFWs, sigpatches, FWs and cheat codes)
* hb-appstore (homebrew app downloader)
* linkalho (link fake Nintendo account without delete saves)
* DBI
* Sxdumper (dump gamecard)
* NXDumptool (dump gamecard)
* Choidujournx (offline update firmware. compatible with both atmosphere and sxos)
* nxmtp (transfer file with usb cable)
* Nx-shell (switch file manager)
* JKSV (function as like as checkpoint，eject or inject save)
* pplay (a video player for the Nintendo Switch)
* playernx
* nx-theme-installer (install themes on switch)
* N-Xplorer (another switch file manager)
* switch cheat updater (update cheat online)
* sxos boot.dat

plugin : 
* sx autoloader 1.4 (auto laod switch xci games on home screen)
* syscon (sysmodule for third-party controller support with usb connection)
* tesla menu (initial overlay menu to be loaded by nx-ovlloader)
* sysclk (overclocked switch)

## sxos minimal version includes:
* sxos boot.dat
* hb-appstore

notes: 
* idn_mitm not work for 11.0.0/0.16.0
* edizon,missioncontrol not work for sxos

Credits / Sources:
* [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)
* [Atmosphere sigpatch](https://github.com/ITotalJustice/)
* [hekate](https://github.com/CTCaer/hekate)
* [Deeepsea toolbox](https://github.com/Team-Neptune/DeepSea-Toolbox)
* [hbg shop(without jits.cc,redump shop,quotas shop,eeveesaveproject)](https://thehbg.shop/main.html)
* [awoo installer](https://github.com/Huntereb/Awoo-Installer)
