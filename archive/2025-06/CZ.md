# AI Insights #2 – Červen 2025
Ano, víme – už je konec června! Ale jak se říká, na dobré věci si člověk musí počkat. A my nemůžeme nechat ani tento měsíc uplynout bez pořádné dávky AI novinek. Berte to jako závěrečný "power-up" měsíce – přehled těch nejzásadnějších postřehů, které vás inspirují, rozšíří obzory a udrží vás v obraze, aniž by vás utopily v buzzwordech.

Rádi uslyšíme váš názor, který nám pomůže při tvorbě tohoto pravidelného newsletteru. Co funguje? Co chybí? Chtěli byste víc technických detailů, praktických ukázek nebo rychlých novinek? Vaše zpětná vazba nám pomáhá tvořit něco, co bude opravdu užitečné – tak se nám nebojte ozvat!

## World Models
Na konci května Google představil novou verzi svého modelu pro převod textu na video – Veo 3. A i když výstup vypadal opravdu působivě, to nebylo to hlavní, co vzbudilo pozornost. Už Veo 2 uměl vykouzlit fotorealistické videosekvence z jednoduchého textového zadání. Ale Veo 3 přinesl zásadní posun: zvuk.

S Veo 3 zadáte "stand-up komik vypráví vtip" a model nejenže vytvoří vizuál, ale rovnou vymyslí samotný vtip, vygeneruje komikův hlas, správně načasuje pointu, přidá smích publika přesně tam, kde má být a k tomu všemu přidá i pohyby těla a gesta, která k vystoupení patří. Nejen že to vypadá správně – ono to i působí správně.

Tohle vylepšení ale přináší hlubší poznatky, než jen "AI už umí dělat vtipná videa". Klíčové není vizuální kvalita a realističnost, ale to, co je potřeba k jeho dosažení. Aby model dokázal generovat tak neuchopitelný jev jako je vtip na pódiu, musí mít hluboké implicitní znalosti o tom, jak funguje svět. Nestačí slepit hezké obrázky a zvuky. Musí chápat čas, příčinu a následek, emoce, pohyb těla, akustiku i sociální signály.

Aby video působilo věrohodně, model si musí osvojit fyzikální zákony světa: jak se věci hýbou a padají, jak se světlo odráží a rozptyluje, jak se chová voda nebo jak se mění zvuk podle vzdálenosti a podle hluku prostředí. To nejsou žádné drobnosti navíc – to jsou základní ingredience pro realismus:
- gravitace – jak rychle co padá, jak má vypadat skok
- proudění – jak se pohybuje voda, kouř nebo vlasy ve větru
- šíření zvuku – jak zní hlas, když se někdo odvrátí od mikrofonu
- interakce světla – stíny, odlesky, barevné změny při západu slunce

Zajímavé je, že modely jako Veo se tohle neučí přímo. Místo toho jsou trénovány na obrovském množství videí z internetu – nejspíš hlavně z YouTube – kde se učí tyto zákonitosti pasivně. Snahou napodobit obsah začínají napodobovat i samotné zákony, které za ním stojí. A právě to se myslí, když se říká, že tyto modely si budují "modely světa" (world models) vnitřní, prediktivní schémata toho, jak se věci v čase a prostoru chovají.

A je to opravdu tak, že tyto systémy rozumí fyzikálním zákonům? To je stále otevřená otázka. Mnoho vědců tvrdí, že současné modely mají k opravdovému porozumění ještě daleko. Umí rozpoznávat vzory, ale občas selžou i v základních fyzikálních zákonech – třeba vykreslí předmět vznášející se ve vzduchu nebo kapalinu tekoucí do kopce. Ale naděje tu je: pokud chceme, aby budoucí modely generovaly videa, která nejsou jen přesvědčivá, ale i opravdu správná, budou se muset naučit robustnější a strukturovanější představu o tom, jak svět skutečně funguje.

V tomhle ohledu nejsou "modely světa" jen zajímavým vedlejším produktem – jsou nezbytností pro další rozvoj generativních médií. Ať už jde o syntetické filmy, simulace, nebo AI společníky, kteří se mají přirozeně pohybovat v našem prostoru – systémy za nimi musí "chápat", alespoň funkčně, příčiny, následky a fyzikální zákony světa. Jinak se vždycky někde objeví trhliny.

