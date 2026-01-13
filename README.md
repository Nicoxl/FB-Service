# 🛠️ FB Service - Web App 

Benvenuti nel repository ufficiale di **FB Service**, la piattaforma digitale dedicata ai servizi di assistenza e riparazione elettrodomestici nella Valle dell'Agno (VI).

🔗 **Sito Live:** [https://fbserviceassistenza.web.app/](https://fbserviceassistenza.web.app/)

## 📝 Descrizione del Progetto
Questa Web App è stata progettata per fornire una presenza online professionale all'attività FB Service. Il sito facilita l'interazione tra i clienti e il tecnico, mettendo in chiaro i servizi offerti e garantendo la massima trasparenza tramite la documentazione legale integrata.

## ✨ Funzionalità Principali

* **🖥️ Hub Assistenza**: Catalogo delle tipologie di elettrodomestici supportati (lavatrici, lavastoviglie, forni, ecc.).
* **📞 Centro Contatti**: Sistema di contatto diretto con integrazione di Google Maps per visualizzare l'area operativa nella Valle dell'Agno.
* **⚖️ Compliance Legale**: Pagine dedicate a **Privacy Policy**, **Cookie Policy** e **Termini di Servizio** in piena conformità con il GDPR.
* **📱 Design Responsive**: Interfaccia ottimizzata per una navigazione fluida sia da desktop che da dispositivi mobile.

## 🛠️ Stack Tecnologico

* **Hosting**: [Firebase Hosting](https://firebase.google.com/docs/hosting) (Infrastruttura Google per massima velocità e affidabilità).
* **Frontend**: HTML5, CSS3 moderno e JavaScript.
* **CI/CD**: GitHub Actions (Distribuzione automatica ad ogni aggiornamento del codice).
* **Gestione Versioni**: Git & GitHub per il controllo del codice sorgente.

## 🚀 Workflow di Sviluppo (Deploy Automatico)

Il progetto utilizza una pipeline di **Continuous Deployment**. Non è necessario il deploy manuale tramite CLI:

1.  Effettua le modifiche ai file in locale.
2.  Esegui il `push` sul ramo `main`:
    ```bash
    git add .
    git commit -m "Descrizione della modifica"
    git push origin main
    ```
3.  **GitHub Actions** rileverà il cambiamento e aggiornerà automaticamente il sito live.

## 📁 Struttura del Progetto
```text
├── .github/workflows/  # Configurazioni per il Deploy automatico
├── public/             # File sorgente del sito (HTML, CSS, JS)
├── firebase.json       # Configurazione Firebase Hosting
├── package.json        # Gestione dipendenze e script di build
└── README.md           # Documentazione del progetto
