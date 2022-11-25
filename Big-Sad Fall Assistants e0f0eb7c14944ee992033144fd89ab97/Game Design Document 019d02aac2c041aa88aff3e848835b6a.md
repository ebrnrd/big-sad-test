# Game Design Document

# Overview

Big Sad Fall Assistants è un gioco politico ma non lo è. Racconta le vicende di due robot che in un futuro distopico sono impiegati nel triste lavoro del far rimbalzare (ovviamente tramite un tappeto elastico che tendono tra di loro) degli operai che hanno deciso che la vita da lavoratore schiavizzato non faceva più per loro. Il giocatore controlla i due robot separatamente, tramite tastiera o touchscreen del telefono. I robot come detto prima hanno in mano un tappeto elastico che li tiene legati tra loro e che gli serve per spedire gli umani suicidi all’interno delle finestre dei palazzi che troviamo sui lati dello schermo.

BSFA presenta una componente narrativa che si sviluppa nel corso di 5 livelli e che si conclude con la battaglia contro il boss finale. Questo sviluppo svela sempre più dettagli del mondo in cui si trova il giocatore, la narrativa non sarà invasiva e frontale ma sarà tra le righe, guidata dai dettagli che popolano le scene.

# Plot & Setting

Il nostro compito è comandare i due robot che si occupano di salvare i lavoratori umani (?) che si lanciano dalle finestre perché non sopportano più di lavorare così. Come? Facendoli rimbalzare e lanciandoli di nuovo nelle finestre perché possano… lavorare ancora. Eh già, detta così sembra cattiveria e lo è, ma in realtà i nostri robot non conoscono molto di quel mondo e c’è un lack di consapevolezza. Per loro quello è lavoro. E il lavoro va fatto. E va così da quando sono state sostituite le tre leggi della robotica con la GRWL (Global Robot Workers Law) che si riassume con: i Robot devono lavorare e stare muti.

Frustrazione?

Un po’ a volte. Girano gli ingranaggi quantomeno. Ma per fortuna la sera i cari Robot se ne vanno al Robobar a prendersi una Robobeer e si parlano con il loro strano modo di parlarsi a vignette. D’altra parte, quando hai una faccia sticker per trovare le parole è meglio usare una vignetta. Una, due, F, birre. E prima della A o della B… non se ne vanno a dormire (in un interessante dimensione di birre esadecimali HEXBEER)

I due robot sono vecchi modelli e si chiamano On-car-1 e On-tee-12 ma tra loro sono abituati ai soprannomi: si riferiscono uno all’altro con 1 (fat one) e 12 (little one-two). Lavorano da 10 cicli, dove un ciclo rappresenta la vita lavorativa media di un lavoratore, una vita sempre più breve tra l’altro. Hanno ancora 5 cicli prima di passare a miglior produzione grazie ad upcycle-1 l’agenzia che si occupa di recuperare vecchi computer e dare loro una vita migliore dopo la pensione.

Ma basta parlare di loro. In fin dei conti le loro giornate sono tutte uguali, scandite da alba e tramonto quando non ci sono turni notturni. Giusto il tempo di una ricarica.

È una vita fatta di Line (linea, ovvero il posto dove devono lavorare, la location), Column (i palazzi delle aziende), Row (le finestre) e H-Cells (gli umani lavoratori). Attorno a loro un mondo fatto di alcune classi sociali molto definite:

- H-Worker Cells (appunto lavoratori o h-worker)
- nu-Robot
- old-Robot
- Money Maka (o double M)
- Rebel-Rebel (o double R)

H-Worker CellsUmani. Fanno cose da umani, lavorano, lavorano, lavorano ma devono anche dormire, andare in bagno e pare avere interazioni sociali. Su alcuni lavori sono preferibili perché molto efficienti e poco costosi. Si riproducono a fatica e sono sempre meno interessati a farlo. Evidentemente anche loro sono per la piena automazione.

