# PROGETTO-FINALE-PERSONALE
Progetto Personale DB scacchi
Concetto
Il progetto consiste nell’utilizzo di un grande dataset inerente il mondo della scacchistica .
L’idea è di sfruttare ed utilizzare una semplice architettura a Medaglioni diviso in 3 layer (Bronzo ,Argento,Oro).
Il database così strutturato vorrà essere arricchito, formattato e standardizzato in maniera semplice(Argento) per esser poi sfruttato dal layer finale(Oro ) per compiere insight sui dati stabiliti in precedenza oppure in opera in corso ed eventualmente arricchire con l’inserimento di dati aggiuntivi e mantenendo i dati grezzi (Bronzo) in modo tale da avere un backup e/o utilizzo esterno da altre figure tecniche (Data Engineers).
Si procederà per la strutturazione degli stessi layer,per poi effettuare la fase di Cleaning e/o altre tipologie di Data Transformation con Python/Pandas.
Salvato poi il file, si procederà con la creazione degli schemas su MYSQL e procedendo successivamente con la creazione di eventuali “Trigger “e “Stored Procedure” per la manutenzione automatica dei dati e caricamento delle tabelle tramite funzioni LOAD DATA INFILE .
Nella parte finale  si procederà con la visualizzazione degli stessi tramite PowerBi con report ad hoc semplici e che possano catturare l’attenzione dell’utente finale facendo attenzione a non innalzare il tasso di difficoltà dei dati stessi sia in ottica Qualitativa che Quantitativa

NB 
1)LA CARTELLA CON TUTTI I FILES ELABORATI,ESSENDO TROPPO GRANDE DA CARICARE SU GITHUB VERRA' CARICATA SUL GOOGLE DRIVE PERSONALE E SARA' POSSIBILE ACCEDERVI AL SEGUENTE LINK: https://drive.google.com/drive/u/0/folders/1FSSqYH8PeZsGBbFUN9x0gZsCIjJF39ew
2)IL DB GOLD ESSENDO DERIVATO DAL SILVER E' STATO EVITATO DI ESSER CARICATO PER NON APPESANTIRE LA CARTELLA,ESSENDO I DB PRATICAMENTE IDENTICI(IL DB GOLD E' UGUALE AL DB SILVER POICHE' VIENE UTILIZZATA COME TABELLA FACTS CENTRALE IN UN DIAGRAMMA STAR SCHEMA)
