Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario
Come fatto stamattina in classe potete fare un file di testo e scrivre la struttura li.

#CONCESSIONARIO BRUM BRUM 

##AUTO:

◉ id | INT - primary key, auto increment, unique, not null
◉ targa(bk000mn) | CHAR(7) -unique, not null
◉ marca (audi,bmw,porsche) | VARCHAR(30) - notnull 
◉ modello (a1,serie 3,cayman) | VARCHAR(30) - notnull
◉ versione (sport,gti,r) | VARCHAR(30) - null
◉ carrozzeria (coupè,berlina,citycar) | VARCHAR(30) - notnull
◉ anno (2010,2009) | YEAR - notnull
◉ kilometri percorsi(180.000,90.000) | MEDIUMINT - notnull
◉ carburante (elettrica,ibrida,benzina) | VARCHAR(30) - notnull 
◉ potenza(cv) | (211,90,400) | SMALLINT - notnull
◉ colore (nera,verde,blu) | VARCHAR(30) - null
◉ cambio (automatico,manuale) | VARCHAR(10) - notnull
◉ n.posti (2,4,5) | TINYINT - notnull
◉ n.porte (3,5) | TINYINT - notnull
◉ trazione (posteriore,anteriore,4x4) | VARCHAR(20) - notnull
◉ classe emissioni (classe1,classe4) | VARCHAR(30) - notnull
◉ per neopatentati (boolean) | VARCHAR(5)|TINYINT(0,1) - null
◉ stato dell'usato (buono,ottimo,usurato) |VARCHAR(30) -null
◉ paese di provenienza (italia,germania,japan) | VARCHAR(50) - null
◉ stato (in vendita,noleggio) | VARCHAR(20) - null, default(in vendita)
◉ immagine vetrina (/audiSport.jpg) | VARCHAR(30) -null
◉ prezzo (10.800€,22.000€) | VARCHAR(20) | - notnull
◉ note (graffio sulla portiera desta) | TEXT -null

indice:
◉ chiave (esempio) | TIPO DI DATO - attributi