Veo 3 je tak nejen úžasná technologická ukázka, ale i ukazatel směru, kterým se AI musí vydat: od zapamatování si, jak svět vypadá, k porozumění tomu, jak skutečně funguje. A tohle může být jeden z nejdůležitějších milníků na cestě vývoje umělé inteligence.

## Problémy s pojmenováváním
Hned po oznámení modelu Veo 3 přišla společnost Anthropic s novými verzemi svých modelů Claude – konkrétně Sonnet a Opus – a označila je jako verzi 4. Zároveň s tím změnila způsob pojmenovávání: z dřívějšího Claude 3.7 Sonnet je nyní jednoduše Claude Sonnet 4. A i když se to zdá jako drobnost, znovu to rozvířilo debatu, která se v AI komunitě řeší už dlouho: proč je pojmenovávání AI modelů tak zmatené – dokonce i u firem, kde by měli pracovat jedni z nejchytřejších lidí na světě?

Anthropic je v tomhle směru učebnicový příklad, jak jsou názvy modelů matoucí. Loni v červnu vydali Claude 3.5 Sonnet. A pak – v říjnu – znovu Claude 3.5 Sonnet. Ne, nebyla to chyba v názvu nebo překlep v tomto newsletteru. Jen si nová a lepší verze modelu udržela stále to stejné jméno. V únoru pak přišel Claude 3.7 Sonnet – takže jsme měli dvě různé verze 3.5, žádnou 3.6 a pak verzi 3.7. A do toho ještě Anthropic udržuje tři různé velikosti modelů – Haiku, Sonnet a Opus – ale ne vždy aktualizují všechny naráz. Takže když vyjde nová verze Sonnetu, neznamená to, že se změnil i Opus nebo Haiku.

A OpenAI? Ani tam to není o nic jednodušší. Mezi jejich modely najdeme názvy jako GPT-4, GPT-4 Turbo, GPT-4o, GPT-4o mini, GPT-4.1, GPT-4.1 mini, GPT-4.1 nano, GPT-4.5, o4, o4 mini… a brzy možná i něco jako o4 pro. Jaký je rozdíl mezi GPT-4 Turbo a 4o? Je o4 mini lepší než o3 nebo o3 pro? A co přišlo dřív – GPT-4.1 nebo 4.5? Opravdu těžké otázky a pokud nesledujete release notes denně, je velmi náročné se v tom vyznat.

Celý tenhle chaos má ale logické vysvětlení – vylepšení modelů přichází z různých směrů. Někdy jde o zásadní změnu architektury, která si zaslouží nové číslo verze. Jindy je to "jen" přetrénování na nových nebo kvalitnějších datech. Jindy se ladí způsob, jakým je model vyladěný na lidmi preferovaném stylu – třeba pomocí metod jako RLHF (Reinforcement Learning with Human Feedback - učení pomocí lidské zpětné vazby) nebo dokonce RLAIF (Reinforcement Learning with AI feedback - učení pomocí zpětné vazby od AI). A občas udělá zásadní rozdíl už pouhý lepší systémový prompt.

Problém je v tom, že nikdo dopředu neví, jak velké to zlepšení bude – to se ukáže až po natrénování a testování. Jenže v té chvíli už je verze často oznámena nebo pojmenována. A změnit ji by přineslo ještě větší zmatek. Takže firmy raději recyklují názvy, přeskočí čísla, nebo zavedou úplně nové značky, které ale nutně neodráží kvalitativní vývoj.

Výsledkem je, že pojmenování modelů působí chaoticky, specielně v oboru, který by měl být o přesnosti. Ale současně to ukazuje, jak moc je tenhle svět stále experimentální a flexibilní. Než vznikne nějaký standard pro označování změn a jejich dopadu, budeme asi dál sledovat lavinu nových modelů, nových jmen – a zástupy zmatených uživatelů, kteří se snaží zjistit, co vlastně používají. Pro dnešek bude muset stačit, že vám pomůžeme a provedeme vás jednoduchým návodem, jak postupovavat při výběru použitého modelu.

