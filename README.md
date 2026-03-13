# Ft_printf

## 📌 Descrizione

**Ft_printf** è una reimplementazione della funzione `printf` della libreria standard C, sviluppata come parte del percorso formativo della scuola **42**.
Il progetto consiste nel creare una funzione in grado di gestire diversi formati di stampa, replicando il comportamento della funzione originale.

L'obiettivo è comprendere il funzionamento delle variadic functions e migliorare la gestione dell'output e della formattazione in C.

---

## 🎯 Obiettivi del progetto

* Reimplementare la funzione `printf`
* Gestire argomenti variabili con `va_list`
* Implementare diversi formati di conversione
* Scrivere codice modulare e riutilizzabile

---

## ⚙️ Linguaggio utilizzato

* C

---

## 🔧 Conversioni supportate

Il progetto gestisce le seguenti conversioni:

* `%c` carattere
* `%s` stringa
* `%p` puntatore
* `%d` intero decimale
* `%i` intero
* `%u` intero senza segno
* `%x` esadecimale minuscolo
* `%X` esadecimale maiuscolo
* `%%` simbolo percentuale

---

## 🛠️ Compilazione

Per compilare la libreria:

```bash
make
```

Per pulire i file oggetto:

```bash
make clean
```

Per pulire tutto:

```bash
make fclean
```

Per ricompilare:

```bash
make re
```

---

## 📚 Note

Questo progetto fa parte del percorso della scuola **42** e introduce l'uso delle funzioni variadiche e della gestione avanzata dell'output.

---

## 👤 Autore

mariaber - Marianna Bernardi
