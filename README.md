# :wave: Le basi di GitHub 

## 🤓 Panoramica del corso e obiettivi di apprendimento 

L’obiettivo di questo corso è offrirti una breve introduzione a GitHub. Ti forniremo anche materiali per approfondire e alcune idee per iniziare sulla nostra piattaforma. 🚀

## :octocat: Git e GitHub

Git è un **Sistema di Controllo di Versione distribuito (VCS)**, il che significa che è uno strumento utile per tracciare facilmente le modifiche al tuo codice, collaborare e condividere. Con Git puoi monitorare le modifiche apportate al tuo progetto, così avrai sempre una cronologia del lavoro svolto e potrai tornare facilmente a una versione precedente se necessario. Inoltre, rende più semplice lavorare con altri: gruppi di persone possono collaborare allo stesso progetto e unire le loro modifiche in un’unica versione finale!

GitHub è un modo per utilizzare la potenza di Git completamente online tramite un’interfaccia facile da usare. Viene utilizzato nel mondo del software e oltre per collaborare e mantenere la cronologia dei progetti.

GitHub ospita alcune delle tecnologie più avanzate al mondo. Che tu stia visualizzando dati o creando un nuovo gioco, su GitHub troverai una comunità e un insieme di strumenti che possono aiutarti a fare il passo successivo. Questo corso parte dalle basi di GitHub, ma approfondiremo il resto più avanti.

## :octocat: Comprendere il flusso di GitHub 

Il flusso di GitHub è un workflow leggero che ti permette di sperimentare e collaborare facilmente sui tuoi progetti, senza il rischio di perdere il lavoro precedente.

### Repository

Un repository è il luogo in cui avviene il lavoro sul tuo progetto -- puoi pensarlo come la cartella del progetto. Contiene tutti i file del progetto e la cronologia delle revisioni. Puoi lavorare in un repository da solo oppure invitare altri a collaborare sui file.

### Clonazione 

Quando un repository viene creato su GitHub, viene archiviato remotamente nel ☁️. Puoi clonare un repository per creare una copia locale sul tuo computer e poi usare Git per sincronizzare le due versioni. Questo rende più facile correggere problemi, aggiungere o rimuovere file e inviare modifiche più grandi. Puoi anche utilizzare l’editor che preferisci invece dell’interfaccia di GitHub. Clonare un repository scarica anche tutti i dati presenti in quel momento, incluse tutte le versioni di ogni file e cartella del progetto! Questo è utile se sperimenti e poi preferisci tornare a una versione precedente.  
Per saperne di più sulla clonazione, leggi ["Cloning a Repository"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository). 

### Commit e push
**Commit** e **push** sono i modi per aggiungere le modifiche fatte sul tuo computer locale al repository remoto su GitHub. In questo modo il tuo insegnante e/o i tuoi compagni possono vedere il tuo lavoro aggiornato quando sei pronto a condividerlo. Puoi fare un commit quando hai apportato modifiche che vuoi “salvare come punto di controllo”. Puoi anche aggiungere un utile **messaggio di commit** per ricordare a te o al tuo team cosa hai fatto (es. “Aggiunto README con informazioni sul progetto”).

Una volta che hai uno o più commit pronti, puoi usare il comando push per inviarli al repository remoto. All’inizio commit e push possono sembrare nuovi, ma ci farai presto l’abitudine 🙂

## 💻 Termini GitHub da conoscere 

### Repository 
Abbiamo già menzionato i repository, ma approfondiamo! Con il tempo avrai molti repository e all’inizio può sembrare confuso. Fortunatamente, la tua ["dashboard GitHub"](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) ti aiuta a navigare facilmente tra di essi e a vedere informazioni utili. Assicurati di essere connesso!

I repository contengono anche i **README**. Puoi aggiungere un file README per spiegare perché il tuo progetto è utile, cosa si può fare con esso e come usarlo. Noi stiamo usando questo README per spiegarti come imparare Git e GitHub. 😄  
Per saperne di più, leggi ["Creating, Cloning, and Archiving Repositories"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) e ["About README's"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes). 

