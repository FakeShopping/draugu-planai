# Draugų planai

Bendras draugų savaitės kalendorius: žymi planus ar laisvą laiką, prisijungi prie draugų veiklų, gali turėti privačių planų.

Veikia su GitHub Pages (puslapis) ir Firebase (prisijungimas su Google ir duomenys). Abu nemokami.

## Failai

- `index.html` – pats kalendorius. Jo viršuje reikia įklijuoti Firebase konfigūraciją.
- `firestore.rules` – saugumo taisyklės ir draugų sąrašas. Jas reikia nukopijuoti į Firebase.

## Kaip pridėti naują draugą

1. Firebase konsolėje atidaryk **Firestore Database → Rules**.
2. Į sąrašą `isFriend()` pridėk draugo Gmail adresą.
3. Spausk **Publish**.
4. Nusiųsk draugui nuorodą į puslapį.
