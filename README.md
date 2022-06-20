game.StarterGui:SetCore("SendNotification", {
    Title = "1tsJustCmds";
    Text = "Credits 1tsJustgp";
    Duration = "15";
    })

	game.StarterGui:SetCore("SendNotification", {
		Title = "1tsJustCmds";
		Text = "send in chat =cmds and press f9 and scroll down";
		Duration = "15";
		})


function dc()
	local plr = game:GetService("Players").LocalPlayer
	local mouse = plr:GetMouse()
	local place = game.PlaceId
	Character = game.Players.LocalPlayer
	Players = game.Players.LocalPlayer.Character
	MouseFunction = game:GetService("Players").LocalPlayer:GetMouse()


	mouse.KeyDown:connect(function(key)

		if key == "k" then
			Players.Humanoid:EquipTool(Character.Backpack["Dragon Crush"])
			Players["Dragon Crush"]:Activate()
			game.Workspace.Live[Character.Name]["Dragon Crush"].Activator["Flip"]:Destroy()
			wait()

		end
	end)
end 
function dc2()
game:GetService("StarterGui"):SetCore("SendNotification", {
Title = "1tsJustCmds";
Text = "DragonCrush Glich Press K";
})
end
local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
if cht:match("=dc") or cht:match("=dragoncrush") then
dc2()
dc()
end
end)

function noslow()
    (getgenv()).noslow = true;

    repeat
        wait();
    until game:IsLoaded();
    game.Players.LocalPlayer.PlayerGui:WaitForChild("HUD");
    (game:GetService("RunService")).RenderStepped:Connect(function()
        for _, v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
            if (getgenv()).noslow then
                if v.Name == "Action" or (v.Name == "Attacking") or 
                        (v.Name == "Using") or (v.Name == "hyper") or 
                        (v.Name == "Hyper") or (v.Name == "heavy") or 
                        (v.Name == "KiBlasted") or (v.Name == "Tele") or 
                        (v.Name == "tele") or (v.Name == "Killed") or 
                        (v.Name == "Slow") then
                    v:Destroy();
                end;
                if game.Players.LocalPlayer.Character.Block.Value then
                    game.Players.LocalPlayer.Character.Block.Value = false;
                end;
            end;
        end;
    end);
end 
function noslow2()
	game:GetService("StarterGui"):SetCore("SendNotification", {
		Title = "1tsJustCmds";
		Text = "Noslow";
	})
end

local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("=ns") or cht:match("=noslow") then
		noslow()
		noslow2()
	end
end)

function freeze()
	local plr = game:GetService("Players").LocalPlayer
	local mouse = plr:GetMouse()
	local place = game.PlaceId
	Character = game.Players.LocalPlayer
	Players = game.Players.LocalPlayer.Character
	MouseFunction = game:GetService("Players").LocalPlayer:GetMouse()


	mouse.KeyDown:connect(function(key)

		if key == "k" then
			Players.Humanoid:EquipTool(Character.Backpack["Dragon Crush"])
			Players["Dragon Crush"]:Activate()
			game.Workspace.Live[Character.Name]["Dragon Crush"].Activator["Flip"]:Destroy()
			wait()

		end
	end)
	mouse.KeyDown:connect(function(key)

		if key == "k" then
			local place = game.PlaceId
			wait(0.5)
			game:GetService("TeleportService"):Teleport(place)
		end
	end)

end
function freeze2()
	game:GetService("StarterGui"):SetCore("SendNotification", {
		Title = "1tsJustCmds";
		Text = "Press K To Use";
	})
end
local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("=freeze") then
		freeze2()
		freeze()
	end
end)

function god()
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("ReplicatedStorage").ResetChar:FireServer()
    wait(0.4)
    local args = {
        [1] = "h"
    }
    
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Transform:FireServer(unpack(args))
    wait(0.4)
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    
    getgenv().showstats = true
    getgenv().Zenni = true
    getgenv().resettop = true 
    getgenv().RespawnLowKi = true
    getgenv().movespam = true;
    getgenv().noslow = true;
    getgenv().Spambans = true;
    local plr = game.Players.LocalPlayer 
