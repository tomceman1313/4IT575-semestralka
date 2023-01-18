<h1>Rozhodnutí o testování</li>

<h2>ID</h2>
3

<h2>Status</h2>
Schválené

<h2>Context</h2>
Je třeba určit si, jakým způsobem bude probíhat testování.
  

<h2>Decision</h2>
Pro frontendový E2E testing bude vytvořena sada testů v nástroji Cypress. Unit testy a integrační testy se budou psát a spouštět pomocí frameworku Jestjs.io. Systémové testy budou probíhat manuální exekucí testery.

<h2>Consequences</h2>

Jakékoliv nové featury budou předány testerům k manuálnímu testování. Testeři budou mít za úkol i vytváření automatických E2E testů v Cypressu, tak aby se ulevilo vývojářům. U těchto testů je potřeba, aby spolehlivě pokrývaly oblast regresních testů. Budou spouštěny ještě s integračními a unit testy před každým nasazením, čímž se zmenší pravděpodobnost zanesení chyb do produkce.
2
