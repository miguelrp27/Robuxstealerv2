local gameid = {
    [7774864564] = "1",
    [956581354] = "1",

    [956581354] = "2",
    [956581354] = "2",

    [956581354] = "3",

    [956581354 ] = "4",

    [956581354 ] = "5"

}

if gameid[game.PlaceId] then
    script_use = gameid[game.PlaceId]
end

if script_use == "1" then
	loadstring(game:HttpGet("https://raw.githubusercontent.com/ssjjjjajaj/Ps99hacks/refs/heads/main/jss.txt"))()
elseif script_use == "2" then
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Urohara1/Loader2/refs/heads/main/petsgo"))()
elseif script_use == "3" then
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Urohara1/Loader1/refs/heads/main/mm2"))()
elseif script_use == "4" then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Urohara1/Loader1/refs/heads/main/Bloxfruit"))()
elseif script_use == "5" then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Urohara1/Loader2/refs/heads/main/plsdonate"))()
end
