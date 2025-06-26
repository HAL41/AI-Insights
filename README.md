# AI Insights #1 - May 2025 // Květen 2025
*Česká verze následuje // Czech version below*

---

# AI Insights #1 – May 2025
Welcome to the inaugural edition of the AI Insights newsletter. Our aim is to keep you regularly updated on the most significant trends and news shaping the world of artificial intelligence. We're here to act as your AI guide, cutting through the jargon and highlighting what truly matters, in order to share important information that can inspire your projects and bring new perspectives. In this first issue, we're focusing on the biggest AI trends we've observed so far. While some news may not be directly applicable to our immediate work, we believe it's essential to stay informed about the broader developments in the industry.

In the coming months, we'll be bringing you more focused updates on month-to-month developments from the leading AI companies, as well as keeping a close eye on the exciting news in the Open Source ecosystem. Since this is our maiden voyage, your feedback is invaluable! Let us know what you think of the format, what topics you'd love us to explore next, whether you want deep dives into specific areas, or if you prefer shorter, more frequent updates. We're all ears and eager to make this newsletter a valuable resource for you.

## AI Agents
AI Agents are THE hottest topic in AI for 2025! But what exactly are they? Broadly speaking, an AI Agent is a system or program engineered to perform tasks autonomously by designing its own workflow and leveraging available tools. Now, you might be thinking, "Hey, doesn't that sound like pretty much every chatbot out there?" And you'd have a point! By this definition, even current chatbots that use search tools to retrieve information before answering your queries could technically qualify as agents. However, it's probably more helpful to think of agentic behavior as a spectrum rather than a simple yes or no. Think of it like 'intelligence' in humans – it's not just a binary condition, but a whole range of abilities. The AI landscape in May 2025 showcases a fascinating array of agentic approaches, which can be broadly categorized into three main patterns.

### AI Agent Products
These are AI systems meticulously optimized for specific use cases, offering impressive power within their defined boundaries. However, this specialization often comes with less flexibility when it comes to integrating custom tools or unique integrations. A prime example of an AI Agent Product making waves is Manus, a Chinese startup that burst onto the scene in March 2025 and genuinely amazed people with its remarkable problem-solving capabilities. Turns out, this impressive feat was powered by the standard Claude Sonnet from Anthropic, armed with a carefully selected arsenal of 29 tools. This showcases just how much reasoning current large language models (LLMs) are capable of when applied strategically. The key takeaway here is that these AI Agent Products are like highly specialized tools – amazing for the job they're built for, but not so great for custom integrations.

### Managed Agentic Platforms
The big players (and some savvy startups) are also jumping into the agent game with Managed Agentic Platforms. Think of these as your 'AI Agent Starter Kits' – pre-configured and ready to roll! Examples include Azure AI Agent Service & Microsoft Copilot Studio, AWS Agent Builder, and Google's Vertex AI Agent Builder. These platforms come loaded with pre-built integrations, making it super quick to get your first agent up and running. However, a word of caution: these platforms are often optimized for their provider's ecosystem, so be mindful of potential 'vendor lock-in'. Pricing can also vary quite a bit, based on everything from the number of conversations to infrastructure usage and compute power.

### Open-Source Libraries
For the DIY enthusiasts out there, the Open-Source ecosystem is brimming with possibilities! These libraries offer maximum flexibility, but remember, you're the one in the driver's seat for development and management. Key players in this space include LangGraph (from the awesome LangChain team), LlamaIndex, SmolAgents (kudos to HuggingFace!), CrewAI, AutoGen, and Microsoft's SemanticKernel.

To provide a clearer picture of these distinct patterns, here's a quick comparison:

Feature | AI Agent Products | Managed Agentic Platforms | Open-Source Libraries
|-----|-----|-----|-----|
**Focus** | Specific Use Cases | Speed of Initial Development | Flexibility and Customization |
**Flexibility** | Less flexible for custom tools/integrations | Optimized for provider's ecosystem | Highly flexible
**Ease of Use** | Generally user-friendly for intended purpose | Easy initial setup with preconfigured integrations | Requires self-management and development effort
**Integration** | Limited to specific use case needs | Optimized for specific cloud provider ecosystem | Highly customizable with various tools and APIs
**Management** | Managed by the product vendor | Managed by the platform provider | Requires self-management
**Example** | Manus | Azure AI Agent Service, Copilot Studio, etc. | LangGraph, LlamaIndex, CrewAI, etc.
**Pros** | Optimized for specific tasks, easy to use | Fast development, preconfigured integrations | High flexibility, no vendor lock-in
**Cons** | Limited flexibility, potential feature lock-in | Potential ecosystem lock-in, pricing variability | Requires technical expertise, self-management

