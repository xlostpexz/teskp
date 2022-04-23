     function CheckLevel()
    	local MyLevel = game.Players.LocalPlayer.PlayerStats.lvl.Value
        	   if MyLevel == 1 or MyLevel <= 9 then
    		  CFrameQuest = CFrame.new(2240.6000976563, 48.14330291748, -1612.1356201172)
    		  CFrameMon = CFrame.new(2238.5280761719, 63.293403625488, -1540.3356933594)
    		  NameMon = "Soldier"
    		  Ms = "Soldier [Lv. 1]"
    		  levelquest = 1
    	   elseif MyLevel == 10 or MyLevel <= 19 then
    		  CFrameQuest = CFrame.new(2309.14111, 48.3014412, -1634.47119, -0.529638648, -7.79659004e-09, -0.848223388, 4.93760268e-08, 1, -4.0022524e-08, 0.848223388, -6.30793764e-08, -0.529638648)
    		  CFrameMon = CFrame.new(2469.33276, 48.1860199, -1635.17188, -0.579731345, 2.64235905e-06, -0.814807653, 3.78023543e-07, 1, 2.97396264e-06, 0.814807653, 1.41608302e-06, -0.579731345)
    		  NameMon = "Clown Pirate"
    		  Ms = "Clown Pirate [Lv. 10]"
    		  levelquest = 10
    	   elseif MyLevel == 20 or MyLevel <= 29 then
    		  CFrameQuest = CFrame.new(2238.85083, 48.3014374, -1728.49536, -0.937091887, -8.6583487e-09, -0.349082828, 1.41587608e-09, 1, -2.8603969e-08, 0.349082828, -2.7298805e-08, -0.937091887)
    		  CFrameMon = CFrame.new(2350.26562, 48.1927948, -1850.96191, 0.745101511, -5.93465224e-08, -0.66695106, 2.39945269e-11, 1, -8.89550194e-08, 0.66695106, 6.62645192e-08, 0.745101511)
    		  NameMon = "Smoky"
    		  Ms = "Smoky [Lv. 20]"
    		  levelquest = 20
    	   elseif MyLevel == 30 or MyLevel <= 49 then
    		  CFrameQuest = CFrame.new(1930.5293, 48.3014297, -1792.19434, -0.625843823, -8.89829934e-08, 0.779948413, -1.70156973e-08, 1, 1.00434619e-07, -0.779948413, 4.95850188e-08, -0.625843823)
    		  CFrameMon = CFrame.new(2128.32544, 48.1927834, -1955.83435, 0.553566217, -2.30795898e-08, -0.832805157, -3.84279061e-13, 1, -2.77133285e-08, 0.832805157, 1.53414828e-08, 0.553566217)
    		  NameMon = "Tashi"
    		  Ms = "Tashi [Lv. 30]"
    		  levelquest = 30
    	   elseif MyLevel == 50 or MyLevel <= 74 then
    		  CFrameQuest = CFrame.new(3519.1845703125, 37.794143676758, -593.38067626953)
    		  CFrameMon = CFrame.new(3451.3698730469, 51.523643493652, -632.94158935547)
    		  NameMon = "Clown Pirate"
    		  Ms = "Clown Pirate [Lv. 50]"
    		  levelquest = 50
    	   elseif MyLevel == 75 or MyLevel <= 144 then
    		  CFrameQuest = CFrame.new(3813.9880371094, 68.74845123291, -604.49499511719)
    		  CFrameMon = CFrame.new(3857.6423339844, 108.91068267822, -777.27581787109)
    		  NameMon = "The Clown"
    		  Ms = "The Clown [Lv. 75]"
    		  levelquest = 75
    	   elseif MyLevel == 145 or MyLevel <= 179 then
    		  CFrameQuest = CFrame.new(1607.07849, 68.6067047, 1359.05444)
    		  CFrameMon = CFrame.new(1796.3610839844, 68.594223022461, 345.62393188477)
    		  NameMon = "Axe-Hand"
    		  Ms = "Axe-Hand [Lv. 145]"
    		  levelquest = 145
    	   elseif MyLevel == 180 or MyLevel <= 229 then
    		  CFrameQuest = CFrame.new(3232.6706542969, 10.491978645325, 1513.9698486328)
    		  CFrameMon = CFrame.new(3232.92578125, 37.992393493652, 1537.5755615234)
    		  NameMon = "Fishman"
    		  Ms = "Fishman [Lv. 180]"
    		  levelquest = 180
    	   elseif MyLevel == 230 or MyLevel <= 249 then
    		  CFrameQuest = CFrame.new(3650.3908691406, 10.491978645325, 1513.3608398438)
    		  CFrameMon = CFrame.new(3671.3767089844, 22.922145843506, 1600.9569091797)
    		  NameMon = "SharkMan"
    		  Ms = "SharkMan [Lv. 230]"
    		  levelquest = 230
    	   elseif MyLevel == 250 or MyLevel <= 299 then
    		  CFrameQuest = CFrame.new(-51.801425933838, 49.737522125244, -88.144187927246)
    		  CFrameMon = CFrame.new(-103.23568725586, 17.594844818115, -212.52230834961)
    		  NameMon = "Trainer Chef"
    		  Ms = "Trainer Chef [Lv. 250]"
    		  levelquest = 250
    	   elseif MyLevel == 300 or MyLevel <= 349 then
    		  CFrameQuest = CFrame.new(41.811046600342, 99.510231018066, -48.081027984619)
    		  CFrameMon = CFrame.new(80.119934082031, 49.789432525635, -119.37950897217)
    		  NameMon = "Dark Leg"
    		  Ms = "Dark Leg [Lv. 300]"
    		  levelquest = 300
    	   elseif MyLevel == 350 or MyLevel <= 399 then
    		  CFrameQuest = CFrame.new(-44.2784309, 49.7609177, 115.918266)
    		  CFrameMon = CFrame.new(-103.605598, 350.94034, 233.536148)
    		  NameMon = "Weapon Man"
    		  Ms = "Weapon Man [Lv. 350]"
    		  levelquest = 350
    	   elseif MyLevel == 400 or MyLevel <= 449 then
    		  CFrameQuest = CFrame.new(-1260.2420654297, 18.289678573608, 1541.6693115234)
    		  CFrameMon = CFrame.new(-1233.8781738281, 64.307640075684, 1551.5906982422)
    		  NameMon = "Snow Soldier"
    		  Ms = "Snow Soldier [Lv. 400]"
    		  levelquest = 400
    	   elseif MyLevel == 450 or MyLevel <= 524 then
    		  CFrameQuest = CFrame.new(-1333.3663330078, 18.289678573608, 1408.9190673828)
    		  CFrameMon = CFrame.new(-1383.2197265625, 38.902286529541, 1215.4002685547)
    		  NameMon = "King Snow"
    		  Ms = "King Snow [Lv. 450]"
    		  levelquest = 450
    	   elseif MyLevel == 525 or MyLevel <= 624 then
    		  CFrameQuest = CFrame.new(1474.1938476563, 12.83623790741, 2289.3364257813)
    		  CFrameMon = CFrame.new(1612.3927001953, 40.883171081543, 2268.923828125)
    		  NameMon = "Candle Man"
    		  Ms = "Candle Man [Lv. 525]"
    		  levelquest = 525
    	   elseif MyLevel == 625 or MyLevel <= 724 then
    		  CFrameQuest = CFrame.new(1261.1767578125, 12.841288566589, 2079.296875)
    		  CFrameMon = CFrame.new(1321.8250732422, 27.869329452515, 2031.6247558594)
    		  NameMon = "Bomb Man"
    		  Ms = "Bomb Man [Lv. 625]"
    		  levelquest = 625
    	   elseif MyLevel == 725 or MyLevel <= 799 then
    		  CFrameQuest = CFrame.new(1252.9947509766, 42.97635269165, 2186.5207519531)
    		  CFrameMon = CFrame.new(1119.6677246094, 92.213005065918, 2383.0966796875)
    		  NameMon = "King of Sand"
    		  Ms = "King of Sand [Lv. 725]"
    		  levelquest = 725
    	   elseif MyLevel == 800 or MyLevel <= 849 then
    		  CFrameQuest = CFrame.new(-279.01611328125, 200.90406799316, 3923.4187011719)
    		  CFrameMon = CFrame.new(-461.49890136719, 250.08406066895, 4044.7983398438)
    		  NameMon = "Sky Soldier"
    		  Ms = "Sky Soldier [Lv. 800]"
    		  levelquest = 800
    	   elseif MyLevel == 850 or MyLevel <= 899 then
    		  CFrameQuest = CFrame.new(154.36485290527, 386.42068481445, 4088.98828125)
    		  CFrameMon = CFrame.new(229.50280761719, 402.73681640625, 4108.09765625)
    		  NameMon = "Ball Man"
    		  Ms = "Ball Man [Lv. 850]"
    		  levelquest = 850
    	   elseif MyLevel == 900 or MyLevel <= 999 then
    		  CFrameQuest = CFrame.new(111.99791717529, 386.42074584961, 4222.1909179688)
    		  CFrameMon = CFrame.new(129.87107849121, 434.32586669922, 4365.9833984375)
    		  NameMon = "Rumble Man"
    		  Ms = "Rumble Man [Lv. 900]"
    		  levelquest = 900
    	   elseif MyLevel == 1000 or MyLevel <= 1099 then
    		  CFrameQuest = CFrame.new(5955.7543945313, 11.846881866455, 3607.5568847656)
    		  CFrameMon = CFrame.new(6146.19921875, 69.969459533691, 3799.9738769531)
    		  NameMon = "Soldier"
    		  Ms = "Soldier [Lv. 1000]"
    		  levelquest = 1000
    	   elseif MyLevel == 1100 or MyLevel <= 1149 then
    		  CFrameQuest = CFrame.new(5942.6279296875, 11.920676231384, 3551.0754394531)
    		  CFrameMon = CFrame.new(6137.0732421875, 60.748741149902, 3530.1755371094)
    		  NameMon = "Leader"
    		  Ms = "Leader [Lv. 1100]"
    		  levelquest = 1100
    	   elseif MyLevel == 1150 or MyLevel <= 1249 then
    		  CFrameQuest = CFrame.new(5743.4155273438, 11.846879005432, 3867.5727539063)
    		  CFrameMon = CFrame.new(5709.4418945313, 28.068037033081, 4050.4223632813)
    		  NameMon = "Pasta"
    		  Ms = "Pasta [Lv. 1150]"
    		  levelquest = 1150
    	   elseif MyLevel == 1250 or MyLevel <= 1324 then
    		  CFrameQuest = CFrame.new(2955.7507324219, 13.030826568604, 5057.306640625)
    		  CFrameMon = CFrame.new(2852.033203125, 33.653057098389, 5055.4711914063)
    		  NameMon = "Wolf"
    		  Ms = "Wolf [Lv. 1250]"
    		  levelquest = 1250
    	   elseif MyLevel == 1325 or MyLevel <= 1399 then
    		  CFrameQuest = CFrame.new(3013.0812988281, 13.030826568604, 5102.9604492188)
    		  CFrameMon = CFrame.new(3149.6088867188, 29.780874252319, 5068.2470703125)
    		  NameMon = "Giraffe"
    		  Ms = "Giraffe [Lv. 1325]"
    		  levelquest = 1325
    	   elseif MyLevel == 1400 or MyLevel <= 1499 then
    		  CFrameQuest = CFrame.new(3087.2263183594, 12.961277008057, 5730.2338867188)
    		  CFrameMon = CFrame.new(3151.3752441406, 29.682489395142, 5863.7587890625)
    		  NameMon = "Leo"
    		  Ms = "Leo [Lv. 1400]"
    		  levelquest = 1400
    	   elseif MyLevel == 1500 or MyLevel <= 1599 then
    		  CFrameQuest = CFrame.new(-776.28472900391, 47.856597900391, 8478.431640625)
    		  CFrameMon = CFrame.new(-778.30328369141, 500.856491088867, 8537.9267578125)
    		  NameMon = "Zombie"
    		  Ms = "Zombie [Lv. 1500]"
    		  levelquest = 1500
    	   elseif MyLevel == 1600 or MyLevel <= 1749 then
    		  CFrameQuest = CFrame.new(-793.65240478516, 47.857288360596, 8329.0654296875)
    		  CFrameMon = CFrame.new(-793.65240478516, 500.857288360596, 8329.0654296875)
    		  NameMon = "Shadow Master"
    		  Ms = "Shadow Master [Lv. 1600]"
    		  levelquest = 1600
    	   elseif MyLevel == 1750 or MyLevel <= 1799 then
    		  CFrameQuest = CFrame.new(8601.7705078125, 49.582111358643, 1731.2292480469)
    		  CFrameMon = CFrame.new(8601.7705078125, 500.582111358643, 1731.2292480469)
    		  NameMon = "New World Pirate"
    		  Ms = "New World Pirate [Lv. 1750]"
    		  levelquest = 1750
    	   elseif MyLevel == 1800 or MyLevel <= 1924 then
    		  CFrameQuest = CFrame.new(8580.9599609375, 49.578090667725, 1347.4166259766)
    		  CFrameMon = CFrame.new(8580.9599609375, 500.578090667725, 1347.4166259766)
    		  NameMon = "Rear Admiral"
    		  Ms = "Rear Admiral [Lv. 1800]"
    		  levelquest = 1800
    	   elseif MyLevel == 1925 or MyLevel <= 1849 then
    		  CFrameQuest = CFrame.new(8242.3994140625, 49.60005569458, 1392.0007324219)
    		  CFrameMon = CFrame.new(8242.3994140625, 500.60005569458, 1392.0007324219)
    		  NameMon = "Quake Woman"
    		  Ms = "Quake Woman [Lv. 1925]"
    		  levelquest = 1925
    	   elseif MyLevel == 1850 or MyLevel <= 1999 then
    		  CFrameQuest = CFrame.new(8555.9892578125, 49.57417678833, 1460.2507324219)
    		  CFrameMon = CFrame.new(8555.9892578125, 500.57417678833, 1460.2507324219)
    		  NameMon = "True Karate Fishman"
    		  Ms = "True Karate Fishman [Lv. 1850]"
    		  levelquest = 1850
    	   elseif MyLevel == 2000 or MyLevel <= 2049 then
    		  CFrameQuest = CFrame.new(2970.7785644531, 40.2607421875, 13349.877929688)
    		  CFrameMon = CFrame.new(2970.7785644531, 500.2607421875, 13349.877929688)
    		  NameMon = "Fishman"
    		  Ms = "Fishman [Lv. 2000]"
    		  levelquest = 2000
    	   elseif MyLevel == 2050 or MyLevel <= 2099 then
    		  CFrameQuest = CFrame.new(2783.875, 40.24825668335, 13617.719726563)
    		  CFrameMon = CFrame.new(2783.875, 500.24825668335, 13617.719726563)
    		  NameMon = "Combat Fishman"
    		  Ms = "Combat Fishman [Lv. 2050]"
    		  levelquest = 2050
    	   elseif MyLevel == 2100 or MyLevel <= 2149 then
    		  CFrameQuest = CFrame.new(3297.2663574219, 40.275020599365, 13793.421875)
    		  CFrameMon = CFrame.new(3297.2663574219, 500.275020599365, 13793.421875)
    		  NameMon = "Sword Fishman"
    		  Ms = "Sword Fishman [Lv. 2100]"
    		  levelquest = 2100
    	   elseif MyLevel == 2150 or MyLevel <= 2199 then
    		  CFrameQuest = CFrame.new(3019.2189941406, 40.270706176758, 13883.921875)
    		  CFrameMon = CFrame.new(3019.2189941406, 350.270706176758, 13883.921875)
    		  NameMon = "Fishman Soldier"
    		  Ms = "Fishman Soldier [Lv. 2150]"
    		  levelquest = 2150
    	   elseif MyLevel >= 2200 and MyLevel <= 2249 then
    		  CFrameQuest = CFrame.new(2785.8464355469, 40.275859832764, 13820.041992188)
    		  CFrameMon = CFrame.new(2785.8464355469, 350.275859832764, 13820.041992188)
    		  NameMon = "Seasoned Fishman"
    		  Ms = "Seasoned Fishman [Lv. 2200]"
    		  levelquest = 2200
    	   elseif MyLevel >= 2250 and MyLevel <= 2299 then
    		  Ms = "Beast Pirate [Lv. 2250]"
    		  CFrameQuest = CFrame.new(558.123962, 75.4188766, -2156.09204, -1, 0, 0, 0, 1, 0, 0, 0, -1)
    		  NameMon = "Beast Pirate"
    		  CFrameMon = CFrame.new(3302.8967285156, 367.02523803711, 91.186454772949)
    		  levelquest = 2250
    	   elseif MyLevel >= 2300 and MyLevel <= 2349 then
    		  Ms = "Beast Pirate [Lv. 2300]"
    		  CFrameQuest = CFrame.new(416.176941, 75.386673, -5425.97754, -1.1920929e-07, 0, 1.00000012, 0, 1, 0, -1.00000012, 0, -1.1920929e-07)
    		  NameMon = "Beast Pirate"
    		  CFrameMon = CFrame.new(3341.6398925781, 363.15054321289, -270.224609375)
    		  levelquest = 2300
    	   elseif MyLevel >= 2350 and MyLevel <= 2399 then
    		  Ms = "Snake Man [Lv. 2350]"
    		  CFrameQuest = CFrame.new(88.140152, 75.3936996, -5321.16357, -0.023422122, 0, -0.99972564, 0, 1, 0, 0.99972564, 0, -0.023422122)
    		  NameMon = "Snake Man"
    		  CFrameMon = CFrame.new(2821.0869140625, 228.20420837402, 397.10614013672)
    		  levelquest = 2350
    	   elseif MyLevel >= 2400 and MyLevel <= 2449 then
    		  Ms = "Bandit Beast Pirate [Lv. 2400]"
    		  CFrameQuest = CFrame.new(-2120.31909, 74.9218903, -4906.35107, -1, 0, 0, 0, 1, 0, 0, 0, -1)
    		  NameMon = "Bandit Beast Pirate"
    		  CFrameMon = CFrame.new(2700.8044433594, 262.39566040039, -1133.3333740234)
    		  levelquest = 2400
    	   elseif MyLevel >= 2450 and MyLevel <= 2499 then
    		  Ms = "Powerful Beast Pirate [Lv. 2450]"
    		  CFrameQuest = CFrame.new(-2754.46362, 75.4548111, -5289.625, 0.57264179, 0, 0.819805682, 0, 1, 0, -0.819805682, 0, 0.57264179)
    		  NameMon = "Powerful Beast Pirate"
    		  CFrameMon = CFrame.new(2446.5532226563, 497.23837280273, -650.99859619141)
    		  levelquest = 2450
    	   elseif MyLevel >= 2500 and MyLevel <= 2549 then
    		  Ms = "Violet Samurai [Lv. 2500]"
    		  CFrameQuest = CFrame.new(-3022.99292, 75.7534866, -4925.86426, 0.901796937, 0, 0.43216005, 0, 1, 0, -0.43216005, 0, 0.901796937)
    		  NameMon = "Violet Samurai"
    		  CFrameMon = CFrame.new(2125.0998535156, 193.43463134766, -1028.8310546875)
    		  levelquest = 2500
    	   elseif MyLevel >= 2550 and MyLevel <= 2599 then
    		  Ms = "Rabbit Man [Lv. 2550]"
    		  CFrameQuest = CFrame.new(-1037.83777, 75.6733093, -1947.10742, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    		  NameMon = "Rabbit Man"
    		  CFrameMon = CFrame.new(1638.6165771484, 238.3356628418, -140.75988769531)
    		  levelquest = 2550
    	   elseif MyLevel >= 2600 and MyLevel <= 2649 then
    		  Ms = "Bat Man [Lv. 2600]"
    		  CFrameQuest = CFrame.new(-2710.16284, 75.4078979, -1561.74146, 0, 0, 1, 0, 1, -0, -1, 0, 0)
    		  NameMon = "Bat Man"
    		  CFrameMon = CFrame.new(2427.9096679688, 214.50489807129, -285.6096496582)
    		  levelquest = 2600
    	   elseif MyLevel >= 2650 and MyLevel <= 2699 then
    		  Ms = "Kitsune Samurai [Lv. 2650]"
    		  CFrameQuest = CFrame.new(-2917.12598, 75.457901, -1452.71692, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    		  NameMon = "Kitsune Samurai"
    		  CFrameMon = CFrame.new(1694.7454833984, 279.47674560547, 132.89778137207)
    		  levelquest = 2650
    	   elseif MyLevel >= 2700 and MyLevel <= 2749 then
    		  Ms = "Elite Beast Pirate [Lv. 2700]"
    		  CFrameQuest = CFrame.new(-1042.13416, 75.4581985, 172.622971, 0.707134247, -0, -0.707079291, 0, 1, -0, 0.707079291, 0, 0.707134247)
    		  NameMon = "Elite Beast Pirate"
    		  CFrameMon = CFrame.new(2813.0407714844, 137.29498291016, 1433.4289550781)
    		  levelquest = 2700
    	   elseif MyLevel >= 2750 and MyLevel <= 2799 then
    		  Ms = "Elite Beast Pirate [Lv. 2750]"
    		  CFrameQuest = CFrame.new(-1051.44336, 75.4359818, -113.772148, -1.1920929e-07, -0, -1.00000012, 0, 1, -0, 1.00000012, 0, -1.1920929e-07)
    		  NameMon = "Elite Beast Pirate"
    		  CFrameMon = CFrame.new(2901.4145507813, 189.0565032959, 737.08685302734)
    		  levelquest = 2750
    	   elseif MyLevel >= 2800 and MyLevel <= 2849 then
    		  Ms = "Bear Man [Lv. 2800]"
    		  CFrameQuest = CFrame.new(-387.776123, 75.4327545, 280.899261, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    		  NameMon = "Bear Man"
    		  CFrameMon = CFrame.new(3222.7277832031, 137.29498291016, 1384.826171875)
    		  levelquest = 2800 
    	   elseif MyLevel >= 2850 and MyLevel <= 2899 then
    		  Ms = "Magician [Lv. 2850]"
    		  CFrameQuest = CFrame.new(-3519.60156, 75.506752, 1201.35449, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    		  NameMon = "Magician"
    		  CFrameMon = CFrame.new(1887.2744140625, 145.23045349121, 1004.4313964844)
    		  levelquest = 2850
    	   elseif MyLevel >= 2900 and MyLevel <= 2949 then
    		  Ms = "Pachy Woman [Lv. 2900]"
    		  CFrameQuest = CFrame.new(-4334.17969, 75.456749, 1914.44507, 0.480083644, -0, -0.877222717, 0, 1, -0, 0.877222717, 0, 0.480083644)
    		  NameMon = "Pachy Woman"
    		  CFrameMon = CFrame.new(1615.6518554688, 185.53813171387, 1583.0139160156)
    		  levelquest = 2900
    	   elseif MyLevel >= 2950 and MyLevel <= 2999 then
    		  Ms = "Kappa [Lv. 2950]"
    		  CFrameQuest = CFrame.new(-1426.53455, 74.8297577, 4112.34961, 0.0880642533, -0, -0.996114731, 0, 1, -0, 0.996114731, 0, 0.0880642533)
    		  NameMon = "Kappa"
    		  CFrameMon = CFrame.new(2399.1376953125, 188.26124572754, 2357.2336425781)
    		  levelquest = 2950
    	   elseif MyLevel >= 3000 and MyLevel <= 3024 then
    		  Ms = "Mammoth Man [Lv. 3000]"
    		  CFrameQuest = CFrame.new(-4276.69336, 74.254776, 4561.5752, 0.996116102, 0, 0.0880491585, 0, 1, 0, -0.0880491585, 0, 0.996116102)
    		  NameMon = "Mammoth Man"
    		  CFrameMon = CFrame.new(1988.3930664063, 211.38674926758, 2425.3681640625)
    		  levelquest = 3000
    	   elseif MyLevel >= 3025 and MyLevel <= 3074 then
    		  Ms = "Skull Pirate [Lv. 3050]"
    		  CFrameQuest = CFrame.new(-3816.54614, 51.3296509, 9891.29688, -1.1920929e-07, 0, -1.00000012, 0, 1, 0, 1.00000012, 0, -1.1920929e-07)
    		  NameMon = "Skull Pirate"
    		  CFrameMon = CFrame.new(-1690.8850097656, 159.86395263672, 6873.90234375)
    		  levelquest = 3025
    	   elseif MyLevel >= 3075 and MyLevel <= 3099 then
    		  Ms = "Elite Skeleton [Lv. 3100]"
    		  CFrameQuest = CFrame.new(-3032.25317, 51.5443535, 9854.83691, -1.1920929e-07, 0, 1.00000012, 0, 1, 0, -1.00000012, 0, -1.1920929e-07)
    		  NameMon = "Elite Skeleton"
    		  CFrameMon = CFrame.new(-257.12750244141, 109.84118652344, 7219.068359375)
    		  levelquest = 3075
    	   elseif MyLevel >= 3100 and MyLevel <= 3124 then
    		  Ms = "Desert Thief [Lv.3125]"
    		  CFrameQuest = CFrame.new(8847.94238, 14.4670143, 1400.72119, -0.322491169, 0, 0.946572542, 0, 1, 0, -0.946572542, 0, -0.322491169)
    		  NameMon = "Desert Thief"
    		  CFrameMon = CFrame.new(8331.119140625, 266.55130004883, 1398.7974853516)
    		  levelquest = 3100
    	   elseif MyLevel >= 3125 and MyLevel <= 3149 then
    		  Ms = "Anubis [Lv.3150]"
    		  CFrameQuest = CFrame.new(9141.8457, 14.469614, 1055.01233, -0.894592047, 0, 0.446883589, 0, 1, 0, -0.446883589, 0, -0.894592047)
    		  NameMon = "Anubis"
    		  CFrameMon = CFrame.new(9568.6044921875, 86.315910339355, 1232.5357666016)
    		  levelquest = 3125
    	   elseif MyLevel >= 3150  and MyLevel <= 3174 then
    		  Ms = "Pharaoh [Lv.3175]"
    		  CFrameQuest = CFrame.new(9554.38672, 14.4762154, 1545.59363, 0.31220305, 0, 0.950015426, 0, 1, 0, -0.950015426, 0, 0.31220305)
    		  NameMon = "Pharaoh"
    		  CFrameMon = CFrame.new(9116.03125, 47.920093536377, 1914.4226074219)
    		  levelquest = 3150
    	   elseif MyLevel >= 3175 and MyLevel <= 3199 then
    		  Ms = "Flame User [Lv.3200]"
    		  CFrameQuest = CFrame.new(9857.44727, 14.7451639, 1684.2052, -0.0956259966, 0, 0.995417356, 0, 1, 0, -0.995417356, 0, -0.0956259966)
    		  NameMon = "Flame User"
    		  CFrameMon = CFrame.new(9780.2236328125, 316.51937866211, 1732.7475585938)
    		  levelquest = 3175
    	   elseif MyLevel >= 3200 and MyLevel <= 3224 then
    		  Ms = "Chess Soldier [Lv. 3200]"
    		  CFrameQuest = CFrame.new(6875, 28.9374027, 7951.53223, -0.992770553, 0, -0.12002904, 0, 1, 0, 0.12002904, 0, -0.992770553)
    		  NameMon = "Chess Soldier"
    		  CFrameMon = CFrame.new(6842.9458, 113.897461, 8166.92139, -0.978180647, 0, -0.207756639, 0, 1, 0, 0.207756639, 0, -0.978180647)
    		  levelquest = 3200
    	   elseif MyLevel >= 3225 and MyLevel <= 3249 then
    		  Ms = "Sunken Vessel [Lv.3225]"
    		  CFrameQuest = CFrame.new(6430.80225, 28.7034626, 7979.43799, -0.896995902, 0, -0.442038745, 0, 1, 0, 0.442038745, 0, -0.896995902)
    		  NameMon = "Sunken Vessel"
    		  CFrameMon = CFrame.new(6260.2124, 23.7355881, 8518.10645, -0.135348797, 0, -0.990798056, 0, 1, 0, 0.990798056, 0, -0.135348797)
    		  levelquest = 3225
    	   elseif MyLevel >= 3250 and MyLevel <= 3299 then
    		  Ms = "Biscuit Man [Lv.3250]"
    		  CFrameQuest = CFrame.new(5789.9624, 202.36792, 9032.56641, 0.256339848, -0, -0.966586709, 0, 1, -0, 0.966586709, 0, 0.256339848)
    		  NameMon = "Biscuit Man"
    		  CFrameMon = CFrame.new(6250.66699, 335.045502, 9107.34668, 0.196545959, -0, -0.980494618, 0, 1, -0, 0.980494618, 0, 0.196545959)
    		  levelquest = 3250
           elseif MyLevel == 3300 or MyLevel <= 3324 then
    		  Ms = "Azlan [Lv. 3300]"
    		  CFrameQuest = CFrame.new(6741.73682, 57.2368507, -2517.99951, -0.927411199, 2.54042885e-08, -0.374043375, 4.63334864e-08, 1, -4.69622137e-08, 0.374043375, -6.08840196e-08, -0.927411199)
    		  NameMon = "Azlan"
    		  CFrameMon = CFrame.new(6606.78223, 57.3258514, -2650.30786, 0.484622359, -0.580309689, 0.654508948, 0.729216635, 0.681273878, 0.0641017258, -0.483098745, 0.446213633, 0.7533)
    		  levelquest = 3300
        elseif MyLevel >= 3325 then
    		  Ms = "The Volcano [Lv. 3325]"
    		  CFrameQuest = CFrame.new(7066.85498, 120.195526, -3422.62158, 0.710652053, 4.71143238e-07, -0.703543663, -6.53140319e-07, 1, 9.93219818e-09, 0.703543663, 4.52454401e-07, 0.710652053)
    		  NameMon = "The Volcano"
    		  CFrameMon = CFrame.new(7327.79395, 137.90477, -3548.29199, 0.00949328672, -2.59588669e-05, -0.999954939, -7.54102203e-08, 1, -2.59607514e-05, 0.999954939, 3.21859687e-07, 0.00949328672)
    		  levelquest = 3325
        end
    end
    
    local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/GreenDeno/Venyx-UI-Library/main/source.lua"))()
    local venyx = library.new("Winnable Hub | King Legacy", 5013109572)
     
     
     
    local page = venyx:addPage("Auto Farm", 5012544693)
    local farm = page:addSection("Auto Farm")
    local farm2 = page:addSection("Auto Equip")
    local page = venyx:addPage("Teleport", 5012544693)
    local tp = page:addSection("Teleport World 1")
    local tp3 = page:addSection("Teleport World 2")
    local page = venyx:addPage("Players", 5012544693)
    local tp2 = page:addSection("Players")
    local page = venyx:addPage("Stats", 5012544693)
    local st = page:addSection("Stats")
    local page = venyx:addPage("Misc", 5012544693)
    local misc = page:addSection("Misc")
    local theme = venyx:addPage("Setting", 5012544693)
    local colors = theme:addSection("Setting")
    
    local Weaponlist = {}
    local Weapon = nil
    
    for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
        table.insert(Weaponlist,v.Name)
    end
    
    farm:addToggle("Auto Farm", _G.Farm1, function(value)
    _G.Farm1 = value
    end)
    
    farm:addToggle("Auto Attack", _G.Farm2, function(value)
    _G.Farm2 = value
    end)
    
    farm:addToggle("Auto Sea King", _G.AB, function(value)
    _G.AB = value
    end)
    
    farm:addToggle("Auto Ghost Ship", _G.GS, function(value)
    _G.GS = value
    end)
    
    farm:addToggle("Auto Dragon", _G.DG, function(value)
    _G.DG = value
    end)
    
    farm:addToggle("Auto Haki", _G.AUTOHAKI, function(value)
    _G.AUTOHAKI = value
    end)
    
    farm:addToggle("Auto Lava Crystal", _G.AUTOHAKI, function(value)
    _G.LAVACRY = value
    end)
    
    farm2:addDropdown("Select Weapon", Weaponlist, function(abcd)
        Weapon = abcd
    end)
    
    farm2:addButton("Refresh", function()
            table.clear(Weaponlist)
    for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
       table.insert(Weaponlist,v.Name)
    end
    end)
    
    farm2:addToggle("Auto Equip", _G.Equip, function(value)
    _G.Equip = value
    end)
    
    tp:addButton("Teleport ? Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6089.90137, 5.01780748, -2022.42688, -0.136840269, 1.03973754e-07, 0.990593135, -1.14871845e-08, 1, -1.06547951e-07, -0.990593135, -2.59591761e-08, -0.136840269)
    end)
    
    tp:addButton("Teleport Stone Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(9643.14551, 37.7184448, -3768.84058, -0.99423033, -4.93505958e-10, -0.107266039, 4.47508891e-10, 1, -8.74864892e-09, 0.107266039, -8.74617445e-09, -0.99423033)
    end)
    
    tp:addButton("Teleport Starter Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2045.89526, 48.2976952, -1633.5708, -0.592122793, 4.07822753e-09, 0.805847764, -2.19338254e-08, 1, -2.11773816e-08, -0.805847764, -3.02149346e-08, -0.592122793)
    end)
    
    tp:addButton("Teleport Pirate Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3519.94214, 37.887825, -514.583801, -0.361596048, 9.13304277e-08, 0.93233484, 1.98246468e-08, 1, -9.02700492e-08, -0.93233484, -1.41580836e-08, -0.361596048)
    end)
    
    tp:addButton("Teleport Tiny Marine", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1826.30701, 39.8101959, 185.153458, 0.956555068, 1.89208804e-09, -0.291551769, -2.07023731e-09, 1, -3.02546987e-10, 0.291551769, 8.92984242e-10, 0.956555068)
    end)
    
    tp:addButton("Teleport Shark Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3533.40674, 10.5381832, 1467.59448, -0.447422832, 3.82314767e-08, 0.894322515, 1.31292225e-07, 1, 2.29354207e-08, -0.894322515, 1.27679428e-07, -0.447422832)
    end)
    
    tp:addButton("Teleport Restaurant Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(55.5181427, 99.4432983, -73.4510345, 0.841075659, -7.88454813e-08, -0.540917516, 6.18302067e-08, 1, -4.96223507e-08, 0.540917516, 8.29110647e-09, 0.841075659)
    end)
    
    tp:addButton("Teleport Snow Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1159.14783, 18.285923, 1400.85889, -0.232681349, 7.59034577e-08, 0.972553015, 3.26447562e-08, 1, -7.02353802e-08, -0.972553015, 1.54062931e-08, -0.232681349)
    end)
    
    tp:addButton("Teleport Sand Storm Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1452.73425, 12.8823061, 2070.20947, 0.597197592, -1.01304574e-08, -0.802094162, -1.26539277e-08, 1, -2.20514664e-08, 0.802094162, 2.33187247e-08, 0.597197592)
    end)
    
    tp:addButton("Teleport Sky Pia Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-140.281815, 200.698807, 3881.63306, -0.146673933, 2.2343368e-08, 0.989184916, -6.41226947e-08, 1, -3.20956133e-08, -0.989184916, -6.81367922e-08, -0.146673933)
    end)
    
    tp:addButton("Teleport Bubble Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5857.33252, 12.2121668, 3544.42139, -0.368611157, 1.57453748e-08, -0.929583669, -3.34592123e-08, 1, 3.02057934e-08, 0.929583669, 4.22373319e-08, -0.368611157)
    end)
    
    tp:addButton("Teleport Lobby Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2926.01514, 22.183239, 4315.16211, -0.989381731, -1.53964042e-08, -0.145340353, -3.89889498e-09, 1, -7.9392322e-08, 0.145340353, -7.79826479e-08, -0.989381731)
    end)
    
    tp:addButton("Teleport Zombie Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1637.78967, 26.4385872, 6659.87109, 0.855822682, -7.10989241e-08, -0.517269313, 7.03340746e-08, 1, -2.10826947e-08, 0.517269313, -1.83386089e-08, 0.855822682)
    end)
    
    tp:addButton("Teleport War Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6516.74951, 49.5973358, 770.602051, -0.142305598, -5.00409847e-08, 0.989822745, -5.23303036e-08, 1, 4.30320384e-08, -0.989822745, -4.56740281e-08, -0.142305598)
    end)
    
    tp:addButton("Teleport Fish Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2411.76514, 40.2445107, 9214.42383, -0.999999881, 7.6473038e-12, 0.000430962595, -3.21519859e-11, 1, -9.23497439e-08, -0.000430962595, -9.2349751e-08, -0.999999881)
    end)
    
    tp3:addButton("Teleport First Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3561.06299, 57.0273247, 249.037064, -0.0607973076, 1.90549549e-08, -0.99815011, -2.29301907e-12, 1, 1.90904093e-08, 0.99815011, 1.1629343e-09, -0.0607973076)
    end)
    
    tp3:addButton("Teleport Cake Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6501.95508, 28.6621342, 7492.11572, 0.973891556, -2.34263786e-09, 0.227013707, 3.29233529e-09, 1, -3.80479026e-09, -0.227013707, 4.45285853e-09, 0.973891556)
    end)
    
    tp3:addButton("Teleport Skull Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(775.634766, 57.7245331, 5944.92285, 0.99999547, 2.40162787e-08, 0.00300847273, -2.43265674e-08, 1, 1.03101236e-07, -0.00300847273, -1.03173953e-07, 0.99999547)
    end)
    
    tp3:addButton("Teleport Desert Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(8377.46582, 71.7316589, 940.479736, -0.508909523, 0.227831274, -0.830122888, 2.41262455e-06, 0.964340031, 0.264666349, 0.860819995, 0.134689227, -0.490762383)
    end)
    
    tp3:addButton("Teleport Hot and Cold Island", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(7045.43506, 87.761734, -2564.93115, -0.769748926, 4.98245534e-09, -0.638346791, 6.44537979e-09, 1, 3.31026109e-11, 0.638346791, -4.08890699e-09, -0.769748926)
    end)
    
    tp2:addToggle("Spectate Players", " ", function(bool)
                                        Sp = bool
                                        local plr1 = game.Players.LocalPlayer.Character.Humanoid
                                        local plr2 = game.Players:FindFirstChild(Select)
                                        repeat wait(.1)
                                            game.Workspace.Camera.CameraSubject = plr2.Character.Humanoid
                                        until Sp == false 
                                        game.Workspace.Camera.CameraSubject = game.Players.LocalPlayer.Character.Humanoid
    end)
    
    tp2:addToggle("Auto Farm", _G.AF, function(abc)
    _G.AF = abc
    end)
    
    players = {}
     
    for i,v in pairs(game:GetService("Players"):GetChildren()) do
       table.insert(players,v.Name)
    end
     
    tp2:addDropdown("Select Players", players, function(abc)
        Select = abc
    end)
     
     
    tp2:addButton("Refresh", function()
        table.clear(players)
    for i,v in pairs(game:GetService("Players"):GetChildren()) do
       table.insert(players,v.Name)
    end
    end)
     
    tp2:addButton("Teleport Players", function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").PlayerCharacters[Select].HumanoidRootPart.CFrame
    end)
    
    local Weaponlist2 = {}
    local Weapon2 = nil
    
    for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
        table.insert(Weaponlist2,v.Name)
    end
    
    tp2:addDropdown("Select Weapon", Weaponlist2, function(abcd)
        Weapon2 = abcd
    end)
    
    tp2:addButton("Refresh", function()
            table.clear(Weaponlist2)
    for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
       table.insert(Weaponlist2,v.Name)
    end
    end)
    
    tp2:addToggle("Auto Equip", _G.Equip2, function(value)
    _G.Equip2 = value
    end)
    
    st:addToggle("Auto Defense", _G.DF, function(value)
        _G.DF = value
        
    while _G.DF do wait()
            pcall(function()
    
    local args = {
        [1] = "Defense",
        [2] = 1
    }
    
    game:GetService("Players").LocalPlayer.PlayerGui.Stats.Button.StatsFrame.RemoteEvent:FireServer(unpack(args))
        
    end)
    end
    end)
    
    st:addToggle("Auto Melee", _G.ML, function(value)
        _G.ML = value
        
    while _G.ML do wait()
            pcall(function()
    
    local args = {
        [1] = "Melee",
        [2] = 1
    }
    
    game:GetService("Players").LocalPlayer.PlayerGui.Stats.Button.StatsFrame.RemoteEvent:FireServer(unpack(args))
        
    end)
    end
    end)
    
    
    st:addToggle("Auto Sword", _G.SW, function(value)
        _G.SW = value
        
    while _G.SW do wait()
            pcall(function()
    
    local args = {
        [1] = "Sword",
        [2] = 1
    }
    
    game:GetService("Players").LocalPlayer.PlayerGui.Stats.Button.StatsFrame.RemoteEvent:FireServer(unpack(args))
    end)
    end
    end)
    
    
    st:addToggle("Auto Devel Fruits", _G.DV, function(value)
        _G.DV = value
        
    while _G.DV do wait()
            pcall(function()
    
    local args = {
        [1] = "Devil Fruit",
        [2] = 1
    }
    
    game:GetService("Players").LocalPlayer.PlayerGui.Stats.Button.StatsFrame.RemoteEvent:FireServer(unpack(args))
    end)
    end
    end)
    
    misc:addButton("Check Sea King Health", function()
    local AkaliNotif = loadstring(game:HttpGet("https://raw.githubusercontent.com/Kinlei/Dynissimo/main/Scripts/AkaliNotif.lua"))();
    local Notify = AkaliNotif.Notify;
    
    Notify({
    Description = "Sea King Health";
    Title = game:GetService("Workspace").SeaMonster.SeaKing.Humanoid.Health;
    Duration = 5;
    });
    end)
    
    misc:addButton("Check Ghost Ship Health", function()
    local AkaliNotif = loadstring(game:HttpGet("https://raw.githubusercontent.com/Kinlei/Dynissimo/main/Scripts/AkaliNotif.lua"))();
    local Notify = AkaliNotif.Notify;
    
    Notify({
    Description = "Ghost Ship Health";
    Title = game:GetService("Workspace").GhostMonster["Ghost Ship"].Humanoid.Health;
    Duration = 5;
    });
    end)
    
    misc:addButton("Delete Effect", function()
    game:GetService("Players").LocalPlayer.PlayerScripts.EffectClient.MakaJungClient:Destroy()
    game:GetService("Players").LocalPlayer.PlayerScripts.EffectClient.EffectHandle:Destroy()
    game:GetService("Players").LocalPlayer.PlayerScripts.EffectClient.PeodizEffects:Destroy()
    end)
    
    
    spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.Equip then
            wait(0.5)
    game.Players.LocalPlayer.Character.Humanoid:EquipTool(game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(Weapon))
            end
        end)
       end)
    end)
    
    spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.Equip2 then
            wait(0.5)
    game.Players.LocalPlayer.Character.Humanoid:EquipTool(game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(Weapon2))
            end
        end)
       end)
    end)
    
    spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.AF then
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").PlayerCharacters[Select].HumanoidRootPart.CFrame * CFrame.new(0,3,0)
            end
        end)
       end)
    end)
    
    spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.Farm2 then
            game:GetService'VirtualUser':CaptureController()
            game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
            end
        end)
       end)
    end)
    
    spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.AF then
            game:GetService'VirtualUser':CaptureController()
            game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
            end
        end)
       end)
    end)
    
    spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
