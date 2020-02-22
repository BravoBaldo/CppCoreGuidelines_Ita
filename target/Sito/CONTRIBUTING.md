## Contribuire alle C++ Core Guidelines

> "All'interno del C++ c'è un più piccolo, semplice e sicuro linguaggio, che lotta per uscire fuori".
> -- <cite>Bjarne Stroustrup</cite>

Le C++ Core Guidelines è un lavoro di gruppo guidato da Bjarne Stroustrup, proprio come lo stesso linguaggio C++. Sono il risultato di molti anni-uomo di discussione e progettazione in diverse organizzazioni. Per come sono progettate incoraggiano una generale applicabilità ed un'ampia adozione ma si possono liberamente copiare e modificare per soddisfare le esigenze della propria organizzazione.

I contributi alle C++ Core Guidelines vengono incoraggiati in diversi modi:
- **feedback individuale** Siete sviluppatori appassionati del vostro codice? Partecipate alla discussione [Issues](https://github.com/isocpp/CppCoreGuidelines/issues). Vogliamo sapere quali regole vi garbano e quali no Ci sono regole eccessivamente difficili da applicare? La 'Guideline Support Library' del proprio compilatore (p.es., [L'implementazione delle GSL di Microsoft](https://github.com/microsoft/gsl)) soddisfa le proprie esigenze adottandole?
- **Adozione nelle organizzazioni** Sebbene le linee-guida siano progettate per essere largamente adottate, devono anche essere modificate per adattarsi alle esigenze della specifica organizzazione. Incoraggiamo le organizzazioni a fare un fork di questo repositori creandosi la propria copia di queste linee-guida con delle modifiche che ne riflettano le necessità. Consigliamo di esplicitare nel titolo che sono delle linee-guida proprie e che costituiscono un fork della propria organizzazione e di fornire un link al set originale delle [linee-guida](https://github.com/isocpp/CppCoreGuidelines). E se una qualsiasi delle modifiche risultasse appropriata per essere inserite nelle linee-guida originali, aprite un [Issue](https://github.com/isocpp/CppCoreGuidelines/issues) che porti ad una 'pull request'.
- **Manutenzione delle Guidelines** Le C++ Core Guidelines sono state create da una vasta gamma di conoscenze diffuse in diverse organizzazioni in tutto il mondo. Se voi o la vostra organizzazione volete collaborare a creare le linee-guida, prendete in considerazione di diventare un redattore o un manutentore. Se siete degli esperti in C++ che vogliono davvero partecipare, mandate una mail a [email coreguidelines@isocpp.org](mailto:coreguidelines@isocpp.org?subject=Maintain the C++ Code Guidelines).

## Accordo di Licenza per i Collaboratori
Contribuendo al contenuto delle C++ Core Guidelines (p.es., inviando una 'pull request' da inserire in questo repository) si accettano quelli che della [Standard C++ Foundation](https://isocpp.org/about) sono i [Termini d'Uso](https://isocpp.org/home/terms-of-use), in special modo tutti i termini specificati in materia di Brevetti e Copyright.
- Voi garantite che il vostro materiale è originale o che avete il diritto di contribuire ad esso.
- Per quanto riguarda il materiale in proprio possesso, concedete una licenza mondiale, non-esclusiva, irrevocabile, trasferibile e esente da royalty per il materiale fornito alla Standard C++ Foundation per mostrare, riprodurre, eseguire, distribuire e creare opere derivate da esso per uso commerciale o non commerciale. Rispetto a qualsiasi altro materiale da voi fornito, questo deve essere coperto da una licenza sufficiente a consentire alla Standard C++ Foundation di mostrare, riprodurre, eseguire, distribuire e creare opere derivate da esso per uso commerciale o non commerciale.
- Accettate che, se il materiale viene successivamente riportato nello standard C++ ISO/IEC in qualsiasi forma, sarà soggetto a tutte le politiche ISO/IEC JTC 1 inclusi i [copyright](http://www.iso.org/iso/home/policies.htm), i [brevetti](http://www.iso.org/iso/home/standards_development/governance_of_technical_work/patents.htm), e le [procedure](http://www.itscj.ipsj.or.jp/sc29/29w7proc.htm); tutte le domande su tali politiche vanno rivolte alla [ISO Central Secretariat](http://www.iso.org/iso/home/about.htm).


## Pull request

Accogliamo con favore le 'pull request' per delle modifiche mirate alle linee-guida--correzione ai bug negli esempi, chiarimento di frasi ambigue, ecc. Le modifiche più significative devono prima essere discusse nelle [Issue](https://github.com/isocpp/CppCoreGuidelines/issues) e il numero della Issue dev'essere incluso nella pull request.  Per le modifiche relative alle linee-guida, specificare il numero della regola nell'Issue e/o nella Pull Request.

Le modifiche devono essere apportate in un commit child di un commit recente nel branch master.  Se si apportano molte piccole modifiche, creare dei PR [Pull Request] separati per minimizzare problemi nel merge.

### Linee-guida sullo Stile del Documento

I documenti in questo repository sono scritti in uno specifico dialetto del Markdown, che lascia delle ambiguità sulla formattazione del testo.  Chiediamo che le [pull request] mantengano le seguenti linee-guida stilistiche, sebbene siamo consapevoli che il documento potrebbe già non essere coerente.

#### Indentazione

Il codice e il testo nidificato devono utilizzare multipli di 4 spazi di rientro e nessun carattere di tabulazione, in questo modo:

    void func(const int x)
    {
    std::cout << x << '\n';
    }

#### Blocchi di Codice

Usare un'indentazione di 4 spazi per attivare il parsing del codice, anziché [blocchi di codice contornato](https://help.github.com/articles/github-flavored-markdown/#fenced-code-blocks) o qualsiasi altro stile, in questo modo:

    Questo è il testo di un documento, seguito da un esempio:
    
    void func()
    {
    std::cout << "Questo è codice.\n";
    }

### Miscellanea

Per evitare problemi con i fine-riga, si prega di impostare `autocrlf = input` e `whitespace =
cr-at-eol` nella propria configurazione git.
