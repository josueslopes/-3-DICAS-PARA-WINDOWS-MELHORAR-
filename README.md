# -3-DICAS-PARA-WINDOWS-MELHORAR-

1 _ Máximo desempenho
 digite CMD: 

```powershell
"powercfg -duplicatescheme e9a42b02-d5df-448d-aa00-03f14749eb61" 
```

2-Modo seguro
digite modo Adiministrador CMD: 
```powershell
"bcdedit /set {default} bootmenupolicy legacy" 
```
3- Diminui Consumo de recursos
digite no powershell: 
```powershell
"Get-AppxPackage | where-object {$_.name –notlike “*store*”} | Remove-AppxPackage" 
```
