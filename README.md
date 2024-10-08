# OneNKode - Rendszerfigyelő Alkalmazás
![Python Version](https://img.shields.io/badge/python-3.6%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

first run : requirementsV1.1.cmd 

**NDXworks** egy egyszerű, de hatékony parancssori rendszerfigyelő alkalmazás, amely valós időben megjeleníti a rendszer erőforrásainak állapotát és statisztikáit. A programot Python nyelven írtuk, és a PyInstaller segítségével készült egy önálló végrehajtható fájl (.exe), amely Windows rendszeren futtatható.

## Funkciók

### 1. CPU Használat Monitorozása
- Az alkalmazás valós időben nyomon követi a CPU használatát és színesen jeleníti meg a százalékos értéket:
  - **Zöld**: 0% - 49%
  - **Sárga**: 50% - 74%
  - **Piros**: 75% - 100%

### 2. Memória Használat Monitorozása
- Valós időben megjeleníti a memória használatát, szintén színesen:
  - **Zöld**: 0% - 49%
  - **Sárga**: 50% - 74%
  - **Piros**: 75% - 100%

### 3. GPU Információk
- Az alkalmazás lekérdezi és megjeleníti a telepített GPU(k) nevét és memóriáját. Ha nincs elérhető GPU, az alkalmazás jelzi ezt is.

### 4. Lemezhasználat Monitorozása
- Megjeleníti a lemezhasználatot százalékos formában és az összes elérhető lemezkapacitást.

### 5. Hálózati Használat Monitorozása
- Az alkalmazás megjeleníti az összesített be- és kimenő hálózati forgalmat MB-ban.

### 6. Rendszerinformációk
- A rendszerinformációkat tartalmazó szakasz megjeleníti a következőket:
  - **Operációs rendszer**: Windows verzió és kiadás
  - **CPU**: CPU típusa és magok száma
  - **Teljes RAM**: Rendszer memóriája GB-ban

### 7. Ikon és Verzió
- Az alkalmazás ikont tartalmaz, amely az `assets/icon.ico` fájlban található.
- A verziószám a kijelző tetején található (`V1.4`).

## Képernyőképek

Az alábbiakban láthatók a program képernyőképei, amelyek bemutatják, hogyan néz ki a felhasználói felület és a rendszerinformációk:
requirementsV1.1.cmd:



![image](https://github.com/user-attachments/assets/7c454f27-bd3d-4950-ab45-8a9305b56858)

the system monitor:




<img width="430" alt="image" src="https://github.com/user-attachments/assets/dac90874-12e8-4730-9f1c-7e14c3ccb4bb">

## Közreműködés

Kérjük, olvasd el a [Hozzájárulási irányelvek](CONTRIBUTING.md) dokumentumot, ha szeretnél hozzájárulni a projekthez.


Kérlek, ha bármilyen kérdésed van a program működésével vagy telepítésével kapcsolatban, ne habozz megkérdezni!


