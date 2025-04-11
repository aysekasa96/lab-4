# lab-4

# Lake Database Maken met Azure Synapse Analytics

## Beschrijving
Dit project demonstreert hoe je een **Lake Database** kunt maken met behulp van **Azure Synapse Analytics**. Het combineert de flexibiliteit van bestandsopslag in een data lake met de gestructureerde schema's en SQL-queryfunctionaliteiten van een relationele database.

Een **Lake Database** voegt een relationeel schema toe aan bestanden in een data lake, waardoor opslag wordt losgekoppeld van rekenkracht. Dit biedt een krachtige oplossing voor data-analyse en opslag.

## Vereisten
1. Een **Azure-abonnement** met admin-rechten.
2. Toegang tot **Azure Synapse Analytics** en een gekoppelde **Azure Data Lake Storage Gen2**.
3. PowerShell voor het uitvoeren van scripts.

## Stappen
1. **Azure Synapse Workspace maken:**
   - Configureer een Synapse-werkruimte en zorg voor toegang tot de data lake-opslag.

2. **Lake Database Ontwerpen:**
   - Maak een database genaamd `RetailDB`.
   - Voeg tabellen toe met gestructureerde schema's.

3. **Data Laden:**
   - Upload CSV-bestanden naar mappen in de data lake en koppel ze aan database-tabellen.

4. **SQL Queries Uitvoeren:**
   - Gebruik serverless SQL-pools om data te analyseren en te combineren.

5. **Opschonen:**
   - Verwijder gebruikte Azure-resources om kosten te voorkomen.

## Resultaat
Een werkende Lake Database die schaalbare opslag combineert met de kracht van SQL-query's voor data-analyse.

## Credits
Gebaseerd op de officiële Microsoft Learning Labs voor DP-203: Azure Data Engineer Associate.
