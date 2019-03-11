# Biblioteche e bene comune digitale

Dall’11 al 16 marzo 2019 la Presidenza del Consiglio dei Ministri, [Dipartimento della Funzione Pubblica](http://www.funzionepubblica.gov.it/) organizza a livello nazionale la “[Settimana dell’Amministrazione aperta](http://open.gov.it/saa/)” con l’obiettivo di promuovere la cultura e la pratica della trasparenza, della partecipazione e della accountability nelle amministrazioni pubbliche e nella società e accrescere la fiducia dei cittadini nelle istituzioni.
Per il Comune di Palermo ha aderito la **[Biblioteca Comunale](https://docs.google.com/document/d/1FOwSyu_n5VtIaKQERatrWk6mz5RkLr9DqXR0G1FHRmA/edit?usp=sharing)** presentando il progetto **Teca digitale**.

Il progetto nasce a fine 2017, quando sono state pubblicate su **[Flickr](https://www.flickr.com/photos/biblioteca-comunale-palermo/albums)** le prime foto della Collezione fotografica di **Enrico Di Benedetto**, scattate a **Palermo** tra il **XIX** ed il **XX** secolo, un progetto permette a noi cittadini di fare **[un meraviglioso viaggio nel tempo](http://opendatasicilia.it/2019/03/11/palermo-un-meraviglioso-viaggio-nel-tempo-grazie-alla-biblioteca-comunale-di-palermo/)** (cit.)

Ad oggi sono state pubblicate più di 800 foto, ad ognuna è associato a un “corredo informativo” costituito da: titolo, posizione geografica, gallerie di appartenenza, tag, licenza e metadati (non sono dati presenti in tutte le foto, ma nella grandissima parte), tutte pubblicate con una **licenza aperta [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.it) che ne consente il riuso**

Grazie all'uso della licenza [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.it) e al *web scraping* [@aborruso](https://twitter.com/aborruso), partendo dagli album di [Flickr](https://www.flickr.com/photos/biblioteca-comunale-palermo/albums) ha ottenuto i dati grezzi ottimi per un **riuso**. <br>
[Qui](https://github.com/opendatasicilia/flickr-biblioteca-comunale-palermo/tree/master/report) il report con i dati

## Il riuso dei dati

Visto che tra le informazioni delle foto c'è la posizione geografica, come prima cosa abbiamo localizzato le foto sul territorio comunale di Palermo, per farlo è stato utilizzato il software [QGIS](https://www.qgis.org/it/site/)

![](/img/qgis.png)

(Qui descizione di Totò)

## La mappa

Sempre con [QGIS](https://www.qgis.org/it/site/) abbiamo ottenuto i file *[geojson](https://it.wikipedia.org/wiki/GeoJSON)* che ci hanno permesso di costruire una mappa dinamica su **[uMap](http://u.osmfr.org/m/301213/)** 

![](/img/palermohub_01.jpg)

![](/img/palermohub_02.jpg)



