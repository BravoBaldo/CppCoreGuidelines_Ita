[![C++ Core Guidelines](cpp_core_guidelines_logo_text.png)](http://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines)

> "All'interno del C++ c'è un più piccolo, semplice e sicuro linguaggio, che lotta per uscire fuori".
> -- <cite>Bjarne Stroustrup</cite>

Le [C++ Core Guidelines](CppCoreGuidelines.md) è un lavoro di gruppo guidato da Bjarne Stroustrup, proprio come lo stesso linguaggio C++. Sono il risultato di molti anni-uomo di discussione e progettazione in diverse organizzazioni. Per come sono progettate incoraggiano una generale applicabilità ed un'ampia adozione ma si possono liberamente copiare e modificare per soddisfare le esigenze della propria organizzazione.

## Per iniziare

Le stesse "guidelines" si trovano in [CppCoreGuidelines](CppCoreGuidelines.md). Il documento è in [GH-flavored MarkDown](https://github.github.com/gfm/). Viene intenzionalmente mantenuto semplice, principalmente in ASCII, per consentire un post-processing automatico come la traduzione e la riformattazione. Gli editors ne mantengono una [versione formattata per la navigazione](http://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines). Si noti che viene integrato manualmente e può essere leggermente più datato della versione nel branch principale.

Le Guidelines costituiscono un documento in continua evoluzione senza una rigida cadenza di "rilascio". Bjarne Stroustrup rivede periodicamente il documento incrementando il numero della versione nell'introduzione. [I checkins che incrementan i numero della versione](https://github.com/isocpp/CppCoreGuidelines/releases) vengno taggati in git.

Molte delle linee-guida usano l'header unico della Guidelines Support Library. Un'implementazione è disponibile su [GSL: Guidelines Support Library](https://github.com/Microsoft/GSL).

## Background e scopo

Lo scopo delle linee-guida è quello di aiutare le persone ad usare il C++ moderno in modo efficace. Per "C++ moderno" intendiamo C++11, C++14, e C++17. In altre parole, come vorreste che fosse il vostro codice tra 5 anni, dato che potete iniziare ora? Tra 10 anni?

Le linee-guida si concentrano sulle questioni di livello relativamente più alto, come le interfacce, la gestione delle risorse, la gestione della memorie e la concorrenza. Queste regole riguardano l'applicazione dell'architettura e il design della libreria. Seguire le regole porterà ad un codice staticamente type-safe, senza leak [perdite] di risorse, e che intercetta molti più errori logici di programmazione di quanto avvenga nel normale codice oggi. E girerà velocemente -- ci si può permettere di fare le cose nel modo giusto.

Ci occupiamo un po' meno dei problemi di basso livello, come le convenzioni sui nomi e lo stile di indentazione. Tuttavia, niente di ciò che può aiutare il programmatore è fuori luogo.

Il nostro gruppo iniziale di regole enfatizza la sicurezza (sotto varie forme) e la semplicità. Potrebbero essere anche troppo severe. Ci aspettiamo di dover introdurre più eccezioni per venire meglio incontro alle esigenze del mondo reale. Abbiamo bisogno anche di più regole.

Troverete alcune delle regole contrarie alle vostre aspettative e persino contrarie alla vostra esperienza. Se non vi abbiamo suggerito di modificare in alcun modo di cambiare lo stile del vostro codice, abbiamo fallito! Provate a verificare o confutare le regole! In particolare, vorremmo davvero avere su alcune nostre regole un sostegno con misure ed esempi migliori.

Troverete alcune regole ovvie o addirittura banali. Ricordate che lo scopo di una linea-guida è quello di aiutare qualcuno che ha meno esperienza o che proviene da un diverso background o da un diverso linguaggio a mettersi al passo.

Le regole sono progettate per essere supportate da uno strumento di analisi. Le violazioni delle regole verranno contrassegnate con riferimenti (o link) alla regola violata.
Non ci aspettiamo che memorizziate tutte le regole senza aver prima provato a scrivere il codice.

Le regole sono pensate per un introduzione graduale su una base di codice. Per questo abbiamo in programma la realizzazione di tool e speriamo che anche altri lo facciano.

## Contributi e LICENZA

I commenti e i suggerimenti per migliorare sono sempre benvenuti. Prevediamo di modificare ed estendere questo documento man mano che migliorano la nostra comprensione, il linguaggio e l'insieme delle librerie disponibili. Ulteriori dettagli si trovano su [CONTRIBUTI](./CONTRIBUTING.md) e [LICENZA](./LICENSE).

Grazie alla [DigitalOcean](https://www.digitalocean.com/?refcode=32f291566cf7&utm_campaign=Referral_Invite&utm_medium=Referral_Program&utm_source=CopyPaste) per ospitare il sito web della Standard C++ Foundation.
