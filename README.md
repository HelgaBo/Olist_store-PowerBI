# 📦 Olist Store – Sales & Customer Analysis (2016–2018)

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

### 📆 Vendite mensili
screen1...
- Numero ordini e ricavi totali per mese  
- Analisi per stato ordine: consegnato, spedito, cancellato, ecc.  
- Segmentazione temporale per anno (2016, 2017, 2018)

### 🌎 Analisi geografica

- Mappa con distribuzione ordini per stato brasiliano  
- Stati con più ordini, più ricavi, maggiori problemi

### 📈 Crescita YoY (Year-over-Year)

- Confronto mese su mese tra anni (es. Gen 2017 vs Gen 2016)  
- Crescita % ordini e ricavi

### 💳 Analisi pagamento

- Metodi di pagamento più usati  
- Importo medio per tipo di pagamento

### ⭐ NPS

-- 

## 📁 File

- `Olist_Sales_Report.pbix` – File Power BI con modello e report completo  
- `Olist_Raw_Data.xlsx` – Versione ridotta e pulita dei dati grezzi  
- `README.md` – Descrizione del progetto

---

## 📌 Tecnologie

- Power BI Desktop  
- DAX per misure personalizzate  
- Power Query per ETL e riduzione tabelle  
- Star schema modeling  
- Time Intelligence

---

## 📊 Screenshot

*(Aggiungi 2–3 immagini del report: overview, mappa, review analysis...)*

---

## 📥 Fonte dati

- [Kaggle – Olist Brazilian E-Commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