## Deep Research
Tired of endless Google searches? Enter Deep Research! This trend takes web search integration to a whole new level, moving beyond simple chatbots that just fetch info. Imagine an AI that not only searches the web but also crafts a detailed research plan, investigates each topic step-by-step, and then compiles its findings into a comprehensive report – complete with links to its sources! This capability, often referred to as report generation, has rapidly gained traction in the AI community. Perplexity was the first to the party with this functionality, launching its Deep Research feature in February 2025. This tool quickly garnered attention for its ability to generate in-depth research reports on virtually any topic, performing numerous searches, analyzing hundreds of sources, and reasoning through the material to deliver a comprehensive output. Perplexity's Deep Research is available on the web and is gradually rolling out to mobile platforms, offering a limited number of free queries daily for non-subscribers and a significantly higher limit for Pro users.

It wasn't long before others like OpenAI and Google jumped in. Shows you how quickly things move in the AI world! OpenAI followed suit in February 2025 with its own Deep Research agent, initially for Pro users, leveraging a version of their upcoming o3 model optimized for web browsing and data analysis. This tool aimed to function as a "research analyst," capable of independently retrieving, analyzing, and synthesizing online information to produce structured reports with citations. OpenAI later expanded access to Plus, Team, Enterprise, and even free users with a lightweight version powered by o4-mini. Google also entered the arena with Gemini's Deep Research, initially launched in December 2024 for Gemini Advanced subscribers and further updated in March 2025. Gemini's approach involves transforming prompts into multi-point research plans, autonomously searching and browsing the web, reasoning over gathered information, and providing comprehensive reports, sometimes even with audio overviews.

Comparisons between these Deep Research tools have already begun to emerge. Perplexity is often lauded for its speed and accessibility, offering a free tier and generally faster response times. OpenAI's Deep Research is noted for its accuracy and the inclusion of clear citations. Gemini's Deep Research benefits from its deep integration with Google's search expertise and the unique feature of audio overviews. Ultimately, the choice of which Deep Research tool to use may depend on individual needs and priorities, whether it's speed, accuracy, integration, or cost-effectiveness.

## Voice Interface
Who needs keyboards anyway? While they've been around for ages, there's a growing wave towards using our voices for more natural chats with AI. While many chatbots already offer basic speech-to-text or text-to-speech functionality, May 2025 has seen some truly remarkable advancements in creating more human-like and intuitive voice interfaces.

### ChatGPT's Advanced Voice Mode
ChatGPT's Advanced Voice Mode is like talking to a real person (almost!). It picks up on your tone, accent, even those awkward pauses when you're thinking. This multi-modal interface processes the user's voice directly, reacting to nuances like tone, accents, pauses, and cadence. It's especially cool for language learning, helping you nail that pronunciation. This mode aims to mimic human conversation more closely by reducing interruptions and allowing for more natural pacing. Users on paid plans also benefit from an updated personality that OpenAI describes as "more engaging, direct, and concise".

### Sesame
Then there's Sesame, a startup making waves with its incredibly realistic AI voices. They can handle tone, pauses, even laughter! While it still infers emotions from context, the responses sound eerily human. Sesame's new Conversational Speech Model (CSM) has even led some testers to report feeling emotional connections to the AI voices, named Maya and Miles. The company, founded by Brendan Iribe (co-founder of Oculus), aims to achieve "voice presence," making spoken interactions feel genuinely real, understood, and valued. Sesame's technology analyzes entire conversations to adjust tone, rhythm, and pacing based on mood and content, mimicking natural human speech.