end

function god2()
	game:GetService("StarterGui"):SetCore("SendNotification", {
		Title = "1tsJustCmds";
		Text = "Become A GOD";
	})
end
local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("=god") then
		god2()
		god()
	end
end)

function respawn()
	-- Script generated by SimpleSpy - credits to exx#9394

	local args = {
		[1] = workspace.FriendlyNPCs:FindFirstChild("Hair Stylist")
	}

	game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart:FireServer(unpack(args))
	-- Script generated by SimpleSpy - credits to exx#9394
	wait(.3)
	local args = {
		[1] = {
			[1] = "Yes"
		}
	}

	game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance:FireServer(unpack(args))
	wait(.3)
	-- Script generated by SimpleSpy - credits to exx#9394

	local args = {
		[1] = "woah"
	}

	game:GetService("Players").LocalPlayer.Backpack.HairScript.RemoteEvent:FireServer(unpack(args))
end
function respawn2()
	game:GetService("StarterGui"):SetCore("SendNotification", {
		Title = "1tsJustCmds";
		Text = "Fast Reseting";
	})
end

local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("=respawn") or cht:match("=re") then
		respawn2()
		respawn()
	end
end)

function rejoin()
    local place = game.PlaceId
    wait(0.1)
    game:GetService("TeleportService"):Teleport(place)
end

local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("=rejoin") or cht:match("=rj") then
		rejoin()
	end
end)

function bonecrush()
	local mouse = game.Players.LocalPlayer:GetMouse()
	mouse.KeyDown:connect(function(key)
		if key == "v" then
			local lplr = game.Players.LocalPlayer
			lplr.Character["Bone Crush"].Activator.Crash:Destroy()
		end
	end)
end

function bonecrush2()
	game:GetService("StarterGui"):SetCore("SendNotification", {
		Title = "1tsJustCmds";
		Text = "Pressing V while bone crush equipped will";
	})
end
local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("=bonecrush") or cht:match("=bc") then
		bonecrush2()
		bonecrush()
	end
end)

function antiq()
    game.Workspace["Wormhole"].TouchInterest:Destroy()
end

function antiq2()
    		game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = "1tsJustCmds";
			Text = "Anti-Queue";
		})
end

Player.Chatted:connect(function(cht)
	if cht:match("=antiq") then
		antiq2()
		antiq()
	end
end)

function invis()
    local lplr = game.Players.LocalPlayer  
    Players = game.Players.LocalPlayer.Character
      Character = game.Players.LocalPlayer
      
      Players.Humanoid:EquipTool(Character.Backpack["Flash Strike"])
         Players["Flash Strike"]:Activate()
     lplr.Character["Flash Strike"].Activator.Animation:Destroy()
end

function invis1()
game:GetService("StarterGui"):SetCore("SendNotification", {
          Title = "1tsJustCmds";
          Text = "U are Invisible";
      })
end

Player.Chatted:connect(function(cht)
  if cht:match("=invis") then
invis1()
invis()
end
end)

function hidelvl()
    game.Players.LocalPlayer.Character:FindFirstChildOfClass("Model"):Destroy()
end

function hidelvl1()
     game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = "1tsJustCmds";
			Text = "LvL hider";
		})
end

Player.Chatted:connect(function(cht)
	if cht:match("=hidelvl") then
hidelvl1()
hidelvl()
end
end)

function wings()
    while wait() do
	        pcall(function()
	            game.Players.LocalPlayer.Character:FindFirstChild('RebirthWings').Handle:Destroy()
	        end)
    end
end
function hidewingsx()
game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = "1tsJustCmds";
			Text = "Wings Removed";
		})
end
Player.Chatted:connect(function(cht)
	if cht:match("=rwings") then
hidewingsx()
wings()
end
end)

function halo()
    while wait() do
	        pcall(function()
	            game.Players.LocalPlayer.Character:FindFirstChild('RealHalo').Handle:Destroy()
	        end)
    end
 end
