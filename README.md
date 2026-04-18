# Debian-Iron-Core
Versione personalizzata di Debian LXDE 13.4.0 con temi di WhiteSur e icone Papirus per Asus k52f i3 prima generazione
# Debian Iron Core 🐧💎

Benvenuti nel repository ufficiale della **Debian Iron Core**, una versione personalizzata e alleggerita di Debian, nata per ridare vita all'hardware datato come l'**Asus K52F (Intel i3 1st Gen)**.

## 🎯 Obiettivo del Progetto
Creare un sistema solido come il ferro ("Iron"), ma esteticamente moderno e fluido, eliminando tutto il software superfluo (niente utility preinstallate) per garantire le massime prestazioni.

## 🛠️ Componenti Inclusi
* **Sistema di Build:** Penguins-eggs
* **Installer:** Calamares (grafico e intuitivo)
* **Desktop Environment:** (Inserisci qui il tuo desktop, es: XFCE o GNOME)
* **Temi:** WhiteSur GTK (Mac Style)
* **Icone:** WhiteSur & Papirus Icons
* **Wallpaper:** Selezione ufficiale Windows 11

## 🚫 Filosofia "No Bloatware"
In questa ISO **non sono state inserite utility extra**. L'utente troverà un sistema pulito e sarà libero di installare solo ciò che realmente gli serve, mantenendo il disco leggero e il processore scattante.

### ⚡ Ottimizzazioni e Performance
* **Base OS**: Debian 13.4 (Trixie) - All'avanguardia con pacchetti e kernel aggiornati.
* **CPU Tuning**: Ottimizzazione specifica per il set di istruzioni dell'Intel i3-M370 (prima generazione).
* **ZRAM**: Configurazione avanzata per gestire meglio la memoria RAM su hardware datato.
* **Fast Boot**: Servizi di sistema ridotti all'osso per un avvio rapido "Iron Core".
* **Ottimizzazione Intel Graphics**: Driver configurati per la massima fluidità dell'interfaccia WhiteSur.

* ### 📚 Repository e Librerie Extra
* **Contrib & Non-Free**: Abilitati per il pieno supporto a driver proprietari e software di terze parti.
* **Non-Free Firmware**: Incluso per garantire che Wi-Fi, Bluetooth e schede grafiche Intel funzionino al 100% senza impazzire con i driver.

### 🎮 Gaming e Performance
* **GameMode (Feral Interactive)**: Preinstallato e configurato. Permette di spremere ogni briciolo di potenza dal processore i3 quando si avviano giochi o applicazioni pesanti, ottimizzando le priorità della CPU.
* **ZRAM**: Ottimizzazione della memoria virtuale (molto più veloce del classico file di Swap su disco).

* ### 💾 Test sul campo (Real Hardware Test)
* **Dispositivo di test**: Asus K52F (Intel i3 1st Gen).
* **Storage**: Testato con successo su **HDD meccanico da 250 GB**.
* **Risultato**: Nonostante l'uso di un disco rigido tradizionale (non SSD), il sistema mantiene una reattività eccellente e tempi di avvio rapidi, grazie all'ottimizzazione del file system e della ZRAM.

* ### 🖼️ Supporto Grafico e Multimedia
* **Intel Media-VAAPI**: Driver completi preinstallati per l'accelerazione hardware video.
* **Intel Media Driver**: Supporto totale alle librerie grafiche Intel per una riproduzione video fluida e minor carico sulla CPU.
* **Mesa Extras**: Librerie aggiornate per garantire che l'interfaccia WhiteSur sia reattiva e senza lag grafici.
