# database-di-skills

[![Licenza: MIT](https://img.shields.io/badge/Licenza-MIT-green?style=flat)](LICENSE)
![Voci](https://img.shields.io/badge/voci-144-blue?style=flat)
![Sezioni](https://img.shields.io/badge/sezioni-31-blue?style=flat)

---

Libreria di riferimento per skill e strumenti che vale la pena conoscere.

---

### 1. 🎨 Migliora il Design degli Agenti AI

- **[pbakaus/impeccable](https://github.com/pbakaus/impeccable)** — Comandi dedicati per ridisegnare il tuo progetto a seconda del tuo gusto, evitando i pattern di AI slop.
- **[Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)** — Dà al modello un gusto estetico per font, immagini e disposizioni.
- **[Nutlope/hallmark](https://github.com/Nutlope/hallmark)** — Simile alle due skills precedenti, riconosce i pattern di AI-slop e impone regole di design diverse. Disponibile in Claude Code, Cursor e Codex.
- **[VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md)** — Raccolta di[ DESIGN.md](http://design.md) ricavati in reverse-engineering dai brand più conosciuti (Airbnb, NVIDIA, Apple, ...). Usala per prendere spunto dai design più famosi.
- **[google-labs-code/](https://github.com/google-labs-code/design.md)[design.md](http://design.md)** — Paradigma introdotto da Google per standardizzare e descrivere l'identità visiva di un prodotto ad un coding agent.

### 2. 🧩 Componenti UI, CSS ed icone

- **[shadcn/ui](https://ui.shadcn.com)** — La libreria di componenti per il design che puoi customizzare, estendere, ed utilizzare come punto di partenza, open source.
- **[21st.dev](http://21st.dev)** — Marketplace di componenti utilizzabili per i tuoi siti web (con MCP incluso).
- **[nexu-io/open-design](https://github.com/nexu-io/open-design)** — La versione open-source di Claude Design, gratuita e senza limiti.
- **[facebook/astryx](https://github.com/facebook/astryx)** — Design system open-source creato sull'esperienza degli anni passati da META.
- **[nexu-io/html-anything](https://github.com/nexu-io/html-anything)** — Crea il tuo progetto in semplice markdown, e questa skill genera poi l'HTML.
- **[Tailwind CSS](https://tailwindcss.com)** — Un framework CSS-first per creare siti web interattivi con agenti.
- **[Motion](https://motion.dev)** — Libreria di animazioni per il web: transizioni e micro-interazioni da prendere ed aggiungere al tuo sito
- **[Lucide](https://lucide.dev)** — Set di icone completamente gratuito, open source.
- **[Jakubantalik/thinking-orbs](https://github.com/Jakubantalik/thinking-orbs)** — Indicatori di caricamento pensati apposta per le UI.

### 3. 🔧CLI (ufficiali + come costruirne una)

- **[HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)** — Repo in grado di creare una CLI per qualsiasi servizio, anche in assenza di API.
- **[jackwener/OpenCLI](https://github.com/jackwener/OpenCLI)** — Trasforma qualsiasi sito in una CLI, sfruttando il browser dove sei già loggato.
- **[mvanhorn/cli-printing-press](https://github.com/mvanhorn/cli-printing-press)** — Crea una CLI per qualsiasi servizio che usi: se esistono API pubbliche o un MCP parte dalla loro documentazione, altrimenti sniffa il traffico del sito per scoprire quali API vengono contattate e ci costruisce sopra la CLI.
- **[googleworkspace/cli](https://github.com/googleworkspace/cli)** — CLI ufficiale di Google per Drive, Gmail, Calendar, Sheets e Docs.
- **[iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)** — CLI per la Suite office, costruita affinché gli agenti possano leggere e modificare i documenti Office direttamente.
- **[cli/cli](https://github.com/cli/cli)** — La CLI ufficiale di GitHub: PR, issues, releases, actions - tutti i comandi a portata di agente.
- **[anthropics/anthropic-cli](https://github.com/anthropics/anthropic-cli)** — La CLI ufficiale per l'API di Claude. Comoda per chiamate veloci da script.

### 4. 🛠️ Tool per il Terminale

- **[BurntSushi/ripgrep](https://github.com/BurntSushi/ripgrep)** — Alternativa al comando grep da terminale, che cerca i file per i tuoi agenti molto più velocemente del comando standard.
- **[jesseduffield/lazygit](https://github.com/jesseduffield/lazygit)** — Utilizza Git in maniera interattiva da terminale, così da tener traccia di ogni comando.
- **[jqlang/jq](https://github.com/jqlang/jq)** — Processa e naviga file JSON direttamente dal tuo terminale. Utilissimo per lavorare con le riposte JSON alle chiamate API.
- **[yt-dlp/yt-dlp](https://github.com/yt-dlp/yt-dlp)** — Scarica audio e video ***gratuitamente*** per qualsiasi file.
- **[herdrdev/herdr](https://github.com/herdrdev/herdr)** — Background server runtime hostato su Github, e creato specificamente per agenti AI di coding.

### 5. 🌐 Controllare il browser con Agenti AI

- **[Playwright](https://playwright.dev)** — La libreria di automazioni browser più conosciuta ed usata: fai screenshot, compila form, fai scraping, esegui tests.
- **[microsoft/playwright-cli](https://github.com/microsoft/playwright-cli)** — CLI di Playwright.
- **[browser-use](https://github.com/browser-use/browser-use)** — alternativa a Playwright in Python.
- **[browserbase/stagehand](https://github.com/browserbase/stagehand)** — Alterna comandi in linguaggio naturale e codice Playwright per irrobustire l'automazione.
- **[browser-use/browser-harness](https://github.com/browser-use/browser-harness)** — Permette di collegare un LLM a un browser attraverso un singolo WebSocket.
- **[alibaba/page-agent](https://github.com/alibaba/page-agent)** — Libreria di Alibaba che produce una graphical user interface (GUI) per agenti AI direttamente in una pagina web.
- **[JCodesMore/ai-website-cloner-template](https://github.com/JCodesMore/ai-website-cloner-template)** — Clona qualsiasi sito con un solo comando. Ottimo per studiare un layout che ti piace.

### 6. 🖥️ Controllare lo schermo e il telefono

- **[Computer Use (Anthropic)](https://platform.claude.com/docs/en/agents-and-tools/tool-use/computer-use-tool)** — Il tool ufficiale che fa uscire Claude dal browser: vede lo schermo via screenshot e usa mouse e tastiera, automatizzando le interazioni con i software che non espongono nessuna API.
- **[ShawnPana/phone-harness](https://github.com/ShawnPana/phone-harness)** — Tool open source che permette agli agenti AI di controllare un iPhone attraverso macOS iPhone Mirroring.

### 7. 🔌 Server MCP (e come crearne uno)

- **[punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)** — La lista di riferimento degli MCP server disponibili, divisi per categoria.
- **[jlowin/fastmcp](https://github.com/jlowin/fastmcp)** — Il modo più rapido per creare un MCP server: aggiungi un *decor* ad funzione Python, e l'agente la ritroverà come tool.
- **[modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk)** — L'SDK Python ufficiale per scrivere server e client MCP.
- **[modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk)** — Come sopra ma per i progetti TypeScript.
- **[tadata-org/fastapi_mcp](https://github.com/tadata-org/fastapi_mcp)** — Espone gli endpoint di una FastAPI che hai già come tool MCP, autenticazione inclusa.
- **[microsoft/mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners)** — Curriculum open source di Microsoft (per beginners) su MCP, con esempi reali.

### 8. 🔎 Ricerca sul web per Agenti AI

- **[Exa](https://exa.ai)** — Motore di ricerca pensato per gli LLM: cerca per significato invece che per parole chiavi.
- **[Tavily](https://tavily.com)** — Simile al precedente, offre API per ricerca ed estrazione di contenuti dal web per agenti AI.
- **[Firecrawl](https://firecrawl.dev)** — Fai scraping di qualsiasi sito web in larga scala.
- **[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)** — Ricerca cosa si è detto negli ultimi 30 giorni sui social (IG, TikTok, YouTube, ...) riguardo ad un tema da te scelto.
- **[koala73/worldmonitor](https://github.com/koala73/worldmonitor)** — Dashboard in tempo reale di notizie e geopolitica, aggregata dall'AI.

### 9. 📄 Manipola documenti

- **[microsoft/markitdown](https://github.com/microsoft/markitdown)** — Converte PDF, Office, immagini e audio in Markdown pulito, pensato per essere dato in pasto a un LLM.
- **[firecrawl/anydoc](https://github.com/firecrawl/anydoc)** — Trasforma Word, PowerPoint, Excel, EPUB e PDF in un file in Markdown.
- **[baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR)** — Esegui parsing di documenti lunghissimi in un colpo solo.

### 10. 🎓 Usa Agenti AI per Imparare

- **[karpathy/autoresearch](https://github.com/karpathy/autoresearch)** — Framework di Karpathy per rendere gli agenti autonomi nel loro ciclo di ricerca.
- **[HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor)** — Trasforma il tuo agente in un tutor personalizzato.
- **[/teach](https://www.aihero.dev/skills-teach)** — Simile al precedente, impara tutto quello che vuoi sapere su di un topic usando il tuo agente come insegnante.
- **[virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill)** — Trasforma libri in PDF, documenti o qualsiasi altra risorsa tecnica in una skill di Claude Code.

### 11. 🪫 Limita il Consumo di Token

- **[JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)** — Taglia circa il 65% dei token mantenendo le performance intatte riducendo la verbosità del modello.
- **[DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail)** — Riduci la quantità di codice scritto mantenendo la qualità e correttezza del codice.
- **[headroomlabs-ai/headroom](https://github.com/headroomlabs-ai/headroom)** — Comprime output dei tool, log, file e chunk RAG prima che arrivino al modello - circa il 20% di token in meno senza toccare il codice originale.
- **[thomaschill/unclog](https://github.com/thomaschill/unclog)** — Tool che dice chi sta utilizzando di più la context window: MCP server, skill,[ CLAUDE.md](http://claude.md), in modo da eliminare ciò che non serve e guadagnare nuovamente contesto.

### 12. 💸 Monitora la spesa di Token

- **[getagentseal/codeburn](https://github.com/getagentseal/codeburn)** — Dashboard visiva dei consumi dei tuoi agenti: legge dal disco i transcript delle sessioni (Claude Code, Codex, Cursor), li classifica per tipo di attività e ti mostra grafici e metriche. Nessuna API key, gira interamente offline.
- **[ryoppippi/ccusage](https://github.com/ryoppippi/ccusage)** — Report da terminale su quanto stai consumando in Claude Code, ricavato dai file di sessione locali.

### 13. 🧠 Memoria tra una sessione e l'altra

- **[thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)** — Cattura quello che l'agente fa durante la sessione e lo comprime nella memoria persistente, così alla sessione dopo non riparte da zero.
- **[MemPalace/mempalace](https://github.com/MemPalace/mempalace)** — Il sistema di memoria open-source che presenta i benchmark migliori.
- **[TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory)** — Memoria condivisa a livello di team, invece che per singolo sviluppatore.

### 14. 📚 Framework RAG

- **[HKUDS/LightRAG](https://github.com/HKUDS/LightRAG)** — RAG semplice, veloce, con struttura a grafo. Il default da cui partire.
- **[HKUDS/RAG-Anything](https://github.com/HKUDS/RAG-Anything)** — Il framework RAG tutto-in-uno, che permette di processare qualsiasi tipo di dato.
- **[run-llama/llama_index](https://github.com/run-llama/llama_index)** — Framework per costruire pipeline RAG per beginners.
- **[langchain-ai/langchain](https://github.com/langchain-ai/langchain)** — Il framework standard e più diffuso per costruire applicazioni e agenti sopra un LLM.
- **[deepset-ai/haystack](https://github.com/deepset-ai/haystack)** — Orchestrazione RAG orientata alla produzione, con pipeline esplicite e valutazione integrata.

### 15. 🗄️ Database vettoriali

- **[pgvector/pgvector](https://github.com/pgvector/pgvector)** — Database vettoriale, di solito il default per sistemi RAG.
- **[Chroma](https://trychroma.com)** — Vector store **locale**, facile da inizializzare.
- **[Qdrant](https://qdrant.tech)** — Database vettoriale ad alte prestazioni, self-hostabile.

### 16. 🕸️ Knowledge Graph per il codice

- **[Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify)** — Trasforma codebase, documentazione, schemi e PDF in un unico knowledge graph interrogabile (consumo di token alto).
- **[vitali87/code-graph-rag](https://github.com/vitali87/code-graph-rag)** — Processa codebase con all'interno linguaggi diversi e crea poi un knowledge graph che permette di interrogare, modificare o ottimizzare il codice tramite linguaggio naturale.
- **[colbymchenry/codegraph](https://github.com/colbymchenry/codegraph)** — Knowledge graph del codice pre-indicizzato che si aggiorna da solo a ogni modifica. Funziona con Claude Code, Codex, Cursor e OpenCode.
- **[DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)** — Indicizza il codebase in un knowledge graph persistente che l'agente può leggere ogni volta che serve.
- **[tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph)** — Mappa locale persistente del codebase, esposta via MCP e CLI.
- **[Egonex-AI/Understand-Anything](https://github.com/Egonex-AI/Understand-Anything)** — Trasforma una codebase in un grafo interattivo da esplorare e interrogare. Pensato per farti capire il codice, non per fare bella figura in slide.

### 17. 🗺️ Documentare il codebase

- **[langchain-ai/openwiki](https://github.com/langchain-ai/openwiki)** — Scrive la documentazione del codice a misura di agente e la mantiene aggiornata ad ogni cambiamento.
- **[shadcn/improve](https://github.com/shadcn/improve)** — Skill che fa un'audit completa della tua codebase e scrive poi un piano di implementazione per altri agenti.

### 18. 📝 Second Brain

- **[Obsidian](https://obsidian.md)** — Visualizzatore ed editor per file in markdown.
- **[kepano/obsidian-skills](https://github.com/kepano/obsidian-skills)** — Utilizza Obsidian via CLI con i tuoi agenti.
- **[AgriciDaniel/claude-obsidian](https://github.com/AgriciDaniel/claude-obsidian)** — Crea ed aggiorna in automatico il tuo second brain attraverso semplici comandi che seguono la struttura LLM-Wiki.
- **[Logseq](https://logseq.com)** — Alternativa a Obsidian basata sui blocchi, con outline e riferimenti bidirezionali.

### 19. 📓 Interroga documenti con l'AI

- **[NotebookLM](https://notebooklm.google.com)** — Il miglior strumento gratuito per rielaborare documenti.
- **[teng-lin/notebooklm-py](https://github.com/teng-lin/notebooklm-py)** — API Python non ufficiale per utilizzare NotebookLM nei nostri agenti.
- **[Open Notebook](https://github.com/lfnovo/open-notebook)** — Versione Open Source di NotebookLM che ha anche le API disponibili.

### 20. 📊 Diagrammi

- **[Excalidraw](https://excalidraw.com)** — Tool N. 1 per creare qualsiasi tipo di diagramma.
- **[coleam00/excalidraw-diagram-skill](https://github.com/coleam00/excalidraw-diagram-skill)** — Skill non ufficiale per utilizza Excalidraw nei coding agents.
- **[yizhiyanhua-ai/fireworks-tech-graph](https://github.com/yizhiyanhua-ai/fireworks-tech-graph)** — Descrivi a parole i diagrammi tecnici che vuoi realizzare (SVG/PNG di alta qualità).
- **[cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)** — 29 tipi di diagrammi editoriali in HTML+SVG pulito.
- **[tt-a1i/archify](https://github.com/tt-a1i/archify)** — Diagrammi di architettura software, sequenze, flusso dati e lifecycle.
- **[Mermaid](https://mermaid.js.org)** — Crea diagrammi a partire da file testuali in markdown. Utile per visualizzare documentazioni Github.
- **[terrastruct/d2](https://github.com/terrastruct/d2)** — Diagrammi come testo, tipo Mermaid ma con layout e resa molto più curati.
- **[tldraw](https://tldraw.com)** — Lavagna infinita con SDK: utile quando il diagramma deve finire dentro un'applicazione.

### 21. 🎙️ Trascrizione audio

- **[openai/whisper](https://github.com/openai/whisper)** — Trascrizione audio in locale, gratuita e con timestamp per parola.
- **[ggml-org/whisper.cpp](https://github.com/ggml-org/whisper.cpp)** — Whisper riscritto in C++: gira veloce anche su macchine modeste, senza dipendenze Python.
- **[SYSTRAN/faster-whisper](https://github.com/SYSTRAN/faster-whisper)** — Reimplementazione di Whisper fino a quattro volte più rapida, a parità di accuratezza.
- **[m-bain/whisperX](https://github.com/m-bain/whisperX)** — Trascrizione con timestamp allineati alla singola parola e riconoscimento di chi parla. Utile per editing di video.

### 22. 🎬 Montaggio video

- **[FFmpeg](https://ffmpeg.org)** — Tool open source che permette di modificare un video (rimuovere frame, cambiare fps, tagliare in dimensione, ...).
- **[Descript](https://www.descript.com)** — Monta il video editando il testo della trascrizione.
- **[Auphonic](https://auphonic.com)** — Normalizzazione audio, riduzione del rumore e livelli uniformi in automatico.
- **[Kdenlive](https://kdenlive.org)** — Editor video open source completo, senza abbonamento.

### 23. 🎛️ Orchestration Layer e task lunghi

- **[obra/superpowers](https://github.com/obra/superpowers)** — Il primo layer di orchestrazione e probabilmente il più famoso. Utile per pianificare lavori di media complessità.
- **[/wayfinder](https://github.com/mattpocock/skills/tree/main/skills/engineering/wayfinder)** — Layer di orchestrazione per pianificare quantità di lavoro elevate che non possono essere completate in una singola sessione di lavoro.
- **[bytedance/deer-flow](https://github.com/bytedance/deer-flow)** — Harness per compiti lunghi che ricerca, scrive codice e produce contenuti dentro a sandbox isolate.
- **[multica-ai/multica](https://github.com/multica-ai/multica)** — Assegna i task a Claude Code, Codex, Cursor e altri agenti in semplicità, distribuendo consumi e sfruttando le peculiarità di ogni servizio. Open source e self-hostabile.
- **[HKUDS/nanobot](https://github.com/HKUDS/nanobot)** — Agente personale self-hosted e ultraleggero in Python, con WebUI, memoria e MCP.
- **[gsd-build/gsd-2](https://github.com/gsd-build/gsd-2)** — Meta-prompting e sviluppo guidato da specifiche, pensato per far lavorare gli agenti a lungo senza perdere di vista il quadro generale.
- **[affaan-m/ECC](https://github.com/affaan-m/ECC)** — Sistema di performance per l'harness che segue il flusso plan -> test -> implement -> review -> verify -> remember -> improve.

### 24. 💻 IDE ed Editor

- **[Visual Studio Code](https://code.visualstudio.com/)** — Uno degli IDE più utilizzati per versatilità e facilità di utilizzo.
- **[Cursor](https://cursor.com)** — IDE costruito su Visual Studio Code con funzionalità di AI coding integrate. Permette di switchare comodamente tra diversi modelli AI e modalità di utilizzo.
- **[cline/cline](https://github.com/cline/cline)** — Agente autonomo dentro VS Code, con approvazione umana a ogni passo.
- **[Warp](https://warp.dev)** — Terminale con le funzioni agentiche native.

### 25. ⌨️ AI Coding Agents da terminale

- **[anthropics/claude-code](https://github.com/anthropics/claude-code)** — Qui poco da dire, il repo ufficiale di Claude Code da terminale.
- **[openai/codex](https://github.com/openai/codex)** — L'agente di coding di OpenAI, diretto competitor di Claude Code.
- **[open code](https://opencode.ai/)** — Alternativa Open Source a Claude Code. Simil harness ma con modelli open source (in locale e non).
- **[pi.dev](http://pi.dev)** — Simile ad Open Code, Harness open source con molta flessibilità, ideale se vuoi utilizzare massivamente i modelli open source.
- **[xai-org/grok-build](https://github.com/xai-org/grok-build)** — Harness di xAI legata a Grok, interattiva.
- **[openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter)** — Agente di coding pensato per i modelli open, esegue codice in locale e lavora sul tuo filesystem.

### 26. 🔀 Routing tra Agenti AI

- **[farion1231/cc-switch](https://github.com/farion1231/cc-switch)** — App desktop per passare al volo tra Claude Code, Codex, OpenCode e Grok Build tenendo profili e configurazioni separati.
- **[openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc)** — Il plugin ufficiale OpenAI per lanciare Codex da dentro una sessione di Claude Code. Serve ad avere un secondo paio di occhi indipendente: Codex non condivide il contesto di Claude, quindi rilegge il codice senza bias — utile soprattutto in code review prima del push.
- **[OpenRouter](https://openrouter.ai)** — Standard che accentra tutti i modelli (open source e non) attraverso una singola chiave API.
- **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)** — Gateway che permette di switchare tra diversi modelli quando i limiti di utilizzo sono terminati.
- **[LLM-Stats](https://llm-stats.com)** — Tool di confronto tra modelli, con prezzi e context window.

### 27. 🏠 Modelli AI in locale

- **[Ollama](https://ollama.com)** — Standard per utilizzare modelli interamente in locale.
- **[LM Studio](https://lmstudio.ai)** — Simile ad Ollama, con interfaccia grafica.

### 28. 🛡️ Sicurezza e verifica del codice

- **[NVIDIA/skillspector](https://github.com/NVIDIA/skillspector)** — Analizza una skill prima che tu la installi: analisi statica AST su 68 pattern di vulnerabilità in 17 categorie, poi un LLM legge i finding per abbattere i falsi positivi.
- **[gitleaks/gitleaks](https://github.com/gitleaks/gitleaks)** — Cerca chiavi API e segreti finiti per errore nella repository o nella cronologia git.
- **[Semgrep](https://semgrep.dev)** — Analisi statica su regole leggibili: intercetta pattern insicuri nel codice.
- **[mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills)** — 817 skill di cybersecurity di Anthropic.
- **[usestrix/strix](https://github.com/usestrix/strix)** — Strix utilizza agenti AI per testare la sicurezza del tuo codice, trovare eventuali vulnerabilità e aiutarti a risolverle

### 29. 🚀 Hosting e Deploy

- **[Vercel](https://vercel.com)** e **[Netlify](https://netlify.com)** — Player principali per hostare siti web ed applicazioni gratuitamente. Disponibili le CLI per fare tutto da terminale.
- **[Railway](https://railway.com)** — Servizio per mettere in produzione il tuo progetto con un vero backend e database.
- **[Cloudflare Workers](https://workers.cloudflare.com)** — Piano gratuito generoso per codice, storage e database.
- **[Coolify](https://coolify.io)** — Alternativa open source self-hosted a Vercel e Railway da installare sulla tua VPS.

### 30. 🐳 Database e Container

- **[Supabase](https://supabase.com)** — Database gratuito che offre moltissime funzioni: Postgres, autenticazione, database vettoriale, ...
- **[Docker](https://docker.com)** — Standard per la portabilità ed esecuzione di codice.
- **[apple/container](https://github.com/apple/container)** — Container Linux su Apple Silicon tramita una virtual machine leggera. Utile nei casi in cui è necessario avere Linux a portata di mano.

### 31. 📦 Raccolte di Skills

- **[hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code)** — La lista più grande di Skills su Github, creata e mantenuta dalla community. Dove cercare una skill quando ne abbiamo bisogno.
- **[anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)** — Directory di plugin ufficiali curata da Anthropic.
- **[anthropics/skills](https://github.com/anthropics/skills)** — Il repo ufficiale di Anthropic per le Skills.
- **[rohitg00/awesome-claude-code-toolkit](https://github.com/rohitg00/awesome-claude-code-toolkit)** — 135 agenti, 35 skill e 42 comandi per Claude Code in un unico posto.
- **[addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)** — Skill di engineering al livello di messa in produzione.
- **[Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)** — Più di 100 app di agenti e RAG da utilizzare e da cui puoi prendere spunto per i tuoi progetti.
- **[HKUDS/OpenSpace](https://github.com/HKUDS/OpenSpace)** — Layer di gestione per quando le skill diventano troppe da tenere in ordine.

---

Designed by **[Dario Fontanel, PhD](https://dariofontanel.com/)**

*Aiuto PMI italiane ad integrare l'intelligenza artificiale per automatizzare i lavori ripetitivi, abbattere i costi e guadagnare tempo per crescere.*

[![Sito](https://img.shields.io/badge/Sito-dariofontanel.com-4285F4?style=flat&logo=googlechrome&logoColor=white)](https://dariofontanel.com/)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white)](https://www.youtube.com/@dariofontanel)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white)](https://www.instagram.com/dariofontanel.ai/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjUgMHoiLz48L3N2Zz4%3D)](https://www.linkedin.com/in/dario-fontanel/)
[![TikTok](https://img.shields.io/badge/TikTok-000000?style=flat&logo=tiktok&logoColor=white)](https://www.tiktok.com/@dario.fontanel)
[![AI Academy](https://img.shields.io/badge/AI_Academy-E7514F?style=flat&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAzIDEgOWwxMSA2IDktNC45MVYxN2gyVjlMMTIgM3pNNSAxMy4xOFYxN2MwIDEuNjYgMy4xMyAzIDcgM3M3LTEuMzQgNy0zdi0zLjgybC03IDMuODItNy0zLjgyeiIvPjwvc3ZnPg%3D%3D)](https://www.skool.com/ai-academy-2306)

Rilasciato sotto [licenza MIT](LICENSE).