### Nari-labs' Dia
Fresh off the press! Nari-labs dropped Dia just last week. This model is a master of context, generating tones that fit the conversation, even handling multiple speakers, laughs, and coughs! Released in late April 2025, Dia is an open-source Text-to-Speech (TTS) model designed to generate realistic, multi-speaker dialogue directly from text transcripts, complete with non-verbal cues. And get this – it was developed by just TWO people! Talk about impressive! This really shows what's achievable today with focused effort. Dia distinguishes itself by focusing on generating realistic dialogue with relevant tones based on conversation context, even handling multiple speakers and non-verbal expressions like laughs and coughs.

## Key AI Releases
The AI world never sleeps, and May 2025 has already brought a flurry of exciting releases and updates. Here are a few noteworthy highlights:

### NotebookLM from Google
Google's NotebookLM just got a cool upgrade: it can now generate podcast-style audio summaries in over 50 languages, including Czech! Great for learning on the go!. This feature, powered by Gemini's native audio support, allows users to transform their notes and sources into engaging, podcast-like conversations that can be downloaded for offline listening.

### Alibaba Group
Big news from Alibaba! They've released an Open-Weight model with some serious reasoning power, and it's under the Apache 2.0 license. This means you can run it on your own hardware, even for commercial use! Alibaba launched its Qwen 3 model family on April 28, 2025, with all models licensed under the permissive Apache 2.0 license. This release includes eight distinct models, featuring both dense and Mixture of Experts (MoE) architectures, with sizes ranging from 0.6B to 235B parameters. A key feature of Qwen 3 is its hybrid approach to problem-solving, supporting both a "Thinking mode" for complex reasoning and a "Non-Thinking mode" for faster, direct responses.

### OpenAI
OpenAI hasn't been sitting still either! They've dropped the full version of their o3 model, along with the o4-mini. These are the 'thinkers' of the AI world, designed to take their time and really ponder before giving you an answer. Great for those tricky tasks like coding, tackling complex math problems, diving into science, or even understanding visual data. Released on April 16, 2025, o3 and o4-mini are the latest in OpenAI's o-series of reasoning models. These models are trained to deliberate longer before responding, showcasing enhanced capabilities in coding, math, science, and even visual perception. They also have full access to tools within ChatGPT, including web search, file analysis, and image generation, enabling a new level of agentic problem-solving.

### Gemini 2.5 from Google
And last but not least, Google's Gemini 2.5 has been making waves, quickly climbing to the top of the LLM leaderboards! You can even try it out for free in preview mode, in both its 'Flash' (fast) and 'Pro' (powerful) versions. Go give it a whirl! Gemini 2.5 from Google has rapidly ascended the LLM leaderboards, demonstrating state-of-the-art performance across a range of benchmarks. Available in preview mode since March and April 2025, both the Flash and Pro versions offer a glimpse into Google's most intelligent AI model yet, featuring enhanced reasoning and advanced coding capabilities.

## Must-Listen AI Podcasts
Staying informed in the fast-paced world of AI can be a challenge, but thankfully, there are some fantastic podcasts out there to help you keep up. We label each podcast using these three categories:
- **Complexity**: Indicates the level of technical knowledge needed to understand the AI concepts discussed.
- **Applicability**: Shows how directly the AI solution can be applied to common tasks.
- **Timeline**: Reflects how long it will take for the technology to be available.

Here are a few must-listens:

### AI for Humans Podcast - [Listen here](https://www.aiforhumans.show/deepmind-says-were-not-ready-for-agi-academy-awards-say-ai-video-is-ok-and-ai-voice-models-get-we/)
- Want to hear some expert opinions on whether we're ready for AGI? The latest episode of the 'AI for Humans' podcast dives into DeepMind's take, plus the Academy Awards' view on AI video and some truly bizarre AI voice model developments. Released on April 24, 2025, this episode breaks down Google’s new "Era of Experience" paper, discussing agentic systems, long-term memory, and the potential for truly intelligent machines. Plus, you'll hear about a real AI vending machine running on Claude and a robot half-marathon in Beijing! And for a bit of dark humor, they talk about Cluely, the tool that helps you lie better with AI! Also, they touch on AI video tools from Minimax and Character.AI. And let's not forget Runway’s 48-hour film contest and Dia, the open-source voice model that can scream and cough better than humans!

- **Complexity**: 🤯
- **Applicability**: 🎯 🎯 🎯
- **Timeline**: 🗓️

