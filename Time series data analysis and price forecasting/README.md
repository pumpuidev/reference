Tesztfeladat: Idősoros adatelemzés és ár előrejelzés

Feladatleírás:
Adott egy szintetikus, 5 éves napi adatsor egy európai nagykereskedelmi villamosenergia-piacról, amely az alábbi változókat tartalmazza:
DATE: Az adott kereskedési nap.
PRICE-AVG: Adott napi átlagár (€/MWh).
PRICE-MIN, PRICE-MAX: Az adott napi árfolyam-ingadozás.
TEMP, PREC: Napi átlaghőmérséklet és csapadék mennyisége.

1. Adattisztítás és előfeldolgozás:
Vizsgálja meg a hiányzó vagy hibás értékeket, és indokolja a kiválasztott imputációs, illetve kiugróérték-kezelési módszereket!
Normalizálja/adattranszformálja a változókat, ha szükséges!

2. Exploratory Data Analysis (EDA):
Vizualizálja az árak időbeli alakulását, azonosítsa a trendeket, szezonális hatásokat és ciklikusságot!
Elemezze, hogyan függ az árak alakulása az időjárási tényezőktől!

3. Előrejelző modell kidolgozása:
Válasszon egy időjárási komponenseket is figyelembe vevő előrejelzési modellt (pl. SARIMAX, Prophet, vagy gépi tanulási alapú modell) a következő 30 nap árának becslésére!
Indokolja a választott modell megközelítését, valamint a paraméterek beállítását!
Mutassa be a modell teljesítményét valamilyen, az adatsor jellegéhez illeszkedő metrikával (pl. MAE, RMSE)!

4. Eredmények interpretációja:
Írjon egy rövid szöveges elemzést, amelyben az eredmények alapján összefoglalja a főbb megállapításokat, a modell erősségeit és gyengeségeit, valamint javaslatokat tesz a továbbfejlesztésre!

5. Eredményfájl:
Az előző pontokat egy futtatható Python vagy R programnyelven megírt fájlban kérjük prezentálni. A szöveges elemzést és kiegészítő magyarázatokat is a kódban, kommentként kérjük megadni.
