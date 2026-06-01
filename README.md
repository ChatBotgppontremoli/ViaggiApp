# 🧳 ViaggiApp

**ViaggiApp** è un'app web per organizzare i bagagli di viaggio per tutta la famiglia, con liste intelligenti personalizzate, consigli AI, modalità offline e installazione come app sul telefono.

---

## 🚀 Come pubblicare su GitHub Pages (passo per passo)

### 1. Crea un account GitHub
Se non ce l'hai, vai su [github.com](https://github.com) e registrati gratuitamente.

---

### 2. Crea un nuovo repository

1. Clicca sul **+** in alto a destra → **New repository**
2. Dai un nome al repo, es: `viaggiapp`
3. Spunta **"Public"** (obbligatorio per GitHub Pages gratuito)
4. Spunta **"Add a README file"**
5. Clicca **Create repository**

---

### 3. Carica il file index.html

1. Dentro il repository appena creato, clicca **"Add file"** → **"Upload files"**
2. Trascina il file `index.html` nella finestra
3. In basso scrivi un messaggio, es: *"Prima versione ViaggiApp"*
4. Clicca **"Commit changes"**

> ⚠️ Il file **deve chiamarsi `index.html`** (non `viaggiapp.html` o altro)

---

### 4. Attiva GitHub Pages

1. Vai su **Settings** (in alto nel repository)
2. Nel menu a sinistra clicca **Pages**
3. Sotto **"Branch"** seleziona **`main`** e cartella **`/ (root)`**
4. Clicca **Save**
5. Aspetta 1-2 minuti

L'app sarà disponibile all'indirizzo:
```
https://TUO_USERNAME.github.io/viaggiapp/
```

---

### 5. Installa l'app sul telefono (PWA)

**Android (Chrome):**
1. Apri il link su Chrome
2. Tocca i tre puntini in alto a destra
3. Seleziona **"Aggiungi a schermata Home"**
4. Conferma → l'app appare come icona sul telefono

**iPhone (Safari):**
1. Apri il link su Safari
2. Tocca l'icona **Condividi** (quadrato con freccia)
3. Scorri e seleziona **"Aggiungi a schermata Home"**
4. Conferma

---

### 6. Aggiornare l'app in futuro

Quando vuoi aggiornare ViaggiApp:
1. Vai nel repository su GitHub
2. Clicca su `index.html`
3. Clicca l'icona **matita** (Edit)
4. Oppure usa **"Add file" → "Upload files"** per sostituire il file

---

## ✨ Funzionalità

- ✅ Liste intelligenti per destinazione, clima e tipo di viaggio
- 👥 Profili per ogni passeggero (uomo, donna, bambino M/F)
- 👕 Vestiti personalizzati per persona e durata
- 💊 Farmacia, documenti, toilette, elettronica, cibo
- ✨ Consigli AI (richiede chiave OpenRouter gratuita)
- 🌙 Dark mode
- ⚖️ Peso stimato bagaglio con limite franchigia
- 📝 Note viaggio con salvataggio automatico
- 🔍 Filtro per priorità (essenziale/consigliato/opzionale)
- 💾 Esporta lista .txt e backup .json
- 📲 Installabile come app (PWA) con funzionamento offline

---

## 🔑 Consigli AI — come attivare

1. Clicca **✨ Consigli AI** in un viaggio
2. Registrati su [openrouter.ai](https://openrouter.ai) (gratis, basta Google)
3. Vai su [openrouter.ai/keys](https://openrouter.ai/keys) e crea una chiave
4. Incollala nel campo che appare nell'app
5. La chiave viene salvata nel browser — si inserisce solo una volta

---

## 📁 Struttura file

```
viaggiapp/
└── index.html     ← tutta l'app in un unico file
└── README.md      ← questo file (opzionale)
```
