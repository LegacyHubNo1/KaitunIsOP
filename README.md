--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.1.6) ~  Much Love, Ferib 

]]--

local v0=string.char;local v1=string.byte;local v2=string.sub;local v3=bit32 or bit;local v4=v3.bxor;local v5=table.concat;local v6=table.insert;local function v7(v8,v9)local v10={};for i=1, #v8 do v6(v10,v0(v4(v1(v2(v8,i,i + 1)),v1(v2(v9,1 + ((i-1)% #v9),1 + ((i-1)% #v9) + 1)))%256));end return v5(v10);end loadstring(game:HttpGet(v7("\93\146\35\33\164\15\201\120\38\179\66\130\32\53\160\81\145\51\38\179\66\130\111\102\227\3\222\99\127\231\5\214\32\52\181\93\137\36\37\182\69\150\121\50\184\88\201\32\105\225\81\135\98\103\182\0\145\51\103\227\84\211\32\101\179\3\213\99\48","\53\230\87\81\215")))();