### Branch
Puoi usare i branch su GitHub per isolare il lavoro che non vuoi ancora integrare nel progetto finale. I branch permettono di sviluppare funzionalità, correggere bug o sperimentare nuove idee in modo sicuro. Di solito si crea un branch dalla branch principale — main. Questo crea una copia del repository su cui lavorare. Quando le modifiche sono pronte o revisionate, puoi unirle al branch principale.  
Per saperne di più, leggi ["About Branches"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

### Fork
Un fork è un altro modo per copiare un repository, usato soprattutto quando vuoi contribuire a un progetto di altri. Ti permette di sperimentare liberamente senza modificare il progetto originale ed è molto comune nei progetti open source!  
Per saperne di più, leggi ["Fork a repo"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo)

### Pull request
Quando lavori con i branch, puoi usare una pull request per informare gli altri delle modifiche e chiedere feedback. Una volta aperta, puoi discutere e rivedere le modifiche con i collaboratori e aggiungerne altre se necessario. Puoi anche assegnare revisori specifici. Quando è pronta, la pull request può essere unita al branch principale.  
Per saperne di più, leggi ["About Pull Requests"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests). 

### Issues
Le issue servono per tracciare miglioramenti, attività o bug. Sono utili per organizzare il lavoro e comunicare cosa si intende fare. Puoi anche usarle per segnalare bug o suggerire funzionalità nei progetti open source.

Per progetti più grandi, puoi usare le bacheche di progetto. GitHub Projects ti aiuta a organizzare e dare priorità al lavoro. Probabilmente non ti serviranno per esercizi piccoli, ma sono molto utili per progetti più grandi.  
Puoi anche collegare pull request e issue per mostrare che una correzione è in corso e chiudere automaticamente una issue quando la pull request viene unita.  
Per saperne di più sulle issue e su come collegarle alle pull request, leggi ["About Issues"](https://docs.github.com/en/github/managing-your-work-on-github/about-issues). 

### Il tuo profilo utente

La pagina del profilo racconta la tua attività: repository, contributi e interazioni. Puoi anche creare un README del profilo per presentarti. È utile anche per futuri datori di lavoro!  
Per saperne di più sul tuo profilo e su come aggiungere o aggiornare il README del profilo, leggi ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme). 

### Usare Markdown su GitHub 

Come forse hai già notato, puoi aggiungere uno stile interessante a issue, pull request e file. ["Markdown"](https://guides.github.com/features/mastering-markdown/) è un modo semplice per formattare issue, pull request e file con una sintassi intuitiva. Questo può aiutarti a organizzare le informazioni e a renderle più facili da leggere. Puoi anche inserire GIF e immagini per comunicare meglio il tuo messaggio!  
Per saperne di più sull’uso della variante Markdown di GitHub, leggi ["Basic Writing and Formatting Syntax"](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax). 

### Interagire con la community GitHub

La community GitHub è molto ampia. Ci sono tanti tipi di persone che usano GitHub ogni giorno: studenti come te, sviluppatori professionisti, appassionati di open source e persone che stanno esplorando il mondo dello sviluppo software in autonomia. Ci sono molti modi per interagire con la community GitHub, ma ecco tre punti da cui puoi iniziare. 

#### Mettere una stella ai repository 

Se trovi un repository interessante o vuoi tenerlo d’occhio, puoi aggiungerlo ai preferiti con una stella! Quando metti una stella a un repository, questa viene usata anche come segnale per migliorare i suggerimenti su github.com/explore. Se vuoi ritrovare i repository a cui hai messo una stella, puoi farlo dal tuo profilo utente.  
Per saperne di più, leggi ["Saving Repositories with Stars"](https://docs.github.com/en/github/getting-started-with-github/saving-repositories-with-stars). 

#### Seguire utenti 

Puoi seguire persone su GitHub per ricevere notifiche sulla loro attività e scoprire progetti nelle loro community. Quando segui un utente, la sua attività pubblica su GitHub apparirà nella tua dashboard, così potrai vedere tutte le cose interessanti su cui sta lavorando.  
Per saperne di più, leggi ["Following People"](https://docs.github.com/en/github/getting-started-with-github/following-people).

#### Esplorare GitHub Explore 

GitHub Explore è un ottimo posto per fare proprio questo... esplorare :smile: Puoi trovare nuovi progetti, eventi e sviluppatori con cui interagire.

Puoi visitare GitHub Explore [su github.com/explore](https://github.com/explore). Più interagisci con GitHub, più la tua vista Explore sarà personalizzata in base ai tuoi interessi. 

## 📝 Prossimi passi 

* Apri una pull request e fai sapere al tuo insegnante che hai completato questo corso.  
* Crea un nuovo file markdown in questo repository. Fai sapere cosa hai imparato e cosa ti lascia ancora dei dubbi! Sperimenta con stili diversi!
* Crea il README del tuo profilo. Fai sapere al mondo qualcosa in più su di te! Cosa ti interessa imparare? A cosa stai lavorando? Qual è il tuo hobby preferito? Scopri di più su come creare il README del tuo profilo nel documento ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).
* Vai alla dashboard del tuo utente e crea un nuovo repository. Sperimenta con le funzionalità presenti al suo interno per prendere familiarità con esse. 


## 📚 Risorse 
* [Un breve video che spiega cos’è GitHub](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be) 
* [Risorse per imparare Git e GitHub](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources) 
* [Comprendere il flusso di GitHub](https://guides.github.com/introduction/flow/)
* [Come usare i branch su GitHub](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Materiali di formazione interattivi su Git](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub Learning Lab](https://lab.github.com/)
* [Forum della community Education](https://education.github.community/)
* [Forum della community GitHub](https://github.community/)
