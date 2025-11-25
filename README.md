# Feladatsor – Windows Server és kliensoldali hálózati környezet kialakítása

## 1. VirtualBox környezet előkészítése
- Készíts egy Windows Server virtuális gépet a megfelelő hardverbeállításokkal.
- Állítsd be a hálózati adaptereket az óraterven meghatározott módon.
- Csatold be a szükséges telepítőlemez képfájlt.

## 2. Szerver alapbeállításai
- Konfiguráld a szerver hálózati kártyáit.
- Állíts be statikus IP-címet a szerver számára a megadott tartomány utolsó kiosztható címével.
- Add meg a szerver nevét az előírt módon.
- Telepítsd a szükséges szerepköröket és szolgáltatásokat.

## 3. Kliensgép alapbeállításai
- Állítsd be a kliensgép hálózati kártyáját a megadott tartomány szerint.
- Konfigurálj statikus IP-címet a kliens számára vagy DHCP-vel lépj be a hatókörbe.
- Nevezd át a klienst a megadott névre.

## 4. DHCP-szerver és hatókör konfigurálása
- Hozz létre DHCP-hatókört, amely legfeljebb 10 IP-címet oszt ki.
- Állítsd be a tiltólistát úgy, hogy az első három cím tiltott legyen.
- Állítsd be a megfelelő alapértelmezett átjárót.

## 5. Távoli asztal beállítása
- Engedélyezd a távoli asztal funkciót a szerveren.
- Teszteld a kapcsolatot egy kliensgépről.
