# Archivi-fotografici

Il repository contiene i tracciati e i vocabolari in uso presso ICCD per la descrizione di tipo inventariale degli archivi fotografici.
I tracciati che seguono sono stati elaborati dall’Istituto Centrale per il Catalogo e la Documentazione per la descrizione di tipo speditivo dei propri archivi fotografici e sono stati implementati all’interno del sistema descrittivo XDAMS in uso presso l’Istituto.

Le entità prese in considerazione (complessi archivistici, album fotografici, singole fotografie, soggetti produttori, soggetti conservatori) sono quelle che tipicamente caratterizzano i sistemi descrittivi di tipo archivistico.

I tracciati fanno riferimento a schemi XML standard di ambito archivistico utilizzati a livello internazionale e nazionale: 
- per i **complessi archivistici** (fondo, serie, album fotografici, unità archivistiche) e per le singole **fotografie** si fa riferimento allo standard <a href="https://www.loc.gov/ead/">EAD3</a>  emanato e gestito dalla Library of Congress
- per i **soggetti produttori** e per gli autori delle fotografie  si fa riferimento allo standard <a href="https://eac.staatsbibliothek-berlin.de/">EAC-CPF</a> elaborato dalla Society of American Archivists
- per la descrizione dei **soggetti conservatori** degli archivi fotografici si fa riferimento al tracciato <a href="https://www.icar.beniculturali.it/fileadmin/risorse/Accordi_e_convenzioni/Interoperabilita_sistemi_archivistici_tracciati_ICAR_20180925.pdf">SCONS2</a> del CAT-SAN elaborato dall’ICAR.
 
Gli schemi dichiarati nel documento e la relativa documentazione sono disponibili in rete. Nel repository ICCD si fornisce il subset di elementi descrittivi effettivamente utilizzati. Il subset è stato definito nel corso degli anni sulla base dell’esperienza acquisita dall’Istituto Centrale per il Catalogo e la Documentazione nella gestione dei propri fondi fotografici.

Per quanto riguarda il subset degli elementi identificati per la descrizione delle fotografie, il tracciato descrittivo espresso secondo uno standard di tipo archivistico (EAD 3) è totalmente  compatibile con la scheda F  di cui vengono anche riutilizzati  i vocabolari già formalizzati, come quelli di materie e tecnica, datazioni, alterazione e deterioramenti, ecc.

Nel repository sono conservati:

1) <b>ICCD-Fotografia_tracciato_Regole.xslx</b> - Il data model in uso presso ICCD in formato tabellare, con un riferimento nominale ai campi della scheda F e con una apposita colonna dedicata all'esplicitazione delle regole da seguire per la corretta compilazione dei record relativi alle fotografie. In giallo sono indicati i campi la cui compilazione è raccomandata per una corretta descrizione dei fototipi d'archivio

2) <b>Dizionari_di_campo.xslx</b> -  Lista dei vocabolari chiusi per la corretta compilazione dei campi: colore, definizione, seolo, categoria, alterazioni

3) <b>Tecniche.skos</b> - Vocabolario controllato relativo alle tecniche fotografiche

4) Una cartella di <b>esempi</b> compilati sulla base dei tracciati in uso
