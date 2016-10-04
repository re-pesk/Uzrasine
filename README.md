## **Tikslas - susipažinti su:** 

<ol type="a">
    <li>elgsena paremto programavimo principais</li>
    <li>moduliniu (angl. "unit") testavimu</li>
    <li>RSpec testavimo karkasu</li>
    <li>Ruby progravimo kalba</li>
</ol>

#### **Užduotis:**

1. Identifikuoti esminę esybę (pvz. bankinėje sistemoje tai būtų Sąskaita); 
2. Įgyvendinti esminės esybės funkcionalumą BDD principu parašant bent 10 testų, kurie testuoja būtent tą dalykinę sritį. Pvz. puikiai tinka testas, kuris bankinėje sistemoje testuoja ar korektiškai nukeliauja pinigai gavėjui, kai siuntėjas atlieka pavedimą. Bet visiškai netinka toks testas, kuris testuoja kokio tipo objektas susikūrė iškvietus 'initialize' metodą, nes tai visiškai neparodo ar sistema veikia korektiškai ar ne.

#### **Reikalavimai:**
1. Visas kodas turi būti 100% padengtas testais.
2. Reikia panaudoti SimpleCov įrankį ir pademonstruoti kodo padengimą testais.
3. Reikia panaudoti RuboCop įrankį ir pademonstruoti kodo atitikimą "Ruby Style Guide". Reikia naudoti standartinę RuboCop konfigūraciją.
4. Reikia panaudoti Reek įrankį ir pademonstruoti, kad kodas neturi tipinių simptomų. Reikia naudoti standartinę Reek konfigūraciją.
5. Jeigu įgyvendinant esminės klasės funkcionalumą prireikia kitų klasių, tai jas taip pat reikia parašyti panaudojant BDD.
6. Negalima naudoti Rails, ActiveRecord ar kokio nors kito karkaso atliekant šią užduotį. T.y. užduotis turi daugiau demonstruoti gebėjimą programuoti Ruby, o ne naudojimąsi kokiu nors karkasu.
7. Testai turi būti parašyti laikantis **http://betterspecs.org** rekomendacijų. 

**Įvertinimas: 1 balas**   