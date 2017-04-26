# PTS---DU3
Domaca uloha 3 z Principov tvorby softveru - Simulator kvalifikacie na MS 2018 vo futbale

Zadanie:

Domácu úlohu odovzdajte ako GITovský repozitár e-mailom na relatko@gmail.com. Do subjectu napiste PTS DU2. Nezabudnite napisat svoje meno. Termín na odovzdanie úlohy je 27.4.2017 23:00

Úlohou je navrhnúť systém, ktorý simuluje proces kvalifikácie na a samotné majstrovstvá sveta vo futbale 2018. Svoj dizajn popíšte. Urobte čiastočnú implemntáciu, ktorá bude simulovať niejaký iný, vymyslený, zjednodušený turnaj. Implementácia nemusí (a ani to neočakavam) byť postačujúca na simuláciu klalifikácie a MS, avšak dizajn má byť dostatočne flexibilný aby implementácia ostatných featurov nebola zásadným problémom vyžadujúcim kompletnú zmenu designu. 
Systém sa nainicializuje do stavu zodpovedajúcemu 1.1.2015. Systém spolupracuje s dvoma inými podsystémami: FIFA World Ranking a Simulátor zápasov (týmito systémami sa nemáte zaoberať, máte však definovať ich interface a na čiastkovú impleméntáciu budete potrebovať ich stuby - triviálne nakódené verzie). 

Systém má dva use casy.
Posunuť sa o deň vpred
Systém odsimuluje (s pomocou simulátora zápasov a FIFA World Ranking) možný vývoj počas nasledujúceho jedného dňa a vytvorí nový stav turnaja. Táto simulácia zahŕňa: zaznamenanie výsledkov zápasov, zmenu tabuliek, žrebovanie tímov do jednotlivých skupín (nasadzovanie do žrebovania určuje FIFA World Ranking), postup tímov medzi rôznymi časťami súťaže.
Zistiť aktuálny stav turnaja
Systém vie poskytnúť klientovy aktualny stav sútaže (výsledky historických zápasov, aktuálne tabuľky, tabuľky už ukončených častí turnaja).
Pre všeobecný prehľad ako prebieha kvalifikácia na MS vo futbale si pozrite Wikipediu. Pre čo najrýchlejšie pochopenie potenciálnej zlošitosti kvalifikačného procesu odporúčam si pozrieť si ako to prebieha v Ázii. 

Ak vám niečo v zadaní chýba, alebo sa vám niečo veľmi nepáči, kľudom si ho obmeňte.

Moj pristup:
