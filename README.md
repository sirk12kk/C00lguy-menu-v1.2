local url = "https://raw.githubusercontent.com/<usuario>/<repositorio>/main/menu.lua" -- Substitua pelo URL bruto do script
local response = game:HttpGet(url, true)
loadstring(response)()
