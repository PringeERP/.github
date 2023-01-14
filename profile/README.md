# Pringe
Pringe est un ERP (ou PGI) visant à aider les développeurs indépendants français à gérer leurs affaires et à générer leurs pièces commerciales afin qu'ils puissent se recentrer sur leur activité.

## Contenu
Il se présente sous forme de modules, incluant :
- Un module de comptabilité simplifié
- Un module de gestion des achats et des ventes, ainsi que les tiers liés
- Un module de gestion des  ressources humaines
- Un module de gestion de la production

### Comptabilité simplifiée
Le module de comptabilité permet la gestion interne de l'argent de l'entreprise.
> **Note :**  
> Aucun document officiel ne peut être généré depuis ce module.

Son unique but est d'aider à faire ses comptes, et ainsi aider à gérer l'entreprise en permettant de savoir où est son argent, et garder la trace des différentes opérations monétaires et financières réalisées ou prévues.

### Gestion des achats/ventes et des tiers liés
Parmi les tiers, on compte les clients, les fournisseurs et les prospects clients et fournisseurs. Ces tiers ont une influence sur la vie courante de l'entreprise en étant à l'origine de pièces commerciales.

Parmi les pièces commerciales gérées par Pringe, on dénombre les devis, les bons de commande, les bons de livraison ainsi que les factures. Ces pièces sont officielles et sont reconnaissables par l'État français. Par conséquent, elles ne doivent pas être falsifiées ou supprimées.
> **Note :**  
> Pringe ou ses éditeurs ne peuvent pas être tenus responsables si vous ne respectez pas les lois françaises.

### Gestion des ressources humaines
Ce module sert principalement à rentrer les temps réels passés sur une commande, afin de pouvoir comparer les prévisions à la réalité. Ses données sont également utilisées pour prévoir le temps médian nécessaire à l'accomplissement d'une tâche donnée, ainsi que l'avancement global d'un projet en particulier.

### Gestion de la production
Ce module prend en charge la définition de produits (les produits les plus classiques tels qu'un site web, une API RESTful, etc... sont déjà définis, mais peuvent être modifiés par l'utilisateur). Ces produits peuvent êtres réalisés à base de sous produits, ce qui aide le client à mieux comprendre ce que vous allez faire et comment son produit fonctionnera, ainsi que l'utilisateur à mieux gérer son temps et produire un résultat de meilleure qualité.
> **Note :**  
> Les changements sur des produits ne sont pas rétro-actifs. On ne peut pas modifier un contrat en cours sans un accord avec le client.

## Fonctionnement du logiciel
Pringe utilise le framework Symfony avec le langage PHP, ainsi que quelques scripts JavaScript pour la gestion du front.

Il est disponible dans une version locale pour un développeur seul, mais peut aussi être exporté pour être déployé sur un serveur (à l'initiative du/des développeur et sans surcoût) si son entreprise s'agrandit. Un guide d'installation pour toutes les différentes plateformes  est disponible [ici](#).
