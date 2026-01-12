# Plateforme d'Apprentissage en Ligne

Une application web moderne pour l'apprentissage en ligne avec des fonctionnalités de suivi de progression, de quiz et de recommandations personnalisées.

## 🚀 Technologies Utilisées

### Frontend
- React avec TypeScript
- Vite comme bundler
- Tailwind CSS pour le styling
- React Query pour la gestion des données

### Backend
- FastAPI (Python)
- SQLAlchemy (ORM)
- JWT pour l'authentification
- Alembic pour les migrations de base de données

## 📦 Prérequis

- Node.js (v18+)
- Python (3.9+)
- pip (gestionnaire de paquets Python)
- npm ou yarn (gestionnaire de paquets Node.js)

## 🛠 Installation

### Backend

1. Créez et activez un environnement virtuel :
   ```bash
   python -m venv venv
   source venv/bin/activate  # Sur Windows: .\venv\Scripts\activate
   ```

2. Installez les dépendances :
   ```bash
   cd backend
   pip install -r requirements.txt
   ```

3. Configurez les variables d'environnement :
   Créez un fichier `.env` dans le dossier `backend` avec les variables nécessaires.

4. Exécutez les migrations :
   ```bash
   alembic upgrade head
   ```

5. Lancez le serveur :
   ```bash
   uvicorn main:app --reload
   ```

### Frontend

1. Installez les dépendances :
   ```bash
   cd frontend
   npm install
   ```

2. Lancez l'application en mode développement :
   ```bash
   npm run dev
   ```

## 🌐 Accès

- **Frontend** : http://localhost:5173
- **Backend (API)** : http://localhost:8000
- **Documentation de l'API** : http://localhost:8000/docs

## 📝 Fonctionnalités

- Authentification des utilisateurs
- Gestion des cours
- Quiz interactifs
- Suivi de la progression
- Recommandations personnalisées
- Tableau de bord analytique
- Interface utilisateur réactive

## 📂 Structure du Projet

```
.
├── backend/               # Code source du backend
│   ├── alembic/          # Migrations de base de données
│   ├── app/              # Code de l'application
│   ├── tests/            # Tests unitaires et d'intégration
│   ├── main.py           # Point d'entrée de l'API
│   └── requirements.txt  # Dépendances Python
│
└── frontend/             # Application React
    ├── public/           # Fichiers statiques
    └── src/              # Code source du frontend
        ├── components/   # Composants réutilisables
        ├── pages/        # Pages de l'application
        ├── services/     # Appels API
        └── utils/        # Utilitaires
```

## 🤝 Contribution

1. Forkez le projet
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/AmazingFeature`)
3. Committez vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Poussez vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

## 📄 Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 🙏 Remerciements

- [FastAPI](https://fastapi.tiangolo.com/)
- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- Et tous les autres projets open source utilisés
