# Radius Project

**Geautomatiseerd RGBW kweeklicht systeem voor 3 onafhankelijke kweekkamers**

---

## Project openen in TIA Portal

### Vereisten
- TIA Portal V20 of hoger
- Siemens S7-1200 hardwarepakket geïnstalleerd
- TP700 Comfort HMI pakket geïnstalleerd
- ET 200SP pakket geïnstalleerd

### Stappen

1. Open **TIA Portal V20**
2. Klik op **"Open existing project"**
3. Klik op **"Browse"**
4. Selecteer het `Radius_Project.zap20` bestand
5. Kies een lokale map om het project in uit te pakken
6. Klik op **"Retrieve"**

> **Let op:** Optimized block access moet **uitgeschakeld** zijn op LED_DB_K1, LED_DB_K2 en LED_DB_K3. Controleer dit via: Data block → rechtermuisknop → Properties → Attributes.

> **Let op:** PUT/GET communicatie moet **ingeschakeld** zijn op de PLC. Controleer dit via: PLC_1 → Device configuration → Protection & Security → "Permit access with PUT/GET communication from remote partner".

> **Let op:** "Only allow secure PG/PC and HMI communication" moet **uitgeschakeld** zijn.
