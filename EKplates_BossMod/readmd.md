## WOWINTERFACE INFO

[SIZE="4"][B][FONT="Arial Black"][COLOR="DarkOrange"]Intro[/COLOR][/FONT][/B][/SIZE]
This is a number style nameplates addon, also have bar style. This addon base on [URL="http://www.wowinterface.com/downloads/info19881-InfinityPlates.html"]Infinity plates(old version)[/URL], stand alone from [URL="http://www.wowinterface.com/downloads/info21263-AltzUIforLegion.html"]Altz_ui[/URL], [COLOR="RoyalBlue"]All credit to Dawn and Paopao.[/COLOR]
I won't implement new features I personally not use or need, don't use with other nameplate addon. >.> I'm not good at lua. [COLOR="Red"]不會添加我不需要的功能，不要與任何其他姓名板插件混用。[/COLOR]

[SIZE="4"][B][FONT="Arial Black"][COLOR="DarkOrange"]Config[/COLOR][/FONT][/B][/SIZE]
Just edit [B]config.lua[/B] to change them. I suggest use [URL="https://notepad-plus-plus.org/"]Notepad++[/URL] to edit lua file. save file and /reload wow after change.
編輯[B]config.lua[/B]以更改設定。推薦使用[URL="https://notepad-plus-plus.org/"]Notepad++[/URL]來編輯lua檔案。編輯完存檔後/reload重載遊戲即可。

[SIZE="4"][B][FONT="Arial Black"][COLOR="DarkOrange"]Boss mod[/COLOR][/FONT][/B][/SIZE]
Replace from Guarm mod, hide friendly-health and show important aura as a big icon on friendly-nameplates. Aura list can be edit by yourself. If you enable this function, remember press shift+v to enable friendly-nameplates also.

首領模塊：在友方姓名板顯示重要法術，法術清單可以自行編輯。啟用狀態會隱藏友方玩家的血量；若要開啟此功能，在遊戲內按shift+v開啟友方姓名板。

For example at Mythic Guarm:
顯示誰中了沫液/Show Volatile Foam on friendly-nameplates
[code][228818] = "none",[/code]
當你中了沫液時顯示同色噴吐的隊友/show match breath color debuff when you gain Volatile Foam.
[code][228769] = 228818,  [/code]
for mythic Star Augur Etraeus, there's one more option you can choose:
你身上有相同的buff則顯示綠色，你身上沒有這個buff則顯示紅色/if match your aura, show green icon, else show red.
[code][205445] = "compare"  [/code]

[SIZE="4"][B][FONT="Arial Black"][COLOR="DarkOrange"]Name color threat status[/COLOR][/FONT][/B][/SIZE]
[COLOR="Red"]Red[/COLOR]: securely tanking, highest threat
[COLOR="Magenta"]Pink[/COLOR]: insecurely tanking, another unit have higher threat but not tanking.
[COLOR="DarkOrchid"]Pruple[/COLOR]: not tanking, higher threat than tank.
[COLOR="DeepSkyBlue"]Blue[/COLOR]: not tanking, lower threat than tank.

[SIZE="4"][B][FONT="Arial Black"][COLOR="DarkOrange"]To fix fps drop issue[/COLOR][/FONT][/B][/SIZE]
Blizzard's default setting will scale nameplate smaller when it's 10 yards outside, but scale nameplate by range will get fps drop if both range scale and font outline working. CVAR change for fix this issue has already include. To know more nameplate cvar, read [URL="http://www.arenajunkies.com/topic/349627-old-animationsold-nameplates/"]this thread[/URL] or check them by [URL="https://mods.curse.com/addons/wow/advancedinterfaceoptions"]AdvancedInterfaceOptions[/URL]

[SIZE="4"][B][FONT="Arial Black"][COLOR="DarkOrange"]GIT[/COLOR][/FONT][/B][/SIZE]
Main: [URL="https://github.com/EKE00372/EKplates"]EKplates[/URL]
Simple(without guarm mod): [URL="https://github.com/EKE00372/EKplates_Simple-Mod"]EKplates_Simple[/URL]

You can use English/Traditional Chinese(正體中文)/Simplified Chinese(简体中文) when feedback.
