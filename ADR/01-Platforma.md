<h1>Rozhodnutí o platformě systému</li>

<h2>ID</h2>
1

<h2>Status</h2>
Schválené

<h2>Context</h2>

Pro zahájení vývoje je potřeba nejprve určit, pro kterou platformu bude portál na prodej vstupenek vyvíjen. V úvahu připadá buď mobilní aplikace nebo webová aplikace.  

<h2>Decision</h2>

Portál budeme vyvíjet jako webovou aplikaci z následujících důvodů: 

<li>Přístup odkudkoliv a bez omezení na typ zařízení, které uživatel používá (pc, mobil, tablet) </li>

<li>Vzhledem k povaze nepravidelného používání portálu uživatelem je webová aplikace vhodnější, protože nezabírá místo v zařízení a nemusí se instalovat </li>

<li>U webové aplikace je snazší provádět změny, jelikož uživatel přijde k hotové věci a nemusí stahovat aktualizaci </li>

<h2>Consequences</h2>

V případě webové aplikace je nutné brát v potaz responzivnost webu, tj. na web by mělo jít přistoupit jak z desktopového, tak mobilního zařízení. Těmto zařízením tak musí tomu tak být přizpůsoben vzhled webové stránky. 

U webové aplikace se nemusí řešit situace, pokud člověk nemá internetové připojení. Na web se bez internetového připojení nedostane, zatímco mobilní aplikaci by měl nainstalovanou. 

U webové aplikace se nebudou ukládat průběžná data lokálně, nebude se tak využívat žádná lokální databáze. Předpokládá se, že na web bude přistupovat z různých zařízení, takže bude probíhat synchronizace online při vstupu na web přes přihlášení. Pro krátkodobé ukládání (např. dat z formulářů) budeme využívat cookies. 
