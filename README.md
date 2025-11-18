# SIEM Wazuh – Tréninkový projekt

## Úvod
V rámci tréninku a vzdělávání jsem se rozhodl nakonfigurovat a zprovoznit SIEM **Wazuh**.  
Cílem je naučit se pracovat s alerty, pravidly a správou agentů.
## Prostředí
- **Host**: Ubuntu 24.04.3 LTS  
- **Agent**: GNUbuntu 24.04.01 ve virtuálním stroji (VM)  
  - VM bylo nutné kvůli konfliktům v adresářích host files.
## Alerty
Po základní konfiguraci se začaly objevovat alerty z defaultních pravidel.  
Většina byla způsobena tím, že agent běží ve VM.  
Příklad alertu: *„Nesrovnalost mezi počtem souborů v adresáři a link countem“*  
→ v běžném prostředí by to mohlo znamenat podezřelou aktivitu, zde je to dáno virtualizací.
## Další kroky
- Naučit se tvořit vlastní jednoduchá pravidla.  
- Testovat je a zaznamenávat výsledky přímo v tomto repozitáři.
