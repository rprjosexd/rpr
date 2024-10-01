
# ¿Que fa rprjose?
En aquesta pagina os mostrare tot el que fa el streamer rprjose, i les coses que fa hi ha jocs també programació i diverses coses més!!!

![Imatge de rprjose](Imatges/rprjose.jpeg)


1. [Battle Guys](BattleGuys.md)
2. [Roblox](roblox.md)







# Roblox Studio
**Aqui os deixo un codigo de si utilitzes Roblox Studio et servira. Per quand un usuari toqui un bloque es mort**

```Script Roblox Studio
// function onTouched(part)
 local h = part.Parent:findFirstChild("Humanoid")
 if h~=nil then
  h.Health = h.Health-100
 end
end
script.Parent.Touched:connect(onTouched)
}
```
