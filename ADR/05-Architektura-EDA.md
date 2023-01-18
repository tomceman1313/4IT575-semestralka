<h1>Rozhodnutí o Údálostmi řízené architektuře</li>

<h2>ID</h2>
5

<h2>Status</h2>
Schválené

<h2>Context</h2>
Prodejní portál vstupenek na koncerty očekává vysokou poptávku po vstupenkách na akce. Na portálu se koná velké množství akcí a prodává se velké množství vstupenek. Portál tak pro svou činnost pořebuje řešení, které by zvládlo vysoký objem provozu a transakcí a zajistilo větší škálovatelnost a efektivitu systému.

<h2>Decision</h2>
Pro portál pro prodej vstupenek na koncerty navrhujeme použít architekturu řízenou událostmi, aby se zlepšil výkon a škálovatelnost. Umožňuje vytvořit flexibilní systém, který zvládne velký počet událostí a velký objem vstupenek a umožňuje aktualizace v reálném čase.

<h2>Consequences</h2>
Architektura řízená událostmi je vhodná pro webové stránky prodávající vstupenky, protože umožňuje elasticitu (schopnost škálovat podle potřeby). Díky přístupu založenému na událostech může systém zvládnout velký nápor návštěvnosti nebo nákupy vstupenek, aniž by došlo k výpadku. Různé komponenty spolu komunikují spíše "emitováním" a posloucháním událostí než přímou komunikací. Lze ji použít jako pro velice složité aplikace, tak i pro ty malé.



Možné problémy:

* Prodleva: Asynchronní zpracování událostí může do systému vnést zpoždění, pokud se v systému provádějí v systému časově náročné operace.
* Závislosti: Součásti systému jsou často závislé na jiných službách, což může vést k selhání systému, pokud dojde k výpadku jiné služby.
