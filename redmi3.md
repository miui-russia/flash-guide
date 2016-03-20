# Installer Xiaomi.eu-programvare for Redmi 3
1. Lås opp din Mi-enhet: http://en.miui.com/unlock/index.html
2. Installer Xiaomi USB drivere fra Mi PC Suite: http://pcsuite.mi.com/
3. Last ned og installer Android ADB og fastboot herfra: http://forum.xda-developers.com/showthread.php?p=48915118
4. Last ned TWRP herfra (Redmi 3 er TWRP_IDO.zip) og legg fila i **C:\ADB**: https://www.androidfilehost.com/?w=files&flid=50678
6. Start enheten i fastboot-modus ved å trykke og holde volum ned + På-knappen
7. Koble telefonen til PCen med USB-kabel
8. Søk etter cmd i Windows søkefeltet og høyreklikk på det => "Kjør som administrator".
9. Skriv inn i ledeteksten: **cd C:\ADB** og trykk Enter for å gå til ADB-mappen.
10. Skriv inn i ledeteksten: **fastboot devices**, og trykk på Enter for å være sikker på at enheten blir gjenkjent.
11. Skriv inn i ledeteksten: **fastboot flash recovery recovery.img** og trykk Enter for å flashe recovery.
12. Skriv inn i ledeteksten: **fastboot boot recovery.img** og trykk på Enter for å gå til installasjonsskjermbildet.
13. Last ned og installer programvare for Redmi 3 (ido): https://www.androidfilehost.com/?fid=24459283995300351
