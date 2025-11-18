# SIEM-Wazuh
V rámci tréningu a vzělávání jsem se rozhodl nakonfigurovat a zprovoznit si SIEM Wazuh. 
Hlavní host jsem vytvořil v OS Ubuntu 24.04.3 LTS
Pro praktičnost jsem vytvořil jednoho agenta ve WM přes GNUbuntu 24.04.01
Agent musel být vytvořen ve VM protože na stejném zařízení se to mlátilo v adresářích s host files kam potřebují oba přistupovat.
Po nastavení hosta jsem začal objevovat alerty, které se vytvořily díky defaultním pravidlům. Z mého zjištění většina alertů byla vygenerévána faktem že se jedná o VM. Konkrétní alert byl třeba "nesrovnalost mezi počtem souborů v adresáři a link countem" standartně by to evokovalo podeřelou aktivitu v souborovém systému ale tady je to zapřičíněno virtualizací.
Aktuálně pracuji na tom abych se naučil tvořit svá jednoduchá pravidla, která budu samozřejmě testovat a zaznamenávat zde v repozitáři
