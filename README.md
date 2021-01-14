# ShallowSea (readme待優化，有空再弄)
The new All-in-One CFW package for the Nintendo Switch with atmosphere(fusee primary version) and sxos.
* You can download rcmloader package(注入器整合包) from [here](https://github.com/carcaschoi/rcmloader-package)
* You can download switch firmware(系統固件) from [here](https://darthsternie.net/switch-firmwares/)
* 按[這裏](https://github.com/carcaschoi/switch-chinese-homebrew-app)下载switch漢化的自制軟件

說明 readme:
# 更新整合包指南 Update aio-package guide !!!:
| 中文指南 | English guide |
| ------ | ------------- |
| 從[這裡](https://github.com/carcaschoi/ShallowSea/releases)下載整合包「Shalloesea.rar」 | Download aio package「Shallowsea.rar」 from [here](https://github.com/carcaschoi/ShallowSea/releases) |
| 如果您是大氣層用戶：除了（Nintendo，emuiibo，emuMMC，BCAT，JKSV，warmboot_mariko）文件夾，刪除其餘文件夾。然後將 shallowsea/atmosphere X.XX.X/ 裏面所有東西解壓縮放到SD卡中。 | If you are Atmosphere user: Delete all the folders but not (Nintendo,emuiibo,emuMMC,BCAT,JKSV,warmboot_mariko) folders. Then drape and drop shallowsea/atmosphere X.XX.X/ into your sd card. |
| 如果您是sxos用戶：除了（Nintendo，emuiibo，sxos/emunand，BCAT，license.dat，Emutendo，JKSV）文件夾，刪除其餘文件夾。然後將 shallowsea/sxos X.X.X/ 裏面所有東西解壓縮放到SD卡中。 | If you are sxos user: Delete all the folders but not (Nintendo,license.dat,emuiibo,sxos/emunand,BCAT,Emutendo,JKSV) folders. Then drape and drop shallowsea/sxos X.X.X/ into your sd card. |

# 大氣層整合包包括 atmosphere package includes:
| 自製軟件 Homebrew | 用途 Function |
| ---------------- | ------------- |
| [大氣層sigpatch(sigpatch for atmosphere)](https://github.com/ITotalJustice/patches) | allow switch to run nsp forwarder & piracy games |
| exosphere.ini（應用了隱身模式）(Incognito applied) | avoid to get ban from Nintendo |
| [hekate](https://github.com/CTCaer/hekate) (with [incognito rcm](https://github.com/jimzrt/Incognito_RCM), [lockpick rcm](https://github.com/shchmue/Lockpick_RCM), [tegraexplorer](https://github.com/suchmememanyskill/TegraExplorer), [fusee-primary.bin](https://github.com/Atmosphere-NX/Atmosphere), [sxos.bin](https://sx.xecuter.com) | Custom Graphical Nintendo Switch bootloader, firmware patcher, tools, and many more.
| hbg shop黑商店([tinfoil shop setup](https://github.com/carcaschoi/ShallowSea/blob/main/tinfoil%20shop%20setup))（語言已更改為中文）(language has changed to chinese) | download piracy games directly to switch |
| [Nightfall(run it on non-applet mode)(only support atmosphere)](https://github.com/D3fau4/NightFall) | 直接連網下載並自動更新任天堂原廠固件，好像系統設置中的系統更新(update the latest of switch offical firmware directly as like as oringal Nintendo update system. One click and go) |
| [awoo installer](https://github.com/Huntereb/Awoo-Installer) | 遊戲安裝軟件，支援格式xci,xcz,nsp,nsz (NSP, NSZ, XCI, and XCZ Installer for Nintendo Switch) |
| [goldlef](https://github.com/XorTroll/Goldleaf) | check function from [here](https://github.com/XorTroll/Goldleaf#features) |
| [ftpd pro](https://github.com/mtheall/ftpd) | Allows file transfer over local network via ftp | 
| [idn_mitm](https://github.com/spacemeowx2/ldn_mitm) | lan play |
| [sysdvr](https://github.com/exelix11/SysDVR) | allows capturing the running game output to a pc via USB or network connection |
| [emuiibo](https://github.com/XorTroll/emuiibo) | 模擬amiibo (amiibo emulation) |
| [aio-switch-updater](https://github.com/HamletDuFromage/AIO-switch-updater) | 更新CFW，sigpatches，FW和金手指 (update CFWs, sigpatches, FWs and cheat codes) |
| [hb-appstore](https://github.com/fortheusers/hb-appstore) | 自製軟件下載器 (homebrew app downloader) |
| [edizon snapshot](https://github.com/WerWolv/EdiZon) | 金手指軟件 (games cheating app) |
| [linkalho](https://github.com/rdmrocha/linkalho) | 鏈接虛假的任天堂帳戶，不刪除用户遊戲保存(link fake Nintendo account without delete user games saves) |
| [DBI](https://github.com/rashevskyv/dbi) | install games & mtp serves |
| [Deepsea toolbox](https://github.com/Team-Neptune/DeepSea-Toolbox) |（可以重新啟動到hekate）(u can choose to reboot to hekate)
| [NXDumptool](https://github.com/DarkMatterCore/nxdumptool) | （轉儲遊戲卡）(Dump gamecard) |
| Daybreak | 離線更新系統固件，與sxos不兼容(offline update firmware. Only compatible with atmosphere) |
| [Choidujournx(大白兔)](https://switchtools.sshnuke.net/) | 離線更新固件。與大氣和sxos兼容(offline update firmware. compatible with both atmosphere and sxos) |
| [nxmtp](https://github.com/liuervehc/nxmtp) | 使用USB電纜傳輸文件(transfer file with usb cable)|
| [Nx-shell](https://github.com/joel16/NX-Shell) | switch文件管理器(switch sd file manager) |
| [JKSV](https://github.com/J-D-K/JKSV) | 功能類似於[checkpoint](https://github.com/FlagBrew/Checkpoint)，導出和導入保存(function as like as [checkpoint](https://github.com/FlagBrew/Checkpoint)，eject or inject save) |
| [sigpatch-updater](https://github.com/ITotalJustice/sigpatch-updater) | 在線更新大氣層sigpatch(update atmosphere sigpatch online) |
| [pplay](https://github.com/Cpasjuste/pplay) | Nintendo Switch的視頻播放器(a video player for the Nintendo Switch) |
| [themezer-nx](https://github.com/suchmememanyskill/themezer-nx) | A switch theme downloader |
| [nx-theme-installer](https://github.com/exelix11/SwitchThemeInjector) | 在switch上安裝螢幕桌布(install themes on switch) |
| [N-Xplorer](https://github.com/CompSciOrBust/N-Xplorer) | 另一個switch文件管理器(another switch sd card file manager) |
| [switch-cheat-updater](https://github.com/HamletDuFromage/switch-cheats-updater) | 在線更新遊戲金手指(update games cheat code online) |
| [nx ntpc](https://github.com/thedax/NX-ntpc) | 在線設置Nintendo Switch的時鐘(sets the Nintendo Switch's clock appropriately) |
| [lock log](https://github.com/StarDustCFW/Lock-Logs) | 停止向Nintendo發送日誌(stops sending telemetry to Nintendo) |
| reboot to payload | / |
| [missioncontrol](https://github.com/ndeadly/MissionControl/)(only support atmosphere) | 無需額外轉接器，即可直接用第三方手柄藍牙連接switch，etc. ps4手柄(sysmodule for third-party controller support with bluetooth) |
| [syscon](https://github.com/cathery/sys-con) | 無需額外轉接器，即可用usb線連接第三方手柄，etc. ps3 ps4 xbox one xbox360等手柄(sysmodule for third-party controller support with USB connection) |
| [nx-ovlloader](https://github.com/WerWolv/nx-ovlloader) | Host process for loading Switch overlay OVL |
| [tesla menu](https://github.com/WerWolv/Tesla-Menu) | 由nx-ovlloader加載的初始覆蓋菜單 (The initial overlay menu to be loaded by nx-ovlloader) |
| [ovlsysmodule](https://github.com/WerWolv/ovl-sysmodules) | / |
| [sysclk](https://github.com/retronx-team/sys-clk) | 超頻switch (overclock switch) |
| [sx gear](https://sx.xecuter.com) | redirect sxos payload to hekate payload |

# sxos整合包包括 sxos package includes :
| 自製軟件 Homebrew | 用途 Function |
| ---------------- | ------------- |
| [hekate](https://github.com/CTCaer/hekate) (with [incognito rcm](https://github.com/jimzrt/Incognito_RCM), [lockpick rcm](https://github.com/shchmue/Lockpick_RCM), [tegraexplorer](https://github.com/suchmememanyskill/TegraExplorer), [fusee-primary.bin](https://github.com/Atmosphere-NX/Atmosphere), [sxos.bin](https://sx.xecuter.com) | Custom Graphical Nintendo Switch bootloader, firmware patcher, tools, and many more.
| hbg shop黑商店([tinfoil shop setup](https://github.com/carcaschoi/ShallowSea/blob/main/tinfoil%20shop%20setup))（語言已更改為中文）(language has changed to chinese) | download piracy games directly to switch |
| [awoo installer](https://github.com/Huntereb/Awoo-Installer) | 遊戲安裝軟件，支援格式xci,xcz,nsp,nsz (NSP, NSZ, XCI, and XCZ Installer for Nintendo Switch) |
| [goldlef](https://github.com/XorTroll/Goldleaf) | check function from [here](https://github.com/XorTroll/Goldleaf#features) |
| [ftpd pro](https://github.com/mtheall/ftpd) | Allows file transfer over local network via ftp | 
| [sysdvr](https://github.com/exelix11/SysDVR) | allows capturing the running game output to a pc via USB or network connection |
| [emuiibo](https://github.com/XorTroll/emuiibo) | 模擬amiibo (amiibo emulation) |
| [aio-switch-updater](https://github.com/HamletDuFromage/AIO-switch-updater) | 更新CFW，sigpatches，FW和金手指 (update CFWs, sigpatches, FWs and cheat codes) |
| [hb-appstore](https://github.com/fortheusers/hb-appstore) | 自製軟件下載器 (homebrew app downloader) |
| [linkalho](https://github.com/rdmrocha/linkalho) | 鏈接虛假的任天堂帳戶，不刪除用户遊戲保存(link fake Nintendo account without delete user games saves) |
| [DBI](https://github.com/rashevskyv/dbi) | install games & mtp serves |
| [Sxdumper](https://sx.xecuter.com) | 轉儲遊戲卡,不支援大氣層 (dump game card & not support atmosphere) |
| [NXDumptool](https://github.com/DarkMatterCore/nxdumptool) | （轉儲遊戲卡）(Dump gamecard) |
| [Choidujournx(大白兔)](https://switchtools.sshnuke.net/) | 離線更新固件。與大氣和sxos兼容(offline update firmware. compatible with both atmosphere and sxos) |
| [nxmtp](https://github.com/liuervehc/nxmtp) | 使用USB電纜傳輸文件(transfer file with usb cable)|
| [Nx-shell](https://github.com/joel16/NX-Shell) | switch文件管理器(switch sd file manager) |
| [JKSV](https://github.com/J-D-K/JKSV) | 功能類似於[checkpoint](https://github.com/FlagBrew/Checkpoint)，導出和導入保存(function as like as [checkpoint](https://github.com/FlagBrew/Checkpoint)，eject or inject save) |
| [themezer-nx](https://github.com/suchmememanyskill/themezer-nx) | A switch theme downloader |
| [nx-theme-installer](https://github.com/exelix11/SwitchThemeInjector) | 在switch上安裝螢幕桌布(install themes on switch) |
| [N-Xplorer](https://github.com/CompSciOrBust/N-Xplorer) | 另一個switch文件管理器(another switch sd card file manager) |
| [switch-cheat-updater](https://github.com/HamletDuFromage/switch-cheats-updater) | 在線更新遊戲金手指(update games cheat code online) |
| [nx ntpc](https://github.com/thedax/NX-ntpc) | 在線設置Nintendo Switch的時鐘(sets the Nintendo Switch's clock appropriately) |
| [lock log](https://github.com/StarDustCFW/Lock-Logs) | 停止向Nintendo發送日誌(stops sending telemetry to Nintendo) |
| [sxos boot.dat](https://sx.xecuter.com) | / |
| [sx autoloader 1.4](https://sx.xecuter.com) | 在桌面直接加載xci相簿遊戲 (auto laod switch xci games on home screen) |
| [syscon](https://github.com/cathery/sys-con) | 無需額外轉接器，即可用usb線連接第三方手柄，etc. ps3 ps4 xbox one xbox360等手柄(sysmodule for third-party controller support with USB connection) |
| [nx-ovlloader](https://github.com/WerWolv/nx-ovlloader) | Host process for loading Switch overlay OVL |
| [tesla menu](https://github.com/WerWolv/Tesla-Menu) | 由nx-ovlloader加載的初始覆蓋菜單 (The initial overlay menu to be loaded by nx-ovlloader) |
| [ovlsysmodule](https://github.com/WerWolv/ovl-sysmodules) | / |
| [sysclk](https://github.com/retronx-team/sys-clk) | 超頻switch (overclock switch) |
