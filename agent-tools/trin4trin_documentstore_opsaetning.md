# Guide: Opsætning af Document Store

*Hvis du vil bygge en dokumentassistent/søge i en dokumentsamling/bygge RAG, får du brug for Document Store. Her er et simpelt eksempel på hvordan sådan en kan oprettes*

## Del 1: Opret Document Store

1. Klik på "Document Stores" fra dashboardet og klik så "Add new". Udfyld felterne

   ![Document Store Create](screendumps/11_documentstore_create.png)

2. Inde i den nyoprettede Document store vælges "+ Add Document Loader", find et indlæsningsmodul, der passer med den/de filer du vil indlæse. Hvis du vil indlæse flere typer af information, så kan du tilføje flere forskellige Document loaders, men bemærk at den gratis cloud udgave af flowise kun kommer med 5MB opbevaring. I dette eksempel vælges en pdf loader

   ![Document Loader Setup](screendumps/12_documentstore_loader.png)

3. Udfyld felterne og upload den/de filer du skal bruge. Text splitteren kan du vælge til at være "Recursive Character Text Splitter", det er et okay standard valg og standard settings går an. 

   Undervejs har du mulighed for at trykke "preview chunk", hvis du vil have en fornemmelse af hvad du er på vej til at tilføje til Document storen.

   Til sidst klikkes "Process"

   ![Process PDF Setup](screendumps/13_documentstore_process_pdf.png)

   I min test har jeg brug en pdf med [AI forordningen](https://eur-lex.europa.eu/legal-content/DA/TXT/PDF/?uri=OJ:L_202401689)

## Del 2: Konfigurer Document Store Actions

1. For at kunne tilgå document store i dit AgentFlow skal den knyttes til en vectorstore og det gøres ved at vælge "Upsert Chunks"

   ![Document Store Extra Actions](screendumps/14_documentstore_ekstra_actionsupsert.png)

2. Her skal Embeddings og Vectorstore konfigureres, mens record manageren udelades. 

   Credential og Server URL for Qdrant deles med jer under workshoppen (men du er også velkommen til selv at oprette en gratis [qdrant vectorstore](screendumps/10_qdrant_signup.png))
   
   **Navngivning af Qdrant Collection** (markeret med "9" på billedet): Start venligst med `flowise-` og så sådan noget som to bogstaver fra dit fornavn, to bogstaver fra et efternavn, 3 tal fra din fødselsdato og så evt. noget beskrivende, der giver mening for dig selv. (For mig ville det så blive `flowise-dakj801-aiforordning`)

   ![Document Store Upsert](screendumps/15_documentstore_upsert.png)