### Last Week in AI Podcast - [Listen here](https://lastweekin.ai/p/lwiai-podcast-205-gemini-25-chatgpt)
- Stay up-to-date with the rapid pace of AI with the 'Last Week in AI' podcast. Their episode #205, released around April 1, 2025, covers the impressive image generation capabilities of ChatGPT, showcasing some serious advancements. They also discuss OpenAI's massive $40 billion funding round (led by SoftBank), Sam Altman's move towards technical direction, and Anthropic's groundbreaking research into understanding how AI models reason. And if you're into pushing AI to its limits, they talk about new benchmarks like ARC AGI 2 and super-tough Sudoku puzzles! This podcast provides weekly summaries and discussions about the most interesting developments in AI, deep learning, and robotics.

- **Complexity**: 🤯 🤯 🤯
- **Applicability**: 🎯 🎯
- **Timeline**: 🗓️ 🗓️

### Practical AI Podcast - [Listen here](https://practicalai.fm/309)
- For a more technical deep-dive, check out the 'Practical AI' podcast. Their episode #309, released around April 14, 2025, features a discussion with EPAM's Chief Technologist about the nitty-gritty of orchestrating AI agents and managing connections to different systems using APIs and MCP servers. You'll get insights from Pavel Veller about his work with agentic architectures and internal tools like 'DIAL'. They also demystify MCP servers and explain why connecting AI assistants via APIs is relatively easy, but making them genuinely useful is the real challenge. This podcast focuses on productive implementations and real-world scenarios in artificial intelligence.

- **Complexity**: 🤯 🤯 🤯 🤯
- **Applicability**: 🎯 🎯 🎯 🎯
- **Timeline**: 🗓️

#### Disclaimer
We've crafted this newsletter based on our own ideas, but leveraged AI for editing, fact-checking, and tone; please share your thoughts to help us refine our approach.

---
---

# AI Insights #1 – Květen 2025
Vítejte u prvního vydání newsletteru AI Insights! Naším cílem je pravidelně vás informovat o nejvýznamnějších trendech a novinkách, které utvářejí svět umělé inteligence. Chceme být vaším průvodcem světem AI, který se prosekává žargonem a zdůrazňuje to, co je skutečně důležité, abychom sdíleli důležité informace, které mohou inspirovat naše projekty a přinést nové perspektivy. V tomto prvním vydání se zaměříme na největší trendy v AI, které jsme dosud zaznamenali. I když některé novinky nemusí být přímo aplikovatelné v naší práci, věříme, že je důležité mít přehled o širším dění v oboru.

V nadcházejících měsících se budeme soustředit na podrobnější aktualizace o vývoji u předních společností v oblasti AI a budeme bedlivě sledovat dění v Open Source ekosystému. Jelikož se jedná o naši první cestu, vaše zpětná vazba je neocenitelná! Dejte nám vědět, co si myslíte o formátu, jaká témata byste chtěli, abychom prozkoumali příště, zda preferujete hlubší analýzy specifických oblastí, nebo kratší a častější aktualizace. Jsme připraveni naslouchat a udělat z tohoto newsletteru cenný zdroj informací pro vás.

## AI Agenti
AI agenti jsou NEJŽHAVĚJŠÍ téma v AI pro rok 2025! Ale co jsou přesně zač? Obecně řečeno, AI agent je systém nebo program navržený k autonomnímu provádění úkolů tím, že si navrhne vlastní pracovní postup a využívá dostupné nástroje. Možná si myslíte: "Hele, to zní jako prakticky každý chatbot, který tu je, že?" A máte pravdu! Podle této definice by i současné chatboti, kteří používají vyhledávací nástroje k získání informací před odpovědí na vaše dotazy, mohli technicky kvalifikovat jako agenti. Ale je pravděpodobně užitečnější přemýšlet o agentním chování jako o spektru, než o jednoduchém ano nebo ne. Představte si to jako 'inteligenci' u lidí – není to jen binární stav, ale celá škála schopností. AI scéna v květnu 2025 ukazuje fascinující škálu agentních přístupů, které lze obecně rozdělit do tří hlavních vzorů.

