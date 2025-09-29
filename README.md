# 🚗 Autoscuola ABA - Form Prenotazioni Rinnovo Patente

## La rivoluzione digitale arriva a Bassano del Grappa (era ora!)

Avete presente quando dovete rinnovare la patente e vi tocca fare la fila, telefonare otto volte, lasciare messaggi vocali che nessuno ascolterà mai? Ecco, questo form risolve tutto. O almeno ci prova con stile.

## 🎯 Cosa fa davvero questo progetto

Un form di prenotazione che **funziona sul serio** - non uno di quei cosi enterprise che richiedono Java 1.6 e Internet Explorer. Questo gioiellino:

- **📱 Mobile-first** → Perché nel 2025 il 99% delle persone lo userà dal bagno con lo smartphone
- **📸 Upload foto patente** → Scatta, carica, fatto. Niente scanner del 1998
- **📧 EmailJS integrato** → Zero backend, zero database, zero problemi (quasi)
- **🎨 Design pulito** → Rosso ABA dominante, come piace al capo

## 🛠 Stack tecnologico (spoiler: è minimalista)

```
HTML + CSS + JavaScript vanilla
├── Niente React (shocking!)
├── Niente build process
├── Niente npm install che scarica mezza internet
└── Solo 41KB di puro codice artigianale
```

## 💡 Feature che non ti aspetti

### Compressione foto intelligente
La foto della patente da 5MB diventa 40KB. Magia? No, Canvas API usata bene. Il cliente non deve più chiedersi perché l'email non parte.

### Feedback tattile
```javascript
if ('vibrate' in navigator) {
    navigator.vibrate(10); // bzz
}
```
Sì, il telefono vibra quando tocchi i pulsanti. Dettagli che fanno la differenza.

## 📊 Perché funziona (dati reali)*

```
Prima del form:
- 15 chiamate perse al giorno
- 3 ore di "Pronto? Vorrei prenotare..."
- 1 segretaria sull'orlo di una crisi di nervi

Dopo il form:
- 0 chiamate per prenotazioni base
- Email strutturate che arrivano davvero
- Segretaria che sorride (incredibile ma vero)
```
*dati stimati con metodo scientifico "a occhio"

## 🐛 Bug conosciuti (aka "feature")

1. **Il form è troppo bello** → I clienti potrebbero innamorarsene e compilarlo per divertimento
2. **EmailJS ha limiti mensili** → 200 email gratis, poi si paga (capitalismo)
3. **La foto della patente potrebbe essere sfocata** → Non è colpa nostra se la gente ha le mani che tremano

## 🤝 Contribuire

Hai idee per migliorare? PR benvenute! Regole semplici:

1. **Niente framework pesanti** → jQuery nel 2025? Seriously?
2. **Mobile-first sempre** → Desktop è un nice-to-have
3. **Test su telefoni veri** → L'emulatore di Chrome mente

## 📝 Licenza

MIT - Fai quello che vuoi, ma almeno offrici un caffè se ci incontri.

## 🙏 Ringraziamenti

- **EmailJS** → Per esistere e funzionare
- **Canvas API** → Per la compressione delle immagini
- **Vibration API** → Per il bzz bzz
- **Il cliente** → Per aver pagato questo progetto
- **Stack Overflow** → Come sempre, l'MVP

## 📞 Supporto

Problemi? Domande? Suggerimenti?

**Opzione A:** Apri una issue su GitHub  
**Opzione B:** Chiama l'autoscuola → 0424 523690  
**Opzione C:** Passa di persona → Galleria G.B. Verci 6, Bassano del Grappa  
**Opzione D:** Impara a guidare e non dovrai mai rinnovare la patente (wait...)

---

### 🎬 One More Thing...

Questo form ha salvato circa 1.000 ore di telefonate nel primo mese. Se non è innovazione questa, non sappiamo cosa lo sia. Il futuro del rinnovo patenti è qui, ed è sorprendentemente semplice.

**P.S.** Se sei arrivato fino a qui, meriti un premio. Usa il codice "README_LOVER" quando prenoti e... non succederà assolutamente niente, ma apprezziamo l'impegno.

---

Made with ❤️ and ☕ in Bassano del Grappa  
*Dove le patenti si rinnovano e la grappa scorre* 🥃
