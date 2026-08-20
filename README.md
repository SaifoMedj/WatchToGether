# WatchToGether

Application web permettant de regarder des videos ensemble dans des salles partagees.
Le projet propose la synchronisation video, le chat en temps reel et la gestion des utilisateurs.

## Fonctionnalites

- Creation et gestion de salles
- Synchronisation de la lecture video
- Chat temps reel
- Authentification des utilisateurs
- Gestion des roles et permissions dans les salles

## Structure du projet

- `project/backend/` : API Node.js, authentification, salles et WebSockets
- `project/frontend/` : interface React et lecteur video
- `project/docs/` : documentation technique

## Technologies

- React
- Node.js et Express
- Socket.IO
- SQLite
- Vite

## Installation

1. Clonez le depot :

	```bash
	git clone https://github.com/SaifoMedj/WatchToGether.git
	cd WatchToGether/project
	```

2. Installez les dependances du backend :

	```bash
	cd backend
	npm install
	```

3. Installez les dependances du frontend :

	```bash
	cd ../frontend
	npm install
	```

## Demarrage

Lancez le backend et le frontend dans deux terminaux distincts :

```bash
cd project/backend
npm run dev
```

```bash
cd project/frontend
npm run dev
```

## Documentation

- [Documentation du projet](project/README.md)
- [Regie video](project/docs/regie-video.md)

## Contribution

Les contributions sont les bienvenues. Creez une branche, effectuez vos modifications, puis ouvrez une pull request.