### AI Agent Produkty
Jedná se o AI systémy pečlivě optimalizované pro specifické případy použití, které nabízejí působivou sílu v rámci jejich definovaných hranic. Tato specializace však často přichází s menší flexibilitou, pokud jde o integraci vlastních nástrojů nebo unikátních integrací. Příkladem AI Agent produktu, který dělá vlny, je Manus, čínský startup, který se objevil v březnu 2025 a skutečně ohromil lidi svými pozoruhodnými schopnostmi řešení problémů. Ukázalo se, že tento působivý výkon byl poháněn standardním Claude Sonnet od Anthropicu, vybaveným pečlivě vybraným arzenálem 29 nástrojů. To ukazuje, kolik současné velké jazykové modely (LLMs) jsou schopny, když jsou aplikovány strategicky. Klíčovým závěrem zde je, že tyto produkty AI agentů jsou jako vysoce specializované nástroje – úžasné pro práci, pro kterou jsou vytvořeny, ale ne tak skvělé pro vlastní integrace.

### Spravované Agentní Platformy
Velcí hráči (a některé přední startupy) také vstupují do hry s agenty pomocí spravovaných agentních platforem. Představte si je jako své 'AI Agent Starter Kits' – předkonfigurované a připravené k použití! Příklady zahrnují Azure AI Agent Service & Microsoft Copilot Studio, AWS Agent Builder a Google's Vertex AI Agent Builder. Tyto platformy přicházejí s předem vytvořenými integracemi, což činí vytvoření prvního agenta velmi rychlým. Nicméně upozornění: tyto platformy jsou často optimalizovány pro ekosystém poskytovatele, takže buďte opatrní vůči potenciálnímu 'vendor lock-in'. Ceny se také mohou značně lišit v závislosti na počtu konverzací, využití infrastruktury a výpočetní síle.

### Open-Source Knihovny
Pro nadšence do DIY je ekosystém Open-Source plný možností! Tyto knihovny nabízejí maximální flexibilitu, ale pamatujte, že jste to vy, kdo je za vývoj a správu zodpovědný. Klíčovými hráči v této oblasti jsou LangGraph (od skvělého týmu LangChain), LlamaIndex, SmolAgents (díky HuggingFace!), CrewAI, AutoGen a Microsoft's SemanticKernel.

Abychom poskytli jasnější obraz o těchto různých vzorech, zde je rychlé srovnání:

Funkcionalita | AI Agent Produkty | Spravované Agentní Platformy | Open-Source Knihovny
|-----|-----|-----|-----|
**Zaměření** | Úzce zaměřené použití | Rychlost implementace | Flexibilita and přizpůsobitelnost
**Flexibilita** | Málo flexibilní pro vlastní integrace | Optimizováné pro ekosystém poskytovatele | Vysoce flexibilní
**Jednoduchost implementace** | Obecně uživatelsky přívětivé pro zamýšlený účel | Snadné počáteční nastavení s předkonfigurovanými integracemi | Vyžaduje vlastní správu a úsilí při vývoji
**Integrace** | Omezeno na potřeby specifických případů použití | Optimalizováno pro ekosystém konkrétního poskytovatele cloudu | Vysoce přizpůsobitelné s různými nástroji a API
**Správa** | Spravováno dodavatelem produktu | Spravováno poskytovatelem platformy | Vyžaduje vlastní správu
**Příklad** | Manus | Azure AI Agent Service, Copilot Studio, etc. | LangGraph, LlamaIndex, CrewAI, etc.
**Výhody** | Optimalizováno pro specifické úkoly, snadné použití | Rychlý vývoj, předkonfigurované integrace | Vysoká flexibilita, bez vendor lock-in
**Nevýhody** | Omezená flexibilita, potenciální uzamčení funkcí | Potenciální uzamčení ekosystému, variabilita cen | Vyžaduje technickou odbornost, vlastní správu

