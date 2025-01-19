# Pravidla pro vývojáře pluginů v organizaci Friends of Sunlight CMS *(FoSC)*

## 1. Zásluhy
- Zásluhy za vývoj pluginu vždy náleží původnímu vývojáři/vývojářům.

## 2. Dostupnost repozitářů
- Repozitáře pro pluginy, šablony nebo překlady zveřejněné pod organizací *FoSC* budou dostupné trvale.
- Pokud repozitář již nebude aktivně vyvíjen, bude mu poskytována základní údržba pro zajištění kompatibility se systémem.
- Pokud se plugin stane nepotřebným *(např. jeho funkce bude přímo implementována do systému)*, bude archivován, ale stále přístupný.

## 3. Pravidla pro publikování
### Povinná pravidla
- Název repozitáře **MUSÍ** mít suffix podle účelu pluginu, tedy: `-plugin`, `-template`, `-language`. Například: `mydesign-template` nebo `pirate-language`.
- ZIP release pluginu **MUSÍ** být kompatibilní s administračním instalátorem pluginů, a tedy mít strukturu: 
  - `plugins/`*`<extemd | languages | templates>`*`/<myplugin>`.

### Doporučení
- Je **silně doporučeno** strukturovat takto i samotný repozitář kvůli nástroji *FoSC* pro tvorbu releasů.

*Nástroj automaticky instaluje závislosti a tvoří ZIP archivy kompatibilní se systémem Sunlight CMS (v budoucnu by mohl umožňovat i automatický release přes GitHub API).* 

## 4. Žádost o zařazení na oficiální web
- Vývojáři **MOHOU** požádat o zařazení jejich pluginu do sekce `Pluginy` na oficiálním webu Sunlight CMS.

## 5. Archivace repozitářů
- Opustěný repozitář **MŮŽE** být na žádost původního vývojáře archivován.
- Archivované nebo opuštěné repozitáře **MOHOU** být dále vyvíjeny jiným členem *FoSC*, obvykle formou forku.

## 6. Bezpečnost a integrita komunity
- Plugin, který úmyslně narušuje bezpečnost systému, komunity nebo koncových uživatelů, bude bez upozornění odstraněn z organizace *FoSC* i z oficiálního webu *(pokud tam bude umístěn)*.

## 7. Spolupráce a vývoj
- *FoSC* podporuje spolupráci na vývoji. Členové **MOHOU** přispívat k vývoji pluginů, včetně těch vytvořených jinými, pokud dodržují pravidla a respektují zásluhy původního vývojáře.
- V případě větších úprav cizího, neopuštěného pluginu *(např. nová funkce nebo oprava bugu vyžadující větší zásah)* se vytváří Pull Request (PR) do původního repozitáře.
- Na jednoduché aktualizace pro kompatibilitu s novými verzemi Sunlight CMS nebo drobné opravy bugů *(hotfixy)* se toto pravidlo nevztahuje.

## 8. Licencování
- Všechny pluginy publikované pod *FoSC* musí používat open-source licenci kompatibilní s filozofií Sunlight CMS. Licence **MUSÍ** být v repozitáři jasně uvedena.

## 9. Komunikace a řešení sporů
- Vývojáři jsou vyzýváni k udržování jasné komunikace s komunitou a ostatními přispěvateli.
- V případě sporů ohledně vlastnictví repozitáře, směru vývoje nebo jiných záležitostí budou moderátoři/administrátoři *FoSC* prostředníky pro nalezení spravedlivého řešení.

## 10. Odebrání nebo přesun pluginů
- Pokud si vývojář přeje přesunout plugin mimo organizaci *FoSC*, **MŮŽE** o to požádat za předpokladu, že to nenaruší stabilitu nebo bezpečnost komunity a jakákoliv změna nebo aktivita neohrozí důvěru nebo funkčnost *FoSC* komunity.
- Odvozené *(forknuté)* verze pluginů mohou existovat pod novým názvem, i pokud autor odebere originální repozitář. Autor však **MŮŽE** požadovat, aby bylo v daném forku jasně uvedeno, že se jedná o plugin vycházející z jeho práce, pokud se kód shoduje ve více než 70 %.

## 11. Dodržování pravidel
- Vývojáři **jsou povinni** dodržovat tato pravidla a jakékoli další pokyny zveřejněné organizací *FoSC*.

Účast v komunitě *FoSC* **je dobrovolná**, vývojáři se však zavazují k dodržování těchto pravidel za účelem vytvoření podpůrného, spolupracujícího a bezpečného prostředí pro všechny přispěvatele a uživatele.

