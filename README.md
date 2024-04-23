# Gofest #
Aplikace pro výběr akce ve tvém okolí.

![image](https://github.com/pslib-cz/2023-l4-web-mockupapp-StepanJakubec/assets/107682109/0863052e-2fba-49bf-af9a-8297fb484573)

![image](https://github.com/pslib-cz/2023-l4-web-mockupapp-StepanJakubec/assets/107682109/4ac941e4-6354-4af7-a86a-ba7ecb05f0e8) ![image](https://github.com/pslib-cz/2023-l4-web-mockupapp-StepanJakubec/assets/107682109/63dc8360-2e0f-4402-a077-71029620ada4)

Aplikace slouží k vyhledání událostí ve zvoleném okolí v nejbližší době. Představte si, že se vám zrovna uvolnil víkend, a tak byste chtěli s kamarády někam vyrazit. K tomu slouží aplikace Gofest. Uživatel při otevření zadá svoji polohu a díky tomu si vyfiltruje akce v jeho okolí. Zobrazí se mu list akcí, na které si může rovnou koupit lístky. 

## Návrh ##
![image](https://github.com/pslib-cz/2023-l4-web-mockupapp-StepanJakubec/assets/107682109/0ef7e181-e0e4-4ec8-8fd6-4733a2187c95)
<img width="491" alt="image" src="https://github.com/pslib-cz/2023-l4-web-mockupapp-StepanJakubec/assets/107682109/eef7a3d1-ecb8-4bbd-a8ff-392ae71a1c06">


### Barvy ###
tlačítka ![image](https://github.com/pslib-cz/2023-l4-web-mockupapp-StepanJakubec/assets/107682109/c4313908-df33-43e4-b702-3af6f6df6d56) barevný přechod ![image](https://github.com/pslib-cz/2023-l4-web-mockupapp-StepanJakubec/assets/107682109/065736c0-07e2-4152-9c2a-bc806b52f2a1)

### Logo ###
<img width="424" alt="image" src="https://github.com/pslib-cz/2023-l4-web-mockupapp-StepanJakubec/assets/107682109/6afaeaa3-5d4e-429a-bd0b-ed9d0d532960">


### Font ###
Roboto

## Co se v aplikaci vyskytuje (web-design) ##
* Navigační menu: Navigační menu odkazuje na stránky jako jsou "events" nebo "giveaways". V mobilní verzi se menu změní na hamburger menu.
* Flexbox/Grid: Flexbox se využívá primárně k tvorbě karet akcí. Zde se poocí flexu zarovnávají prvky, například ve footeru (justify-content: space-between). Grid se využívá v desktopové verzi na stránce events. Zde díky němu vzniká mřížka z karet akcí o velikosti 3x3. 
* Pozicování: Pozicování se využívá pro vytvoření textu, který překrývá obrázek. To můžeme vidět například na stránce opened event. Zde se pomocí absolutního a relativního pozicování vytvoří text, který překrývá obrázek.
* Slider/Carousel: Na úvodní stránce v desktopové verzi se využívá slider. Ten posouvá nově přidané akce a umožňuje tak ukázat nové. Slider můžeme implementovat pomocí javascript knihoven

## Jak aplikace funguje ##
Aplikace slouží pořadatelům akcí jako platforma, na které mohou inzerovat svůj event. Pořadatelé kontaktují tým Gofestu a řeknou jim o jejich akci. Důležité je datum, čas, místo a cena vstupného. Grafiku i textaci si zajišťuje pořadatel akce. Následně se akce nahraje do aplikace Gofest, aby ji mohli vidět uživatelé. Gofest si bere provize z prodeje online vstupenek. Kromě prodeje vstupenek nabízí aplikace i možnost soutěžit o vstupenky. Tímto si získává sledující a buduje povědomí. Soutěže se lidé zúčastí tak, že začnou sledovat sociální sítě Gofestu. Soutěže a jejich grafiku si tvoří sám.

Hlavní účel aplikace je pomoct lidem ve vyhledávání zábavy. Gofest shrne všechny informace a je přes něj i možné platit, čímž vám ušetří spoustu času.