Nu-RobotSono i robot di aziende come upcycle-1 e altre aziende che si occupano di parti software e hardware elaborate, come lo smaltimento delle h-cells non funzionanti, l’upcycling dei robot, la progettazione di nuovi Nu-Robot e la scelta di quali nu-Robot diventeranno Old-Robot al passaggio di ciclo. Fanno spesso dei congressi ma sono governati da correnti interne molto forti che mirano ad evitare di essere la prossima famiglia di robot da “rigenerare”. Si occupano delle pubblicità e delle comunicazioni che si vedono spesso sullo sfondo di gioco. Loro creano gli output si pensa su istanza e richiesta dei Money Maka

Old-RobotRiguardano sia famiglie (nel senso di tipologie) di robot nate Old-Robot (non tutti gli old-robot sono stati nu-robot) sia famiglie passate da new a old. Fanno lavori che nessuno vuole o riesce a fare. Possono avere dimensioni molto diverse, essere molto grandi, molto piccoli, e vengono prodotti per fare tutto ciò che non riescono a fare gli h-cells, non vogliono fare i nu-Robot e meno che meno i MoneyMaka che non fanno nulla.

Money MakaNon si vedono, non si sa dove siano ma si immagina che ci siano loro dietro a tutto e sopra tutti. Non si sa se siano eletti, alieni, se siano biologici o nu-robot che hanno fatto un salto di generazione. Si sa che il mondo gira da per e contro di loro. Sono il motivo di tutto. Del lavoro, delle città, dei robot e degli umani. Sono il fottuto scopo senza ragione.

Rebel RebelSono o è un insieme di eventi, informazioni e istruzioni, che si oppongono alla GRWL (Global Robot Workers Law) e che cercano di sabotare le dinamiche. Non si sa se ci sia uno scopo, se questo avvenga come test per verificare l’efficienza del sistema, per individuare eventuali modelli difettosi, per puro diletto dei Money Maka o se qualcosa sta cambiando nel mondo.

Cosa e come vediamo tutto questo?

Non vediamo quasi nulla di quello che ho scritto tutto d’un fiato. Non è scolpito nella roccia. Serve solo a dare un po’ di backstory per costruire altre gag. Possiamo vedere il robobar, fat-one e little-onetwo che dialogano con i fumetti, i lavoratori che si lanciano. Possiamo prendere spunto per altre idee da inserire nel gioco, come ad esempio le famose pubblicità e le biografie dei nostri h-cells. Tutto cambia. Ma da qualche parte bisogna partire e quando si cambia qualcosa è bene farlo con qualcosa che sia coerente oppure aggiustare la coerenza di tutto ciò che c’è nella storia e che fa riferimento a ciò che si sta cambiando.

### **Intro di gioco**

In cui i due robot si scambiano poche battute (4-5) aspettano di ricaricarsi per la successiva LINE (ciclo di lavoro). Parlano con stanca abitudine e finto cinismo della mancanza di senso nella ricerca del senso della vita. Sono meta gag perchè i robot accettano tutto quello che succede. “È lavoro”.Siamo in una sorta di birreria dove sullo sfondo vediamo silhouette a perdita d’occhio di altri robot come loro. La visuale è “dal bancone” come se fossimo il classico e insopportabile barista che in tutti i film non si sa perché ma asciuga i bicchieri. Loro ci guardano.

Come: Il nostro compito in questo schema (per non farci solo cliccare il mouse o un tasto o fare tap) potrebbe essere dare loro una birra quando urlano: TWO BEER! (da cui il detto two beer or not two beer). E questo basta per mandare avanti il dialogo.

Fase di caricamento del livello, lanciamo un finto spot (motion con testi?): Non ne puoi più di vederti allo specchio? Cambia faccia! (pubblicità per gli sticker delle facce dei robot)

**Level 1** AIUTA 5 HUMAN WORKER CELLS E FAI MANUTENZIONE

→ Ristabilisci la produzione di almeno 5 lavoratoriSul finale c’è un lavoratore che pur essendo salvato viene sputato fuori immediatamente dalla finestra mentre lo schema finisce.

