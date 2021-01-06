# ShallowSea (readme待優化，有空再弄)
The new All-in-One CFW package for the Nintendo Switch with atmosphere(fusee primary version) and sxos. 有中文版本指南 & English version readme(lower side)
# The ultimate solution for jailbreaking your Nintendo Switch has arrived.(copy from sxos)🤪
* You can download rcmloader package from [here](https://github.com/carcaschoi/rcmloader-package)
* You can download switch firmware from [here](https://darthsternie.net/switch-firmwares/)

中文版本說明:
# 警告 warning！！！ :
* 如果你是第一次破解switch，強烈建議你弄虛擬系統&應用隱身模式，以防被任天堂禁止網絡服務(ban機)
* sxos需自購激活碼

# Update aio-package guide(for beginners)更新整合包指南(給初學者):
* 從[這裡](https://github.com/carcaschoi/ShallowSea/releases)下載整合包
* Download aio package from [here](https://github.com/carcaschoi/ShallowSea/releases)
* 如果您是大氣層用戶：除了（Nintendo，emuiibo，emuMMC，BCAT，JKSV）文件夾，刪除其餘文件夾。然後將 shallowsea/atmosphere X.XX.X/full（or minimal)/ 裏面所有東西解壓縮放到SD卡中。
* If you are Atmosphere user: Delete all the folders but not (Nintendo,emuiibo,emuMMC,BCAT,JKSV) folders. Then drape and drop shallowsea/atmosphere X.XX.X/full（or minimal)/ into your sd card.
* 如果您是sxos用戶：除了（Nintendo，emuiibo，sxos/emunand，BCAT，license.dat，Emutendo，JKSV）文件夾，刪除其餘文件夾。然後將 shallowsea/sxos X.X.X/full（or minimal)/ 裏面所有東西解壓縮放到SD卡中。
* If you are sxos user: Delete all the folders but not (Nintendo,license.dat,emuiibo,sxos/emunand,BCAT,Emutendo,JKSV) folders. Then drape and drop shallowsea/sxos X.X.X/full（or minimal)/ into your sd card.
# 大氣層完整版本整合包包括:
| Homebrew | Function |
| ------ | ------ |
| [大氣層sigpatch(sigpatch for atmosphere)](https://github.com/ITotalJustice/patches) | allow switch to run piracy games |
| exosphere.ini（應用了隱身模式）(Incognito applied) | avoid to get ban from Nintendo |
| hekate (with incognito rcm, lockpick rcm, fusee-primary.bin, sxos.bin) | 
| hbg shop黑商店（jits.cc，redump shop，quotas shop，under shop，eeveesaveproject）（語言已更改為中文）(language has changed to chinese) | download piracy games directly to switch |
| Nightfall | 直接連網下載並自動更新任天堂原廠固件，好像系統設置中的系統更新(update the latest of switch offical firmware directly as like as oringal Nintendo update system. One click and go) |
* awoo installer（遊戲安裝軟件，支援格式xci,xcz,nsp,nsz）(multi games format installer)
* goldlef
* ftpd (電腦遠端控制sd卡文件)(需要[filezilla](https://download.filezilla-project.org/client/FileZilla_3.51.0_win64_sponsored-setup.exe))(remote control sd card file from pc via wifi)(required [filezilla](https://download.filezilla-project.org/client/FileZilla_3.51.0_win64_sponsored-setup.exe))
* idn_mitm（lan play）
* sysdvr（輸出遊戲畫面到電腦）(stream switch games screen to pc)
* emuiibo（模擬amiibo）(amiibo emulation)
* aio-switch-updater（更新CFW，sigpatches，FW和金手指）(update CFWs, sigpatches, FWs and cheat codes)
* hb-appstore（自製軟件下載器）(homebrew app downloader)
* edizon 4.0 snapshot（金手指軟件）
* linkalho（鏈接虛假的任天堂帳戶，不刪除用户遊戲保存）(link fake Nintendo account without delete user games saves)
* DBI
* Deepsea toolbox（可以重新啟動到hekate）(u can choose to reboot to hekate)
* NXDumptool（轉儲遊戲卡）(Dump gamecard)
* daybreak（離線更新固件，與sxos不兼容）(offline update firmware. Only compatible with atmosphere)
* Choidujournx大白兔（離線更新固件。與大氣和sxos兼容）(offline update firmware. compatible with both atmosphere and sxos)
* nxmtp（使用USB電纜傳輸文件）(transfer file with usb cable)
* Nx-shell（switch文件管理器）(switch sd file manager)
* JKSV（功能類似於checkpoint，導出和導入保存）(function as like as checkpoint，eject or inject save)
* sigpatch-updater（在線更新大氣層sigpatch）
* pplay（Nintendo Switch的視頻播放器）(a video player for the Nintendo Switch)
* Playernx
* nx-theme-installer（在switch上安裝螢幕桌布）
* N-Xplorer（另一個switch文件管理器）(another swqitch file manager)
* switch-cheat-updater（在線更新金手指）(update cheat online)
* nx ntpc （適當設置Nintendo Switch的時鐘）(sets the Nintendo Switch's clock appropriately)
* lock log (停止向Nintendo發送日誌)(stops sending telemetry to Nintendo)
* reboot to payload

插件 ：
* missioncontrol (無需額外轉接器，即可直接用第三方手柄 藍牙連接switch，etc. ps4手柄)（不支持sxos）
* syscon（無需額外轉接器，即可用usb線連接第三方手柄，etc. ps3 ps4 xbox one xbox360等手柄）
* nx-ovlloader
* tesla菜單（由nx-ovlloader加載的初始覆蓋菜單）
* sysclk（超頻switch軟件）

# 大氣層精簡整合包包括:
* 大氣層sigpatch
* exosphere.ini(應用了隱身模式)
* hekate(with incognito rcm, lockpick rcm, fusee-primary.bin, sxos.bin)
* Nightfall (直接連網下載並自動更新任天堂原廠固件，好像系統設置中的系統更新)(只適用大氣層)
* daybreak(離線更新固件)(不適用sxos)
* reboot to payload
* hb-appstore(自製軟件下載器)

# sxos完整版本整合包包括:
* hekate(with incognito rcm, lockpick rcm, fusee-primary.bin, sxos.bin)
* hbg shop黑商店(已加入jits.cc,redump shop,quotas shop,under shop,eeveesaveproject)（語言已更改為中文）(language has changed to chinese)
* awoo installer（遊戲安裝器，支援各種格式遊戲檔案，nsp nsz xci xcz）
* goldlef
* ftpd (遠端控制switch SD文件)（需要[filezilla](https://download.filezilla-project.org/client/FileZilla_3.51.0_win64_sponsored-setup.exe)）
* idn_mitm（lan play局域網播放）
* sysdvr（把遊戲畫面投影到電腦）
* emuiibo（模擬amiibo）
* aio-switch-updater（在線更新CFW，sigpatches，FW和金手指）(update CFWs, sigpatches, FWs and cheat codes)
* hb-appstore（自製軟件下載器）
* linkalho（鏈接虛假的任天堂帳戶，不刪除用户保存）
* DBI
* Sxdumper（轉儲遊戲卡）(不支援大氣層)
* NXDumptool（轉儲遊戲卡）
* Choidujournx（離線更新固件。與大氣層和sxos兼容）
* nxmtp（使用USB線傳輸文件到電腦）
* Nx-shell（switch文件管理器）
* JKSV（功能類似於checkpoint，導出導入保存）
* pplay（Nintendo Switch的視頻播放器）
* Playernx
* nx-theme-installer（在switch上安裝螢幕桌布）(install themes on switch)
* N-Xplorer（另一個switch文件管理器）(another switch file manager)
* switch-cheat-updater（在線更新金手指）
* nx ntpc(sets the Nintendo Switch's clock appropriately)
* lock log(停止向Nintendo發送日誌)
* sxos boot.dat

插件 ：
* sx autoloader 1.4（在桌面直接加載xci相簿遊戲)(auto laod switch xci games on home screen)
* syscon (無需額外轉接器，即可用usb線連接第三方手柄，etc. ps3 ps4 xbox one xbox360等手柄)
* tesla menu (快捷菜單)（由nx-ovlloader加載的初始覆蓋菜單）
* nx-ovlloader
* sysclk（超頻軟件）

# sxos精簡整合包包括:
* sxos boot.dat
* hb-appstore
* hekate(with incognito rcm, lockpick rcm, fusee-primary.bin, sxos.bin)


Poor English version readme
# warning!!! : 
* If you are first time to hack switch, strongly recommend you to make emuMMC/emunand & applied Incognito to avoid ban from Nintendo
* sxos need license.dat (buy sxos license yourself)

# Update aio-package guide(for beginners):
* Download aio package from [here](https://github.com/carcaschoi/ShallowSea/releases)
* If you are Atmosphere user: Delete all the folders but not (Nintendo,emuiibo,emuMMC,BCAT,JKSV) folders. Then drape and drop shallowsea/atmosphere X.XX.X/full（or minimal)/ into your sd card.
* If you are sxos user: Delete all the folders but not (Nintendo,license.dat,emuiibo,sxos/emunand,BCAT,Emutendo,JKSV) folders. Then drape and drop shallowsea/sxos X.X.X/full（or minimal)/ into your sd card.

## atmosphere full version includes:
* sigpatch for atmosphere
* exosphere.ini (Incognito applied)
* hekate(with incognito rcm, lockpick rcm, fusee-primary.bin, sxos.bin)
* hbg shop (with jits.cc,redump shop,quotas shop,under shop,eeveesaveproject)(language has changed to chinese)
* Nightfall (update the latest of switch offical firmware directly as like as oringal Nintendo update system. One click and go)(only for atmosphere)
* awoo installer (multi games format installer)
* goldlef
* ftpd (required [filezilla](https://download.filezilla-project.org/client/FileZilla_3.51.0_win64_sponsored-setup.exe))
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
* nx ntpc(sets the Nintendo Switch's clock appropriately)
* lock log(stops sending telemetry to Nintendo)
* reboot to payload

plugin : 
* missioncontrol (sysmodule for third-party controller support with bluetooth)(not support sxos)
* syscon (sysmodule for third-party controller support with usb connection)
* tesla menu (initial overlay menu to be loaded by nx-ovlloader)
* nx-ovlloader
* sysclk (overclocked switch)

## atmosphere minimal version includes:
* sigpatch for atmosphere
* exosphere.ini(Incognito applied)
* hekate(with incognito rcm, lockpick rcm, fusee-primary.bin, sxos.bin)
* Nightfall (update the latest of switch offical firmware directly as like as oringal Nintendo update system. One click and go)(only for atmosphere)
* daybreak
* reboot to payload
* hb-appstore

## sxos full version includes:
* hekate(with incognito rcm, lockpick rcm, fusee-primary.bin, sxos.bin)
* hbg shop  (with jits.cc,redump shop,quotas shop,under shop,eeveesaveproject)(language has changed to chinese)(language has changed to chinese)
* awoo installer (multi games format installer)
* goldlef
* ftp4sxos (required [filezilla](https://download.filezilla-project.org/client/FileZilla_3.51.0_win64_sponsored-setup.exe))
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
* nx ntpc(sets the Nintendo Switch's clock appropriately)
* lock log(stops sending telemetry to Nintendo)
* sxos boot.dat

plugin : 
* sx autoloader 1.4 (auto laod switch xci games on home screen)
* syscon (sysmodule for third-party controller support with usb connection)
* tesla menu (initial overlay menu to be loaded by nx-ovlloader)
* nx-ovlloader
* sysclk (overclocked switch)

## sxos minimal version includes:
* sxos boot.dat
* hb-appstore
* hekate(with incognito rcm, lockpick rcm, fusee-primary.bin, sxos.bin)

notes: 
* edizon,missioncontrol, Nightfall not work for sxos
* atmosphere sysdvr syscon x

Sources:
* [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)
* [Atmosphere sigpatch](https://github.com/ITotalJustice/patches)
* [sigpatch updater](https://github.com/ITotalJustice/sigpatch-updater)
* [hekate](https://github.com/CTCaer/hekate)
* [Deeepsea toolbox](https://github.com/Team-Neptune/DeepSea-Toolbox)
* [hbg shop(without jits.cc,redump shop,quotas shop,under shop,eeveesaveproject)](https://thehbg.shop/main.html)
* [Nightfall](https://github.com/D3fau4/NightFall)
* [awoo installer](https://github.com/Huntereb/Awoo-Installer)
* [goldleaf](https://github.com/XorTroll/Goldleaf)
* [ftpd](https://github.com/mtheall/ftpd)
* [idn_mitm](https://github.com/spacemeowx2/ldn_mitm)
* [sysdvr](https://github.com/exelix11/SysDVR/)
* [emuiibo](https://github.com/XorTroll/emuiibo/)
* [aio-switch-updater](https://github.com/HamletDuFromage/AIO-switch-updater)
* [hb-appstore](https://github.com/fortheusers/hb-appstore)
* [edizon](https://github.com/WerWolv/EdiZon)
* [linkalho](https://github.com/rdmrocha/linkalho)
* [Deepsea toolbox](https://github.com/Team-Neptune/DeepSea-Toolbox)
* [nxdumptool](https://github.com/DarkMatterCore/nxdumptool)
* [choijournx](https://switchtools.sshnuke.net/)
* [nxmtp](https://github.com/liuervehc/nxmtp)
* [nx shell](https://github.com/joel16/NX-Shell)
* [jksv](https://github.com/J-D-K/JKSV)
* [pplay](https://github.com/Cpasjuste/pplay)
* [nxthemeinstaller](https://github.com/exelix11/SwitchThemeInjector)
* [N-Xplorer](https://github.com/CompSciOrBust/N-Xplorer)
* [switch-cheat-updater](https://github.com/HamletDuFromage/switch-cheats-updater)
* [nx ntpc](https://github.com/thedax/NX-ntpc)
* [ftp4sxos](https://github.com/Falki14/ftpd4sxos)
* [lock-logs](https://github.com/StarDustCFW/Lock-Logs)
* [nx-ovlloader](https://github.com/WerWolv/nx-ovlloader)
* [dbi](https://github.com/rashevskyv/dbi)
* [sxos items(such as sxos boot.dat, sxos.bin)](https://sx.xecuter.com)
* [missioncontrol](https://github.com/ndeadly/MissionControl)
* [syscon](https://github.com/cathery/sys-con)
* [tesla menu](https://github.com/WerWolv/Tesla-Menu)
* [sysclk](https://github.com/retronx-team/sys-clk)
* [incognito rcm](https://github.com/Scandal-UK/Incognito_RCM)
* [Lockpick rcm](https://github.com/shchmue/Lockpick_RCM)
