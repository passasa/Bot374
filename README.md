# 🤖 Amazon Price Monitor Discord Bot

Surveille automatiquement les erreurs de prix sur Amazon et envoie des alertes sur Discord.

## 🚀 Déploiement Docker

### Prérequis
- Docker
- Docker Compose
- Un token Discord

### Étapes
1. Clonez le dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/amazon-price-monitor-bot.git
   cd amazon-price-monitor-bot
   ```

2. Créez un fichier `.env` :
   ```env
   DISCORD_TOKEN=ton_token_discord
   ```

3. Lancez le bot :
   ```bash
   docker-compose up --build -d
   ```

4. Sur Discord, utilisez `!set_channel` dans le canal souhaité pour recevoir les alertes.

## 📋 Commandes
- `!add_product <ASIN>` : Ajoute un produit
- `!remove_product <ASIN>` : Supprime un produit
- `!list_products` : Liste les produits
- `!check_now` : Vérifie immédiatement
- `!set_channel` : Définit le canal pour les alertes
