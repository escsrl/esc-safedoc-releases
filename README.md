# ESC SafeDoc
 
**ESC SafeDoc** è un'applicazione desktop per l'anonimizzazione di documenti. Rileva e oscura automaticamente dati personali e sensibili (nomi, indirizzi, codici fiscali, e altre informazioni identificative) all'interno dei tuoi file, restituendo una versione anonimizzata pronta da condividere o archiviare.
 
## Requisiti di sistema
 
- **Windows** 10/11 a 64 bit
- **macOS** su Apple Silicon (M1/M2/M3/M4)
- **Linux** a 64 bit (via AppImage)
## Installazione
 
### Windows
 
1. Scarica `ESC-SafeDoc_3.7.0_x64-setup.exe`
2. Esegui il file e segui la procedura guidata
3. Al termine, l'app sarà disponibile nel menu Start
### macOS
 
1. Scarica `ESC-SafeDoc_3.7.0_aarch64.dmg`
2. Apri il file `.dmg` e trascina **ESC SafeDoc** nella cartella Applicazioni
3. Al primo avvio, se macOS mostra un avviso di sicurezza, apri **Preferenze di Sistema → Privacy e Sicurezza** e conferma l'apertura dell'app
### Linux
 
1. Scarica `ESC-SafeDoc_3.7.0_amd64.AppImage`
2. Rendi il file eseguibile:
```bash
   chmod +x ESC-SafeDoc_3.7.0_amd64.AppImage
```
3. Avvia l'app con doppio click o da terminale:
```bash
   ./ESC-SafeDoc_3.7.0_amd64.AppImage
```
 
## Utilizzo
 
1. Apri ESC SafeDoc
2. Carica il documento da anonimizzare (sono supportati i formati documento e foglio di calcolo più comuni)
3. L'app analizza il contenuto e individua automaticamente i dati sensibili
4. Rivedi le rilevazioni proposte, se necessario
5. Esporta il documento anonimizzato
## Aggiornamenti
 
ESC SafeDoc include un sistema di aggiornamento automatico: alla partenza l'app verifica se è disponibile una nuova versione e propone l'installazione con un click. Non è necessario scaricare manualmente i nuovi installer.
 
## Sicurezza e verifica
 
Ogni installer è distribuito insieme a una firma digitale (file `.sig`) che ne garantisce l'autenticità e l'integrità. La verifica avviene automaticamente tramite il sistema di aggiornamento integrato dell'app.
 
## Supporto
 
Per problemi, richieste o segnalazioni, contattare ESC Enterprise Software Consulting S.R.L.
 
---
Versione corrente: **3.7.0**
