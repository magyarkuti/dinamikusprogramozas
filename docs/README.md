{% include head.html %}

## Az órákon elhangzott fontosabb fogalmak (Tételjegyzék) 
A Corvinus egyetem Matematika Tanszékének Dinamikus Programozás előadásai a 2024-2025 tanév tavaszi félévében.

Az órák: 
   * szerda 17.20-18.50 az CIX teremben
   * csütörtök: 08:00-9.30 a C101 teremben

## Jegyzetek
Az előadások anyaga: [Mértékelmélet és Dinamikus Programozás (v1.5-28)](http://www.bke.hu/magyarkuti/main.pdf).
Itt javítom a megjelenés óta talált hibákat elírásokat, ezért ajánlom a fenti jegyzet letöltését.
Kötelességem feltüntetni a kiadói jogok tulajdonosát az eredeti változat megjelölésével: 
[Mértékelmélet és Dinamikus Programozás, TypoTeX 2014](https://dtk.tankonyvtar.hu/xmlui/handle/123456789/3221).

Ajánlott olvasmányok: 
   * [Nancy L. Stokey and Robert E. Lucas Jr. with Erward C. Prescott: Recursive Methods in Economic Dynamics](https://www.amazon.com/gp/reader/0674750969/ref=sib_dp_pt#reader-link)
   * [ Lars Ljungqvist, Thomas J. Sargent: Recursive Macroeconomic Theory](http://www.amazon.com/Recursive-Macroeconomic-Theory-Lars-Ljungqvist/dp/0262194511/ref=sr_1_1?ie=UTF8&s=books&qid=1233988909&sr=8-1)

## Számonkérés
Szóbeli vizsga a szemeszter végén

## Az órákon elhangzott legfontosabb fogalmak egyben tételjegyzék
   
1. Szuprémum probléma és a Bellman-egyenlet 
   * Állapot tér, hozadék függvény, rákövetkező függvény, diszkont tényező
   * Megengedett út, vagy terv; út hasznossága
   * Alapfeltevések, speciálisan korlátos hozadék függvény, és <math>0\leq \beta<1</math> esetben
   * Szupremum feladat (SP) formalizációja
   * Érték függvény és optimális út
   * Bellman-egyenlet
   * Indukciós lemma
   * Optimális út jellemzése
   * (SP) értékfüggvénye egyben a Bellman-egyenlet megoldása
   * A Bellman-egyenlet megoldása egyben (SP) értékfüggvénye
   * Policy leképezés, Optimal policy leképezés
   * Korlátos pillanatnyi hasznosság függvény és <math>\beta<1</math> diszkont tényező mellett, egy pálya pontosan akkor optimális, ha azt az op-leképezés generálja

1. Az (SP) feladat és a Bellmann-egyenlet illusztrációja 
Három modell arra szolgál, hogy szokjuk a fogalmakat és lássuk a fent bizonyított állítások mellékfeltételeinek p(f)ontosságát:
   * Fő a változatosság
   * Befektés-megtakarítás-modell
   * Megtakarítás-modell

1. A Bellman-egyenlet megoldása mint fixpont
   * Korlátos hozam függvény és beta<1 mellett
   * Blackwell-lemma
   * Bellman-operátor
   * Bellman-operátor monotonitása és konkavitása
   * Berge-tétel alkalmazása
   * Bellman-egyenlet egyetlen megoldásának folytonossága
   * Bellman-egyenlet egyetlen megoldásának monotonitása és folytonossága
   * Bellman-egyenlet egyetlen megoldásának szigorú konkavitása
   * Az optimális policy függvény folytonossága és egyértékűsége

1. A Bellman-egyenlet megoldásának közelítése
   * Berge-tétel értékfüggvényének pontonkénti és egyenletes közelítése
   * A Bellman-egyenlet megoldásának pontonkénti és egyenletes közelítése, kompaktsági feltétel mellett
  
1. Differenciálhatósági feltételek
   * Lemma a grafikon konvexitásáról
   * Konvex függvény szubderiváltja
   * Lemma a konvex függvény differenciálhatóságáról
   * Lemma a konkáv halmazértékű leképezés belső pontjáról
   * A programozás értékfüggvényének deriváltja a Bellman-egyenlet konkáv megoldásának esetében
   * A (SP) feladat belső optimális megoldásának fogalma
   * Az Euler-egyenlet szükségessége
   * Transzverzalitási feltétel
   * A transzverzalitási feltétel és az Euler-egyenlet elegendősége
   * A transzverzalitási feltétel szükségessége

1. Stabilitás
   * Globális stabilitás fogalma
   * Ljapunov-függvény
   * A Ljapunov-függvény létezése a globális stabilitás elegendő feltétele
   * Egy Ljapunov--függvény jelölt
   * Lineáris rendszer stabilitása

1. Markov-transzformáció
   * Meta-Dynkin-tétel
   * Sztochasztikus mag fogalma
   * Markov-transzformáció fogalma
   * Markov-transzformáció tulajdonságai, a monton konvergencia tétel alapján
   * Mérhető függvény Markov-transzformáltja is mérhető

1. Sztochasztikus magok szorzata
   * A szorzat fogalma
   * Fubini-tétel sztochasztikus magokra

1. Átmenet függvények magszorzata
   * Átmenet függvény fogalma
   * Fubini-tétel alkalmazása átmenet függvényekre
   * Az átmenet függvényeknek mint sztochasztikus magoknak szorzata

1. Markov-operátor
   * Az átmenet függvény szorzat fogalma
   * Markov-operátor fogalma
   * Adjungált Markov-operátor fogalma
   * Asszociatív szabály
   * Kiterjesztett asszociatív szabály
   * Chapmann-Kolmogorov-azonosság
   * Markov-operátor hatványa is Markov-operátor

1. Sztochasztikus programozási feladat
   * A feladat definiálása
   * Állapot tér
   * Sokk-tér
   * Átmenet függvény
   * Transzformációs függvény
   * Profit függvény
   * diszkont tényező
   * Megengedett út fogalma
   * Az út létezése
   * Az út folytatása
  
1. Optimal policy leképezés által generált út
   * Sztochasztikus supremum feladat
   * Az SP feladat megfogalmazásai
   * A feladathoz értelmezéséhez szükséges feltételek
   * Bellman-egyenlet
   * Optimal policy leképezés
   * Optimal policy leképezés által generált út fogalma és létezése
   * Optimal policy leképezés által generált út, optmális út is
   * Bellman-egyenlet megoldása SP feladat értékfüggvénye

1. Optimális út
   * Indukciós lemma
   * Optimális terv folytatása is optimális terv
   * SP értékfüggvényére is fennál az indukciós lemma
   * Optimális út egyben az optimal policy leképezás által generált út is.

1. A sztochasztikus Bellman-egyenlet megoldása mint fixpont
   * Markov operátorok Feller-feltétele
   * Sokk-feltétel
   * Blackwell-lemma
   * Bellman-operátor
   * Bellman-operátor monotonitása és konkavitása
   * Berge-tétel alkalmazása
   * Bellman-egyenlet egyetlen megoldásának folytonossága
   * Bellman-egyenlet egyetlen megoldásának monotonitása és folytonossága
   * Bellman-egyenlet egyetlen megoldásának szigorú konkavitása
   * Az optimális policy függvény folytonossága és egyértékűsége
