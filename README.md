-- Infinite Stats Script for DBZFS

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local stats = character:WaitForChild("Stats")

-- Infinite Strength, Speed, and Energy
stats.Strength.Value = math.huge
stats.Speed.Value = math.huge
stats.Energy.Value = math.huge

-- Continuously update the stats to infinite
while true do
    wait(0.1) -- Update every 0.1 seconds to avoid lag
    stats.Strength.Value = math.huge
    stats.Speed.Value = math.huge
    stats.Energy.Value = math.huge
end
https://raw.githubusercontent.com/YourUsername/RobloxScripts/main/InfiniteStatsScript.lua
