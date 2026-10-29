
EgoCenter è un progetto ombrello che raccoglie più progetti con un unico
obiettivo: riportare i tuoi dati a casa tua.

Nasce dall'esigenza di staccarsi dai servizi cloud commerciali, che troppo
spesso usano i contenuti degli utenti per addestrare modelli senza che gli
utenti lo sappiano. EgoCenter è una soluzione headless (senza monitor né
interfaccia grafica locale, si gestisce via rete) per creare un media server
e un cloud personale. Parte semplice, ma può crescere fino a configurazioni
molto più complesse, adattandosi alle tue esigenze.


------------------------------------------------------------------
EgOS — semplice e pulito
------------------------------------------------------------------

Un sistema essenziale, pensato per chi vuole un posto sicuro per foto, video
e media senza complicazioni.

Cosa include
  - Utility per la gestione dello storage
  - Jellyfin: il tuo media server per film, serie TV e musica
  - Immich: backup e galleria per foto e video
  - Solo queste due app: niente di superfluo

Come funziona
  - Serve una connessione a internet solo per i primi due avvii
  - Una volta pronto, puoi scollegarlo completamente dalla rete esterna:
    i tuoi dati restano in un posto sicuro, lontano da qualsiasi esposizione

Limiti
  - Le app incluse sono solo Jellyfin e Immich: per aggiungerne altre
    serve EgoBuilder
  - Quando è offline, le funzioni che si appoggiano a servizi online non
    sono disponibili. Riguarda soprattutto Jellyfin: niente download
    automatico di metadati, locandine e sottotitoli
  - Senza internet non riceve aggiornamenti: per installarli devi
    ricollegarlo temporaneamente


------------------------------------------------------------------
EgoBuilder — per chi vuole di più
------------------------------------------------------------------

Un container Docker con una web app che ti guida nella creazione del tuo
EgOS personale: scegli le app, e EgoBuilder le precarica nell'immagine ISO.

Cosa permette
  - Creare un'immagine ISO di EgOS su misura
  - Precaricare nell'immagine qualsiasi app dockerizzata
  - Configurare tutto dalla web app, invece che a mano

Limiti
  - Richiede qualche competenza in più: devi saper avviare un container
    Docker e conoscere le app che vuoi aggiungere
  - La compatibilità, la configurazione e il funzionamento offline delle
    app aggiunte dipendono dalle app stesse


------------------------------------------------------------------
EgoAppCenter — in costruzione
------------------------------------------------------------------

Il prossimo tassello dell'ecosistema. Lavori in corso: novità presto.

