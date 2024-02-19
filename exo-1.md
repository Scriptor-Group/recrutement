## Système de Gestion de Tâches Collaboratif avec Temps Réel et GraphQL

### Objectif:
Développer une application web de gestion de tâches collaboratif qui permet aux utilisateurs de créer, assigner, suivre, et mettre à jour des tâches en temps réel. L'application doit utiliser React pour le frontend, Node.js pour le backend, et intégrer GraphQL pour la communication entre les deux, utilisant idéalement Prisma pour la gestion base de données (PGSQL).

### Fonctionnalités Clés:

#### 1. **Authentification Utilisateur**
- Inscription, connexion, et déconnexion.
- Utiliser GraphQL pour les requêtes d'authentification.

#### 2. **Gestion des Tâches**
- Créer, visualiser, modifier, et supprimer des tâches via une interface utilisateur.
- Chaque tâche doit inclure: titre, description, priorité, date d'échéance, et statut (ex: À faire, En cours, Terminé).
- Implémenter des abonnements GraphQL pour les mises à jour en temps réel des tâches.

#### 3. **Assignation des Tâches**
- Assigner des tâches à des utilisateurs et afficher les tâches assignées à un utilisateur spécifique.
- Utiliser les abonnements GraphQL pour notifier les utilisateurs des nouvelles tâches assignées en temps réel.

#### 4. **Filtrage et Recherche**
- Filtrer les tâches par statut, priorité, et date d'échéance.
- Rechercher des tâches par mots-clés.
- Implémenter ces fonctionnalités à l'aide de requêtes GraphQL.

#### 5. **Interface Utilisateur**
- Développer une interface utilisateur réactive et intuitive avec React, en utilisant des composants fonctionnels et Hooks.
- Intégrer des notifications en temps réel pour les mises à jour des tâches.

#### 6. **API Backend et GraphQL**
- Construire une API RESTful avec Node.js pour gérer l'authentification et la logique métier.
- Utiliser GraphQL pour la communication entre le frontend et le backend, y compris les requêtes, mutations, et abonnements.

#### 7. **Sécurité**
- Mettre en œuvre des pratiques de sécurité, comme le hachage des mots de passe et la protection contre les attaques XSS et CSRF.
- Sécuriser les requêtes GraphQL et les abonnements.

### Critères d'Évaluation:
- **Qualité du Code:** Propreté, utilisation des bonnes pratiques, modularité.
- **Fonctionnalité:** Conformité aux fonctionnalités demandées, fonctionnement sans bugs.
- **Design et UX/UI:** Esthétique de l'interface, expérience utilisateur fluide.
- **Sécurité:** Implémentation des pratiques de sécurité.
- **Documentation:** Documentation claire du code, instructions d'installation et d'exécution.

### Livrables:
- Code source de l'application (frontend et backend).
- Documentation incluant: instructions d'installation, de configuration, et d'utilisation; description de l'architecture; et guide d'utilisation de l'API GraphQL.
- Une démo vidéo de l'application en fonctionnement, montrant les fonctionnalités en temps réel.

### Délai:
Réalisation complète de cet exercice dans un délai de 1 à 2 semaines.

