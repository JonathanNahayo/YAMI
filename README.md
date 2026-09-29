<<<<<<< HEAD
# Yami Backend

Backend Node.js/TypeScript pour le site Yami — La Douce Énergie.

## Installation

```bash
npm install
cp .env.example .env
# Éditer .env avec vos configurations SMTP
```

## Développement

```bash
npm run dev    # Serveur avec hot-reload
npm run build  # Compilation TypeScript
npm start      # Production
```

## API Endpoints

- `POST /api/orders` - Créer une commande
- `GET /api/orders` - Lister les commandes
- `PATCH /api/orders/:id` - Modifier le statut d'une commande
- `POST /api/contact` - Envoyer un message de contact

## Variables d'environnement

- `PORT` - Port serveur (défaut: 3000)
- `SMTP_HOST` - Serveur SMTP
- `SMTP_PORT` - Port SMTP
- `SMTP_USER` - Utilisateur SMTP
- `SMTP_PASS` - Mot de passe SMTP
- `ADMIN_EMAIL` - Email admin pour notifications
- `MONGODB_URI` - URI MongoDB
=======
# yami-site
>>>>>>> 9c1d04c632e31cd6f6e23edc17cd84fb740716e9
