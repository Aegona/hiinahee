
--- sccript by Aegona 




local Fire = Instance.new("Fire")
Fire.Parent = game.Players.LocalPlayer.Character.RightHand
Fire.Heat = 5
Fire.Size = 5







function CheckQuest()
   local Lv =  game.Players.LocalPlayer.Data.Level.Value
   if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
   elseif  Lv == 1 or Lv <= 9 then
       Ms = "Bandit [Lv. 5]"
       CQ = CFrame.new(1059.838623046875, 16.516624450683594, 1545.941162109375)
       CM = CFrame.new(1177.2108154296875, 16.43285369873047, 1616.587646484375)
       NQ = "BanditQuest1"
       NM = "Bandit"
       LQ = 1
   elseif Lv == 10 or Lv <= 49 then
       Ms = "Shanda [Lv. 475]"
       CQ = CFrame.new(-7679.10400390625, 5595.53173828125, -498.8669738769531)
       CM = CFrame.new(-7683.90234375, 5567.1435546875, -498.32098388671875)
       NQ = ""
       NM = "Shanda"
       LQ = 1
       elseif Lv == 50 or Lv <= 100 then
       Ms = "Royal Squad [Lv. 525]"
       CQ = CFrame.new(-7780.8359375, 5648.13037109375, -1365.7181396484375)
       CM = CFrame.new(-7773.3046875, 5622.67431640625, -1355.3155517578125)
       NQ = ""
       NM = "Royal Squad"
       LQ = 1
       elseif Lv == 101 or Lv <= 119 then
       Ms = "Snowman [Lv. 100]"
       CQ = CFrame.new(1384.1134033203125, 87.27277374267578, -1298.09130859375)
       CM = CFrame.new(1202.4942626953125, 105.77490997314453, -1475.2557373046875)
       NQ = "SnowQuest"
       NM = "Snowman"
       LQ = 2
              elseif Lv == 120 or Lv <= 149 then
       Ms = "Chief Petty Officer [Lv. 120]"
       CQ = CFrame.new(-5034.1435546875, 28.777360916137695, 4322.96142578125)
       CM = CFrame.new(-4891.8876953125, 20.777360916137695, 4070.431396484375)
       NQ = "MarineQuest2"
       NM = "MarineQuest2"
       LQ = 1
                     elseif Lv == 150 or Lv <= 174 then
       Ms = "Sky Bandit [Lv. 150]"
       CQ = CFrame.new(-4845.04296875, 717.70703125, -2624.240966796875)
       CM = CFrame.new(-4951.09423828125, 296.0914001464844, -2823.39501953125)
       NQ = "SkyQuest"
       NM = "Sky Bandit"
       LQ = 1
              elseif Lv == 175 or Lv <= 189 then
       Ms = "Prisoner [Lv. 190]"
       CQ = CFrame.new(5316.4765625, 15.77651596069336, 463.12200927734375)
       CM = CFrame.new(5298.9482421875, 1.7777401208877563, 429.47412109375)
       NQ = "PrisonerQuest"
       NM = "Prisoner"
       LQ = 1
                elseif Lv == 209 or Lv <= 249 then
       Ms = "Dangerous Prisoner [Lv. 210]"
       CQ = CFrame.new(5316.4765625, 15.77651596069336, 463.12200927734375)
       CM = CFrame.new(5589.62744140625, 1.7775516510009766, 593.0758666992188)
       NQ = "PrisonerQuest"
       NM = "Dangerous Prisoner"
       LQ = 2    
		elseif Lv == 250 or Lv <= 274 then -- Toga Warrior
					Ms = "Toga Warrior [Lv. 250]"
					NQ = "ColosseumQuest"
					LQ = 1
					NM = "Toga Warrior"
					CQ = CFrame.new(-1576.11743, 7.38933945, -2983.30762, 0.576966345, 1.22114863e-09, 0.816767931, -3.58496594e-10, 1, -1.24185606e-09, -0.816767931, 4.2370063e-10, 0.576966345)
					CM = CFrame.new(-1779.97583, 44.6077499, -2736.35474, 0.984437346, 4.10396339e-08, 0.175734788, -3.62286876e-08, 1, -3.05844168e-08, -0.175734788, 2.3741821e-08, 0.984437346)
				elseif Lv == 275 or Lv <= 299 then -- Gladiato
					Ms = "Gladiator [Lv. 275]"
					NQ = "ColosseumQuest"
					LQ = 2
					NM = "Gladiator"
					CQ = CFrame.new(-1576.11743, 7.38933945, -2983.30762, 0.576966345, 1.22114863e-09, 0.816767931, -3.58496594e-10, 1, -1.24185606e-09, -0.816767931, 4.2370063e-10, 0.576966345)
					CM = CFrame.new(-1274.75903, 58.1895943, -3188.16309, 0.464524001, 6.21005611e-08, 0.885560572, -4.80449414e-09, 1, -6.76054768e-08, -0.885560572, 2.71497012e-08, 0.464524001)
				elseif Lv == 300 or Lv <= 329 then -- Military Soldier
					Ms = "Military Soldier [Lv. 300]"
					NQ = "MagmaQuest"
					LQ = 1
					NM = "Military Soldier"
					CQ = CFrame.new(-5316.55859, 12.2370615, 8517.2998, 0.588437557, -1.37880001e-08, -0.808542669, -2.10116209e-08, 1, -3.23446478e-08, 0.808542669, 3.60215964e-08, 0.588437557)
					CM = CFrame.new(-5363.01123, 41.5056877, 8548.47266, -0.578253984, -3.29503091e-10, 0.815856814, 9.11209668e-08, 1, 6.498761e-08, -0.815856814, 1.11920997e-07, -0.578253984)
				elseif Lv == 330 or Lv <= 374 then -- Military Spy
					Ms = "Military Spy [Lv. 325]"
					NQ = "MagmaQuest"
					LQ = 2
					NM = "Military Spy"
					CQ = CFrame.new(-5316.55859, 12.2370615, 8517.2998, 0.588437557, -1.37880001e-08, -0.808542669, -2.10116209e-08, 1, -3.23446478e-08, 0.808542669, 3.60215964e-08, 0.588437557)
					CM = CFrame.new(-5787.99023, 120.864456, 8762.25293, -0.188358366, -1.84706277e-08, 0.982100308, -1.23782129e-07, 1, -4.93306951e-09, -0.982100308, -1.22495649e-07, -0.188358366)
				elseif Lv == 375 or Lv <= 399 then -- Fishman Warrior

				    local args = {
    [1] = "requestEntrance",
    [2] = Vector3.new(61163.8515625, 11.6796875, 1819.7841796875)
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
					Ms = "Fishman Warrior [Lv. 375]"
					NQ = "FishmanQuest"
					LQ = 1
					NM = "Fishman Warrior"
					CQ = CFrame.new(61122.5625, 18.4716396, 1568.16504, 0.893533468, 3.95251609e-09, 0.448996574, -2.34327455e-08, 1, 3.78297464e-08, -0.448996574, -4.43233645e-08, 0.893533468)
					CM = CFrame.new(60946.6094, 48.6735229, 1525.91687, -0.0817126185, 8.90751153e-08, 0.996655822, 2.00889794e-08, 1, -8.77269599e-08, -0.996655822, 1.28533992e-08, -0.0817126185)
				elseif Lv == 400 or Lv <= 449 then -- Fishman Commando

					Ms = "Fishman Commando [Lv. 400]"
					NQ = "FishmanQuest"
					LQ = 2
					NM = "Fishman Commando"
					CQ = CFrame.new(61122.5625, 18.4716396, 1568.16504, 0.893533468, 3.95251609e-09, 0.448996574, -2.34327455e-08, 1, 3.78297464e-08, -0.448996574, -4.43233645e-08, 0.893533468)
					CM = CFrame.new(61885.5039, 18.4828243, 1504.17896, 0.577502489, 0, -0.816389024, -0, 1.00000012, -0, 0.816389024, 0, 0.577502489)
				elseif Lv == 450 or Lv <= 474 then -- God's Guards
					Ms = "God's Guard [Lv. 450]"
					NQ = "SkyExp1Quest"
					LQ = 1
					NM = "God's Guards"
					CQ = CFrame.new(-4721.71436, 845.277161, -1954.20105, -0.999277651, -5.56969759e-09, 0.0380011722, -4.14751478e-09, 1, 3.75035256e-08, -0.0380011722, 3.73188307e-08, -0.999277651)
					CM = CFrame.new(-4716.95703, 853.089722, -1933.92542, -0.93441087, -6.77488776e-09, -0.356197298, 1.12145182e-08, 1, -4.84390199e-08, 0.356197298, -4.92565206e-08, -0.93441087)
				elseif Lv == 475 or Lv <= 524 then -- Shandas
local args = {
    [1] = "requestEntrance",
    [2] = Vector3.new(-7894.61767578125, 5547.1416015625, -380.29119873046875)
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
					Ms = "Shanda [Lv. 475]"
					NQ = "SkyExp1Quest"
					LQ = 2
					NM = "Shandas"
					CQ = CFrame.new(-7863.63672, 5545.49316, -379.826324, 0.362120807, -1.98046344e-08, -0.93213129, 4.05822291e-08, 1, -5.48095125e-09, 0.93213129, -3.58431969e-08, 0.362120807)
					CM = CFrame.new(-7685.12354, 5601.05127, -443.171509, 0.150056243, 1.79768236e-08, -0.988677442, 6.67798661e-09, 1, 1.91962481e-08, 0.988677442, -9.48289181e-09, 0.150056243)
				elseif Lv == 525 or Lv <= 549 then -- Royal Squad

local args = {
    [1] = "requestEntrance",
    [2] = Vector3.new(-7894.61767578125, 5547.1416015625, -380.29119873046875)
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))

					Ms = "Royal Squad [Lv. 525]"
					NQ = "SkyExp2Quest"
					LQ = 1
					NM = "Royal Squad"
					CQ = CFrame.new(-7902.66895, 5635.96387, -1411.71802, 0.0504222959, 2.5710392e-08, 0.998727977, 1.12541557e-07, 1, -3.14249675e-08, -0.998727977, 1.13982921e-07, 0.0504222959)
					CM = CFrame.new(-7685.02051, 5606.87842, -1442.729, 0.561947823, 7.69527464e-09, -0.827172697, -4.24974544e-09, 1, 6.41599973e-09, 0.827172697, -9.01838604e-11, 0.561947823)
				elseif Lv == 550 or Lv <= 624 then -- Royal Soldier
					Ms = "Royal Soldier [Lv. 550]"
					NQ = "SkyExp2Quest"
					LQ = 2
					NM = "Royal Soldier"
					CQ = CFrame.new(-7902.66895, 5635.96387, -1411.71802, 0.0504222959, 2.5710392e-08, 0.998727977, 1.12541557e-07, 1, -3.14249675e-08, -0.998727977, 1.13982921e-07, 0.0504222959)
					CM = CFrame.new(-7864.44775, 5661.94092, -1708.22351, 0.998389959, 2.28686137e-09, -0.0567218624, 1.99431383e-09, 1, 7.54200258e-08, 0.0567218624, -7.54117195e-08, 0.998389959)
				elseif Lv == 625 or Lv <= 649 then -- Galley Pirate
					Ms = "Galley Pirate [Lv. 625]"
					NQ = "FountainQuest"
					LQ = 1
					NM = "Galley Pirate"
					CQ = CFrame.new(5254.60156, 38.5011406, 4049.69678, -0.0504891425, -3.62066501e-08, -0.998724639, -9.87921389e-09, 1, -3.57534553e-08, 0.998724639, 8.06145284e-09, -0.0504891425)
					CM = CFrame.new(5595.06982, 41.5013695, 3961.47095, -0.992138803, -2.11610267e-08, -0.125142589, -1.34249509e-08, 1, -6.26613996e-08, 0.125142589, -6.04887518e-08, -0.992138803)
				elseif Lv >= 650 then -- Galley Captain
					Ms = "Galley Captain [Lv. 650]"
					NQ = "FountainQuest"
					LQ = 2
					NM = "Galley Captain"
					CQ = CFrame.new(5254.60156, 38.5011406, 4049.69678, -0.0504891425, -3.62066501e-08, -0.998724639, -9.87921389e-09, 1, -3.57534553e-08, 0.998724639, 8.06145284e-09, -0.0504891425)
					CM = CFrame.new(5658.5752, 38.5361786, 4928.93506, -0.996873081, 2.12391046e-06, -0.0790185928, 2.16989656e-06, 1, -4.96097414e-07, 0.0790185928, -6.66008248e-07, -0.996873081)
				end
			end
			if NewWorld then
				if Lv == 700 or Lv <= 724 then -- Raider [Lv. 700]
					Ms = "Raider [Lv. 700]"
					NQ = "Area1Quest"
					LQ = 1
					NM = "Raider"
					CQ = CFrame.new(-424.080078, 73.0055847, 1836.91589, 0.253544956, -1.42165932e-08, 0.967323601, -6.00147771e-08, 1, 3.04272909e-08, -0.967323601, -6.5768397e-08, 0.253544956)
					CM = CFrame.new(-737.026123, 39.1748352, 2392.57959, 0.272128761, 0, -0.962260842, -0, 1, -0, 0.962260842, 0, 0.272128761)
				elseif Lv == 725 or Lv <= 774 then -- Mercenary [Lv. 725]
					Ms = "Mercenary [Lv. 725]"
					NQ = "Area1Quest"
					LQ = 2
					NM = "Mercenary"
					CQ = CFrame.new(-424.080078, 73.0055847, 1836.91589, 0.253544956, -1.42165932e-08, 0.967323601, -6.00147771e-08, 1, 3.04272909e-08, -0.967323601, -6.5768397e-08, 0.253544956)
					CM = CFrame.new(-973.731995, 95.8733215, 1836.46936, 0.999135971, 2.02326991e-08, -0.0415605344, -1.90767793e-08, 1, 2.82094952e-08, 0.0415605344, -2.73922804e-08, 0.999135971)
				elseif Lv == 775 or Lv <= 799 then -- Swan Pirate [Lv. 775]
					Ms = "Swan Pirate [Lv. 775]"
					NQ = "Area2Quest"
					LQ = 1
					NM = "Swan Pirate"
					CQ = CFrame.new(632.698608, 73.1055908, 918.666321, -0.0319722369, 8.96074881e-10, -0.999488771, 1.36326533e-10, 1, 8.92172336e-10, 0.999488771, -1.07732087e-10, -0.0319722369)
					CM = CFrame.new(970.369446, 142.653198, 1217.3667, 0.162079468, -4.85452638e-08, -0.986777723, 1.03357589e-08, 1, -4.74980872e-08, 0.986777723, -2.50063148e-09, 0.162079468)
				elseif Lv == 800 or Lv <= 874 then -- Factory Staff [Lv. 800]
					Ms = "Factory Staff [Lv. 800]"
					NQ = "Area2Quest"
					LQ = 2
					NM = "Factory Staff"
					CQ = CFrame.new(632.698608, 73.1055908, 918.666321, -0.0319722369, 8.96074881e-10, -0.999488771, 1.36326533e-10, 1, 8.92172336e-10, 0.999488771, -1.07732087e-10, -0.0319722369)
					CM = CFrame.new(296.786499, 72.9948196, -57.1298141, -0.876037002, -5.32364979e-08, 0.482243896, -3.87658332e-08, 1, 3.99718729e-08, -0.482243896, 1.63222538e-08, -0.876037002)
				elseif Lv == 875 or Lv <= 899 then -- Marine Lieutenant [Lv. 875]
					Ms = "Marine Lieutenant [Lv. 875]"
					NQ = "MarineQuest3"
					LQ = 1
					NM = "Marine Lieutenant"
					CQ = CFrame.new(-2442.65015, 73.0511475, -3219.11523, -0.873540044, 4.2329841e-08, -0.486752301, 5.64383384e-08, 1, -1.43220786e-08, 0.486752301, -3.99823996e-08, -0.873540044)
					CM = CFrame.new(-2913.26367, 73.0011826, -2971.64282, 0.910507619, 0, 0.413492233, 0, 1.00000012, 0, -0.413492233, 0, 0.910507619)
				elseif Lv == 900 or Lv <= 949 then -- Marine Captain [Lv. 900]
					Ms = "Marine Captain [Lv. 900]"
					NQ = "MarineQuest3"
					LQ = 2
					NM = "Marine Captain"
					CQ = CFrame.new(-2442.65015, 73.0511475, -3219.11523, -0.873540044, 4.2329841e-08, -0.486752301, 5.64383384e-08, 1, -1.43220786e-08, 0.486752301, -3.99823996e-08, -0.873540044)
					CM = CFrame.new(-1868.67688, 73.0011826, -3321.66333, -0.971402287, 1.06502087e-08, 0.237439692, 3.68856199e-08, 1, 1.06050372e-07, -0.237439692, 1.11775684e-07, -0.971402287)
				elseif Lv == 950 or Lv <= 974 then -- Zombie [Lv. 950]
					Ms = "Zombie [Lv. 950]"
					NQ = "ZombieQuest"
					LQ = 1
					NM = "Zombie"
					CQ = CFrame.new(-5492.79395, 48.5151672, -793.710571, 0.321800292, -6.24695815e-08, 0.946807742, 4.05616092e-08, 1, 5.21931227e-08, -0.946807742, 2.16082796e-08, 0.321800292)
					CM = CFrame.new(-5634.83838, 126.067039, -697.665039, -0.992770672, 6.77618939e-09, 0.120025545, 1.65461245e-08, 1, 8.04023372e-08, -0.120025545, 8.18070234e-08, -0.992770672)
				elseif Lv == 975 or Lv <= 999 then -- Vampire [Lv. 975]
					Ms = "Vampire [Lv. 975]"
					NQ = "ZombieQuest"
					LQ = 2
					NM = "Vampire"
					CQ = CFrame.new(-5492.79395, 48.5151672, -793.710571, 0.321800292, -6.24695815e-08, 0.946807742, 4.05616092e-08, 1, 5.21931227e-08, -0.946807742, 2.16082796e-08, 0.321800292)
					CM = CFrame.new(-6030.32031, 6.4377408, -1313.5564, -0.856965423, 3.9138893e-08, -0.515373945, -1.12178942e-08, 1, 9.45958547e-08, 0.515373945, 8.68467822e-08, -0.856965423)
				elseif Lv == 1000 or Lv <= 1049 then -- Snow Trooper [Lv. 1000] **
					Ms = "Snow Trooper [Lv. 1000]"
					NQ = "SnowMountainQuest"
					LQ = 1
					NM = "Snow Trooper"
					CQ = CFrame.new(604.964966, 401.457062, -5371.69287, 0.353063971, 1.89520435e-08, -0.935599446, -5.81846002e-08, 1, -1.70033754e-09, 0.935599446, 5.50377841e-08, 0.353063971)
					CM = CFrame.new(535.893433, 401.457062, -5329.6958, -0.999524176, 0, 0.0308452044, 0, 1, -0, -0.0308452044, 0, -0.999524176)
				elseif Lv == 1050 or Lv <= 1099 then -- Winter Warrior [Lv. 1050]
					Ms = "Winter Warrior [Lv. 1050]"
					NQ = "SnowMountainQuest"
					LQ = 2
					NM = "Winter Warrior"
					CQ = CFrame.new(604.964966, 401.457062, -5371.69287, 0.353063971, 1.89520435e-08, -0.935599446, -5.81846002e-08, 1, -1.70033754e-09, 0.935599446, 5.50377841e-08, 0.353063971)
					CM = CFrame.new(1223.7417, 454.575226, -5170.02148, 0.473996818, 2.56845354e-08, 0.880526543, -5.62456428e-08, 1, 1.10811016e-09, -0.880526543, -5.00510211e-08, 0.473996818)
				elseif Lv == 1100 or Lv <= 1124 then -- Lab Subordinate [Lv. 1100]
					Ms = "Lab Subordinate [Lv. 1100]"
					NQ = "IceSideQuest"
					LQ = 1
					NM = "Lab Subordinate"
					CQ = CFrame.new(-6060.10693, 15.9868021, -4904.7876, -0.411000341, -5.06538868e-07, 0.91163528, 1.26306062e-07, 1, 6.12581289e-07, -0.91163528, 3.66916197e-07, -0.411000341)
					CM = CFrame.new(-5769.2041, 37.9288292, -4468.38721, -0.569419742, -2.49055017e-08, 0.822046936, -6.96206541e-08, 1, -1.79282633e-08, -0.822046936, -6.74401548e-08, -0.569419742)
				elseif Lv == 1125 or Lv <= 1174 then -- Horned Warrior [Lv. 1125]
					Ms = "Horned Warrior [Lv. 1125]"
					NQ = "IceSideQuest"
					LQ = 2
					NM = "Horned Warrior"
					CQ = CFrame.new(-6060.10693, 15.9868021, -4904.7876, -0.411000341, -5.06538868e-07, 0.91163528, 1.26306062e-07, 1, 6.12581289e-07, -0.91163528, 3.66916197e-07, -0.411000341)
					CM = CFrame.new(-6400.85889, 24.7645149, -5818.63574, -0.964845479, 8.65926566e-08, -0.262817472, 3.98261392e-07, 1, -1.13260398e-06, 0.262817472, -1.19745812e-06, -0.964845479)
				elseif Lv == 1175 or Lv <= 1199 then -- Magma Ninja [Lv. 1175]
					Ms = "Magma Ninja [Lv. 1175]"
					NQ = "FireSideQuest"
					LQ = 1
					NM = "Magma Ninja"
					CQ = CFrame.new(-5431.09473, 15.9868021, -5296.53223, 0.831796765, 1.15322464e-07, -0.555080295, -1.10814341e-07, 1, 4.17010995e-08, 0.555080295, 2.68240168e-08, 0.831796765)
					CM = CFrame.new(-5496.65576, 58.6890411, -5929.76855, -0.885073781, 0, -0.465450764, 0, 1.00000012, -0, 0.465450764, 0, -0.885073781)
				elseif Lv == 1200 or Lv <= 1249 then -- Lava Pirate [Lv. 1200]
					Ms = "Lava Pirate [Lv. 1200]"
					NQ = "FireSideQuest"
					LQ = 2
					NM = "Lava Pirate"
					CQ = CFrame.new(-5431.09473, 15.9868021, -5296.53223, 0.831796765, 1.15322464e-07, -0.555080295, -1.10814341e-07, 1, 4.17010995e-08, 0.555080295, 2.68240168e-08, 0.831796765)
					CM = CFrame.new(-5169.71729, 34.1234779, -4669.73633, -0.196780294, 0, 0.98044765, 0, 1.00000012, -0, -0.98044765, 0, -0.196780294)
				elseif Lv == 1250 or Lv <= 1274 then -- Ship Deckhand [Lv. 1250]
					Ms = "Ship Deckhand [Lv. 1250]"
					NQ = "ShipQuest1"
					LQ = 1
					NM = "Ship Deckhand"
					CQ = CFrame.new(1037.80127, 125.092171, 32911.6016, -0.244533166, -0, -0.969640911, -0, 1.00000012, -0, 0.96964103, 0, -0.244533136)
					CM = CFrame.new(1163.80872, 138.288452, 33058.4258, -0.998580813, 5.49076979e-08, -0.0532564968, 5.57436763e-08, 1, -1.42118655e-08, 0.0532564968, -1.71604082e-08, -0.998580813)
				elseif Lv == 1275 or Lv <= 1299 then -- Ship Engineer [Lv. 1275]
					Ms = "Ship Engineer [Lv. 1275]"
					NQ = "ShipQuest1"
					LQ = 2
					NM = "Ship Engineer"
					CQ = CFrame.new(1037.80127, 125.092171, 32911.6016, -0.244533166, -0, -0.969640911, -0, 1.00000012, -0, 0.96964103, 0, -0.244533136)
					CM = CFrame.new(916.666504, 44.0920448, 32917.207, -0.99746871, -4.85034697e-08, -0.0711069331, -4.8925461e-08, 1, 4.19294288e-09, 0.0711069331, 7.66126895e-09, -0.99746871)
				elseif Lv == 1300 or Lv <= 1324 then -- Ship Steward [Lv. 1300]
					Ms = "Ship Steward [Lv. 1300]"
					NQ = "ShipQuest2"
					LQ = 1
					NM = "Ship Steward"
					CQ = CFrame.new(968.80957, 125.092171, 33244.125, -0.869560242, 1.51905191e-08, -0.493826836, 1.44108379e-08, 1, 5.38534195e-09, 0.493826836, -2.43357912e-09, -0.869560242)
					CM = CFrame.new(918.743286, 129.591064, 33443.4609, -0.999792814, -1.7070947e-07, -0.020350717, -1.72559169e-07, 1, 8.91351277e-08, 0.020350717, 9.2628369e-08, -0.999792814)
				elseif Lv == 1325 or Lv <= 1349 then -- Ship Officer [Lv. 1325]
					Ms = "Ship Officer [Lv. 1325]"
					NQ = "ShipQuest2"
					LQ = 2
					NM = "Ship Officer"
					CQ = CFrame.new(968.80957, 125.092171, 33244.125, -0.869560242, 1.51905191e-08, -0.493826836, 1.44108379e-08, 1, 5.38534195e-09, 0.493826836, -2.43357912e-09, -0.869560242)
					CM = CFrame.new(786.051941, 181.474106, 33303.2969, 0.999285698, -5.32193063e-08, 0.0377905183, 5.68968588e-08, 1, -9.62386864e-08, -0.0377905183, 9.83201005e-08, 0.999285698)
				elseif Lv == 1350 or Lv <= 1374 then -- Arctic Warrior [Lv. 1350]
					Ms = "Arctic Warrior [Lv. 1350]"
					NQ = "FrostQuest"
					LQ = 1
					NM = "Arctic Warrior"
					CQ = CFrame.new(5669.43506, 28.2117786, -6482.60107, 0.888092756, 1.02705066e-07, 0.459664226, -6.20391774e-08, 1, -1.03572376e-07, -0.459664226, 6.34646895e-08, 0.888092756)
					CM = CFrame.new(5995.07471, 57.3188477, -6183.47314, 0.702747107, -1.53454167e-07, -0.711440146, -1.08168464e-07, 1, -3.22542007e-07, 0.711440146, 3.03620908e-07, 0.702747107)
				elseif Lv == 1375 or Lv <= 1424 then -- Snow Lurker [Lv. 1375]
					Ms = "Snow Lurker [Lv. 1375]"
					NQ = "FrostQuest"
					LQ = 2
					NM = "Snow Lurker"
					CQ = CFrame.new(5669.43506, 28.2117786, -6482.60107, 0.888092756, 1.02705066e-07, 0.459664226, -6.20391774e-08, 1, -1.03572376e-07, -0.459664226, 6.34646895e-08, 0.888092756)
					CM = CFrame.new(5518.00684, 60.5559731, -6828.80518, -0.650781393, -3.64292951e-08, 0.759265184, -4.07668654e-09, 1, 4.44854642e-08, -0.759265184, 2.58550248e-08, -0.650781393)
				elseif Lv == 1425 or Lv <= 1449 then -- Sea Soldier [Lv. 1425]
					Ms = "Sea Soldier [Lv. 1425]"
					NQ = "ForgottenQuest"
					LQ = 1
					NM = "Sea Soldier"
					CQ = CFrame.new(-3052.99097, 236.881363, -10148.1943, -0.997911751, 4.42321983e-08, 0.064591676, 4.90968759e-08, 1, 7.37270085e-08, -0.064591676, 7.67442998e-08, -0.997911751)
					CM = CFrame.new(-3029.78467, 66.944252, -9777.38184, -0.998552859, 1.09555076e-08, 0.0537791774, 7.79564235e-09, 1, -5.89660658e-08, -0.0537791774, -5.84614881e-08, -0.998552859)
				elseif Lv >= 1450 then -- Water Fighter [Lv. 1450]
					Ms = "Water Fighter [Lv. 1450]"
					NQ = "ForgottenQuest"
					LQ = 2
					NM = "Water Fighter"
					CQ = CFrame.new(-3052.99097, 236.881363, -10148.1943, -0.997911751, 4.42321983e-08, 0.064591676, 4.90968759e-08, 1, 7.37270085e-08, -0.064591676, 7.67442998e-08, -0.997911751)
					CM = CFrame.new(-3262.00098, 298.699615, -10553.6943, -0.233570755, -4.57538185e-08, 0.972339869, -5.80986068e-08, 1, 3.30992194e-08, -0.972339869, -4.87605725e-08, -0.233570755)

    end
end






















local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Patskorn/GUI/main/Copy-SynapOver.lua"))()

local GUI = library:new("Aegona Hub","[ RightControl ]")
local Tab1 = GUI:Tap("Menu ")
local Tab2 = GUI:Tap("POINT")



Tab1:Toggle("AutoFarm",nil,function(t)    
    _G.Farm = t
    _G.BringMob = t
end)

Tab1:Toggle("FastAttack Mobile and PCC ",nil,function(t)    
_G._G.FastAttackMobile = t
end)
  
 Tab1:Toggle("FastAttack PC (NOOB)",nil,function(t)    
_G.FastAttack = t
end)          
Tab1:Toggle("AutoSaber",nil,function(t)    
    wait(1)
game.Players.LocalPlayer.Character.Humanoid.Health = 0
    wait(.4)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1338.741943359375, 11.978065490722656, 489.11395263671875)
wait(.1)
local string_1 = "SetSpawnPoint";
local Target = game:GetService("ReplicatedStorage").Remotes["CommF_"];
Target:InvokeServer(string_1);
    wait(1)
game.Players.LocalPlayer.Character.Humanoid.Health = 0
    wait(.4)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1338.741943359375, 11.978065490722656, 489.11395263671875)
