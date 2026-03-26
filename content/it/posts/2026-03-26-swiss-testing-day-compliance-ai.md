---
title: "Conformità e IA in primo piano allo Swiss Testing Day 2026"
date: 2026-03-26
description: "Lo Swiss Testing Day 2026 ha messo al centro la conformità dell'IA e i test non deterministici, con relatori provenienti dal settore bancario, dalla governance e dall'ingegneria del software."
summary: "Lo Swiss Testing Day 2026 ha reso evidente una cosa: conformità e IA non sono più conversazioni separate. Dalla keynote di Bertrand Meyer sulla verifica del software a un intervento eccezionale sull'inutilità dell'IA per la conformità — e sulla sua indispensabilità —, la conferenza ha dimostrato che testare sistemi non deterministici è la sfida centrale per i professionisti della qualità oggi."
featured_image: "images/bertrand-meyer.jpg"
featured_image_alt: "Bertrand Meyer allo Swiss Testing Day 2026"
featured_image_caption: "Software Correctness Authority Bertrand Meyer"
---

Lo Swiss Testing Day 2026, tenutosi a Zurigo il 26 marzo, ha riunito tester, ingegneri della qualità e professionisti della conformità per una giornata di interventi e panel incentrati su un tema dominante: cosa succede quando l'IA entra in sistemi che devono essere affidabili, verificabili e corretti?

## La correttezza del software incontra il non-determinismo

La keynote di apertura di Bertrand Meyer — pioniere del design-by-contract e del linguaggio Eiffel — ha dato il tono alla giornata. Meyer ha affrontato un'ampia gamma di temi, ma è tornato costantemente a un'idea centrale: dimostrare che il software fa ciò che promette. I grandi modelli linguistici (LLM), con il loro non-determinismo intrinseco, hanno reso questa sfida più difficile, non più semplice.

Meyer ha sottolineato che le prestazioni delle funzionalità stocastiche — in particolare gli LLM — devono essere *misurate*, perché un semplice verdetto superato/non superato non è sufficiente. Non è tuttavia entrato nel dettaglio del *come*, ribadendo la sua convinzione di lunga data: la correttezza deve essere integrata nel software fin dalla progettazione.

Ha concluso con una nota ottimistica, sostenendo che il bisogno di ingegneri del software qualificati non scomparirà, anche se i loro strumenti cambieranno. Il codice generato deve comunque essere verificato, e la comprensione umana del codice resta essenziale.

## La strategia di test non è un elenco di obiettivi

Iosif Itkin ha invitato il pubblico a riflettere con attenzione su cosa significhi realmente strategia di test — e cosa non lo sia. Non è un elenco di obiettivi. Non è nemmeno la stessa cosa dell'assicurazione qualità, che richiede una mentalità fondamentalmente diversa.

Facendo ampio riferimento al libro *Good Strategy/Bad Strategy*, Itkin ha offerto un prezioso promemoria: le organizzazioni che prendono sul serio l'IA devono progettare deliberatamente la propria strategia di test, non lasciarla emergere per caso.

## I test agentici producono già risultati nel settore bancario

Un team del settore bancario svizzero ha presentato «Avalon», un sistema basato su agenti che genera dati di test sintetici. Sebbene la presentazione sia entrata rapidamente nei dettagli del prodotto, il messaggio chiave era chiaro: si tratta di un'applicazione agentica sofisticata che sta già producendo guadagni di produttività misurabili. Il sistema opera in modo trasparente, mostrando le interazioni LLM e le chiamate agli strumenti in tempo reale attraverso la sua interfaccia.

## L'intervento sulla conformità della giornata

La sessione più rilevante è stata quella di Nick Gushchin, *Why AI Is Useless for Compliance …and Why You Still Need It*. Gushchin, AI Transformation Manager, ha presentato un approccio strutturato alla gestione del rischio dell'IA attraverso una matrice probabilità-impatto — un framework collaudato la cui importanza, ha sottolineato, non è minore nell'era dell'IA.

La sua domanda centrale — come quantificare la dimensione «probabilità» quando si ha a che fare con sistemi non deterministici — è esattamente la sfida che i framework di test probabilistici mirano ad affrontare. È stato il primo intervento della conferenza ad affrontare esplicitamente il problema del test di sistemi i cui output sono intrinsecamente variabili.

Niente clamore, niente discorsi vaghi — solo indicazioni pratiche e concrete per chiunque sia responsabile di test e affidabilità in ambienti guidati dall'IA.

## Definire la qualità in un decennio pericoloso

Il panel pomeridiano ha riunito Bertrand Meyer, Elmar Jürgens e Marcel Gygli, moderati da Anne-Lea Marte, attorno a una domanda apparentemente semplice: in un mondo in cui i sistemi apprendono, come si definisce la qualità?

