Diagramme d'états 

Ces diagrammes illustrent les différentes étapes et transitions possibles en fonction des actions des utilisateurs et des réponses du système.  

**1. Diagramme d’État : Connexion du Client**  

Ce diagramme décrit le processus de connexion d’un utilisateur à l’application. Deux scénarios sont possibles :  
1. **L’utilisateur n’a pas de compte** :  
   - Il doit passer par une phase d’enregistrement.  
   - Un code de vérification lui est envoyé.  
   - Si le code est correct, le compte est créé. Sinon, il doit recommencer l’opération.  

2. **L’utilisateur a déjà un compte** :  
   - Il entre ses identifiants pour se connecter.  
   - Après trois essais incorrects, l’accès est refusé.  
   - Si les identifiants sont corrects avant d’atteindre la limite d’essais, l’utilisateur est connecté.  

Ce diagramme met en évidence un processus sécurisé de connexion, avec la gestion des erreurs et des tentatives de connexion infructueuses. L’intégration d’une vérification par code renforce la sécurité du système.  

**2. Diagramme d’État : Gestionnaire**  

Ce diagramme représente les actions possibles pour un gestionnaire après sa connexion à l’application. Une fois authentifié, il accède à un tableau de bord où il peut :  
- **Gérer les disponibilités** (ajouter, modifier, afficher).  
- **Gérer les éléments** (ajouter, modifier, afficher).  
- **Gérer les avis des utilisateurs** (valider ou ignorer).  

Le diagramme illustre un système bien structuré permettant au gestionnaire d’interagir avec les différentes fonctionnalités de l’application. Il suit une logique fluide où chaque action aboutit à un état défini, garantissant un contrôle optimal des ressources et des avis utilisateurs.  


**3. Diagramme d’État : Paiement**  

Ce diagramme modélise le processus de paiement dans l’application :  
1. L’utilisateur fait une **demande de paiement** et choisit un mode de paiement :  
   - **Paiement en totalité**  
   - **Paiement en tranche**  
2. Le système vérifie le solde disponible :  
   - Si le solde est insuffisant, le paiement échoue.  
   - Si le solde est suffisant, le paiement est validé.  
3. Une fois validé, un **message de confirmation** est envoyé à l’utilisateur.  

Ce diagramme montre un processus simple et efficace pour la gestion des paiements, intégrant un contrôle des fonds avant validation. Il assure une gestion fluide des transactions, tout en traitant les cas d’échec.  


Ces trois diagrammes d’état offrent une vision détaillée du fonctionnement de l’application à différents niveaux :  
- **Connexion et sécurité des utilisateurs**  
- **Gestion des émements et des avis par un gestionnaire**  
- **Traitement des paiements avec validation**  

Chaque processus est bien défini, avec des transitions claires entre les différents états, garantissant une utilisation efficace et sécurisée de l’application.

IRAKOZE Olive Audrey et TOMBEZE Noah

