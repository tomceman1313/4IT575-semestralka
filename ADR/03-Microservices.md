<h1>Rozhodnutie o architektúre Microservices</li>

<h2>ID</h2>
3

<h2>Status</h2>
Schválené

<h2>Context</h2>
Predajný portál pre vstupenky na koncerty a iné akcie má veľké množstvo udalostí a veľké množstvo vstupeniek.
Takáto aplikácia si vyžaduje architektúru s výbornou elasticitou, čiže výdrž vysokého náporu užívateľov a predaja vstupeniek.
  

<h2>Decision</h2>

Pre tento portál bola zvolená architektúra mikroslužieb. V tejto architektúre bude systém rozdelený do viacerých služieb, ktoré budú nezávislé a schopné sa ďalej škálovať.


<h2>Consequences</h2>

Výhody architektúry spočívajú práve v elasticite - teda schopnosti zvládnuť veľké nápory užívateľov a vstupeniek. Taktiež samotné služby budú ľahko škálovateľné a testovateľné,
takže ďalší rozvoj portálu bude možný bez veľkého pozastavenia celej služby. 

Je treba si dať pozor na vytváranie príliš malých služieb, aby nedošlo k príliš veľkému volaniu medzi nimi. Väčšie množstvo služieb bude mať aj negatívny vplyv na výkon
aplikácie. Bude potreba správneho manažmentu celej organizácie na zjednotenie komunikácie medzi jednotlivými tímami, ktoré pracujú na daných službách.