function halox()
game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = "1tsJustCmds";
			Text = "Halo Removed";
		})
end
Player.Chatted:connect(function(cht)
	if cht:match("=rhalo") then
halox()
halo()
end
end)

function godmode()
    game:GetService("RunService").Stepped:Connect(function()
firetouchinterest(game.Players.LocalPlayer.Character.HumanoidRootPart, game.Workspace.Touchy.Part, 0)
firetouchinterest(game.Players.LocalPlayer.Character.HumanoidRootPart, game.Workspace.Touchy.Part, 1)
if game.Players.LocalPlayer.PlayerGui:FindFirstChild("Popup") then
game.Players.LocalPlayer.PlayerGui.Popup:Remove()
end end)
end

function godmode2()
    		game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = "1tsJustCmds";
			Text = "Godmode Only Earth";
		})
end
Player.Chatted:connect(function(cht)
	if cht:match("=godmode") or cht:match("=gm") then
		godmode2()
		godmode()
	end
end)

function commands()
    print ("=freeze Press K")
    print ("=dc Press K")
    print ("=rj for rejoin")
    print ("=gm (only earth)")
    print ("=rhalo for remove halo")
    print ("=rwings for remove wings")
    print ("=hidelvl hide level")
    print ("=invis become invisible")
    print ("=antiq antiqueue")
    print ("=bonecrush / =bc for bc glich")
    print ("=re fast reset (only earth)")
    print ("=god for GOD form and UI and MUI")
    print ("=iy for infinite Yield")
    print ("=anch for anchor")
    print ("=unanch for unanchor")
    print ("=earth")
	print ("=namek")
	print ("=space")
	print ("=future")
	print ("=secret")
	print ("=zaros")
	print ("=queue")
	print ("=heaven")
	print ("=south for tp south city")
	print ("=west tp west city")
	print ("=central tp central city")
	print ("=hr for hard reset")
	print ("=1tsjusthub for use my hub")
	print ("=qk for queue kick")
	print ("=slot and select u the slot after")


end

Player.Chatted:connect(function(cht)
	if cht:match("=cmds") then
		commands()
	end
end)

function IY()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()

end

Player.Chatted:connect(function(cht)
	if cht:match("=iy") then
		IY()
	end
end)

function anch1()
    game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = true 

end

function anch()
     game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = "1tsJustCmds";
			Text = "Anchored Player";
		})
end

Player.Chatted:connect(function(cht)
	if cht:match("=anch") or cht:match("=anchor") then
        anch1()
        anch()
    end
end)

function unanch1()
    game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = false 

end

function unanch()
     game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = "1tsJustCmds";
			Text = "Unanchored Player";
		})
end

Player.Chatted:connect(function(cht)
	if cht:match("=unanch") or cht:match("=unanchor") then
        unanch1()
        unanch()
    end
end)

function earth()
    game:GetService("TeleportService"):Teleport(536102540)
end



Player.Chatted:connect(function(cht)
	if cht:match("=earth") then
		earth()
	end
end)

function namek()
    game:GetService("TeleportService"):Teleport(882399924)
end



Player.Chatted:connect(function(cht)
	if cht:match("=namek") then
		namek()
	end
end)

function space()
    game:GetService("TeleportService"):Teleport(478132461)
end



Player.Chatted:connect(function(cht)
	if cht:match("=space") then
		space()
	end
end)

function future()
    game:GetService("TeleportService"):Teleport(569994010)
end



Player.Chatted:connect(function(cht)
	if cht:match("=future") then
		future()
	end
end)

function secret()
    game:GetService("TeleportService"):Teleport(2046990924)
end



Player.Chatted:connect(function(cht)
	if cht:match("=secret") then
		secret()
	end
end)

function zaros()
    game:GetService("TeleportService"):Teleport(2651456105)
end



Player.Chatted:connect(function(cht)
	if cht:match("=zaros") then
		zaros()
	end
end)

