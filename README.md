# AnalisiCompetitorCalzature_Python_Team

**IT**  
# **Analisi Competitiva VANS vs CONVERSE**  
*(Web Scraping e Data Analysis - Progetto di gruppo)*  

Il progetto **in team** ha riguardato l'analisi comparativa del mercato calzaturiero tra i brand VANS e CONVERSE, due marchi iconici del settore sneakers. Attraverso tecniche di web scraping, sono stati raccolti dati da siti rivenditori per analizzare posizionamento, strategie di prodotto e differenze competitive tra i due brand.  
Durante la fase di raccolta dati, si è utilizzato web scraping per estrarre informazioni sui prodotti, applicando filtri per genere (uomo/donna), marca e categorie specifiche. Le pagine HTML sono state salvate localmente per garantire stabilità nell'estrazione dei dati, successivamente processati in CSV e uniti tramite concatenazione per creare il dataset finale.  
Nella fase di Data Engineering & Analysis, è stata effettuata una pulizia approfondita del dataset: conversione dei prezzi da object a float, estrazione di modello, categoria e colore dalla colonna nome_prodotto tramite split pattern, gestione dei prodotti unisex per evitare duplicazioni e trattamento dei valori mancanti nella colonna colore.  
Il risultato è un'analisi completa che evidenzia le diverse strategie dei brand: VANS focalizzata sui modelli diversificati, CONVERSE sulla varietà di colori. Sono stati creati grafici interattivi per visualizzare differenze di posizionamento, quantità, prezzi e segmentazione per genere, fornendo insights strategici sul mercato sneakers.  

**Tecnologie utilizzate:**  

- 🌐 **Web Scraping** (Raccolta dati automatizzata)
- 🐍 **Python** (Pandas, Matplotlib, OS)
- 📊 **Data Analysis** (Pulizia dati, visualizzazioni)

**EN**  
# **VANS vs CONVERSE Competitive Analysis**  
*(Web Scraping and Data Analysis | Team Project)*  

This team project involved comparative analysis of the footwear market between VANS and CONVERSE brands, two iconic players in the sneakers sector. Through web scraping techniques, we collected data from retailer websites to analyze positioning, product strategies, and competitive differences between the two brands.

**Data Preparation Highlights**  
  - Web scraping implementation with filters for:
    - Gender categories (men/women)
    - Brand-specific data extraction
    - Product category segmentation
  - HTML pages saved locally for extraction stability
  - Data processing into CSV format with concatenation for final dataset creation

**Key Features**
  - Comprehensive data cleaning process:
    - Price conversion from object to float format
    - Model, category, and color extraction from product names using split patterns
    - Unisex product handling to avoid duplications
    - Missing value treatment in color columns
  - Interactive visualizations for:
    - Brand positioning differences
    - Quantity and pricing analysis
    - Gender segmentation insights

**Insights Uncovered**  
The analysis reveals distinct brand strategies: VANS focuses on diversified models while CONVERSE emphasizes color variety. Interactive charts showcase positioning differences, quantities, prices, and gender segmentation, providing strategic insights into the sneakers market.  

**Technical Stack:**  

- 🌐 **Web Scraping** (Automated data collection)
- 🐍 **Python** (Pandas, Matplotlib, OS)
- 📊 **Data Analysis** (Data cleaning, visualizations)