wait(.1)
local string_1 = "SetSpawnPoint";
local Target = game:GetService("ReplicatedStorage").Remotes["CommF_"];
Target:InvokeServer(string_1);
wait(1)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1647.2904052734375, 23.377431869506836, 437.4636535644531)
wait(1)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1420.787353515625, 48.33733367919922, 23.527286529541016)
wait(1)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1648.208740234375, 23.377416610717773, 437.99322509765625)
wait(1)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1179.1500244140625, 19.63349723815918, 188.8375244140625)
wait(1)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1325.3642578125, 31.754444122314453, -462.1560974121094)
wait(1)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1151.65673828125, 2.6079061031341553, -701.0443115234375)
wait(1)
local TweenService = game:GetService("TweenService")

local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
{CFrame = CFrame.new(-1610.9407958984375, 12.177388191223145, 162.7132568359375)}):Play()

end)


Tab1:Toggle("AutoMelee",nil,function(t)    
_G.autoequipmelee = t
end)


Tab2:Toggle("Melee",nil,function(t)    
    while true do wait()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Melee",1)
end
end)

local Weaponlist = {}
local Weapon = nil







function TP(P)
    NoClip = true
    Distance = (P.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
    if Distance < 10 then
        Speed = 1000
    elseif Distance < 170 then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = P
        Speed = 360
    elseif Distance < 1000 then
        Speed = 360
    elseif Distance >= 1000 then
        Speed = 280
    end
    game:GetService("TweenService"):Create(
        game.Players.LocalPlayer.Character.HumanoidRootPart,
        TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
        {CFrame = P}
    ):Play()
    NoClip = false
end




spawn(function()
    while wait() do
        if _G.Farm then
            CheckQuest()
            if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
                wait(.3)
                TP(CQ)
                wait(0.5)
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest",NQ,LQ)
                
            elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
                for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                    if v.Name == Ms then
                        posmon = v.HumanoidRootPart.CFrame
                        wait(.1)
                        posmon = v.HumanoidRootPart.CFrame
                        wait(.1)
                        posmon = v.HumanoidRootPart.CFrame
                        TP(v.HumanoidRootPart.CFrame * CFrame.new(0,25,0))
                        end
                    end
                end
            end    
        end
    end)

spawn(function()
    pcall(function()
        while task.wait() do
            if _G.Farm then
                if not game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip") then
                    local Noclip = Instance.new("BodyVelocity")
                    Noclip.Name = "BodyClip"
                    Noclip.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
                    Noclip.MaxForce = Vector3.new(100000,100000,100000)
                    Noclip.Velocity = Vector3.new(0,0,0)
                end
            else
                if game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip") then
                    game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip"):Destroy()
                end
            end
        end
    end)
end)



spawn(function()
    while task.wait() do
        if _G.Farm then
        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
            if v.Name == Ms then
                v.HumanoidRootPart.CFrame = CM
                wait(.1)
                v.HumanoidRootPart.CFrame = CM
                wait(.1)
                v.HumanoidRootPart.CFrame = CM
                v.HumanoidRootPart.CanCollide = false
                sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                end
            end
        end
    end
end)


             while _G.BringMob do wait()
            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                 for i2,v2 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                    if v.Name == MON and v2.Name == MON then
                        v2.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame
                        v2.HumanoidRootPart.CanCollide = false
                           game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * Method
                            sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                    end
                 end
            end
             end





Tab1:Button("Reedem AllCode",function()
local args = {
    [1] = "kittgaming"
}

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(unpack(args))
wait(.5)
local args = {
    [1] = "Sub2Fer999"
}

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(unpack(args))
wait(.5)
local args = {
    [1] = "Enyu_is_Pro"
}

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(unpack(args))
wait(.5)
local args = {
    [1] = "Magicbus"
}

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(unpack(args))
wait(.5)
local args = {
    [1] = "JCWK"
}

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(unpack(args))
wait(.5)
local args = {
    [1] = "Starcodeheo"
}

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(unpack(args))
wait(.5)
local args = {
    [1] = "Bluxxy"
}

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(unpack(args))
wait(.5)
local args = {
    [1] = "Bignews"
}

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(unpack(args))
wait(.5)
local args = {
    [1] = "Sub2OfficialNoobie"
}

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(unpack(args))
wait(.5)
local args = {
    [1] = "TheGreatAce"
}

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(unpack(args))
wait(.5)
local args = {
    [1] = "Sub2NoobMaster123"
}

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(unpack(args))
wait(.5)
local args = {
    [1] = "TheGreatAce"
}

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(unpack(args))
wait(.5)
local args = {
    [1] = "Axiore"
}

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(unpack(args))
wait(.5)
local args = {
    [1] = "Sub2Daigrock"
}

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(unpack(args))
wait(.5)
local args = {
    [1] = "StrawHatMaine"
}

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(unpack(args))
wait(.5)
local args = {
    [1] = "TantaiGaming"
}

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(unpack(args))
wait(.5)
local args = {
    [1] = "SUB2GAMERROBOT_EXP1"
}

game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(unpack(args))

end)

local CombatFramework = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)
local Camera = require(game.ReplicatedStorage.Util.CameraShaker)
Camera:Stop()
coroutine.wrap(function()
    game:GetService("RunService").Stepped:Connect(function()
        if getupvalues(CombatFramework)[2]['activeController'].timeToNextAttack then
            getupvalues(CombatFramework)[2]['activeController'].timeToNextAttack = 0
            getupvalues(CombatFramework)[2]['activeController'].hitboxMagnitude = 60
            getupvalues(CombatFramework)[2]['activeController']:attack()
        end
    end)
end)()
--hi xenon