function queue()
    game:GetService("TeleportService"):Teleport(3565304751)
end



Player.Chatted:connect(function(cht)
	if cht:match("=queue") then
		queue()
	end
end)

function heaven()
    game:GetService("TeleportService"):Teleport(3552157537)
end



Player.Chatted:connect(function(cht)
	if cht:match("=heaven") then
		heaven()
	end
end)

function hardreset()
	local Player = game:GetService("Players").LocalPlayer
	local Mouse = Player:GetMouse()
	
		   Player.Character.Humanoid.Health = 0
	
end

local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("=hr") then
		hardreset()
	end
end)

function myhub()
loadstring(game:HttpGet(("https://raw.githubusercontent.com/gp1tsJust/1tsJustHub-V2-DBZ/main/README.md"), true))()
	
end

local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("=1tsjusthub") then
		myhub()
	end
end)

function queue1()
	local plr = game:GetService("Players").LocalPlayer
	local mouse = plr:GetMouse()
	local place = game.PlaceId
	Character = game.Players.LocalPlayer
	Players = game.Players.LocalPlayer.Character
	MouseFunction = game:GetService("Players").LocalPlayer:GetMouse()


	mouse.KeyDown:connect(function(key)

		if key == "k" then
			Players.Humanoid:EquipTool(Character.Backpack["Dragon Crush"])
			Players["Dragon Crush"]:Activate()
			game.Workspace.Live[Character.Name]["Dragon Crush"].Activator["Flip"]:Destroy()
			
			wait (0.2)
			
			game.Workspace["Wormhole"].TouchInterest:Destroy()
			
			wait(2)
			
			game:GetService("TweenService"):Create(
           game.Players.LocalPlayer.Character.HumanoidRootPart,
           TweenInfo.new(1.2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
           {CFrame = CFrame.new(2656.7854, 3946.00439, -2515.78467, 0.969526529, 0, -0.244986445, -0, 1, -0, 0.244986445, 0, 0.969526529)}
           ):Play()
            
            
            

		end
	end)
end 
function queue2()
game:GetService("StarterGui"):SetCore("SendNotification", {
Title = "1tsJustCmds";
Text = "Queue Kick Press K";
})
end
local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
if cht:match("=qk") then
queue2()
queue1()
end
end)

function south()
	game:GetService("TweenService"):Create(
		game.Players.LocalPlayer.Character.HumanoidRootPart,
		TweenInfo.new(1.2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
		{CFrame = CFrame.new(-456, 28, -6412)}
		):Play()
		
	end
	
	local Player = game.Players.LocalPlayer
	Player.Chatted:connect(function(cht)
		if cht:match("=south") then
			south()
		end
	end)

	function west()
		game:GetService("TweenService"):Create(
			game.Players.LocalPlayer.Character.HumanoidRootPart,
			TweenInfo.new(1.2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
			{CFrame = CFrame.new(-570, 23, -2884)}
			):Play()
			
		end
		
		local Player = game.Players.LocalPlayer
		Player.Chatted:connect(function(cht)
			if cht:match("=west") then
				west()
			end
		end)

		function centrals()
			game:GetService("TweenService"):Create(
				game.Players.LocalPlayer.Character.HumanoidRootPart,
				TweenInfo.new(1.2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
				{CFrame = CFrame.new(-3834, 23, -1428)}
				):Play()
				
			end
			
			local Player = game.Players.LocalPlayer
			Player.Chatted:connect(function(cht)
				if cht:match("=central") then
					centrals()
				end
			end)


			function slot()
				-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = workspace.FriendlyNPCs:FindFirstChild("Character Slot Changer")
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart:FireServer(unpack(args))

wait(0.6)

-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = {
        [1] = "Yes"
    }
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance:FireServer(unpack(args))

wait(0.5)

-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = {
        [1] = "k"
    }
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance:FireServer(unpack(args))


					
				end
				
				local Player = game.Players.LocalPlayer
				Player.Chatted:connect(function(cht)
					if cht:match("=slot") then
						slot()
					end
				end)







