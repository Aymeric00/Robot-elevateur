# Robot Élévateur

## Description
Ce projet consiste en la conception et la réalisation d'un robot élévateur capable de trier des déchets en fonction de leur magnétisme. Le robot est construit à partir de composants LEGO et utilise un processeur conçu sur Logisim. Ce projet a été réalisé dans le cadre du cours de systèmes logiques à l'HEPIA.

## Auteurs
- [Aymeric Gros](https://github.com/Aymeric00)
- Maxence Besombes(https://github.com/Kamaxxx)

## Objectif du projet
L'objectif principal est de développer un robot élévateur capable de :
- Identifier la magnétisation des objets à l'aide d'un capteur à effet Hall.
- Déplacer les objets vers des zones spécifiques en fonction de leur magnétisme.
- Gérer deux types de déplacements : avec la fourche en position haute (avec objet) et basse (sans objet).

## Fonctionnalités
- Conception d'un processeur 8 bits de type RISC avec l'architecture Von Neumann.
- Utilisation de périphériques UART pour la communication avec les capteurs de distance.
- Utilisation du protocole SPI pour la communication avec le capteur à effet Hall.
- Contrôle des moteurs (dont un moteur LEGO pour la fourche) via des signaux PWM.
- Gestion de la mémoire (RAM et ROM) pour le stockage des instructions et des données.

## Architecture
Le projet comprend les éléments suivants :
- **Processeur 8 bits** : Capable d'exécuter des instructions arithmétiques, logiques et de contrôle.
- **Capteur à effet Hall** : Utilisé pour détecter les objets magnétiques.
- **Moteur élévateur LEGO** : Contrôle la position de la fourche.
- **Périphériques UART** : Interfacent les capteurs de distance et l'odomètre.

## Instructions Principales du Processeur
- **ALU** : Exécute les opérations telles que ADD, SUB, LSL, LSR, AND, OR, NOT.
- **Mémoire** : Supporte les opérations de lecture (Load) et d'écriture (Store).
- **Contrôle** : Instructions de saut et de contrôle, y compris MOVC et JMP.

## Vidéos
Le projet est accompagné de trois vidéos démonstratives :
1. **Robot en mouvement et prise d'objet** : Le robot détecte et soulève un objet.
2. **Détection de matériau magnétique** : Le robot identifie si l'objet est magnétique.
3. **Affichage de l'odomètre** : Le robot affiche la distance parcourue via des LEDs.

## Conclusion
Ce projet nous a permis de combiner nos connaissances théoriques sur les systèmes logiques avec une application pratique. Nous avons conçu un processeur capable de contrôler un robot élévateur fonctionnel, capable de trier des objets en fonction de leur magnétisme.

## Remerciements
Nous tenons à remercier :
- Mathias Rullo
- Kirill Goundiaev
- Laurent Gantel

Votre soutien a été essentiel à la réussite de ce projet.

## Annexes
- Documentation du capteur à effet Hall PMODISNS20 : [Lien](#lien-capteur)
- Documentation du moteur LEGO : [Lien](#lien-moteur)