## Podrobný výzkum (deep research)
Jste unaveni nekonečným vyhledáváním na Googlu? Právě pro vás je tu podrobný výzkum! Tento trend posouvá integraci webového vyhledávání na zcela novou úroveň, přesahující jednoduché chatboti, kteří pouze získávají informace. Představte si AI, která nejen hledá na webu, ale také vytváří podrobný výzkumný plán, vyšetřuje každé téma krok za krokem a poté své závěry sestaví do komplexní zprávy – včetně odkazů na své zdroje! Tato schopnost, často označovaná jako generování zpráv, rychle získává na popularitě v komunitě AI. Perplexity byla první na party s touto funkcí, spuštěním své funkce Deep Research v únoru 2025. Tento nástroj rychle získal pozornost díky své schopnosti generovat podrobné výzkumné zprávy prakticky na jakékoli téma, provádět četné vyhledávání, analyzovat stovky zdrojů a důkladně procházet materiál, aby poskytl komplexní výstup. Deep Research od Perplexity je k dispozici na webu a postupně se rozšiřuje na mobilní platformy, nabízí omezený počet bezplatných dotazů denně pro nepředplatitele a výrazně vyšší limit pro uživatele Pro.

Netrvalo dlouho, než se připojili i další, jako OpenAI a Google. Ukazuje to, jak rychle se věci v AI světě pohybují! OpenAI následovalo v únoru 2025 s vlastním agentem Deep Research zpočátku pro uživatele Pro, využívající verzi jejich nadcházejícího o3 modelu optimalizovaného pro prohlížení webu a analýzu dat. Tento nástroj měl fungovat jako "výzkumný analytik," schopný samostatně získávat, analyzovat a syntetizovat online informace k vytvoření strukturovaných zpráv s citacemi. OpenAI později rozšířilo přístup na uživatele Plus, Team, Enterprise a dokonce i na bezplatné uživatele s lehkou verzí poháněnou o4-mini. Google také vstoupil na scénu s Gemini's Deep Research, původně spuštěným v prosinci 2024 pro předplatitele Gemini Advanced a dále aktualizovaným v březnu 2025. Přístup Gemini zahrnuje transformaci podnětů do vícepásmových výzkumných plánů, autonomní vyhledávání a prohlížení webu, uvažování nad shromážděnými informacemi a poskytování komplexních zpráv, někdy i s audio přehledy.

Porovnání mezi těmito nástroji pro podrobný výzkum již začala vznikat. Perplexity je často chváleno za svou rychlost a dostupnost, nabízející bezplatnou úroveň a obecně rychlejší reakční časy. Hluboký výzkum od OpenAI je známý svou přesností a zahrnutím jasných citací. Podrobný výzkum od Gemini těží ze své hluboké integrace s odbornými znalostmi v oblasti vyhledávání Google a unikátní funkcí audio přehledů. Nakonec volba, který nástroj pro Deep Research použít, může záviset na individuálních potřebách a prioritách, ať už jde o rychlost, přesnost, integraci nebo nákladovou efektivitu.

## Hlasové rozhraní
Kdo potřebuje klávesnice, že? I když jsou tu už dlouho, existuje rostoucí vlna směrem k používání našich hlasů pro přirozenější rozhovory s AI. Ačkoli mnoho chatbotů již nabízí základní funkce převodu řeči na text nebo textu na řeč, květen 2025 zaznamenal skutečně pozoruhodný pokrok ve vytváření více lidských a intuitivních hlasových rozhraní.

### Pokročilý hlasový režim ChatGPT
Pokročilý hlasový režim ChatGPT je jako mluvit s skutečným člověkem (skoro!). Vnímá váš tón, přízvuk, dokonce i ty trapné pauzy, když přemýšlíte. Toto multimodální rozhraní zpracovává uživatelův hlas přímo, reaguje na nuance jako tón, přízvuky, pauzy a kadence. Je zvlášť skvělé pro učení jazyků, pomáhá vám zvládnout tu výslovnost. Tento režim si klade za cíl napodobit lidskou konverzaci blíže tím, že omezuje přerušení a umožňuje přirozenější tempo. Uživatelé na placených plánech také těží z aktualizované osobnosti, kterou OpenAI popisuje jako "více poutavou, přímou a stručnou".

### Sesame
Pak je tu Sesame, startup, který dělá vlny svými neuvěřitelně realistickými AI hlasy. Zvládnou tón, pauzy, dokonce i smích! I když stále odvozuje emoce z kontextu, reakce zní děsivě lidsky. Nový model konverzační řeči (CSM) od Sesame vedl dokonce některé testery k pocitu emocionálních spojení s AI hlasy, pojmenovanými Maya a Miles. Společnost, kterou založil Brendan Iribe (spoluzakladatel Oculus), si klade za cíl dosáhnout "hlasové přítomnosti," takže mluvené interakce působí skutečně reálně, pochopeně a ceněně. Technologie Sesame analyzuje celé rozhovory, aby upravila tón, rytmus a tempo na základě nálady a obsahu, napodobujíc přirozenou lidskou řeč.