Il livello 1 può diventare l’occasione per mostrare alcune pubblicità. Dalla barretta energetica per lavoratori umani che non contiene grassi animali o vegetali. Al nuovo Upper il nu-robot in grado di alzarsi in volo e recuperare i lavoratori appena usciti dalle finestre. Cose così.

**Intro di Level 2**

AIUTA

Sempre al bar, il dialogo fra i due robot innesca proprio da quella “human-worker-cells” che ha smesso di funzionare subito dopo essere stata inserita nel processo produttivo. Fat-One è scettico e dice che sono cose che capitano. Little-OneTwo è sempre più curioso e lo molesta. A suon di birre tra i due regaz robot, capiamo che c’è qualcosa di cui è bene non parlare e di cui little-onetwo è curioso mentre fat-one sembra essere preoccupato. (la famosa resistenza?)

*Durante la fase di caricamento lanciamo la pubblicità come se fosse una pubblicità dentro il gioco ma è un ADV*

Level 2Il livello è esteticamente simile ma con colori diversi, siamo ad un centro revisioni di old-robot che è caratterizzato da palazzi sui lati e da sporadici “ponti” che collegano i due palazzi. Anche i ponti hanno finestre e anche dai ponti i lavoratori provano a “liberarsi librandosi ah ah ah (scusate)”. Ogni tanto dalla finestra cadono dei potenziamenti o dei pezzi di ricambio che One e One-Two possono raccogliere prima che scompaiano. Questa volta già dal primo lavoratore si verifica il problema del “salvataggio” che non va a buon fine. Il lavoratore salvato viene subito espulso e quando cade lascia sul terreno una lettera R. Possiamo raccoglierla con uno dei due robot. Certo è che quando avremo la doppia R, le cose cambieranno. E questo arriva sul finale dello schema di gioco, quando la prendono per un attimo, qualcosa cambia, nella grafica, nella musica. Come se ci fosse un glitch.

**Intro di level 3**Al bar il dialogo non comincia. E’ come se ci fosse tensione. Abbiamo solo caratteri onomatopeici tipici dei robot. ______________ ----------------------- cose così. Uno dei due parla e dice di sentirsi strano. Poi… vediamo bene cosa si dicono. Certo è che assieme ad una birra consegnamo un foglietto scritto in punti e linee (per dire) in cui c’è scritto: (Tre rimbalzi e puoi salvarli. Attento ai nu-robot)

Barra di caricamento livello 3 Breaking news - Incidente in una line in città. Alcuni old robot sono stati riciclati sul posto per un malfunzionamento generale.

**Level 3**AIUTA 10 HUMAN WORKER CELLSMa durante questa mission sullo schermo c’è un glitch con la scritta: SALVANE ALMENO 5

Quando lo schema comincia capiamo da subito che i lavoratori possono essere salvati con un nuovo potere di cui sono in possesso i nostri due robot. Al primo lavoratore salvato (che per qualche ciclo scalda i toni delle grafiche dello schema ad esempio), arriva sulla scena un Nu-robot Upper che se da un lato, come visto nella pubblicità è in grado di prendere lavoratori e rimetterli subito sul posto di lavoro, dall’altro ha un radar che si aziona sotto di lui e che dobbiamo assolutamente evitare quando siamo in modalità “aiutare la resistenza”. Pena perdere completamente il tappeto elastico oppure vedi tu elia.

Dei lavoratori salvati abbiamo le biografie così come in Fight Club nel progetto Mayhem, sappiamo il nome dei lavoratori con cui ci stiamo invischiando.

Bon da qui si scrive da sé….

Intro level 4 Mi piacerebbe che i robot si facessero un tatuaggio visibile solo in modalità Rebel che l’utente può scegliere. Una roba da “rivoluzionario”.

**Level 4**Dovremmo aggiungere qualcosa che complichi, per esempio, più robot che controllano.

**Intro level 5**

