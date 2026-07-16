# ⚔️ Rytíř Čísel

Výuková matematická hra pro děti (cca 7 let) v češtině, inspirovaná hrou
[Matemág](https://matemag.cz/) a Hejného metodou výuky matematiky.

**▶️ Hrát:** https://zakkomino.github.io/rytir-cisel/

## O hře

Zlý drak Chaos ukradl království kouzelná čísla. Rytíř putuje po stezce ke svému
cíli — každý vyřešený úkol ho posune o krok dál a zažene překážky (troll, balvan,
krokodýl…). Za 10 drahokamů je medaile, se dvěma medailemi se otevře Dračí věž.

### Příběh

Drak Chaos rozbil Křišťál čísel na tři střepy a ukryl je ve třech světech.
První medaile v každém světě odhalí jeden střep — složený křišťál otevře
Dračí věž a souboj s drakem.

### Světy

- **🏔️ Pyramidová hora** — součtové trojúhelníky (každá cihla je součtem dvou cihel pod ní)
- **🐍 Hadí údolí** — číselní hadi (počítání po krocích +/−)
- **🚌 Kouzelný autobus** — Hejného prostředí autobus: cestující přistupují a vystupují
- **🏰 Dračí věž** — souboj s drakem: rozbíjení kouzel (rovnice s chybějícím číslem nebo znaménkem)

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
