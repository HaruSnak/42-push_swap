<img src="readme/push_swap.png" alt="push_swap" width="900"/>

<div align="center">

# Push Swap
### A Sorting Algorithm Implementation Using Stacks

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![License][license-shield]][license-url]

</div>

---

## 🇬🇧 English

<details>
<summary><b>📖 Click to expand/collapse English version</b></summary>

### 📖 About

**Push Swap** is a compulsory project for 42 School students. It consists of implementing a sorting algorithm using two stacks and a limited set of operations, aiming to sort the stack with the minimum number of moves.

This project teaches:
- Stack data structure manipulation
- Sorting algorithm design and optimization
- Command-line argument parsing
- Error handling and input validation
- Algorithm efficiency and benchmarking
- Code organization and modular programming

### 🧠 Skills Learned

By completing the Push Swap project, students develop essential skills in C programming:

- **Stack operations**: Mastering push, swap, rotate, and reverse rotate operations on stacks.
- **Sorting algorithms**: Designing efficient sorting strategies for stacks with limited operations.
- **Input parsing**: Handling command-line arguments, converting strings to integers, and validating inputs.
- **Error management**: Implementing robust error checking for invalid inputs, duplicates, and integer overflows.
- **Algorithm optimization**: Minimizing the number of operations to achieve sorting, with benchmarks for 100 and 500 numbers.
- **Memory management**: Using dynamic memory allocation for stacks and ensuring no memory leaks.
- **Code efficiency**: Writing performant code that meets strict operation limits.
- **Bonus: Checker program**: Creating a program to verify the correctness of the sorting instructions.
- **Project structure**: Organizing code into logical modules, adhering to 42 norms for documentation and style.
- **Makefile usage**: Creating efficient Makefiles for compilation, cleaning, and rebuilding.

