# Analysis-of-Algorithms-and-Data-Structures

Progetto didattico per il corso Analysis of Algorithms and Data Structures (AADS) basato sull'analisi dei Skew Dyck Paths.


# 📘 Progetto AADS – Analisi dei *Skew Dyck Paths*

### Autori:

- **Magrini Roberto** – roberto.magrini@stud.unifi.it  
- **Serena Vannacci** – serena.vannacci@stud.unifi.it

### Corso:

Analysis of Algorithms and Data Structures – a.a. 2022/2023

---

## 🎯 Obiettivo

Il progetto ha lo scopo di esplorare i **percorsi Skew Dyck** attraverso l'analisi simbolica e algebrica delle funzioni generatrici, sulla base dei risultati presentati nell'articolo accademico:

> *"Skew Dyck Paths Having no Peaks at Level 1" – Helmut Prodinger, Stellenbosch University*

L'obiettivo è **riprodurre e verificare i risultati matematici** dell’articolo tramite **calcolo simbolico**, con particolare attenzione all'uso del **Kernel Method** e delle **funzioni generatrici bivariate**.

---

## 🧠 Contenuti Principali

### 📌 Introduzione teorica
- Definizione di **Skew Dyck Paths** come generalizzazione dei Dyck Paths.
- Presentazione grafica dei passi consentiti nel piano cartesiano:
  - `(1, 1)` → salita diagonale destra
  - `(1, -1)` → discesa diagonale destra
  - `(-1, -1)` → discesa diagonale sinistra *(caratteristica distintiva)*

### 🔬 Kernel Method
- Studio ricorsivo delle successioni \( f_j, g_j, h_j \) relative ai livelli dei cammini.
- Derivazione delle **funzioni generatrici**:
  \[
  F(z,u), \quad G(z,u), \quad H(z,u)
  \]
- Risoluzione simbolica e verifica dei risultati espressi tramite radici quadrate e coefficienti polinomiali.

---

## 🛠️ Strumenti Utilizzati

| Strumento | Descrizione |
|----------|-------------|
| `Python` | Linguaggio di programmazione |
| `Jupyter Notebook` | Ambiente interattivo per la documentazione e l’esecuzione |
| `SymPy` | Libreria per algebra simbolica |
| `LaTeX (Markdown)` | Per la scrittura di formule matematiche leggibili |

---

## 🗂️ Struttura del Codice

- **Import dei moduli**: `sympy`, `abc`, inizializzazione del pretty printing
- **Definizione simbolica**: \( z, u, r_1, r_2, g_0, F(u), G(u), H(u) \)
- **Verifica algebrica**: uso di `Eq`, `solve`, `expand` e `simplify` per dimostrare le uguaglianze e identità
- **Visualizzazione** delle formule e dei passaggi di calcolo simbolico

---

## 🧪 Esecuzione

### Prerequisiti
- Python ≥ 3.7
- `sympy`
- Jupyter Notebook

### Esecuzione (locale)
```bash
pip install sympy notebook
jupyter notebook ProgettoAADS_MagriniVannacci.ipynb
````

---

## 📈 Competenze Acquisite

* Comprensione di **tecniche di analisi combinatoriale**
* Uso di **funzioni generatrici** e metodi simbolici
* Manipolazione e risoluzione di **equazioni ricorsive**
* Approfondimento di tecniche di **kernel method**
* Esperienza con **algebra simbolica computazionale**

---

## 📄 Riferimenti

* H. Prodinger, *Skew Dyck Paths Having no Peaks at Level 1*, Stellenbosch University
* Documentazione [SymPy](https://docs.sympy.org)
* Dispense del corso AADS – UniFi

---
