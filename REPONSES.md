# Réponses — Évaluation POO : héritage, polymorphisme, transtypage

- Matricule : K2345
- Nom et prénom : Ndeye Khady Babou
- N (deux derniers chiffres du matricule) :45

> Rédigez vos justifications **avec vos propres mots**. Elles serviront de base à l'échange oral.

## Exercice 1 — A. Affichage prédit

Écrivez ci-dessous, entre les deux lignes de trois accents graves, **une ligne par ligne affichée**, dans l'ordre.
Ne modifiez pas les lignes de trois accents graves.

```text
A vehicule
F moto XXX
E moto XXX
MotoY
vehicule
moto
C3
C2
D-vehicule
true false
true
A vehicule
B vehicule
...(répété N % 3 fois)
Z


```

## Exercice 1 — A. Justifications

1. Ligne qui commence par « F » :Le constructeur de vehicule appelle demarrer()
2. Ligne « C3 » :comparer
3. Ligne « C2 » :comparer
4. Ligne qui commence par « D- » :categorie
5. Pourquoi des lignes « A », « F », « E » apparaissent avant « true false » :o.equals(v) utilise Objet.equals(meme reference)true.o == new Moto()crée un nouvel objet false

## Exercice 1 — B. Transtypage

Colonne « Compile ? » : `oui` ou `non`. Colonne « Exécution » : `OK`, `exception` (en précisant laquelle), ou `-` si le code ne compile pas.

| n° | Compile ? | Exécution | Justification |
|----|-----------|-----------|---------------|
| 1  |oui        |       ok  |moto_vehicule          |
| 2  |nom              _
| 3  |Oui        |      ok   | interdit            |
| 4  |Oui        |ClassCast  | a pointe moto           |
| 5  |oui        |ClassCast    b pointe camion             | 
| 6  |oui        |ClassCast  | c moto              |
| 7  |non        | _         | camion n'est pas string              |
| 8  |oui               ok     cast vers vehicules          |
