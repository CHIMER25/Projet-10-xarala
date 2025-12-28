1. Architecture Docker
L'application est conteneurisée pour garantir la parité entre les environnements.
Dockerfile pour l'optimisation.
docker-compose.yml


2. Configuration du Serveur & Sécurité
Avant tout déploiement, sécurise .

3. Reverse Proxy (Nginx)

4. Workflow CI/CD (GitHub Actions)
L'automatisation est gérée via .github/workflows/deploy.yml. À chaque push sur la branche main :
Tests : Exécution des tests unitaires.
Build : Création de l'image Docker.
Deploy : Connexion SSH au VPS, docker pull
