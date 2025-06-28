# ici Comence mon apprentissage en python 

##  Bases de Python

# Tableau des Types de Base en Python

| Type       | Exemple de déclaration         | Description                                |
| ---------- | ------------------------------ | ------------------------------------------ |
| `int`      | `age = 25`                     | Nombre entier, positif ou négatif.         |
| `float`    | `pi = 3.14`                    | Nombre décimal (virgule flottante).        |
| `str`      | `nom = "Alice"`                | Chaîne de caractères (texte).              |
| `bool`     | `est_ok = True`                | Booléen : `True` ou `False`.               |
| `list`     | `notes = [12, 14, 18]`         | Liste ordonnée et modifiable.              |
| `tuple`    | `coord = (10, 20)`             | Liste ordonnée **immuable**.               |
| `dict`     | `personne = {"nom": "Bob"}`    | Dictionnaire (clé/valeur).                 |
| `set`      | `couleurs = {"rouge", "vert"}` | Ensemble non ordonné **sans doublons**.    |
| `NoneType` | `resultat = None`              | Valeur spéciale indiquant "aucune valeur". |
| `complex`  | `z = 2 + 3j`                   | Nombre complexe (rarement utilisé).        |

---

## Pourquoi on n'écrit pas les types en Python ?

Python est un langage **à typage dynamique et implicite**. Cela signifie que :

* Tu **n'as pas besoin** de déclarer le type des variables.
* Python **déduit automatiquement** le type en fonction de la valeur que tu assignes.

### Exemple :

```python
age = 30        # Python comprend que c'est un int
prix = 12.5     # Python comprend que c'est un float
nom = "Alice"   # Python comprend que c'est une str
est_membre = True  # Python comprend que c'est un bool
```

###  Avantages

* Moins de code à écrire
* Plus lisible
* Flexible pour prototyper rapidement

---

## Les Opérateurs en Python

Voici les principaux opérateurs que tu utiliseras souvent en Python, avec leur signification et des exemples.

---

## 🔢 Opérateurs arithmétiques

| Opérateur | Nom              | Exemple   | Résultat |
| --------- | ---------------- | --------- | -------- |
| `+`       | Addition         | `3 + 2`   | `5`      |
| `-`       | Soustraction     | `5 - 2`   | `3`      |
| `*`       | Multiplication   | `4 * 3`   | `12`     |
| `/`       | Division         | `10 / 2`  | `5.0`    |
| `//`      | Division entière | `10 // 3` | `3`      |
| `%`       | Modulo (reste)   | `10 % 3`  | `1`      |
| `**`      | Puissance        | `2 ** 3`  | `8`      |

---

## Opérateurs de comparaison

| Opérateur | Signification       | Exemple  | Résultat |
| --------- | ------------------- | -------- | -------- |
| `==`      | Égal à              | `5 == 5` | `True`   |
| `!=`      | Différent de        | `4 != 4` | `False`  |
| `>`       | Supérieur à         | `7 > 3`  | `True`   |
| `<`       | Inférieur à         | `9 < 8`  | `False`  |
| `>=`      | Supérieur ou égal à | `5 >= 5` | `True`   |
| `<=`      | Inférieur ou égal à | `7 <= 6` | `False`  |

---

## 🔗 Opérateurs logiques

| Opérateur | Nom logique | Exemple           | Résultat |
| --------- | ----------- | ----------------- | -------- |
| `and`     | ET logique  | `5 > 2 and 3 < 4` | `True`   |
| `or`      | OU logique  | `5 > 2 or 3 > 4`  | `True`   |
| `not`     | NON logique | `not True`        | `False`  |

---








