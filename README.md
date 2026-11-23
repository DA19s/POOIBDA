# POOIBDA – TP .NET : POO, classes et interfaces

École Supérieure Polytechnique (ESP) – Département Génie Informatique – Année universitaire 2026/2027

Solution `POOIBDA.sln` contenant un projet par lien du TP :

| Projet | Exercice | Notions |
|---|---|---|
| `P1CreateClasses` | Créer des classes | classes, objets, constructeurs, champs `readonly` et `static`, constructeur statique |
| `P2UpdateClasses` | Mettre à jour les classes | propriétés (`get`/`set`, auto-implémentées, lecture seule), méthodes, méthodes d'extension |
| `P3ImplementClasses` | Gérer les implémentations des classes | classe partielle, classe statique, paramètres optionnels et nommés, constructeur de copie, initialiseur d'objet |
| `P4ImplementInterfaces` | Implémenter des interfaces | interface `IPerson`, classes `Student` et `Teacher`, polymorphisme |

## Exécution

Prérequis : SDK .NET 10 ou plus récent.

```bash
dotnet build POOIBDA.sln
dotnet run --project P1CreateClasses
dotnet run --project P2UpdateClasses
dotnet run --project P3ImplementClasses
dotnet run --project P4ImplementInterfaces
```

Les sorties obtenues lors des tests sont dans [`RESULTATS_TESTS.txt`](RESULTATS_TESTS.txt).

## Remarques

- Les projets P2 et P3 partent du code de démarrage fourni (`LP1SampleApps.zip`, dossiers `Classes_M2/Starter` et `Classes_M3/Starter`). P1 et P4 n'ont pas de code de démarrage.
- Le code de démarrage ciblait `net9.0` ; les projets ciblent `net10.0`.
- Les identifiants clients et numéros de compte partent d'une valeur aléatoire : ils changent à chaque exécution.
- Dans P3, les montants sont formatés avec `CultureInfo.CurrentCulture` : le symbole monétaire dépend de la langue de Windows (ici F CFA).
