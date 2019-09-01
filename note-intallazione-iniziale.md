Note di installazione iniziale
==============================

* creare cartella progetto
* git init
* git clone … repostory utente
* git remote add upstream … repository adempiere
* importare progetto git locale in Eclipse
* settare java 8 per la compilazione
* lanciare una build.xml nella cartella principale
* Verificare se lanciare il build.xml con target runSetup oppure lanciare Adempiere-setup.launch nella cartella Install
* N.B. verificare server database (localhost?), verificare system password (postgres). Verificare che postgres sia installato e avviato, con utente postgres e password impostata e accesso via client abilitato nel file di configurazione pg_hba.conf di Postgres.
* lanciare Adempiere*all.launch nella cartella base, o con il pulsante di Run scegliendo opzione Adempiere-all