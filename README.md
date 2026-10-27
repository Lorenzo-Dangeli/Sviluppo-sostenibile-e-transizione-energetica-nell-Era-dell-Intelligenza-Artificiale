# AI Energy Impact & Global Grid Pressure: Analisi Strategica per una ONG

## 🌍 Panoramica del Progetto
Questo progetto nasce con l'obiettivo di analizzare, quantificare e valutare l'**impatto dei data center dedicati all'intelligenza artificiale sulle reti energetiche globali**. 

Attraverso un approccio data-driven, il lavoro è stato concepito per fornire a un'organizzazione non governativa (ONG) impegnata nella sostenibilità ambientale un quadro analitico rigoroso e **raccomandazioni strategiche azionabili**, superando una narrazione puramente allarmistica e puntando su modelli di transizione energetica di successo.

---

## 🛠️ Metodologia e Stack Tecnologico

Il flusso di lavoro si sviluppa in due fasi principali, combinando l'estrazione strutturata dei dati con la modellazione e visualizzazione avanzata:

1. **Data Engineering ed Estrazione (SQL):**
   * Interrogazione ed elaborazione di dataset globali primari (tra cui *Epoch AI Data Centers Dataset* e *Global Data on Sustainable Energy*) per aggregare i dati relativi ai cluster di calcolo, alla potenza installata (MW) e al mix energetico nazionale.
   * Normalizzazione delle serie storiche (2000–2020) e calcolo di metriche chiave (KPI) per isolare l'incidenza dei consumi tecnologici rispetto alla produzione elettrica totale e alla ricchezza nazionale (PIL).

2. **Modellazione, Pivot e Visualizzazione (Microsoft Excel / Google Sheets):**
   * Elaborazione tramite tabelle pivot e grafici dinamici per confrontare l'evoluzione ventennale del mix energetico (fossili vs. rinnovabili).
   * Normalizzazione della pressione infrastrutturale tramite l'indicatore di **intensità energetica ($TWh / Mld \$ PIL$)** e calcolo dell'impatto percentuale dei data center sulle reti nazionali (es. il carico critico registrato negli Stati Uniti e in Malesia).

---

## 📊 Principali KPI e Metriche Analizzate
* **Impatto Data Center (%):** Rapporto percentuale tra il consumo energetico stimato dei cluster AI e la produzione elettrica totale del Paese.
* **Intensità Energetica sul PIL:** Misura della pressione infrastrutturale normalizzata rispetto alla ricchezza nazionale per identificare economie ad alta vulnerabilità.
* **Trend Storico 2000–2020:** Analisi della transizione energetica globale, con un focus sul benchmark di successo del **Regno Unito** (passato dal 3% a oltre il 51% di energia rinnovabile in vent'anni) come modello operativo per le economie avanzate.

---

## 💡 Implicazioni e Raccomandazioni per la ONG
Il report finale tradotto in presentazione evidenzia come la crescita esponenziale dell'IA richieda un cambio di passo nelle politiche di monitoraggio ambientale:
* **Monitoraggio dei Rischi:** Identificazione dei mercati a maggiore densità infrastrutturale e dipendenza fossile (es. Stati Uniti e specifici hub asiatici) dove l'espansione dei data center rischia di aggravare le emissioni.
* **Adozione di Standard Virtuosi:** Promozione del modello britannico come benchmark di riferimento per sincronizzare la transizione digitale con la decarbonizzazione della rete elettrica.

---

## 📁 Struttura del Repository
* `data/`: Dataset originali e tabelle di output elaborate.
* `sql/`: Query e script utilizzati per l'estrazione e l'aggregazione dei dati.
* `presentation/`: Report visivo e slide di presentazione orientate agli stakeholder istituzionali e ONG.
