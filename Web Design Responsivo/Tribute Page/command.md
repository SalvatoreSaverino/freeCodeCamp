Crea una Tribute Page
Obiettivo: crea un'app funzionalmente simile a https://tribute-page.freecodecamp.rocks

User story:

La tua Tribute Page dovrebbe avere un elemento main con un corrispondente id di main, che contiene tutti gli altri elementi
Dovresti vedere un elemento con un attributo id del valore di title, che contiene una stringa (cioè del testo) che descrive il soggetto della pagina tributo (per esempio "Dr. Normal Borlaug")
Dovresti vedere o un elemento figure o un elemento div con un attributo id del valore di img-div
Dentro l'elemento #img-div, dovresti vedere un elemento img con un corrispondente id="image"
Dentro l'elemento #img-div, dovresti vedere un elemento con un corrispondente attributo id="img-caption" che contiene del testo che descrive l'immagine mostrata in #img-div
Dovresti vedere un elemento con un corrispondente attributo id="tribute-info" contenente del testo che descrive il soggetto della pagina tributo
Dovresti vedere un elemento a con un corrispondente attributo id="tribute-link" che linka a un sito esterno che contiene informazioni aggiuntive sul soggetto della pagina tributo. Suggerimento: Devi dare al tuo elemento un attributo target e impostarlo su _blank per far si che il link si apra in una scheda nuova
Il tuo elemento #image dovrebbe usare le proprietà max-width e height per ridimensionarsi in maniera reattiva, a seconda della larghezza dell'elemento genitore senza eccedere la dimensione originale
Il tuo elemento img dovrebbe essere centrato dentro il suo elemento genitore
Soddisfa le user story e passa tutti i test qui sotto per completare questo progetto. Usa il tuo stile personale. Buon divertimento!

Nota: Assicurati di aggiungere <link rel="stylesheet" href="styles.css"> nel tuo HTML per linkare il tuo foglio di stile e applicare il tuo CSS

Test
Attendi:Dovrebbe esserci un elemento main con un id del valore di main.
Attendi:Gli elementi #img-div, #image, #img-caption, #tribute-info e #tribute-link dovrebbero essere tutti discendenti di #main.
Attendi:Dovresti avere un elemento con un attributo id del valore di title.
Attendi:Il tuo elemento #title non dovrebbe essere vuoto.
Attendi:Dovrebbe esserci o un elemento figure o un elemento div con un attributo id del valore di img-div.
Attendi:Dovrebbe esserci un elemento img con un id del valore di image.
Attendi:Il tuo elemento #image dovrebbe essere un discendente di #img-div.
Attendi:Dovrebbe esserci o un elemento figcaption o un elemento div con un attributo id di img-caption.
Attendi:L'elemento #img-caption dovrebbe essere un discendente di #img-div.
Attendi:L'elemento #img-caption non dovrebbe essere vuoto.
Attendi:Dovrevve esserci un elemento con un attributo id del valore di tribute-info.
Attendi:L'elemento #tribute-info non dovrebbe essere vuoto.
Attendi:Dovrebbe esserci un elemento a con un id del valore di tribute-link.
Attendi:L'elemento #tribute-link dovrebbe avere un attributo href con un valore.
Attendi:L'elemento #tribute-link dovrebbe avere un attributo target con il valore _blank.
Attendi:L'elemento img dovrebbe avere una proprietà display con il valore block.
Attendi:#image dovrebbe avere una proprietà max-width del 100%.
Attendi:#image dovrebbe avere una proprietà height con il valore auto.
Attendi:L'elemento #image dovrebbe essere centrato dentro l'elemento genitore.