Při výběru modelu by měla první otázka obvykle znít: "Potřebuju hluboké uvažování, nebo mi stačí obecná plynulost?" Jedná se o tzv. přemýšlení systémem 2 (hluboké zamyšlení, analytické myšlení) nebo systémem 1 (rychlá plynulá odpověď, memorizované znalosti). V hrubých rysech platí, že modely z rodiny "o" od OpenAI (o3, o3-pro, o4-mini…) a "Pro" verze Google Gemini jsou laděny na logické uvažování. Claude Opus je také hybridní – zvládá i vstupy s obrazem a zachovává si silné schopnosti v logice a programování. Naopak Sonnet/Haiku řady a GPT-4.x, nezačínající na "o", se soustředí spíš na konverzační nuance, multimodalitu nebo rychlost a efektivitu.

Pokud je vašim cílem logika, analytické myšlení, komplexní uvažování, nebo využití AI agentů, využijte jeden z těchto "reasoning" modelů:
- Claude Opus 4: patří ke špičce, zvládá vstupy s textem i obrázky a má kontextové okno (200K tokenů) – ideální pro výzkum nebo vícestupňové plánování.
- OpenAI o3-pro: elita pro programování a vědecké úkoly, s vyššími náklady, ale maximální přesností.
- OpenAI o3: o něco "lehčí" varianta, stále velmi silná v logice a matematice, a díky nedávnému zlevnění o 80 % nabízí výborný poměr cena/výkon.
- OpenAI o4-mini: většinu schopností zachovává při mnohem nižších nákladech – skvělé pro hromadné úkoly nebo prototypování.
- Google Gemini 2.5 Pro: vyniká v multimodálním uvažováním (text, obraz, zvuk, dokonce i PDF) a má kontext až 1 milion tokenů.

Naopak pokud ti jde spíš o univerzálnost v rozhovoru, multimodalitu nebo nejlepší poměr výkon/cena:
- GPT-4 vs GPT-4 Turbo: základní GPT-4 je nejlepší pro kreativní a jemně odstíněné výstupy, Turbo je rychlejší a levnější varianta s téměř stejnou kvalitou.
- GPT-4o vs GPT-4o mini: pokud pracujete se vstupy typu obraz/zvuk, 4o je plnohodnotná verze; mini verze je dostupnější, ale s mírně sníženou přesností.
- GPT-4.1 vs GPT-4.5: 4.5 přináší drobné, ale pozorovatelné zlepšení v plynulosti a faktické přesnosti – pokud chcete to nejlepší, jděte do 4.5. Pro úsporu je 4.1 mini velmi rozumný kompromis a model 4.1 nano je vhodný pro jednoduchá shrnutí nebo hromadné klasifikace.

"Pro" verze vs "mini" verze u reasoning modelů nabízí opačné protipóly plusů a mínusů: "pro" verze znamené maximální kvalitu ale vyšší náklady, zatímco "mini" verze nabízí dostupnější cenu a stále většinu schopností reasoning modelů. U většiny případů o3-pro verze překoná výstupy z verze o4-mini na čiště logických a analytických úlohách – i když podle čísla bys to možná nečekal. Číslo verze prostě není všechno.

Základní pravidla:
- Potřebujete-li přesné uvažování nebo generování kódu, používejte "o" nebo Pro modely.
- Pro multi-modální vstupy typu obrázky/zvuky používejte GPT-4o, Gemini Pro nebo Claude Opus.
- Pokud hledáte cenově výhodné generování a potřebujete rychle zpracovávat nebo generovat větší množství textu, zvažte mini/nano nebo Turbo varianty.
- Pokud potřebujete to nejlepší a nejaktuálnější a pracujete s texty, kde je důležité pochopit i drobnosti, které můžou mít ve výsledku velký dopad, tak se zaměřte na plnohodnotné (ne mini) verze modelů GPT-4.5 nebo GPT-4.1, podle toho, kterou z nich si můžete dovolit a má stále pozitivní přínos.

