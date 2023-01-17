<h1>Component view</h1>
Jedná se o pohled na komponenty navrhovaného systému
<h3>UML</h3>

![EDA-component](https://user-images.githubusercontent.com/73756512/213027939-0c951370-52c7-4f21-bfdc-51a1abee3daa.jpg)

<h2>Katalog elementů</h2>

<h3>Klientská aplikace</h5>
<p>Single-page aplikace vytvořená s využitím knihovny React, která komunikuje s backendem skrze API</p>

<h3>Webový server</h5>
Jedná se o komponentu, která slouží k hostování API webové aplikace. Vytvořen bude s využitím Node.js (stejně jako veškeré komponenty služeb).
<li>Mediátor - V rámci architektonického rozhodnutí o celkové architektuře byla vybrána architektura EDA s topologií mediátor. Tato komponenta zajišťuje výměnu zpráv mezi klientskou aplikací a jednotlivými službami na aplikačním serveru a řídí jednotlivé eventy. </li>

<h3>Aplikační server</h5>

<li>Služba vstupenek - Zajišťuje poskytování funkčnosti nákupu a rezervace vstupenek</li>
<li>Služba obsazenosti míst - Stará se o poskytnutí údajů o dostupnosti míst pro zvolenou akci</li>
<li>Služba administrace - Nabízí funkcionalitu pro zaměstnance a správu systému. Jedná se například o přidávání novinek ohledně plánovaných koncertů nebo upozornění na důležité údálosti. Zároveň by poskytovala data k monitoringu. </li>
<li>Služba uživatelských účtů - Poskytuje data o uživatelích, zařizuje provedení autentizace uživatele při přihlášení a stará se o funkce spojené s uživ. účty (změna hesla, změna osobních údajů, uložení platební karty..). </li>
<li>Služba koncertů - Služba poskytující funkčnost týkající se koncertů jako je zasílání dat o koncertu, vytvoření koncertu a úprava informací o akci.</li>

<h3>Databázový systém</h5>
Obsahuje databázi, která slouží k ukládání veškerých dat systému.
<li>ODBC - rozhraní pro komunikaci se SŘBD za cílem abstrakce od konkrétních databázových systémů. </li>
<li>Databáze</li>


