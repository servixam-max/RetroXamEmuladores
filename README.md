# RetroXam — Emuladores para AYN Thor

Pack de **Obtainium** con los **34 emuladores** recomendados para emular con la app
[Arley4d Bypass](https://play.google.com/store/apps/details?id=com.arley4d.bypassarley4d)
en un **AYN Thor** (u otro Android handheld).

## Qué incluye

| Sistema | Emulador(es) |
|---|---|
| **Frontend** | **iiSU** (el launcher), ES-DE Custom Systems |
| **Arcade** (fbneo, cps1/2/3, neogeo, mame) | **MAME4droid Current**, RetroArch |
| **Dreamcast / Naomi / Atomiswave / Model 2-3** | **Flycast** |
| **PSX** | **DuckStation** |
| **PS2** | **NetherSX2** (+ Classic y Turnip) |
| **PS3** | **ARMSX3**, aPS3e, RPCSX |
| **PSP** | **PPSSPP** |
| **PSVita** | **Vita3K** |
| **SNES** | RetroArch / SkyEmu |
| **NES** | RetroArch |
| **GB / GBC / GBA** | RetroArch / SkyEmu |
| **NDS** | **MelonDS** + **WatermelonDS** (2 pantallas) + SeedlessDS |
| **3DS** | **Azahar** + **AzaharDS** (2 pantallas) |
| **N64** | RetroArch / Gopher64 |
| **GameCube / Wii** | **Dolphin** |
| **Wii U** | **Cemu Dual-Screen** (2 pantallas) |
| **Switch** | Eden, Citron Neo |
| **Xbox** | Xemu (X1 BOX), hakuX |
| **Xbox 360** | X360 Mobile, Xendroid |
| **OpenBOR** | OpenBOR |
| **Drivers GPU** | Adreno-Tools-Drivers, Mr. Purple Turnip |

## Cómo usarlo

1. Instala **Obtainium** en el Thor: https://github.com/ImranR98/Obtainium/releases
2. Descarga el archivo **`retroxam-emuladores.json`** de este repo (botón "Download raw file").
3. En Obtainium: menú → **Import/Export** → **Import Apps** → elige el JSON.
4. Ya tienes los 34 emuladores listados. Pulsa **Install** en los que quieras:
   - Los marcados como **Track Only** (drivers/XML) no se instalan, solo se vigilan.
   - Los de **HTML source** (Dolphin, DuckStation, PPSSPP, RetroArch, Eden) se actualizan
     desde sus webs oficiales.
5. Obtainium avisará de nuevas versiones automáticamente.

## Los que NO están (y por qué)

- **M64Plus FZ** (N64) — solo existe en Play Store, se instalaba desde GitHub sin APK.
  → Búscalo en Google Play: "M64Plus FZ".
- **Yaba Sanshiro 2** (Saturn) — solo en Play Store: "Yaba Sanshiro 2".
- **DraStic** — de pago y descontinuado; usa MelonDS/WatermelonDS.

## Emparejar con Arley4d

1. En **Arley4d** → *Frontends compatibles* → **Cambiar emuladores.json** (apunta iisu a Arley).
2. En **iisu** → por consola → *Detectar emulador*.
3. Con este pack instalas los emuladores; Arley4d los lanza.

---
Hecho para el ecosistema **RetroXam** — listas: `github.com/servixam-max/RetroXam`