while wait(.1) do
    pcall(function()
	if _G.AutoMelee then
		wait(0.3)
		game:GetService("ReplicatedStorage").Remotes["CommF_"]:InvokeServer("AddPoint", "Melee", 1)
	end
	if _G.AutoDefense then
		wait(0.3)
		game:GetService("ReplicatedStorage").Remotes["CommF_"]:InvokeServer("AddPoint", "Defense", 1)
	end
	if _G.AutoSword then
		wait(0.3)
		game:GetService("ReplicatedStorage").Remotes["CommF_"]:InvokeServer("AddPoint", "Sword", 1)
	end
	if _G.AutoGun then
		wait(0.3)
		game:GetService("ReplicatedStorage").Remotes["CommF_"]:InvokeServer("AddPoint", "Gun", 1)
	end
	if _G.AutoFruit then
		wait(0.3)
		game:GetService("ReplicatedStorage").Remotes["CommF_"]:InvokeServer("AddPoint", "Demon Fruit", 1)
	end
	if _G.NoClip then
		game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
	end
	if _G.autoequipmelee then
	    pcall(function()
	    for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
           if v.ToolTip == "Melee" then
          if game.Players.LocalPlayer.Backpack:FindFirstChild(tostring(v.Name)) then
              local ToolSe = tostring(v.Name)
             local tool = game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe)
             wait(.4)
             game.Players.LocalPlayer.Character.Humanoid:EquipTool(tool)
          end
           end
	    end
	end)
end
end)
end

spawn(function()
   game:GetService("RunService").RenderStepped:Connect(function()
    pcall(function()
        if _G.FastAttackMobile then
            game:GetService'VirtualUser':CaptureController()
            game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
        end
    end)
end) 
end)
