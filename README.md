# -3-DICAS-PARA-WINDOWS-MELHORAR-

1 _ Máximo desempenho
 digite CMD: 

```powershell
irm "powercfg -duplicatescheme e9a42b02-d5df-448d-aa00-03f14749eb61" | iex
```

2-Modo seguro
digite modo Adiministrador CMD: 
```
irm "bcdedit /set {default} bootmenupolicy legacy" | iex
```
3- Diminui Consumo de recursos
digite no powershell: 
```
irm "Get-AppxPackage | where-object {$_.name –notlike “*store*”} | Remove-AppxPackage" | iex
```
