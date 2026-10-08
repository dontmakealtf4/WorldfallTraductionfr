# 🇫🇷 Worldfall : Traduction française pour WorldBox

**Bienvenue sur le projet de traduction française de Worldfall !**

Ce dépôt propose une traduction française complète du catalogue de textes du mod **Worldfall**, développé pour le jeu **WorldBox : God Simulator**.

L'objectif est simple : permettre à la communauté francophone de profiter pleinement de l'expérience Worldfall, sans la barrière de la langue !

> ⚠️ **Projet communautaire non officiel** : cette traduction est réalisée de manière indépendante. Je ne suis ni affilié aux développeurs de Worldfall, ni membre de l'équipe de développement du mod.

---

## 🌍 Présentation

Worldfall enrichit considérablement l'expérience de WorldBox en proposant notamment une exploration du monde à la première personne, des interactions avec les habitants, des quêtes et de nombreuses mécaniques de gameplay.

Malheureusement, le mod ne propose pas officiellement de traduction française parmi ses langues intégrées.

C'est pourquoi ce projet a vu le jour !

### ✨ Que contient cette traduction ?

La traduction française couvre **4 149 entrées de texte**, comprenant notamment :

- 🎮 Les menus, paramètres et interfaces
- 💬 Les dialogues et interactions avec les personnages
- 📜 Les quêtes, missions et objectifs
- ⚔️ Les combats, capacités et pouvoirs
- 👑 La diplomatie, les royaumes et la gestion militaire
- ❤️ Les relations, familles et interactions sociales
- 🎒 L'inventaire, les objets et l'artisanat
- 🏘️ Les villes, bâtiments et activités
- 🔔 Les notifications et messages du jeu

**L'intégralité des entrées présentes dans le catalogue de traduction utilisé a été traduite.**

Certaines expressions peuvent néanmoins nécessiter des ajustements, et de nouveaux textes pourraient apparaître lors de futures mises à jour du mod.

---

## 📥 Installation de la traduction

L'installation est simple et ne nécessite **aucune connaissance en programmation** !

### Étape 1 : Installer Worldfall

Assurez-vous d'avoir installé le mod Worldfall et de l'avoir lancé au moins une fois.

Cette traduction nécessite le mod original pour fonctionner.

### Étape 2 : Télécharger la traduction

Téléchargez l'archive `WorldFall_TraductionFR.rar`, puis extrayez le.

### Étape 3 : Placer le fichier au bon endroit

1. Fermez complètement WorldBox.
2. Appuyez sur `Windows + R`.
3. Copiez et collez le chemin suivant :

`%USERPROFILE%\AppData\LocalLow\mkarpenko\WorldBox\FirstPerson\lang`

4. Appuyez sur Entrée pour ouvrir le dossier.
5. Placez le fichier `fr.txt` directement dans ce dossier.

Votre installation doit ressembler à ceci :

📁 **FirstPerson**

　├── 📁 lang

　│　　├── 📁 shipped

　│　　└── 🇫🇷 fr.txt ✅

　├── 📄 settings.txt

　└── 📄 FirstPerson.log

**⚠️ Attention :** ne placez pas `fr.txt` dans le sous-dossier `shipped` et ne remplacez pas les fichiers des autres langues.

---

## ⚙️ Étape 4 : Activer le français dans settings.txt

**Cette étape est importante pour que la traduction fonctionne correctement !**

Par défaut, Worldfall peut conserver l'anglais même lorsque WorldBox est configuré en français.

Pour forcer l'utilisation de notre traduction :

1. Retournez dans le dossier `FirstPerson`, situé juste au-dessus du dossier `lang`.
2. Repérez le fichier `settings.txt`.
3. Ouvrez-le avec le Bloc-notes Windows.
4. Cherchez le paramètre `language=`.
5. Remplacez sa valeur par :

`language=fr`

6. Enregistrez le fichier avec `Ctrl + S`.
7. Relancez WorldBox.

🎉 **Félicitations ! Worldfall devrait désormais afficher ses textes en français !**

**Remarque :** il est normal que le menu des langues de Worldfall ne propose pas de bouton « Français ». La sélection manuelle dans `settings.txt` permet de charger notre fichier de traduction.

Évitez de changer la langue dans le menu F2 après cette manipulation, car cela pourrait écraser votre réglage.

---

## 🔧 Problèmes fréquents

### Le mod est toujours en anglais

Vérifiez les points suivants :

- Le fichier se nomme exactement `fr.txt` et non `fr.txt.txt`.
- Le fichier se trouve bien dans `FirstPerson\lang`.
- Il n'est pas placé dans `FirstPerson\lang\shipped`.
- Le fichier `settings.txt` contient `language=fr`.
- Vous avez bien enregistré les modifications avant de relancer le jeu.

### Toujours aucun changement ?

Worldfall dispose d'un fichier de journal qui peut aider à identifier le problème :

`FirstPerson\FirstPerson.log`

Ouvrez-le avec le Bloc-notes et recherchez une ligne commençant par :

`lang: fr (Français)`

Si cette ligne indique `0 lines from the mod`, cela signifie qu'aucune entrée de traduction du mod n'a été chargée.

Dans ce cas, vérifiez à nouveau l'emplacement et le contenu du fichier `fr.txt`.

Si le problème persiste, n'hésitez pas à ouvrir une **Issue** sur ce dépôt GitHub ou de me contacter sur discord : **elmathos2702**

---

## 📌 Compatibilité et mises à jour

Cette traduction a été préparée à partir du catalogue de textes d'une version de Worldfall.

Les futures mises à jour du mod peuvent introduire de nouvelles fonctionnalités et de nouveaux textes qui ne seront pas immédiatement traduits.

Si vous découvrez une phrase encore en anglais, une faute d'orthographe ou une traduction étrange, vous pouvez ouvrir une Issue en précisant le texte concerné, idéalement accompagné d'une capture d'écran ou de me contacter sur discord : **elmathos2702**

Vos retours aideront à améliorer la qualité de la traduction !

---

## ❤️ Remerciements

Un grand merci aux développeurs de **Worldfall** pour leur travail et pour toutes les fonctionnalités apportées à WorldBox.

Merci également à la communauté de WorldBox et à toutes les personnes qui testeront cette traduction et contribueront à son amélioration.

Ce projet a été réalisé par passion pour le jeu et dans le but de rendre Worldfall plus accessible aux joueurs francophones.

---

## ⚖️ Avertissement

Ce dépôt est un projet de traduction communautaire indépendant.

- Il ne s'agit pas d'une traduction officielle.
- Les droits du mod Worldfall restent la propriété de leurs détenteurs respectifs.
- Le mod original est indispensable pour utiliser cette traduction.
- Aucun fichier exécutable ou DLL du mod original n'est nécessairement distribué avec cette traduction.
- Si vous voulez me contacter sur discord : **elmathos2702**

---

**🇫🇷 Bon jeu à toutes et à tous, et profitez de Worldfall en français ! ⚔️🌍**
