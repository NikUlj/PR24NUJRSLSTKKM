# Analiza letalskih nesreč
### Člani:
- Nik Uljarević
- Jernej Rednak Stana
- Leon Šturm
- Tomaž Kerec
- Kristjan Maroh

### PREDSTAVITEV MNOŽICE PODATKOV 
-----
Mnozica podatkov s katero bomo poskusali odgovoriti na izbrana vprasanja je baza podatkov o vseh letalskih nesrečah od leta 1918 do leta 2022. Podatki so v obliki "csv" datoteke in za vsako nesrečo vsebujejo naslednje informacije:

Za to množico podatkov smo se odločili, ker nam lahko poda odgovore na različna zanimiva vprašanja.

| Column                 | Data Type | Opis                                 |
|------------------------|-----------|--------------------------------------|
| Date (Datum)           | Date      | Datum nesreče                        |
| Time (Čas)             | Time    | Čas nesreče                          |
| Aircraft (Letalo)      | String    | Tip letala    |
| Operator (Operater)    | String    | Operater letala                      |
| Registration (Registracija) | String | Registracijska oznaka letala     |
| Flight phase (Faza leta) | String  | Faza letenja ob nesreči              |
| Flight type (Vrsta leta) | String  | Vrsta leta, vpletenega v nesrečo     |
| Survivors (Preživeli)  | String    | Ali je kdo preživel          |
| Crash site (Kraj nesreče) | String | Kraj nesreče                         |
| Schedule (Urnik)       | String    | Relacija leta                         |
| MSN                     | String    | Serijska številka proizvajalca     |
| YOM                     | Date   | Leto izdelave letala                 |
| Flight no. (Št. leta)  | String    | Številka leta                        |
| Crash location (Kraj nesreče) | String | Lokacija nesreče        |
| Country (Država)       | String    | Država, kjer se je zgodila nesreča  |
| Region (Regija)        | String    | Celina, kjer se je zgodila nesreča  |
| Crew on board (Posadka na krovu) | Integer | Število posadke na krovu letala |
| Crew fatalities (Št. smrtnih primerov posadke) | Integer | Število smrtnih primerov posadke |
| Pax on board (Potniki na krovu) | Integer | Število potnikov na krovu letala    |
| PAX fatalities (Št. smrtnih primerov potnikov) | Integer | Število smrtnih primerov potnikov |
| Other fatalities (Drugi smrtni primeri) | Integer | Število smrtnih primerov drugih oseb|
| Total fatalities (Skupno št. smrtnih primerov) | Integer | Skupno število smrtnih primerov   |
| Circumstances (Okoliščine) | String | Opis okoliščin nesreče               |
| Crash cause (Vzrok nesreče) | String | Opis vzroka nesreče                  |

### UGOTOVITVE 
----- 
Po letu 1940 je opazen velik porast letalskih nesreč, kar lahko pripišemo posledicam 2. svetovne vojne in morda tudi korejske vojne v petdesetih letih. Število nesreč nato hitro upade, vendar se v šestdesetih letih začne počasneje povečevati, verjetno zaradi naraščanja komercialne uporabe letal in podobnih dejavnikov. V osemdesetih letih pa opažamo začetek počasnega zmanjševanja števila nesreč, kar je verjetno posledica izboljšane varnosti letenja.
![alt text](./Grafi/graf1.png?raw=true)

Med znanimi vzroki je najpogostejša človeška napaka, nato tehnična napaka. Opazimo tudi, da za zelo veliko število nesreč vzrok ni znan, medtem ko ostali dejavniki, kot so vreme in terorizem, prispevajo manjše število nesreč v primerjavi z že omenjenimi vzroki.
![alt text](./Grafi/graf2.png?raw=true)

Vidimo, da je največ nesreč nastalo pri komercialnih letih. Takoj za njimi so vojaška letala, pogosto povezana z vojnami in konflikti. Sledijo nesreče med treningi ter leti s tovorom. Najmanj nesreč se zgodi pri akrobatskih poletih.
![alt text](./Grafi/graf3.png?raw=true)