if _G.LAVACRY then

local args = {
    [1] = "Down"
}

game:GetService("Players").LocalPlayer.Character.QuakeQuake.V:InvokeServer(unpack(args))

wait(0)

local args = {
    [1] = "Up"
}

game:GetService("Players").LocalPlayer.Character.QuakeQuake.V:InvokeServer(unpack(args))
            end
        end)
       end)
    end)
    
        spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
if _G.LAVACRY then
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(7386.65674, 75.3272858, -3491.4519, -0.739999473, 0.277837604, 0.612541378, -0.0416523032, 0.890019476, -0.454015911, -0.671316504, -0.361485302, -0.64704138)
            end
        end)
       end)
    end)
    
    
        spawn(function()
        game:GetService("RunService").Heartbeat:Connect(function()
            if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") and _G.LAVACRY then
                setfflag("HumanoidParallelRemoveNoPhysics", "False")
                setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
                game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
            end
        end)
        end)

    spawn(function()
        game:GetService("RunService").Heartbeat:Connect(function()
            if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") and _G.Farm1 then
                setfflag("HumanoidParallelRemoveNoPhysics", "False")
                setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
                game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
            end
        end)
    end)
    
    spawn(function()
        game:GetService("RunService").Heartbeat:Connect(function()
            if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") and _G.AB then
                setfflag("HumanoidParallelRemoveNoPhysics", "False")
                setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
                game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
            end
        end)
    end)
    
    spawn(function()
        game:GetService("RunService").Heartbeat:Connect(function()
            if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") and _G.GS then
                setfflag("HumanoidParallelRemoveNoPhysics", "False")
                setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
                game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
            end
        end)
    end)
    
    spawn(function()
        game:GetService("RunService").Heartbeat:Connect(function()
            if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") and _G.AF then
                setfflag("HumanoidParallelRemoveNoPhysics", "False")
                setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
                game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
            end
        end)
    end)
    
    spawn(function()
        game:GetService("RunService").Heartbeat:Connect(function()
            if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") and _G.DG then
                setfflag("HumanoidParallelRemoveNoPhysics", "False")
                setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
                game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
            end
        end)
    end)
    
    spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.AB then
                game.Players.LocalPLayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Island["Legacy Island4"].ChestSpawner.CFrame
            end
        end)
       end)
    end)
    
    spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.AB then
                game.Players.LocalPLayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Island["Legacy Island5"].ChestSpawner.CFrame
            end
        end)
       end)
    end)
    
    spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.AB then
                game.Players.LocalPLayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Island["Legacy Island3"].ChestSpawner.CFrame
            end
        end)
       end)
    end)
    
    spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.AB then
                game.Players.LocalPLayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Island["Legacy Island2"].ChestSpawner.CFrame
            end
        end)
       end)
    end)
    
    spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.AB then
                game.Players.LocalPLayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Island["Legacy Island1"].ChestSpawner.CFrame
            end
        end)
       end)
    end)
    
    spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.AB then
                game.Players.LocalPLayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Island["Legacy Island"].ChestSpawner.CFrame
            end
        end)
       end)
    end)
    
    spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.AUTOHAKI then
    if game.Players.LocalPlayer.Character.Haki.Value == 0 then
        game.Players.LocalPlayer.Character.Haki.Value = 1
    	game:GetService("Players").LocalPlayer.Character.Services.Client.Armament:FireServer()
    			 end
            end
    			end)
    			end)
    end)
    	
    		spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.AF then
    if game.Players.LocalPlayer.Character.Haki.Value == 0 then
        game.Players.LocalPlayer.Character.Haki.Value = 1
    	game:GetService("Players").LocalPlayer.Character.Services.Client.Armament:FireServer()
    			 end
            end
    			end)
    			end)
    		end)
    
    spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.AB then
    _G.MON = "SeaKing" -- NAME MONSTER
    
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").SeaMonster[_G.MON].HumanoidRootPart.CFrame * CFrame.new(0,50,0)
            end
        end)
    end) 
    end)
    
    spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.DG then
    _G.MON = "Dragon [Lv. 5000]" -- NAME MONSTER
    
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Monster.Boss[_G.MON].HumanoidRootPart.CFrame * CFrame.new(0,0,0)
            end
        end)
    end) 
    end)
    
    
    spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.GS then
    _G.MON = "Ghost Ship" -- NAME MONSTER
    
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").GhostMonster[_G.MON].HumanoidRootPart.CFrame * CFrame.new(0,50,0)
            end
        end)
    end) 
    end)
    
    vu = game:GetService("VirtualUser")
    
    spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.Farm1 then
            CheckLevel()
                if game:GetService("Players").LocalPlayer.PlayerGui.Quest.QuestBoard.Visible == false then
                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
                    wait(1.5)
                    for i,v in pairs(game:GetService("Players").LocalPlayer.PlayerGui:GetDescendants()) do
                        if v.Name == "Dialogue" then
                           v.Accept.Size = UDim2.new(5000, 50, 50, 0)
                           v.Accept.Position = UDim2.new(0, -900, 0, -900)
                        end
                    end
                    wait(.3)
                elseif game:GetService("Players").LocalPlayer.PlayerGui.Quest.QuestBoard.Visible == true then
                    for i,v in pairs(game:GetService("Workspace").Monster.Mon:GetChildren()) do 
                        if v.Name == Ms and v.Humanoid.Health > 0 then
                            repeat wait()
                           game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,-6,3) 
                            until _G.Farm1 == false or game:GetService("Players").LocalPlayer.PlayerGui.Quest.QuestBoard.Visible == false or v.Humanoid.Health <= 0
                        end
        end
        end
    end
    end)
    end)
    end)
    
    spawn(function()
       game:GetService("RunService").RenderStepped:Connect(function()
        pcall(function()
            if _G.Farm1 then
            CheckLevel()
                if game:GetService("Players").LocalPlayer.PlayerGui.Quest.QuestBoard.Visible == false then
                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
                    wait(1.5)
                    for i,v in pairs(game:GetService("Players").LocalPlayer.PlayerGui:GetDescendants()) do
                        if v.Name == "Dialogue" then
                           v.Accept.Size = UDim2.new(5000, 50, 50, 0)
                           v.Accept.Position = UDim2.new(0, -900, 0, -900)
                        end
                    end
                    wait(.3)
                    vu:ClickButton1(Vector2.new(500,0))
                elseif game:GetService("Players").LocalPlayer.PlayerGui.Quest.QuestBoard.Visible == true then
                    for i,v in pairs(game:GetService("Workspace").Monster.Boss:GetChildren()) do 
                        if v.Name == Ms and v.Humanoid.Health > 0 then
                            repeat wait()
                           game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,8,3) 
                            until _G.Farm1 == false or game:GetService("Players").LocalPlayer.PlayerGui.Quest.QuestBoard.Visible == false or v.Humanoid.Health <= 0
                        end
        end
        end
    end
    end)
    end)
    end)
    
    
    
    
    local themes = {
    Background = Color3.fromRGB(24, 24, 24),
    Glow = Color3.fromRGB(60, 0, 200),
    Accent = Color3.fromRGB(10, 10, 10),
    LightContrast = Color3.fromRGB(20, 20, 20),
    DarkContrast = Color3.fromRGB(14, 14, 14),  
    TextColor = Color3.fromRGB(241, 146, 255)
    }
     
    for theme, color in pairs(themes) do -- all in one theme changer, i know, im cool
    colors:addColorPicker(theme, color, function(color3)
    venyx:setTheme(theme, color3)
    end)
    end
     
    -- load
    venyx:SelectPage(venyx.pages[1], true)
    
    
    colors:addKeybind("Toggle Keybind", Enum.KeyCode.RightControl, function()
    print("Activated Keybind")  
    venyx:toggle()
    end, function()
    game.StarterGui:SetCore("SendNotification", {
    Title = "Keybind";
    Text = "Change Keybind Success";
    Duration = "10";
    })
    end)