### Dia od Nari-labs
Máme tu i žhavou novinku! Nari-labs zveřejnil Dia teprve minulý týden. Tento model je mistrem kontextu, generuje tóny, které odpovídají konverzaci, zvládá dokonce více mluvčích, smích a kašlání! Uvolněný koncem dubna 2025, Dia je open-source model textu na řeč (TTS) navržený k generování realistického, více mluvčího dialogu přímo z textových přepisů, včetně neverbálních narážek. A představte si to – vyvinuli ho jen DVA lidé! To opravdu ukazuje, co je dnes možné s cíleným úsilím. Dia se vyznačuje tím, že se zaměřuje na generování realistického dialogu s relevantními tóny na základě kontextu konverzace, zvládá dokonce více mluvčích a neverbální projevy jako smích a kašel.

## Klíčové novinky AI
AI svět nikdy nespí, a květen 2025 již přinesl záplavu vzrušujících vydání a aktualizací. Zde jsou některé pozoruhodné momenty:

### NotebookLM od Google
NotebookLM od Google právě dostal skvělou aktualizaci: nyní může generovat audio souhrny ve stylu podcastů ve více než 50 jazycích, včetně češtiny! Skvělé pro učení na cestách! Tato funkce, poháněná nativní podporou audia od Gemini, umožňuje uživatelům transformovat své poznámky a zdroje do poutavých, podcastových konverzací, které lze stáhnout pro poslech offline.

### Alibaba Group
Velké zprávy od Alibaba! Vydali model s otevřenou váhou s vážnou schopností uvažování a je pod licencí Apache 2.0. To znamená, že jej můžete spustit na svém vlastním hardwaru, dokonce i pro komerční použití! Alibaba uvedla svou modelovou rodinu Qwen 3 dne 28. dubna 2025, přičemž všechny modely jsou licencovány pod permisivní licencí Apache 2.0. Toto vydání zahrnuje osm různých modelů, včetně jak hustých, tak architektur Mixture of Experts (MoE), s velikostmi od 0.6B do 235B parametrů. Klíčovou vlastností Qwen 3 je jeho hybridní přístup k řešení problémů, podporující jak "Thinking mode" pro složité uvažování, tak "Non-Thinking mode" pro rychlejší, přímé odpovědi.

### OpenAI
OpenAI také nezůstává pozadu! Vydali plnou verzi svého modelu o3, spolu s o4-mini. Jsou to 'myslitelé' AI světa, navržení tak, aby si dali načas a opravdu přemýšleli, než vám poskytnou odpověď. Skvělé pro ty složité úkoly jako kódování, řešení složitých matematických problémů, ponoření se do vědy nebo dokonce porozumění vizuálním datům. Vydané 16. dubna 2025, o3 a o4-mini jsou nejnovějšími modely v sérii o-modelů OpenAI pro uvažování. Tyto modely jsou vyškoleny k tomu, aby déle přemýšlely před odpovědí, což ukazuje rozšířené schopnosti v kódování, matematice, vědě a dokonce i vizuálním vnímání. Mají také plný přístup k nástrojům v ChatGPT, včetně webového vyhledávání, analýzy souborů a generování obrázků, což umožňuje novou úroveň agentního řešení problémů.

### Gemini 2.5 od Google
A nakonec, ale ne méně důležité, Gemini 2.5 od Google dělá vlny, rychle se vyšplhalo na vrchol žebříčků LLM! Můžete si ho dokonce vyzkoušet zdarma v režimu náhledu, v jeho verzích 'Flash' (rychlý) a 'Pro' (výkonný). Jděte to zkusit! Gemini 2.5 od Google rychle vystoupalo na žebříčky LLM, demonstrující špičkový výkon na celé řadě benchmarků. K dispozici v režimu náhledu od března a dubna 2025, obě verze Flash a Pro nabízejí pohled na nejinteligentnější AI model Google dosud, zahrnující rozšířené uvažování a pokročilé schopnosti kódování.

