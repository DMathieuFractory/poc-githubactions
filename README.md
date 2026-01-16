🧪 Projet de test GitHub Actions

Ce dépôt a pour objectif de tester, expérimenter et comprendre le fonctionnement de GitHub Actions à travers différents workflows (CI, lint, tests, build, etc.).

Il sert de bac à sable pour :
	•	Découvrir la syntaxe YAML des workflows
	•	Tester des actions existantes
	•	Créer et maintenir ses propres workflows
	•	Comprendre les triggers et les jobs

⸻

🎯 Objectifs
	•	✔️ Tester les déclencheurs (push, pull_request, workflow_dispatch, etc.)
	•	✔️ Mettre en place une pipeline CI simple
	•	✔️ Tester des matrices (versions de Node, PHP, etc.)
	•	✔️ Vérifier le cache des dépendances
	•	✔️ Observer les logs et statuts d’exécution

⸻

📁 Structure du projet

.
├── .github/
│   └── workflows/
│       └── ci.yml
├── README.md
└── (autres fichiers de test)

Les workflows GitHub Actions sont définis dans le dossier :

.github/workflows/

⸻

📌 Notes
	•	Ce projet est volontairement simple
	•	Les workflows peuvent évoluer et être cassés volontairement pour test
	•	Le dépôt n’est pas destiné à la production

⸻

📄 Licence

Projet libre d’expérimentation.