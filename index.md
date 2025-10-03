---
layout: default
title: TravyPlay
---

<style>
  body {
    background-color: #000;
    color: #fff;
    margin: 0;
    padding: 0;
    font-family: 'Segoe UI', sans-serif;
  }

  a {
    color: #56ff8a;
  }

  /* Titolo principale grande e neon animato */
  h1 {
    font-size: 4em;
    color: #56ff8a;
    text-align: center;
    animation: neonGlow 1.5s ease-in-out infinite alternate;
    text-shadow:
       0 0 5px #56ff8a,
       0 0 10px #56ff8a,
       0 0 20px #56ff8a,
       0 0 40px #56ff8a,
       0 0 80px #56ff8a;
  }

  h2 {
    color: #56ff8a;
  }

  strong {
    color: #56ff8a;
  }

  table {
    border-collapse: collapse;
  }

  img {
    border-radius: 12px;
    box-shadow: 0 2px 12px #0f0;
  }

  ul li {
    line-height: 1.7;
  }

  .roadmap li {
    margin-bottom: 8px;
  }

  /* Animazione neon */
  @keyframes neonGlow {
    from {
      text-shadow:
       0 0 5px #56ff8a,
       0 0 10px #56ff8a,
       0 0 20px #56ff8a,
       0 0 40px #56ff8a,
       0 0 80px #56ff8a;
    }
    to {
      text-shadow:
       0 0 10px #56ff8a,
       0 0 20px #56ff8a,
       0 0 30px #56ff8a,
       0 0 50px #56ff8a,
       0 0 100px #56ff8a;
    }
  }
</style>


## 📖 Descrizione

**TravyPlay** è un media player open-source costruito in **Flutter**, progettato per unificare:  

- Libreria **musicale locale** 🎵  
- Collezione di **film e serie TV** 🎬  
- Liste e canali **IPTV** 📺  

Il tutto in **un’unica interfaccia moderna e semplice da usare**, pensata per sostituire più app con una sola soluzione.

<table style="width:100%; border-spacing:0 0;">
  <tr>
    <td style="width:60%; vertical-align:top;">
      <h2 style="margin-top:0; text-align:left;">✨ Funzionalità Principali</h2>
      <table style="width:100%; border-spacing:0 20px;">
        <tr>
          <td style="width:130px; vertical-align:top;">
            <img src="screenshots/Screenshot_TravyPlay2.png" width="120"/>
          </td>
          <td style="vertical-align:top; padding-left:10px;">
            <strong>🎵 Gestione Musica</strong><br>
            Scansione automatica dei file audio.<br>
            Libreria organizzata per genere, artista e album.<br>
            Creazione e gestione playlist personalizzate.
          </td>
        </tr>
        <tr>
          <td style="width:130px; vertical-align:top;">
            <img src="screenshots/Screenshot_TravyPlay3.png" width="120"/>
          </td>
          <td style="vertical-align:top; padding-left:10px;">
            <strong>🎬 Libreria Video</strong><br>
            Collezioni intelligenti di film e serie.<br>
            Navigazione fluida tra i contenuti video.
          </td>
        </tr>
        <tr>
          <td style="width:130px; vertical-align:top;">
            <img src="screenshots/Screenshot_TravyPlay4.png" width="120"/>
          </td>
          <td style="vertical-align:top; padding-left:10px;">
            <strong>📺 Supporto IPTV</strong><br>
            Aggiunta sorgenti M3U (link o file locali).<br>
            Canali organizzati per nazione o categoria.<br>
            Streaming TV integrato.
          </td>
        </tr>
      </table>
    </td>
    <td style="width:40%; vertical-align:top;">
      <h2 style="margin-top:0; text-align:right;">🚀 Funzioni Secondarie</h2>
      <ul style="font-size:1.05em; margin-bottom:30px; text-align:right;">
        <li><strong>⭐ Show Preferiti</strong> – Accesso rapido a film, serie o canali IPTV.</li>
        <li><strong>🎶 Playlist Musicali</strong> – Gestione lista brani personalizzata.</li>
        <li><strong>🔍 Ricerca Potente</strong> – Filtri veloci e risultati in tempo reale.</li>
        <li><strong>🔄 Sincronizzazione Automatica</strong> – Libreria sempre aggiornata.</li>
        <li><strong>📱 Cross-Platform</strong> – Android e presto iOS. <span style="font-size:0.95em; color:#56ff8a;">(iOS non ancora disponibile)</span></li>
      </ul>
      <div style="margin-top:10px; text-align:right;">
        <table style="margin:auto; border-spacing:10px 0;">
          <tr>
            <td><img src="screenshots/Screenshot_TravyPlay4.png" width="200"/></td>
            <td><img src="screenshots/Screenshot_TravyPlay9.png" width="200"/></td>
          </tr>
        </table>
      </div>
    </td>
  </tr>
</table>

## 🌟 Highlights
✅ Unifica Musica + Video + IPTV in un’unica app<br>
✅ Interfaccia moderna e fluida (Flutter)<br>
✅ Gratuito & Open Source<br>
✅ Ottimizzato per mobile

## ⚠️ Stato del Progetto
**Versione attuale:** `0.9.5 Beta`<br>
👉 L’app è stabile ma ancora in sviluppo attivo. Alcune funzioni potrebbero cambiare o migliorare.

## 📅 Roadmap (Prossimi Step)
<ul class="roadmap">
<li>Integrazione con **Open Library (Internet Archive) API's** per ricerca, lettura, download di Libri 📚</li>
<li>Finalizzazione **versione iOS**</li>
<li>Rilascio su **Android / IOS**</li>
</ul>

<p align="center" style="font-size:14px; color:#56ff8a;">
  <img src="icon_travyplay.png" alt="TravyPlay Logo Footer" width="40" style="vertical-align:middle;"/>  
</p>
