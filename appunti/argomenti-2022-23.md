# Argomenti di esame (a.a. 2022-23)

## 1 Linguaggio modale e semantica

### 1.1 Linguaggio

- def. 1.1: $\mathcal{L}^\Phi$, alfabeto del linguaggio modale enunciativo
  (pag. 1);
- def. 1.2: $Fm^\Phi$$, insieme delle formule ben formate di $\mathcal{L}^\Phi$
  (pag. 1);
- def. 1.3: simboli logici ausiliari (pag. 2);
- def.: $lg(A)$, lunghezza della formula $A$ (pag. 2);
- def.: $Sf(A)$, insieme delle sottoformule di $A$ (pag. 2);
- def.: $A[D/p]$, sostituzione uniforme di $D$ al posto di $p$ in una fbf $A$
  (pag. 2).

### 1.2 Semantica per $L^\Phi$

- 1.2.1 Strutture relazionali
  - def. 1.4: $\mathcal{F}$, struttura relazionale (pag. 3).
- 1.2.2 Modelli
  - def.: $\mathcal{M}$, ($\mathcal{F}$-)modello (pag. 4).
- 1.2.3 Verità e validità
  - def. 1.5: $\mathcal{M} \models_w A$, $A$ è vera in un mondo $w$ di
    $\mathcal{M}$ (pag. 4);
  - def. 1.6: $\mathcal{M} \models A$, $A$ è vera in un modello $\mathcal{M}$
    (pag. 4);
  - def. 1.7: $\mathcal{F} \models A$, $A$ è valida su una struttura $\mathcal{F}$
    (pag. 4);
  - def. 1.8: $\models A$, $A$ è valida (pag. 5);
  - def. 1.9: $\mathcal{C} \models A$, $A$ è valida su una classe di strutture
    $\mathcal{C}$ (pag. 5);
  - def. 1.10: $\Gamma \models_{\mathcal{C}} A$, $A$ è conseguenza semantica di
    $\Gamma$ rispetto a una classe di strutture $\mathcal{C}$ (pag. 5);
  - def.: schema (pag. 5).

### 1.3 Schemi validi e non validi

- th.: validità delle tautologie classiche e di K (pag. 6).

### 1.4 Regole che conservano la validità

- th.: MP conserva la verità in un punto di un modello (pag. 7);
- th.: N conserva la verità in un modello (pag. 7);
- th.: SU conserva la validità su una struttura (pag. 8).

### 1.5 Cos'è una logica modale normale?

- def.: logica modale normale (pag. 9).

### 1.6 Chiusura riflessiva e transitiva

- def. 1.11: $\Box^n$ ($\Diamond^n$), applicare $\Box$ ($\Diamond$) $n$ volte
  (pag. 10);
- def. 1.12: $\mathcal{R}^n$, poter accedere tramite $\mathcal{R}$ in
  esattamente $n$ passi (pag.10);
- def. 1.13: $\mathcal{R}*$, chiusura riflessiva e transitiva di $\mathcal{R}$
  (pag. 10);
- lem. 1.14: sia $S$ una relazione riflessiva e transitiva tale che
  $\mathcal{R} \subset S$. Allora $\mathcal{R}* \subset S$ (pag. 10);
- oss. 1: il lemma 1.14 ci dice che $\mathcal{R}*$ è la più piccola relazione riflessiva e
  transitiva che estende $\mathcal{R}$;
- lem. 1.15: $\Box^n$ ($\Diamond^n$) e $\mathcal{R}^n$ (pag. 11).

## 2 Corrispondenza e non esprimibilità

- def. 2.1: $A$ corrisponde a $\mathcal{P}$ (pag. 13).

### 2.1 Risultati di corrispondenza

- th. 2.2: T corrisponde alla riflessività (pag. 15);
- th. 2.3: 4 corrisponde alla transitività (pag. 15);
- th. 2.4: D corrisponde alla serialità (pag. 15);
- th. 2.6: B corrisponde alla simmetria (pag. 16);
- th. 2.7: 5 corrisponde alla proprietà euclidea (pag. 16);
- th. 2.8: 2 corrisponde alla convergenza debole (pag. 16);
- th. 2.14: mnkj-Lemmon corrisponde alla proprietà mnkj-Lemmon (pag. 18).

### 2.2 Proprietà non esprimibili

- 2.2.1 Sottomodelli generati
  - def. 2.15: sottomodello generato (pag. 19);
  - lem. 2.16: sottomodello generato $\mathcal{M^v} \models_{\mathcal{z}} A$ sse $\mathcal{M} \models_{\mathcal{z}}A$ (pag. 19).
