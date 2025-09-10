# Guide: Opsætning af Document Store

*Hvis du vil bygge en dokumentassistent/søge i en dokumentsamling/bygge RAG, får du brug for Document Store. Her er et simpelt eksempel på hvordan sådan en kan oprettes*

## Del 1: Opret Document Store

1. For at oprette en Document Store, skal du først tilføje en ny node ved at klikke på "+ Add Node" og vælge "Document Store"

   ![Document Store Create](screendumps/11_documentstore_create.png)

2. Tilføj en Document Loader node, som skal bruges til at indlæse dokumenter i din Document Store

   ![Document Loader Setup](screendumps/12_documentstore_loader.png)

3. Konfigurer PDF-behandling ved at forbinde de relevante nodes og indstillinger

   ![Process PDF Setup](screendumps/13_documentstore_process_pdf.png)

## Del 2: Konfigurer Document Store Actions

1. Tilføj ekstra actions for at kunne upserte dokumenter i din Document Store

   ![Document Store Extra Actions](screendumps/14_documentstore_ekstra_actionsupsert.png)

2. Konfigurer upsert-funktionaliteten for at gemme og opdatere dokumenter

   ![Document Store Upsert](screendumps/15_documentstore_upsert.png)
