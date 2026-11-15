# calcul-c

Petit programme en C qui demande deux nombres à l'utilisateur et affiche leur somme.
Réalisé dans le cadre du TP Git (ENSA Khouribga) pour pratiquer le versionnement local puis la publication sur GitHub.

---

## Execution

```
Hello class
------------------------------------------------------------------
|       programe pour calculer la sommation - soustraction:      |
------------------------------------------------------------------
| Entrer respectivement les deux valeurs de a et b :4 3.5
|                   La somme est        : 7.50                   |
|----------------------------------------------------------------|
```

## Prérequis

- Un compilateur C, par exemple [GCC](https://gcc.gnu.org/) (MinGW sous Windows)
- [Git](https://git-scm.com/) pour récupérer le projet

Pour vérifier que GCC est bien installé :

```bash
gcc --version
```

## Compilation et exécution


```bash
# 1. Récupérer le projet
git clone https://github.com/youssef0600/calcul-c.git
cd calcul-c

# 2. Compiler
gcc main.c -o main

# 3. Lancer
./main
```

Sous Windows (CMD ou PowerShell), l'exécutable s'appelle `main.exe` :

```
main.exe
```

## Utilisation

Une fois le programme lancé, saisir les deux valeurs séparées par un espace, puis valider avec Entrée :

```
4 3.5
```

Le résultat est affiché avec deux décimales.

## Structure du projet

```
calcul-c/

├── main.c        # code source du programme
├── .gitignore    # exclut l'exécutable et les fichiers objets
└── README.md     # ce fichier
```

L'exécutable (`main`, `main.exe`) et les fichiers objets (`*.o`) ne sont volontairement pas suivis par Git : ils se régénèrent à chaque compilation.

## Historique du projet

| Étape | Description                                       |
|-------|---------------------------------------------------|
| 1     | Initialisation du projet C (message de bienvenue) |
| 2     | Ajout du calcul de la somme de deux nombres       |
| 3     | Ajout du `.gitignore` et du `README.md`           |

## Auteur

**Youssef Bouyzourn**
Étudiant à l'ENSA Khouribga, cycle IID
GitHub : [@youssef0600](https://github.com/youssef0600)
