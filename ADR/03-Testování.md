<h1>Rozhodnutí o testování</li>

<h2>ID</h2>
3

<h2>Status</h2>
Schválené

<h2>Context</h2>
Je třeba určit si, jakým způsobem bude probíhat funkční testování.
  

<h2>Decision</h2>
Unit testy a integrační testy se budou psát a spouštět pomocí frameworku Jest. Systémové testy budou probíhat manuální exekucí testery, kterým budou k těmto testům předány všechny nové featury. Testeři budou mít za úkol i vytváření automatických E2E testů v nástroji Cypress, tak aby se ulevilo vývojářům. U těchto testů je potřeba, aby spolehlivě pokrývaly oblast regresních testů.

<h2>Consequences</h2>

Frontendové E2E testy budou spouštěny ještě s integračními a unit testy před každým nasazením, čímž se zmenší pravděpodobnost zanesení chyb do produkce. Tím se zajistí, aby nové featury negativně neovlivnili dosavadní funkcionalitu. Exekuce manuálních systémových testů zajistí správné fungování nových funkcionalit, případně odhalení defektů na začátku vývoje.
