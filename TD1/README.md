# TD1 — Pharmacies de garde

## 1. Présentation du projet

Ce projet consiste à créer une application mobile avec Flutter permettant d'afficher une liste de pharmacies et d'identifier celles qui sont de garde.

L'application utilise des données fictives.

## 2. Structure des données

La classe `Pharmacie` possède quatre attributs :

- `nom` : nom de la pharmacie.
- `commune` : commune de la pharmacie.
- `telephone` : numéro de téléphone.
- `deGarde` : indique si la pharmacie est de garde.

Une liste appelée `pharmacies` contient cinq pharmacies fictives.

## 3. Fonctionnalités

- Afficher les cinq pharmacies.
- Afficher le nom, la commune et le téléphone.
- Identifier les pharmacies de garde avec une icône.
- Filtrer les pharmacies de garde avec un bouton Switch.
- Actualiser le compteur selon le filtre sélectionné.

## 4. Interface utilisateur

Les principaux widgets Flutter utilisés sont :

- `MaterialApp`
- `Scaffold`
- `AppBar`
- `Column` et `Row`
- `Card` et `ListTile`
- `ListView.builder`
- `Switch`

## 5. Gestion du filtre

La variable `_gardeSeulement` mémorise l'état du filtre.

Lorsque le filtre est activé, seules les pharmacies dont `deGarde` vaut `true` sont affichées.

La méthode `setState()` actualise l'interface lorsque l'utilisateur modifie le filtre.

## 6. Technologies utilisées

- Langage : Dart
- Framework : Flutter
- Interface : Material Design 3

## 7. Exécution du projet

Depuis le dossier `hello_ispa`, exécuter :

```bash
flutter pub get
flutter run
```
## 8. Conclusion

Ce travail pratique permet de découvrir les bases de Flutter : création d'une classe de données, affichage d'une liste et gestion d'un état interactif avec `StatefulWidget` et `setState()`.