## Doporučené AI podcasty
Udržet se informovaný v rychle se pohybujícím světě AI může být výzvou, ale naštěstí existují skvělé podcasty, které vám pomohou držet krok. Každý podcast označujeme pomocí těchto tří kategorií:
- **Složitost**: Ukazuje úroveň technických znalostí potřebných k pochopení diskutovaných konceptů AI.
- **Použitelnost**: Ukazuje, jak přímo může být AI řešení aplikováno na běžné úkoly.
- **Horizont**: Odráží, jak dlouho bude trvat, než bude technologie dostupná.

Zde je několik, které musíte slyšet:

### AI for Humans Podcast - [Listen here](https://www.aiforhumans.show/deepmind-says-were-not-ready-for-agi-academy-awards-say-ai-video-is-ok-and-ai-voice-models-get-we/)
Chcete slyšet nějaké odborné názory na to, zda jsme připraveni na AGI? Nejnovější epizoda podcastu 'AI for Humans' se ponoří do pohledu DeepMind, plus pohled Akademie filmových umění na AI video a některé skutečně bizarní vývoj AI hlasových modelů. Vydáno 24. dubna 2025, tato epizoda rozebírá nový dokument Google "Era of Experience", diskutuje agentní systémy, dlouhodobou paměť a potenciál skutečně inteligentních strojů. Navíc uslyšíte o skutečném AI automatu běžícím na Claude a robotickém půlmaratonu v Pekingu! A pro trochu černého humoru, mluví o Cluely, nástroji, který vám pomáhá lépe lhát s AI! Také se dotýkají AI video nástrojů od Minimax a Character.AI. A nezapomeňme na 48hodinovou filmovou soutěž Runway a Dia, open-source hlasový model, který dokáže lépe křičet a kašlat než lidé!

- **Složitost**: 🤯
- **Použitelnost**: 🎯 🎯 🎯
- **Horizont**: 🗓️

### Last Week in AI Podcast - [Listen here](https://lastweekin.ai/p/lwiai-podcast-205-gemini-25-chatgpt)
Zůstaňte aktuální s rychlým tempem AI s podcastem 'Last Week in AI'. Jejich epizoda #205, vydaná kolem 1. dubna 2025, pokrývá působivé schopnosti generování obrázků ChatGPT, ukazující některé vážné pokroky. Také diskutují o masivním kole financování OpenAI ve výši 40 miliard dolarů (vedeném SoftBank), o přesunu Sama Altmana směrem k technickému vedení a průlomovém výzkumu Anthropicu ohledně pochopení, jak AI modely uvažují. A pokud se zajímáte o posouvání AI na její hranice, mluví o nových benchmarcích jako ARC AGI 2 a super-těžkých Sudoku hádankách! Tento podcast poskytuje týdenní souhrny a diskuse o nejzajímavějších vývoji v AI, hlubokém učení a robotice.

- **Složitost**: 🤯 🤯 🤯
- **Použitelnost**: 🎯 🎯
- **Horizont**: 🗓️ 🗓️

### Practical AI Podcast - [Listen here](https://practicalai.fm/309)
Pro technicky hlubší ponor si poslechněte podcast 'Practical AI'. Jejich epizoda #309, vydaná kolem 14. dubna 2025, obsahuje diskusi s hlavním technologem EPAM o detailech orchestrace AI agentů a řízení spojení s různými systémy pomocí API a MCP serverů. Získáte náhledy od Pavla Vellera o jeho práci s agentními architekturami a interními nástroji jako 'DIAL'. Také demystifikují MCP servery a vysvětlují, proč je připojení AI asistentů prostřednictvím API relativně snadné, ale jejich skutečné využití je skutečnou výzvou. Tento podcast se zaměřuje na produktivní implementace a reálné scénáře v oblasti umělé inteligence.

- **Složitost**: 🤯 🤯 🤯 🤯
- **Použitelnost**: 🎯 🎯 🎯 🎯
- **Horizont**: 🗓️

#### Upozornění
Tento newsletter jsme vytvořili na základě našich vlastních názorů, ale využili jsme AI pro úpravy, kontrolu faktů a tón; prosím, podělte se o své názory, abyste nám pomohli vylepšit následující vydání.