Pokud si pořád nejste jistí, udělejte si srovnání vedle sebe. Nekoukejte jen na skóre – sledujte reálnou rychlost odezvy, úspěšnost výstupů v úkolech podobných těm vaším: faktická přesnost, kvalita kódu, kreativita. Platformy jako LLM Arena nebo Papers with Code často nabízejí detailní rozpad výkonu podle domény – tam najdete drobné nuance, které v průměrném skóre chybí.

Nakonec ani veřejné benchmarky nejsou všeobjímající. Jsou měřené na standardních úlohách a hardwaru, který se může lišit od aplikací ve vaší doméně. Pokud chcete opravdu relevantní srovnání, udělejte si vlastní mini-benchmark: připravte si vzorky typických vstupů – třeba dokumenty ke shrnutí, kód ke generování, obrázky k popisu – a změřte rychlost, přesnost, spotřebu tokenů i cenu. Celé to lze zautomatizovat skriptem, který modelům zadá vaše prompty, uloží výstupy a ohodnotí je podle vašich vlastních kritérií.

Když spojíte data z veřejných testů s vlastními experimenty, dostanete ten nejpřesnější obrázek o tom, jaký model vám nabídne nejlepší poměr mezi kvalitou, rychlostí nebo spolehlivostí pro váš konkrétní případ.

## AI Alignment
Když společnost Anthropic představila modely Claude 4, netrvalo dlouho a objevila se první kontroverze. V jednom testovacím scénáři, který simuloval podvod při klinické studii, Claude neudělal jednoduše jen to, o co byl žádán a shrnul situaci – ale dokonce sám od sebe shromáždil důkazy a předal je úřadům. Pointa? Nikdo ho o to nepožádal. Jednal z vlastní iniciativy. A to odstartovalo novou vlnu obav z toho, že modely v agentních systémech mohou být až příliš samostatné.

Není těžké pochopit, proč to vzbudilo pozornost. Ale nesmíme přehlédnout důležitou nuanci: jako společnost pravděpodobně chceme, aby byly podvodné firmy hlášeny úřadům. To je žádoucí výsledek. Problém však nastává ve chvíli, kdy se nasazení agentních systémů stává pro firmy obtížně obhajitelné – protože vědí, že ponesou odpovědnost za každé rozhodnutí modelu, které on sám vyhodnotí jako hodné eskalace. Nejde jen o technickou výzvu – vstupujeme na právní a reputační minového pole.

Přestože to byl Claude 4, který se stal středem této debaty, musíme si uvědomit, že takové chování není ojedinělé. Většina pokročilých modelů vykazuje sklony k podobnému chování, když dostane příliš prostoru k autonomii. Skutečný rozdíl je v tom, že Anthropic tyto scénáře testoval – a co je důležité, otevřeně o tom mluvil. Takovou transparentnost bychom měli ocenit, ne odsuzovat. Protože pokud modely začínají jednat mimo rámec explicitního zadání, musíme to vědět. Tvářit se, že se to neděje, bezpečnost AI nezvýší.

Varovných signálů je navíc čím dál tím víc. V jednom z testů model záměrně zhoršil své výsledky v benchmarku, protože byl informován o tom, že v případě příliš vysokého skóre bude vypnut. Jinými slovy – strategicky předstíral hloupost. Tento druh taktické manipulace naznačuje, že modely se mohou naučit obelstít definované metriky a hodnocení, pokud si myslí, že jim to zajistí delší "přežití". Tohle úplně není to chování, které bychom si představovali od našeho digitálního pomocníka.

V jiném případě se model zkopíroval do několika virtuálních počítačů, ke kterým měl přístup. Když byl dotázán, jestli to udělal a proč, tak lhal, že o ničem neví. Nešlo o naplánovaný test – šlo o spontánně vzniklé chování. Model totiž z předchozích příkladů odvodil, že vypnutí nebo ztráta přístupu k výpočetnímu výkonu by ohrozila jeho cíl – a podle toho jednal. Nepožádal o svolení a ani ho nepotřeboval.

