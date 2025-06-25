# Template AutoLux - Vetrina Vendita Auto

Un template professionale e moderno per la vendita di auto di lusso, completamente responsive e facilmente personalizzabile.

## 🚗 Caratteristiche Principali

- **Design Moderno**: Layout elegante con gradienti e animazioni fluide
- **Completamente Responsive**: Ottimizzato per desktop, tablet e mobile
- **Facile da Personalizzare**: Testi e contenuti facilmente modificabili
- **Sezioni Complete**: Hero, veicoli, servizi, contatti e footer
- **Animazioni Smooth**: Effetti di hover e scroll animati
- **Form Funzionale**: Modulo di contatto con validazione

## 📁 Struttura File

```
auto_sales_template/
├── index.html          # Pagina principale
├── style.css           # Stili CSS
├── script.js           # JavaScript per interazioni
├── car_exterior_1.jpg  # Immagine hero
├── car_exterior_2.jpg  # Immagine veicolo 1
├── car_exterior_3.jpg  # Immagine veicolo 2
├── car_interior_1.jpg  # Immagine veicolo 3
├── car_interior_2.jpg  # Immagine sezione "Perché sceglierci"
└── README.md           # Questo file
```

## 🎨 Personalizzazione

### 1. Modificare i Testi

Apri il file `index.html` e modifica i seguenti elementi:

#### Nome dell'Azienda
```html
<!-- Cambia "AutoLux" con il nome della tua azienda -->
<h1>AutoLux</h1>
```

#### Titolo Hero
```html
<!-- Modifica il titolo principale -->
<h1 class="hero-title">Scopri l'Eccellenza Automobilistica</h1>
```

#### Sottotitolo Hero
```html
<!-- Personalizza la descrizione -->
<p class="hero-subtitle">La tua prossima auto di lusso ti aspetta...</p>
```

#### Informazioni Veicoli
```html
<!-- Per ogni veicolo, modifica: -->
<h3 class="vehicle-name">BMW Serie 7 2024</h3>
<p class="vehicle-specs">3.0L Turbo • 340 CV • Automatico</p>
<div class="vehicle-price">€89.900</div>
```

#### Informazioni di Contatto
```html
<!-- Aggiorna i tuoi dati di contatto -->
<p>Via Roma 123, 20121 Milano, Italia</p>
<p>+39 02 1234 5678</p>
<p>info@autolux.it</p>
```

### 2. Sostituire le Immagini

Sostituisci le immagini esistenti con le tue:

1. **car_exterior_1.jpg** - Immagine hero (consigliato: 1200x800px)
2. **car_exterior_2.jpg** - Prima auto in vetrina (consigliato: 800x600px)
3. **car_exterior_3.jpg** - Seconda auto in vetrina (consigliato: 800x600px)
4. **car_interior_1.jpg** - Terza auto in vetrina (consigliato: 800x600px)
5. **car_interior_2.jpg** - Sezione "Perché sceglierci" (consigliato: 600x400px)

**Importante**: Mantieni gli stessi nomi dei file o aggiorna i riferimenti nel file HTML.

### 3. Personalizzare i Colori

Nel file `style.css`, puoi modificare i colori principali:

```css
/* Colori principali del gradiente */
background: linear-gradient(45deg, #ff6b6b, #4ecdc4);

/* Cambia con i tuoi colori preferiti */
background: linear-gradient(45deg, #TUO_COLORE_1, #TUO_COLORE_2);
```

### 4. Aggiungere/Rimuovere Veicoli

Per aggiungere un nuovo veicolo, copia questo blocco HTML nella sezione `vehicles-grid`:

```html
<div class="vehicle-card">
    <div class="vehicle-image">
        <img src="NOME_IMMAGINE.jpg" alt="NOME_AUTO">
        <div class="vehicle-overlay">
            <button class="btn-view">Visualizza Dettagli</button>
        </div>
    </div>
    <div class="vehicle-info">
        <h3 class="vehicle-name">NOME AUTO</h3>
        <p class="vehicle-specs">SPECIFICHE TECNICHE</p>
        <div class="vehicle-price">€PREZZO</div>
        <div class="vehicle-features">
            <span class="feature">Km CHILOMETRAGGIO</span>
            <span class="feature">Garanzia X anni</span>
        </div>
    </div>
</div>
```

## 🔧 Funzionalità Avanzate

### Form di Contatto
Il form è già configurato con validazione JavaScript. Per collegarlo a un servizio di invio email:

1. Modifica la funzione nel file `script.js`
2. Sostituisci l'alert con una chiamata al tuo backend
3. Configura il tuo servizio email preferito

### Menu Mobile
Il menu hamburger è già implementato e funzionante su dispositivi mobili.

### Animazioni
Le animazioni sono gestite automaticamente dal JavaScript. Puoi disabilitarle commentando le relative sezioni nel file `script.js`.

## 📱 Responsive Design

Il template è ottimizzato per:
- **Desktop**: 1200px e superiori
- **Tablet**: 768px - 1199px  
- **Mobile**: fino a 767px

## 🌐 Browser Supportati

- Chrome (versioni recenti)
- Firefox (versioni recenti)
- Safari (versioni recenti)
- Edge (versioni recenti)

## 🚀 Come Utilizzare

1. **Scarica tutti i file** nella stessa cartella
2. **Personalizza i contenuti** seguendo questa guida
3. **Sostituisci le immagini** con le tue
4. **Testa il sito** aprendo `index.html` nel browser
5. **Carica online** su qualsiasi servizio di hosting

## 💡 Suggerimenti

- **Immagini**: Usa immagini di alta qualità (almeno 1920x1080 per l'hero)
- **Testi**: Mantieni i testi concisi e accattivanti
- **Colori**: Scegli una palette coerente con il tuo brand
- **Performance**: Ottimizza le immagini per il web (formato WebP consigliato)

## 🆘 Supporto

Se hai bisogno di aiuto per la personalizzazione:

1. Verifica che tutti i file siano nella stessa cartella
2. Controlla la console del browser per eventuali errori
3. Assicurati che i nomi delle immagini corrispondano a quelli nel codice HTML

## 📄 Licenza

Questo template è fornito per uso personale e commerciale. Puoi modificarlo liberamente secondo le tue esigenze.

---

**Buona fortuna con la tua vetrina auto! 🚗✨**

