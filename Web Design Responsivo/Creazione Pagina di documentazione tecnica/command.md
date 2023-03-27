Crea una pagina di documentazione tecnica
Obiettivo: crea un'app funzionalmente simile a https://technical-documentation-page.freecodecamp.rocks

User story:

Devi avere un elemento main con un corrispondente id="main-doc", che contiene il contenuto principale della pagina (technical documentation)
Dentro l'elemento #main-doc, puoi aggiungere svariati elementi section, ognuno con una classe di valore main-section. Dovrebbero essercene almeno cinque
Il primo elemento dentro ogni .main-section dovrebbe essere un elemento header, che contiene testo che descrive l'argomento della sezione.
Ogni elemento section con la classe main-section dovrebbe avere un id che corrisponde al testo di ogni elemento header al suo interno. Qualsiasi spazio deve essere sostituito con un underscore (ad esempio, la sezione che contiene l'intestazione "JavaScript and Java" dovrebbe avere un corrispondente id="JavaScript_and_Java")
Gli elementi .main-section dovrebbero contenere almeno dieci elementi p in totale (non ciascuno)
Gli elementi .main-section dovrebbero contenere almeno cinque elementi code in totale (non ciascuno)
Gli elementi .main-section dovrebbero contenere almeno cinque elementi li in totale (non ciascuno)
Dovresti aggiungere un elemento nav con un corrispondente id="navbar"
L'elemento navbar dovrebbe contenere un elemento header con del testo che descrive l'argomento della documentazione tecnica
In aggiunta, l'elemento navbar dovrebbe contenere dei link (elementi a) con la classe nav-link. Dovrebbe essercene uno per ogni elemento di classe main-section
L'elemento header dentro #navbar deve trovarsi prima di qualsiasi link (elemento a) nella barra di navigazione
Ogni elemento con la classe nav-link dovrebbe contenere del testo corrispondente al testo dell'elemento header dentro ogni elemento section (per esempio, se c'è una sezione/intestazione "Hello world", la barra di navigazione dovrebbe avere un elemento che contiene il testo "Hello world")
Quando clicchi su un elemento navbar, la pagina dovrebbe andare alla sezione corrispondente dell'elemento #main-doc (per esempio se clicchi su un elemento .nav-link che contiene il testo "Hello world", la pagina va fino all'elemento section che ha quell'id, e contiene l'intestazione corrispondente)
Su dispositivi di dimensione regolare (laptop, desktop), l'elemento con id="navbar" dovrebbe essere sempre nella parte sinistra dello schermo e dovrebbe essere sempre visibile all'utente
La tua documentazione tecnica dovrebbe avere almeno un media query
Soddisfa le user story e passa tutti i test qui sotto per completare questo progetto. Usa il tuo stile personale. Buon divertimento!

Nota: Assicurati di aggiungere <link rel="stylesheet" href="styles.css"> nell'HTML per linkare il foglio di stile e applicare il CSS

Test
Attendi:Dovresti avere un elemento main con un id di main-doc.
Attendi:Dovresti avere almeno cinque elementi section con la classe main-section.
Attendi:Tutti gli elementi .main-section dovrebbero essere elementi section.
Attendi:Dovrebbero esserci almeno cinque elementi .main-section discendenti di #main-doc.
Attendi:Il primo figlio di ogni elemento .main-section dovrebbe essere un elemento header.
Attendi:Nessuno degli elementi header dovrebbe essere vuoto.
Attendi:Tutti gli elementi .main-section dovrebbero avere un id.
Attendi:Ogni elemento .main-section dovrebbe avere un id che corrisponde con il testo del primo figlio, e ogni spazio nel testo del figlio deve essere sostituito con dei trattini bassi (_).
Attendi:Dovresti avere almeno 10 elementi p (in totale) dentro gli elementi .main-section.
Attendi:Dovresti avere almeno cinque elementi code che sono discendenti degli elementi .main-section.
Attendi:Dovrebbero esserci almeno cinque elementi li che sono discendenti degli elementi .main-section.
Attendi:Dovrebbe esserci un elemento nav con un attributo id con il valore navbar.
Attendi:L'elemento #navbar dovrebbe avere un solo elemento header al suo interno.
Attendi:Dovrebbe esserci almeno un elemento a con la classe nav-link.
Attendi:Tutti gli elementi .nav-link dovrebbero essere elementi di ancoraggio (a).
Attendi:Tutti gli elementi .nav-link dovrebbero essere dentro #navbar.
Attendi:Dovresti avere lo stesso numero di elementi .nav-link e di elementi .main-section.
Attendi:L'elemento header dentro #navbar dovrebbe trovarsi prima di qualsiasi link (elemento a) all'interno di #navbar.
Attendi:Ogni elemento .nav-link dovrebbe avere del testo corrispondente all'elemento header del relativo elemento section (per esempio, se hai una sezione/intestazione con "Hello world", l'elemento #navbar dovrebbe avere un elemento .nav-link con il testo "Hello world").
Attendi:Ogni elemento .nav-link dovrebbe avere un attributo href che linka all'elemento .main-section corrispondente (per esempio, se clicchi su un elemento .nav-link che contiene il testo "Hello world", la pagina va all'elemento section con quell'id).
Attendi:L'elemento #navbar dovrebbe sempre essere sul bordo sinistro della finestra.
Attendi:Il progetto di documentazione tecnica dovrebbe avere almeno un media query.