Le risposte hanno subito divergo. Gygli ha definito la qualità in base a ciò che l'utente ottiene. Jürgens ha obiettato: per software semplice, forse — ma i sistemi critici richiedono di più. Meyer ha adottato la visione più ampia, insistendo sul fatto che la qualità è multidimensionale, vive negli occhi di tutti gli stakeholder e deve essere mantenuta nel tempo.

Sul tema della velocità, i panelisti si sono mostrati cauti. Jürgens ha avvertito di un possibile compromesso se la generazione di codice supera la generazione di test. Gygli ha posto una domanda più incisiva: se il 90 % del codice generato è corretto ma il restante 10 % è estremamente difficile da testare o debuggare, il guadagno di velocità apparente potrebbe essere illusorio.

La discussione si è fatta più serrata sul tema della responsabilità. Quando un sistema di IA causa danni, chi ne risponde? Jürgens è stato categorico: chi ha creato il software. Meyer ha avvertito che sia l'entusiasmo sia il rifiuto dell'IA sono pericolosi, e che i decisori si lasciano troppo facilmente trascinare dall'hype. Tutti e tre hanno concordato che educazione e regolamentazione sono essenziali per mantenere i presidi umani.

Alla domanda su cosa sia assurdo nel settore, i panelisti non si sono trattenuti. Meyer ha criticato l'affidare il controllo agli agenti con gli umani come backup. Gygli ha preso di mira il vibe coding. Jürgens ha definito la maggior parte degli approcci alla misurazione della produttività come privi di significato.

Su cosa vorrebbero vedere realizzato, i panelisti hanno converguto sulla regolamentazione. Gygli ha chiesto una regolamentazione utilizzabile che rifletta ciò di cui la società ha realmente bisogno. Meyer — scherzando che «l'America innova, la Cina copia, l'Europa regola» — ha espresso la speranza di vedere più prove matematiche nei test. Jürgens sperava che Meyer avesse ragione, pur notando che i metodi formali restano limitati nella pratica.

## Quando il codice generato non può essere testato

Jonas Hermansson ha condiviso un resoconto schietto sullo sviluppo software interamente affidato ad agenti IA. Il suo team utilizza ora più team di agenti con ruoli distinti — frontend, backend, database — e impiega il doppio degli agenti di test rispetto a quelli di sviluppo.

Le lezioni sono state conquistate a caro prezzo. I primi esperimenti con codice generato tramite vibe coding hanno prodotto soluzioni praticamente impossibili da testare. Una funzionalità di login generata conteneva un bug riconducibile a un requisito ambiguo. Un wrapper QA che testava l'intento dai requisiti al prodotto finale non ha comunque individuato bug di concorrenza. Alla fine, il team ha reintrodotto i test manuali come verifica finale — costosi, ma necessari.

La rivelazione forse più sorprendente: il team di Hermansson non effettua più alcuna manutenzione del codice. Quando qualcosa deve cambiare, il codice viene rigenerato da zero. Un flusso di lavoro radicale che solleva tante domande quante ne risolve.

## La keynote di chiusura: un appello al pensiero statistico

Robert Sabourin — accademico e veterano del testing — ha tenuto una keynote di chiusura che ha trasformato la corrente di inquietudine della conferenza in opportunità. Ha ripreso il tono di allerta che gli organizzatori avevano deliberatamente scelto, contrapponendo un messaggio positivo sulle opportunità di business che derivano dal testare sistemi guidati dall'IA.

{{< figure src="images/test-oracle.jpeg" alt="Slide sugli oracoli di test probabilistici dalla keynote di chiusura di Robert Sabourin" caption="Robert Sabourin on the need for experiments and probabilistic testing" >}}

Ancora più significativo per i temi di questa conferenza, Sabourin ha sostenuto esplicitamente il testing probabilistico. Ha esortato i tester a sviluppare un pensiero statistico, argomentando che i servizi stocastici devono essere testati in modo probabilistico — non con i verdetti binari superato/non superato ereditati dal software deterministico. Una conclusione perfettamente adatta a una giornata che aveva girato attorno a questa idea più volte senza sempre nominarla direttamente.

## Il filo conduttore

Lungo l'intero programma della giornata, un filo conduttore era inconfondibile: la professione del testing si confronta con sistemi che non si comportano mai allo stesso modo due volte. I test tradizionali superato/non superato sono stati progettati per software deterministico. I sistemi oggi in uso — dagli agenti basati su LLM al rilevamento di media sintetici — richiedono nuovi approcci: misurazione statistica, garanzie probabilistiche e framework di governance capaci di gestire l'incertezza.

Lo Swiss Testing Day 2026 ha dimostrato che la professione ne è consapevole. La domanda ora è quanto velocemente gli strumenti e le pratiche si adegueranno.