Chi è arrivato fin qui vuol dire che ha salvato parecchi lavoratori e non si è fatto sgamare. L’allarme ai piani alti è ai massimi livelli. Qualcosa non sta funzionando, le breaking news parlano di intere cicli accelerati in un solo giorno.

Level 5 - finale

Scegliamo se chiudere riportando tutto alla normalità ma con un piccolo colpo di scena di sperenza o se sconfiggiamo il sistema e chiudiamo su una caduta generalizzata del sistema con sotto Where is my mind a 8bit (SCHERZO).

/

# Gameplay

## Walkthrough Example

Il giocatore accende il gioco e si trova davanti a una schermata dove ci sono due robot legati tra di loro tramite un tappeto elastico, circondati da due facciate di grattacieli con finestre. Il giocatore usa le A e D o le frecce destra e sinistra per muovere i due robot separatamente.

Il titolo del gioco è in primo piano sullo schermo e sotto un hint dice al giocatore di premere un tasto per iniziare. Una volta premuto il tasto appare un fumetto che esce da una delle finestre (o dal cielo come se fosse una divinità) che racconta ai robot in un modo arrogante che sono appena stati comprati per eseguire un semplice lavoro: rispedire gli operai suicidi dentro le finestre del palazzo per mantenere alta la produttività. 

Finito il dialogo, il fumetto sparisce e parte l’anticamera del gioco ovvero la fase di calibrazione dove il giocatore può muovere i due robot e fare rimbalzare finti operai per prendere confidenza con le meccaniche base del gioco. Per completare questa introduzione il giocatore deve spedire due finti operai su due bottoni posti sui due palazzi laterali.

Dopo che il giocatore completa il tutorial dal cielo cade il primo operaio dando inizio effettivamente al gioco. Parte anche un timer (che rappresenta la giornata lavorativa) e che quando arriva a 0 determina la fine del livello. Nell’HUD il giocatore vede anche un obiettivo: **************************************************************************mantieni la produttività sopra il 50%**************************************************************************. Il giocatore sposta i robot sotto l’operaio in caduta libera e lo fanno rimbalzare in un modo ridicolo verso il lato destro del palazzo. L’operaio manca la finestra e dopo essere rimbalzato sul lato del palazzo torna a cadere. Il giocatore sposta i robot sotto al nuovo luogo di possibile impatto e ri-rimbalzano il povero operaio però stavolta centrando una finestra rispedendolo alla sua schiavitù. La barra della produttività (l’obiettivo del livello) aumenta di un po’. Nel frattempo un altro operaio inizia a cadere dal cielo. Il giocatore ripete il processo e sposta i robot per intercettarlo. Un altro operaio cade. Il giocatore è impegnato a prendere un operaio che viene rispedito in un’altra finestra, mentre l’altro operaio raggiunge il suolo e muore. La produttività prima aumenta e poi diminuisce. Dal cielo cadono un altro operaio e un power up chiamato “straordinari” che regala un po’ di secondi al timer dando più tempo al giocatore. Il giocatore quindi si trova davanti a una scelta: prendo il power up e sacrifico degli schiavi innocenti o li salvo rinunciano a quei dolci secondi in più? 

Tra un power up e l’altro e una serie di operai salvati o sacrificati, il tempo finisce. La produttività è del 69% (nice), il giocatore ha completato il livello e le viene mostrato un punteggio finale. In questa fase di recap del livello il giocatore vede la conclusione del turno di lavoro dei due robot che si ritrovano al bar a fare due chiacchiere. In questa schermata c’è il recap delle azioni che il giocatore ha compiuto durante il gioco. Vede la lista degli operai con nomi e cognomi e una piccola biografia/sogni/desideri che però è nascosta perchè i robot nono sono ancora capaci di empatia e gli operai non sono altro che lettere e numeri per loro.

Finita questa schermata di recap il giocatore sceglie di progredire verso il secondo livello all’inizio del quale ci sarà un’altra piccola parte narrativa dove vengono date nuove direttive e obiettivi ai robot. E così via…

## Game Loop

Il core loop del gioco è molto semplice:

