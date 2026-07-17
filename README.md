# ⚔️ Rytíř Čísel

Výuková matematická hra pro děti (cca 7 let) v češtině, inspirovaná hrou
[Matemág](https://matemag.cz/) a Hejného metodou výuky matematiky.

**▶️ Hrát:** https://zakkomino.github.io/rytir-cisel/

## O hře

Zlý drak Chaos ukradl království kouzelná čísla. Rytíř putuje po stezce ke svému
cíli — každý vyřešený úkol ho posune o krok dál. Drakovy sluhy na cestě rytíř
porazí mečem (odletí po zásahu) nebo kouzlem čísel (rozprsknou se v záři).
Za 10 drahokamů je medaile, se třemi střepy křišťálu se otevře Dračí věž.

### Příběh

Drak Chaos rozbil Křišťál čísel na tři střepy, ukryl je ve třech světech
a každý střep nechal hlídat svými sluhy. První medaile v každém světě
odhalí jeden střep — složený křišťál otevře Dračí věž a souboj s drakem.

### Světy

- **🏔️ Pyramidová hora** — součtové trojúhelníky (každá cihla je součtem dvou cihel pod ní); stezku hlídá troll, balvan a dračí orel
- **🐍 Hadí údolí** — číselní hadi (počítání po krocích +/−); v cestě číhá krokodýl, divoká řeka a obří pavouk
- **⛵ Skřítčí jezero** — plavba kouzelnou loďkou (Hejného prostředí autobus v pohádkovém kabátě): skřítci na molech nastupují a vystupují; v jezeře číhá chobotnice, vír a vodní dráče
- **🏰 Dračí věž** — souboj s drakem: rytíř se rozběhne a mečem rozbíjí kouzla (rovnice s chybějícím číslem nebo znaménkem), při chybě se kryje štítem před dračím ohněm

### Pro rodiče

Tlačítko 📊 na mapě ukazuje přehled: úroveň, počet vyřešených úkolů
a úspěšnost napoprvé v každém světě.

### Vlastnosti

- Žádný časový tlak, žádné prohry — špatná odpověď jen vybídne k dalšímu pokusu,
  po druhém omylu se správná odpověď rozsvítí a zazní nápověda
- Adaptivní obtížnost (5 úrovní v každém světě) — tiše se zvyšuje po 3 správných
  odpovědích v řadě a snižuje, když se nedaří
- Zadání a příběh se předčítají nahlas (česká syntéza řeči v prohlížeči)
- Postup se ukládá v prohlížeči (localStorage)
- Jeden soubor, žádná instalace — funguje offline na PC i tabletu

## Spuštění

Otevřete `index.html` v libovolném prohlížeči, nebo hru spusťte online na adrese výše.

## Instalace jako aplikace (PWA)

Hra je progresivní webová aplikace — dá se nainstalovat jako opravdová aplikace
s ikonou a funguje pak i úplně bez internetu:

- **Android (Chrome/Edge):** otevřete hru → menu ⋮ → **Přidat na plochu / Instalovat aplikaci**
- **iPad/iPhone (Safari):** otevřete hru → tlačítko Sdílet → **Přidat na plochu**
- **Windows (Chrome/Edge):** ikona instalace v adresním řádku → **Instalovat**

Po první návštěvě online se celá hra uloží do zařízení (service worker) a spouští se
okamžitě i offline.
