# acidity-v3-client
Updates will be posted here.

**Execute latest version:**\
getgenv().key = ""; -- whitelist key goes here\
loadstring(game:HttpGet("https://api.acidity.emeraldsys.xyz/v1/auth/whitelist/script?key=" .. getgenv().key, true))();

OR

**Execute pre-release version:**\
getgenv().key = ""; -- whitelist key goes here\
loadstring(game:HttpGet("https://api.acidity.emeraldsys.xyz/v1/auth/whitelist/script?key=" .. getgenv().key .."&isPre=true", true))();
