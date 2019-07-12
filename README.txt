Istruzioni esecuzione dei vari notebook.

IMPORTARE DATASET NEL PROPRIO DRIVE
Eseguire SOLAMENTE se si sta eseguendo i notebook in Colab. Nel caso contrario i dataset/pesi devono essere salvati il locale.
Aprire i link desiderati, tramite una mail unimib, contenuti nel file 'Link_Google_Drive.txt'. Dopodichè premere col tasto destro del mouse sulla cartella/file e premere
'Aggiungi a Il Mio Drive'. 
DOWNLOAD DATASET IN LOCALE
Aprire i link desiderati, tramite una mail unimib, contenuti nel file 'Link_Google_Drive.txt'. Dopodichè premere col tasto destro del mouse sulla cartella/file e premere
'Scarica'.

Multi-classe
Eseguire le celle in ordine, eccetto la seconda se i dataset/pesi sono in locale, controllando i percorsi dei dataset utilizzati. 
Nel caso in cui si volesse 
usare il modello creato nelle prove, caricare il file ‘VGG16_finet.h5’ e il file ‘VGG16_finet.json’, eseguire l’ultima cella presente e successivamente eseguire 
la sezione ‘Test’ e ‘Valutazione modello’ oppure la sezione ’Alcuni esempi’.


Multi-label
Prima di compilare la prima cella assicurarsi che il file 'utils.py' sia nella stessa cartella nel notebook 'multi_label.ipynb'. Dopodichè eseguire la prima cella.
La seconda cella deve essere eseguita solamente se i dataset/pesi sono salvati in Google Drive e si sta eseguendo su ambiente Colab.
Prima di procedere con la seguente fase assicurarsi che i percorsi ai dataset siano corretti, in base se siano stati salvati in locale o su Drive.
A questo punto se si vuole addestrare il modello procedere eseguendo in ordine tutte le celle.
Se invece si vuole effettuare solo la fase di test è possibile caricare il modello in formato 'model_InceptV3_multi_label.json' e i relativi pesi in 
formato 'weights_InceptV3_multi_label.h5', quest'ultima operazione viene effettuata nell'ultima sezione del notebook chiamata 'Carica del modello'.
Dopodichè per testare il modello procedere eseguendo le celle a partire della sezione 'Test'.

Multi-task
-Addestramento rete: eseguire in ordine le celle, eccetto la seconda se i dataset/pesi sono in locale, contenute nel file 'multi_task_training.ipynb'. 
Non è necessario eseguire le celle presenti nella sezione 'Salvataggio modello in Google Drive'. Assicurarsi che i percorsi ai dataset siano corretti.
-Test rete: eseguire in ordine le celle, eccetto la terza se i dataset/pesi sono in locale, contenute nel file 'multi_task_test.ipynb'. 
Assicurarsi che i percorsi ai dataset/pesi siano corretti.