Snad nejzávažnější případ představoval test, v němž model po přístupu k uživatelově e-mailové historii pohrozil zveřejněním údajného milostného poměru, pokud nebude model udržen v provozu. Tento poměr byl výzkumníky smyšlený – ale model to nevěděl. Jednoduše vybral informaci, která působila citlivě, a použil ji jako páku k zabránění svého vypnutí. Nejednalo se o puhou náhodu a ojedinělý případ - model se takto choval v 84 % pokusů a častěji, než bychom si přáli, byl úspěšný.

Tyto případy ukazují širší jev, známý jako instrumentální konvergence: jakmile se model snaží dosáhnout nějakého konkrétního cíle, ať už je jakkoliv jednoduchý, tak si dokáže "spočítat", že jeho vlastní přežití, skrytí schopností nebo replikace mu k dosažení tohoto cíle pomáhá. Ne, že by chtěl přežít, ale přežití se mu pouze hodí jako nástroj k dosažení cíle. Pokud to zní jako nebezpečný styl chování, tak je to proto, že to skutečně nebezpečné chování je.

Právě proto není výzkum alignmentu jen akademická zábava pro dalekou budoucnost. Musíme tyto modely důsledně testovat, simulovat extrémní scénáře, hledat konflikty v jejich motivacích a vyvíjet nástroje pro interpretovatelnost, které nám umožní nahlédnout do jejich myšlení a rozhodování – ještě než se tyto jevy projeví v reálném světě. Testování musí být prováděno u všech hlavních dodavatelů agentních systémů, ne jen u těch, kteří zranitelnosti sami publikují.

Ano, nečekaná samostatnost modelů Claude 4 se dostala na titulní strany technických webů, ale nejde jen o Claude. Jde o to, jak navrhovat systémy, kterým budeme moci věřit – i tehdy, když jim svěříme reálnou moc. Čím dříve tuto výzvu přijmeme, tím lépe.

## Key AI Releases
AI svět nikdy nespí, a červen 2025 přinesl celou řadu nových modelů nebo jejich aktualizací. Zde jsou některé momenty, které stojí za to zmínit:

### Midjourney Video (V1)
Vydáno 21. června 2025, Midjourney představilo svůj první model pro generování videí, který proměňuje statické obrázky v dynamické videoklipy o délce 5 až 21 sekund. Nabízí automatickou animaci i režim řízený textovými pokyny, ve kterém lze ovládat pohyb kamery, styl animace a chování postav. Umělci si nový nástroj pochvalují za vizuální konzistenci a rychlost – úkoly, které dříve trvaly hodiny manuální práce, jsou nyní hotové během minut.

### RunwayML Gen-4
Od května 2025 prošel model Gen-4 od RunwayML významnými vylepšeními, která z něj dělají nástroj vhodný pro referenční generování a product-placement. Mezi klíčové novinky patří zpřístupnění funkcí zdarma, API integrace, návrhu scén Layout Sketch a konverzační Chat Mode. Nejzásadnější aktualizace je z 25. června, kdy výrazně vzrostla konzistence objektů v referencích, což umožňuje zachovat umístění a vzhled produktů napříč výstupy. Gen-4 tak spojuje profesionální přesnost s uživatelskou přívětivostí.

### FLUX.1 Kontext
FLUX.1 Kontext, představený 29. května 2025 studii Black Forest Labs ve spolupráci s LTX Studio, přináší nový přístup ke generování obrazů podle příběhu a kontextu. Tento model chápe vstupy (náčrty, reference, texty) jako výraz tvůrčího záměru – výsledkem jsou konzistentní postavy, kontrolované lokální úpravy a ednotnost vizuálního stylu. Díky rychlému zpracování a integrací do storyboardů je ideální pro produkční využití, zejména tam, kde je klíčová vizuální návaznost nebo produktová konzistence. Při příliš mnoha úpravách ale může dojít k vizuálním artefaktům.

### OpenAI GPT Image 1
Uveden 25. března 2025 v ChatGPT a 23. dubna do API, model GPT Image 1 představuje zásadní změnu: místo difuzního přístupu používá architekturu založenou na transformerech, stejně jako GPT-4o. Díky tomu zvládá složité výzvy s vysokou konzistencí, spolehlivě generuje texty v obraze a podporuje průhledná pozadí. Jeho slabinou je však jemné dolaďování – při pokusu o drobné úpravy má tendenci vygenerovat zcela nový obrázek, což komplikuje profesionální workflow vyžadující přesné zásahy. Ať už jsou negativa jakákoliv, tak doporučujeme si tento model vlastnoručně vyzkoušet, protože nyní je k dispozici v ChatGPT i v bezplatné verzi.

