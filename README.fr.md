# Blue Team Labs

🇬🇧 [English](./README.md) | 🇫🇷 [Français](./README.fr.md)

Un espace de pratique et de documentation consacré à la **sécurité défensive** : comprendre les menaces, détecter les comportements suspects, protéger les systèmes et valider les mesures de défense.

## À propos

Ce dépôt rassemble des rooms (labs pratiques) réalisées dans des environnements isolés et autorisés. Il constitue un portfolio évolutif de travaux Blue Team, avec une approche Purple Team pour relier les techniques d'attaque aux capacités de défense.

Chaque room traite un scénario précis et présente son contexte, sa démarche, ses preuves et ses conclusions. Selon le sujet, elle peut porter sur l'analyse de journaux, la détection, le durcissement ou la réponse à incident : la reproduction d'une attaque n'est pas un prérequis systématique.

## Objectifs

- **Observer et analyser** les événements système et réseau pour identifier les activités suspectes.
- **Détecter et comprendre** les techniques d'attaque et leurs traces.
- **Protéger et durcir** les services, les configurations et les mécanismes d'accès.
- **Réagir et valider** les mesures de confinement, de remédiation et de prévention.
- **Documenter** les résultats avec des preuves et des recommandations exploitables.

## Rooms disponibles

| Room | Description | Outils |
|---|---|---|
| [SSH Brute Force & Durcissement](./ssh-hardening/RAPPORT.md) | Analyse d'une attaque par brute force SSH, durcissement du serveur et validation des protections | Nmap, Hydra, Fail2ban, OpenSSH |

Cette liste sera enrichie au fil des travaux. Seules les rooms déjà disponibles y figurent.

## Organisation et démarche

Chaque room possède son propre dossier. Selon le scénario, il contient un rapport Markdown, une version PDF, des captures d'écran et les fichiers utiles à la compréhension du lab.

La démarche générale : **définir le périmètre → observer et analyser → mettre en place les défenses → tester leur efficacité → documenter les résultats et les limites**.

## Mention légale et éthique

Ces travaux sont réalisés à des fins éducatives dans des environnements isolés, sur des systèmes appartenant à l'auteur ou explicitement autorisés. N'appliquez aucune technique à un système tiers sans autorisation écrite préalable. L'auteur décline toute responsabilité en cas d'usage détourné de ces informations.
