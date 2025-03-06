L'app desktop è progettata per visualizzare una pagina web personalizzata all'interno di una finestra dell'applicazione utilizzando WebView2. L'interfaccia include pulsanti con icone per eseguire azioni come Salva, Carica, Esci, Aggiungi, Rimuovi e Stampa.

Tecnologie Utilizzate:
Visual Studio 2022: Ambiente di sviluppo integrato (IDE).
.NET Core WPF: Framework per creare applicazioni desktop Windows.
WebView2: Componente per incorporare una pagina web basata su Microsoft Edge Chromium.
HTML/CSS: Per costruire l'interfaccia utente.
Font Awesome: Per aggiungere icone professionali ai pulsanti.
C#: Per la logica dell'app e il caricamento della pagina web.
Funzionalità dell'App:
Visualizzazione della Pagina Web:

La pagina HTML index.html viene caricata nella WebView2 all'avvio dell'app.
L'interfaccia web è completamente stilizzata con CSS, inclusi pulsanti e riquadri di output.
Pulsanti con Icone:

Ogni pulsante ha un'icona associata per un'interazione più intuitiva.
Icone integrate tramite Font Awesome.
Effetti Visivi e Animazioni:

I pulsanti cambiano colore al passaggio del mouse (hover effect).
Utilizzo di Flexbox in CSS per un layout ordinato e reattivo.
Riquadro di Output:

Un riquadro fisso nella parte inferiore della finestra mostra il testo stampato o informazioni aggiuntive.
Flusso di Lavoro dell'App:
Avvio dell'app: L'app si apre e carica automaticamente la pagina index.html tramite WebView2.
Interazione con i pulsanti:
Cliccando sui pulsanti, l'app potrebbe eseguire azioni come:
Salva: Apre la finestra dei file del sistema e ti permette di scegliere dove salvare il file
Carica: Apre la finestra dei file del sistema e ti permette di scegliere quale file caricare
Esci: Esci dal programma.
Aggiungi: Apre una finestra che chiede titolo e autore del libro.
Rimuovi: Apre una finestra che chiede indice del libro e rimuove il corrispondente.
Visualizzazione del testo: Il riquadro inferiore mostra il testo relativo all'azione eseguita.