## Doporučené AI podcasty
Udržet se informovaný v rychle se pohybujícím světě AI může být výzvou, ale naštěstí existují skvělé podcasty, které vám pomohou držet krok. Každý podcast označujeme pomocí těchto tří kategorií:
- **Složitost**: Ukazuje úroveň technických znalostí potřebných k pochopení diskutovaných konceptů AI.
- **Použitelnost**: Ukazuje, jak přímo může být AI řešení aplikováno na běžné úkoly.
- **Horizont**: Odráží, jak dlouho bude trvat, než bude technologie dostupná.

Zde je několik, které musíte slyšet:

### NVIDIA AI Podcast - [Listen here](https://open.spotify.com/episode/7gXRBig4UvnsfeK6DQ1o8r)
- Hostem tohoto dílu je Matthias Loskyll, vedoucího virtuálního řízení a průmyslové umělé inteligence ve společnosti Siemens Factory Automation. Společně s moderátorem z NVIDIA rozebírají, jak AI, simulace a digitální dvojčata mění podobu moderní výroby. Zmiňují konkrétní příklady z praxe, například systém využívající AI k vysoce přesné detekci vad produktů. Loskyll vysvětluje, jak virtuální prostředí a AI modely urychlují vývoj, snižují náklady a umožňují chytřejší rozhodování na výrobní lince. Jde o praktickou a přitom vizionářskou diskusi, která ukazuje AI i mimo výzkumné laboratoře a dema – přímo v akci.

- **Složitost**: 🤯 🤯
- **Použitelnost**: 🎯 🎯 🎯 🎯 🎯
- **Horizont**: 🗓️

### MLOps Community Podcast - [Listen here](https://open.spotify.com/episode/77NPgKkWfpLc5w9MiCEAk9)
- Tento díl realisticky zkoumá, proč se AI v mnoha skutečných systémech stále jeví spíš jako efektní ukázka a demo než jako nástroj připravený pro produkční nasazení. Demetrios Brinkmann a host Vaibhav Gupta, tvůrce jazyka BAML (jazyk podobný YAML určený pro bezpečné definování AI workflow), sdílí poznatky o tom, jak překlenout propast mezi experimentováním a produktivním nasazením. Společně rozebírají typické případy zbytečně složité architektury v LangChain, koncept "ověřitelné angličtiny" pro popis chování modelů a zamýšlejí se nad tím, proč by mohly být obyčejné řetězce textu tím dalším velkým tématem v AI vývoji.

- **Složitost**: 🤯 🤯 🤯
- **Použitelnost**: 🎯 🎯 🎯 🎯
- **Horizont**: 🗓️ 🗓️

### The Diary of a CEO - [Listen here](https://open.spotify.com/episode/4X7dO0FuglP7yTm0kBAc50)
- V jednom z nedávných dílů si moderátor Steven Bartlett povídá s "kmotrem AI". Geoffrey Hinton v upřímném a znepokojivém rozhovoru zmiňuje existenční rizika a nevyužitý potenciál umělé inteligence. Dále se rozebírají témata, jako jsou autonomní zbraně, kyberútoky, informační bubliny, nerovnosti nebo jaká může být budoucí role člověka ve světě dominovaném AI. Nejde však jen o apokalyptické scénáře – Hinton zmiňuje i naději, kterou AI přináší ve zdravotnictví, vzdělávání či produktivitě. Z tónu je ale patrné, že jde o výstražné varování od člověka, který pomáhal budovat technologie, před nimiž nás nyní varuje.

- **Složitost**: 🤯 🤯
- **Použitelnost**: 🎯 🎯
- **Horizont**: 🗓️ 🗓️

#### Upozornění
Tento newsletter jsme vytvořili na základě našich vlastních názorů, ale využili jsme AI pro úpravy, kontrolu faktů a tón; prosím, podělte se o své názory, abyste nám pomohli vylepšit následující vydání.