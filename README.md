# Archivi-fotografici
Il repository contiene i tracciati e i vocabolari in uso presso ICCD per la descrizione di tipo inventariale degli archivi fotografici.

Il tracciato per la descrizione delle fotografie è una selezione dei campi derivanti dalla <a href="http://www.iccd.beniculturali.it/it/ricercanormative/62/f-fotografia-4_00">scheda F</a>. La selezione è stata disegnata sui campi comuni provenienti dagli inventari digitali dei vari settori dell'istituto sia per la normalizzazione degli inventari sia per disporre di una descrizione speditiva ma codificata che descrivesse le centinaia di migliaia di fotografie ancora non consultabili on line. Per fare questo si è portato ad un minimo comune denominatore tutte le varie tipologie di tracciati. Si sono poi analizzate tutte le schede F presenti nel <a href="http://www.iccd.beniculturali.it/it/sigec-web">SIGECweb</a>e si sono poi riutilizzati i vocabolari già formalizzati in scheda F, come quelli di materie e tecnica, datazioni, alterazione e deterioramenti, ecc. L'idea è stata quella di semplificare molto la scheda F per creare una banca dati "di base" che servisse poi ad una eventuale importazione nel <a href="https://www.catalogo.beniculturali.it/">Catalogo generale dei beni culturali</a>.

Nel repository sono conservati:
1) <b>schema_XSD_foto.xsd</b> - Il data model XSD in uso presso ICCD - basato su un subset di elementi di EAD (Encoded Archival Description) - e relativo alle singole fotografie. Per i livelli superiori di descrizione degli archivi fotografici (Fondo, Serie, Sottoserie, ALbum, Unità archivistica) e per la descrizione dei soggetti conservatori e dei soggetti produttori, l'ICCD utilizza il data model rilasciato da ICAR relativamente ai <a href="https://www.icar.beniculturali.it/fileadmin/risorse/Accordi_e_convenzioni/Interoperabilita_sistemi_archivistici_tracciati_ICAR_20180925.pdf">tracciati ICAR-IMPORT di Interoperabilità</a> fra sistemi archivistici (EAD3, EAC-CPF SCONS2)

2) <b>ICCD-Fotografia_tracciato_Regole.xslx</b> - Il data model in uso presso ICCD in formato tabellare, con un riferimento nominale ai campi della scheda F e con una apposita colonna dedicata all'esplicitazione delle regole da seguire per la corretta compilazione dei record relativi alle fotografie. In giallo sono indicati i campi la cui compilazione è raccomandata per una corretta descrizione dei fototipi d'archivio

3) <b>Dizionari_di_campo.xslx</b> -  Lista dei vocabolari chiusi per la corretta compilazione dei campi: colore, definizione, seolo, categoria, alterazioni

4) <b>Tecniche.skos</b> - Vocabolario controllato relativo alle tecniche fotografiche

5) Una cartella di <b>esempi</b> compilati
