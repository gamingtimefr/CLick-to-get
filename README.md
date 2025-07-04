# CLick-to-get
roblox
--by Gamingtime--


CODE




-- instructions:
-- 1) take your tool and put it in ServerStorage
-- 2) in the script below, change the word in brackets & quotations to the name of your tool
-- 3) dont touch anything else in the script!



local tool = game.ServerStorage["tool"] -- change "tool" to your tool name
local klone = tool:clone()
script.Parent.ClickDetector.MouseClick:connect (function(plr)
if klone.Parent ~= plr.Backpack then
klone.Parent = plr.Backpack
else
end
end)

---DoNOT EDIT EDIT TOOL
