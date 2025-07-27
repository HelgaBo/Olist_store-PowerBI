# Olist Store – Sales & Customer Analysis (2016–2018)

Questo progetto presenta un'analisi completa del dataset pubblico [Olist Store](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), una piattaforma di e-commerce brasiliana attiva in tutto il paese.

---

## Obiettivo

Analizzare le performance di vendita, la soddisfazione dei clienti e la distribuzione geografica degli ordini tra il 2016 e il 2018, tramite un report interattivo in **Power BI**.

Il report è progettato per evidenziare:

- Trend di vendita e crescita nel tempo  
- Comportamento degli utenti e livello di soddisfazione  
- Analisi dei problemi (ordini cancellati, tempi lunghi di consegna)  
- Differenze regionali nella domanda e nella performance commerciale  
- Performance dei venditori  
- Insight azionabili tramite visual storytelling

---

## Architettura del Modello Dati

Il modello è stato costruito con approccio **star schema**, semplificando e riducendo il dataset originale per migliorare prestazioni e chiarezza:

### Tabelle principali:

- **Orders** – Ordini dei clienti con timestamp, stato, ID cliente  
- **Order Items** – Dettaglio prodotti per ordine, con prezzo e venditore  
- **Customers** – Informazioni su clienti e geolocalizzazione  
- **Sellers** – Venditori e loro sede  
- **Products** – Informazioni su prodotti e categorie  
- **Payments** – Dettaglio metodi di pagamento e importi  
- **Reviews** – Valutazioni e commenti dei clienti  
- **Calendar** – Tabella date con calcoli per analisi temporale

---

## Pagini

### KPI & Andamento Vendite

- Indicatori chiave: ordini, ricavi, AOV YoY  
- Confronto mensile rispetto all’anno precedente  
- Ripartizione degli ordini consegnati per categoria
<img width="1650" height="906" alt="image" src="https://github.com/user-attachments/assets/abf6212f-bcdb-4960-95b0-2de7daedee4e" />

### Analisi pagamento

- Metodi di pagamento più usati  
- Rateizzazione con carta di credito (da 1 a 10)  
- Volume mensile dei pagamenti
<img width="1648" height="928" alt="image" src="https://github.com/user-attachments/assets/76cf5e1f-89c0-43c5-adec-df0eabb6bc65" />

### Analisi NPS

- NPS medio dei clienti  
- % di promoter, passivi e detrattori  
- NPS per stato e per categoria

<img width="1625" height="932" alt="image" src="https://github.com/user-attachments/assets/11e91586-46d5-46fd-b0eb-8fd36344c9b1" />

### Analisi geografica

- Ricavi per stato e confronto YoY  
- Distribuzione ordini per stato e stato ordine  
- Differenze di categorie vendute tra regioni

<img width="1664" height="925" alt="image" src="https://github.com/user-attachments/assets/2d2e7788-d6c2-49ce-8dc3-0fa5a5550f28" />


## Files

- `Olist_Sales_Report.pbix` – File Power BI con modello e report completo  
- `Olist_Raw_Data.xlsx` – Versione ridotta e pulita dei dati grezzi  
- `README.md` – Descrizione del progetto

---

## Fonte dati

- [Kaggle – Olist Brazilian E-Commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
