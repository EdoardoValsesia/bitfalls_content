Una questione che viene spesso citata dalle istituzioni finanziarie, dai politici e dalle autorit� di controllo contro l'adozione su larga scala delle [criptovalute][cc] � il fatto che sono anonime e quindi adatte per essere usate da criminali e terroristi.

## Ignoriamo...

Ignoriamo il fatto che il denaro non sar� mai completamente rimovibile dalla societ�. Un governo potrebbe dichiarare criminali tutte le transazioni in contanti o [rimuovere l'85% del valore monetario circolante in uno Stato da un giorno all'altro][India], ma questo renderebbe tutti i cittadini criminali e stiamo ipotizzando una dittatura completamente fuori controllo. Cambiare il modo in cui funziona il denaro servir� solo a punire chi ha buone intenzioni, ed � qualcosa di facilmente superabile dai criminali che possono passare con facilit� a un'altra forma di pagamento.

Ignoriamo anche il fatto che, anche se il contante fosse completamente rimosso dalla circolazione, i criminali che il governo dovrebbe presumibilmente temere possono scambiare oro, argento, petrolio, diamanti e perfino il [detersivo Tide][tide].

![Confezioni di Tide messe in sicurezza](https://bitfalls.com/wp-content/uploads/2017/09/01-3.jpg)

Chiudiamo anche un occhio sul fatto che, nella maggior parte degli Stati, il mercato nero esiste solo perch� il mercato "bianco" ha deluso la gente. Ad esempio, in Venezuela esiste un [mercato nero per il cibo](http://www.npr.org/sections/thesalt/2017/01/09/508986586/as-venezuelan-go-hungry-the-military-is-trafficking-in-food) perch�, semplicemente, *la gente non ha da mangiare*. Durante la depressione degli anni 80 in Russia � nato un [mercato nero per i Dollari americani][dollarus] perch� i Rubli erano considerati senza valore da molte aziende ed esercizi. Vale la pena notare che, se il mercato nero di una societ� � basato su oppiacei, pornografia o altri tipi di contrabbando "ricreativo", � normalmente un buon indicatore di quanto le cose vadano bene in quella societ�: significa che tutte le necessit� di base della sua gente vengono soddisfatte. Societ� del genere sono infatti molto rare.

Per finire, ignoriamo anche il fatto che stiamo chiedendo alla stessa entit� che governa il nostro denaro di autoregolarsi, dandole la completa libert� di decidere il valore del denaro. Quando esiste una tale libert� ci stupiamo davvero quando scopriamo che sono [i governi a finanziare direttamente il terrorismo][terror]? Ma, come abbiamo detto sopra, ignoriamo anche questo.

Invece, concentriamoci su quello di cui hanno presumibilmente paura: l'anonimato.

### Bitcoin e anonimato 

![L'icona dell'anonimato - Maschera di Guy Fawkes](https://bitfalls.com/wp-content/uploads/2017/09/02-2.jpg)

Per prima cosa, � importante capire la differenza tra privacy e anonimato.

Quando comprate o vendete qualcosa e quello che avete comprato o venduto - e da chi - non � registrato da nessuna parte, si parla di privacy. Quando comprate o vendete qualcosa e nessuno registra *chi* ha fatto l'acquisto o la vendita, si parla di anonimato. 

Uno scambio di contanti, beni o servizi (o una combinazione di essi) � sia privata che anonima, soprattutto se non c'� alcuna ricevuta e le parti non si conoscono. Un acquisto con carta di credito non � n� l'una n� l'altra cosa, perch� viene registrato chi compra, per quanto e quando.

I Bitcoin sono _parzialmente anonimi_ e _assolutamente non privati_ in virt� del fatto del funzionamento della [blockchain][bc].

Perch� _parzialmente_? Perch� la maggior parte delle persone non entrano nel mondo delle criptovalute usando mezzi anonimi. Vista la relativamente alta complessit� di ottenere le prime criptovalute (generare un [wallet], ottenere i BTC da qualcuno, immagazzinare i BTC, imparare [come usarli][startbtc]...), in molti fanno i primi acquisti tramite piattaforme come [Coinbase][coinbase], [Litebit][litebit] o [Cex][cex], che rendono tutto il processo molto pi� semplice.

Ma, in tutti questi siti, l'acquisto richiede di superare le misure di KYC e AML (Conosci il tuo cliente - Know Your Customer - e Anti riciclaggio - Anti-Money-Laundering) inviando un documento personale e a volte anche una foto di voi che tenete in mano un documento valido. Una volta inviate tali informazioni, il vostro indirizzo bitcoin � tanto anonimo quanto un conto bancario: per niente. Da qui � realistico concludere che chiunque sia interessato ai bitcoin in modo legittimo non ha nulla da nascondere e per questo li usa in maniera del tutto aperta.

![Caricatura di una registrazione biometrica](https://bitfalls.com/wp-content/uploads/2017/09/03-2.jpg)

Ma, se un utente entra nel mondo delle criptovalute tramite altri mezzi che garantiscono l'anonimato (ad esempio via mining, acquisto in contanti, essere pagato in BTC per i propri servizi), nel migliore dei casi l'anonimato � ancora fragile. Ecco come lo si pu� perdere.

## Perdere l'anonimato

### Distrazione

Visto che lo stato dell'intera [blockchain][bc] � pubblico, fare una sbadataggine e rivelare la propriet� di un in indirizzo (guardando il saldo da un computer pubblico, usare un indirizzo bitcoin come firma di un post su un forum, fare acquisti da un negozio che permette il pagamento tramite bitcoin...) � sufficiente per legare in modo permanente la vera identit� di una persona alla blockchain e alle sua azioni effettuate al suo interno (guardate il grafico delle transazioni in basso).

### Identificazione dell'IP

Quando un utente bitcoin genera e invia una transazione dal proprio computer, la transazione � inviata a tutti gli altri software bitcoin (miner) che fanno parte del protocollo bitcoin e devono confermare tale transazione.

Visto che non tutti i computer sono uno vicino all'altro, il segnale richiede pi� tempo per raggiungere quelli pi� lontani. Ogni miner che riceve una transazione registra anche l'IP dal quale questa transazione � arrivata. Un indirizzo IP � letteralmente un indirizzo nello "spazio di internet" che definisce dov'� un computer, cos� che tutti gli altri lo possano trovare. Ogni dispositivo connesso a internet ha un proprio indirizzo IP.

Se un'autorit� riesce a ottenere abbastanza registri relativi a un IP da diversi miner pu� confrontarli con i momenti in cui un segnale ha raggiunto una certa macchina e usarli per estrapolare la locazione geografica di chi ha inviato la transazione. Nel caso peggiore tutto questo pu� permettere di restringere la ricerca a un'area grande quanto un quartiere o una citt�, nel migliore dei casi pu� portare davanti alla porta della persona. [Qui][bitip] c'� un accurato documento di ricerca.

![Come funziona internet](https://bitfalls.com/wp-content/uploads/2017/09/04-1.jpg)

Un indirizzo IP pu� essere parzialmente oscurato tramite Tor, ma anche questo [non � granch� sicuro][tor].

Ovviamente, se usate degli exchange che gestiscono centinaia di migliaia di indirizzi bitcoin in un dato momento e li cambiano con regolarit�, gli IP non hanno molta importanza. *A meno che* questi exchange non tengano registrati gli IP, gli indirizzi passati e le transazioni, se la legge lo richiede: in tal caso le informazioni possono essere portate in giudizio e analizzate.

### Grafico delle transazioni

Il metodo pi� avanzato, il [grafico delle transazioni][tg], consiste nel tracciare dettagliatamente la blockchain stessa.

Come regola generale, gli utenti bitcoin dovrebbero utilizzare un nuovo indirizzo con ogni transazioni per aumentare la privacy ed essere sicuri: non potete mai sapere chi ha la vostra chiave privata una volta che questa arriva su internet. Per questo � consigliabile che, inviando una quantit� X dall'indirizzo A all'indirizzo B, il mittente abbia anche un indirizzo generato C al quale inviare i fondi che rimangono dall'indirizzo A.

Il grafico delle transazioni tiene conto di tutto questo. Se una transazione ha pi� di un indirizzo di input, � logico supporre che tali indirizzi appartengano alla stessa persona o gruppo. Se una transazione ha multipli indirizzi in uscita, si pu� supporre che l'indirizzo che non � mai apparso prima nella blockchain sia l'indirizzo rimasto, quello al quale vengono inviati i fondi che rimangono sul primo indirizzo dopo aver effettuato l'invio di cui sopra. Se poi prendiamo in considerazione la tendenza umana a utilizzare i numeri interi, ha senso concludere che, se una transazione contiene un numero intero di BTC verso un indirizzo e una quantit� frazionaria verso un altro (ad esempio, 3 BTC e 2.5379824792878972 BTC), il secondo � probabilmente il valore residuo mentre il primo � il destinatario. La stessa ipotesi pu� essere verificata convertendo i BTC in fiat, anche se questo � un po' pi� complesso: implica sapere la valuta fiat del destinatario e il valore di scambio in un preciso momento.

![Esempio di grafico delle transazioni](https://bitfalls.com/wp-content/uploads/2017/09/05.png)

Tutto questo, per�, traccia il percorso nella blockchain, non c'� modo di collegarlo a una precisa identit�. Per identificare le parti dobbiamo eliminare gli elementi non noti dall'equazione che ci interessa. Per farlo, bisogna sostituire gli indirizzi del grafico con le entit� note.

Ad esempio, vari negozi online accettano i bitcoin solo su un indirizzo, tenendolo fisso nel tempo. La stessa cosa vale per le organizzazioni che accettano donazioni. Gli utenti dei forum hanno spesso il loro indirizzo bitcoin come firma, beatamente ignari di tutte le informazioni pubbliche che si sono lasciati alle spalle proprio in tali forum. Alcuni hanno anche indirizzi bitcoin nelle firme delle email. Dire a qualcuno che avete comprato un bellissimo paio di calzini di Star Wars tramite bitcoin potrebbe sembrare del tutto innocente, ma se quel qualcuno sa che quel paio di calzini viene venduto solo da un negozio e combina il prezzo di acquisto con il momento stimato dell'acquisto e l'indirizzo BTC del negozio, non � difficile trovare il *vostro* indirizzo, identificandovi per sempre nella blockchain. In futuro, se qualcuno avr� mai bisogno di sapere qualcosa su di voi, lo potr� utilizzare come punto di partenza e svelare la storia delle vostre transazioni.

Combinando tutti i tre metodi, le autorit� hanno preso il proprietario di Silkroad, un noto mercato nero di droga, armi e altre merci di contrabbando. I programmatori fra di voi possono divertirsi un po' con i grafici delle transazioni con strumenti come [questi] [sparkx].

## Conclusioni

La rete Bitcoin non � privata ed � solo parzialmente anonima. Al momento, la criptovaluta pi� anonima � Monero, seguita da Dash, Zcash, Verge, Vertcoin e presto Ether.

Le transazioni di Bitcoin sono semplici da seguire ma, anche se non lo fossero, cercare di combattere le criptovalute a livello di governo porter� agli stessi effetti sulla rete che ha portato la guerra alla droga. In altre parole, le criptovalute verrebbero relegate a qualcosa di underground: tutti quelli che le stavano gi� utilizzando continuerebbero a farlo e come risultato ci sarebbero frodi, criminalit� e altri scenari pericolosi e, come per la droga, un valore di tasse incassate pari a zero.

L'unico approccio *corretto* �:

- definire con chiarezza le regole e gli obblighi per gli utenti di criptovalute

e

- accettare la fungibilit� delle criptovalute. In altre parole, rendere irrilevante la provenienza del denaro proprio come per i contanti, e trattare ogni [Satoshi][finite] come unit� a s�.

L'unico modo per combattere l'uso criminale delle criptovalute � una decriminalizzazione nazionale e l'accettazione come valuta. Qualsiasi divieto fa solo in modo che la tecnologia diventi underground, facendo fiorire il crimine, e allo stesso tempo negando completamente qualsiasi potenziale effetto positivo.

[terror]: http://www.balkaninsight.com/en/article/the-pentagon-s-2-2-billion-soviet-arms-pipeline-flooding-syria-09-12-2017
[tide]: http://nymag.com/news/features/tide-detergent-drugs-2013-1/
[india]: https://www.bloomberg.com/news/articles/2016-11-23/india-s-cash-canceling-experiment
[dollarus]: http://www.nytimes.com/1987/07/22/world/in-soviet-rubles-coupons-and-real-money.html?mcubz=0
[tor]: https://arxiv.org/abs/1410.6079
[blockchain]: https://bitfalls.com/it/2017/08/20/blockchain-explained-blockchain-works/
[bc]: https://bitfalls.com/it/2017/08/20/blockchain-explained-blockchain-works/
[wallet]: https://bitfalls.com/it/2017/08/31/what-cryptocurrency-wallet/
[startbtc]: https://bitfalls.com/2017/09/01/send-receive-bitcoin/
[litebit]: https://www.litebit.eu?referrer=111550
[coinbase]: https://www.coinbase.com/join/542b0423734ab06764000001
[cex]: https://cex.io/r/0/up108919585/0/
[bitip]: https://arxiv.org/pdf/1405.7418.pdf
[tg]: https://arxiv.org/abs/1502.01657
[sparkx]: https://github.com/ZuInnoTe/hadoopcryptoledger/wiki/Using-Spark-Scala-Graphx-to-analyze-the-Bitcoin-transaction-graph
[cc]: https://bitfalls.com/it/2017/08/20/cryptocurrency/
[finite]: https://bitfalls.com/2017/09/17/bitcoin-finite-just-myth/