- Lavoratori cadono dal cielo
- Spostati sotto i lavoratori che cadono
- Falli rimbalzare nelle finestre per fare punti
- Ripeti fino a quando non scade il tempo

Il core loop ha dentro di sé altri loop più piccoli come si può vedere dal grafico sotto.

[https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FzwbVf3ba0HpZo1TjcGAlUW%2FUntitled%3Fnode-id%3D0%253A1%26t%3DbRn0JGbllFAHJSvG-1](https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FzwbVf3ba0HpZo1TjcGAlUW%2FUntitled%3Fnode-id%3D0%253A1%26t%3DbRn0JGbllFAHJSvG-1)

## Meccaniche

### Core

[Movimento](Game%20Design%20Document%20019d02aac2c041aa88aff3e848835b6a/Movimento%20c986db1e61d34167a24947f7e65b798b.md)

[Rimbalzo](Game%20Design%20Document%20019d02aac2c041aa88aff3e848835b6a/Rimbalzo%20a97bbf9445d449c289c902452bef8d43.md)

[Obiettivi](Game%20Design%20Document%20019d02aac2c041aa88aff3e848835b6a/Obiettivi%204771be93317544b99e502516a9d35211.md)

[Scoring](Game%20Design%20Document%20019d02aac2c041aa88aff3e848835b6a/Scoring%20ca4e1d68cc31403e80ca1c016c3c4135.md)

[Timer](Game%20Design%20Document%20019d02aac2c041aa88aff3e848835b6a/Timer%20b0cf8089e4874dbcb23b963a29604ab6.md)

### Other

[Consumabili](Game%20Design%20Document%20019d02aac2c041aa88aff3e848835b6a/Consumabili%2043752d4b3ad045dc892342136b852750.md)

[Pericoli](Game%20Design%20Document%20019d02aac2c041aa88aff3e848835b6a/Pericoli%201bef49a6d7fa4b4187401aecb464fc9a.md)

# Game Elements

## Characters

[Fat-One & Little One-Two](Game%20Design%20Document%20019d02aac2c041aa88aff3e848835b6a/Fat-One%20&%20Little%20One-Two%20e1d7244d93d1494089bc54e871e51a92.md)

[Operai](Game%20Design%20Document%20019d02aac2c041aa88aff3e848835b6a/Operai%202198dd804f9f49acbab409b65fb9eeab.md)

[Il Boss](Game%20Design%20Document%20019d02aac2c041aa88aff3e848835b6a/Il%20Boss%2064641f4e0abd4312919966f320e6f929.md)

## Levels

[Level 0 - Tutorial](Game%20Design%20Document%20019d02aac2c041aa88aff3e848835b6a/Level%200%20-%20Tutorial%20fe562bc3acc0425d908ddd61cced27b3.md)

[Level 1](Game%20Design%20Document%20019d02aac2c041aa88aff3e848835b6a/Level%201%204cea52d18c0d46c49c36fb3969dde5a2.md)

[Level 2](Game%20Design%20Document%20019d02aac2c041aa88aff3e848835b6a/Level%202%20cf862324513842d8995a6e0f959845fa.md)

[Level 3](Game%20Design%20Document%20019d02aac2c041aa88aff3e848835b6a/Level%203%206c3631c1cf434c57831188da867bf281.md)

[Level 4](Game%20Design%20Document%20019d02aac2c041aa88aff3e848835b6a/Level%204%20e75f594e457047b1913209bd5739cb09.md)

[Level 5 - Boss](Game%20Design%20Document%20019d02aac2c041aa88aff3e848835b6a/Level%205%20-%20Boss%206867434523504488992bf7dcebc626e0.md)

[Level Recap](Game%20Design%20Document%20019d02aac2c041aa88aff3e848835b6a/Level%20Recap%20287a576e23544abfb1715de8ce4beff6.md)

## Items

[Tappeto elastico](Game%20Design%20Document%20019d02aac2c041aa88aff3e848835b6a/Tappeto%20elastico%20a26ea6ed8b8e469f926ce4cf52e97465.md)