### 📋 Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Compilation](#compilation)
- [Operations](#operations)
- [Benchmark](#benchmark)
- [Credits](#credits)

<a name="features"></a>

### ✨ Features

- **Complete sorting implementation** using two stacks and limited operations
- **Strict C89/C99 compliance** with 42 School norming standards
- **Bonus checker program** to validate sorting instructions
- **Fully documented** with clear purpose statements
- **Optimized algorithms** meeting benchmark requirements

<a name="installation"></a>

### 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/HaruSnak/Push_Swap.git
cd Push_Swap
```

<a name="usage"></a>

### 💻 Usage

Compile the program:

```bash
make
```

Run the program with a list of integers:

```bash
./push_swap 4 67 3 87 23
```

The program will output the sequence of operations to sort the stack.

For the bonus checker:

```bash
make bonus
./checker 4 67 3 87 23
```

Then input the operations from push_swap.

<a name="project-structure"></a>

### 📂 Project Structure

```
Push_Swap/
├── Makefile                      # Main Makefile
├── includes/
│   ├── push_swap.h               # Main header file
│   └── libft/                    # Libft library
│       ├── Makefile
│       ├── includes/libft.h
│       └── ... (libft source files)
├── srcs/
│   ├── push_swap.c               # Main program
│   ├── parsing.c                 # Argument parsing
│   ├── ranking.c                 # Ranking functions
│   ├── split.c                   # Splitting utilities
│   ├── case_errors.c             # Error handling
│   ├── algo_sorting.c            # Sorting algorithms
│   ├── algo_sorting_extract.c
│   ├── algo_sorting_iteration.c
│   ├── algo_sorting_pre.c
│   ├── algo_sorting_three.c
│   ├── algo_sortingmore.c
│   ├── algo_utils.c              # Algorithm utilities
│   ├── commands/
│   │   ├── commands.c            # Stack operations
│   │   └── commands2.c
│   └── bonus/
│       ├── checker.c             # Bonus checker program
│       └── checker
├── numbers.py                    # Python script for testing
├── LICENSE                       # License file
├── README.md                     # This file
└── readme/                       # Assets folder
    └── push_swap.png
```

<a name="compilation"></a>

### 🔧 Compilation

Compile the mandatory part:

```bash
make
```

Compile the bonus:

```bash
make bonus
```

Clean object files:

```bash
make clean
```

Clean all:

```bash
make fclean
```

Recompile:

```bash
make re
```

<a name="operations"></a>

### 📚 Operations

The program uses the following operations:

- **pa**: Push from B to A
- **pb**: Push from A to B
- **sa**: Swap first two elements of A
- **sb**: Swap first two elements of B
- **ss**: Swap A and B simultaneously
- **ra**: Rotate A upwards
- **rb**: Rotate B upwards
- **rr**: Rotate A and B upwards
- **rra**: Reverse rotate A
- **rrb**: Reverse rotate B
- **rrr**: Reverse rotate A and B

<a name="benchmark"></a>

### 📊 Benchmark

To validate the project:

- **100 numbers**: Less than 700 operations (for 100% score)
- **500 numbers**: Less than 5500 operations (for 100% score)

Alternative thresholds for minimum validation (80% score):
- 100 numbers < 1100, 500 numbers < 8500
- 100 numbers < 700, 500 numbers < 11500
- 100 numbers < 1300, 500 numbers < 5500

### 👨‍🎓 Note
<p align="left">
    <img src="https://image.noelshack.com/fichiers/2024/29/4/1721314123-sans-titre.png"
         alt="94/100" width="216" height="164">
</p>

<a name="credits"></a>

### 📖 Credits

- **42 School Norm**: [Official C Coding Standard](https://cdn.intra.42.fr/pdf/pdf/960/norme.en.pdf)
- [Mechanical Turk](https://en.wikipedia.org/wiki/Amazon_Mechanical_Turk)
- [Fred Orion | Similar method | inspiration](https://www.youtube.com/watch?v=2aMrmWOgLvU)

### 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

</details>

---

## 🇫🇷 Français

<details>
<summary><b>📖 Cliquez pour développer/réduire la version française</b></summary>

### 📖 À propos

**Push Swap** est un projet obligatoire pour les étudiants de l'école 42. Il s'agit d'implémenter un algorithme de tri utilisant deux piles et un ensemble limité d'opérations, visant à trier la pile avec le nombre minimum de mouvements.

Ce projet enseigne :
- La manipulation de structures de données de type pile
- La conception et l'optimisation d'algorithmes de tri
- L'analyse des arguments de ligne de commande
- La gestion d'erreurs et la validation des entrées
- L'efficacité des algorithmes et les benchmarks
- L'organisation du code et la programmation modulaire

### 🧠 Compétences acquises

En complétant le projet Push Swap, les étudiants développent des compétences essentielles en programmation C :

- **Opérations sur les piles** : Maîtriser les opérations push, swap, rotate et reverse rotate sur les piles.
- **Algorithmes de tri** : Concevoir des stratégies de tri efficaces pour les piles avec des opérations limitées.
- **Analyse des entrées** : Gérer les arguments de ligne de commande, convertir les chaînes en entiers et valider les entrées.
- **Gestion d'erreurs** : Implémenter une vérification d'erreurs robuste pour les entrées invalides, les doublons et les débordements d'entiers.
- **Optimisation d'algorithmes** : Minimiser le nombre d'opérations pour atteindre le tri, avec des benchmarks pour 100 et 500 nombres.
- **Gestion de la mémoire** : Utiliser l'allocation dynamique de mémoire pour les piles et assurer l'absence de fuites.
- **Efficacité du code** : Écrire du code performant qui respecte des limites strictes d'opérations.
- **Bonus : Programme de vérification** : Créer un programme pour vérifier la correction des instructions de tri.
- **Structure du projet** : Organiser le code en modules logiques, en respectant les normes 42 pour la documentation et le style.
- **Utilisation de Makefile** : Créer des Makefiles efficaces pour la compilation, le nettoyage et la reconstruction.

### 📋 Table des matières

- [Caractéristiques](#caractéristiques)
- [Installation](#installation-1)
- [Utilisation](#utilisation)
- [Structure du projet](#structure-du-projet)
- [Compilation](#compilation-1)
- [Opérations](#opérations)
- [Benchmark](#benchmark-1)
- [Crédits](#crédits-1)

<a name="caractéristiques"></a>

### ✨ Caractéristiques

- **Implémentation complète de tri** utilisant deux piles et des opérations limitées
- **Conformité stricte C89/C99** avec les normes de l'école 42
- **Programme de vérification bonus** pour valider les instructions de tri
- **Entièrement documentées** avec des descriptions claires
- **Algorithmes optimisés** répondant aux exigences de benchmark

<a name="installation-1"></a>

### 🚀 Installation

```bash
# Cloner le dépôt
git clone https://github.com/HaruSnak/Push_Swap.git
cd Push_Swap
```

<a name="utilisation"></a>

### 💻 Utilisation

Compilez le programme :

```bash
make
```

Exécutez le programme avec une liste d'entiers :

```bash
./push_swap 4 67 3 87 23
```

Le programme affichera la séquence d'opérations pour trier la pile.

Pour le vérificateur bonus :

```bash
make bonus
./checker 4 67 3 87 23
```

Puis entrez les opérations depuis push_swap.

<a name="structure-du-projet"></a>

### 📂 Structure du projet

```
Push_Swap/
├── Makefile                      # Makefile principal
├── includes/
│   ├── push_swap.h               # Fichier d'en-tête principal
│   └── libft/                    # Bibliothèque Libft
│       ├── Makefile
│       ├── includes/libft.h
│       └── ... (fichiers source libft)
├── srcs/
│   ├── push_swap.c               # Programme principal
│   ├── parsing.c                 # Analyse des arguments
│   ├── ranking.c                 # Fonctions de classement
│   ├── split.c                   # Utilitaires de division
│   ├── case_errors.c             # Gestion d'erreurs
│   ├── algo_sorting.c            # Algorithmes de tri
│   ├── algo_sorting_extract.c
│   ├── algo_sorting_iteration.c
│   ├── algo_sorting_pre.c
│   ├── algo_sorting_three.c
│   ├── algo_sortingmore.c
│   ├── algo_utils.c              # Utilitaires d'algorithmes
│   ├── commands/
│   │   ├── commands.c            # Opérations sur les piles
│   │   └── commands2.c
│   └── bonus/
│       ├── checker.c             # Programme de vérification bonus
│       └── checker
├── numbers.py                    # Script Python pour les tests
├── LICENSE                       # License file
├── README.md                     # Ce fichier
└── readme/                       # Dossier des ressources
    └── push_swap.png
```

<a name="compilation-1"></a>

### 🔧 Compilation

Compilez la partie obligatoire :

```bash
make
```

Compilez le bonus :

```bash
make bonus
```

Nettoyez les fichiers objets :

```bash
make clean
```

Nettoyez tout :

```bash
make fclean
```

Recompilez :

```bash
make re
```

<a name="opérations"></a>

### 📚 Opérations

Le programme utilise les opérations suivantes :

- **pa** : Pousser de B vers A
- **pb** : Pousser de A vers B
- **sa** : Échanger les deux premiers éléments de A
- **sb** : Échanger les deux premiers éléments de B
- **ss** : Échanger A et B simultanément
- **ra** : Rotation de A vers le haut
- **rb** : Rotation de B vers le haut
- **rr** : Rotation de A et B vers le haut
- **rra** : Rotation inverse de A
- **rrb** : Rotation inverse de B
- **rrr** : Rotation inverse de A et B

<a name="benchmark-1"></a>

### 📊 Benchmark

Pour valider le projet :

- **100 nombres** : Moins de 700 opérations (pour 100% de score)
- **500 nombres** : Moins de 5500 opérations (pour 100% de score)

Seuils alternatifs pour validation minimale (80% de score) :
- 100 nombres < 1100, 500 nombres < 8500
- 100 nombres < 700, 500 nombres < 11500
- 100 nombres < 1300, 500 nombres < 5500

### 👨‍🎓 Note
<p align="left">
    <img src="https://image.noelshack.com/fichiers/2024/29/4/1721314123-sans-titre.png"
         alt="94/100" width="216" height="164">
</p>

<a name="crédits-1"></a>

### 📖 Crédits

- **Norme 42** : [Standard C officiel](https://cdn.intra.42.fr/pdf/pdf/960/norme.en.pdf)
- [Mechanical Turk](https://en.wikipedia.org/wiki/Amazon_Mechanical_Turk)
- [Fred Orion | Méthode similaire | inspiration](https://www.youtube.com/watch?v=2aMrmWOgLvU)

### 📄 Licence

Ce projet est sous licence **MIT** - voir le fichier [LICENSE](LICENSE) pour plus de détails.

</details>

---

[contributors-shield]: https://img.shields.io/github/contributors/HaruSnak/Push_Swap.svg?style=for-the-badge
[contributors-url]: https://github.com/HaruSnak/Push_Swap/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/HaruSnak/Push_Swap.svg?style=for-the-badge
[forks-url]: https://github.com/HaruSnak/Push_Swap/network/members
[stars-shield]: https://img.shields.io/github/stars/HaruSnak/Push_Swap.svg?style=for-the-badge
[stars-url]: https://github.com/HaruSnak/Push_Swap/stargazers
[issues-shield]: https://img.shields.io/github/issues/HaruSnak/Push_Swap.svg?style=for-the-badge
[issues-url]: https://github.com/HaruSnak/Push_Swap/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/shany-moreno-5a863b2aa
[license-shield]: https://img.shields.io/github/license/HaruSnak/Push_Swap.svg?style=for-the-badge
[license-url]: https://github.com/HaruSnak/Push_Swap/blob/master/LICENSE
