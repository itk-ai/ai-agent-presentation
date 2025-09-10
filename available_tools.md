# Flowise AI Workshop – Værktøjsoversigt

Her finder du en oversigt over gode startværktøjer og lidt mere avancerede muligheder i [Flowise AgentFlow v2](https://docs.flowiseai.com/using-flowise/agentflowv2). 
Listen er kurateret i samarbejde med ChatGPT og Claude Sonnet 3.5.

## ⭐ Begyndervenlige værktøjer

Disse værktøjer kræver ingen eller minimal opsætning og er perfekte til at eksperimentere med i workshoppen.

1. Calculator

    - **Hvad den gør:** Fungerer som lommeregner for agenten
    - **Opsætning:** Ingen opsætning nødvendig – kan bruges direkte.

2. CurrentDateTime

   - **Hvad den gør:** Returnerer den aktuelle dato og tid. Kan bruges til tidsstempler eller tidsafhængige svar.
   - **Opsætning:** Ingen opsætning nødvendig.

3. **SerpAPI**
    - **Hvad den gør:** Giver adgang til Google-søgninger via SerpAPI, hvilket muliggør automatiserede og avancerede søgninger. Kan bruges til at finde information på nettet og hente strukturerede søgeresultater.
    - **Opsætning:**
        - Kræver en **API-nøgle** fra [SerpAPI](https://serpapi.com/).
        - [Se denne guide](./trin4trin_serpAPI_opsaetning.md)

4. WebScraperTool

   - **Hvad den gør:** Henter tekstindhold fra en given URL. Godt til at hente oplysninger fra en kommunes hjemmeside eller offentlig side.
   - **Opsætning:** Ingen API-nøgle kræves. Du skal blot give en URL som input.


## ⚡ Lidt mere avancerede værktøjer

Disse værktøjer åbner for mere funktionalitet, men kan kræve opsætning med tredjepartskonti. Overvej at bruge **testkonti**, hvis I ikke vil forbinde private profiler.


## Alternative gode værktøjer

3. BraveSearch *(alternativ til SerpAPI)*

   - **Hvad den gør:** Giver adgang til websearch via Brave’s søge-API. Kan bruges til at finde oplysninger på nettet i realtid.
   - **Opsætning:**

     - Kræver en **API-nøgle** fra Brave - denne er gratis, men man skal tilføje sine kreditkort oplysninger.
     - Opret en konto på [Brave Search API](https://api.search.brave.com/).
     - Kopiér API-nøglen ind i værktøjet i Flowise.


1. TavilySearchAPI *(alternativ til SerpAPI)*

   - **Hvad den gør:** Moderne søge-API der er nem at integrere, god til simple webopslag.
   - **Opsætning:**

     - Kræver en gratis **API-nøgle**.
     - Tilmeld dig på [Tavily](https://tavily.com/) og kopier API-nøglen til Flowise.


## Alle værktøjer i web udgaven af Flowise ai

_Bemærk der er flere værktøjer tilgængelige hvis man installerer Flowise AI på ens egen computer (det gør vi dog ikke til denne workshop)_

1. [AWS_SNS](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/AWSSNS)
2. [AgentTool](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/AgentTool)
3. [Arxiv](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/Arxiv)
4. [BraveSearch](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/BraveSearch)
5. [Calculator](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/Calculator)
6. [ChatflowTool](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/ChatflowTool)
7. [CodeInterpreterTool](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/CodeInterpreterTool)
8. [Composio](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/Composio)
8. [CurrentDateTime](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/CurrentDateTime)
9. [CustomTool](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/CustomTool)
10. [ExaSearchTool](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/ExaSearchTool)
11. [GmailTool](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/GmailTool)
12. [GoogleCalendarTool](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/GoogleCalendarTool)
13. [GoogleDocsTool](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/GoogleDocsTool)
14. [GoogleDriveTool](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/GoogleDriveTool)
15. [GoogleSheetsTool](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/GoogleSheetsTool)
16. [GoogleCustomSearchTool](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/GoogleCustomSearchTool)
17. [JiraTool](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/JiraTool)

MCP Tools:
1. [BraveSearchMCP](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/MCP/BraveSearch)
2. [GitHub](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/MCP/Github)
3. [CustomMCP](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/MCP/CustomMCP)
4. [PostgreSQL](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/MCP/PostgreSQL)
5. [Slack](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/MCP/Slack)
6. [SequentialThinking](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/MCP/SequentialThinking)
7. [Supergateway](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/MCP/Supergateway)

Microsoft Tools:
1. [OutlookTool](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/OutlookTool)
2. [TeamsTool](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/TeamsTool)

API Tools:
1. [OpenAPIToolkit](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/OpenAPIToolkit)
2. [RequestsDelete](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/RequestsDelete)
3. [RequestsGet](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/RequestsGet)
4. [RequestsPut](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/RequestsPut)
5. [RequestsPost](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/RequestsPost)

Search Tools:
1. [SearchAPI](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/SearchAPI)
2. [SearXNG](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/SearXNG)
3. [SerperDevTool](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/SerperDevTool)
4. [SerpAPI](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/SerpAPI)

Other Tools:
1. [StripeAgentTool](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/StripeAgentTool)
2. [TavilySearchAPI](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/TavilySearchAPI)
3. [WolframAlpha](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/WolframAlpha)
4. [WebScraperTool](https://github.com/FlowiseAI/Flowise/tree/main/packages/components/nodes/tools/WebScraperTool)