- 2.2.2 P-morfismi
  - def. 2.17: p-morfismo tra strutture (pag. 20);
  - def. 2.18: p-morfismo tra modelli (pag. 20);
  - lem. 2.19: p-morfismo fra modelli $\mathcal{M_1} \models_{\mathcal{w}} A$ sse $\mathcal{M_2} \models_{\mathcal{f(w)}}A$ (pag. 21);
  - def. 2.20: p-morfismo suriettivo (pag. 21);
  - def. 2.21: immagine p-morfa (pag. 21);
  - lem. 2.22: p-morfismo suriettivo fra modelli $\mathcal{M_1} \models A$ sse $\mathcal{M_2} \models A$ (pag. 21);
  - lem. 2.23: p-morfismo tra strutture implica p-morfismo fra modelli (p. 22);
  - lem. 2.24: p-morfismo suriettivo fra strutture (p. 22).
- 2.2.3 Proprietà non esprimibili
  - th. 2.25: la convergenza non è esprimibile (p. 23);
  - th. 2.26: la connessione non è esprimibile (p. 23);
  - th. 2.27: l'irriflessività non è esprimibile (p. 23);
  - th. 2.28: l'antisimmetria non è esprimibile (p. 23).

## 3 Logiche modali normali

### 3.1 La logica K

- def.: $K$, logica modale normale minimale (pag. 25);
- def.: $L$, logica modale normale (pag. 25);
- def. 3.1: dimostrazione in $L$, profondità, teorema (pag. 25).

### 3.2 Alcune estensioni di K

- fig.: cubo delle logiche modali normali (pag. 31).

### 3.3 Validità

- def.: $\mathcal{F} \models L$, $\mathcal{F}$ è una struttura per $L$ (pag.33);
- def.: $\mathcal{C}^L$, classe delle strutture per $L$ (pag. 33);
- def.: $\mathcal{C} \subset \mathcal{C}^L$, $L$ è valida rispetto a
  $\mathcal{C}$ (pag. 33);
- th. 3.8: validità di $K$ (senza dimostrazione) (pag. 34).

### 3.4 Modalità

- def. 3.11: modalità (pag. 35).

## 9 Sequenti etichettati

### 9.1 Nozioni introduttive

- def. 9.1: linguaggio etichettato (pag. 104)
- def. 9.2: sequente (pag. 105)
- def. 9.3: derivazione $\Gamma \Longrightarrow \Delta$ (pag. 105)

### 9.2 Il calcolo G3.K

- tab. 9.1: regole logiche e sequenti iniziali (pag. 106)

### 9.3 Alcune estensioni di G3.K

- G3.T, G3.K4, G3.B, G3.K5 (pag. 108-109)
- G3.D, G3.K2 (pag. 109,110)

### 9.4 Elementi basi di metateoria

- def. 9.4: contesti, formule principali e formule principali (pag. 112)
- def. 9.5: lunghezza. profondità, n-derivabilità, ammissibilità e pp-ammissibilità (pag. 112)
- lem. 9.6: $G3.L \vdash w:A ,\Gamma \Longrightarrow \Delta , w:A$ (pag.112)
- def. 9.7: sostituzione etichette (pag.112)
- lem. 9.8: ammissibilità regola sostituzione etichette (pag. 113)

### 9.5 Validità e completezza

- 9.5.1 Validità

  - def. 9.9: $\mathcal{M}$-realizzazione, verità di una formula, sequente verificato da $\mathcal{M}$-realizzazione, sequente $L$-valido (pag. 114)
  - th. 9.10: validità ($G3.L \vdash \Gamma \Longrightarrow \Delta$  $implica$  $\mathcal{C^L} \models \Gamma \Longrightarrow \Delta$) (pag. 114)
  
- 9.5.2 Completezza
 
  - def. 9.11: ramo $L$-saturo (pag. 117)
  - def. 9.12: costruzione $L$-albero (pag. 118)
  - def. 9.13: modello da un ramo $L$-saturo (pag. 119)
  - lem. 9.14: chiamato in classe truth lemma (pag. 119)
  - th. 9.15: completezza ($\mathcal{C^L} \models \Gamma \Longrightarrow \Delta$ $implica$ $G3.L \vdash \Gamma \Longrightarrow \Delta$) (pag. 120)
  
### 9.6 Proprietà strutturali

- lem. 9.16: pp-ammissibilità di $LW$ e $RW$ (pag. 121)
- cor. 9.17: ammissibilità necessitazione in $G3.L$ (pag. 122)
- lem. 9.18: pp-invertibilità di tutte le regole di $G3.L$ (pag. 122)
- th. 9.19: pp-ammissibilità di $LC_R$, $LC$ e $RC$ (pag. 123)
- th. 9.20: ammissibilità regola cesura/taglio/cut (pag. 124)

### 9.7 Decidibilità

- def. 9.23: derivazione minimale (pag. 127)
- prop. 9.24: etichette di una derivazione minimale (pag. 127)
- lem. 9.25: permutazione delle regole (pag. 128)
- cor. 9.26: $L\Box$ in una derivazione minimale (pag. 129)

### 9.8 Identità e proprietà inesprimibili

- 9.8.1 Identità
- 9.8.2 Proprietà inesprimibili
