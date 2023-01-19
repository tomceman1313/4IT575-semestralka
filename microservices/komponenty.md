
<h1>Component view</h1>
Jedná se o pohled na komponenty navrhovaného systému
<h3>UML</h3>

![micro](https://user-images.githubusercontent.com/73756512/213572035-a8245205-74cf-4ae5-9694-fe816ca78055.jpg)

<h2>Katalog elementů</h2>

<h3>Klientská aplikace</h5>
<p>Single-page aplikace vytvořená s využitím knihovny React, která komunikuje s backendem skrze API</p>

<h3>Aplikační server server</h5>

<li>Služba vstupenek - Zajišťuje poskytování funkčnosti nákupu a rezervace vstupenek</li>
<li>Služba obsazenosti míst - Stará se o poskytnutí údajů o dostupnosti míst pro zvolenou akci</li>
<li>Služba administrace - Nabízí funkcionalitu pro zaměstnance a správu systému. Jedná se například o přidávání novinek ohledně plánovaných koncertů nebo upozornění na důležité údálosti. Zároveň by poskytovala data k monitoringu. </li>
<li>Služba uživatelských účtů - Poskytuje data o uživatelích, zařizuje provedení autentizace uživatele při přihlášení a stará se o funkce spojené s uživ. účty (změna hesla, změna osobních údajů, uložení platební karty..). </li>
<li>Služba koncertů - Služba poskytující funkčnost týkající se koncertů jako je zasílání dat o koncertu, vytvoření koncertu a úprava informací o akci.</li>

<h3>Databázový systém</h5>
Obsahuje databáze, které jsou propojeny s jednotlivými službami.
<li>Databáze vstupenek</li>
<li>Databáze míst</li>
<li>Databáze administrace</li>
<li>Databáze uživatelských účtů</li>
<li>Databáze koncertů</li>


## Popis funkčnosti

Uživatel přes rozhraní frontendu zasílá požadavky na služby, která požadavek zpracuje a vrátí odpověď. Každá služba má svojí vlastní databázi, čímž naplňuje chrakteristiku architektury microservices.
